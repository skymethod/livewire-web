---
title: "Top Podcast Tracking Services by Episode Share (June 2023)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-june-2023"
images:
- trackers-2023-06.png
date: 2023-07-01T09:57:00-05:00
lastmod: 2023-07-01T09:57:00-05:00
draft: false
rssrevision: 2023-06
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.7 million in June 2023), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in June, how many
of them included one or more of these tracking services?  Some episodes had as many as *eight* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Chartable	Adswizz	Podsights	Podcorn	Blubrry	Médiamétrie	Podscribe	Feedpress	Podder	ArtsAI	Podroll	OP3	Gumshoe	Claritas	Veritonic	Zippycast	Zencastr	Voxalyze	Glystn	Podkite	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.00	1.16	2.09	2.07	0.42		0.32															1.61
Oct 2021	4.05	4.09	1.01	1.20	2.13	2.11	0.54		0.34															1.61
Nov 2021	4.07	4.30	1.02	1.25	2.14	2.01	0.57		0.32															0.59
Dec 2021	4.06	4.42	1.24	1.19	2.27	1.57	0.59		0.19															
Jan 2022	4.11	4.45	1.41	1.21	2.31	1.56	0.63		0.16															
Feb 2022	4.15	4.48	1.44	1.25	2.38	1.53	0.58		0.17															
Mar 2022	4.37	4.72	1.51	1.34	2.40	1.56	0.53		0.17															
Apr 2022	4.44	4.71	1.49	1.33	2.33	1.55	0.51		0.16															
May 2022	4.49	4.87	1.58	1.41	2.26	1.48	0.56		0.17															
Jun 2022	4.75	5.10	1.77	1.54	2.06	1.50	0.62		0.21								0.02							
Jul 2022	4.70	5.10	1.89	1.50	2.16	1.50	0.54		0.25								0.02							
Aug 2022	4.83	5.26	2.08	1.73	2.45	1.51	0.41		0.20		0.10						0.01							
Sep 2022	7.53	5.40	2.26	1.74	2.45	1.49	0.52	0.02	0.21		0.09				0.01		0.02				0.01	0.02		
Oct 2022	8.24	5.48	2.35	1.81	2.51	1.61	0.50	0.07	0.18		0.10		0.03		0.02		0.02	0.01			0.01	0.04		
Nov 2022	8.11	5.62	2.37	2.03	2.43	1.62	0.50	0.15	0.18	0.01	0.10		0.04		0.03		0.02	0.01			0.01	0.05		
Dec 2022	8.01	5.54	2.32	1.81	2.05	1.61	0.49	0.03	0.18	0.04	0.05		0.05		0.02		0.02	0.01		0.01	0.01	0.05		
Jan 2023	7.85	5.56	2.35	1.88	2.15	1.61	0.54	0.20	0.18	0.11	0.10		0.07		0.06		0.02	0.01		0.01	0.01	0.06		
Feb 2023	7.58	5.51	2.29	1.92	2.30	1.62	0.49	0.21	0.19	0.11	0.10		0.07		0.07		0.02	0.01		0.01	0.01	0.06	0.03	
Mar 2023	7.79	5.53	2.25	2.03	2.22	1.53	0.45	0.21	0.18	0.11	0.11	0.04	0.08		0.07	0.04	0.02	0.01		0.01	0.01	0.06		
Apr 2023	7.66	5.43	2.26	2.00	2.20	1.67	0.45	0.21	0.17	0.15	0.11	0.06	0.09	0.08	0.07	0.05	0.01	0.01		0.01	0.01			
May 2023	7.58	5.59	2.27	2.04	2.28	1.67	0.45	0.24	0.19	0.15	0.11	0.09	0.09	0.07	0.08	0.05	0.01	0.01	0.01	0.01	0.01			
Jun 2023	8.22	5.83	2.39	2.23	1.86	1.64	0.51	0.26	0.19	0.15	0.12	0.10	0.09	0.08	0.07	0.05	0.01	0.01	0.01	0.01	0.01			
{{< /graph >}}

---

### Overall

At least one tracker was found on 17.58% of new episodes in June, growing 3.06% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "22.28%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "13.52%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.01%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "6.01%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.89%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "4.06%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.63%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.50%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.43%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.08%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of June 2023.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 8.22% of new episodes in June, growing 8.23% from last month.

Of these, 23.24% had one other tracker, 11.77% had 2 other trackers, 1.86% had 3 other trackers, 0.81% had 4 other trackers, 0.56% had 5 other trackers, 0.19% had 6 other trackers, and 0.14% had 7 other trackers.

29.96% also included Chartable, 14.76% also included Podsights, 6.08% also included Adswizz, 1.74% also included Podcorn, 1.40% also included Podscribe, 1.27% also included Podder, 1.06% also included ArtsAI, 0.62% also included Blubrry, 0.61% also included OP3, 0.58% also included Claritas, 0.57% also included Veritonic, 0.54% also included Gumshoe, 0.53% also included Magellan AI, 0.41% also included Podroll, 0.15% also included Feedpress, 0.10% also included Glystn, 0.05% also included Voxalyze, 0.04% also included Médiamétrie, 0.03% also included AdBarker, 0.02% also included Podkite, 0.02% also included Zencastr, <0.01% also included Zippycast, and <0.01% also included Firstory.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "46.80%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "16.98%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.56%" >}}
4. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "3.11%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.56%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.46%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.66%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.42%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.31%" >}}
10. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "1.31%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 6.53% of new episodes in June, growing 5.23% from last month.

Of these, 40.81% also included Podtrac, 6.53% also included Adswizz, 3.70% also included Podscribe, 3.54% also included Podcorn, 1.97% also included Podder, 1.76% also included ArtsAI, 1.17% also included Podroll, 1.12% also included Magellan AI, 1.12% also included Claritas, 0.88% also included Gumshoe, 0.82% also included Firstory, 0.81% also included OP3, 0.81% also included Veritonic, 0.38% also included Blubrry, 0.12% also included Glystn, 0.08% also included Feedpress, 0.07% also included AdBarker, 0.06% also included Voxalyze, 0.04% also included Zencastr, 0.04% also included Podkite, and <0.01% also included Zippycast.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "31.40%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "22.94%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.72%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.93%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.41%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.36%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.66%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.39%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.34%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.29%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.83% of new episodes in June, growing 3.96% from last month.

Of these, 36.24% had one other tracker, 17.20% had 2 other trackers, 2.89% had 3 other trackers, 1.15% had 4 other trackers, 0.81% had 5 other trackers, 0.21% had 6 other trackers, and 0.20% had 7 other trackers.

42.22% also included Podtrac, 26.34% also included Podsights, 5.13% also included Adswizz, 3.34% also included Podcorn, 3.31% also included Podscribe, 1.83% also included Podder, 1.69% also included ArtsAI, 1.14% also included Magellan AI, 1.13% also included Podroll, 1.00% also included Claritas, 0.92% also included Firstory, 0.71% also included Veritonic, 0.53% also included Gumshoe, 0.48% also included OP3, 0.35% also included Blubrry, 0.14% also included Glystn, 0.09% also included Feedpress, 0.07% also included AdBarker, 0.07% also included Voxalyze, 0.03% also included Zencastr, 0.03% also included Podkite, 0.01% also included Spotify, and <0.01% also included Zippycast.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "31.63%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.37%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.03%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.05%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.81%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.76%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.60%" >}}
8. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.56%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.50%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.37%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.39% of new episodes in June, growing 5.52% from last month.

Of these, 29.03% had one other tracker, 2.36% had 2 other trackers, 2.28% had 3 other trackers, 0.59% had 5 other trackers, 0.45% had 7 other trackers, 0.37% had 6 other trackers, and 0.36% had 4 other trackers.

20.90% also included Podtrac, 12.51% also included Chartable, 9.55% also included Podsights, 1.58% also included Blubrry, 1.45% also included Podscribe, 1.36% also included ArtsAI, 1.15% also included Claritas, 0.53% also included Podroll, 0.50% also included Veritonic, 0.49% also included Magellan AI, 0.18% also included Podcorn, 0.06% also included Podder, 0.06% also included OP3, 0.02% also included Gumshoe, 0.01% also included Spotify, and <0.01% also included Feedpress.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "29.00%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "17.84%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.95%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "9.65%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "9.03%" >}}
6. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "5.59%" >}}
7. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.35%" >}}
8. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "3.40%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.30%" >}}
10. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.26%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.23% of new episodes in June, growing 9.43% from last month.

Of these, 39.02% had 2 other trackers, 32.39% had one other tracker, 7.29% had 3 other trackers, 3.85% had 4 other trackers, 2.32% had 5 other trackers, 0.70% had 6 other trackers, and 0.51% had 7 other trackers.

68.74% also included Chartable, 54.28% also included Podtrac, 10.23% also included Adswizz, 8.55% also included Podscribe, 4.29% also included ArtsAI, 3.86% also included Podder, 3.01% also included Claritas, 2.90% also included Magellan AI, 2.77% also included Podcorn, 2.18% also included Veritonic, 2.09% also included Gumshoe, 2.02% also included Podroll, 1.62% also included OP3, 0.22% also included Blubrry, 0.11% also included Feedpress, 0.10% also included Voxalyze, 0.08% also included Zencastr, 0.07% also included Podkite, 0.02% also included AdBarker, and 0.01% also included Zippycast.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "45.76%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "34.30%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.60%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.59%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.32%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.23%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.75%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.11%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.07%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.92%" >}}
---

### 5. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 1.86% of new episodes in June, shrinking 18.53% from last month.

Of these, 11.40% had one other tracker, 2.38% had 2 other trackers, 1.30% had 4 other trackers, 0.82% had 3 other trackers, 0.53% had 5 other trackers, 0.04% had 7 other trackers, and 0.02% had 6 other trackers.

10.48% also included Chartable, 7.68% also included Podtrac, 3.32% also included Podsights, 1.87% also included OP3, 1.83% also included Gumshoe, 0.49% also included Podder, 0.29% also included Blubrry, 0.23% also included Adswizz, 0.19% also included Podroll, 0.11% also included Podkite, 0.11% also included Voxalyze, 0.10% also included AdBarker, 0.08% also included Zencastr, 0.06% also included Feedpress, 0.03% also included Podscribe, 0.02% also included Magellan AI, and <0.01% also included Spotify.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "44.98%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "23.44%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "7.97%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.36%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.79%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.25%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.53%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.25%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.15%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.92%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.64% of new episodes in June, shrinking 4.76% from last month.

Of these, 6.79% had one other tracker, 0.56% had 2 other trackers, 0.06% had 3 other trackers, 0.03% had 4 other trackers, and 0.02% had 5 other trackers.

3.09% also included Podtrac, 2.29% also included Adswizz, 1.26% also included Chartable, 0.89% also included Feedpress, 0.33% also included Podcorn, 0.30% also included Podsights, 0.07% also included Podder, 0.03% also included Podscribe, 0.02% also included OP3, 0.02% also included AdBarker, and 0.01% also included Claritas.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "43.48%" >}}
2. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "6.67%" >}}
3. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.26%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.15%" >}}
5. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.99%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.87%" >}}
7. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "1.68%" >}}
8. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.33%" >}}
9. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.21%" >}}
10. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.19%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.51% of new episodes in June, growing 15.36% from last month.

Of these, 0.71% had one other tracker.

0.71% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "38.58%" >}}
2. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "37.83%" >}}
3. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "10.62%" >}}
4. {{< a "https://soundcast.fm/" "SoundCast" >}} {{< span "weak" "6.63%" >}}
5. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "3.25%" >}}
6. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "1.78%" >}}
7. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "1.00%" >}}
---

### 8. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.26% of new episodes in June, growing 10.44% from last month.

Of these, 21.13% had one other tracker, 16.71% had 3 other trackers, 16.62% had 4 other trackers, 14.81% had 5 other trackers, 13.65% had 2 other trackers, 5.67% had 6 other trackers, and 4.10% had 7 other trackers.

73.20% also included Chartable, 72.56% also included Podsights, 43.58% also included Podtrac, 29.68% also included ArtsAI, 24.58% also included Claritas, 16.95% also included Magellan AI, 16.64% also included Veritonic, 13.20% also included Adswizz, 8.24% also included Podroll, 1.85% also included Podder, 0.65% also included Gumshoe, 0.31% also included Spotify, 0.20% also included Podcorn, and 0.17% also included Blubrry.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "42.99%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "23.82%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "9.64%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.39%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.63%" >}}
6. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "4.08%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.64%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.16%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.81%" >}}
10. {{< a "https://twit.tv/" "TWiT" >}} {{< span "weak" "0.68%" >}}
---

### 9. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.19% of new episodes in June, growing 0.28% from last month.

Of these, 16.40% had one other tracker, 2.07% had 2 other trackers, 0.24% had 3 other trackers, and 0.03% had 5 other trackers.

7.73% also included Blubrry, 6.51% also included Podtrac, 2.71% also included Chartable, 2.56% also included OP3, 1.25% also included Podsights, 0.61% also included Podcorn, 0.03% also included Veritonic, and 0.03% also included Adswizz.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "45.79%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.22%" >}}
3. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "8.97%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.12%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.87%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.32%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.79%" >}}
8. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.37%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.31%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "0.97%" >}}
---

### 10. [Podder](https://www.podderapp.com/)

Podder was found on 0.15% of new episodes in June, shrinking 1.83% from last month.

Of these, 37.47% had 2 other trackers, 28.12% had 3 other trackers, 9.80% had 4 other trackers, 9.61% had one other tracker, 2.42% had 5 other trackers, 0.87% had 6 other trackers, and 0.45% had 7 other trackers.

70.48% also included Chartable, 68.51% also included Podtrac, 56.89% also included Podsights, 7.53% also included Magellan AI, 6.02% also included Podcorn, 4.13% also included Podroll, 3.90% also included OP3, 3.22% also included Podscribe, 2.76% also included Gumshoe, 1.78% also included ArtsAI, 0.98% also included Adswizz, 0.79% also included Blubrry, 0.61% also included Podkite, 0.57% also included Claritas, 0.42% also included Veritonic, 0.04% also included Voxalyze, and 0.04% also included Spotify.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "72.07%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "7.57%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.22%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.97%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.84%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.65%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.25%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.95%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.79%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.76%" >}}
---

### 11. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.12% of new episodes in June, growing 4.54% from last month.

Of these, 32.94% had 5 other trackers, 19.61% had 3 other trackers, 18.28% had 2 other trackers, 11.84% had 6 other trackers, 9.31% had 7 other trackers, 4.56% had 4 other trackers, and 2.43% had one other tracker.

84.79% also included Chartable, 82.62% also included Podsights, 75.19% also included Podtrac, 67.41% also included Podscribe, 31.95% also included Claritas, 29.77% also included Veritonic, 28.08% also included Adswizz, 14.02% also included Magellan AI, 2.33% also included Podder, 0.45% also included Podroll, and 0.35% also included Spotify.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "32.19%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "25.71%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "12.93%" >}}
4. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "9.26%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.87%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "8.77%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.63%" >}}
8. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.25%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.20%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.15%" >}}
---

### 12. [Podroll](https://podroll.fm/)

Podroll was found on 0.10% of new episodes in June, growing 10.59% from last month.

Of these, 31.50% had one other tracker, 30.28% had 2 other trackers, 23.22% had 4 other trackers, 8.98% had 3 other trackers, 0.35% had 6 other trackers, and 0.17% had 5 other trackers.

66.24% also included Chartable, 45.45% also included Podsights, 34.22% also included Podtrac, 21.89% also included Podscribe, 21.13% also included Magellan AI, 12.85% also included Adswizz, 6.31% also included Podder, 3.47% also included Podcorn, 1.74% also included Voxalyze, 0.52% also included ArtsAI, 0.41% also included Gumshoe, 0.29% also included Zencastr, 0.12% also included Spotify, 0.12% also included Claritas, and 0.06% also included OP3.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "56.92%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.92%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.45%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.56%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.78%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.87%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.64%" >}}
8. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.41%" >}}
9. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "0.29%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.12%" >}}
---

### 13. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.09% of new episodes in June, growing 7.80% from last month.

Of these, 24.27% had 4 other trackers, 22.41% had one other tracker, 10.80% had 3 other trackers, 10.06% had 5 other trackers, 8.50% had 2 other trackers, 0.74% had 7 other trackers, and 0.50% had 6 other trackers.

53.94% also included Podtrac, 51.46% also included Gumshoe, 39.04% also included Podsights, 37.49% also included Podcorn, 30.17% also included Chartable, 6.39% also included Podder, 5.21% also included Feedpress, 1.61% also included Adswizz, 1.18% also included Podkite, 0.37% also included Blubrry, 0.37% also included Magellan AI, 0.06% also included Podroll, and 0.06% also included Spotify.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "61.02%" >}}
2. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "5.21%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.79%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.60%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.17%" >}}
6. {{< a "https://podnews.net/" "Podnews" >}} {{< span "weak" "2.73%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.42%" >}}
8. {{< a "https://changelog.com/" "Changelog" >}} {{< span "weak" "1.99%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.49%" >}}
10. {{< a "https://letscast.fm/" "LetsCast.fm" >}} {{< span "weak" "1.37%" >}}
---

### 14. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.08% of new episodes in June, growing 10.80% from last month.

Of these, 39.28% had 4 other trackers, 13.56% had 2 other trackers, 13.21% had 7 other trackers, 12.37% had one other tracker, 12.30% had 3 other trackers, 5.83% had 6 other trackers, and 2.18% had 5 other trackers.

81.59% also included Chartable, 79.41% also included Podsights, 54.60% also included Podscribe, 53.76% also included Podtrac, 25.65% also included Podroll, 19.89% also included ArtsAI, 18.76% also included Claritas, 14.34% also included Adswizz, 13.98% also included Podder, 9.00% also included Veritonic, 0.49% also included Podcorn, and 0.42% also included OP3.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "60.44%" >}}
2. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "13.14%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "11.10%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.89%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.36%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.26%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.12%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.70%" >}}
9. {{< a "https://twit.tv/" "TWiT" >}} {{< span "weak" "0.35%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.35%" >}}
---

### 15. [Firstory](https://firstory.me/)

Firstory was found on 0.08% of new episodes in June, shrinking 3.66% from last month.

Of these, 66.79% had one other tracker, and 0.29% had 2 other trackers.

67.07% also included Chartable, and 0.29% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.50%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.50%" >}}
---

### 16. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.08% of new episodes in June, growing 6.47% from last month.

Of these, 28.26% had 4 other trackers, 18.09% had one other tracker, 17.78% had 2 other trackers, 13.19% had 3 other trackers, 12.21% had 5 other trackers, 0.90% had 7 other trackers, and 0.60% had 6 other trackers.

62.47% also included OP3, 61.19% also included Podsights, 57.87% also included Podtrac, 44.69% also included Podcorn, 40.69% also included Chartable, 5.50% also included Podder, 2.26% also included Podscribe, 1.43% also included Podkite, 0.60% also included Adswizz, and 0.53% also included Podroll.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "63.23%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.91%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.25%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "8.67%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.39%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.36%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.83%" >}}
8. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.23%" >}}
9. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.08%" >}}
---

### 17. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.07% of new episodes in June, shrinking 2.60% from last month.

Of these, 21.49% had 4 other trackers, 18.65% had 5 other trackers, 15.73% had 3 other trackers, 14.43% had 7 other trackers, 14.35% had 6 other trackers, 12.28% had 2 other trackers, and 2.76% had one other tracker.

89.79% also included Podsights, 86.49% also included Podscribe, 77.67% also included Chartable, 63.47% also included Podtrac, 49.50% also included ArtsAI, 36.91% also included Adswizz, 20.49% also included Magellan AI, 14.20% also included Veritonic, 1.15% also included Podder, 0.84% also included Spotify, 0.15% also included Blubrry, and 0.15% also included Podroll.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.46%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "15.81%" >}}
3. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "14.35%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.05%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "9.29%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "9.06%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.53%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.23%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.15%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.08%" >}}
---

### 18. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.05% of new episodes in June, growing 12.71% from last month.

Of these, 49.73% had 5 other trackers, 19.66% had 6 other trackers, 14.82% had 4 other trackers, 7.30% had 2 other trackers, 5.91% had 3 other trackers, and 1.72% had one other tracker.

91.30% also included Podsights, 87.11% also included Podtrac, 81.95% also included Podscribe, 77.34% also included Chartable, 64.55% also included ArtsAI, 22.34% also included Adswizz, 19.87% also included Claritas, 13.75% also included Magellan AI, 1.18% also included Podder, 0.43% also included Spotify, and 0.11% also included Feedpress.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "58.54%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "22.99%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.85%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.20%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.21%" >}}
6. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.11%" >}}
---

### 19. [Zippycast](https://zippycast.io/)

Zippycast was found on 0.01% of new episodes in June, growing 8.05% from last month.

Of these, 2.44% had one other tracker, and 1.63% had 2 other trackers.

2.44% also included Podtrac, 1.63% also included Podsights, and 1.63% also included Chartable.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "30.08%" >}}
2. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "26.02%" >}}
3. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "23.98%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "15.85%" >}}
5. {{< a "https://podcloud.fr/" "podCloud" >}} {{< span "weak" "2.44%" >}}
6. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "1.63%" >}}
---

### 20. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in June, shrinking 8.92% from last month.

Of these, 37.43% had one other tracker, 7.82% had 2 other trackers, 2.79% had 4 other trackers, and 1.12% had 3 other trackers.

18.99% also included Chartable, 17.88% also included Podsights, 13.97% also included Podcorn, 13.97% also included Podtrac, and 2.79% also included Podroll.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "100.00%" >}}
---

### 21. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on 0.01% of new episodes in June, growing 14.29% from last month.

Of these, 42.28% had 3 other trackers, 18.79% had one other tracker, 7.38% had 2 other trackers, and 1.34% had 4 other trackers.

51.01% also included Podtrac, 45.64% also included Chartable, 25.50% also included Podsights, 22.82% also included Podcorn, 20.13% also included Podroll, and 0.67% also included Podder.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "35.57%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "25.50%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "21.48%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "6.04%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.37%" >}}
6. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "3.36%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.34%" >}}
8. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "0.67%" >}}
---

### 22. [Glystn](https://glystn.com/)

Glystn was found on 0.01% of new episodes in June, shrinking 11.09% from last month.

Of these, 97.16% had 2 other trackers, and 2.84% had one other tracker.

100.00% also included Chartable, and 97.16% also included Podtrac.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "97.16%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.84%" >}}
---

### 23. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in June, growing 2.00% from last month.

Of these, 24.43% had one other tracker, 9.16% had 7 other trackers, 8.40% had 5 other trackers, and 3.05% had 2 other trackers.

26.72% also included Podtrac, 25.95% also included Podcorn, 22.14% also included Chartable, 20.61% also included Podsights, 14.50% also included OP3, 14.50% also included Gumshoe, and 12.21% also included Podder.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "21.37%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "20.61%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "15.27%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "12.98%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "8.40%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "6.11%" >}}
7. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "6.11%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.05%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.29%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.76%" >}}
---

### 24. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in June, shrinking 7.33% from last month.

Of these, 48.18% had 2 other trackers, 19.09% had one other tracker, and 5.45% had 5 other trackers.

69.09% also included Chartable, 32.73% also included Podtrac, 30.00% also included Podcorn, 5.45% also included Blubrry, and 5.45% also included Podsights.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "35.45%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "21.82%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "20.91%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "10.91%" >}}
5. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "4.55%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.73%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.82%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.82%" >}}
---

### 25. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on <0.01% of new episodes in June.

Of these, 54.55% had 2 other trackers, 18.18% had 5 other trackers, 13.64% had one other tracker, and 4.55% had 4 other trackers.

63.64% also included Podscribe, 50.00% also included Claritas, 31.82% also included ArtsAI, 27.27% also included Chartable, 18.18% also included Veritonic, 18.18% also included Adswizz, 9.09% also included Podroll, 4.55% also included OP3, 4.55% also included Podcorn, and 4.55% also included Podder.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "45.45%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "31.82%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "18.18%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "4.55%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
*Updated 2023-07-01, with data for the month of June 2023. Includes new Spotify Ad Analytics prefix launched in June.*

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
 - [Podcast Tracker Rankings by Episode Share (May 2023)](/archive/podcast-trackers-by-episode-share-may-2023/)
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2023-06.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
