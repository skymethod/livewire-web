---
title: "Top Podcast Tracking Services by Episode Share (November 2022)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2022-11.png
date: 2022-12-01T10:48:00-06:00
lastmod: 2022-12-01T10:48:00-06:00
draft: false
rssrevision: 2022-11
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

{{% subscribe %}}
---

We already did the work of analyzing _every single new podcast episode published_ (about 1.7 million in November 2022), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in November, how many
of them included one or more of these tracking services?  Some episodes had as many as *six* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Chartable	Podcorn	Adswizz	Podsights	Blubrry	Médiamétrie	Feedpress	Podscribe	ArtsAI	Gumball	OP3	Claritas	Zippycast	Zencastr	Podder	Podkite	FeedBurner
Sep 2021	4.16	4.06	2.09	1.00	1.16	2.07	0.42	0.32										1.61
Oct 2021	4.05	4.09	2.13	1.01	1.20	2.11	0.54	0.34										1.61
Nov 2021	4.07	4.30	2.14	1.02	1.25	2.01	0.57	0.32										0.59
Dec 2021	4.06	4.42	2.27	1.24	1.19	1.57	0.59	0.19										
Jan 2022	4.11	4.45	2.31	1.41	1.21	1.56	0.63	0.16										
Feb 2022	4.15	4.48	2.38	1.44	1.25	1.53	0.58	0.17										
Mar 2022	4.37	4.72	2.40	1.51	1.34	1.56	0.53	0.17										
Apr 2022	4.44	4.71	2.33	1.49	1.33	1.55	0.51	0.16										
May 2022	4.49	4.87	2.26	1.58	1.41	1.48	0.56	0.17										
Jun 2022	4.75	5.10	2.06	1.77	1.54	1.50	0.62	0.21						0.02				
Jul 2022	4.70	5.10	2.16	1.89	1.50	1.50	0.54	0.25						0.02				
Aug 2022	4.83	5.26	2.45	2.08	1.73	1.51	0.41	0.20		0.10				0.01				
Sep 2022	7.53	5.40	2.45	2.26	1.74	1.49	0.52	0.21	0.02	0.09	0.02		0.01	0.02			0.01	
Oct 2022	8.24	5.48	2.51	2.35	1.81	1.61	0.50	0.18	0.07	0.10	0.04	0.03	0.02	0.02	0.01		0.01	
Nov 2022	8.11	5.62	2.43	2.37	2.03	1.62	0.50	0.18	0.13	0.10	0.05	0.04	0.03	0.02	0.01	0.01	0.01	
{{< /graph >}}

---

### Overall

At least one tracker was found on 17.68% of new episodes in November, shrinking 0.04% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "22.39%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.85%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.56%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "7.92%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "6.94%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.20%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.75%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "3.24%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.48%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.10%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of November 2022.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 8.11% of new episodes in November, shrinking 1.58% from last month.

Of these, 22.56% had one other tracker, 11.92% had 2 other trackers, 2.13% had 3 other trackers, 0.68% had 4 other trackers, and 0.25% had 5 other trackers.

29.83% also included Chartable, 14.74% also included Podsights, 6.11% also included Adswizz, 1.87% also included Podcorn, 1.16% also included Podscribe, 0.90% also included ArtsAI, 0.60% also included Blubrry, 0.32% also included OP3, 0.31% also included Gumball, 0.23% also included Claritas, 0.20% also included Feedpress, 0.16% also included Magellan AI, 0.12% also included Backtracks, 0.06% also included Médiamétrie, 0.05% also included Veritonic, 0.03% also included Zippycast, 0.03% also included AdBarker, 0.02% also included Podder, 0.01% also included Podkite, <0.01% also included Zencastr, and <0.01% also included Firstory.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "47.78%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "15.54%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.97%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.05%" >}}
5. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.58%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.08%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.97%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.73%" >}}
9. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "1.45%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.30%" >}}
---

### [Spotify (Chartable & Podsights)](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/)

At least one Spotify tracker was found on 6.28% of new episodes in November, growing 5.58% from last month.

Of these, 40.79% also included Podtrac, 8.34% also included Adswizz, 4.60% also included Podcorn, 1.90% also included Podscribe, 1.54% also included ArtsAI, 0.98% also included Firstory, 0.65% also included Gumball, 0.55% also included OP3, 0.50% also included Claritas, 0.46% also included Blubrry, 0.24% also included Magellan AI, 0.07% also included AdBarker, 0.06% also included Veritonic, 0.05% also included Podder, 0.04% also included Backtracks, 0.04% also included Zippycast, 0.04% also included Feedpress, 0.03% also included Zencastr, and 0.02% also included Podkite.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "26.13%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "21.62%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.75%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.46%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.47%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.47%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.77%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.56%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.26%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.26%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.62% of new episodes in November, growing 2.60% from last month.

Of these, 33.87% had one other tracker, 17.93% had 2 other trackers, 3.17% had 3 other trackers, 0.81% had 4 other trackers, and 0.35% had 5 other trackers.

43.06% also included Podtrac, 24.40% also included Podsights, 5.74% also included Adswizz, 4.27% also included Podcorn, 2.04% also included Podscribe, 1.59% also included ArtsAI, 1.10% also included Firstory, 0.55% also included Claritas, 0.43% also included Blubrry, 0.28% also included Gumball, 0.26% also included Magellan AI, 0.20% also included OP3, 0.08% also included AdBarker, 0.07% also included Veritonic, 0.05% also included Podder, 0.04% also included Backtracks, 0.04% also included Feedpress, 0.02% also included Podkite, 0.01% also included Zencastr, and 0.01% also included Zippycast.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "26.69%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "18.24%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.25%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.43%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.88%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.87%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.06%" >}}
8. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.53%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.50%" >}}
10. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "2.49%" >}}
---

### 3. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 2.43% of new episodes in November, shrinking 2.96% from last month.

Of these, 10.46% had one other tracker, 2.29% had 2 other trackers, 1.07% had 3 other trackers, 0.75% had 4 other trackers, and 0.18% had 5 other trackers.

9.87% also included Chartable, 6.23% also included Podtrac, 2.87% also included Podsights, 1.15% also included Gumball, 1.14% also included OP3, 0.20% also included Blubrry, 0.16% also included Magellan AI, 0.12% also included Adswizz, 0.12% also included Backtracks, 0.10% also included AdBarker, 0.09% also included Podscribe, 0.05% also included Podkite, 0.03% also included Podder, and 0.02% also included Zencastr.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "50.26%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "23.46%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.58%" >}}
4. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "4.80%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.58%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.81%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.31%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.29%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.26%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.92%" >}}
---

### 4. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.37% of new episodes in November, growing 0.83% from last month.

Of these, 29.66% had one other tracker, 4.24% had 3 other trackers, 3.41% had 2 other trackers, 0.65% had 4 other trackers, and 0.07% had 5 other trackers.

20.92% also included Podtrac, 15.09% also included Podsights, 13.63% also included Chartable, 1.29% also included Blubrry, 0.41% also included ArtsAI, 0.30% also included Podscribe, 0.30% also included Claritas, 0.12% also included Podcorn, 0.03% also included Gumball, 0.02% also included Podder, and 0.01% also included Veritonic.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "29.62%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "15.68%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "12.04%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "9.28%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "8.90%" >}}
6. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "5.43%" >}}
7. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.81%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.88%" >}}
9. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "1.83%" >}}
10. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.64%" >}}
---

### 5. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.03% of new episodes in November, growing 12.09% from last month.

Of these, 45.51% had 2 other trackers, 27.46% had one other tracker, 8.62% had 3 other trackers, 2.97% had 4 other trackers, and 0.99% had 5 other trackers.

67.43% also included Chartable, 58.79% also included Podtrac, 17.57% also included Adswizz, 4.59% also included Podscribe, 3.80% also included ArtsAI, 3.44% also included Podcorn, 1.83% also included Gumball, 1.32% also included OP3, 1.31% also included Claritas, 0.35% also included Blubrry, 0.33% also included Magellan AI, 0.12% also included Zippycast, 0.11% also included Zencastr, 0.06% also included Veritonic, 0.06% also included Backtracks, 0.03% also included Podkite, 0.02% also included Podder, and 0.01% also included AdBarker.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "39.44%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "35.11%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "5.64%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.39%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.90%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.82%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.02%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.68%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.03%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.80%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.62% of new episodes in November, growing 1.07% from last month.

Of these, 5.82% had one other tracker, 0.76% had 2 other trackers, 0.11% had 4 other trackers, 0.08% had 3 other trackers, and 0.01% had 5 other trackers.

2.98% also included Podtrac, 1.88% also included Adswizz, 1.49% also included Chartable, 0.83% also included Feedpress, 0.44% also included Podsights, 0.31% also included Podcorn, 0.08% also included Podscribe, 0.05% also included Zencastr, 0.03% also included Podder, 0.02% also included OP3, and 0.01% also included AdBarker.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "75.51%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.90%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.64%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.97%" >}}
5. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.45%" >}}
6. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.32%" >}}
7. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.29%" >}}
8. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.19%" >}}
9. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "1.19%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.00%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.50% of new episodes in November, shrinking 0.85% from last month.

Of these, 0.96% had one other tracker.

0.96% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "36.89%" >}}
2. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "36.67%" >}}
3. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "11.17%" >}}
4. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "8.29%" >}}
5. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "6.07%" >}}
6. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "0.48%" >}}
---

### 8. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.18% of new episodes in November, shrinking 3.82% from last month.

Of these, 16.07% had one other tracker, and 1.09% had 2 other trackers.

9.39% also included Podtrac, 7.60% also included Blubrry, and 1.25% also included Chartable.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "64.29%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "11.97%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.02%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.48%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.19%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.00%" >}}
7. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.46%" >}}
8. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "1.12%" >}}
9. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.98%" >}}
10. {{< a "https://www.subsplash.com/" "Subsplash" >}} {{< span "weak" "0.88%" >}}
---

### 9. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.13% of new episodes in November, growing 81.71% from last month.

Of these, 32.48% had 3 other trackers, 25.91% had 4 other trackers, 11.45% had 5 other trackers, 10.83% had one other tracker, and 8.37% had 2 other trackers.

85.68% also included Chartable, 70.16% also included Podtrac, 69.71% also included Podsights, 33.24% also included ArtsAI, 15.79% also included Claritas, 5.32% also included Adswizz, 2.42% also included Veritonic, 1.66% also included Podcorn, 0.98% also included Blubrry, and 0.94% also included OP3.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "47.02%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "43.13%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.22%" >}}
4. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.95%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.15%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.89%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.27%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.22%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.09%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.04%" >}}
---

### 10. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.10% of new episodes in November, growing 0.48% from last month.

Of these, 33.81% had 4 other trackers, 20.42% had 3 other trackers, 19.70% had 2 other trackers, 15.14% had 5 other trackers, and 7.93% had one other tracker.

89.55% also included Chartable, 77.54% also included Podsights, 73.45% also included Podtrac, 44.62% also included Podscribe, 23.72% also included Claritas, 9.85% also included Adswizz, and 0.78% also included Veritonic.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "40.48%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "32.55%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "14.83%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.79%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "4.80%" >}}
6. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.54%" >}}
---

### 11. [Firstory](https://firstory.me/)

Firstory was found on 0.10% of new episodes in November, growing 2.43% from last month.

Of these, 63.29% had one other tracker, and 0.25% had 2 other trackers.

63.54% also included Chartable, and 0.25% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.44%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.43%" >}}
3. {{< a "https://cloud.google.com/" "Google Cloud" >}} {{< span "weak" "0.12%" >}}
---

### 12. [Gumball](https://gumball.fm/)

Gumball was found on 0.05% of new episodes in November, growing 8.90% from last month.

Of these, 31.17% had 4 other trackers, 22.69% had 2 other trackers, 20.32% had 3 other trackers, 8.10% had one other tracker, and 7.86% had 5 other trackers.

77.43% also included Podsights, 58.23% also included Podcorn, 55.36% also included OP3, 52.24% also included Podtrac, 32.29% also included Chartable, 1.25% also included Adswizz, 0.87% also included Podder, and 0.75% also included Podkite.

For episodes that used Gumball, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "60.35%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "18.20%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.10%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "6.11%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.74%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.24%" >}}
7. {{< a "https://sounder.fm/" "Sounder" >}} {{< span "weak" "0.25%" >}}
---

### 13. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.04% of new episodes in November, growing 25.54% from last month.

Of these, 35.19% had 4 other trackers, 24.36% had 3 other trackers, 11.97% had 2 other trackers, 8.97% had 5 other trackers, and 3.56% had one other tracker.

65.95% also included Podcorn, 63.68% also included Podsights, 63.25% also included Gumball, 61.54% also included Podtrac, 26.50% also included Chartable, 2.99% also included Podscribe, 0.85% also included Podkite, 0.71% also included Blubrry, and 0.71% also included Podder.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "75.07%" >}}
2. {{< a "https://podnews.net/" "Podnews" >}} {{< span "weak" "6.27%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.13%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.56%" >}}
5. {{< a "https://changelog.com/" "Changelog" >}} {{< span "weak" "3.56%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.57%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.71%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.71%" >}}
9. {{< a "https://www.digitalocean.com/products/spaces/" "DigitalOcean Spaces" >}} {{< span "weak" "0.28%" >}}
10. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "0.28%" >}}
---

### 14. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.03% of new episodes in November, growing 54.60% from last month.

Of these, 44.65% had 5 other trackers, 30.44% had 3 other trackers, 19.19% had 4 other trackers, 1.11% had 2 other trackers, and 0.55% had one other tracker.

95.02% also included Chartable, 82.29% also included Podsights, 72.88% also included ArtsAI, 65.13% also included Podscribe, 56.83% also included Podtrac, and 21.96% also included Adswizz.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "66.61%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "16.61%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.64%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.54%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "4.61%" >}}
---

### 15. [Zippycast](https://zippycast.io/)

Zippycast was found on 0.02% of new episodes in November, shrinking 0.46% from last month.

Of these, 10.36% had 2 other trackers, and 3.11% had one other tracker.

12.18% also included Podtrac, 10.36% also included Podsights, and 1.30% also included Chartable.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "31.35%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "22.02%" >}}
3. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "20.21%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "16.84%" >}}
5. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "7.77%" >}}
6. {{< a "https://podcloud.fr/" "podCloud" >}} {{< span "weak" "1.81%" >}}
---

### 16. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.02% of new episodes in November, growing 32.68% from last month.

Of these, 40.31% had one other tracker, 39.27% had 2 other trackers, and 15.97% had 3 other trackers.

64.40% also included Chartable, 55.50% also included Podtrac, 29.58% also included Podsights, and 17.28% also included Podcorn.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "55.50%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "24.87%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "15.18%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.36%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.09%" >}}
---

### 17. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.01% of new episodes in November, growing 5.73% from last month.

Of these, 55.98% had one other tracker, 13.25% had 2 other trackers, 5.56% had 4 other trackers, and 2.56% had 3 other trackers.

66.67% also included Podtrac, 20.09% also included Podcorn, 17.52% also included Chartable, and 8.12% also included Podsights.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "43.16%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "14.10%" >}}
3. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "10.68%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "9.40%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "6.41%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.85%" >}}
7. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "2.56%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.28%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.28%" >}}
10. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.43%" >}}
---

### 18. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in November, growing 15.23% from last month.

Of these, 13.01% had 2 other trackers, 10.57% had one other tracker, 4.07% had 4 other trackers, and 3.25% had 3 other trackers.

29.27% also included Podsights, 11.38% also included Blubrry, 10.57% also included Chartable, 7.32% also included Podcorn, and 4.07% also included Podtrac.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "65.85%" >}}
2. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "11.38%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.38%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.07%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.25%" >}}
6. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "1.63%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.63%" >}}
8. {{< a "https://sounder.fm/" "Sounder" >}} {{< span "weak" "0.81%" >}}
---

### 19. [Podder](https://www.podderapp.com/)

Podder was found on 0.01% of new episodes in November, growing 83.46% from last month.

Of these, 29.25% had 2 other trackers, 21.70% had one other tracker, 6.60% had 5 other trackers, and 2.83% had 3 other trackers.

44.34% also included Chartable, 28.30% also included Podtrac, 11.32% also included Podcorn, 7.55% also included Blubrry, 7.55% also included Adswizz, 6.60% also included Podsights, 6.60% also included Gumball, 4.72% also included Podkite, and 4.72% also included OP3.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "33.02%" >}}
2. {{< a "https://sounder.fm/" "Sounder" >}} {{< span "weak" "12.26%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.32%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.38%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "9.43%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "7.55%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.66%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.72%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.77%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.94%" >}}
---

### 20. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in November, shrinking 11.62% from last month.

Of these, 64.08% had 2 other trackers, 10.68% had one other tracker, and 3.88% had 5 other trackers.

71.84% also included Chartable, 40.78% also included Podtrac, 37.86% also included Podcorn, 3.88% also included Blubrry, and 3.88% also included Podsights.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "37.86%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "24.27%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "16.50%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "10.68%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.83%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.85%" >}}
---

### 21. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in November, shrinking 30.76% from last month.

Of these, 26.26% had one other tracker, and 11.11% had 5 other trackers.

19.19% also included Podcorn, 19.19% also included Chartable, 15.15% also included Podtrac, 11.11% also included Podsights, 6.06% also included OP3, 6.06% also included Gumball, and 5.05% also included Podder.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "35.35%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "23.23%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "12.12%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.10%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "8.08%" >}}
6. {{< a "https://analytics.podtrac.com/" "Podtrac" >}} {{< span "weak" "4.04%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "3.03%" >}}
8. {{< a "https://www.bbc.co.uk/" "BBC" >}} {{< span "weak" "1.01%" >}}
9. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "1.01%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.01%" >}}
---

### 22. [Veritonic](https://www.veritonic.com/)

Veritonic was found on <0.01% of new episodes in November, growing 2.11% from last month.

Of these, 66.67% had 3 other trackers, 18.84% had 5 other trackers, 7.25% had 2 other trackers, and 5.80% had 4 other trackers.

98.55% also included Podtrac, 98.55% also included Chartable, 78.26% also included Podscribe, 31.88% also included Podsights, 18.84% also included ArtsAI, and 5.80% also included Adswizz.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "73.91%" >}}
2. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "24.64%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.45%" >}}


---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
*Updated 2022-12-01, with data for the month of November 2022.*

*Updated 2022-11-02, with data for the month of October 2022.*

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
 - [Podcast Tracker Rankings by Episode Share (October 2022)](/archive/podcast-trackers-by-episode-share-october-2022/)
 - [Podcast Tracker Rankings by Episode Share (September 2022)](/archive/podcast-trackers-by-episode-share-september-2022/)
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/podcast-trackers-by-episode-share.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
