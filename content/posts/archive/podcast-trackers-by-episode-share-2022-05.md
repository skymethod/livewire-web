---
title: "Top Podcast Tracking Services by Episode Share (May 2022)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-may-2022"
images:
- trackers-2022-05.png
date: 2022-06-01T19:49:00-05:00
lastmod: 2022-06-01T19:49:00-05:00
draft: false
rssrevision: 2022-05
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

---

We already did the work of analyzing _every single new podcast episode published_ (about 1.8 million in May 2022), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in May, how many
of them included one or more of these tracking services?  Some episodes had as many as *five* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Chartable	Podtrac	Podcorn	Adswizz	Blubrry	Podsights	Médiamétrie	Feedpress	FeedBurner
Sep 2021	4.06	4.16	2.09	1.00	2.07	1.16	0.42	0.32	1.61
Oct 2021	4.09	4.05	2.13	1.01	2.11	1.20	0.54	0.34	1.61
Nov 2021	4.30	4.07	2.14	1.02	2.01	1.25	0.57	0.32	0.59
Dec 2021	4.42	4.06	2.27	1.24	1.57	1.19	0.59	0.19	
Jan 2022	4.45	4.11	2.31	1.41	1.56	1.21	0.63	0.16	
Feb 2022	4.48	4.15	2.38	1.44	1.53	1.25	0.58	0.17	
Mar 2022	4.72	4.37	2.40	1.51	1.56	1.34	0.53	0.17	
Apr 2022	4.71	4.44	2.33	1.49	1.55	1.33	0.51	0.16	
May 2022	4.87	4.49	2.26	1.58	1.48	1.41	0.56	0.17	
{{< /graph >}}

---

### Overall

At least one tracker was found on 12.77% of new episodes in May, growing 1.38% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.07%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.01%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.12%" >}}
4. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "9.05%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.36%" >}}
6. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "5.08%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.85%" >}}
8. {{< a "https://analytics.podtrac.com/" "Podtrac" >}} {{< span "weak" "4.47%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "4.17%" >}}
10. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "3.07%" >}}
---

### [Spotify (Chartable & Podsights)](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/)

At least one Spotify tracker was found on 5.11% of new episodes in May, growing 3.96% from last month.

Of these, 37.89% also included Podtrac, 6.52% also included Adswizz, 4.60% also included Podcorn, 1.23% also included Firstory, 0.46% also included Blubrry, 0.26% also included Magellan AI, 0.10% also included AdBarker, 0.08% also included Feedpress, 0.04% also included Backtracks, and 0.01% also included Podkite.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.21%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.71%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "8.04%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.82%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.81%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.73%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.36%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.11%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.85%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.65%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of May 2022.

---

### 1. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 4.87% of new episodes in May, growing 3.46% from last month.

Of these, 30.40% had one other tracker, 18.27% had 2 other trackers, 2.80% had 3 other trackers, and 0.01% had 4 other trackers.

38.00% also included Podtrac, 24.02% also included Podsights, 6.60% also included Adswizz, 4.52% also included Podcorn, 1.30% also included Firstory, 0.44% also included Blubrry, 0.27% also included Magellan AI, 0.09% also included AdBarker, 0.09% also included Feedpress, 0.04% also included Backtracks, and 0.01% also included Podkite.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "21.97%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.91%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "8.40%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.97%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.51%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.93%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.51%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.16%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.96%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.78%" >}}
---

### 2. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 4.49% of new episodes in May, growing 1.25% from last month.

Of these, 29.97% had one other tracker, 18.90% had 2 other trackers, 3.04% had 3 other trackers, and 0.01% had 4 other trackers.

41.23% also included Chartable, 22.24% also included Podsights, 10.55% also included Adswizz, 1.53% also included Podcorn, 1.06% also included Blubrry, 0.13% also included Feedpress, 0.09% also included Backtracks, 0.07% also included AdBarker, 0.02% also included Magellan AI, 0.01% also included Firstory, <0.01% also included Podkite, and <0.01% also included Médiamétrie.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "20.70%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "18.95%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "13.10%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "6.45%" >}}
5. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "3.98%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.69%" >}}
7. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "3.03%" >}}
8. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "2.63%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.36%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.30%" >}}
---

### 3. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 2.26% of new episodes in May, shrinking 3.02% from last month.

Of these, 8.92% had one other tracker, 2.07% had 2 other trackers, 0.50% had 3 other trackers, and 0.02% had 4 other trackers.

9.72% also included Chartable, 3.03% also included Podtrac, 1.35% also included Podsights, 0.23% also included Blubrry, 0.17% also included Magellan AI, 0.09% also included AdBarker, 0.03% also included Adswizz, 0.02% also included Backtracks, and 0.01% also included Podkite.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "55.60%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "17.28%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "6.56%" >}}
4. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "4.79%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "4.09%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.33%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.22%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.66%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.36%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.00%" >}}
---

### 4. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 1.58% of new episodes in May, growing 6.11% from last month.

Of these, 29.46% had one other tracker, 7.90% had 3 other trackers, 4.40% had 2 other trackers, and 0.02% had 4 other trackers.

29.91% also included Podtrac, 20.32% also included Chartable, 11.56% also included Podsights, 0.21% also included Blubrry, and 0.05% also included Podcorn.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "25.37%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "21.78%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "14.92%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.38%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "8.54%" >}}
6. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "7.19%" >}}
7. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "7.11%" >}}
8. {{< a "https://www.bbc.co.uk/" "BBC" >}} {{< span "weak" "2.68%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.27%" >}}
10. {{< a "https://www.washingtonpost.com/" "The Washington Post" >}} {{< span "weak" "0.28%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.48% of new episodes in May, shrinking 4.06% from last month.

Of these, 4.26% had one other tracker, 0.90% had 2 other trackers, 0.04% had 4 other trackers, and 0.01% had 3 other trackers.

3.21% also included Podtrac, 1.45% also included Chartable, 0.85% also included Feedpress, 0.35% also included Podcorn, 0.22% also included Adswizz, and 0.15% also included Podsights.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "77.91%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "4.74%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "2.73%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.35%" >}}
5. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.52%" >}}
6. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.19%" >}}
7. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.03%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.03%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.81%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.77%" >}}
---

### 6. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.41% of new episodes in May, growing 5.90% from last month.

Of these, 60.06% had 2 other trackers, 20.18% had one other tracker, 9.63% had 3 other trackers, and 0.02% had 4 other trackers.

82.83% also included Chartable, 70.70% also included Podtrac, 12.96% also included Adswizz, 2.16% also included Podcorn, 0.45% also included Magellan AI, 0.16% also included Blubrry, and 0.02% also included AdBarker.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "36.12%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "34.03%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "11.16%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.48%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.35%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.51%" >}}
7. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.65%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.41%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.13%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.73%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.56% of new episodes in May, growing 10.27% from last month.

Of these, 0.01% had one other tracker.

0.01% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "37.41%" >}}
2. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "29.80%" >}}
3. {{< a "https://www.streamakaci.com/" "Streamakaci" >}} {{< span "weak" "27.50%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "0.92%" >}}
---

### 8. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.17% of new episodes in May, growing 7.88% from last month.

Of these, 13.08% had one other tracker, and 0.07% had 2 other trackers.

7.35% also included Blubrry, 3.44% also included Podtrac, and 2.42% also included Chartable.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "62.07%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "11.32%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.26%" >}}
4. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "5.23%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.87%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.32%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.09%" >}}
8. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.62%" >}}
9. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "1.09%" >}}
10. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "1.03%" >}}
---

### 9. [Firstory](https://firstory.me/)

Firstory was found on 0.10% of new episodes in May, growing 3.52% from last month.

Of these, 64.77% had one other tracker, and 0.29% had 2 other trackers.

65.06% also included Chartable, and 0.29% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.53%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.47%" >}}
---

### 10. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.02% of new episodes in May, growing 10.61% from last month.

Of these, 57.10% had 2 other trackers, and 19.56% had one other tracker.

72.87% also included Chartable, 35.65% also included Podsights, 21.45% also included Podcorn, and 3.79% also included Podtrac.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.44%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "33.44%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "19.87%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.46%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.79%" >}}
---

### 11. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.01% of new episodes in May, shrinking 1.44% from last month.

Of these, 53.43% had one other tracker, and 1.96% had 2 other trackers.

36.27% also included Podtrac, 17.65% also included Chartable, and 3.43% also included Podcorn.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "31.37%" >}}
2. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "30.39%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "12.25%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.43%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.94%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.45%" >}}
7. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "1.96%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.96%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.47%" >}}
10. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.98%" >}}
---

### 12. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in May, shrinking 9.33% from last month.

Of these, 66.67% had 2 other trackers, 6.67% had one other tracker, and 2.50% had 3 other trackers.

67.50% also included Chartable, 45.00% also included Podtrac, 30.83% also included Podcorn, and 4.17% also included Podsights.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "36.67%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "33.33%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "14.17%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "7.50%" >}}
5. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "3.33%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.33%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.67%" >}}
---

### 13. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on <0.01% of new episodes in May, growing 21.18% from last month.

Of these, 26.83% had one other tracker, and 2.44% had 2 other trackers.

24.39% also included Chartable, 4.88% also included Podcorn, and 2.44% also included Podtrac.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "36.59%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "29.27%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "14.63%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "12.20%" >}}
5. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "2.44%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.44%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.44%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2022-05.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
