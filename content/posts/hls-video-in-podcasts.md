---
title: "HLS video in podcasts, who's doing what?"
description: "Keeping an eye on every HLS video in the podcast system"
slug: "hls-video-in-podcasts"
images:
- hls-video-in-podcasts.png
date: 2026-03-11T11:47:00-04:00
lastmod: 2026-03-11T11:47:00-04:00
draft: false
---

Apple Podcasts recently announced they will be [supporting HLS video](https://www.apple.com/newsroom/2026/02/apple-introduces-a-new-video-podcast-experience-on-apple-podcasts/), bringing a high-quality video option to their app for shows that want to do video episodes, including the ability to
seamlessly switch between video and audio-only during playback.

Publishers can make the same high-quality video experience available in _all_ podcast apps simply by adding the same [HLS multivariant playlist](https://docs.aws.amazon.com/mediatailor/latest/ug/hls-playlist-types.html) url to the [`podcast:alternateEnclosure`](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/tags/alternate-enclosure.md) tag at the episode-level in their existing audio podcast RSS feed.

{{% subscribe %}}

---

HLS is a rich format with an almost endless variety of optional features and configurations, so "HLS video" doesn't really tell the whole story.

I'll be keeping an eye out for HLS video in Apple Podcasts and in RSS feeds. Let's take a look at what hosting companies are actually doing with their HLS video in podcasts so far, and how they are doing it.

{{% funding %}}

---

# Acast

- Supports HLS video in Apple Podcasts: yes ✔︎
- Supports HLS video in RSS feeds: not yet

I've found at least 9 shows (689 video episodes) hosted by Acast using the new HLS video integration in Apple Podcasts, and used the latest episode from each show as the basis for the analysis below.

They use [HLS version 7](https://alexzambelli.com/blog/2016/05/04/understanding-hls-versions-and-client-compatibility/) and include one common audio track (English) using the [AAC](https://en.wikipedia.org/wiki/Advanced_Audio_Coding) format, at an average declared bitrate of ~140kbps (max declared peak of 157kbps).

Acast don't provide HLS subtitles.

Video resolutions:
  - 1080p in most shows (7 of 9), 30fps, AVC/H.264 High Profile (aka HD) / Level 4.1, average declared bitrate ranging from 1,015kbps to 5,297kbps (max declared peak ranging from 1,723kbps to 6,403kbps)
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

I've found at least 5 shows (97 video episodes) hosted by ART19 using the new HLS video integration in Apple Podcasts, and used the latest episode from each show as the basis for the analysis below.

They use [HLS version 8](https://alexzambelli.com/blog/2016/05/04/understanding-hls-versions-and-client-compatibility/) and include one common audio track (English) using the [AAC](https://en.wikipedia.org/wiki/Advanced_Audio_Coding) format, at an average declared bitrate of 128kbps (max declared peak of 129kbps).

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

I haven't found any shows hosted by Omny Studio using the new HLS video integration in Apple Podcasts, but they are listed as an official partner. {{< contact "Let me know" >}} if you find one!

---

# Simplecast

- Supports HLS video in Apple Podcasts: yes ✔︎
- Supports HLS video in RSS feeds: not yet

I haven't found any shows hosted by Simplecast using the new HLS video integration in Apple Podcasts, but they are listed as an official partner. {{< contact "Let me know" >}} if you find one!

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

# Transistor

- Supports HLS video in Apple Podcasts: not yet
- Supports HLS video in RSS feeds: yes ✔︎

I've found a few shows hosted by Transistor using HLS in their podcast RSS feeds, and chosen one hosted on a Transistor domain, and one externally, to be analyzed separately below.

The show using a Transistor-hosted HLS uses [version 7](https://alexzambelli.com/blog/2016/05/04/understanding-hls-versions-and-client-compatibility/) and includes one common audio track using the [AAC](https://en.wikipedia.org/wiki/Advanced_Audio_Coding) format, with a max declared peak bitrate of 132kbps.

HLS subtitles were not available.

Video resolutions:
  - 1080p, AVC/H.264 High Profile (aka HD) / Level 4, average declared bitrate 3,772kbps (max declared peak 4,286kbps)
  - 720p, AVC/H.264 High Profile (aka HD) / Level 3.1, average declared bitrate 2,145kbps (max declared peak 2,437kbps)
  - 480p, AVC/H.264 High Profile (aka HD) / Level 3, average declared bitrate 971kbps (max declared peak 1,103kbps)

HLS thumbnails, used for scrubbing and hovering in players, are provided in 480p.

The audio is served from Cloudflare using a single .mp4 (fMP4) file, using byte ranges to delineate 6-second chunks. Same for video and thumbnails.

No ad slots were found.

Example show: [Justin's brain](https://podcasts.apple.com/us/podcast/justins-brain/id1655281489) ([RSS feed](https://feeds.transistor.fm/justin-jackson))

The show using an externally-hosted HLS uses [Cloudflare Stream](https://www.cloudflare.com/developer-platform/products/cloudflare-stream/) for HLS, [version 6](https://alexzambelli.com/blog/2016/05/04/understanding-hls-versions-and-client-compatibility/) and includes one common audio track using the [AAC](https://en.wikipedia.org/wiki/Advanced_Audio_Coding) format

HLS subtitles (English) were also provided.

Video resolutions:
  - 1080p, 24fps, AVC/H.264 Main Profile (aka SD) / Level 4, average declared bitrate 2,648kbps (max declared peak 4,716kbps)
  - 720p, 24fps, AVC/H.264 Main Profile (aka SD) / Level 3.1, average declared bitrate 1,401kbps (max declared peak 2,481kbps)
  - 480p, 24fps, AVC/H.264 Main Profile (aka SD) / Level 3, average declared bitrate 765kbps (max declared peak 1,356kbps)
  - 360p, 24fps, AVC/H.264 Main Profile (aka SD) / Level 3, average declared bitrate 525kbps (max declared peak 915kbps)
  - 240p, 24fps, AVC/H.264 Constrained Baseline Profile / Level 2.1, average declared bitrate 393kbps (max declared peak 676kbps)

No HLS thumbnails for scrubbing and hovering in players.

The audio is served from Cloudflare using separate 4-second .mp4 (fMP4) files, as are the video tracks.

No ad slots were found.

Example show: [Primary Technology](https://podcasts.apple.com/us/podcast/primary-technology/id1723943281) ([RSS feed](https://feeds.transistor.fm/primary-technology))

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

Research by [John Spurlock](https://twitter.com/johnspurlock).

{{< contact "Let me know" >}} if you know of any other podcast hosting companies supporting HLS video in podcasts, and I'll update the findings here.

{{% subscribe %}}


---
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/hls-video-in-podcasts.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*