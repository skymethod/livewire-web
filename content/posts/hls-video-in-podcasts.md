---
title: "HLS video in podcasts, who's doing what?"
description: "Keeping an eye on every HLS video in the podcast system"
slug: "hls-video-in-podcasts"
images:
- hls-video-in-podcasts.png
date: 2026-03-11T11:47:00-04:00
lastmod: 2026-03-29T11:34:00-04:00
draft: false
---

Apple Podcasts recently announced they will be [supporting HLS video](https://www.apple.com/newsroom/2026/02/apple-introduces-a-new-video-podcast-experience-on-apple-podcasts/), bringing a high-quality video option to their app for shows that want to do video episodes, including the ability to
seamlessly switch between video and audio-only during playback.

It is now officially launched in Apple Podcasts for iOS 26.4 - phones, tables, web only, no support in the Apple Podcasts for macOS or tvOS yet.

Publishers can make the same high-quality video experience available in _all_ podcast apps simply by adding the same [HLS multivariant playlist](https://docs.aws.amazon.com/mediatailor/latest/ug/hls-playlist-types.html) url to the [`podcast:alternateEnclosure`](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/tags/alternate-enclosure.md) tag at the episode-level in their existing audio podcast RSS feed.

{{% subscribe %}}

---

HLS is a rich format with an almost endless variety of optional features and configurations, so "HLS video" doesn't really tell the whole story.

I'll be keeping an eye out for HLS video in Apple Podcasts and in RSS feeds. Let's take a look at what hosting companies are actually doing with their HLS video in podcasts so far, and how they are doing it.

Since this analysis looks at the actual media files, it excludes hosting companies that have announced future support but have no actual HLS video episodes to show yet in either RSS or Apple Podcasts.

So far I've found at least 78 shows with HLS video support (1070 HLS video episodes) in Apple Podcasts.

{{< contact "Let me know" >}} if you find one not already on this list.

{{% funding %}}

---

# Acast

- Supports HLS video in Apple Podcasts: yes ✔︎
- Supports HLS video in RSS feeds: not yet

I've found at least 52 shows (894 video episodes) hosted by Acast using the new HLS video integration in Apple Podcasts, and used the latest episode from each show as the basis for the analysis below.

They use [HLS version 7](https://alexzambelli.com/blog/2016/05/04/understanding-hls-versions-and-client-compatibility/) and include one common audio track (English) using the [AAC](https://en.wikipedia.org/wiki/Advanced_Audio_Coding) format, at an average declared bitrate of ~140kbps (max declared peak of 157kbps).

Acast don't provide HLS subtitles.

Video resolutions:
  - 1080p in most shows (all but two), 30fps, AVC/H.264 High Profile (aka HD) / Level 4.1, average declared bitrate ranging from 1,015kbps to 5,297kbps (max declared peak ranging from 1,723kbps to 6,403kbps)
  - 720p in all shows, 30fps, AVC/H.264 High Profile (aka HD) / Level 3.1, average declared bitrate ranging from 626kbps to 3,062kbps (max declared peak ranging from 802kbps to 3,524kbps)
  - 480p in all shows, 30fps, AVC/H.264 High Profile (aka HD) / Level 3.1, average declared bitrate ranging from 393kbps to 1,596kbps (max declared peak ranging from 544kbps to 1,921kbps)
  - 360p in all shows, 30fps, AVC/H.264 Main Profile (aka SD) / Level 3, average declared bitrate ranging from 362kbps to 999kbps (max declared peak ranging from 443kbps to 1,171kbps)
  - 240p in all shows, 30fps, AVC/H.264 Main Profile (aka SD) / Level 3, average declared bitrate ranging from 367kbps to 577kbps (max declared peak ranging from 419kbps to 700kbps)

HLS thumbnails, used for scrubbing and hovering in players, are provided in 240p.

The audio is served from AWS using a single .ts file, using byte ranges to delineate 6-second chunks. Same for video and thumbnails.

Up to four ad slots are defined: pre-roll, 2 mid-rolls, and post-roll using [HLS intersitials](https://ubik-ingenierie.com/blog/understanding-hls-interstitials-and-ext-x-discontinuity-in-ad-insertion/). Ads are served from the same infrastructure.

Example show: [Mind If We Talk?](https://podcasts.apple.com/us/podcast/mind-if-we-talk/id1811677507) ([RSS feed](https://feeds.acast.com/public/shows/681285089704d99f847a77e1))

---

# ART19

- Supports HLS video in Apple Podcasts: yes ✔︎
- Supports HLS video in RSS feeds: not yet

I've found at least 10 shows (136 video episodes) hosted by ART19 using the new HLS video integration in Apple Podcasts, and used the latest episode from each show as the basis for the analysis below.

They use [HLS version 7](https://alexzambelli.com/blog/2016/05/04/understanding-hls-versions-and-client-compatibility/) and include one common audio track (English) using the [AAC](https://en.wikipedia.org/wiki/Advanced_Audio_Coding) format, at an average declared bitrate of 128kbps (max declared peak of 129kbps).

ART19 provided HLS subtitles on some shows (2 of 5).

Video resolutions:
  - 1080p in all shows, 23.976fps, AVC/H.264 Main Profile (aka SD) / Level 4 & 4.2, average declared bitrate ranging from 5,276kbps to 5,564kbps (max declared peak ranging from 6,262kbps to 6,661kbps)
  - 720p in all shows, 23.976fps, AVC/H.264 Main Profile (aka SD) / Level 4, average declared bitrate ranging from 2,936kbps to 3,129kbps (max declared peak ranging from 3,458kbps to 3,799kbps)
  - 480p in all shows, 23.976fps, AVC/H.264 Main Profile (aka SD) / Level 4, average declared bitrate ranging from 1,540kbps to 1,631kbps (max declared peak ranging from 1,842kbps to 1,943kbps)
  - 360p in all shows, 23.976fps, AVC/H.264 Main Profile (aka SD) / Level 3.1, average declared bitrate ranging from 937kbps to 995kbps (max declared peak ranging from 1,114kbps to 1,186kbps)
  - 240p in all shows, 23.976fps, AVC/H.264 Main Profile (aka SD) / Level 3.2, average declared bitrate ranging from 557kbps to 580kbps (max declared peak ranging from 650kbps to 668kbps)

HLS thumbnails, used for scrubbing and hovering in players, are provided in 480p.

The audio is served from AWS using separate 6-second .aac files. The video and thumbnails are served using single .ts files, using byte ranges to delineate 6-second chunks.

No ad slots were found on any shows.

Example show: [Baby, this is Keke Palmer](https://podcasts.apple.com/us/podcast/baby-this-is-keke-palmer/id1668446854) ([RSS feed](https://rss.art19.com/baby-this-is-keke-palmer))

---

# Omny Studio

- Supports HLS video in Apple Podcasts: yes ✔︎
- Supports HLS video in RSS feeds: not yet

I've found at least 5 shows (11 video episodes) hosted by Omny using the new HLS video integration in Apple Podcasts, and used the latest episode from each show as the basis for the analysis below.

They use [HLS version 8](https://alexzambelli.com/blog/2016/05/04/understanding-hls-versions-and-client-compatibility/) and include one common audio track (English) using the [AAC](https://en.wikipedia.org/wiki/Advanced_Audio_Coding) format, at an average declared bitrate of 128kbps (max declared peak of 128kbps).

No HLS subtitles were provided.

Video resolutions:
  - 720p in all shows, 30fps, AVC/H.264 High Profile (aka HD) / Level 4, average declared bitrate ranging from 2,798kbps to 2,802kbps (max declared peak ranging from 3,804kbps to 3,853kbps)

No HLS thumbnails for scrubbing and hovering in players.

The audio is served from AWS using separate 6-second .m4s (fMP4) files. Same for video.

Up to five ad slots are defined: pre-roll, and 4 mid-rolls using [HLS intersitials](https://ubik-ingenierie.com/blog/understanding-hls-interstitials-and-ext-x-discontinuity-in-ad-insertion/). Ads are served from the same infrastructure (iheart and triton in the hostname).
Also the first interstitial definition I've come across using `EXT-X-DATERANGE CUE=PRE`

Example show: [Las Culturistas with Matt Rogers and Bowen Yang](https://podcasts.apple.com/us/podcast/las-culturistas-with-matt-rogers-and-bowen-yang/id1092361338) ([RSS feed](https://omnycontent.com/d/playlist/e73c998e-6e60-432f-8610-ae210140c5b1/F6816727-C503-47AC-A7AC-AE2700391B1E/935C500F-8BB0-436B-BA7F-AE2700391B49/podcast.rss))

---

# Podigee

- Supports HLS video in Apple Podcasts: yes ✔︎
- Supports HLS video in RSS feeds: not yet

I've found at least 2 shows (5 video episodes) hosted by Podigee using the new HLS video integration in Apple Podcasts, and used one episode as the basis for the analysis below.

They use [HLS version 7](https://alexzambelli.com/blog/2016/05/04/understanding-hls-versions-and-client-compatibility/) and include one common audio track (German) using the [AAC](https://en.wikipedia.org/wiki/Advanced_Audio_Coding) format, at an average declared bitrate of 128kbps (max declared peak of 128kbps).

No HLS subtitles were provided.

Video resolutions:
  - 1080p, 25fps, AVC/H.264 High Profile (aka HD) / Level 4, average declared bitrate 4,913kbps (max declared peak 5,446kbps)
  - 720p, 25fps, AVC/H.264 High Profile (aka HD) / Level 4, average declared bitrate 2,822kbps (max declared peak 3,172kbps)
  - 480p, 25fps, AVC/H.264 High Profile (aka HD) / Level 4, average declared bitrate 1,492kbps (max declared peak 1,677kbps)
  - 360p, 25fps, AVC/H.264 High Profile (aka HD) / Level 4, average declared bitrate 913kbps (max declared peak 1,018kbps)
  - 240p, 25fps, AVC/H.264 High Profile (aka HD) / Level 4, average declared bitrate 525kbps (max declared peak 581kbps)

HLS thumbnails, used for scrubbing and hovering in players, are provided in all resolutions.

The audio is served from Amazon S3 (Ireland) using a single .mp4 (fMP4) file, using byte ranges to delineate 6-second chunks. Same for video and thumbails.

No ad slots were found on any shows.

Example show: [$HZ wir müssen reden](https://podcasts.apple.com/us/podcast/%24hz-wir-m%C3%BCssen-reden/id1818584366) ([RSS feed](https://shz-wir-muessen-reden.podigee.io/feed/mp3))

---

# Transistor

- Supports HLS video in Apple Podcasts: yes ✔︎
- Supports HLS video in RSS feeds: yes ✔︎

I've found at least 2 shows (3 video episodes) hosted by Transistor using the new HLS video integration in Apple Podcasts, and used the latest episode from each show as the basis for the analysis below.
Transistor supports HLS urls via `podcast:alternateEnclosure` in their RSS feeds, and in the case of these two shows, the same HLS video episodes in Apple Podcasts are also available in the corresponding public feeds.

They use [version 7](https://alexzambelli.com/blog/2016/05/04/understanding-hls-versions-and-client-compatibility/) and include one common audio track using the [AAC](https://en.wikipedia.org/wiki/Advanced_Audio_Coding) format, at an average declared bitrate of ~128kbps (max declared peak of ~128kbps).

HLS subtitles were not available.

Video resolutions:
  - 1080p in all shows, 24fps, AVC/H.264 High Profile (aka HD) / Level 4, average declared bitrate ranging from 3,826kbps to 3,851kbps (max declared peak ranging from 4,348kbps to 4,376kbps)
  - 720p in all shows, 24fps, AVC/H.264 High Profile (aka HD) / Level 3.1, average declared bitrate ranging from 2,189kbps to 2,194kbps (max declared peak ranging from 2,488kbps to 2,494kbps)
  - 480p in all shows, 24fps, AVC/H.264 High Profile (aka HD) / Level 3, average declared bitrate ranging from 990kbps to 990kbps (max declared peak ranging from 1,125kbps to 1,125kbps)

HLS thumbnails, used for scrubbing and hovering in players, are provided in 480p.

The audio is served from Cloudflare using a single .mp4 (fMP4) file, using byte ranges to delineate 6-second chunks. Same for video and thumbnails.

No ad slots were found.

Example show: [Primary Technology](https://podcasts.apple.com/us/podcast/primary-technology/id1723943281) ([RSS feed](https://feeds.transistor.fm/primary-technology))

---

# Audiomeans

- Supports HLS video in Apple Podcasts: yes ✔︎
- Supports HLS video in RSS feeds: not yet

I've found at least 7 shows (21 video episodes) hosted by Audiomeans using the new HLS video integration in Apple Podcasts, and used the latest episode from one show as the basis for the analysis below.

They use [version 7](https://alexzambelli.com/blog/2016/05/04/understanding-hls-versions-and-client-compatibility/) and include one common (French) audio track using the [AAC](https://en.wikipedia.org/wiki/Advanced_Audio_Coding) format, at a max declared peak bitrate of 141kbps.

HLS subtitles were not available.

Video resolutions:
  - 1080p, 30fps, AVC/H.264 Main Profile (aka SD) / Level 4, max declared peak bitrate ranging from 5,641kbps to 5,641kbps
  - 720p, 30fps, AVC/H.264 Main Profile (aka SD) / Level 4, max declared peak bitrate ranging from 3,221kbps to 3,221kbps

HLS thumbnails, used for scrubbing and hovering in players, are provided in 480p.

The audio is served from AWS using a single .mp4 (fMP4) file, using byte ranges to delineate 6-second chunks. Same for video and thumbnails.

One post-roll ad slot is defined using [HLS intersitials](https://ubik-ingenierie.com/blog/understanding-hls-interstitials-and-ext-x-discontinuity-in-ad-insertion/). Ads are served from an `audiosvr.com` (?) url, an EC2 server.
The post-roll ad slot is defined using `EXT-X-DATERANGE CUE=POST`

Example show: [Small Talk - Konbini](https://podcasts.apple.com/us/podcast/small-talk-konbini/id1644493181) ([RSS feed](https://feeds.audiomeans.fr/feed/f57a29ac-5ce1-423d-8ca2-82369d9ca230.xml))

---

# Fountain

- Supports HLS video in Apple Podcasts: not yet
- Supports HLS video in RSS feeds: yes ✔︎

I've found at least 57 shows (710 video episodes) hosted by Fountain using HLS in their podcast RSS feeds, and used a few recent epsiodes as the basis for the analysis below.

They use [HLS version 3](https://alexzambelli.com/blog/2016/05/04/understanding-hls-versions-and-client-compatibility/) and do _not_ have one common audio track, instead baking [AAC](https://en.wikipedia.org/wiki/Advanced_Audio_Coding) audio into each video track.

Fountain don't provide HLS subtitles.

Video resolutions:
  - 720p in all shows, 30fps, AVC/H.264 High Profile (aka HD) / Level 4, average declared bitrate 2,628kbps (max declared peak 3,128kbps)
  - 360p in all shows, 30fps, AVC/H.264 High Profile (aka HD) / Level 3.1, average declared bitrate 896kbps (max declared peak 1,096kbps)

No HLS thumbnails for scrubbing and hovering in players.

The audio and video is served from Cloudflare using separate 6-second .ts files.

No ad slots were found on any shows.

Example show: [Digital Credit Frontier](https://fountain.fm/show/QNrtJ381gXchvVzfk0CF) ([RSS feed](https://feeds.fountain.fm/9WmHfs1BM9WGEZXpq2n4))

---

# RSS.com

- Supports HLS video in Apple Podcasts: not yet
- Supports HLS video in RSS feeds: yes ✔︎

I've found at least 2 RSS.com shows using HLS in their podcast RSS feeds. They don't host HLS directly, but support a "bring your own HLS" model. As such, each show can bring different HLS infrastructure so are analyzed separately below.

One show uses [Mux](https://www.mux.com/) for HLS, [version 5](https://alexzambelli.com/blog/2016/05/04/understanding-hls-versions-and-client-compatibility/) and includes one common audio track using the [AAC](https://en.wikipedia.org/wiki/Advanced_Audio_Coding) format.

No HLS subtitles were provided.

Video resolutions:
  - 1080p, AVC/H.264 High Profile (aka HD) / Level 4.2, average declared bitrate 4,477kbps (max declared peak 4,477kbps)
  - 480p , AVC/H.264 High Profile (aka HD) / Level 3.1, average declared bitrate 1,097kbps (max declared peak 1,097kbps)
  - 270p, AVC/H.264 High Profile (aka HD) / Level 3, average declared bitrate 487kbps (max declared peak 487kbps)

No HLS thumbnails for scrubbing and hovering in players.

The audio is served from Mux using separate 6-second .m4s (fMP4) files, as are the video tracks.

No ad slots were found.

Example show: [Foc a Terra](https://podcasts.apple.com/us/podcast/foc-a-terra/id1604172036) ([RSS feed](https://media.rss.com/focaterra/feed.xml))


One show uses [Cloudflare Stream](https://www.cloudflare.com/developer-platform/products/cloudflare-stream/) for HLS, [version 6](https://alexzambelli.com/blog/2016/05/04/understanding-hls-versions-and-client-compatibility/) and includes one common audio track using the [AAC](https://en.wikipedia.org/wiki/Advanced_Audio_Coding) format.

HLS subtitles (English) were also provided.

Video resolutions:
  - 1080p, 29.97fps, AVC/H.264 Main Profile (aka SD) / Level 4, average declared bitrate 1,837kbps (max declared peak 3,891kbps)
  - 720p, 29.97fps, AVC/H.264 Main Profile (aka SD) / Level 3.1, average declared bitrate 919kbps (max declared peak 1,873kbps)
  - 480p, 29.97fps, AVC/H.264 Main Profile (aka SD) / Level 3.1, average declared bitrate 532kbps (max declared peak 1,037kbps)
  - 240p, 29.97fps, AVC/H.264 Constrained Baseline Profile / Level 2.1, average declared bitrate 297kbps (max declared peak 726kbps)

No HLS thumbnails for scrubbing and hovering in players.

The audio is served from Cloudflare using separate 4-second .mp4 (fMP4) files, as are the video tracks.

No ad slots were found.

Example show: [The Steady State Sentinel](https://podcasts.apple.com/us/podcast/the-steady-state-sentinel/id1865054486) ([RSS feed](https://media.rss.com/the-steady-state-sentinel/feed.xml))

---

# LISTEN

- Supports HLS video in Apple Podcasts: not yet
- Supports HLS video in RSS feeds: yes ✔︎

I've found at least one LISTEN (listen.style) show using HLS in the podcast RSS feed, and used the episodes as the basis for the analysis below.

It uses HLS [version 7](https://alexzambelli.com/blog/2016/05/04/understanding-hls-versions-and-client-compatibility/) and two of three episosdes use one common audio track using the [AAC](https://en.wikipedia.org/wiki/Advanced_Audio_Coding) format.

HLS subtitles were not found.

Video resolutions:
  - 1080p, AVC/H.264 Main Profile (aka SD) / Level 4, average declared bitrate ranging from 4,885kbps to 5,106kbps (max declared peak ranging from 5,642kbps to 5,897kbps)
  - 720p, AVC/H.264 Main Profile (aka SD) / Level 3.1, average declared bitrate ranging 2,684kbps to 2,866kbps (max declared peak ranging from 3,074kbps to 3,238kbps)

No HLS thumbnails for scrubbing and hovering in players.

The audio is served using separate 10-second .m4s (fMP4) files, as are the video tracks.

No ad slots were found.

Example show: [jkondoの朝の散歩](https://podcasts.apple.com/us/podcast/jkondo%E3%81%AE%E6%9C%9D%E3%81%AE%E6%95%A3%E6%AD%A9/id1706956513) ([RSS feed](https://rss.listen.style/p/asanosanpo/rss))

---

# Q & A

<br><br>

{{< details "_What about auto-downloads?_" "open" >}}
Any video episodes published via HLS can be downloaded for offline use, just like audio episodes. They can also be auto-downloaded, depending on what the app wants to do.

Apple Podcasts provides a global on/off setting to download video just like audio when auto-downloading, which defaults to off. This setting can also be overridden at an individual show level.
Listeners can also force a download of any video episode at any time for offline use, the same as audio.

{{< /details >}}

<br><br>

{{< details "_What exactly is downloaded, though?_" "open" >}}
Ultimately, it is up to the app. Think of HLS as providing a menu of video/audio track selections for the episode, with the app having the final say on what to order.

In general, iOS applications do _not_ include HLS interstitials (i.e. dynamic ads) by default when downloading HLS, but iOS provides a rich API for selecting which track qualities, and even which interstitials
to include in the download. Different apps can make different decisions, and can decide to surface additional settings (or not) for the listener to have a say.

We'll have to wait and see what Apple Podcasts chooses to do when auto-downloading and when force-downloading. At the moment, I notice that for a show that has known pre-roll interstitial ads, the interstitials are _not_ downloaded when force-downloading an episode and playing it back in airplane mode.

{{< /details >}}

<br><br>

---
*Updated 2026-03-29, added LISTEN, updated Apple Podcasts show and episode counts.*

*Updated 2026-03-27, updated Apple Podcasts show and episode counts, and a total at the top.*

*Updated 2026-03-26, updated show and episode counts following Apple Podcasts official iOS 26.4 launch, added Omny and Audiomeans, removed Simplecast.*

*Updated 2026-03-23, updated Transistor with examples from Apple Podcasts.*

*Updated 2026-03-17, added Podigee.*

---

Research by [John Spurlock](https://twitter.com/johnspurlock).

{{< contact "Let me know" >}} if you know of any other podcast hosting companies supporting HLS video in podcasts, and I'll update the findings here.

{{% funding %}}


---
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/hls-video-in-podcasts.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*