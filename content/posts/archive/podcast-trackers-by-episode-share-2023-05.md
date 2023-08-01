---
title: "Top Podcast Tracking Services by Episode Share (May 2023)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-may-2023"
images:
- trackers-2023-05.png
date: 2023-06-01T12:20:00-05:00
lastmod: 2023-06-01T12:20:00-05:00
draft: false
rssrevision: 2023-05
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.8 million in May 2023), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in May, how many
of them included one or more of these tracking services?  Some episodes had as many as *eight* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Chartable	Podcorn	Adswizz	Podsights	Blubrry	Médiamétrie	Podscribe	Feedpress	Podder	ArtsAI	Podroll	OP3	Claritas	Gumshoe	Veritonic	Zippycast	Zencastr	Glystn	Voxalyze	Podkite	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	2.09	1.00	1.16	2.07	0.42		0.32															1.61
Oct 2021	4.05	4.09	2.13	1.01	1.20	2.11	0.54		0.34															1.61
Nov 2021	4.07	4.30	2.14	1.02	1.25	2.01	0.57		0.32															0.59
Dec 2021	4.06	4.42	2.27	1.24	1.19	1.57	0.59		0.19															
Jan 2022	4.11	4.45	2.31	1.41	1.21	1.56	0.63		0.16															
Feb 2022	4.15	4.48	2.38	1.44	1.25	1.53	0.58		0.17															
Mar 2022	4.37	4.72	2.40	1.51	1.34	1.56	0.53		0.17															
Apr 2022	4.44	4.71	2.33	1.49	1.33	1.55	0.51		0.16															
May 2022	4.49	4.87	2.26	1.58	1.41	1.48	0.56		0.17															
Jun 2022	4.75	5.10	2.06	1.77	1.54	1.50	0.62		0.21								0.02							
Jul 2022	4.70	5.10	2.16	1.89	1.50	1.50	0.54		0.25								0.02							
Aug 2022	4.83	5.26	2.45	2.08	1.73	1.51	0.41		0.20		0.10						0.01							
Sep 2022	7.53	5.40	2.45	2.26	1.74	1.49	0.52	0.02	0.21		0.09			0.01			0.02				0.01	0.02		
Oct 2022	8.24	5.48	2.51	2.35	1.81	1.61	0.50	0.07	0.18		0.10		0.03	0.02			0.02	0.01			0.01	0.04		
Nov 2022	8.11	5.62	2.43	2.37	2.03	1.62	0.50	0.15	0.18	0.01	0.10		0.04	0.03			0.02	0.01			0.01	0.05		
Dec 2022	8.01	5.54	2.05	2.32	1.81	1.61	0.49	0.03	0.18	0.04	0.05		0.05	0.02			0.02	0.01	0.01		0.01	0.05		
Jan 2023	7.85	5.56	2.15	2.35	1.88	1.61	0.54	0.20	0.18	0.11	0.10		0.07	0.06			0.02	0.01	0.01		0.01	0.06		
Feb 2023	7.58	5.51	2.30	2.29	1.92	1.62	0.49	0.21	0.19	0.11	0.10		0.07	0.07			0.02	0.01	0.01		0.01	0.06	0.03	
Mar 2023	7.79	5.53	2.22	2.25	2.03	1.53	0.45	0.21	0.18	0.11	0.11	0.04	0.08	0.07		0.04	0.02	0.01	0.01		0.01	0.06		
Apr 2023	7.66	5.43	2.20	2.26	2.00	1.67	0.45	0.21	0.17	0.15	0.11	0.06	0.09	0.07	0.08	0.05	0.01	0.01	0.01		0.01			
May 2023	7.58	5.59	2.28	2.27	2.04	1.67	0.45	0.24	0.19	0.15	0.11	0.09	0.09	0.08	0.07	0.05	0.01	0.01	0.01	0.01	0.01			
{{< /graph >}}

---

### Overall

At least one tracker was found on 16.99% of new episodes in May, growing 0.65% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "21.38%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.44%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.18%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "8.34%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.29%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "4.09%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.88%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.72%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.20%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.11%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of May 2023.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 7.58% of new episodes in May, shrinking 1.05% from last month.

Of these, 22.44% had one other tracker, 11.54% had 2 other trackers, 1.92% had 3 other trackers, 0.92% had 4 other trackers, 0.64% had 5 other trackers, 0.19% had 7 other trackers, and 0.16% had 6 other trackers.

29.77% also included Chartable, 14.12% also included Podsights, 6.25% also included Adswizz, 2.00% also included Podcorn, 1.52% also included Podscribe, 1.39% also included Podder, 1.10% also included ArtsAI, 0.72% also included OP3, 0.69% also included Claritas, 0.63% also included Blubrry, 0.63% also included Gumshoe, 0.56% also included Veritonic, 0.50% also included Magellan AI, 0.16% also included Feedpress, 0.11% also included Glystn, 0.11% also included Podroll, 0.06% also included Voxalyze, 0.06% also included Médiamétrie, 0.03% also included AdBarker, 0.03% also included Backtracks, 0.02% also included Podkite, 0.02% also included Zencastr, <0.01% also included Zippycast, and <0.01% also included Firstory.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "47.05%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "16.45%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.57%" >}}
4. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.97%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.81%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.58%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.80%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.54%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.53%" >}}
10. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "1.47%" >}}
---

### [Spotify (Chartable & Podsights)](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/)

At least one Spotify tracker was found on 6.19% of new episodes in May, growing 2.90% from last month.

Of these, 38.65% also included Podtrac, 7.47% also included Adswizz, 4.56% also included Podcorn, 3.52% also included Podscribe, 2.16% also included Podder, 1.78% also included ArtsAI, 1.21% also included Claritas, 1.12% also included Podroll, 1.04% also included Magellan AI, 0.98% also included Gumshoe, 0.93% also included OP3, 0.90% also included Firstory, 0.76% also included Veritonic, 0.57% also included Blubrry, 0.14% also included Glystn, 0.08% also included AdBarker, 0.07% also included Feedpress, 0.05% also included Zencastr, 0.05% also included Voxalyze, 0.03% also included Podkite, and <0.01% also included Zippycast.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.47%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "22.53%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.20%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.27%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.88%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.20%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.97%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.52%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.46%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.35%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.59% of new episodes in May, growing 2.96% from last month.

Of these, 35.91% had one other tracker, 16.79% had 2 other trackers, 2.85% had 3 other trackers, 1.14% had 4 other trackers, 0.83% had 5 other trackers, 0.26% had 7 other trackers, and 0.22% had 6 other trackers.

40.34% also included Podtrac, 25.79% also included Podsights, 5.82% also included Adswizz, 4.19% also included Podcorn, 3.15% also included Podscribe, 2.05% also included Podder, 1.68% also included ArtsAI, 1.10% also included Podroll, 1.10% also included Magellan AI, 1.09% also included Claritas, 0.99% also included Firstory, 0.65% also included Veritonic, 0.57% also included Blubrry, 0.48% also included Gumshoe, 0.44% also included OP3, 0.16% also included Glystn, 0.09% also included AdBarker, 0.07% also included Feedpress, 0.05% also included Voxalyze, 0.04% also included Zencastr, 0.03% also included Podkite, and 0.01% also included Zippycast.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.48%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.68%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.44%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.33%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.24%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.52%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.73%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.70%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.60%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.49%" >}}
---

### 3. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 2.28% of new episodes in May, growing 3.89% from last month.

Of these, 10.94% had one other tracker, 2.05% had 2 other trackers, 1.33% had 4 other trackers, 0.80% had 3 other trackers, 0.51% had 5 other trackers, 0.03% had 7 other trackers, and 0.02% had 6 other trackers.

10.27% also included Chartable, 6.64% also included Podtrac, 3.38% also included Podsights, 1.95% also included OP3, 1.93% also included Gumshoe, 0.48% also included Podder, 0.24% also included Blubrry, 0.18% also included Adswizz, 0.12% also included AdBarker, 0.12% also included Podroll, 0.11% also included Zencastr, 0.09% also included Voxalyze, 0.08% also included Podkite, 0.05% also included Feedpress, 0.02% also included Podscribe, 0.02% also included Magellan AI, and <0.01% also included Backtracks.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "53.49%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "20.14%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "6.15%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.39%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.29%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.10%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.10%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.66%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.97%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.89%" >}}
---

### 4. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.27% of new episodes in May, growing 0.56% from last month.

Of these, 32.98% had one other tracker, 3.73% had 2 other trackers, 2.38% had 3 other trackers, 0.60% had 7 other trackers, 0.59% had 5 other trackers, 0.41% had 6 other trackers, and 0.39% had 4 other trackers.

20.87% also included Podtrac, 14.34% also included Chartable, 12.00% also included Podsights, 4.93% also included Blubrry, 1.72% also included Podscribe, 1.55% also included ArtsAI, 1.37% also included Claritas, 0.60% also included Magellan AI, 0.58% also included Podroll, 0.51% also included Veritonic, 0.19% also included Podcorn, 0.02% also included Podder, 0.02% also included Gumshoe, and 0.01% also included OP3.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "31.79%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "16.51%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.77%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "8.16%" >}}
5. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "6.34%" >}}
6. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "6.25%" >}}
7. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "5.39%" >}}
8. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.74%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.45%" >}}
10. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.40%" >}}
---

### 5. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.04% of new episodes in May, growing 1.85% from last month.

Of these, 40.71% had 2 other trackers, 29.93% had one other tracker, 7.80% had 3 other trackers, 4.37% had 4 other trackers, 2.65% had 5 other trackers, 0.70% had 7 other trackers, and 0.60% had 6 other trackers.

70.74% also included Chartable, 52.49% also included Podtrac, 13.36% also included Adswizz, 9.01% also included Podscribe, 4.51% also included ArtsAI, 4.30% also included Podder, 3.78% also included Podcorn, 3.42% also included Claritas, 2.81% also included Magellan AI, 2.73% also included Gumshoe, 2.22% also included OP3, 2.16% also included Veritonic, 1.90% also included Podroll, 0.22% also included Blubrry, 0.11% also included Zencastr, 0.10% also included Voxalyze, 0.07% also included Podkite, 0.04% also included Feedpress, 0.01% also included Zippycast, and 0.01% also included AdBarker.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "42.84%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "35.27%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.91%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.42%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.12%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.29%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.97%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.21%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.02%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.02%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.67% of new episodes in May, growing 0.36% from last month.

Of these, 11.42% had one other tracker, 0.51% had 2 other trackers, 0.09% had 3 other trackers, 0.04% had 4 other trackers, and 0.04% had 5 other trackers.

6.69% also included Adswizz, 2.86% also included Podtrac, 1.92% also included Chartable, 0.81% also included Feedpress, 0.33% also included Podcorn, 0.27% also included Podsights, 0.09% also included OP3, 0.06% also included Podder, 0.02% also included AdBarker, 0.02% also included Podscribe, 0.01% also included Zencastr, <0.01% also included Podroll, and <0.01% also included Claritas.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "41.60%" >}}
2. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "5.68%" >}}
3. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "5.54%" >}}
4. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.31%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.33%" >}}
6. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "2.02%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.71%" >}}
8. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.65%" >}}
9. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.19%" >}}
10. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.19%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.45% of new episodes in May, shrinking 0.18% from last month.

Of these, 0.96% had one other tracker.

0.96% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "38.28%" >}}
2. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "36.22%" >}}
3. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "12.00%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "8.75%" >}}
5. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "1.89%" >}}
6. {{< a "https://soundcast.fm/" "SoundCast" >}} {{< span "weak" "1.43%" >}}
7. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "0.97%" >}}
---

### 8. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.24% of new episodes in May, growing 13.20% from last month.

Of these, 19.20% had 4 other trackers, 16.85% had 5 other trackers, 16.82% had 3 other trackers, 15.46% had one other tracker, 13.39% had 2 other trackers, 5.72% had 7 other trackers, and 4.87% had 6 other trackers.

77.01% also included Podsights, 73.79% also included Chartable, 48.38% also included Podtrac, 33.15% also included ArtsAI, 28.33% also included Claritas, 17.53% also included Magellan AI, 16.40% also included Adswizz, 16.05% also included Veritonic, 9.27% also included Podroll, 2.12% also included Podder, 0.52% also included Gumshoe, 0.21% also included Podcorn, 0.12% also included Blubrry, and 0.12% also included OP3.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "45.06%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.29%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.49%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.80%" >}}
5. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "5.72%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.51%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.48%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.11%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.64%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.49%" >}}
---

### 9. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.19% of new episodes in May, growing 8.44% from last month.

Of these, 16.31% had one other tracker, 1.41% had 2 other trackers, and 0.06% had 3 other trackers.

7.28% also included Blubrry, 6.53% also included Podtrac, 2.29% also included OP3, 2.20% also included Chartable, 0.60% also included Podcorn, and 0.42% also included Podsights.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "46.75%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.57%" >}}
3. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "9.06%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.43%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.05%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.19%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.93%" >}}
8. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.65%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.23%" >}}
10. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.96%" >}}
---

### 10. [Podder](https://www.podderapp.com/)

Podder was found on 0.15% of new episodes in May, growing 3.42% from last month.

Of these, 41.08% had 2 other trackers, 28.39% had 3 other trackers, 9.46% had one other tracker, 7.03% had 4 other trackers, 2.72% had 5 other trackers, 0.69% had 6 other trackers, and 0.47% had 7 other trackers.

74.00% also included Chartable, 68.24% also included Podtrac, 56.71% also included Podsights, 7.11% also included Podcorn, 5.37% also included Magellan AI, 4.02% also included OP3, 3.26% also included Podscribe, 2.76% also included Gumshoe, 1.67% also included ArtsAI, 0.69% also included Blubrry, 0.65% also included Podkite, 0.51% also included Claritas, 0.36% also included Adswizz, 0.33% also included Veritonic, 0.18% also included Podroll, and 0.11% also included Voxalyze.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "72.95%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "8.34%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.47%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.15%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.05%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.97%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.94%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.80%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.44%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.40%" >}}
---

### 11. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.11% of new episodes in May, growing 5.57% from last month.

Of these, 35.09% had 5 other trackers, 18.10% had 2 other trackers, 17.69% had 3 other trackers, 12.29% had 7 other trackers, 10.01% had 6 other trackers, 3.34% had 4 other trackers, and 2.53% had one other tracker.

84.83% also included Chartable, 82.91% also included Podsights, 75.13% also included Podtrac, 71.23% also included Podscribe, 35.89% also included Claritas, 31.65% also included Adswizz, 28.41% also included Veritonic, 14.26% also included Magellan AI, and 2.33% also included Podder.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.13%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "24.67%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "12.94%" >}}
4. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "12.29%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "9.15%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.80%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.47%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.25%" >}}
9. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.20%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.10%" >}}
---

### 12. [Podroll](https://podroll.fm/)

Podroll was found on 0.09% of new episodes in May, growing 50.03% from last month.

Of these, 55.40% had one other tracker, 23.86% had 4 other trackers, 13.24% had 2 other trackers, and 4.00% had 3 other trackers.

68.58% also included Chartable, 43.10% also included Podsights, 24.61% also included Podscribe, 23.74% also included Magellan AI, 14.62% also included Adswizz, 9.31% also included Podtrac, 2.94% also included Podcorn, 1.75% also included Voxalyze, 0.31% also included Podder, 0.25% also included Zencastr, 0.06% also included Blubrry, and 0.06% also included Backtracks.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "51.97%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "24.23%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "14.68%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.75%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.00%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.75%" >}}
7. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.37%" >}}
8. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "0.25%" >}}
---

### 13. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.09% of new episodes in May, shrinking 2.55% from last month.

Of these, 32.94% had 4 other trackers, 12.94% had 5 other trackers, 12.42% had one other tracker, 9.28% had 2 other trackers, 8.50% had 3 other trackers, 0.85% had 7 other trackers, and 0.65% had 6 other trackers.

63.14% also included Podtrac, 52.68% also included Podsights, 51.83% also included Podcorn, 50.33% also included Gumshoe, 28.95% also included Chartable, 7.25% also included Podder, 4.97% also included Feedpress, 1.76% also included Blubrry, 1.05% also included Podkite, 0.33% also included Podscribe, 0.33% also included Magellan AI, and 0.20% also included Adswizz.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "61.63%" >}}
2. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "4.97%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.73%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.20%" >}}
5. {{< a "https://podnews.net/" "Podnews" >}} {{< span "weak" "3.01%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.94%" >}}
7. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "2.55%" >}}
8. {{< a "https://changelog.com/" "Changelog" >}} {{< span "weak" "1.70%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.63%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.24%" >}}
---

### 14. [Firstory](https://firstory.me/)

Firstory was found on 0.08% of new episodes in May, growing 0.76% from last month.

Of these, 66.44% had one other tracker, and 0.34% had 2 other trackers.

66.78% also included Chartable, and 0.34% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.19%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.81%" >}}
---

### 15. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.08% of new episodes in May, growing 7.09% from last month.

Of these, 23.35% had 4 other trackers, 20.72% had 5 other trackers, 17.79% had 7 other trackers, 13.76% had 3 other trackers, 10.69% had 6 other trackers, 10.25% had 2 other trackers, and 2.93% had one other tracker.

91.00% also included Podsights, 88.14% also included Podscribe, 79.87% also included Chartable, 67.72% also included Podtrac, 51.98% also included ArtsAI, 40.48% also included Adswizz, 17.86% also included Magellan AI, 12.23% also included Veritonic, 1.02% also included Podder, and 0.07% also included Blubrry.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "35.14%" >}}
2. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "17.79%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "14.20%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "11.42%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "10.03%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "9.59%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.02%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.66%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.07%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.07%" >}}
---

### 16. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.07% of new episodes in May, growing 4.52% from last month.

Of these, 39.27% had 4 other trackers, 18.49% had 7 other trackers, 14.08% had one other tracker, 11.87% had 2 other trackers, 11.04% had 3 other trackers, and 3.04% had 5 other trackers.

83.33% also included Chartable, 77.78% also included Podsights, 56.70% also included Podscribe, 51.83% also included Podtrac, 28.92% also included Podroll, 21.46% also included ArtsAI, 18.57% also included Claritas, 18.49% also included Adswizz, 11.26% also included Podder, 3.35% also included Veritonic, 0.61% also included Podcorn, and 0.38% also included OP3.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "55.86%" >}}
2. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "18.49%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "11.72%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.77%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.49%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.76%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.68%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.61%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.53%" >}}
10. {{< a "https://twit.tv/" "TWiT" >}} {{< span "weak" "0.08%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.07% of new episodes in May, shrinking 5.51% from last month.

Of these, 38.16% had 4 other trackers, 20.54% had 2 other trackers, 15.03% had 5 other trackers, 9.52% had 3 other trackers, 5.04% had one other tracker, 1.02% had 7 other trackers, and 0.79% had 6 other trackers.

78.13% also included Podsights, 66.96% also included Podtrac, 61.68% also included Podcorn, 60.58% also included OP3, 37.37% also included Chartable, 5.98% also included Podder, 1.73% also included Podscribe, 1.26% also included Podkite, and 0.63% also included Adswizz.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "62.86%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "12.59%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.13%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "7.71%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.07%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.83%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.26%" >}}
8. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.47%" >}}
---

### 18. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.05% of new episodes in May, growing 3.21% from last month.

Of these, 58.46% had 5 other trackers, 15.74% had 4 other trackers, 12.31% had 6 other trackers, 5.80% had 2 other trackers, 4.73% had 3 other trackers, and 1.78% had one other tracker.

92.66% also included Podsights, 89.35% also included Podtrac, 80.71% also included Podscribe, 77.04% also included Chartable, 66.51% also included ArtsAI, 24.38% also included Adswizz, 19.76% also included Claritas, 5.21% also included Magellan AI, and 1.07% also included Podder.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "58.58%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "25.21%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "8.99%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.86%" >}}
5. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.12%" >}}
---

### 19. [Zippycast](https://zippycast.io/)

Zippycast was found on 0.01% of new episodes in May, shrinking 6.56% from last month.

Of these, 2.56% had one other tracker, and 2.14% had 2 other trackers.

2.56% also included Podtrac, 2.14% also included Podsights, and 2.14% also included Chartable.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "29.91%" >}}
2. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "27.78%" >}}
3. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "22.65%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "16.67%" >}}
5. {{< a "https://podcloud.fr/" "podCloud" >}} {{< span "weak" "2.56%" >}}
6. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "0.43%" >}}
---

### 20. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.01% of new episodes in May, shrinking 83.47% from last month.

Of these, 18.91% had one other tracker, and 0.50% had 4 other trackers.

18.91% also included Podtrac, 1.00% also included Podcorn, 0.50% also included Voxalyze, and 0.50% also included Podroll.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://www.rferl.org/" "Radio Free Europe and Radio Liberty" >}} {{< span "weak" "71.64%" >}}
2. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "15.92%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.49%" >}}
4. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.49%" >}}
5. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "1.00%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.50%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.50%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.50%" >}}
9. {{< a "https://www.martinoticias.com/" "Radio Martí" >}} {{< span "weak" "0.50%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.50%" >}}
---

### 21. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in May, growing 20.93% from last month.

Of these, 38.69% had one other tracker, 11.06% had 2 other trackers, 3.02% had 4 other trackers, and 2.51% had 3 other trackers.

21.61% also included Podcorn, 20.60% also included Podsights, 20.10% also included Chartable, 15.08% also included Podtrac, 2.01% also included Podroll, and 1.01% also included Blubrry.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "100.00%" >}}
---

### 22. [Glystn](https://glystn.com/)

Glystn was found on 0.01% of new episodes in May, growing 3.02% from last month.

Of these, 96.86% had 2 other trackers, and 3.14% had one other tracker.

100.00% also included Chartable, and 96.86% also included Podtrac.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "96.86%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.14%" >}}
---

### 23. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on 0.01% of new episodes in May, growing 57.95% from last month.

Of these, 44.78% had 3 other trackers, 14.93% had one other tracker, 5.97% had 2 other trackers, and 3.73% had 4 other trackers.

57.46% also included Podtrac, 40.30% also included Chartable, 28.36% also included Podcorn, 26.12% also included Podsights, 20.90% also included Podroll, 2.24% also included Podder, and 0.75% also included Backtracks.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.33%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "23.88%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "23.13%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "8.96%" >}}
5. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "6.72%" >}}
6. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "2.99%" >}}
---

### 24. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in May, growing 22.99% from last month.

Of these, 21.21% had one other tracker, 9.85% had 7 other trackers, 6.06% had 5 other trackers, and 3.79% had 2 other trackers.

25.76% also included Podcorn, 23.48% also included Podtrac, 21.21% also included Chartable, 19.70% also included Podsights, 13.64% also included Podder, 12.12% also included OP3, and 12.12% also included Gumshoe.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "25.76%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "18.18%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "15.91%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "10.61%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "7.58%" >}}
6. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "6.82%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.82%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.79%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.52%" >}}
---

### 25. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in May, growing 11.55% from last month.

Of these, 61.48% had 2 other trackers, 10.66% had one other tracker, and 4.10% had 5 other trackers.

72.13% also included Chartable, 38.52% also included Podcorn, 35.25% also included Podtrac, 4.10% also included Blubrry, and 4.10% also included Podsights.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "32.79%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "31.15%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "18.85%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "9.84%" >}}
5. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "3.28%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.46%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.64%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
*Updated 2023-06-01, with data for the month of May 2023.*

*Updated 2023-05-04, with data for the month of April 2023.*

*Updated 2023-04-01, with data for the month of March 2023.*

*Updated 2023-03-01, with data for the month of February 2023.*

*Updated 2023-02-01, with data for the month of January 2023.*

*Updated 2023-01-01, with data for the month of December 2022.*

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
 - [Podcast Tracker Rankings by Episode Share (April 2023)](/archive/podcast-trackers-by-episode-share-april-2023/)
 - [Podcast Tracker Rankings by Episode Share (March 2023)](/archive/podcast-trackers-by-episode-share-march-2023/)
 - [Podcast Tracker Rankings by Episode Share (February 2023)](/archive/podcast-trackers-by-episode-share-february-2023/)
 - [Podcast Tracker Rankings by Episode Share (January 2023)](/archive/podcast-trackers-by-episode-share-january-2023/)
 - [Podcast Tracker Rankings by Episode Share (December 2022)](/archive/podcast-trackers-by-episode-share-december-2022/)
 - [Podcast Tracker Rankings by Episode Share (November 2022)](/archive/podcast-trackers-by-episode-share-november-2022/)
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2023-05.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
