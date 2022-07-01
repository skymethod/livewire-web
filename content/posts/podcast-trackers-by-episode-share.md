---
title: "Top Podcast Tracking Services by Episode Share (June 2022)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2022-06.png
date: 2022-06-30-T20:32:00-05:00
lastmod: 2022-06-30-T20:32:00-05:00
draft: false
rssrevision: 2022-06
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.6 million in June 2022), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in June, how many
of them included one or more of these tracking services?  Some episodes had as many as *five* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Chartable	Podtrac	Podcorn	Adswizz	Podsights	Blubrry	Médiamétrie	Feedpress	Zippycast	FeedBurner
Sep 2021	4.06	4.16	2.09	1.00	1.16	2.07	0.42	0.32		1.61
Oct 2021	4.09	4.05	2.13	1.01	1.20	2.11	0.54	0.34		1.61
Nov 2021	4.30	4.07	2.14	1.02	1.25	2.01	0.57	0.32		0.59
Dec 2021	4.42	4.06	2.27	1.24	1.19	1.57	0.59	0.19		
Jan 2022	4.45	4.11	2.31	1.41	1.21	1.56	0.63	0.16		
Feb 2022	4.48	4.15	2.38	1.44	1.25	1.53	0.58	0.17		
Mar 2022	4.72	4.37	2.40	1.51	1.34	1.56	0.53	0.17		
Apr 2022	4.71	4.44	2.33	1.49	1.33	1.55	0.51	0.16		
May 2022	4.87	4.49	2.26	1.58	1.41	1.48	0.56	0.17		
Jun 2022	5.10	4.75	2.06	1.77	1.54	1.50	0.62	0.21	0.02	
{{< /graph >}}

---

### Overall

At least one tracker was found on 13.22% of new episodes in June, growing 3.23% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.46%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.65%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "10.29%" >}}
4. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "8.87%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.49%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.10%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.91%" >}}
8. {{< a "https://analytics.podtrac.com/" "Podtrac" >}} {{< span "weak" "4.48%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "4.10%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.93%" >}}
---

### [Spotify (Chartable & Podsights)](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/)

At least one Spotify tracker was found on 5.37% of new episodes in June, growing 5.05% from last month.

Of these, 38.65% also included Podtrac, 6.52% also included Adswizz, 4.53% also included Podcorn, 1.23% also included Firstory, 0.49% also included Blubrry, 0.27% also included Magellan AI, 0.08% also included AdBarker, 0.07% also included Feedpress, 0.05% also included Zippycast, 0.03% also included Backtracks, and 0.02% also included Podkite.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.78%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.96%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.68%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.85%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.71%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.62%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.29%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.09%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.70%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.69%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of June 2022.

---

### 1. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.10% of new episodes in June, growing 4.64% from last month.

Of these, 31.12% had one other tracker, 18.58% had 2 other trackers, 2.89% had 3 other trackers, 0.02% had 4 other trackers, and <0.01% had 5 other trackers.

38.81% also included Podtrac, 24.91% also included Podsights, 6.64% also included Adswizz, 4.42% also included Podcorn, 1.30% also included Firstory, 0.49% also included Blubrry, 0.28% also included Magellan AI, 0.08% also included AdBarker, 0.07% also included Feedpress, 0.03% also included Backtracks, 0.03% also included Podkite, and <0.01% also included Zippycast.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "22.62%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "21.26%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.02%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.88%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.47%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.80%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.31%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.24%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.84%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.81%" >}}
---

### 2. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 4.75% of new episodes in June, growing 5.85% from last month.

Of these, 30.43% had one other tracker, 19.03% had 2 other trackers, 3.10% had 3 other trackers, 0.02% had 4 other trackers, and 0.01% had 5 other trackers.

41.63% also included Chartable, 22.56% also included Podsights, 10.70% also included Adswizz, 1.56% also included Podcorn, 1.06% also included Blubrry, 0.11% also included Feedpress, 0.09% also included Backtracks, 0.06% also included Zippycast, 0.06% also included AdBarker, 0.03% also included Magellan AI, 0.02% also included Médiamétrie, 0.01% also included Firstory, and <0.01% also included Podkite.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "20.70%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "18.91%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "13.27%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "6.35%" >}}
5. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "4.27%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.76%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.92%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.54%" >}}
9. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "2.49%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.34%" >}}
---

### 3. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 2.06% of new episodes in June, shrinking 8.87% from last month.

Of these, 10.10% had one other tracker, 2.43% had 2 other trackers, 0.58% had 3 other trackers, 0.03% had 4 other trackers, and 0.01% had 5 other trackers.

10.91% also included Chartable, 3.60% also included Podtrac, 1.62% also included Podsights, 0.35% also included Blubrry, 0.20% also included Magellan AI, 0.10% also included AdBarker, 0.05% also included Adswizz, 0.02% also included Podkite, and 0.01% also included Backtracks.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "58.77%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "10.86%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.33%" >}}
4. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "5.24%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "4.34%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.66%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.57%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.01%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.68%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.07%" >}}
---

### 4. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 1.77% of new episodes in June, growing 10.13% from last month.

Of these, 27.92% had one other tracker, 7.59% had 3 other trackers, 4.24% had 2 other trackers, and 0.03% had 4 other trackers.

28.75% also included Podtrac, 19.12% also included Chartable, 11.16% also included Podsights, 0.19% also included Blubrry, and 0.06% also included Podcorn.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "25.36%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "21.86%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "13.58%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.14%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "8.04%" >}}
6. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "6.80%" >}}
7. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "6.48%" >}}
8. {{< a "https://www.bbc.co.uk/" "BBC" >}} {{< span "weak" "2.54%" >}}
9. {{< a "https://kostenlos-hosten.de/" "Podcastbude" >}} {{< span "weak" "1.35%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.19%" >}}
---

### 5. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.54% of new episodes in June, growing 9.34% from last month.

Of these, 58.74% had 2 other trackers, 21.23% had one other tracker, 9.52% had 3 other trackers, 0.03% had 4 other trackers, and 0.02% had 5 other trackers.

82.19% also included Chartable, 69.41% also included Podtrac, 12.79% also included Adswizz, 2.17% also included Podcorn, 0.45% also included Magellan AI, 0.25% also included Blubrry, 0.16% also included Zippycast, and 0.03% also included AdBarker.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "36.07%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "32.61%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "11.32%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.92%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.84%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.51%" >}}
7. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.55%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.37%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.16%" >}}
10. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.72%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.50% of new episodes in June, growing 1.25% from last month.

Of these, 4.35% had one other tracker, 0.90% had 2 other trackers, 0.12% had 3 other trackers, 0.05% had 4 other trackers, and 0.02% had 5 other trackers.

3.35% also included Podtrac, 1.65% also included Chartable, 0.83% also included Feedpress, 0.48% also included Podcorn, 0.26% also included Podsights, 0.22% also included Adswizz, 0.02% also included AdBarker, and 0.01% also included Backtracks.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "78.08%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "4.71%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.45%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.38%" >}}
5. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.43%" >}}
6. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.15%" >}}
7. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.12%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.85%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.79%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.72%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.62% of new episodes in June, growing 11.41% from last month.

Of these, 0.18% had one other tracker.

0.18% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "34.95%" >}}
2. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "27.23%" >}}
3. {{< a "https://www.streamakaci.com/" "Streamakaci" >}} {{< span "weak" "26.03%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "3.02%" >}}
---

### 8. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.21% of new episodes in June, growing 21.19% from last month.

Of these, 10.17% had one other tracker, and 0.03% had 2 other trackers.

5.96% also included Blubrry, 2.57% also included Podtrac, and 1.69% also included Chartable.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "69.78%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.12%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.92%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "3.92%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.89%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.72%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.64%" >}}
8. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.34%" >}}
9. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "1.05%" >}}
10. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.96%" >}}
---

### 9. [Firstory](https://firstory.me/)

Firstory was found on 0.10% of new episodes in June, growing 7.81% from last month.

Of these, 63.06% had one other tracker, and 0.23% had 2 other trackers.

63.29% also included Chartable, and 0.23% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.53%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.47%" >}}
---

### 10. [Zippycast](https://zippycast.io/)

Zippycast was found on 0.02% of new episodes in June, growing 24.69% from last month.

Of these, 12.93% had 2 other trackers, and 2.21% had one other tracker.

13.88% also included Podtrac, 12.93% also included Podsights, and 1.26% also included Chartable.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "42.27%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "21.14%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "17.35%" >}}
4. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "10.41%" >}}
5. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "7.57%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.63%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.32%" >}}
8. {{< a "https://podcloud.fr/" "podCloud" >}} {{< span "weak" "0.32%" >}}
---

### 11. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.02% of new episodes in June, growing 4.97% from last month.

Of these, 60.77% had 2 other trackers, and 18.01% had one other tracker.

74.28% also included Chartable, 36.66% also included Podsights, 21.54% also included Podcorn, and 7.07% also included Podtrac.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "35.37%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "33.12%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "19.29%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.04%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.18%" >}}
---

### 12. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.01% of new episodes in June, shrinking 7.17% from last month.

Of these, 54.80% had one other tracker, 1.13% had 3 other trackers, and 0.56% had 2 other trackers.

39.55% also included Podtrac, 15.82% also included Chartable, 2.82% also included Podcorn, and 1.13% also included Blubrry.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "37.85%" >}}
2. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "33.90%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.91%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.39%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.82%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.13%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.13%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.13%" >}}
---

### 13. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in June, growing 0.75% from last month.

Of these, 56.64% had 2 other trackers, 8.85% had one other tracker, and 3.54% had 5 other trackers.

61.95% also included Chartable, 38.05% also included Podtrac, 29.20% also included Podcorn, 7.08% also included Podsights, and 3.54% also included Blubrry.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "30.97%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "30.09%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "15.93%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "11.50%" >}}
5. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "6.19%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.54%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.77%" >}}
---

### 14. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on <0.01% of new episodes in June, growing 72.23% from last month.

Of these, 39.39% had one other tracker, and 3.03% had 2 other trackers.

33.33% also included Chartable, 9.09% also included Podcorn, and 3.03% also included Podtrac.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "31.82%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "22.73%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "19.70%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "10.61%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.06%" >}}
6. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "6.06%" >}}
7. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "1.52%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.52%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/podcast-trackers-by-episode-share.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
