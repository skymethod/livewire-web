---
title: "Top Podcast Tracking Services by Episode Share (April 2022)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-april-2022"
images:
- trackers-2022-04.png
date: 2022-05-01T12:54:00-05:00
lastmod: 2022-05-01T12:54:00-05:00
draft: false
rssrevision: 2022-04
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.8 million in April 2022), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in April, how many
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
Apr 2022	4.71	4.44	2.33	1.55	1.49	1.33	0.51	0.16	
{{< /graph >}}

---

### Overall

At least one tracker was found on 12.60% of new episodes in April, shrinking 0.45% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.56%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.24%" >}}
3. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "9.57%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.53%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.56%" >}}
6. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "5.10%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.77%" >}}
8. {{< a "https://analytics.podtrac.com/" "Podtrac" >}} {{< span "weak" "4.34%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "4.19%" >}}
10. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "3.17%" >}}
---

### [Spotify (Chartable & Podsights)](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/)

At least one Spotify tracker was found on 4.92% of new episodes in April, shrinking 0.48% from last month.

Of these, 38.36% also included Podtrac, 6.31% also included Adswizz, 4.74% also included Podcorn, 1.24% also included Firstory, 0.48% also included Blubrry, 0.24% also included Magellan AI, 0.11% also included AdBarker, 0.06% also included Feedpress, 0.04% also included Backtracks, and 0.02% also included Podkite.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "24.11%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.12%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "8.28%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.89%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.68%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.82%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.34%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.28%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.94%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.74%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of April 2022.

---

### 1. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 4.71% of new episodes in April, shrinking 0.31% from last month.

Of these, 30.07% had one other tracker, 18.41% had 2 other trackers, 2.86% had 3 other trackers, and 0.01% had 4 other trackers.

38.41% also included Podtrac, 23.86% also included Podsights, 6.40% also included Adswizz, 4.63% also included Podcorn, 1.29% also included Firstory, 0.44% also included Blubrry, 0.24% also included Magellan AI, 0.12% also included AdBarker, 0.06% also included Feedpress, 0.04% also included Backtracks, and 0.02% also included Podkite.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.03%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.43%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "8.61%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.08%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.33%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.99%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.47%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.23%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.05%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.86%" >}}
---

### 2. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 4.44% of new episodes in April, growing 1.61% from last month.

Of these, 29.11% had one other tracker, 18.81% had 2 other trackers, 3.04% had 3 other trackers, and 0.01% had 4 other trackers.

40.78% also included Chartable, 22.02% also included Podsights, 10.12% also included Adswizz, 1.51% also included Podcorn, 1.12% also included Blubrry, 0.13% also included Feedpress, 0.09% also included Backtracks, 0.09% also included AdBarker, 0.03% also included Magellan AI, 0.01% also included Firstory, and <0.01% also included Médiamétrie.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "21.37%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "18.32%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "13.70%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "6.53%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.74%" >}}
6. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "3.71%" >}}
7. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "3.05%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.63%" >}}
9. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "2.62%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.16%" >}}
---

### 3. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 2.33% of new episodes in April, shrinking 2.91% from last month.

Of these, 8.57% had one other tracker, 2.00% had 2 other trackers, 0.47% had 3 other trackers, and 0.02% had 4 other trackers.

9.35% also included Chartable, 2.87% also included Podtrac, 1.26% also included Podsights, 0.27% also included Blubrry, 0.16% also included Magellan AI, 0.10% also included AdBarker, 0.04% also included Adswizz, and 0.02% also included Backtracks.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "56.37%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "17.08%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "6.10%" >}}
4. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "4.58%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.93%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.42%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.22%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.67%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.43%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.07%" >}}
---

### 4. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.55% of new episodes in April, shrinking 0.78% from last month.

Of these, 4.17% had one other tracker, 0.82% had 2 other trackers, 0.04% had 4 other trackers, and <0.01% had 3 other trackers.

3.20% also included Podtrac, 1.35% also included Chartable, 0.72% also included Feedpress, 0.40% also included Podcorn, 0.18% also included Podsights, and 0.12% also included Adswizz.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "77.79%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "4.75%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "2.76%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.37%" >}}
5. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.36%" >}}
6. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.30%" >}}
7. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.20%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.03%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.95%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.85%" >}}
---

### 5. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 1.49% of new episodes in April, shrinking 0.91% from last month.

Of these, 29.16% had one other tracker, 8.30% had 3 other trackers, 3.88% had 2 other trackers, and 0.02% had 4 other trackers.

30.10% also included Podtrac, 20.21% also included Chartable, 11.42% also included Podsights, 0.13% also included Blubrry, and 0.06% also included Podcorn.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "26.08%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "22.72%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "14.15%" >}}
4. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "9.03%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.41%" >}}
6. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "7.31%" >}}
7. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "7.23%" >}}
8. {{< a "https://www.bbc.co.uk/" "BBC" >}} {{< span "weak" "2.79%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.29%" >}}
10. {{< a "https://hubhopper.com/" "Hubhopper" >}} {{< span "weak" "0.35%" >}}
---

### 6. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.33% of new episodes in April, shrinking 0.66% from last month.

Of these, 61.73% had 2 other trackers, 19.16% had one other tracker, 10.06% had 3 other trackers, and 0.02% had 4 other trackers.

84.21% also included Chartable, 73.20% also included Podtrac, 12.76% also included Adswizz, 2.20% also included Podcorn, 0.30% also included Magellan AI, and 0.21% also included Blubrry.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "35.68%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "33.81%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "11.95%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.62%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.44%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.43%" >}}
7. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.68%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.38%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.86%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.71%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.51% of new episodes in April, shrinking 4.16% from last month.

Of these, 0.01% had one other tracker.

0.01% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "39.33%" >}}
2. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "30.13%" >}}
3. {{< a "https://www.streamakaci.com/" "Streamakaci" >}} {{< span "weak" "29.39%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "0.76%" >}}
---

### 8. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.16% of new episodes in April, shrinking 7.44% from last month.

Of these, 12.11% had one other tracker, and 0.07% had 2 other trackers.

6.96% also included Blubrry, 3.52% also included Podtrac, and 1.78% also included Chartable.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "63.09%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "11.40%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.68%" >}}
4. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "4.76%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.45%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.10%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.71%" >}}
8. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.56%" >}}
9. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "1.35%" >}}
10. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "1.17%" >}}
---

### 9. [Firstory](https://firstory.me/)

Firstory was found on 0.09% of new episodes in April, growing 5.57% from last month.

Of these, 64.73% had one other tracker, and 0.24% had 2 other trackers.

64.98% also included Chartable, and 0.24% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.34%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.48%" >}}
---

### 10. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.02% of new episodes in April, shrinking 0.34% from last month.

Of these, 49.31% had 2 other trackers, and 25.35% had one other tracker.

70.14% also included Chartable, 24.31% also included Podsights, 22.22% also included Podcorn, and 7.29% also included Podtrac.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "40.63%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "31.60%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "12.50%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.38%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.51%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.39%" >}}
---

### 11. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.01% of new episodes in April, shrinking 1.33% from last month.

Of these, 50.96% had one other tracker, and 1.92% had 2 other trackers.

35.58% also included Podtrac, 15.87% also included Chartable, and 3.37% also included Podcorn.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "31.73%" >}}
2. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "28.37%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "11.54%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.85%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.37%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.88%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.40%" >}}
8. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.44%" >}}
9. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "0.96%" >}}
10. {{< a "https://www.whooshkaa.com/" "Whooshkaa" >}} {{< span "weak" "0.96%" >}}
---

### 12. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in April, shrinking 5.36% from last month.

Of these, 66.92% had 2 other trackers, 6.77% had 3 other trackers, and 3.76% had one other tracker.

74.44% also included Chartable, 51.88% also included Podtrac, and 31.58% also included Podcorn.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "39.10%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "30.83%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "18.05%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "4.51%" >}}
5. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "3.01%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.01%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.50%" >}}
---

### 13. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on <0.01% of new episodes in April, growing 10.82% from last month.

Of these, 41.18% had one other tracker.

41.18% also included Chartable.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "44.12%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "23.53%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "17.65%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "14.71%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
 - [Podcast Tracker Rankings by Episode Share (March 2022)](/archive/podcast-trackers-by-episode-share-march-2022/)
 - [Podcast Tracker Rankings by Episode Share (February 2022)](/archive/podcast-trackers-by-episode-share-february-2022/)
 - [Podcast Tracker Rankings by Episode Share (January 2022)](/archive/podcast-trackers-by-episode-share-january-2022/)
 - [Podcast Tracker Rankings by Episode Share (December 2021)](/archive/podcast-trackers-by-episode-share-december-2021/)
 - [Podcast Tracker Rankings by Episode Share (November 2021)](/archive/podcast-trackers-by-episode-share-november-2021/)
 - [Podcast Tracker Rankings by Episode Share (October 2021)](/archive/podcast-trackers-by-episode-share-october-2021/)
 - [Podcast Tracker Rankings by Episode Share (September 2021)](/archive/podcast-trackers-by-episode-share-september-2021/)

{{% funding %}}

---
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2022-04.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
