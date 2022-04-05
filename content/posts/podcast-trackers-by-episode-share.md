---
title: "Top Podcast Tracking Services by Episode Share (March 2022)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2022-03.png
date: 2022-04-03T17:34:00-05:00
lastmod: 2022-04-05T11:51:00-05:00
draft: false
rssrevision: 2022-03
---

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

We already did the work of analyzing _every single new podcast episode published_ (about 1.8 million in March 2022), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in March, how many
of them included one or more of these tracking services?  Some episodes had as many as *five* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Chartable	Podtrac	Podcorn	Blubrry	Adswizz	Podsights	Médiamétrie	Feedpress	FeedBurner
Sep 2021	4.06	4.16	2.09	2.07	1.00	1.16	0.42	0.32	1.61
Oct 2021	4.09	4.05	2.13	2.11	1.01	1.20	0.54	0.34	1.61
Nov 2021	4.30	4.07	2.14	2.01	1.02	1.25	0.57	0.32	0.59
Dec 2021	4.42	4.06	2.27	1.57	1.24	1.19	0.59	0.19	
Jan 2022	4.45	4.11	2.31	1.56	1.41	1.21	0.63	0.16	
Feb 2022	4.48	4.15	2.38	1.53	1.44	1.25	0.58	0.17	
Mar 2022	4.72	4.37	2.40	1.56	1.51	1.34	0.53	0.17	
{{< /graph >}}

---

### Overall

At least one tracker was found on 12.65% of new episodes in March, growing 1.40% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "12.73%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.95%" >}}
3. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "9.56%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.59%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.80%" >}}
6. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "5.00%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.89%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "4.34%" >}}
9. {{< a "https://analytics.podtrac.com/" "Podtrac" >}} {{< span "weak" "4.01%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.59%" >}}
---

### [Spotify (Chartable & Podsights)](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/)

At least one Spotify tracker was found on 4.94% of new episodes in March, growing 3.10% from last month.

Of these, 37.42% also included Podtrac, 6.64% also included Adswizz, 5.09% also included Podcorn, 1.17% also included Firstory, 0.51% also included Blubrry, 0.25% also included Magellan AI, 0.12% also included AdBarker, 0.04% also included Backtracks, 0.03% also included Feedpress, and <0.01% also included Podkite.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "26.06%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.30%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "8.15%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.08%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.90%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.36%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.55%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.43%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.92%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.74%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of March 2022.

---

### 1. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 4.72% of new episodes in March, growing 3.28% from last month.

Of these, 29.27% had one other tracker, 18.53% had 2 other trackers, 2.88% had 3 other trackers, and 0.01% had 4 other trackers.

37.33% also included Podtrac, 23.78% also included Podsights, 6.77% also included Adswizz, 4.99% also included Podcorn, 1.23% also included Firstory, 0.48% also included Blubrry, 0.25% also included Magellan AI, 0.12% also included AdBarker, 0.04% also included Backtracks, 0.03% also included Feedpress, and <0.01% also included Podkite.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "25.08%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.44%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "8.50%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.09%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.73%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.56%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.69%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.36%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.02%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.87%" >}}
---

### 2. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 4.37% of new episodes in March, growing 2.88% from last month.

Of these, 28.58% had one other tracker, 19.29% had 2 other trackers, 3.12% had 3 other trackers, and 0.01% had 4 other trackers.

40.39% also included Chartable, 22.72% also included Podsights, 10.29% also included Adswizz, 1.58% also included Podcorn, 1.18% also included Blubrry, 0.16% also included Feedpress, 0.11% also included Backtracks, 0.07% also included AdBarker, 0.05% also included Magellan AI, and 0.01% also included Firstory.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "24.28%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "15.06%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "14.46%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "6.81%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.95%" >}}
6. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "3.71%" >}}
7. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "2.91%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.75%" >}}
9. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "2.59%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.26%" >}}
---

### 3. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 2.40% of new episodes in March, shrinking 1.11% from last month.

Of these, 9.04% had one other tracker, 2.07% had 2 other trackers, 0.44% had 3 other trackers, and 0.02% had 4 other trackers.

9.81% also included Chartable, 2.88% also included Podtrac, 1.25% also included Podsights, 0.31% also included Blubrry, 0.15% also included Magellan AI, 0.10% also included AdBarker, 0.06% also included Adswizz, and 0.03% also included Backtracks.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "60.45%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "13.27%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "5.83%" >}}
4. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "4.29%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.98%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.52%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.31%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.70%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.39%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.15%" >}}
---

### 4. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.56% of new episodes in March, shrinking 1.09% from last month.

Of these, 4.24% had one other tracker, 0.91% had 2 other trackers, 0.03% had 3 other trackers, and 0.02% had 4 other trackers.

3.30% also included Podtrac, 1.45% also included Chartable, 0.71% also included Feedpress, 0.48% also included Podcorn, 0.19% also included Podsights, 0.10% also included Adswizz, and <0.01% also included Backtracks.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "77.49%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "5.13%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "2.77%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.43%" >}}
5. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.43%" >}}
6. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.36%" >}}
7. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.18%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.98%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.93%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "0.90%" >}}
---

### 5. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 1.51% of new episodes in March, growing 2.26% from last month.

Of these, 31.45% had one other tracker, 8.32% had 3 other trackers, 3.89% had 2 other trackers, and <0.01% had 4 other trackers.

29.85% also included Podtrac, 21.25% also included Chartable, 11.48% also included Podsights, 1.45% also included Médiamétrie, 0.10% also included Blubrry, and 0.09% also included Podcorn.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "26.17%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "21.76%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "13.90%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.16%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "8.98%" >}}
6. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "7.40%" >}}
7. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "7.20%" >}}
8. {{< a "https://www.bbc.co.uk/" "BBC" >}} {{< span "weak" "2.67%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.35%" >}}
10. {{< a "https://www.washingtonpost.com/" "The Washington Post" >}} {{< span "weak" "0.31%" >}}
---

### 6. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.34% of new episodes in March, growing 5.41% from last month.

Of these, 61.76% had 2 other trackers, 19.14% had one other tracker, 10.09% had 3 other trackers, and 0.03% had 4 other trackers.

83.62% also included Chartable, 73.82% also included Podtrac, 12.86% also included Adswizz, 2.23% also included Podcorn, 0.25% also included Magellan AI, 0.22% also included Blubrry, and 0.01% also included Backtracks.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "35.87%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "33.82%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "12.49%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.58%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.97%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.01%" >}}
7. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.78%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.41%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.96%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.90%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.53% of new episodes in March, shrinking 10.62% from last month.

Of these, 4.14% had one other tracker.

4.14% also included Adswizz.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "38.65%" >}}
2. {{< a "https://www.streamakaci.com/" "Streamakaci" >}} {{< span "weak" "30.40%" >}}
3. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "25.49%" >}}
4. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "4.14%" >}}
5. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "1.00%" >}}
---

### 8. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.17% of new episodes in March, shrinking 1.22% from last month.

Of these, 11.26% had one other tracker, and 0.07% had 2 other trackers.

6.48% also included Blubrry, 4.00% also included Podtrac, and 0.91% also included Chartable.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "60.85%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "12.89%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.92%" >}}
4. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "4.91%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.38%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.15%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.02%" >}}
8. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.56%" >}}
9. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "1.30%" >}}
10. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.94%" >}}
---

### 9. [Firstory](https://firstory.me/)

Firstory was found on 0.09% of new episodes in March, growing 12.76% from last month.

Of these, 64.98% had one other tracker, and 0.25% had 2 other trackers.

65.24% also included Chartable, and 0.25% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "98.93%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.50%" >}}
---

### 10. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.02% of new episodes in March, growing 5.07% from last month.

Of these, 50.34% had 2 other trackers, and 28.08% had one other tracker.

73.63% also included Chartable, 21.92% also included Podcorn, 20.89% also included Podsights, and 12.33% also included Podtrac.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "46.92%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "32.19%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.90%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.51%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.74%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.74%" >}}
---

### 11. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.01% of new episodes in March, growing 3.47% from last month.

Of these, 53.05% had one other tracker, 2.35% had 2 other trackers, 0.94% had 4 other trackers, and 0.47% had 3 other trackers.

39.91% also included Podtrac, 15.49% also included Chartable, 6.10% also included Podcorn, 0.94% also included Podsights, and 0.47% also included Blubrry.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "31.92%" >}}
2. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "25.82%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "7.04%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.63%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.16%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "4.23%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.35%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.41%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.41%" >}}
10. {{< a "https://www.whooshkaa.com/" "Whooshkaa" >}} {{< span "weak" "0.94%" >}}
---

### 12. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in March, growing 8.91% from last month.

Of these, 59.86% had 2 other trackers, 7.04% had one other tracker, and 6.34% had 3 other trackers.

73.24% also included Chartable, 40.85% also included Podtrac, and 31.69% also included Podcorn.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "34.51%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "30.99%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "19.72%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "6.34%" >}}
5. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "3.52%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.82%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.11%" >}}
---

### 13. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on <0.01% of new episodes in March, growing 146.41% from last month.

Of these, 3.23% had one other tracker.

3.23% also included Chartable.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "51.61%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "22.58%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "19.35%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "6.45%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
 - [Podcast Tracker Rankings by Episode Share (February 2022)](/archive/podcast-trackers-by-episode-share-february-2022/)
 - [Podcast Tracker Rankings by Episode Share (January 2022)](/archive/podcast-trackers-by-episode-share-january-2022/)
 - [Podcast Tracker Rankings by Episode Share (December 2021)](/archive/podcast-trackers-by-episode-share-december-2021/)
 - [Podcast Tracker Rankings by Episode Share (November 2021)](/archive/podcast-trackers-by-episode-share-november-2021/)
 - [Podcast Tracker Rankings by Episode Share (October 2021)](/archive/podcast-trackers-by-episode-share-october-2021/)
 - [Podcast Tracker Rankings by Episode Share (September 2021)](/archive/podcast-trackers-by-episode-share-september-2021/)

{{% funding %}}

---
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/podcast-trackers-by-episode-share.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
