---
title: "Top Podcast Tracking Services by Episode Share (July 2022)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2022-07.png
date: 2021-07-31T19:01:00-05:00
lastmod: 2021-07-31T19:01:00-05:00
draft: false
rssrevision: 2022-07
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.5 million in July 2022), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in July, how many
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
Jul 2022	5.10	4.70	2.16	1.89	1.50	1.50	0.54	0.25	0.02	
{{< /graph >}}

---

### Overall

At least one tracker was found on 13.37% of new episodes in July, growing 0.73% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.63%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.10%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "10.39%" >}}
4. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "8.66%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.44%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.12%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.79%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.99%" >}}
9. {{< a "https://analytics.podtrac.com/" "Podtrac" >}} {{< span "weak" "2.93%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.81%" >}}
---

### [Spotify (Chartable & Podsights)](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/)

At least one Spotify tracker was found on 5.41% of new episodes in July, growing 0.68% from last month.

Of these, 38.30% also included Podtrac, 6.08% also included Adswizz, 4.65% also included Podcorn, 1.28% also included Firstory, 0.53% also included Blubrry, 0.27% also included Magellan AI, 0.08% also included AdBarker, 0.07% also included Zippycast, 0.04% also included Feedpress, 0.04% also included Backtracks, and 0.02% also included Podkite.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "24.31%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.94%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.57%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.62%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.47%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.87%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.93%" >}}
8. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.87%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.74%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.69%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of July 2022.

---

### 1. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.10% of new episodes in July, shrinking 0.03% from last month.

Of these, 31.50% had one other tracker, 17.75% had 2 other trackers, 2.65% had 3 other trackers, 0.02% had 4 other trackers, and 0.01% had 5 other trackers.

38.77% also included Podtrac, 23.24% also included Podsights, 6.19% also included Adswizz, 4.55% also included Podcorn, 1.36% also included Firstory, 0.49% also included Blubrry, 0.28% also included Magellan AI, 0.08% also included AdBarker, 0.04% also included Feedpress, 0.04% also included Backtracks, 0.02% also included Podkite, and 0.01% also included Zippycast.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.26%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "21.26%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.94%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.81%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.15%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.06%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.10%" >}}
8. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "3.05%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.81%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.79%" >}}
---

### 2. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 4.70% of new episodes in July, shrinking 1.16% from last month.

Of these, 32.10% had one other tracker, 18.46% had 2 other trackers, 2.88% had 3 other trackers, 0.02% had 4 other trackers, and 0.01% had 5 other trackers.

42.06% also included Chartable, 21.72% also included Podsights, 10.72% also included Adswizz, 1.60% also included Podcorn, 1.13% also included Blubrry, 0.14% also included Feedpress, 0.13% also included Backtracks, 0.10% also included Zippycast, 0.09% also included Médiamétrie, 0.06% also included AdBarker, 0.04% also included Magellan AI, 0.01% also included Firstory, and <0.01% also included Podkite.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "21.17%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "18.67%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "13.67%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "6.35%" >}}
5. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "4.32%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.30%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.88%" >}}
8. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "2.79%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.60%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.13%" >}}
---

### 3. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 2.16% of new episodes in July, growing 4.39% from last month.

Of these, 9.96% had one other tracker, 2.31% had 2 other trackers, 0.60% had 3 other trackers, 0.04% had 4 other trackers, and 0.01% had 5 other trackers.

10.76% also included Chartable, 3.49% also included Podtrac, 1.68% also included Podsights, 0.30% also included Blubrry, 0.20% also included Magellan AI, 0.09% also included AdBarker, 0.05% also included Adswizz, 0.02% also included Podkite, and 0.02% also included Backtracks.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "57.11%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "13.31%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.95%" >}}
4. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "5.52%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "4.14%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.68%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.60%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.89%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.76%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.96%" >}}
---

### 4. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 1.89% of new episodes in July, growing 3.71% from last month.

Of these, 26.55% had one other tracker, 6.33% had 3 other trackers, 3.83% had 2 other trackers, and 0.03% had 4 other trackers.

26.71% also included Podtrac, 16.73% also included Chartable, 9.56% also included Podsights, 0.20% also included Blubrry, 0.06% also included Podcorn, and 0.03% also included Feedpress.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "25.26%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "19.95%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "15.24%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "13.48%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "6.69%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "6.63%" >}}
7. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "4.59%" >}}
8. {{< a "https://www.bbc.co.uk/" "BBC" >}} {{< span "weak" "2.19%" >}}
9. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.83%" >}}
10. {{< a "https://kostenlos-hosten.de/" "Podcastbude" >}} {{< span "weak" "1.05%" >}}
---

### 5. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.50% of new episodes in July, shrinking 3.06% from last month.

Of these, 58.03% had 2 other trackers, 19.58% had one other tracker, 9.01% had 3 other trackers, 0.06% had 4 other trackers, and 0.02% had 5 other trackers.

79.09% also included Chartable, 68.14% also included Podtrac, 12.03% also included Adswizz, 2.42% also included Podcorn, 0.51% also included Blubrry, 0.48% also included Magellan AI, 0.24% also included Zippycast, 0.04% also included AdBarker, 0.03% also included Backtracks, and 0.01% also included Podkite.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "36.66%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "32.08%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "9.73%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.33%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.05%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.60%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.57%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.38%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.24%" >}}
10. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.98%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.50% of new episodes in July, shrinking 0.49% from last month.

Of these, 4.50% had one other tracker, 0.84% had 2 other trackers, 0.23% had 3 other trackers, 0.05% had 4 other trackers, and 0.02% had 5 other trackers.

3.56% also included Podtrac, 1.67% also included Chartable, 0.74% also included Feedpress, 0.51% also included Podsights, 0.44% also included Podcorn, 0.26% also included Adswizz, and 0.02% also included AdBarker.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "77.41%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "4.85%" >}}
3. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.59%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.44%" >}}
5. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.48%" >}}
6. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.25%" >}}
7. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.13%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.95%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.82%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.72%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.54% of new episodes in July, shrinking 12.39% from last month.

Of these, 0.78% had one other tracker.

0.78% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "37.34%" >}}
2. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "26.77%" >}}
3. {{< a "https://www.streamakaci.com/" "Streamakaci" >}} {{< span "weak" "18.45%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "7.13%" >}}
5. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "6.11%" >}}
6. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "3.59%" >}}
7. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "0.22%" >}}
---

### 8. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.25% of new episodes in July, growing 21.00% from last month.

Of these, 7.90% had one other tracker, and 0.05% had 2 other trackers.

4.38% also included Blubrry, 2.57% also included Podtrac, 0.79% also included Chartable, and 0.25% also included Adswizz.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "76.30%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.47%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.39%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "3.36%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "1.81%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.61%" >}}
7. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.10%" >}}
8. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.79%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.76%" >}}
10. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "0.74%" >}}
---

### 9. [Firstory](https://firstory.me/)

Firstory was found on 0.11% of new episodes in July, growing 3.01% from last month.

Of these, 64.06% had one other tracker, and 0.30% had 2 other trackers.

64.36% also included Chartable, and 0.30% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.64%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.36%" >}}
---

### 10. [Zippycast](https://zippycast.io/)

Zippycast was found on 0.02% of new episodes in July, shrinking 2.46% from last month.

Of these, 19.45% had 2 other trackers, and 6.14% had one other tracker.

24.23% also included Podtrac, 19.45% also included Podsights, and 1.37% also included Chartable.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "27.99%" >}}
2. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "24.57%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.89%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "15.70%" >}}
5. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "6.14%" >}}
6. {{< a "https://podcloud.fr/" "podCloud" >}} {{< span "weak" "1.71%" >}}
---

### 11. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.02% of new episodes in July, shrinking 2.62% from last month.

Of these, 63.41% had 2 other trackers, and 24.74% had one other tracker.

78.40% also included Chartable, 38.68% also included Podsights, 23.69% also included Podcorn, and 10.80% also included Podtrac.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "39.72%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "33.45%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "21.95%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.53%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.35%" >}}
---

### 12. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.01% of new episodes in July, growing 0.76% from last month.

Of these, 66.27% had one other tracker, and 3.55% had 4 other trackers.

54.44% also included Podtrac, 17.75% also included Chartable, 4.73% also included Podcorn, and 3.55% also included Podsights.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "48.52%" >}}
2. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "31.95%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "4.73%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.73%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.78%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.18%" >}}
7. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.59%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.59%" >}}
---

### 13. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in July, shrinking 7.55% from last month.

Of these, 57.58% had 2 other trackers, 9.09% had one other tracker, and 5.05% had 5 other trackers.

62.63% also included Chartable, 42.42% also included Podtrac, 30.30% also included Podcorn, 9.09% also included Podsights, and 5.05% also included Blubrry.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "32.32%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "30.30%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "17.17%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "10.10%" >}}
5. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "4.04%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.04%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.02%" >}}
---

### 14. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on <0.01% of new episodes in July, growing 10.32% from last month.

Of these, 34.78% had one other tracker, 2.90% had 3 other trackers, and 1.45% had 2 other trackers.

27.54% also included Chartable, 11.59% also included Podcorn, 4.35% also included Podtrac, and 2.90% also included Podsights.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "24.64%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "23.19%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "15.94%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.70%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "8.70%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.35%" >}}
7. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "2.90%" >}}
8. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "2.90%" >}}
9. {{< a "http://www.npo.nl/" "Nederlandse Publieke Omroep" >}} {{< span "weak" "2.90%" >}}
10. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "1.45%" >}}


---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/podcast-trackers-by-episode-share.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
