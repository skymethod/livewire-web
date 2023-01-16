---
title: "A Tale of Two Bytes: Prefix vs Host-based analytics"
description: "Why your podcast download stats from 3rd-party analytics providers might differ from your hosting company's stats."
slug: "a-tale-of-two-bytes-prefix-vs-host-based-analytics"
date: 2023-01-15T18:32:00-06:00
draft: false
---
Why your podcast download stats from third-party analytics providers might differ from your hosting company's stats.

---
### Downloads {#downloads}

"Downloads" are currently the industry-standard for measuring a podcast's audience, they are visible evidence on the server-side (can be observed by your hosting company and any analytics prefixes you've configured) without the need for any coordination or special APIs from every podcast player app.

Of course, many podcast apps _auto-download_ episodes ahead of time, so a Download does not necessarily mean someone actually started playing the episode, or indeed played very much of it - but it's the best metric we currently have.

_[Learn more about podcast stats at Podnews →](https://podnews.net/article/understanding-podcast-statistics)_

Over time, podcast hosting companies and advertising standards entities such as the [IAB](https://en.wikipedia.org/wiki/Interactive_Advertising_Bureau) have developed [best practices](https://iabtechlab.com/wp-content/uploads/2021/03/PodcastMeasurement_v2.1.pdf) about turning raw server logs into unique listener requests, so that there is a standard baseline across the various players in the industry.

Third-party analytics providers like Podtrac & Chartable ([see our full list](/podcast-trackers-by-episode-share/)) go through the same certification processes as hosting companies like Libsyn ([see our full list](/podcast-hosts-by-episode-share/)), but they often show somewhat different numbers to the podcaster for the same show.

How can this be? Aren't they seeing the same underlying episode media file download and running it through the same calculations?

Let's get some of the reasons for these discrepancies out in the open!

---
### Source of discrepancy: Implementation

The certifications themselves are high-level best practices, so any certified hosting or third-party analytics implementation can differ on:
* IP address ranges to ignore or treat differently
* How to define a "day" (midnight to midnight @ timezone vs a rolling 24 hr window) - duplicate downloads for the same file in the same "day" from the same user are ignored
* How to define automated traffic / "bots" - bot traffic is ignored

All of which result in 7-day or 30-day download numbers reported to podcasters that can vary from host to host.

The story is even more complicated for prefixes, based fundamentally on the way they function.

---
### Source of discrepancy: Prefix limitations that over-report

Third-party prefixes will always have different data to work with than the hosting companies based on where they sit in the request sequence.

These prefixes work by putting themselves _before_ the actual media file destination (hence "prefix") in the episode media file url, thus getting a chance
to observe the same download as the hosting company, in theory.

When a podcast app downloads (or auto-downloads) an episode, it fetches the enclosure url which is now controlled by the prefix, and receives no episode media, but a small response that says: _"Actually, the media is at another location."_

Most prefixes use an [HTTP 302 response code](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/302), a "temporary" redirect - which tells the podcast app: 
_"Even though I told you the media is somewhere else, ask me again if you want to redownload in the future - I might tell you somewhere else to go."_

The prefix is out of the loop at this point in the sequence.  The podcast app creates a separate followup connection to the destination url and fetches the episode media file (or another redirect from another prefix) from there.
* If the listener's connection dies at this point, the prefix won't know
* If the destination is slow to load, and the listener cancels the request at this point, the prefix won't know
* If the destination url is invalid, or the destination hosting company or [CDN](/podcast-cdns-by-episode-share/) are temporarily down, the prefix won't know
* Only the final destination server will know exactly how many bytes were sent back to the app

Since these are rare cases overall (most requests succeed), in general this results in reported download numbers from prefixes being slightly _higher_ than reported numbers from hosting companies.

These limitations are well-known, so many prefix analytics services will slice a predefined percentage off of their reported numbers to compensate.  None of this is an exact science.

---
### Source of discrepancy: Prefix limitations that under-report {#first-two-bytes}

It turns out there is also at least one fairly significant case where prefixes can _under-report_ legitimate user downloads as well!

_👉 Thanks to Jason over at [Transistor](https://transistor.fm) for bringing this issue to our attention - as it helps make [OP3](https://op3.dev) (an open source podcast prefix analytics service) as accurate as possible in this regard._

The issue is [Range requests](https://developer.mozilla.org/en-US/docs/Web/HTTP/Range_requests) - podcast apps that ask for a _part_ of the media file, specifically _the first two bytes_.

The IAB (and Podsights' [oDL](https://github.com/open-downloads/odl#spec)) say to ignore these requests when calculating downloads, however...

___
### Should prefixes ignore requests for the first two bytes?
Apple's CoreMedia framework is used by almost every podcast app and browser on Apple platforms for making streaming playback requests (e.g. when auto-downloading is turned off in Apple Podcasts). It is the engine underneath [AVPlayer](https://developer.apple.com/documentation/avfoundation/avplayer)/[AVURLAsset](https://developer.apple.com/documentation/avfoundation/avurlasset), the default media player framework on iOS.

AVURLAsset is a high-level framework, taking the episode url as input, and making all of the underlying HTTP calls on the app's behalf - responsible for fetching pieces of the file on-demand, according to the current device posture (data connection, battery life, data caps, etc).

When making a request for a given episode, AppleCoreMedia makes two or more HTTP calls: first with a Range header of bytes=0-1, asking for the first two bytes of the file to verify the server supports range requests (these days, most do). It then follows up with one or more HTTP requests for various byte ranges of the file, based on internal heuristics.

👉 The problem for analytics prefixes is that the first bytes=0-1 request is sometimes _the only request the prefix will see_. That is, AppleCoreMedia sends the subsequent range requests directly to the redirect destination url, bypassing the prefix completely!

_This can be easily reproduced using a client HTTP proxy like [Charles](https://www.charlesproxy.com/)._

___
### No, they shouldn't
So analytics prefixes can't ignore these bytes=0-1 requests or they would miss legitimate user-initiated downloads, and _under-report_ stats compared to podcast hosting companies (who can see all requests).

> _The HTTP spec is somewhat ambiguous about this redirect+range situation, [saying](https://httpwg.org/specs/rfc9110.html#status.302) "the client ought to continue to use the target URI (original url) for future requests", but one can see how a client might decide to make immediate followup calls to the destination, say as part of a single user-initiated play request._

OP3 started tagging net-new downloads that are the result of letting these requests through, and they represent 6-7% of total non-bot downloads.

This seems reasonable, given that on-demand requests are relatively rare (most podcasts are auto-downloaded ahead of time), and AppleCoreMedia only seems to bypass the prefix completely on subsequent requests in a subset of these cases (usually when the device is on a fast connection).

These net-new requests are sent almost exclusively from Apple platforms (based on User-Agent), consistent with our rationale.

___
### Any downsides to letting them through?

Another problem would be if apps routinely sent requests for the first two bytes with no followup range requests.  Letting these requests through would then greatly _over-report_ actual downloads.  Working with Transistor (who are able to see both redirect and destination requests), we were able to confirm that in the wild, across _all_ Transistor shows, this is in fact extremely rare.  At around 0.22% of downloads, consistent with network failure noise.

These requests have little danger of inflating downloads since duplicates from the same agent + IP + download url in the same day are already ignored, so **we recommend removing this rule from best practices for analytics prefixes going forward**.

---

Writeup by [John Spurlock](https://twitter.com/johnspurlock)

Thanks again to the Jason at [Transistor](https://transistor.fm) for bringing the [range-request issue]({{< ref "#first-two-bytes" >}}) to our attention!

---

*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/a-tale-of-two-bytes.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
