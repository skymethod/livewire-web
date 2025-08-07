---
title: "Podcast Index Statistics, visualized"
description: "Visualizing the podcast data provided daily by podcastindex.org"
slug: "podcast-index-stats-visualized"
images:
- podcast-index-stats.png
date: 2022-12-03T15:42:00-06:00
lastmod: 2022-12-03T15:42:00-06:00
updatefrequency: daily
draft: false
---

The [Podcast Index](https://podcastindex.org), an open index of all podcasts, provides [summary statistics](https://stats.podcastindex.org/daily_counts.json) about how many feeds and episodes it has seen and stored in its database.

{{% subscribe %}}
---
Here is a live look at the Podcast Index:

{{< iframe src="https://stats.livewire.io/pc20-counts-summary.html" height="830" >}}

---

We capture daily snapshots of these numbers, and make a [tab-delimited data file](https://stats.livewire.io/pc20-counts-daily.tsv) available.

Below are live charts to keep an eye on changes to these stats on a daily basis:

---

{{< graph feeds-with-new-episodes "Feeds with new episodes in the last N days">}}
Date	Last 3 days	Last 7 days	Last 10 days	Last 14 days	Last 30 days	Last 60 days	Last 90 days
https://stats.livewire.io/pc20-counts-daily.tsv?columns=feedsWithNewEpisodes
{{< /graph >}}

---

{{< graph feeds-with "Feeds with transcripts, value blocks, chapters, etc">}}
Date	Value blocks	Transcripts	Funding	Chapters	Medium=Music	Medium=Video	Social Interact	Soundbites
https://stats.livewire.io/pc20-counts-daily.tsv?columns=feedsWith
{{< /graph >}}

---

{{< graph feed-count-change "Feed count change" "type:bar,min:-20000,max:20000">}}
Date	Feed count change
https://stats.livewire.io/pc20-counts-daily.tsv?columns=feedCountChange
{{< /graph >}}

---

{{< graph new-episodes "New episodes in the last N days">}}
Date	Last 3 days	Last 7 days	Last 10 days	Last 14 days	Last 30 days	Last 60 days	Last 90 days
https://stats.livewire.io/pc20-counts-daily.tsv?columns=newEpisodes
{{< /graph >}}

---

Data provided by the [Podcast Index](https://podcastindex.org), visualized by [John Spurlock](https://twitter.com/johnspurlock)

{{% funding %}}

---
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/podcast-index-stats-visualized.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*