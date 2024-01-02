---
title: "Top Podcast Tracking Services by Episode Share (November 2023)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-november-2023"
images:
- trackers-2023-11.png
date: 2023-12-03T10:27:00-06:00
lastmod: 2023-12-03T10:27:00-06:00
draft: false
rssrevision: 2023-11
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.8 million in November 2023), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in October, how many
of them included one or more of these tracking services?  Some episodes had as many as *ten* of these redirecting trackers!

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
Month	Podtrac	Chartable	Podsights	Adswizz	Blubrry	Podcorn	Podscribe	Médiamétrie	Feedpress	Podder	OP3	Podroll	ArtsAI	Claritas	Spotify	Gumshoe	Veritonic	Audiotakes	Voxalyze	Zencastr	Podkite	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.16	1.00	2.07	2.09		0.42	0.32																	1.61
Oct 2021	4.05	4.09	1.20	1.01	2.11	2.13		0.54	0.34																	1.61
Nov 2021	4.07	4.30	1.25	1.02	2.01	2.14		0.57	0.32																	0.59
Dec 2021	4.06	4.42	1.19	1.24	1.57	2.27		0.59	0.19																	
Jan 2022	4.11	4.45	1.21	1.41	1.56	2.31		0.63	0.16																	
Feb 2022	4.15	4.48	1.25	1.44	1.53	2.38		0.58	0.17																	
Mar 2022	4.37	4.72	1.34	1.51	1.56	2.40		0.53	0.17																	
Apr 2022	4.44	4.71	1.33	1.49	1.55	2.33		0.51	0.16																	
May 2022	4.49	4.87	1.41	1.58	1.48	2.26		0.56	0.17																	
Jun 2022	4.75	5.10	1.54	1.77	1.50	2.06		0.62	0.21														0.02			
Jul 2022	4.70	5.10	1.50	1.89	1.50	2.16		0.54	0.25														0.02			
Aug 2022	4.83	5.26	1.73	2.08	1.51	2.45		0.41	0.20				0.10										0.01			
Sep 2022	7.53	5.40	1.74	2.26	1.49	2.45	0.02	0.52	0.21				0.09	0.01							0.01		0.02	0.02		
Oct 2022	8.24	5.48	1.81	2.35	1.61	2.51	0.07	0.50	0.18		0.03		0.10	0.02						0.01	0.01		0.02	0.04		
Nov 2022	8.11	5.62	2.03	2.37	1.62	2.43	0.15	0.50	0.18	0.01	0.04		0.10	0.03						0.01	0.01		0.02	0.05		
Dec 2022	8.01	5.54	1.81	2.32	1.61	2.05	0.03	0.49	0.18	0.04	0.05		0.05	0.02						0.01	0.01	0.01	0.02	0.05		
Jan 2023	7.85	5.56	1.88	2.35	1.61	2.15	0.20	0.54	0.18	0.11	0.07		0.10	0.06						0.01	0.01	0.01	0.02	0.06		
Feb 2023	7.58	5.51	1.92	2.29	1.62	2.30	0.21	0.49	0.19	0.11	0.07		0.10	0.07						0.01	0.01	0.01	0.02	0.06	0.03	
Mar 2023	7.79	5.53	2.03	2.25	1.53	2.22	0.21	0.45	0.18	0.11	0.08	0.04	0.11	0.07			0.04			0.01	0.01	0.01	0.02	0.06		
Apr 2023	7.66	5.43	2.00	2.26	1.67	2.20	0.21	0.45	0.17	0.15	0.09	0.06	0.11	0.07		0.08	0.05			0.01	0.01	0.01	0.01			
May 2023	7.58	5.59	2.04	2.27	1.67	2.28	0.24	0.45	0.19	0.15	0.09	0.09	0.11	0.08		0.07	0.05		0.01	0.01	0.01	0.01	0.01			
Jun 2023	8.22	5.83	2.23	2.39	1.64	1.86	0.26	0.51	0.19	0.15	0.09	0.10	0.12	0.07		0.08	0.05		0.01	0.01	0.01	0.01	0.01			
Jul 2023	8.60	5.95	2.52	2.38	1.53	1.17	0.27	0.55	0.18	0.14	0.08	0.14	0.11	0.07	0.01	0.06	0.06		0.01	0.01	0.01	0.01	0.01			
Aug 2023	9.19	6.43	2.76	2.72	1.58	1.23	0.36	0.53	0.17	0.15	0.11	0.16	0.12	0.08	0.03	0.07	0.07	0.04	0.02	0.01	0.01	0.01				
Sep 2023	8.46	5.77	2.47	2.49	1.39	1.10	0.37	0.58	0.16	0.15	0.10	0.13	0.12	0.10	0.05	0.07	0.06	0.05	0.02	0.01	0.01	0.01				
Oct 2023	7.90	5.54	2.28	2.29	1.37	1.11	0.39	0.50	0.16	0.16	0.10	0.12	0.12	0.10	0.08	0.08	0.06	0.05	0.03	0.02	0.01	0.01				
Nov 2023	7.65	5.59	2.33	2.25	1.45	1.14	0.47	0.33	0.17	0.16	0.13	0.12	0.12	0.11	0.11	0.10	0.06	0.06	0.03	0.01	0.01					
{{< /graph >}}

---

### Overall

At least one tracker was found on 15.73% of new episodes in November, shrinking 1.99% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "20.39%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "16.14%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.11%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.81%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.78%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.74%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "3.11%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.73%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.09%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.99%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of November 2023.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 7.65% of new episodes in November, shrinking 3.08% from last month.

Of these, 23.16% had one other tracker, 12.48% had 2 other trackers, 2.69% had 3 other trackers, 1.34% had 4 other trackers, 0.94% had 5 other trackers, 0.51% had 6 other trackers, 0.13% had 7 other trackers, 0.01% had 8 other trackers, and <0.01% had 9 other trackers.

32.24% also included Chartable, 19.01% also included Podsights, 4.35% also included Adswizz, 3.43% also included Podscribe, 1.84% also included Podcorn, 1.68% also included Magellan AI, 1.28% also included Podder, 1.08% also included ArtsAI, 1.02% also included OP3, 0.82% also included Podroll, 0.79% also included Gumshoe, 0.77% also included Claritas, 0.68% also included Veritonic, 0.53% also included Blubrry, 0.42% also included Spotify, 0.12% also included Voxalyze, 0.09% also included Feedpress, 0.08% also included Audiotakes, 0.03% also included Médiamétrie, 0.02% also included Zencastr, 0.02% also included Podkite, 0.01% also included AdBarker, 0.01% also included Glystn, <0.01% also included CoHost Prefix, and <0.01% also included Firstory.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "40.88%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "20.29%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "12.55%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.76%" >}}
5. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.44%" >}}
6. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.36%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.10%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.74%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.53%" >}}
10. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "1.13%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 6.30% of new episodes in November, shrinking 0.05% from last month.

Of these, 44.71% also included Podtrac, 6.66% also included Podscribe, 6.09% also included Adswizz, 3.01% also included Magellan AI, 2.52% also included Podcorn, 2.04% also included Podder, 1.87% also included ArtsAI, 1.68% also included Claritas, 1.50% also included Podroll, 1.36% also included Gumshoe, 1.16% also included OP3, 0.94% also included Veritonic, 0.87% also included Firstory, 0.42% also included Audiotakes, 0.34% also included Blubrry, 0.25% also included Voxalyze, 0.07% also included Zencastr, 0.07% also included Feedpress, 0.05% also included AdBarker, 0.03% also included Podkite, 0.01% also included Glystn, and 0.01% also included CoHost Prefix.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.43%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.72%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.45%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.43%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.33%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.79%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.91%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.85%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.40%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.26%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.59% of new episodes in November, growing 0.89% from last month.

Of these, 34.79% had one other tracker, 17.99% had 2 other trackers, 4.38% had 3 other trackers, 1.95% had 4 other trackers, 0.83% had 5 other trackers, 0.68% had 6 other trackers, 0.15% had 7 other trackers, 0.01% had 8 other trackers, and <0.01% had 9 other trackers.

44.12% also included Podtrac, 29.41% also included Podsights, 5.36% also included Podscribe, 5.34% also included Adswizz, 2.78% also included Magellan AI, 2.05% also included Podder, 1.94% also included Podcorn, 1.63% also included ArtsAI, 1.53% also included Podroll, 1.52% also included Claritas, 1.32% also included Spotify, 0.98% also included Firstory, 0.88% also included Veritonic, 0.71% also included Gumshoe, 0.51% also included OP3, 0.30% also included Blubrry, 0.27% also included Voxalyze, 0.21% also included Audiotakes, 0.07% also included Zencastr, 0.07% also included Feedpress, 0.06% also included AdBarker, 0.03% also included Podkite, 0.01% also included Glystn, and 0.01% also included CoHost Prefix.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.65%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.39%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.79%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.45%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.75%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.11%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.83%" >}}
8. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.71%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.52%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.39%" >}}
---

### 3. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.33% of new episodes in November, growing 2.34% from last month.

Of these, 37.20% had 2 other trackers, 34.10% had one other tracker, 9.31% had 3 other trackers, 5.73% had 4 other trackers, 3.45% had 5 other trackers, 1.65% had 6 other trackers, 0.37% had 7 other trackers, 0.03% had 8 other trackers, and 0.01% had 9 other trackers.

70.64% also included Chartable, 62.48% also included Podtrac, 14.80% also included Podscribe, 7.34% also included Magellan AI, 6.99% also included Adswizz, 4.15% also included Podder, 4.08% also included ArtsAI, 3.50% also included Claritas, 3.08% also included Podcorn, 2.91% also included Gumshoe, 2.21% also included Veritonic, 2.19% also included OP3, 2.00% also included Podroll, 1.25% also included Spotify, 1.03% also included Audiotakes, 0.35% also included Voxalyze, 0.25% also included Blubrry, 0.07% also included Feedpress, 0.04% also included Podkite, 0.03% also included Zencastr, 0.02% also included Glystn, and 0.01% also included CoHost Prefix.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "55.60%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "26.26%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.73%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.30%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.84%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.68%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.40%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.97%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.91%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.87%" >}}
---

### 4. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.25% of new episodes in November, shrinking 1.77% from last month.

Of these, 22.32% had one other tracker, 2.87% had 2 other trackers, 2.53% had 3 other trackers, 0.52% had 4 other trackers, 0.50% had 6 other trackers, 0.46% had 5 other trackers, and 0.25% had 7 other trackers.

14.81% also included Podtrac, 13.27% also included Chartable, 7.23% also included Podsights, 2.40% also included Blubrry, 1.46% also included Podscribe, 1.17% also included Audiotakes, 1.04% also included ArtsAI, 0.91% also included Claritas, 0.75% also included Podroll, 0.72% also included Veritonic, 0.31% also included Magellan AI, 0.28% also included Spotify, 0.18% also included OP3, 0.12% also included Podcorn, 0.09% also included Podder, and 0.03% also included Gumshoe.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "33.86%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "14.63%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "9.71%" >}}
4. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "9.60%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.36%" >}}
6. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "6.84%" >}}
7. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "4.21%" >}}
8. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.48%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.46%" >}}
10. {{< a "https://www.mediastre.am/" "mediastream" >}} {{< span "weak" "1.40%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.45% of new episodes in November, growing 5.83% from last month.

Of these, 7.84% had one other tracker, 0.61% had 2 other trackers, 0.08% had 3 other trackers, 0.05% had 4 other trackers, and 0.01% had 6 other trackers.

3.73% also included Adswizz, 2.78% also included Podtrac, 1.17% also included Chartable, 0.95% also included Feedpress, 0.40% also included Podsights, 0.25% also included Podcorn, 0.12% also included Podscribe, 0.11% also included OP3, 0.03% also included Podder, 0.01% also included Voxalyze, 0.01% also included Podroll, 0.01% also included Magellan AI, 0.01% also included ArtsAI, <0.01% also included Spotify, and <0.01% also included Claritas.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "41.09%" >}}
2. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "7.61%" >}}
3. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.21%" >}}
4. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "2.99%" >}}
5. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "2.35%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.27%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.63%" >}}
8. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.43%" >}}
9. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.17%" >}}
10. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.86%" >}}
---

### 6. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 1.14% of new episodes in November, growing 2.75% from last month.

Of these, 10.32% had one other tracker, 3.57% had 2 other trackers, 2.90% had 5 other trackers, 1.40% had 4 other trackers, 1.07% had 3 other trackers, 0.11% had 6 other trackers, 0.10% had 7 other trackers, 0.07% had 8 other trackers, and 0.02% had 9 other trackers.

12.32% also included Podtrac, 9.51% also included Chartable, 6.30% also included Podsights, 4.62% also included Gumshoe, 4.32% also included OP3, 3.07% also included Podscribe, 0.70% also included Podder, 0.67% also included Voxalyze, 0.37% also included Podroll, 0.32% also included Blubrry, 0.24% also included Adswizz, 0.11% also included Zencastr, 0.10% also included Spotify, 0.10% also included Magellan AI, 0.08% also included Podkite, 0.06% also included Feedpress, 0.04% also included AdBarker, and 0.01% also included CoHost Prefix.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "42.32%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.85%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "11.11%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.66%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "6.52%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "5.39%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.49%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.31%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.59%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.25%" >}}
---

### 7. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.47% of new episodes in November, growing 22.84% from last month.

Of these, 23.20% had 3 other trackers, 17.82% had 4 other trackers, 14.36% had 5 other trackers, 14.16% had 2 other trackers, 13.27% had one other tracker, 8.61% had 6 other trackers, 2.09% had 7 other trackers, 0.06% had 9 other trackers, and 0.02% had 8 other trackers.

72.69% also included Podsights, 63.24% also included Chartable, 55.30% also included Podtrac, 27.00% also included Magellan AI, 19.24% also included ArtsAI, 18.93% also included Claritas, 10.67% also included Veritonic, 10.13% also included Spotify, 8.73% also included Gumshoe, 7.37% also included Podcorn, 6.94% also included Adswizz, 6.41% also included OP3, 5.59% also included Audiotakes, 4.34% also included Podroll, 4.09% also included Podder, 0.36% also included Blubrry, 0.08% also included Voxalyze, and 0.07% also included Podkite.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "48.19%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.72%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "8.95%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "6.66%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.51%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.85%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.52%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.69%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.26%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.05%" >}}
---

### 8. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.33% of new episodes in November, shrinking 34.02% from last month.

Of these, 0.70% had one other tracker.

0.70% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "46.82%" >}}
2. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "18.41%" >}}
3. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "11.05%" >}}
4. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "9.31%" >}}
5. {{< a "https://soundcast.fm/" "SoundCast" >}} {{< span "weak" "8.38%" >}}
6. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "3.15%" >}}
7. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "2.25%" >}}
---

### 9. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.20% of new episodes in November, growing 26.76% from last month.

Of these, 38.00% had 4 other trackers, 17.28% had 3 other trackers, 13.76% had 5 other trackers, 12.47% had 6 other trackers, 8.92% had 2 other trackers, 5.37% had one other tracker, and 3.16% had 7 other trackers.

86.08% also included Podsights, 78.29% also included Chartable, 64.80% also included Podtrac, 64.47% also included Podscribe, 23.03% also included Claritas, 21.82% also included Podder, 18.35% also included ArtsAI, 12.77% also included Veritonic, 10.70% also included Podroll, 5.15% also included Spotify, 3.49% also included Adswizz, 2.12% also included Audiotakes, 0.99% also included Gumshoe, 0.58% also included Podcorn, 0.08% also included Voxalyze, and 0.06% also included Blubrry.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "73.80%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.49%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.44%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.31%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.38%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.81%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.94%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.39%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.28%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.11%" >}}
---

### 10. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.17% of new episodes in November, growing 5.99% from last month.

Of these, 14.27% had one other tracker, and 1.15% had 2 other trackers.

8.21% also included Blubrry, 4.25% also included Podtrac, 2.42% also included Chartable, 1.01% also included Podsights, 0.43% also included Podcorn, 0.16% also included OP3, and 0.07% also included Podder.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "46.60%" >}}
2. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "9.69%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.97%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.91%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.58%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.80%" >}}
7. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "2.13%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.03%" >}}
9. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.64%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.47%" >}}
---

### 11. [Podder](https://www.podderapp.com/)

Podder was found on 0.16% of new episodes in November, growing 2.57% from last month.

Of these, 22.62% had 3 other trackers, 17.66% had 4 other trackers, 17.15% had 2 other trackers, 12.73% had one other tracker, 9.66% had 5 other trackers, 2.23% had 6 other trackers, 0.95% had 7 other trackers, 0.47% had 8 other trackers, and 0.17% had 9 other trackers.

70.83% also included Chartable, 60.57% also included Podtrac, 59.72% also included Podsights, 26.77% also included Magellan AI, 11.99% also included Podscribe, 8.31% also included Podroll, 4.96% also included Podcorn, 4.15% also included Claritas, 3.68% also included OP3, 2.87% also included Gumshoe, 1.49% also included ArtsAI, 1.32% also included Adswizz, 0.78% also included Veritonic, 0.71% also included Voxalyze, 0.41% also included Spotify, 0.24% also included Blubrry, 0.17% also included Podkite, 0.07% also included CoHost Prefix, and 0.07% also included Feedpress.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "69.01%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "8.34%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.96%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.92%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.81%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.65%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.99%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.92%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.88%" >}}
10. {{< a "https://www.thepodops.com/" "PodOps" >}} {{< span "weak" "0.37%" >}}
---

### 12. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.13% of new episodes in November, growing 23.34% from last month.

Of these, 25.66% had 5 other trackers, 23.53% had one other tracker, 11.43% had 2 other trackers, 11.09% had 4 other trackers, 1.95% had 3 other trackers, 0.98% had 6 other trackers, 0.59% had 8 other trackers, 0.21% had 7 other trackers, and 0.21% had 9 other trackers.

60.75% also included Podtrac, 39.63% also included Podsights, 38.32% also included Podcorn, 37.68% also included Gumshoe, 23.62% also included Podscribe, 22.22% also included Chartable, 4.63% also included Podder, 3.10% also included Adswizz, 2.63% also included Podroll, 2.46% also included Voxalyze, 2.21% also included Spotify, 1.19% also included Blubrry, 0.25% also included Podkite, and 0.21% also included Feedpress.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "46.73%" >}}
2. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "11.94%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.42%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.16%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.44%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.85%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.55%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.38%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.74%" >}}
10. {{< a "https://letscast.fm/" "LetsCast.fm" >}} {{< span "weak" "1.27%" >}}
---

### 13. [Podroll](https://podroll.fm/)

Podroll was found on 0.12% of new episodes in November, shrinking 1.02% from last month.

Of these, 27.26% had 2 other trackers, 18.48% had 4 other trackers, 18.16% had 3 other trackers, 8.65% had one other tracker, 3.23% had 5 other trackers, 2.02% had 6 other trackers, 1.84% had 7 other trackers, 0.54% had 8 other trackers, and 0.22% had 9 other trackers.

70.27% also included Chartable, 51.43% also included Podtrac, 38.30% also included Podsights, 17.44% also included Magellan AI, 16.91% also included Podscribe, 13.90% also included Adswizz, 11.03% also included Podder, 3.86% also included Voxalyze, 3.81% also included Claritas, 3.54% also included Gumshoe, 3.45% also included Podcorn, 2.78% also included OP3, 1.35% also included ArtsAI, 0.72% also included Spotify, 0.13% also included Blubrry, and 0.09% also included CoHost Prefix.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "41.52%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "22.42%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "12.83%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.76%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.00%" >}}
6. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "2.38%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.79%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.75%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.35%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.26%" >}}
---

### 14. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.12% of new episodes in November, growing 2.23% from last month.

Of these, 24.17% had 6 other trackers, 18.05% had 5 other trackers, 17.28% had 3 other trackers, 15.83% had 2 other trackers, 15.37% had 4 other trackers, 6.62% had 7 other trackers, and 1.77% had one other tracker.

78.91% also included Podsights, 75.74% also included Podscribe, 75.60% also included Chartable, 68.93% also included Podtrac, 30.43% also included Claritas, 30.25% also included Magellan AI, 28.16% also included Veritonic, 19.46% also included Adswizz, 9.66% also included Spotify, 6.39% also included Audiotakes, 2.00% also included Podder, 1.41% also included Gumshoe, 1.36% also included Podroll, and 0.09% also included Blubrry.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.88%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.54%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "13.11%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.16%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.84%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "8.30%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.81%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.41%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.32%" >}}
10. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.23%" >}}
---

### 15. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.11% of new episodes in November, growing 8.02% from last month.

Of these, 24.25% had 3 other trackers, 20.51% had 4 other trackers, 18.20% had 6 other trackers, 17.56% had 5 other trackers, 7.43% had 7 other trackers, 6.59% had 2 other trackers, and 3.34% had one other tracker.

80.82% also included Podscribe, 76.59% also included Chartable, 73.39% also included Podsights, 53.17% also included Podtrac, 41.17% also included Magellan AI, 33.01% also included ArtsAI, 18.74% also included Spotify, 18.49% also included Adswizz, 14.66% also included Veritonic, 6.05% also included Podder, 4.18% also included Podroll, and 0.05% also included Blubrry.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "43.04%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "22.77%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "13.13%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.44%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "6.84%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.90%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.52%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.25%" >}}
9. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "0.05%" >}}
10. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.05%" >}}
---

### 16. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.11% of new episodes in November, growing 32.69% from last month.

Of these, 32.52% had one other tracker, 29.91% had 3 other trackers, 21.44% had 2 other trackers, 4.44% had 6 other trackers, 3.93% had 7 other trackers, 2.30% had 5 other trackers, and 2.19% had 4 other trackers.

68.96% also included Chartable, 44.87% also included Podscribe, 29.71% also included Podtrac, 27.21% also included Podsights, 19.45% also included Claritas, 10.97% also included Gumshoe, 10.87% also included ArtsAI, 9.55% also included Magellan AI, 5.82% also included Adswizz, 3.68% also included Veritonic, 3.27% also included Audiotakes, 2.65% also included OP3, 1.07% also included Podcorn, 0.82% also included Podroll, 0.61% also included Podder, and 0.05% also included Blubrry.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "27.51%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "21.75%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "15.47%" >}}
4. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "7.91%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.53%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.43%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.44%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.29%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.52%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.28%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.10% of new episodes in November, growing 28.83% from last month.

Of these, 33.68% had 5 other trackers, 17.98% had 4 other trackers, 15.43% had 2 other trackers, 10.71% had 3 other trackers, 7.38% had one other tracker, 3.05% had 6 other trackers, 1.17% had 7 other trackers, 0.78% had 8 other trackers, and 0.28% had 9 other trackers.

68.76% also included Podsights, 61.65% also included Podtrac, 53.50% also included Podcorn, 49.22% also included OP3, 42.06% also included Podscribe, 40.46% also included Chartable, 11.93% also included Spotify, 4.72% also included Podder, 4.38% also included Podroll, 2.61% also included Audiotakes, 2.00% also included Magellan AI, 1.72% also included ArtsAI, 1.50% also included Voxalyze, 0.72% also included Adswizz, 0.33% also included Podkite, and 0.33% also included Veritonic.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "49.72%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "24.58%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "20.09%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.33%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.94%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.44%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.28%" >}}
8. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.28%" >}}
9. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.11%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.11%" >}}
---

### 18. [Firstory](https://firstory.me/)

Firstory was found on 0.08% of new episodes in November, growing 3.40% from last month.

Of these, 69.85% had one other tracker, and 0.28% had 2 other trackers.

70.13% also included Chartable, and 0.28% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.44%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.56%" >}}
---

### 19. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.06% of new episodes in November, growing 2.26% from last month.

Of these, 43.67% had 6 other trackers, 20.59% had 5 other trackers, 15.24% had 4 other trackers, 6.06% had 7 other trackers, 5.53% had 3 other trackers, 4.46% had 2 other trackers, and 3.57% had one other tracker.

85.47% also included Podtrac, 84.05% also included Podsights, 82.53% also included Podscribe, 80.57% also included Chartable, 55.35% also included ArtsAI, 41.35% also included Magellan AI, 26.56% also included Claritas, 26.38% also included Adswizz, 6.42% also included Spotify, 6.15% also included Audiotakes, 2.05% also included Podder, and 0.53% also included Gumshoe.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "53.65%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "24.33%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "11.50%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.88%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.41%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.96%" >}}
---

### 20. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.06% of new episodes in November, growing 10.54% from last month.

Of these, 49.32% had one other tracker, 16.14% had 2 other trackers, 14.58% had 3 other trackers, 10.67% had 4 other trackers, 4.50% had 5 other trackers, and 3.03% had 6 other trackers.

47.46% also included Podscribe, 47.36% also included Adswizz, 43.05% also included Podsights, 20.74% also included Chartable, 13.80% also included ArtsAI, 11.15% also included Podtrac, 7.53% also included Magellan AI, 6.75% also included Veritonic, 6.26% also included Spotify, and 4.60% also included Gumshoe.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "24.56%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "16.14%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.70%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.82%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.45%" >}}
6. {{< a "https://kostenlos-hosten.de/" "Podcastbude" >}} {{< span "weak" "1.86%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.78%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.49%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.39%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.39%" >}}
---

### 21. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on 0.03% of new episodes in November, growing 20.62% from last month.

Of these, 34.03% had one other tracker, 18.50% had 3 other trackers, 8.03% had 4 other trackers, 5.41% had 2 other trackers, 2.44% had 8 other trackers, 0.87% had 9 other trackers, 0.52% had 6 other trackers, and 0.35% had 5 other trackers.

49.04% also included Chartable, 29.84% also included Podtrac, 25.83% also included Podsights, 24.26% also included Podcorn, 15.01% also included Podroll, 10.12% also included OP3, 4.71% also included Gumshoe, 3.66% also included Podder, 1.22% also included Podscribe, 0.52% also included Blubrry, and 0.52% also included Magellan AI.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "24.61%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "24.08%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "10.99%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "10.65%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.65%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.08%" >}}
7. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "3.14%" >}}
8. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "1.40%" >}}
9. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "0.87%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.70%" >}}
---

### 22. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in November, shrinking 14.10% from last month.

Of these, 35.86% had one other tracker, 6.75% had 2 other trackers, and 3.38% had 3 other trackers.

31.65% also included Chartable, 12.66% also included Podtrac, 9.28% also included Podcorn, and 5.91% also included Podsights.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "100.00%" >}}
---

### 23. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in November, growing 15.45% from last month.

Of these, 28.15% had one other tracker, 4.44% had 2 other trackers, 4.44% had 6 other trackers, and 2.96% had 5 other trackers.

20.74% also included Chartable, 17.78% also included Podtrac, 11.85% also included Podcorn, 11.11% also included Podsights, 4.44% also included Podscribe, 4.44% also included OP3, 4.44% also included Gumshoe, and 3.70% also included Podder.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "36.30%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "15.56%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "10.37%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "8.15%" >}}
5. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "6.67%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.67%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.70%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.70%" >}}
9. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.22%" >}}
10. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "2.22%" >}}
---

### 24. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in November, growing 5.17% from last month.

Of these, 43.88% had one other tracker, and 24.49% had 2 other trackers.

64.29% also included Chartable, 19.39% also included Podtrac, and 9.18% also included Podcorn.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "33.67%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "20.41%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "18.37%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "13.27%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.16%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.08%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.04%" >}}
---

### 25. [Zippycast](https://zippycast.io/)

Zippycast was found on <0.01% of new episodes in November, shrinking 6.64% from last month.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "86.21%" >}}
2. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "13.79%" >}}
---

### 26. [Glystn](https://glystn.com/)

Glystn was found on <0.01% of new episodes in November, shrinking 88.52% from last month.

Of these, 69.23% had 3 other trackers, and 30.77% had one other tracker.

100.00% also included Chartable, 69.23% also included Podtrac, and 69.23% also included Podsights.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "69.23%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "30.77%" >}}
---

### 27. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on <0.01% of new episodes in November, growing 1213.51% from last month.

Of these, 66.67% had 3 other trackers.

66.67% also included Chartable, 50.00% also included Podtrac, 33.33% also included Podsights, 16.67% also included Podcorn, 16.67% also included Podroll, and 16.67% also included Podder.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.33%" >}}
2. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "25.00%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "25.00%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "16.67%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2023-11.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
