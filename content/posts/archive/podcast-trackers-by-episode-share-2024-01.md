---
title: "Top Podcast Tracking Services by Episode Share (January 2024)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-january-2024"
images:
- trackers-2024-01.png
date: 2024-02-02T12:08:00-06:00
lastmod: 2024-02-02T12:08:00-06:00
draft: false
rssrevision: 2024-01
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.8 million in January 2024), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in January, how many
of them included one or more of these tracking services?  Some episodes had as many as *nine* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

### A special note for September/October 2023 {#s4p}
_We now have a better signal of when Spotify for Podcasters (formerly Anchor) podcasts release new episodes, so our crawlers are finding more, starting mid-September._

_October was the first full month where this new signal was incorporated for the entire month, so should be a good baseline going forward.  It's likely that we were undercounting S4P prior to this,
in general our goal is to observe and validate every change to every podcast._

_Higher share of new episodes on S4P (which typically do not have prefixes) leads to lower share overall for all prefixes over these two months, but should be stable going forward now that we have a more accurate baseline._

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Chartable	Adswizz	Podsights	Blubrry	Podcorn	Podscribe	Médiamétrie	Feedpress	Podder	Spotify	ArtsAI	OP3	Claritas	Podroll	Gumshoe	Audiotakes	Veritonic	Zencastr	Podkite	Voxalyze	United Podcasters	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.00	1.16	2.07	2.09		0.42	0.32																		1.61
Oct 2021	4.05	4.09	1.01	1.20	2.11	2.13		0.54	0.34																		1.61
Nov 2021	4.07	4.30	1.02	1.25	2.01	2.14		0.57	0.32																		0.59
Dec 2021	4.06	4.42	1.24	1.19	1.57	2.27		0.59	0.19																		
Jan 2022	4.11	4.45	1.41	1.21	1.56	2.31		0.63	0.16																		
Feb 2022	4.15	4.48	1.44	1.25	1.53	2.38		0.58	0.17																		
Mar 2022	4.37	4.72	1.51	1.34	1.56	2.40		0.53	0.17																		
Apr 2022	4.44	4.71	1.49	1.33	1.55	2.33		0.51	0.16																		
May 2022	4.49	4.87	1.58	1.41	1.48	2.26		0.56	0.17																		
Jun 2022	4.75	5.10	1.77	1.54	1.50	2.06		0.62	0.21															0.02			
Jul 2022	4.70	5.10	1.89	1.50	1.50	2.16		0.54	0.25															0.02			
Aug 2022	4.83	5.26	2.08	1.73	1.51	2.45		0.41	0.20			0.10												0.01			
Sep 2022	7.53	5.40	2.26	1.74	1.49	2.45	0.02	0.52	0.21			0.09		0.01						0.01				0.02	0.02		
Oct 2022	8.24	5.48	2.35	1.81	1.61	2.51	0.07	0.50	0.18			0.10	0.03	0.02					0.01	0.01				0.02	0.04		
Nov 2022	8.11	5.62	2.37	2.03	1.62	2.43	0.15	0.50	0.18	0.01		0.10	0.04	0.03					0.01	0.01				0.02	0.05		
Dec 2022	8.01	5.54	2.32	1.81	1.61	2.05	0.03	0.49	0.18	0.04		0.05	0.05	0.02					0.01	0.01			0.01	0.02	0.05		
Jan 2023	7.85	5.56	2.35	1.88	1.61	2.15	0.20	0.54	0.18	0.11		0.10	0.07	0.06					0.01	0.01			0.01	0.02	0.06		
Feb 2023	7.58	5.51	2.29	1.92	1.62	2.30	0.21	0.49	0.19	0.11		0.10	0.07	0.07					0.01	0.01			0.01	0.02	0.06	0.03	
Mar 2023	7.79	5.53	2.25	2.03	1.53	2.22	0.21	0.45	0.18	0.11		0.11	0.08	0.07	0.04			0.04	0.01	0.01			0.01	0.02	0.06		
Apr 2023	7.66	5.43	2.26	2.00	1.67	2.20	0.21	0.45	0.17	0.15		0.11	0.09	0.07	0.06	0.08		0.05	0.01	0.01			0.01	0.01			
May 2023	7.58	5.59	2.27	2.04	1.67	2.28	0.24	0.45	0.19	0.15		0.11	0.09	0.08	0.09	0.07		0.05	0.01	0.01	0.01		0.01	0.01			
Jun 2023	8.22	5.83	2.39	2.23	1.64	1.86	0.26	0.51	0.19	0.15		0.12	0.09	0.07	0.10	0.08		0.05	0.01	0.01	0.01		0.01	0.01			
Jul 2023	8.60	5.95	2.38	2.52	1.53	1.17	0.27	0.55	0.18	0.14	0.01	0.11	0.08	0.07	0.14	0.06		0.06	0.01	0.01	0.01		0.01	0.01			
Aug 2023	9.19	6.43	2.72	2.76	1.58	1.23	0.36	0.53	0.17	0.15	0.03	0.12	0.11	0.08	0.16	0.07	0.04	0.07	0.01	0.01	0.02		0.01				
Sep 2023	8.46	5.77	2.49	2.47	1.39	1.10	0.37	0.58	0.16	0.15	0.05	0.12	0.10	0.10	0.13	0.07	0.05	0.06	0.01	0.01	0.02		0.01				
Oct 2023	7.90	5.54	2.29	2.28	1.37	1.11	0.39	0.50	0.16	0.16	0.08	0.12	0.10	0.10	0.12	0.08	0.05	0.06	0.02	0.01	0.03		0.01				
Nov 2023	7.65	5.59	2.25	2.33	1.45	1.14	0.47	0.33	0.17	0.16	0.11	0.12	0.13	0.11	0.12	0.10	0.06	0.06	0.01	0.01	0.03						
Dec 2023	7.48	5.60	2.20	2.19	1.53	1.12	0.54	0.33	0.16	0.16	0.12	0.12	0.11	0.11	0.12	0.09	0.06	0.06	0.01	0.01	0.03						
Jan 2024	7.64	5.61	2.37	2.21	1.55	1.17	0.65	0.25	0.17	0.16	0.15	0.14	0.13	0.12	0.11	0.10	0.08	0.06	0.01	0.01	0.01	0.01							
{{< /graph >}}

---

### Overall

At least one tracker was found on 15.88% of new episodes in January, growing 1.42% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "19.84%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "15.67%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.42%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.40%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.66%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.62%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "3.38%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.82%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.18%" >}}
10. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.92%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of January 2024.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 7.64% of new episodes in January, growing 2.22% from last month.

Of these, 22.23% had one other tracker, 12.79% had 2 other trackers, 2.87% had 3 other trackers, 1.73% had 4 other trackers, 0.83% had 5 other trackers, 0.61% had 6 other trackers, 0.20% had 7 other trackers, and 0.02% had 8 other trackers.

32.38% also included Chartable, 18.13% also included Podsights, 5.42% also included Podscribe, 4.62% also included Adswizz, 2.14% also included Magellan AI, 1.54% also included Podcorn, 1.34% also included ArtsAI, 1.31% also included Podder, 0.90% also included Spotify, 0.88% also included OP3, 0.84% also included Claritas, 0.76% also included Veritonic, 0.76% also included Podroll, 0.68% also included Gumshoe, 0.50% also included Blubrry, 0.25% also included Audiotakes, 0.09% also included Feedpress, 0.03% also included Médiamétrie, 0.02% also included Zencastr, 0.02% also included AdBarker, 0.02% also included United Podcasters, 0.01% also included Voxalyze, 0.01% also included Podkite, 0.01% also included CoHost Prefix, 0.01% also included Glystn, and <0.01% also included Firstory.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "40.36%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "19.83%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.63%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.43%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.72%" >}}
6. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.53%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.18%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.86%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.85%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.47%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 6.20% of new episodes in January, shrinking 0.26% from last month.

Of these, 44.35% also included Podtrac, 8.84% also included Podscribe, 5.98% also included Adswizz, 3.88% also included Magellan AI, 2.27% also included Podcorn, 2.13% also included Podder, 2.13% also included ArtsAI, 1.81% also included Claritas, 1.43% also included Podroll, 1.29% also included Gumshoe, 1.00% also included OP3, 0.97% also included Veritonic, 0.86% also included Firstory, 0.62% also included Audiotakes, 0.30% also included Blubrry, 0.08% also included Zencastr, 0.08% also included Feedpress, 0.06% also included AdBarker, 0.06% also included United Podcasters, 0.05% also included Voxalyze, 0.03% also included Podkite, 0.02% also included CoHost Prefix, and 0.01% also included Glystn.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.31%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.16%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.72%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.30%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.57%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.76%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.98%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.76%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.40%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.31%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.61% of new episodes in January, growing 0.11% from last month.

Of these, 32.90% had one other tracker, 18.44% had 2 other trackers, 4.33% had 3 other trackers, 2.63% had 4 other trackers, 1.04% had 5 other trackers, 0.82% had 6 other trackers, 0.25% had 7 other trackers, and 0.03% had 8 other trackers.

44.12% also included Podtrac, 29.45% also included Podsights, 7.26% also included Podscribe, 5.56% also included Adswizz, 3.64% also included Magellan AI, 2.16% also included Podder, 2.02% also included Podcorn, 1.86% also included ArtsAI, 1.81% also included Spotify, 1.63% also included Claritas, 1.44% also included Podroll, 0.95% also included Firstory, 0.92% also included Gumshoe, 0.91% also included Veritonic, 0.63% also included OP3, 0.34% also included Audiotakes, 0.27% also included Blubrry, 0.08% also included Feedpress, 0.08% also included Zencastr, 0.07% also included AdBarker, 0.06% also included Voxalyze, 0.05% also included United Podcasters, 0.03% also included Podkite, 0.02% also included CoHost Prefix, and 0.01% also included Glystn.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.28%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.74%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.52%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.48%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.93%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.95%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.80%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.75%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.66%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.54%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.37% of new episodes in January, growing 7.46% from last month.

Of these, 20.60% had one other tracker, 3.12% had 2 other trackers, 2.42% had 3 other trackers, 0.61% had 4 other trackers, 0.59% had 5 other trackers, 0.45% had 7 other trackers, and 0.36% had 6 other trackers.

14.91% also included Podtrac, 13.17% also included Chartable, 5.45% also included Podsights, 2.08% also included Podscribe, 1.70% also included Blubrry, 1.56% also included Audiotakes, 1.09% also included ArtsAI, 1.06% also included Claritas, 0.92% also included Spotify, 0.76% also included Podroll, 0.69% also included Veritonic, 0.45% also included Magellan AI, 0.36% also included Podcorn, 0.35% also included OP3, 0.09% also included Podder, 0.05% also included Gumshoe, and 0.05% also included Zencastr.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "36.69%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "14.62%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "10.28%" >}}
4. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "8.98%" >}}
5. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "6.93%" >}}
6. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "5.62%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.09%" >}}
8. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.33%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.30%" >}}
10. {{< a "https://www.julephosting.de/" "Julep Hosting" >}} {{< span "weak" "1.20%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.21% of new episodes in January, growing 0.63% from last month.

Of these, 39.11% had 2 other trackers, 29.85% had one other tracker, 9.83% had 3 other trackers, 6.97% had 4 other trackers, 3.44% had 5 other trackers, 2.07% had 6 other trackers, 0.64% had 7 other trackers, and 0.07% had 8 other trackers.

74.80% also included Chartable, 62.77% also included Podtrac, 18.92% also included Podscribe, 9.64% also included Magellan AI, 5.84% also included Adswizz, 4.87% also included ArtsAI, 4.48% also included Podder, 4.02% also included Claritas, 2.46% also included Gumshoe, 2.38% also included Veritonic, 2.28% also included Podcorn, 2.10% also included Podroll, 1.84% also included Spotify, 1.51% also included OP3, 1.50% also included Audiotakes, 0.21% also included Blubrry, 0.13% also included United Podcasters, 0.10% also included Feedpress, 0.07% also included Voxalyze, 0.04% also included Zencastr, 0.03% also included CoHost Prefix, 0.03% also included Podkite, and 0.02% also included Glystn.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "58.86%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "23.11%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.68%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.57%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.02%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.77%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.53%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.07%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.97%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.90%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.55% of new episodes in January, growing 1.19% from last month.

Of these, 6.27% had one other tracker, 0.59% had 2 other trackers, 0.08% had 3 other trackers, 0.06% had 4 other trackers, and <0.01% had 5 other trackers.

2.60% also included Adswizz, 2.46% also included Podtrac, 1.04% also included Feedpress, 0.98% also included Chartable, 0.30% also included Podsights, 0.20% also included Podcorn, 0.15% also included Podscribe, 0.11% also included OP3, 0.06% also included Podder, 0.03% also included Podroll, 0.01% also included Gumshoe, 0.01% also included Spotify, and <0.01% also included Claritas.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "37.55%" >}}
2. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "7.55%" >}}
3. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "7.24%" >}}
4. {{< a "https://www.rferl.org/" "Radio Free Europe and Radio Liberty" >}} {{< span "weak" "3.05%" >}}
5. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "2.90%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.98%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.69%" >}}
8. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.62%" >}}
9. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.58%" >}}
10. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.15%" >}}
---

### 6. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 1.17% of new episodes in January, growing 4.88% from last month.

Of these, 10.34% had one other tracker, 3.11% had 2 other trackers, 1.51% had 5 other trackers, 1.14% had 4 other trackers, 0.96% had 3 other trackers, 0.21% had 6 other trackers, 0.13% had 8 other trackers, and 0.04% had 7 other trackers.

10.01% also included Podtrac, 9.63% also included Chartable, 4.29% also included Podsights, 3.04% also included Gumshoe, 2.72% also included OP3, 1.74% also included Podscribe, 0.73% also included Adswizz, 0.69% also included Podder, 0.40% also included Podroll, 0.26% also included Blubrry, 0.16% also included Spotify, 0.10% also included Voxalyze, 0.10% also included Feedpress, 0.08% also included Claritas, 0.04% also included Podkite, 0.04% also included Zencastr, 0.04% also included CoHost Prefix, 0.04% also included Magellan AI, and 0.03% also included AdBarker.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "44.97%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "12.50%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "10.55%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.27%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "5.19%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.51%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.18%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.14%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.68%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.18%" >}}
---

### 7. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.65% of new episodes in January, growing 20.03% from last month.

Of these, 19.56% had 3 other trackers, 19.53% had 4 other trackers, 18.49% had one other tracker, 18.17% had 2 other trackers, 10.13% had 5 other trackers, 7.26% had 6 other trackers, 2.59% had 7 other trackers, and 0.17% had 8 other trackers.

64.00% also included Podsights, 63.43% also included Podtrac, 62.36% also included Chartable, 28.40% also included Magellan AI, 16.51% also included ArtsAI, 15.52% also included Claritas, 14.27% also included Spotify, 8.21% also included Veritonic, 7.56% also included Adswizz, 5.80% also included Audiotakes, 4.93% also included Gumshoe, 4.13% also included Podder, 3.32% also included OP3, 3.23% also included Podroll, 3.14% also included Podcorn, 0.36% also included Blubrry, 0.23% also included United Podcasters, and 0.02% also included Feedpress.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "54.33%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.08%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "7.28%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.72%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.32%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.32%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.30%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.48%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.83%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.00%" >}}
---

### 8. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.25% of new episodes in January, growing 5.14% from last month.

Of these, 41.42% had 4 other trackers, 16.52% had 5 other trackers, 13.75% had 6 other trackers, 12.58% had 3 other trackers, 7.22% had 2 other trackers, 4.40% had 7 other trackers, and 3.07% had one other tracker.

85.52% also included Podsights, 81.92% also included Chartable, 74.48% also included Podscribe, 65.68% also included Podtrac, 26.90% also included Claritas, 21.51% also included ArtsAI, 18.14% also included Podder, 14.50% also included Veritonic, 12.42% also included Spotify, 4.67% also included Audiotakes, 4.31% also included Adswizz, 3.83% also included Podroll, 2.45% also included Gumshoe, 0.25% also included United Podcasters, and 0.18% also included Podcorn.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "70.90%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.77%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.23%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.00%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.87%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.82%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.73%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.30%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.14%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.14%" >}}
---

### 9. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.25% of new episodes in January, shrinking 24.41% from last month.

Of these, 0.85% had one other tracker.

0.85% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "63.47%" >}}
2. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "14.43%" >}}
3. {{< a "https://soundcast.fm/" "SoundCast" >}} {{< span "weak" "12.86%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "4.30%" >}}
5. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "2.60%" >}}
6. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "1.13%" >}}
7. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "0.21%" >}}
---

### 10. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.17% of new episodes in January, growing 2.01% from last month.

Of these, 15.52% had one other tracker, 1.16% had 2 other trackers, 0.21% had 4 other trackers, 0.07% had 5 other trackers, and 0.03% had 3 other trackers.

9.64% also included Blubrry, 4.17% also included Podtrac, 2.84% also included Chartable, 1.33% also included Podsights, 0.68% also included Podcorn, 0.27% also included Claritas, 0.10% also included OP3, and 0.07% also included Podscribe.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "50.75%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.45%" >}}
3. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "5.33%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.85%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.10%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "4.10%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.32%" >}}
8. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.91%" >}}
9. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.88%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.78%" >}}
---

### 11. [Podder](https://www.podderapp.com/)

Podder was found on 0.16% of new episodes in January, shrinking 1.12% from last month.

Of these, 21.70% had 3 other trackers, 19.36% had 4 other trackers, 15.37% had 2 other trackers, 13.41% had one other tracker, 11.48% had 5 other trackers, 1.58% had 6 other trackers, 1.37% had 7 other trackers, and 0.42% had 8 other trackers.

74.31% also included Chartable, 61.46% also included Podtrac, 60.73% also included Podsights, 27.72% also included Magellan AI, 16.56% also included Podscribe, 7.56% also included Podroll, 5.01% also included Podcorn, 2.98% also included OP3, 2.42% also included Gumshoe, 1.75% also included Claritas, 1.51% also included ArtsAI, 1.33% also included Adswizz, 0.77% also included Spotify, 0.77% also included Veritonic, 0.53% also included Blubrry, 0.32% also included CoHost Prefix, 0.28% also included United Podcasters, 0.28% also included Zencastr, and 0.18% also included Podkite.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "69.13%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "7.77%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.78%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.48%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.61%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.77%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.68%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.84%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.77%" >}}
10. {{< a "https://www.thepodops.com/" "PodOps" >}} {{< span "weak" "0.67%" >}}
---

### 12. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.15% of new episodes in January, growing 26.93% from last month.

Of these, 35.63% had 2 other trackers, 25.02% had 3 other trackers, 15.13% had 4 other trackers, 9.43% had one other tracker, 7.38% had 7 other trackers, 2.89% had 5 other trackers, 1.71% had 6 other trackers, and 0.53% had 8 other trackers.

67.60% also included Chartable, 62.13% also included Podscribe, 45.63% also included Podtrac, 27.03% also included Podsights, 20.61% also included Magellan AI, 16.77% also included ArtsAI, 15.21% also included Claritas, 14.52% also included Adswizz, 9.35% also included Gumshoe, 5.44% also included Veritonic, 4.68% also included OP3, 4.64% also included Audiotakes, 1.22% also included Podcorn, 1.14% also included Podroll, 0.84% also included Podder, and 0.08% also included Blubrry.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.23%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "16.96%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "15.67%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.97%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.43%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "5.17%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.06%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.74%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "2.47%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.95%" >}}
---

### 13. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.14% of new episodes in January, growing 12.95% from last month.

Of these, 24.63% had 6 other trackers, 21.30% had 3 other trackers, 18.52% had 4 other trackers, 15.94% had 5 other trackers, 11.26% had 7 other trackers, 6.92% had 2 other trackers, and 0.89% had one other tracker.

79.71% also included Podscribe, 79.50% also included Podsights, 77.18% also included Chartable, 75.66% also included Podtrac, 39.60% also included Magellan AI, 31.34% also included Claritas, 26.61% also included Veritonic, 19.02% also included Adswizz, 18.60% also included Spotify, 7.09% also included Audiotakes, 1.81% also included Podder, 1.52% also included Gumshoe, and 1.35% also included Podroll.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.63%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.75%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "12.99%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.54%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.28%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "7.47%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.60%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.35%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.76%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.25%" >}}
---

### 14. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.13% of new episodes in January, growing 16.81% from last month.

Of these, 25.37% had one other tracker, 12.92% had 5 other trackers, 10.23% had 4 other trackers, 9.72% had 2 other trackers, 6.78% had 3 other trackers, 1.75% had 6 other trackers, 0.51% had 8 other trackers, and 0.30% had 7 other trackers.

50.45% also included Podtrac, 26.52% also included Chartable, 26.06% also included Gumshoe, 24.95% also included Podsights, 23.92% also included Podcorn, 16.20% also included Podscribe, 6.18% also included Adswizz, 5.25% also included Spotify, 3.62% also included Podder, 2.47% also included Podroll, 1.32% also included Blubrry, 0.26% also included CoHost Prefix, 0.13% also included Feedpress, and 0.04% also included Voxalyze.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "39.32%" >}}
2. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "12.20%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.61%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.48%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.80%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.11%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.05%" >}}
8. {{< a "https://podnews.net/" "Podnews" >}} {{< span "weak" "1.96%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.96%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.83%" >}}
---

### 15. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.12% of new episodes in January, growing 9.99% from last month.

Of these, 28.41% had 4 other trackers, 21.52% had 5 other trackers, 18.94% had 6 other trackers, 9.90% had 3 other trackers, 8.70% had 7 other trackers, 6.31% had 2 other trackers, 3.63% had one other tracker, and 0.67% had 8 other trackers.

84.98% also included Podscribe, 76.61% also included Chartable, 74.46% also included Podsights, 56.15% also included Magellan AI, 54.14% also included Podtrac, 35.53% also included ArtsAI, 21.09% also included Adswizz, 19.13% also included Spotify, 17.50% also included Veritonic, 2.92% also included Podroll, 2.39% also included Podder, 1.00% also included Gumshoe, 0.77% also included Podcorn, 0.38% also included Feedpress, and 0.05% also included Blubrry.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "40.46%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "21.62%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "14.40%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.28%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "7.27%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.54%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.53%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.33%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.24%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.24%" >}}
---

### 16. [Podroll](https://podroll.fm/)

Podroll was found on 0.11% of new episodes in January, shrinking 5.38% from last month.

Of these, 30.67% had 3 other trackers, 25.59% had 2 other trackers, 10.82% had one other tracker, 7.68% had 4 other trackers, 4.24% had 5 other trackers, 1.80% had 7 other trackers, 1.30% had 8 other trackers, and 0.95% had 6 other trackers.

70.77% also included Chartable, 50.92% also included Podtrac, 40.65% also included Podsights, 18.45% also included Podscribe, 15.71% also included Adswizz, 10.77% also included Podder, 8.33% also included Magellan AI, 4.14% also included Podcorn, 3.99% also included Gumshoe, 3.04% also included Claritas, 2.89% also included OP3, 1.60% also included ArtsAI, 1.50% also included Spotify, 0.50% also included Voxalyze, 0.50% also included United Podcasters, 0.45% also included CoHost Prefix, and 0.35% also included Blubrry.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "43.19%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "14.46%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "13.62%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.47%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "5.24%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.14%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.75%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.60%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.60%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.45%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.10% of new episodes in January, growing 10.88% from last month.

Of these, 18.86% had 5 other trackers, 17.98% had 4 other trackers, 17.63% had 3 other trackers, 14.76% had 2 other trackers, 11.60% had one other tracker, 2.64% had 7 other trackers, 2.58% had 6 other trackers, and 1.52% had 8 other trackers.

55.83% also included Podsights, 53.31% also included Podtrac, 52.90% also included Chartable, 36.67% also included Podcorn, 35.79% also included OP3, 33.04% also included Podscribe, 14.41% also included Spotify, 6.27% also included Magellan AI, 4.69% also included Podroll, 4.04% also included Podder, 3.10% also included Audiotakes, 2.11% also included ArtsAI, 1.29% also included Adswizz, 1.23% also included Claritas, 1.11% also included United Podcasters, 0.35% also included CoHost Prefix, 0.18% also included Blubrry, and 0.06% also included Voxalyze.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "36.67%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.93%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "21.73%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.57%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.64%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.41%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.70%" >}}
8. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.29%" >}}
9. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.23%" >}}
10. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.23%" >}}
---

### 18. [Firstory](https://firstory.me/)

Firstory was found on 0.08% of new episodes in January, shrinking 7.36% from last month.

Of these, 69.07% had one other tracker, and 0.15% had 2 other trackers.

69.21% also included Chartable, and 0.15% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.55%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.45%" >}}
---

### 19. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.08% of new episodes in January, growing 16.33% from last month.

Of these, 47.95% had one other tracker, 19.80% had 4 other trackers, 11.53% had 3 other trackers, 10.47% had 2 other trackers, 6.07% had 5 other trackers, 2.73% had 7 other trackers, and 1.06% had 6 other trackers.

50.38% also included Podscribe, 49.17% also included Adswizz, 44.08% also included Podsights, 25.42% also included Podtrac, 25.19% also included Chartable, 15.48% also included Magellan AI, 12.75% also included ArtsAI, 9.26% also included Spotify, 4.02% also included Gumshoe, and 2.81% also included Veritonic.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "22.15%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "15.02%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.04%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.03%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.35%" >}}
6. {{< a "https://kostenlos-hosten.de/" "Podcastbude" >}} {{< span "weak" "1.75%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.29%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.68%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.61%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.38%" >}}
---

### 20. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.06% of new episodes in January, growing 12.14% from last month.

Of these, 53.82% had 6 other trackers, 14.26% had 7 other trackers, 12.51% had 5 other trackers, 10.12% had 4 other trackers, 3.31% had 2 other trackers, 3.04% had one other tracker, and 2.48% had 3 other trackers.

94.02% also included Podtrac, 86.48% also included Podscribe, 84.82% also included Podsights, 82.61% also included Chartable, 58.23% also included Magellan AI, 58.05% also included ArtsAI, 33.67% also included Claritas, 26.40% also included Adswizz, 13.16% also included Spotify, 3.40% also included Audiotakes, and 2.02% also included Podder.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "59.43%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "24.10%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "6.35%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.23%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.58%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.84%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.92%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.28%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.09%" >}}
---

### 21. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in January, growing 7.69% from last month.

Of these, 25.00% had one other tracker, 21.36% had 2 other trackers, and 2.27% had 3 other trackers.

37.73% also included Chartable, 13.18% also included Podtrac, 9.55% also included Adswizz, 6.36% also included Podsights, 4.09% also included Podcorn, and 3.64% also included Podder.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "100.00%" >}}
---

### 22. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in January, shrinking 0.09% from last month.

Of these, 30.16% had one other tracker, 3.97% had 2 other trackers, and 3.97% had 5 other trackers.

26.19% also included Chartable, 12.70% also included Podtrac, 7.94% also included Podsights, 7.14% also included Podcorn, and 3.97% also included Podder.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "44.44%" >}}
2. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "14.29%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "12.70%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.14%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.56%" >}}
6. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "5.56%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.97%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.97%" >}}
9. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.59%" >}}
10. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "0.79%" >}}
---

### 23. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on 0.01% of new episodes in January, shrinking 80.22% from last month.

Of these, 37.38% had one other tracker, 20.56% had 3 other trackers, 10.28% had 2 other trackers, and 0.93% had 4 other trackers.

51.40% also included Chartable, 24.30% also included Podsights, 19.63% also included Podcorn, 16.82% also included Podtrac, 9.35% also included Podroll, 0.93% also included OP3, and 0.93% also included Gumshoe.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "42.06%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "20.56%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "17.76%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.41%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.80%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.80%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.87%" >}}
8. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "1.87%" >}}
9. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "0.93%" >}}
10. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "0.93%" >}}
---

### 24. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in January, growing 9.33% from last month.

Of these, 42.86% had one other tracker, and 30.61% had 2 other trackers.

70.41% also included Chartable, 26.53% also included Podtrac, and 7.14% also included Podcorn.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "33.67%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "21.43%" >}}
3. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "18.37%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "18.37%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.10%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.06%" >}}
---

### 25. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in January, shrinking 3.07% from last month.

Of these, 32.65% had one other tracker, 26.53% had 4 other trackers, 18.37% had 3 other trackers, and 5.10% had 2 other trackers.

53.06% also included Podsights, 53.06% also included Chartable, 26.53% also included Podscribe, 22.45% also included Podtrac, 19.39% also included Gumshoe, 11.22% also included Magellan AI, 10.20% also included Podroll, and 8.16% also included Podder.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "30.61%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.61%" >}}
3. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "20.41%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "17.35%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.02%" >}}
---

### 26. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on <0.01% of new episodes in January, growing 74.44% from last month.

Of these, 55.00% had 3 other trackers, and 30.00% had 8 other trackers.

85.00% also included Chartable, 70.00% also included Podtrac, 55.00% also included Podsights, 45.00% also included Podcorn, 45.00% also included Podroll, 45.00% also included Podder, 30.00% also included OP3, and 30.00% also included Gumshoe.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "45.00%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "25.00%" >}}
3. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "20.00%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.00%" >}}
---

### 27. [Glystn](https://glystn.com/)

Glystn was found on <0.01% of new episodes in January, growing 11.93% from last month.

Of these, 64.29% had 3 other trackers, and 35.71% had one other tracker.

100.00% also included Chartable, 64.29% also included Podtrac, and 64.29% also included Podsights.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "64.29%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "35.71%" >}}
---

### 28. [Zippycast](https://zippycast.io/)

Zippycast was found on <0.01% of new episodes in January, shrinking 82.23% from last month.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "100.00%" >}}


---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
*Updated 2024-02-02, with data for the month of January 2024.*

*Updated 2024-01-01, with data for the month of December 2023.*

*Updated 2023-12-03, with data for the month of November 2023.*

*Updated 2023-11-02, with data for the month of October 2023. Improved accuracy in observing Spotify for Podcasters podcasts: more S4P new episodes leads to lower share of prefixed episodes overall.*

*Updated 2023-10-01, with data for the month of September 2023. Improved accuracy in observing Spotify for Podcasters podcasts: more S4P new episodes leads to lower share of prefixed episodes overall.*

*Updated 2023-09-01, with data for the month of August 2023.*

*Updated 2023-08-01, with data for the month of July 2023.*

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
 - [Podcast Tracker Rankings by Episode Share (December 2023)](/archive/podcast-trackers-by-episode-share-december-2023/)
 - [Podcast Tracker Rankings by Episode Share (November 2023)](/archive/podcast-trackers-by-episode-share-november-2023/)
 - [Podcast Tracker Rankings by Episode Share (October 2023)](/archive/podcast-trackers-by-episode-share-october-2023/)
 - [Podcast Tracker Rankings by Episode Share (September 2023)](/archive/podcast-trackers-by-episode-share-september-2023/)
 - [Podcast Tracker Rankings by Episode Share (August 2023)](/archive/podcast-trackers-by-episode-share-august-2023/)
 - [Podcast Tracker Rankings by Episode Share (July 2023)](/archive/podcast-trackers-by-episode-share-july-2023/)
 - [Podcast Tracker Rankings by Episode Share (June 2023)](/archive/podcast-trackers-by-episode-share-june-2023/)
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2024-01.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
