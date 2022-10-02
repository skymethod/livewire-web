---
title: "Statistics about Podcast Chapters"
description: "Popularity of various podcast chapter technologies, based on number of new episodes published"
slug: "podcast-chapters-stats"
images:
- podcast-chapters-stats-2022-09.png
date: 2022-10-02T11:48:00-05:00
lastmod: 2022-10-02T11:48:00-05:00
draft: false
rssrevision: 2022-09
---
Some podcast publishers choose to provide additional chapter information when they publish their podcast episodes,
breaking down a single episode into multiple segments - each of which may have a title, link, image, etc.

Right now, there are four mechanisms that podcasters can use to do this:
1. Embed chapter information directly inside the MP3 audio file using [standard ID3 tags](https://id3.org/id3v2-chapters-1.0), with tools such as [Forecast](https://overcast.fm/forecast).
2. Embed chapter information directly inside the AAC/M4A audio file using MPEG-4 [Chapter Lists](https://developer.apple.com/library/archive/documentation/QuickTime/QTFF/QTFFChap3/qtff3.html#//apple_ref/doc/uid/TP40000939-CH205-57863).
3. Include chapter information inside the RSS feed at the episode level using the [Podlove Simple Chapters](https://podlove.org/simple-chapters) spec, first published in 2012.
4. Create a separate json file with the chapter information, and reference it from the RSS feed at the episode level using the newer [Podcast Namespace Chapters](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#chapters) spec.


Apple published [Using chapters on Apple Podcasts](https://podcasters.apple.com/support/2482-using-chapters-on-apple-podcasts) earlier this year to highlight this little-known feature of podcasting.

Since we already analyze _every single new podcast episode published_ to produce our podcast [host](/podcast-hosts-by-episode-share), [tracker](/podcast-trackers-by-episode-share), and [CDN](/podcast-cdns-by-episode-share) rankings, we are in a good position to see how often podcast chapters are used in the wild, and which mechanisms are most prevalent.

{{% subscribe %}}
---

### Podcast Chapters frequency, by mechanism

_as a percentage of all new episodes published in the given month_

| Month | Any Chapters  | ID3 Chapters   | Namespace Chapters | Podlove Chapters | M4A Chapters |
|----------------|-------|-------|-----------|---------|-------|
| January 2022   | 1.22% | 0.87% | 0.18%     | 0.05%   | 0.02% |
| February 2022  | 1.22% | 0.85% | 0.19%     | 0.05%   | 0.02% |
| ...            | ...   | ...   | ...       | ...     | ...   |
| September 2022 | 1.80% | 1.29% | 0.44%     | 0.06%   | 0.02% |

---

About *1 in every 55* new podcast episodes provide chapter information.

In the last month, ID3 tags are the most popular mechanism.
- about 3x as prevalent as the Podcast Namespace chapters
- about 22x as prevalent as Podlove chapters
- and about 62x as prevalent as AAC/M4A chapters

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

---
*Updated 2022-10-02, with data for the month of September 2022.*

{{% funding %}}

---
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/podcast-chapters-stats.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
