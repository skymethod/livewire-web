---
title: "Top Podcast Tracking Services by Episode Share (September 2022)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-september-2022"
images:
- trackers-2022-09.png
date: 2022-10-03T11:00:00-05:00
lastmod: 2022-10-03T11:00:00-05:00
draft: false
rssrevision: 2022-09
tags:
- archive
---
*This is an archived version, the current version is [here](/podcast-trackers-by-episode-share/).*

Now that we have a good idea of [which podcast hosts are producing new podcast episodes](/podcast-hosts-by-episode-share),
let's turn our attention to third-party podcast analytics services.

These services are typically provided by a company that is not the podcast host, but can provide tracking and analytics 
by being specified as the underlying media file url, which then redirects back to the host.  Sometimes, these services
are implemented as custom prefixes (taking the original media url and adding a prefix to it), but not always.

By intercepting every episode media file request, these analytics services can provide a view that is potentially larger than
what the underlying podcast host analytics can provide.

Podtrac, one of the most popular services, released some 
[interesting data about their US download figures for September 2021](https://podnews.net/article/podtrac-us-downloads-and-users-sep21).

But how representative of the entire podcast world is this data?  How many podcasters use services like these?

{{% subscribe %}}
---

We already did the work of analyzing _every single new podcast episode published_ (about 1.7 million in September 2022), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in September, how many
of them included one or more of these tracking services?  Some episodes had as many as *six* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

> As previewed a few weeks ago in our story [Podtrac's share of new podcast episodes started taking off in September](/podtrac-share-of-new-episodes-taking-off/),
there is a new number one, thanks to Podtrac's recent integration with many shows hosted by Spreaker.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Chartable	Podcorn	Adswizz	Podsights	Blubrry	Médiamétrie	Feedpress	ArtsAI	Zippycast	Podscribe	Gumball	Claritas	Podkite	FeedBurner
Sep 2021	4.16	4.06	2.09	1.00	1.16	2.07	0.42	0.32							1.61
Oct 2021	4.05	4.09	2.13	1.01	1.20	2.11	0.54	0.34							1.61
Nov 2021	4.07	4.30	2.14	1.02	1.25	2.01	0.57	0.32							0.59
Dec 2021	4.06	4.42	2.27	1.24	1.19	1.57	0.59	0.19							
Jan 2022	4.11	4.45	2.31	1.41	1.21	1.56	0.63	0.16							
Feb 2022	4.15	4.48	2.38	1.44	1.25	1.53	0.58	0.17							
Mar 2022	4.37	4.72	2.40	1.51	1.34	1.56	0.53	0.17							
Apr 2022	4.44	4.71	2.33	1.49	1.33	1.55	0.51	0.16							
May 2022	4.49	4.87	2.26	1.58	1.41	1.48	0.56	0.17							
Jun 2022	4.75	5.10	2.06	1.77	1.54	1.50	0.62	0.21		0.02					
Jul 2022	4.70	5.10	2.16	1.89	1.50	1.50	0.54	0.25		0.02					
Aug 2022	4.83	5.26	2.45	2.08	1.73	1.51	0.41	0.20	0.10	0.01					
Sep 2022	7.53	5.40	2.45	2.26	1.74	1.49	0.52	0.21	0.09	0.02	0.02	0.02	0.01	0.01	
{{< /graph >}}

---

### Overall

At least one tracker was found on 16.89% of new episodes in September, growing 20.51% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "20.73%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.41%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.57%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "8.55%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "6.78%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.35%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.92%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "3.15%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.75%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.21%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of September 2022.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 7.53% of new episodes in September, growing 55.04% from last month.

Of these, 22.66% had one other tracker, 12.09% had 2 other trackers, 2.37% had 3 other trackers, 0.16% had 4 other trackers, and 0.01% had 5 other trackers.

29.38% also included Chartable, 14.66% also included Podsights, 6.50% also included Adswizz, 1.65% also included Podcorn, 0.89% also included ArtsAI, 0.65% also included Blubrry, 0.23% also included Podscribe, 0.19% also included Feedpress, 0.10% also included Magellan AI, 0.10% also included Backtracks, 0.06% also included Médiamétrie, 0.06% also included Veritonic, 0.05% also included Gumball, 0.04% also included Zippycast, 0.04% also included AdBarker, 0.02% also included OP3, 0.01% also included Podder, <0.01% also included Claritas, <0.01% also included Firstory, and <0.01% also included Podkite.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "44.72%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "14.48%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.68%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.49%" >}}
5. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.74%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.18%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.17%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.87%" >}}
9. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "1.60%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.35%" >}}
---

### [Spotify (Chartable & Podsights)](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/)

At least one Spotify tracker was found on 5.80% of new episodes in September, growing 1.85% from last month.

Of these, 40.25% also included Podtrac, 5.44% also included Adswizz, 4.75% also included Podcorn, 1.58% also included ArtsAI, 1.08% also included Firstory, 0.46% also included Blubrry, 0.33% also included Podscribe, 0.29% also included Magellan AI, 0.24% also included Gumball, 0.14% also included Claritas, 0.08% also included AdBarker, 0.08% also included Veritonic, 0.04% also included Feedpress, 0.03% also included Zippycast, 0.03% also included Podder, 0.02% also included OP3, 0.02% also included Podkite, and 0.02% also included Backtracks.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "25.86%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.21%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.27%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.50%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.80%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.78%" >}}
7. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "2.58%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.54%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.46%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.43%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.40% of new episodes in September, growing 1.86% from last month.

Of these, 33.96% had one other tracker, 17.59% had 2 other trackers, 3.40% had 3 other trackers, 0.20% had 4 other trackers, and 0.02% had 5 other trackers.

41.00% also included Podtrac, 24.73% also included Podsights, 5.55% also included Adswizz, 4.54% also included Podcorn, 1.55% also included ArtsAI, 1.16% also included Firstory, 0.40% also included Blubrry, 0.30% also included Magellan AI, 0.30% also included Podscribe, 0.23% also included Gumball, 0.15% also included Claritas, 0.09% also included AdBarker, 0.08% also included Veritonic, 0.04% also included Feedpress, 0.03% also included Podder, 0.02% also included Podkite, 0.02% also included Backtracks, 0.01% also included OP3, and <0.01% also included Zippycast.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "24.92%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.45%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.59%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.21%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.03%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.00%" >}}
7. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "2.77%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.69%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.61%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.61%" >}}
---

### 3. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 2.45% of new episodes in September, shrinking 0.79% from last month.

Of these, 10.54% had one other tracker, 2.29% had 2 other trackers, 0.77% had 3 other trackers, 0.06% had 4 other trackers, and 0.03% had 5 other trackers.

10.02% also included Chartable, 5.07% also included Podtrac, 2.00% also included Podsights, 0.22% also included Blubrry, 0.21% also included Magellan AI, 0.10% also included AdBarker, 0.06% also included Gumball, 0.04% also included OP3, 0.03% also included Podkite, 0.03% also included Backtracks, 0.02% also included Adswizz, and 0.01% also included Podder.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "52.22%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "21.72%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.86%" >}}
4. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "4.50%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.90%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.62%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.30%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.93%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.37%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.75%" >}}
---

### 4. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.26% of new episodes in September, growing 8.24% from last month.

Of these, 22.58% had one other tracker, 5.08% had 3 other trackers, 2.55% had 2 other trackers, 0.13% had 4 other trackers, and 0.01% had 5 other trackers.

21.61% also included Podtrac, 13.24% also included Chartable, 7.33% also included Podsights, 0.85% also included Blubrry, 0.39% also included ArtsAI, 0.03% also included Podcorn, 0.01% also included Claritas, 0.01% also included Veritonic, 0.01% also included Gumball, and <0.01% also included Podkite.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "30.64%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "16.46%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.81%" >}}
4. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "9.84%" >}}
5. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "9.39%" >}}
6. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "5.45%" >}}
7. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.12%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "4.06%" >}}
9. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.51%" >}}
10. {{< a "https://www.bbc.co.uk/" "BBC" >}} {{< span "weak" "1.28%" >}}
---

### 5. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.74% of new episodes in September, growing 0.07% from last month.

Of these, 51.30% had 2 other trackers, 23.45% had one other tracker, 10.30% had 3 other trackers, 0.67% had 4 other trackers, and 0.05% had 5 other trackers.

76.80% also included Chartable, 63.55% also included Podtrac, 9.56% also included Adswizz, 4.36% also included ArtsAI, 2.81% also included Podcorn, 0.69% also included Podscribe, 0.63% also included Gumball, 0.41% also included Blubrry, 0.39% also included Magellan AI, 0.33% also included Claritas, 0.12% also included Zippycast, 0.09% also included Veritonic, 0.06% also included OP3, 0.02% also included AdBarker, 0.02% also included Backtracks, 0.01% also included Podkite, and 0.01% also included Podder.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "42.90%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "28.06%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "6.77%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.19%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.35%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.51%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.95%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.49%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.25%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.92%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.49% of new episodes in September, shrinking 1.55% from last month.

Of these, 5.56% had one other tracker, 0.76% had 2 other trackers, 0.16% had 3 other trackers, 0.03% had 4 other trackers, and 0.02% had 5 other trackers.

3.30% also included Podtrac, 1.46% also included Chartable, 1.29% also included Adswizz, 0.89% also included Feedpress, 0.48% also included Podsights, 0.37% also included Podcorn, 0.02% also included AdBarker, and 0.01% also included OP3.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "76.66%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "4.62%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.52%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.08%" >}}
5. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.37%" >}}
6. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.12%" >}}
7. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.08%" >}}
8. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "1.01%" >}}
9. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "0.99%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.85%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.52% of new episodes in September, growing 24.86% from last month.

Of these, 0.92% had one other tracker.

0.92% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "37.26%" >}}
2. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "35.79%" >}}
3. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "12.00%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "8.59%" >}}
5. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "5.47%" >}}
6. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "0.51%" >}}
---

### 8. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.21% of new episodes in September, growing 4.70% from last month.

Of these, 12.60% had one other tracker, and 0.78% had 2 other trackers.

6.73% also included Podtrac, 6.33% also included Blubrry, and 1.09% also included Chartable.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "69.12%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "10.53%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.35%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.74%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.82%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.64%" >}}
7. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.27%" >}}
8. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.83%" >}}
9. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "0.83%" >}}
10. {{< a "https://www.subsplash.com/" "Subsplash" >}} {{< span "weak" "0.78%" >}}
---

### 9. [Firstory](https://firstory.me/)

Firstory was found on 0.10% of new episodes in September, shrinking 4.12% from last month.

Of these, 62.32% had one other tracker, and 0.24% had 2 other trackers.

62.56% also included Chartable, and 0.24% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.64%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.36%" >}}
---

### 10. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.09% of new episodes in September, shrinking 3.18% from last month.

Of these, 52.88% had 3 other trackers, 24.94% had 2 other trackers, 10.23% had 4 other trackers, 8.76% had one other tracker, and 0.13% had 5 other trackers.

88.55% also included Chartable, 79.99% also included Podsights, 70.46% also included Podtrac, 9.34% also included Adswizz, 6.71% also included Podscribe, 2.88% also included Claritas, and 0.90% also included Veritonic.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "38.81%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "35.68%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "14.39%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.65%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.96%" >}}
6. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.51%" >}}
---

### 11. [Zippycast](https://zippycast.io/)

Zippycast was found on 0.02% of new episodes in September, growing 62.97% from last month.

Of these, 9.38% had 2 other trackers, and 5.97% had one other tracker.

14.20% also included Podtrac, 9.38% also included Podsights, and 1.14% also included Chartable.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "34.66%" >}}
2. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "21.59%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "18.18%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "17.33%" >}}
5. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "6.53%" >}}
6. {{< a "https://podcloud.fr/" "podCloud" >}} {{< span "weak" "1.70%" >}}
---

### 12. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.02% of new episodes in September, growing 14.58% from last month.

Of these, 52.01% had 2 other trackers, 22.29% had one other tracker, and 18.89% had 3 other trackers.

83.28% also included Chartable, 39.32% also included Podtrac, 34.67% also included Podsights, and 25.70% also included Podcorn.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "44.58%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.34%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "18.58%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.33%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.17%" >}}
---

### 13. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.02% of new episodes in September, growing 262.71% from last month.

Of these, 35.31% had 2 other trackers, 32.81% had 4 other trackers, 19.69% had 3 other trackers, and 12.19% had one other tracker.

87.81% also included Podtrac, 83.44% also included Chartable, 62.19% also included Podsights, 32.81% also included ArtsAI, and 6.88% also included Veritonic.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "80.63%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "19.38%" >}}
---

### 14. [Gumball](https://gumball.fm/)

Gumball was found on 0.02% of new episodes in September, growing 44.57% from last month.

Of these, 58.28% had 2 other trackers, 16.89% had one other tracker, 3.97% had 4 other trackers, 2.32% had 3 other trackers, and 1.32% had 5 other trackers.

68.54% also included Chartable, 60.26% also included Podsights, 19.87% also included Podtrac, 7.62% also included Podcorn, 5.96% also included OP3, and 0.66% also included Adswizz.

For episodes that used Gumball, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "49.67%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "23.84%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.26%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "8.28%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "7.62%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.33%" >}}
---

### 15. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.01% of new episodes in September, shrinking 12.11% from last month.

Of these, 61.95% had one other tracker, 2.93% had 2 other trackers, and 2.44% had 4 other trackers.

61.46% also included Podtrac, 8.29% also included Chartable, 5.37% also included Podcorn, and 2.44% also included Podsights.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "54.15%" >}}
2. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "15.12%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "6.34%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.39%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.90%" >}}
6. {{< a "https://www.subsplash.com/" "Subsplash" >}} {{< span "weak" "1.46%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.98%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.49%" >}}
---

### 16. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.01% of new episodes in September, growing 669.18% from last month.

Of these, 80.77% had 2 other trackers, 2.56% had one other tracker, 2.56% had 4 other trackers, and 1.28% had 5 other trackers.

84.62% also included Chartable, 60.26% also included Podsights, 28.85% also included ArtsAI, 3.85% also included Podtrac, and 3.21% also included Adswizz.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "92.31%" >}}
2. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.85%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.85%" >}}
---

### 17. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in September, shrinking 6.12% from last month.

Of these, 58.82% had 2 other trackers, 5.88% had one other tracker, and 5.04% had 5 other trackers.

67.23% also included Chartable, 37.82% also included Podtrac, 33.61% also included Podcorn, 5.04% also included Blubrry, and 5.04% also included Podsights.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "35.29%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "31.93%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "15.13%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "8.40%" >}}
5. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "4.20%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.52%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.52%" >}}
---

### 18. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in September, growing 29.75% from last month.

Of these, 20.00% had one other tracker, 2.00% had 2 other trackers, 2.00% had 5 other trackers, 1.00% had 3 other trackers, and 1.00% had 4 other trackers.

17.00% also included Chartable, 13.00% also included Podcorn, 4.00% also included Podtrac, 4.00% also included Podsights, 2.00% also included Podder, and 1.00% also included Adswizz.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.00%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "23.00%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "11.00%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.00%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "8.00%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "6.00%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.00%" >}}
8. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "3.00%" >}}
9. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.00%" >}}
10. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "1.00%" >}}
---

### 19. [Veritonic](https://www.veritonic.com/)

Veritonic was found on <0.01% of new episodes in September, growing 10.57% from last month.

Of these, 40.54% had 3 other trackers, 35.14% had 2 other trackers, and 24.32% had 4 other trackers.

100.00% also included Podtrac, 100.00% also included Chartable, 35.14% also included Podsights, 29.73% also included Podscribe, 18.92% also included ArtsAI, and 5.41% also included Adswizz.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "74.32%" >}}
2. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "25.68%" >}}
---

### 20. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on <0.01% of new episodes in September,  from last month.

Of these, 22.64% had 4 other trackers, 7.55% had 3 other trackers, 7.55% had 5 other trackers, and 1.89% had one other tracker.

35.85% also included Podtrac, 33.96% also included Podcorn, 33.96% also included Podsights, 33.96% also included Gumball, 11.32% also included Chartable, and 3.77% also included Blubrry.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://podnews.net/" "Podnews" >}} {{< span "weak" "37.74%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "35.85%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.77%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.77%" >}}
5. {{< a "https://www.digitalocean.com/products/spaces/" "DigitalOcean Spaces" >}} {{< span "weak" "1.89%" >}}
---

### 21. [Podder](https://www.podderapp.com/)

Podder was found on <0.01% of new episodes in September, growing 38.06% from last month.

Of these, 42.86% had one other tracker, 10.20% had 2 other trackers, and 4.08% had 5 other trackers.

51.02% also included Chartable, 14.29% also included Podtrac, 10.20% also included Podcorn, 4.08% also included Podkite, and 4.08% also included Podsights.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "34.69%" >}}
2. {{< a "https://sounder.fm/" "Sounder" >}} {{< span "weak" "24.49%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "20.41%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.16%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.16%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.08%" >}}


---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
*Updated 2022-10-03, with data for the month of September 2022.*

*Updated 2022-09-01, with data for the month of August 2022.*

*Updated 2022-08-01, with data for the month of July 2022.*

*Updated 2022-07-01, with data for the month of June 2022.*

*Updated 2022-06-01, with data for the month of May 2022.*

*Updated 2022-05-01, with data for the month of April 2022.*

*Updated 2022-04-05, RSS Podcasting is now known as RSS.com.*

*Updated 2022-04-03, with data for the month of March 2022 and a new graph.*

*Updated 2022-03-03, with data for the month of February 2022, added AdBarker.*

*Updated 2022-02-19, added new overall breakdowns of how many new episodes use at least one tracker, and how many use at least one Spotify-owned tracker.*

*Updated 2022-02-08, with data for the month of January 2022.*

*Updated 2022-01-10, was missing data for December 31, now fixed.*

*Updated 2022-01-07, with data for the month of December 2021.*

*Updated 2021-12-04, with data for the month of November 2021.*

*Updated 2021-11-18, added Backtracks.*

*Updated 2021-11-14, with data for the month of October 2021.*

*Updated 2021-10-21: Added Adswizz and tweaked the host identification to choose the last known host in the redirect chain instead of the first, in an attempt to better capture customer-driven host migrations.*

*Updated 2021-10-14: Added a section about how direct server-to-server analytics integrations are not publically visible, and thus out of scope.*

*Updated 2021-10-13: Removed Podtrac as a host under itself, even when it is the last media file url in the redirect chain.*

---
Previous versions:
 - [Podcast Tracker Rankings by Episode Share (August 2022)](/archive/podcast-trackers-by-episode-share-august-2022/)
 - [Podcast Tracker Rankings by Episode Share (July 2022)](/archive/podcast-trackers-by-episode-share-july-2022/)
 - [Podcast Tracker Rankings by Episode Share (June 2022)](/archive/podcast-trackers-by-episode-share-june-2022/)
 - [Podcast Tracker Rankings by Episode Share (May 2022)](/archive/podcast-trackers-by-episode-share-may-2022/)
 - [Podcast Tracker Rankings by Episode Share (April 2022)](/archive/podcast-trackers-by-episode-share-april-2022/)
 - [Podcast Tracker Rankings by Episode Share (March 2022)](/archive/podcast-trackers-by-episode-share-march-2022/)
 - [Podcast Tracker Rankings by Episode Share (February 2022)](/archive/podcast-trackers-by-episode-share-february-2022/)
 - [Podcast Tracker Rankings by Episode Share (January 2022)](/archive/podcast-trackers-by-episode-share-january-2022/)
 - [Podcast Tracker Rankings by Episode Share (December 2021)](/archive/podcast-trackers-by-episode-share-december-2021/)
 - [Podcast Tracker Rankings by Episode Share (November 2021)](/archive/podcast-trackers-by-episode-share-november-2021/)
 - [Podcast Tracker Rankings by Episode Share (October 2021)](/archive/podcast-trackers-by-episode-share-october-2021/)
 - [Podcast Tracker Rankings by Episode Share (September 2021)](/archive/podcast-trackers-by-episode-share-september-2021/)

{{% funding %}}

---
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2022-09.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
