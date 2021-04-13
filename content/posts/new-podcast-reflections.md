---
title: "New podcast: Reflections"
description: "A new test podcast called Reflections that not only will show you in the show notes which user agent was used to fetch the feed, but each episode will also read back which user agent was used to fetch the audio file!"
slug: "new-podcast-reflections"
date: 2021-04-12T14:40:00-05:00
draft: false
---

{{< iframe "https://api.livewire.io/reflections.html" >}}

There has been some talk recently (particularly from the podcast host [Buzzsprout](https://www.buzzsprout.com/)) that [Spotify has overtaken Apple Podcasts in podcast downloads](https://discoverpods.com/spotify-overtakes-apple-podcast-downloads/).  One way they arrived at this was by excluding any "AppleCoreMedia" [^1] [user agent](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/User-Agent) strings found in their backend analytics from attributing to the Apple Podcasts app.

While it's true that the AppleCoreMedia user agent string is not exclusive to Apple Podcasts, it is better thought of as applying equally to all podcast apps on Apple's platforms. It should therefore not be excluded, but rather allocated according to the percentage of the "Apple Share" each app already receives.  

When is AppleCoreMedia sent?  Whenever the audio file is fetched directly as the result of an undownloaded playback by an Apple media API (e.g. [AVAudioPlayer](https://developer.apple.com/documentation/avfaudio/avaudioplayer)), in which case the user agent string cannot be easily specified.

In constrast, in cases where the app can fetch the audio file ahead-of-time (e.g. by [URLRequest](https://developer.apple.com/documentation/foundation/urlrequest)), the user agent can be easily specified (to Overcast or Apple Podcasts etc).  For podcast apps, this is a common case, since "Followed" shows are often auto-downloaded.

Ideally, it would be interesting to know - for each app - when AppleCoreMedia (and other user agents) are used in practice.

In order to help get to the bottom of this, I've created a new test podcast called __Reflections__ that not only will show you in the show notes which user agent was used to fetch the feed, but each episode will also _read back which user agent was used to fetch the audio file!_

Here is the feed URL for the Reflections podcast, you should be able to add it to any podcast app:

* https://api.livewire.io/reflections.xml

_(e.g. for Apple Podcasts, Library -> Shows -> Edit -> Add a Show by URL...)_

User agents for known apps are categorized into shorter names using the excellent [User agent list](https://github.com/opawg/user-agents) by [James Cridland](https://james.cridland.net/), as raw user agent strings are not exactly radio friendly. : )

The information contained in this test podcast simply reflects a single request and response, it does absolutely no server-side logging or tracking, so if you find something interesting, let us know via email at <a href="mailto:reflections@livewire.io">reflections@livewire.io</a>, thanks!

Some findings thus far:
 * Apple Podcasts sends AppleCoreMedia when playing an undownloaded episode, which can be quite often when sampling new podcasts, or when "Auto-Download" is disabled.
 * Apple Podcasts fetches both the feed and each media file directly from the user's device.
 * [Overcast](https://overcast.fm/) never sends AppleCoreMedia, and always seems to pre-download the file before playback.
 * Overcast fetches the media file from the user's device, but fetches the feed (even for user-added feeds) from a central server.

---

*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/new-podcast-reflections.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*


[^1]: e.g. `AppleCoreMedia/1.0.0.18E5198a (iPhone; U; CPU OS 14_5 like Mac OS X; en_us)`