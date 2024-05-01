---
title: "Top Podcast Tracking Services by Episode Share (April 2024)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2024-04.png
date: 2024-05-01T13:19:00-05:00
lastmod: 2024-05-01T13:19:00-05:00
draft: false
rssrevision: 2024-04
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.8 million in April 2024), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in April, how many
of them included one or more of these tracking services?  Some episodes had as many as *nine* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

### A special note for March/April 2024 {#spreaker}
_We now have a better signal of when Spreaker releases new episodes, so our crawlers are finding more, starting early-March. This more accurate view seems to have helped Podtrac and Adswizz the most in this month's share rankings._

### A special note for September/October 2023 {#s4p}
_We now have a better signal of when Spotify for Podcasters (formerly Anchor) podcasts release new episodes, so our crawlers are finding more, starting mid-September._

_October was the first full month where this new signal was incorporated for the entire month, so should be a good baseline going forward.  It's likely that we were undercounting S4P prior to this,
in general our goal is to observe and validate every change to every podcast._

_Higher share of new episodes on S4P (which typically do not have prefixes) leads to lower share overall for all prefixes over these two months, but should be stable going forward now that we have a more accurate baseline._

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Chartable	Adswizz	Podsights	Blubrry	Podcorn	Podscribe	Podroll	Spotify	Médiamétrie	OP3	Podder	Feedpress	Claritas	ArtsAI	Gumshoe	Audiotakes	Veritonic	Zencastr	Podkite	United Podcasters	CoHost Prefix	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.00	1.16	2.07	2.09				0.42			0.32															1.61
Oct 2021	4.05	4.09	1.01	1.20	2.11	2.13				0.54			0.34															1.61
Nov 2021	4.07	4.30	1.02	1.25	2.01	2.14				0.57			0.32															0.59
Dec 2021	4.06	4.42	1.24	1.19	1.57	2.27				0.59			0.19															
Jan 2022	4.11	4.45	1.41	1.21	1.56	2.31				0.63			0.16															
Feb 2022	4.15	4.48	1.44	1.25	1.53	2.38				0.58			0.17															
Mar 2022	4.37	4.72	1.51	1.34	1.56	2.40				0.53			0.17															
Apr 2022	4.44	4.71	1.49	1.33	1.55	2.33				0.51			0.16															
May 2022	4.49	4.87	1.58	1.41	1.48	2.26				0.56			0.17															
Jun 2022	4.75	5.10	1.77	1.54	1.50	2.06				0.62			0.21												0.02			
Jul 2022	4.70	5.10	1.89	1.50	1.50	2.16				0.54			0.25												0.02			
Aug 2022	4.83	5.26	2.08	1.73	1.51	2.45				0.41			0.20		0.10										0.01			
Sep 2022	7.53	5.40	2.26	1.74	1.49	2.45	0.02			0.52			0.21	0.01	0.09					0.01					0.02	0.02		
Oct 2022	8.24	5.48	2.35	1.81	1.61	2.51	0.07			0.50	0.03		0.18	0.02	0.10				0.01	0.01					0.02	0.04		
Nov 2022	8.11	5.62	2.37	2.03	1.62	2.43	0.15			0.50	0.04	0.01	0.18	0.03	0.10				0.01	0.01					0.02	0.05		
Dec 2022	8.01	5.54	2.32	1.81	1.61	2.05	0.03			0.49	0.05	0.04	0.18	0.02	0.05				0.01	0.01				0.01	0.02	0.05		
Jan 2023	7.85	5.56	2.35	1.88	1.61	2.15	0.20			0.54	0.07	0.11	0.18	0.06	0.10				0.01	0.01				0.01	0.02	0.06		
Feb 2023	7.58	5.51	2.29	1.92	1.62	2.30	0.21			0.49	0.07	0.11	0.19	0.07	0.10				0.01	0.01				0.01	0.02	0.06	0.03	
Mar 2023	7.79	5.53	2.25	2.03	1.53	2.22	0.21	0.04		0.45	0.08	0.11	0.18	0.07	0.11			0.04	0.01	0.01				0.01	0.02	0.06		
Apr 2023	7.66	5.43	2.26	2.00	1.67	2.20	0.21	0.06		0.45	0.09	0.15	0.17	0.07	0.11	0.08		0.05	0.01	0.01				0.01	0.01			
May 2023	7.58	5.59	2.27	2.04	1.67	2.28	0.24	0.09		0.45	0.09	0.15	0.19	0.08	0.11	0.07		0.05	0.01	0.01			0.01	0.01	0.01			
Jun 2023	8.22	5.83	2.39	2.23	1.64	1.86	0.26	0.10		0.51	0.09	0.15	0.19	0.07	0.12	0.08		0.05	0.01	0.01			0.01	0.01	0.01			
Jul 2023	8.60	5.95	2.38	2.52	1.53	1.17	0.27	0.14	0.01	0.55	0.08	0.14	0.18	0.07	0.11	0.06		0.06	0.01	0.01			0.01	0.01	0.01			
Aug 2023	9.19	6.43	2.72	2.76	1.58	1.23	0.36	0.16	0.03	0.53	0.11	0.15	0.17	0.08	0.12	0.07	0.04	0.07	0.01	0.01			0.02	0.01				
Sep 2023	8.46	5.77	2.49	2.47	1.39	1.10	0.37	0.13	0.05	0.58	0.10	0.15	0.16	0.10	0.12	0.07	0.05	0.06	0.01	0.01			0.02	0.01				
Oct 2023	7.90	5.54	2.29	2.28	1.37	1.11	0.39	0.12	0.08	0.50	0.10	0.16	0.16	0.10	0.12	0.08	0.05	0.06	0.02	0.01			0.03	0.01				
Nov 2023	7.65	5.59	2.25	2.33	1.45	1.14	0.47	0.12	0.11	0.33	0.13	0.16	0.17	0.11	0.12	0.10	0.06	0.06	0.01	0.01			0.03					
Dec 2023	7.48	5.60	2.20	2.19	1.53	1.12	0.54	0.12	0.12	0.33	0.11	0.16	0.16	0.11	0.12	0.09	0.06	0.06	0.01	0.01			0.03					
Jan 2024	7.64	5.61	2.37	2.21	1.55	1.17	0.65	0.11	0.15	0.25	0.13	0.16	0.17	0.12	0.14	0.10	0.08	0.06	0.01	0.01	0.01		0.01					
Feb 2024	7.69	5.58	2.38	2.22	1.52	1.21	0.69	0.12	0.22	0.22	0.16	0.17	0.17	0.13	0.13	0.11	0.09	0.06	0.01	0.01	0.01							
Mar 2024	9.01	5.46	2.53	2.19	1.54	1.14	0.69	0.12	0.25	0.22	0.14	0.16	0.16	0.14	0.12	0.10	0.09	0.06	0.01	0.01	0.01							
Apr 2024	10.78	5.47	2.53	2.16	1.51	1.24	0.73	0.34	0.27	0.19	0.18	0.17	0.15	0.15	0.13	0.11	0.07	0.07	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

### Overall

At least one tracker was found on 18.77% of new episodes in April, growing 10.09% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "32.87%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.07%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.97%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.11%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.16%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.11%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "3.08%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.31%" >}}
9. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.93%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.57%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of April 2024.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 10.78% of new episodes in April, growing 19.65% from last month.

Of these, 14.98% had one other tracker, 11.78% had 2 other trackers, 2.25% had 3 other trackers, 1.01% had 4 other trackers, 0.95% had 5 other trackers, 0.37% had 6 other trackers, 0.25% had 7 other trackers, and 0.04% had 8 other trackers.

21.88% also included Chartable, 13.07% also included Podsights, 5.47% also included Adswizz, 4.53% also included Podscribe, 2.58% also included Podroll, 1.77% also included Magellan AI, 1.69% also included Spotify, 1.66% also included Podcorn, 1.03% also included Podder, 0.93% also included ArtsAI, 0.93% also included Claritas, 0.78% also included OP3, 0.59% also included Veritonic, 0.58% also included Gumshoe, 0.38% also included Blubrry, 0.28% also included Audiotakes, 0.05% also included Feedpress, 0.04% also included CoHost Prefix, 0.02% also included Médiamétrie, 0.02% also included Zencastr, 0.02% also included United Podcasters, 0.01% also included AdBarker, and 0.01% also included Podkite.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "56.72%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.43%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.14%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.71%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.15%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.06%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.57%" >}}
8. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.49%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.31%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.16%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 6.09% of new episodes in April, shrinking 0.11% from last month.

Of these, 44.33% also included Podtrac, 10.01% also included Podscribe, 6.63% also included Adswizz, 4.25% also included Magellan AI, 2.66% also included Podcorn, 2.31% also included Claritas, 2.15% also included ArtsAI, 1.99% also included Podder, 1.62% also included Podroll, 1.46% also included Gumshoe, 1.39% also included OP3, 1.08% also included Veritonic, 0.83% also included Firstory, 0.81% also included Audiotakes, 0.35% also included Blubrry, 0.09% also included Feedpress, 0.09% also included United Podcasters, 0.09% also included CoHost Prefix, 0.06% also included Zencastr, 0.05% also included AdBarker, 0.04% also included Podkite, 0.01% also included Voxalyze, and <0.01% also included Glystn.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "31.34%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.68%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.19%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.31%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.76%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.51%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.84%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.72%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.42%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.28%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.47% of new episodes in April, growing 0.23% from last month.

Of these, 29.59% had one other tracker, 20.61% had 2 other trackers, 4.59% had 3 other trackers, 2.04% had 4 other trackers, 1.87% had 5 other trackers, 0.80% had 6 other trackers, 0.42% had 7 other trackers, and 0.07% had 8 other trackers.

43.09% also included Podtrac, 29.05% also included Podsights, 8.44% also included Podscribe, 6.24% also included Adswizz, 4.11% also included Magellan AI, 4.02% also included Spotify, 2.29% also included Podcorn, 2.26% also included Claritas, 2.06% also included ArtsAI, 2.02% also included Podder, 1.70% also included Podroll, 1.03% also included Veritonic, 0.97% also included Gumshoe, 0.95% also included OP3, 0.92% also included Firstory, 0.45% also included Audiotakes, 0.30% also included Blubrry, 0.10% also included Feedpress, 0.10% also included CoHost Prefix, 0.09% also included United Podcasters, 0.06% also included Zencastr, 0.05% also included AdBarker, 0.04% also included Podkite, 0.01% also included Voxalyze, and <0.01% also included Glystn.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.69%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.22%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.13%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.57%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.08%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.89%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.90%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.68%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.53%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.52%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.53% of new episodes in April, shrinking 0.09% from last month.

Of these, 18.56% had one other tracker, 12.68% had 2 other trackers, 2.24% had 3 other trackers, 0.57% had 4 other trackers, 0.52% had 5 other trackers, 0.33% had 7 other trackers, 0.26% had 6 other trackers, and 0.12% had 8 other trackers.

23.31% also included Podtrac, 13.51% also included Chartable, 9.35% also included Podroll, 5.24% also included Podsights, 1.81% also included Podscribe, 1.10% also included Blubrry, 1.01% also included ArtsAI, 0.95% also included Claritas, 0.87% also included Audiotakes, 0.73% also included Spotify, 0.70% also included OP3, 0.68% also included Magellan AI, 0.62% also included Veritonic, 0.39% also included Podcorn, 0.09% also included Podder, 0.07% also included Gumshoe, and <0.01% also included United Podcasters.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "47.06%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "11.65%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "8.61%" >}}
4. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "7.32%" >}}
5. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "5.29%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.27%" >}}
7. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "3.16%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.32%" >}}
9. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.20%" >}}
10. {{< a "https://www.mediastre.am/" "mediastream" >}} {{< span "weak" "1.12%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.16% of new episodes in April, shrinking 1.43% from last month.

Of these, 38.12% had 2 other trackers, 30.27% had one other tracker, 10.20% had 3 other trackers, 5.75% had 5 other trackers, 5.43% had 4 other trackers, 2.11% had 6 other trackers, 1.07% had 7 other trackers, and 0.18% had 8 other trackers.

73.50% also included Chartable, 65.17% also included Podtrac, 21.49% also included Podscribe, 10.59% also included Magellan AI, 6.12% also included Adswizz, 5.80% also included Claritas, 4.76% also included ArtsAI, 4.08% also included Podder, 3.15% also included Spotify, 2.85% also included Gumshoe, 2.60% also included Podcorn, 2.50% also included Veritonic, 2.03% also included Podroll, 1.99% also included OP3, 1.85% also included Audiotakes, 0.22% also included Blubrry, 0.18% also included United Podcasters, 0.11% also included CoHost Prefix, 0.08% also included Feedpress, 0.06% also included Zencastr, 0.02% also included Podkite, and 0.01% also included Voxalyze.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "58.78%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "23.23%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.57%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.43%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.43%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.46%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.43%" >}}
8. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.11%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.08%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.99%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.51% of new episodes in April, shrinking 1.51% from last month.

Of these, 6.41% had one other tracker, 0.65% had 2 other trackers, 0.08% had 3 other trackers, 0.03% had 4 other trackers, 0.01% had 6 other trackers, and 0.01% had 5 other trackers.

2.74% also included Podtrac, 1.84% also included Adswizz, 1.23% also included Feedpress, 1.10% also included Chartable, 0.34% also included OP3, 0.31% also included Podsights, 0.25% also included Podcorn, 0.19% also included Podscribe, 0.06% also included Magellan AI, 0.04% also included Spotify, 0.04% also included Podder, 0.01% also included Podroll, 0.01% also included Audiotakes, 0.01% also included Veritonic, and <0.01% also included ArtsAI.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "39.18%" >}}
2. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "6.22%" >}}
3. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "6.19%" >}}
4. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.05%" >}}
5. {{< a "https://www.rferl.org/" "Radio Free Europe and Radio Liberty" >}} {{< span "weak" "2.86%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.45%" >}}
7. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "2.23%" >}}
8. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "1.81%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.81%" >}}
10. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.29%" >}}
---

### 6. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 1.24% of new episodes in April, growing 8.72% from last month.

Of these, 13.56% had one other tracker, 3.55% had 2 other trackers, 2.09% had 5 other trackers, 1.44% had 3 other trackers, 0.91% had 4 other trackers, 0.30% had 6 other trackers, 0.06% had 8 other trackers, and 0.03% had 7 other trackers.

14.43% also included Podtrac, 10.09% also included Chartable, 4.52% also included Podsights, 3.55% also included OP3, 3.51% also included Gumshoe, 2.88% also included Podscribe, 0.80% also included Adswizz, 0.46% also included Podder, 0.33% also included Podroll, 0.31% also included Blubrry, 0.17% also included Spotify, 0.17% also included Feedpress, 0.09% also included Magellan AI, 0.08% also included CoHost Prefix, 0.04% also included AdBarker, 0.04% also included Zencastr, 0.03% also included Podkite, 0.02% also included Voxalyze, and 0.02% also included United Podcasters.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "45.79%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.13%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "8.60%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.15%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.85%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "4.91%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.90%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.79%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.55%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.28%" >}}
---

### 7. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.73% of new episodes in April, growing 6.74% from last month.

Of these, 20.59% had 3 other trackers, 17.27% had 2 other trackers, 16.94% had one other tracker, 16.16% had 5 other trackers, 13.80% had 4 other trackers, 6.30% had 6 other trackers, 3.73% had 7 other trackers, and 0.47% had 8 other trackers.

66.81% also included Podtrac, 63.55% also included Podsights, 63.19% also included Chartable, 29.45% also included Magellan AI, 17.77% also included Claritas, 16.25% also included Spotify, 15.14% also included ArtsAI, 7.24% also included Veritonic, 6.83% also included Audiotakes, 6.27% also included Adswizz, 6.08% also included Gumshoe, 5.33% also included Podder, 4.90% also included Podcorn, 4.43% also included OP3, 3.01% also included Podroll, 0.40% also included Blubrry, 0.23% also included United Podcasters, and 0.07% also included Feedpress.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "57.08%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.17%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.53%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "5.98%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.28%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.12%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.76%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.30%" >}}
9. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.80%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.72%" >}}
---

### 8. [Podroll](https://podroll.fm/)

Podroll was found on 0.34% of new episodes in April, growing 194.76% from last month.

Of these, 76.50% had 2 other trackers, 9.45% had 3 other trackers, 5.12% had one other tracker, 2.01% had 4 other trackers, 0.80% had 5 other trackers, 0.73% had 6 other trackers, 0.22% had 8 other trackers, and 0.18% had 7 other trackers.

81.64% also included Podtrac, 69.30% also included Adswizz, 27.34% also included Chartable, 12.87% also included Podsights, 6.44% also included Podscribe, 1.61% also included Podder, 1.21% also included Podcorn, 1.19% also included Magellan AI, 1.19% also included Gumshoe, 1.16% also included OP3, 1.07% also included Claritas, 0.30% also included ArtsAI, 0.21% also included CoHost Prefix, 0.16% also included Spotify, 0.14% also included United Podcasters, and 0.03% also included Blubrry.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "68.92%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "16.73%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.66%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.12%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "2.42%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.05%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.60%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.53%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.46%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.24%" >}}
---

### 9. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.27% of new episodes in April, growing 7.30% from last month.

Of these, 29.30% had 5 other trackers, 22.69% had 4 other trackers, 12.83% had 3 other trackers, 12.57% had 6 other trackers, 8.99% had 7 other trackers, 7.05% had 2 other trackers, 4.61% had one other tracker, and 1.15% had 8 other trackers.

83.78% also included Podsights, 82.31% also included Chartable, 78.74% also included Podscribe, 69.82% also included Podtrac, 38.46% also included Claritas, 21.80% also included ArtsAI, 19.20% also included Spotify, 15.13% also included Veritonic, 14.19% also included Podder, 7.72% also included Audiotakes, 6.25% also included Adswizz, 1.87% also included Gumshoe, 1.49% also included Podroll, 0.48% also included United Podcasters, 0.40% also included Podcorn, 0.34% also included Blubrry, and 0.06% also included OP3.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "65.61%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.40%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.23%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.19%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.94%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.68%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.77%" >}}
8. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.26%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.24%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.22%" >}}
---

### 10. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.27% of new episodes in April, growing 6.87% from last month.

Of these, 50.28% had 2 other trackers, 13.86% had 3 other trackers, 11.08% had one other tracker, 8.27% had 7 other trackers, 6.35% had 6 other trackers, 5.44% had 4 other trackers, 2.51% had 5 other trackers, and 1.17% had 8 other trackers.

81.92% also included Chartable, 67.72% also included Podtrac, 44.26% also included Podscribe, 25.36% also included Podsights, 19.56% also included Magellan AI, 16.99% also included ArtsAI, 8.96% also included Veritonic, 8.43% also included Claritas, 6.86% also included Adswizz, 4.67% also included Gumshoe, 4.65% also included Audiotakes, 1.64% also included OP3, 0.81% also included Podcorn, 0.59% also included Podder, 0.22% also included Blubrry, 0.20% also included Podroll, and 0.08% also included United Podcasters.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "51.38%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.89%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.00%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "7.40%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.78%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.00%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.78%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.73%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.52%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.46%" >}}
---

### 11. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.19% of new episodes in April, shrinking 15.55% from last month.

Of these, 1.21% had one other tracker.

1.21% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "63.64%" >}}
2. {{< a "https://soundcast.fm/" "SoundCast" >}} {{< span "weak" "13.24%" >}}
3. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "13.00%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "5.39%" >}}
5. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "2.77%" >}}
---

### 12. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.18% of new episodes in April, growing 23.62% from last month.

Of these, 24.82% had one other tracker, 15.68% had 2 other trackers, 14.41% had 5 other trackers, 7.15% had 4 other trackers, 5.30% had 3 other trackers, 1.97% had 6 other trackers, 0.43% had 8 other trackers, and 0.22% had 7 other trackers.

47.83% also included Podtrac, 29.63% also included Chartable, 25.07% also included Podcorn, 24.39% also included Podsights, 23.62% also included Gumshoe, 18.39% also included Podscribe, 10.07% also included Adswizz, 2.89% also included Blubrry, 2.49% also included Spotify, 2.31% also included Podder, 2.25% also included Podroll, 0.28% also included CoHost Prefix, 0.09% also included Magellan AI, 0.09% also included ArtsAI, and 0.09% also included Feedpress.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "34.52%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.53%" >}}
3. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "8.01%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.23%" >}}
5. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "3.20%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.17%" >}}
7. {{< a "https://vodio.fr/" "Vodio" >}} {{< span "weak" "2.93%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.68%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.34%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.03%" >}}
---

### 13. [Podder](https://www.podderapp.com/)

Podder was found on 0.17% of new episodes in April, growing 6.34% from last month.

Of these, 24.08% had one other tracker, 18.72% had 3 other trackers, 14.54% had 5 other trackers, 14.00% had 2 other trackers, 10.68% had 4 other trackers, 2.65% had 6 other trackers, 0.51% had 7 other trackers, and 0.45% had 8 other trackers.

65.47% also included Podtrac, 64.89% also included Chartable, 51.88% also included Podsights, 22.90% also included Podscribe, 22.80% also included Magellan AI, 3.38% also included Podcorn, 3.22% also included Podroll, 2.46% also included Gumshoe, 2.39% also included OP3, 2.33% also included Claritas, 1.28% also included Adswizz, 0.92% also included Spotify, 0.80% also included ArtsAI, 0.57% also included Zencastr, 0.35% also included Veritonic, 0.32% also included Blubrry, 0.29% also included United Podcasters, 0.29% also included CoHost Prefix, and 0.16% also included Podkite.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "60.81%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "13.36%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "6.63%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.87%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.64%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.00%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.97%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.63%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.64%" >}}
10. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "0.38%" >}}
---

### 14. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.15% of new episodes in April, shrinking 1.34% from last month.

Of these, 18.83% had one other tracker, 0.98% had 2 other trackers, and 0.32% had 5 other trackers.

12.01% also included Blubrry, 3.65% also included Chartable, 3.48% also included Podtrac, 1.33% also included Podcorn, 1.16% also included Podsights, 0.32% also included Podscribe, 0.32% also included Claritas, and 0.11% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "47.56%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.11%" >}}
3. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "7.80%" >}}
4. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "6.08%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.71%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.32%" >}}
7. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.97%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.86%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.69%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.23%" >}}
---

### 15. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.15% of new episodes in April, growing 6.15% from last month.

Of these, 36.97% had 5 other trackers, 21.90% had 6 other trackers, 17.23% had 4 other trackers, 7.49% had 7 other trackers, 6.99% had 3 other trackers, 4.49% had 2 other trackers, and 3.26% had one other tracker.

86.64% also included Podscribe, 83.64% also included Podsights, 82.51% also included Chartable, 70.13% also included Magellan AI, 66.91% also included Podtrac, 29.58% also included ArtsAI, 16.00% also included Adswizz, 15.10% also included Spotify, 14.81% also included Veritonic, 2.64% also included Podder, 2.43% also included Podroll, 0.33% also included Feedpress, and 0.14% also included Gumshoe.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "56.59%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.68%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.59%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.23%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.55%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "5.29%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.12%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.33%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.29%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.25%" >}}
---

### 16. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.13% of new episodes in April, growing 6.99% from last month.

Of these, 26.36% had 5 other trackers, 19.99% had 3 other trackers, 19.95% had 7 other trackers, 14.36% had 6 other trackers, 10.49% had 4 other trackers, 5.71% had 2 other trackers, 2.37% had 8 other trackers, and 0.57% had one other tracker.

84.54% also included Chartable, 83.19% also included Podscribe, 77.27% also included Podsights, 75.48% also included Podtrac, 44.80% also included Magellan AI, 34.27% also included Spotify, 33.33% also included Claritas, 26.19% also included Veritonic, 19.26% also included Adswizz, 10.16% also included Audiotakes, 1.02% also included Podder, 0.78% also included Podroll, 0.12% also included OP3, and 0.04% also included Blubrry.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.60%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "21.18%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "11.71%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.57%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.40%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "7.47%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.67%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.26%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.61%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.20%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.11% of new episodes in April, growing 12.33% from last month.

Of these, 26.39% had 5 other trackers, 17.58% had 4 other trackers, 16.46% had 2 other trackers, 13.48% had 3 other trackers, 11.20% had one other tracker, 3.29% had 6 other trackers, 0.71% had 8 other trackers, and 0.35% had 7 other trackers.

58.00% also included Podtrac, 57.60% also included Podsights, 49.70% also included Chartable, 41.49% also included Podscribe, 40.73% also included Podcorn, 38.86% also included OP3, 11.70% also included Spotify, 4.76% also included Magellan AI, 3.90% also included Podder, 3.80% also included Podroll, 1.57% also included Adswizz, 0.91% also included United Podcasters, 0.86% also included Audiotakes, 0.46% also included CoHost Prefix, 0.20% also included Claritas, and 0.20% also included Veritonic.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "39.21%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "27.76%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "20.67%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.19%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.82%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.62%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.66%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.30%" >}}
9. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.25%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.20%" >}}
---

### 18. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.07% of new episodes in April, shrinking 19.61% from last month.

Of these, 28.42% had 4 other trackers, 28.12% had one other tracker, 17.84% had 3 other trackers, 8.77% had 5 other trackers, 8.01% had 6 other trackers, and 7.11% had 2 other trackers.

69.54% also included Podscribe, 55.78% also included Podsights, 41.87% also included Podtrac, 34.09% also included Chartable, 30.46% also included Adswizz, 29.40% also included Magellan AI, 18.82% also included ArtsAI, 17.38% also included Spotify, 2.65% also included Veritonic, 1.28% also included Gumshoe, and 0.15% also included Blubrry.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "27.66%" >}}
2. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "24.64%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "10.36%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.33%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.80%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.12%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.13%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.68%" >}}
9. {{< a "https://kostenlos-hosten.de/" "Podcastbude" >}} {{< span "weak" "0.30%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.23%" >}}
---

### 19. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.07% of new episodes in April, growing 7.37% from last month.

Of these, 33.82% had 7 other trackers, 22.28% had 6 other trackers, 11.62% had 5 other trackers, 10.98% had 4 other trackers, 7.83% had 2 other trackers, 6.62% had 3 other trackers, 4.68% had 8 other trackers, and 1.53% had one other tracker.

94.19% also included Podtrac, 84.10% also included Chartable, 80.47% also included Podsights, 78.69% also included Podscribe, 61.50% also included Magellan AI, 51.82% also included ArtsAI, 35.75% also included Spotify, 33.01% also included Claritas, 23.16% also included Adswizz, 2.82% also included Audiotakes, 0.89% also included Podder, 0.32% also included Gumshoe, and 0.16% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "62.71%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "20.66%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.30%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.36%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.50%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.69%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.81%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.56%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.32%" >}}
---

### 20. [Firstory](https://firstory.me/)

Firstory was found on 0.07% of new episodes in April, shrinking 3.70% from last month.

Of these, 75.08% had one other tracker.

75.08% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.76%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.24%" >}}
---

### 21. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in April, growing 1.63% from last month.

Of these, 16.59% had one other tracker, 16.14% had 2 other trackers, 3.14% had 3 other trackers, and 3.14% had 4 other trackers.

26.01% also included Chartable, 18.83% also included Podtrac, 10.31% also included Podsights, 8.07% also included Podder, 4.48% also included Podcorn, and 3.14% also included United Podcasters.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "40.36%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "17.94%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "13.90%" >}}
4. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "10.31%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.73%" >}}
6. {{< a "https://www.blogtalkradio.com/" "Blog Talk Radio" >}} {{< span "weak" "3.59%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.14%" >}}
8. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "2.69%" >}}
9. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "1.35%" >}}
---

### 22. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in April, growing 7.17% from last month.

Of these, 30.87% had one other tracker, 3.36% had 5 other trackers, and 2.68% had 2 other trackers.

24.83% also included Chartable, 14.09% also included Podtrac, 6.04% also included Podsights, 4.70% also included Podcorn, and 3.36% also included Podder.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "44.30%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "12.75%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "12.08%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "8.72%" >}}
5. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "6.04%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.04%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.04%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.68%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.67%" >}}
10. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "0.67%" >}}
---

### 23. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in April, shrinking 0.93% from last month.

Of these, 36.57% had one other tracker, 23.13% had 4 other trackers, 19.40% had 3 other trackers, 8.96% had 2 other trackers, and 2.99% had 6 other trackers.

65.67% also included Chartable, 54.48% also included Podsights, 23.13% also included Podscribe, 22.39% also included Podtrac, 17.91% also included Magellan AI, 13.43% also included Gumshoe, 6.72% also included Podroll, 6.72% also included Podder, 5.22% also included Zencastr, 2.99% also included Podcorn, 2.99% also included Spotify, and 1.49% also included Adswizz.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.33%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "20.90%" >}}
3. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "18.66%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "13.43%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "8.21%" >}}
6. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.49%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.49%" >}}
8. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.49%" >}}
---

### 24. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.01% of new episodes in April, growing 57.89% from last month.

Of these, 39.29% had 2 other trackers, 32.14% had 3 other trackers, 8.04% had one other tracker, and 8.04% had 8 other trackers.

87.50% also included Chartable, 66.96% also included Podtrac, 40.18% also included Podsights, 16.96% also included Podcorn, 11.61% also included Podroll, 8.04% also included OP3, 8.04% also included Podder, and 8.04% also included Gumshoe.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "35.71%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "26.79%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "16.07%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "11.61%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.36%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "4.46%" >}}
---

### 25. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in April, shrinking 2.48% from last month.

Of these, 29.47% had one other tracker, 29.47% had 2 other trackers, and 1.05% had 3 other trackers.

53.68% also included Chartable, 27.37% also included Podtrac, and 10.53% also included Podcorn.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "40.00%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "18.95%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "18.95%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "11.58%" >}}
5. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "4.21%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.16%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.16%" >}}
---

### 26. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on <0.01% of new episodes in April, shrinking 25.11% from last month.

Of these, 52.94% had one other tracker, and 17.65% had 2 other trackers.

41.18% also included Chartable, 29.41% also included Podcorn, and 17.65% also included Podsights.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "47.06%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.53%" >}}
3. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "17.65%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "11.76%" >}}
---

### 27. [Glystn](https://glystn.com/)

Glystn was found on <0.01% of new episodes in April, growing 32.16% from last month.

Of these, 100.00% had one other tracker.

100.00% also included Chartable.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "100.00%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
*Updated 2024-05-01, with data for the month of April 2024.*

*Updated 2024-04-01, with data for the month of March 2024.*

*Updated 2024-03-02, with data for the month of February 2024.*

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
 - [Podcast Tracker Rankings by Episode Share (March 2024)](/archive/podcast-trackers-by-episode-share-march-2024/)
 - [Podcast Tracker Rankings by Episode Share (February 2024)](/archive/podcast-trackers-by-episode-share-february-2024/)
 - [Podcast Tracker Rankings by Episode Share (January 2024)](/archive/podcast-trackers-by-episode-share-january-2024/)
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/podcast-trackers-by-episode-share.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
