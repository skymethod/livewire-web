---
title: "Top Podcast Tracking Services by Episode Share (February 2024)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2024-02.png
date: 2024-03-02T12:05:00-06:00
lastmod: 2024-03-02T12:05:00-06:00
draft: false
rssrevision: 2024-02
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.7 million in February 2024), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in February, how many
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
Month	Podtrac	Chartable	Adswizz	Podsights	Blubrry	Podcorn	Podscribe	Spotify	Médiamétrie	Feedpress	Podder	OP3	ArtsAI	Claritas	Podroll	Gumshoe	Audiotakes	Veritonic	Zencastr	Podkite	United Podcasters	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.00	1.16	2.07	2.09			0.42	0.32																	1.61
Oct 2021	4.05	4.09	1.01	1.20	2.11	2.13			0.54	0.34																	1.61
Nov 2021	4.07	4.30	1.02	1.25	2.01	2.14			0.57	0.32																	0.59
Dec 2021	4.06	4.42	1.24	1.19	1.57	2.27			0.59	0.19																	
Jan 2022	4.11	4.45	1.41	1.21	1.56	2.31			0.63	0.16																	
Feb 2022	4.15	4.48	1.44	1.25	1.53	2.38			0.58	0.17																	
Mar 2022	4.37	4.72	1.51	1.34	1.56	2.40			0.53	0.17																	
Apr 2022	4.44	4.71	1.49	1.33	1.55	2.33			0.51	0.16																	
May 2022	4.49	4.87	1.58	1.41	1.48	2.26			0.56	0.17																	
Jun 2022	4.75	5.10	1.77	1.54	1.50	2.06			0.62	0.21														0.02			
Jul 2022	4.70	5.10	1.89	1.50	1.50	2.16			0.54	0.25														0.02			
Aug 2022	4.83	5.26	2.08	1.73	1.51	2.45			0.41	0.20			0.10											0.01			
Sep 2022	7.53	5.40	2.26	1.74	1.49	2.45	0.02		0.52	0.21			0.09	0.01						0.01				0.02	0.02		
Oct 2022	8.24	5.48	2.35	1.81	1.61	2.51	0.07		0.50	0.18		0.03	0.10	0.02					0.01	0.01				0.02	0.04		
Nov 2022	8.11	5.62	2.37	2.03	1.62	2.43	0.15		0.50	0.18	0.01	0.04	0.10	0.03					0.01	0.01				0.02	0.05		
Dec 2022	8.01	5.54	2.32	1.81	1.61	2.05	0.03		0.49	0.18	0.04	0.05	0.05	0.02					0.01	0.01			0.01	0.02	0.05		
Jan 2023	7.85	5.56	2.35	1.88	1.61	2.15	0.20		0.54	0.18	0.11	0.07	0.10	0.06					0.01	0.01			0.01	0.02	0.06		
Feb 2023	7.58	5.51	2.29	1.92	1.62	2.30	0.21		0.49	0.19	0.11	0.07	0.10	0.07					0.01	0.01			0.01	0.02	0.06	0.03	
Mar 2023	7.79	5.53	2.25	2.03	1.53	2.22	0.21		0.45	0.18	0.11	0.08	0.11	0.07	0.04			0.04	0.01	0.01			0.01	0.02	0.06		
Apr 2023	7.66	5.43	2.26	2.00	1.67	2.20	0.21		0.45	0.17	0.15	0.09	0.11	0.07	0.06	0.08		0.05	0.01	0.01			0.01	0.01			
May 2023	7.58	5.59	2.27	2.04	1.67	2.28	0.24		0.45	0.19	0.15	0.09	0.11	0.08	0.09	0.07		0.05	0.01	0.01		0.01	0.01	0.01			
Jun 2023	8.22	5.83	2.39	2.23	1.64	1.86	0.26		0.51	0.19	0.15	0.09	0.12	0.07	0.10	0.08		0.05	0.01	0.01		0.01	0.01	0.01			
Jul 2023	8.60	5.95	2.38	2.52	1.53	1.17	0.27	0.01	0.55	0.18	0.14	0.08	0.11	0.07	0.14	0.06		0.06	0.01	0.01		0.01	0.01	0.01			
Aug 2023	9.19	6.43	2.72	2.76	1.58	1.23	0.36	0.03	0.53	0.17	0.15	0.11	0.12	0.08	0.16	0.07	0.04	0.07	0.01	0.01		0.02	0.01				
Sep 2023	8.46	5.77	2.49	2.47	1.39	1.10	0.37	0.05	0.58	0.16	0.15	0.10	0.12	0.10	0.13	0.07	0.05	0.06	0.01	0.01		0.02	0.01				
Oct 2023	7.90	5.54	2.29	2.28	1.37	1.11	0.39	0.08	0.50	0.16	0.16	0.10	0.12	0.10	0.12	0.08	0.05	0.06	0.02	0.01		0.03	0.01				
Nov 2023	7.65	5.59	2.25	2.33	1.45	1.14	0.47	0.11	0.33	0.17	0.16	0.13	0.12	0.11	0.12	0.10	0.06	0.06	0.01	0.01		0.03					
Dec 2023	7.48	5.60	2.20	2.19	1.53	1.12	0.54	0.12	0.33	0.16	0.16	0.11	0.12	0.11	0.12	0.09	0.06	0.06	0.01	0.01		0.03					
Jan 2024	7.64	5.61	2.37	2.21	1.55	1.17	0.65	0.15	0.25	0.17	0.16	0.13	0.14	0.12	0.11	0.10	0.08	0.06	0.01	0.01	0.01	0.01					
Feb 2024	7.69	5.58	2.38	2.22	1.52	1.21	0.69	0.22	0.22	0.17	0.17	0.16	0.13	0.13	0.12	0.11	0.09	0.06	0.01	0.01	0.01								
{{< /graph >}}

---

### Overall

At least one tracker was found on 15.84% of new episodes in February, shrinking 0.24% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "19.54%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "15.09%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.83%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.71%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.70%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.69%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "3.65%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.83%" >}}
9. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.42%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.06%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of February 2024.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 7.69% of new episodes in February, growing 0.65% from last month.

Of these, 22.29% had one other tracker, 13.66% had 2 other trackers, 2.90% had 3 other trackers, 1.78% had 4 other trackers, 0.82% had 5 other trackers, 0.65% had 6 other trackers, 0.16% had 7 other trackers, and 0.04% had 8 other trackers.

32.03% also included Chartable, 18.62% also included Podsights, 5.88% also included Podscribe, 4.97% also included Adswizz, 2.22% also included Magellan AI, 1.76% also included Spotify, 1.56% also included Podcorn, 1.42% also included Podder, 1.33% also included ArtsAI, 0.92% also included Claritas, 0.90% also included OP3, 0.80% also included Veritonic, 0.77% also included Podroll, 0.68% also included Gumshoe, 0.51% also included Blubrry, 0.34% also included Audiotakes, 0.09% also included Feedpress, 0.03% also included Médiamétrie, 0.03% also included Zencastr, 0.02% also included AdBarker, 0.01% also included Podkite, 0.01% also included CoHost Prefix, 0.01% also included United Podcasters, <0.01% also included Glystn, and <0.01% also included Voxalyze.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "39.37%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "19.12%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.70%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.64%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.75%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.36%" >}}
7. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.33%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.17%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.85%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.71%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 6.21% of new episodes in February, growing 0.11% from last month.

Of these, 45.11% also included Podtrac, 9.20% also included Podscribe, 6.34% also included Adswizz, 4.00% also included Magellan AI, 2.40% also included Podcorn, 2.10% also included ArtsAI, 2.00% also included Podder, 1.88% also included Claritas, 1.52% also included Podroll, 1.29% also included Gumshoe, 1.11% also included OP3, 1.02% also included Veritonic, 0.76% also included Firstory, 0.66% also included Audiotakes, 0.38% also included Blubrry, 0.09% also included Zencastr, 0.07% also included Feedpress, 0.06% also included United Podcasters, 0.05% also included AdBarker, 0.03% also included Podkite, 0.02% also included CoHost Prefix, 0.01% also included Glystn, and 0.01% also included Voxalyze.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.15%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.79%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.81%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.26%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.57%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.77%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.97%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.70%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.35%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.08%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.58% of new episodes in February, shrinking 0.52% from last month.

Of these, 31.53% had one other tracker, 19.79% had 2 other trackers, 4.21% had 3 other trackers, 2.74% had 4 other trackers, 1.19% had 5 other trackers, 0.89% had 6 other trackers, 0.20% had 7 other trackers, and 0.06% had 8 other trackers.

44.16% also included Podtrac, 29.24% also included Podsights, 7.67% also included Podscribe, 5.81% also included Adswizz, 3.90% also included Magellan AI, 3.10% also included Spotify, 2.13% also included Podcorn, 2.03% also included Podder, 1.95% also included ArtsAI, 1.84% also included Claritas, 1.61% also included Podroll, 0.98% also included Veritonic, 0.89% also included Gumshoe, 0.84% also included Firstory, 0.67% also included OP3, 0.38% also included Audiotakes, 0.34% also included Blubrry, 0.10% also included Zencastr, 0.08% also included Feedpress, 0.06% also included AdBarker, 0.06% also included United Podcasters, 0.03% also included Podkite, 0.02% also included CoHost Prefix, 0.01% also included Glystn, and 0.01% also included Voxalyze.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "31.78%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.22%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.66%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.50%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.97%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.00%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.83%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.79%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.58%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.27%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.38% of new episodes in February, growing 0.39% from last month.

Of these, 21.86% had one other tracker, 3.39% had 2 other trackers, 2.55% had 3 other trackers, 0.72% had 4 other trackers, 0.59% had 5 other trackers, 0.36% had 6 other trackers, 0.36% had 7 other trackers, and 0.09% had 8 other trackers.

16.09% also included Podtrac, 13.64% also included Chartable, 5.98% also included Podsights, 2.29% also included Podscribe, 1.99% also included Audiotakes, 1.27% also included Blubrry, 1.10% also included ArtsAI, 1.06% also included Claritas, 1.03% also included Spotify, 0.70% also included Podroll, 0.67% also included Veritonic, 0.60% also included OP3, 0.57% also included Magellan AI, 0.32% also included Podcorn, 0.09% also included Podder, 0.07% also included Gumshoe, and 0.05% also included Zencastr.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "38.63%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "13.75%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "9.87%" >}}
4. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "8.42%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.54%" >}}
6. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "5.65%" >}}
7. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "4.80%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.39%" >}}
9. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.37%" >}}
10. {{< a "https://www.julephosting.de/" "Julep Hosting" >}} {{< span "weak" "1.22%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.22% of new episodes in February, growing 0.66% from last month.

Of these, 38.59% had 2 other trackers, 31.44% had one other tracker, 9.52% had 3 other trackers, 6.77% had 4 other trackers, 3.74% had 5 other trackers, 2.27% had 6 other trackers, 0.49% had 7 other trackers, and 0.15% had 8 other trackers.

73.40% also included Chartable, 64.44% also included Podtrac, 19.34% also included Podscribe, 9.71% also included Magellan AI, 6.39% also included Adswizz, 4.78% also included ArtsAI, 4.17% also included Podder, 4.17% also included Claritas, 2.52% also included Gumshoe, 2.45% also included Veritonic, 2.35% also included Podcorn, 1.88% also included Spotify, 1.78% also included Podroll, 1.63% also included OP3, 1.59% also included Audiotakes, 0.24% also included Blubrry, 0.13% also included United Podcasters, 0.10% also included Feedpress, 0.04% also included Zencastr, 0.04% also included CoHost Prefix, 0.02% also included Podkite, 0.01% also included Voxalyze, and 0.01% also included Glystn.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "57.95%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "24.18%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.56%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.49%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.07%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.80%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.46%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.02%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.02%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.01%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.52% of new episodes in February, shrinking 1.47% from last month.

Of these, 6.33% had one other tracker, 0.64% had 2 other trackers, 0.06% had 3 other trackers, 0.03% had 4 other trackers, 0.01% had 6 other trackers, and <0.01% had 5 other trackers.

2.56% also included Podtrac, 1.97% also included Adswizz, 1.25% also included Chartable, 1.10% also included Feedpress, 0.34% also included Podsights, 0.26% also included OP3, 0.25% also included Podcorn, 0.17% also included Podscribe, 0.03% also included Podder, 0.02% also included Podroll, 0.02% also included Magellan AI, 0.01% also included Gumshoe, <0.01% also included Voxalyze, and <0.01% also included Spotify.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "38.48%" >}}
2. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "7.07%" >}}
3. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "6.82%" >}}
4. {{< a "https://www.rferl.org/" "Radio Free Europe and Radio Liberty" >}} {{< span "weak" "3.24%" >}}
5. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "2.86%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.46%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.64%" >}}
8. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.55%" >}}
9. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.51%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "0.92%" >}}
---

### 6. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 1.21% of new episodes in February, growing 2.61% from last month.

Of these, 10.32% had one other tracker, 2.99% had 2 other trackers, 1.59% had 5 other trackers, 1.24% had 3 other trackers, 1.14% had 4 other trackers, 0.23% had 6 other trackers, 0.10% had 8 other trackers, and 0.03% had 7 other trackers.

9.95% also included Podtrac, 9.88% also included Chartable, 4.33% also included Podsights, 3.13% also included Gumshoe, 2.99% also included OP3, 2.10% also included Podscribe, 0.66% also included Podder, 0.63% also included Adswizz, 0.37% also included Podroll, 0.32% also included Blubrry, 0.15% also included Spotify, 0.15% also included Feedpress, 0.07% also included Voxalyze, 0.06% also included Claritas, 0.05% also included CoHost Prefix, 0.04% also included Zencastr, 0.04% also included Magellan AI, 0.02% also included Podkite, and 0.01% also included AdBarker.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "47.34%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "12.09%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "9.43%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.59%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "4.98%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.72%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.12%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.07%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.48%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.27%" >}}
---

### 7. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.69% of new episodes in February, growing 6.37% from last month.

Of these, 19.88% had 3 other trackers, 18.72% had 4 other trackers, 18.63% had one other tracker, 17.65% had 2 other trackers, 10.83% had 5 other trackers, 7.48% had 6 other trackers, 1.99% had 7 other trackers, and 0.40% had 8 other trackers.

65.12% also included Podtrac, 61.91% also included Podsights, 61.60% also included Chartable, 28.05% also included Magellan AI, 15.97% also included ArtsAI, 15.16% also included Claritas, 14.83% also included Spotify, 8.03% also included Veritonic, 7.84% also included Adswizz, 5.81% also included Audiotakes, 5.22% also included Gumshoe, 4.26% also included Podder, 3.95% also included OP3, 3.64% also included Podcorn, 2.63% also included Podroll, 0.37% also included Blubrry, 0.19% also included United Podcasters, and 0.08% also included Feedpress.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "55.23%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.50%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "7.13%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.32%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.46%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.03%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.42%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.50%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.80%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.30%" >}}
---

### 8. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.26% of new episodes in February, growing 3.25% from last month.

Of these, 37.70% had 4 other trackers, 17.66% had 5 other trackers, 15.30% had 6 other trackers, 14.06% had 3 other trackers, 7.06% had 2 other trackers, 3.76% had 7 other trackers, 2.69% had one other tracker, and 0.79% had 8 other trackers.

84.67% also included Chartable, 84.02% also included Podsights, 75.80% also included Podscribe, 66.40% also included Podtrac, 30.00% also included Claritas, 21.51% also included ArtsAI, 16.21% also included Veritonic, 15.08% also included Podder, 13.20% also included Spotify, 5.41% also included Audiotakes, 5.30% also included Adswizz, 2.35% also included Gumshoe, 1.77% also included Podroll, 0.52% also included United Podcasters, 0.18% also included Podcorn, and 0.14% also included Blubrry.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "65.38%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "12.36%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.54%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.52%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.94%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.71%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.70%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.27%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.25%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.18%" >}}
---

### 9. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.22% of new episodes in February, growing 47.89% from last month.

Of these, 52.73% had 2 other trackers, 18.02% had 3 other trackers, 12.22% had 4 other trackers, 6.45% had one other tracker, 3.73% had 7 other trackers, 2.12% had 6 other trackers, 2.02% had 5 other trackers, and 1.10% had 8 other trackers.

77.89% also included Chartable, 61.18% also included Podtrac, 46.43% also included Podscribe, 18.81% also included Podsights, 15.29% also included Magellan AI, 11.36% also included ArtsAI, 10.99% also included Adswizz, 10.23% also included Claritas, 6.40% also included Gumshoe, 4.93% also included OP3, 3.96% also included Veritonic, 3.20% also included Audiotakes, 0.81% also included Podcorn, 0.71% also included Podder, 0.39% also included Podroll, and 0.03% also included Blubrry.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "38.25%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "12.62%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "12.51%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.94%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.58%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.20%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.62%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.07%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.15%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.78%" >}}
---

### 10. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.22% of new episodes in February, shrinking 11.00% from last month.

Of these, 1.03% had one other tracker.

1.03% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "63.34%" >}}
2. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "14.25%" >}}
3. {{< a "https://soundcast.fm/" "SoundCast" >}} {{< span "weak" "13.51%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "4.50%" >}}
5. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "2.29%" >}}
6. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "0.21%" >}}
---

### 11. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.17% of new episodes in February, growing 1.61% from last month.

Of these, 15.85% had one other tracker, 1.20% had 2 other trackers, 0.24% had 5 other trackers, and 0.07% had 6 other trackers.

9.92% also included Blubrry, 3.98% also included Podtrac, 2.75% also included Chartable, 1.27% also included Podsights, 1.06% also included Podcorn, 0.31% also included Podscribe, 0.31% also included Claritas, 0.21% also included OP3, and 0.07% also included Podroll.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "49.18%" >}}
2. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "8.96%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.93%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.74%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "4.60%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.74%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.06%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.78%" >}}
9. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.72%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.58%" >}}
---

### 12. [Podder](https://www.podderapp.com/)

Podder was found on 0.17% of new episodes in February, growing 3.78% from last month.

Of these, 20.54% had 3 other trackers, 20.23% had one other tracker, 16.96% had 4 other trackers, 14.73% had 2 other trackers, 9.53% had 5 other trackers, 2.24% had 6 other trackers, 0.69% had 7 other trackers, and 0.48% had 8 other trackers.

66.90% also included Chartable, 64.83% also included Podtrac, 54.89% also included Podsights, 22.92% also included Magellan AI, 17.48% also included Podscribe, 4.71% also included Podcorn, 4.44% also included Podroll, 3.27% also included OP3, 2.41% also included Gumshoe, 1.34% also included ArtsAI, 1.34% also included Claritas, 1.27% also included Adswizz, 0.93% also included Spotify, 0.58% also included Zencastr, 0.52% also included Veritonic, 0.34% also included CoHost Prefix, 0.31% also included Blubrry, 0.31% also included United Podcasters, and 0.14% also included Podkite.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "62.59%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.67%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "7.12%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.57%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.96%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.23%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.58%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.58%" >}}
9. {{< a "https://www.thepodops.com/" "PodOps" >}} {{< span "weak" "0.69%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.69%" >}}
---

### 13. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.16% of new episodes in February, growing 17.43% from last month.

Of these, 30.34% had one other tracker, 11.30% had 5 other trackers, 10.78% had 4 other trackers, 9.82% had 2 other trackers, 7.11% had 3 other trackers, 1.56% had 6 other trackers, 0.52% had 8 other trackers, and 0.15% had 7 other trackers.

43.98% also included Podtrac, 29.16% also included Gumshoe, 23.93% also included Chartable, 23.12% also included Podsights, 22.93% also included Podcorn, 17.49% also included Podscribe, 9.04% also included Adswizz, 6.97% also included Spotify, 3.52% also included Podder, 2.56% also included Blubrry, 2.26% also included Podroll, 0.30% also included CoHost Prefix, and 0.22% also included Feedpress.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "41.42%" >}}
2. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "9.97%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.45%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.56%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.22%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.89%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.04%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.78%" >}}
9. {{< a "https://rssblue.com/" "RSS Blue" >}} {{< span "weak" "1.74%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.59%" >}}
---

### 14. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.13% of new episodes in February, shrinking 2.45% from last month.

Of these, 25.41% had 6 other trackers, 24.08% had 5 other trackers, 19.89% had 3 other trackers, 13.45% had 4 other trackers, 9.57% had 7 other trackers, 5.25% had 2 other trackers, 1.54% had 8 other trackers, and 0.40% had one other tracker.

84.08% also included Podscribe, 82.53% also included Chartable, 80.55% also included Podsights, 77.59% also included Podtrac, 41.91% also included Magellan AI, 32.29% also included Claritas, 26.86% also included Veritonic, 19.76% also included Adswizz, 19.10% also included Spotify, 7.68% also included Audiotakes, 1.72% also included Podder, 1.46% also included Gumshoe, and 1.10% also included Podroll.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.36%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.67%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "14.34%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.67%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.26%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "7.85%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.54%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.37%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.26%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.26%" >}}
---

### 15. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.13% of new episodes in February, growing 5.25% from last month.

Of these, 26.19% had 4 other trackers, 25.92% had 5 other trackers, 20.21% had 6 other trackers, 8.44% had 3 other trackers, 7.97% had 7 other trackers, 4.73% had 2 other trackers, 4.45% had one other tracker, and 0.32% had 8 other trackers.

83.87% also included Podscribe, 81.87% also included Chartable, 73.95% also included Podsights, 61.43% also included Magellan AI, 56.24% also included Podtrac, 33.94% also included ArtsAI, 20.12% also included Adswizz, 18.08% also included Spotify, 17.71% also included Veritonic, 2.41% also included Podroll, 1.81% also included Podder, 0.83% also included Gumshoe, 0.60% also included Podcorn, and 0.42% also included Feedpress.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "41.45%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.07%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "13.35%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.74%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "6.95%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.66%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.44%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.51%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.42%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.37%" >}}
---

### 16. [Podroll](https://podroll.fm/)

Podroll was found on 0.12% of new episodes in February, growing 7.37% from last month.

Of these, 32.32% had 2 other trackers, 25.88% had 3 other trackers, 12.70% had one other tracker, 5.45% had 4 other trackers, 1.71% had 5 other trackers, 1.23% had 6 other trackers, 1.00% had 8 other trackers, and 0.95% had 7 other trackers.

73.13% also included Chartable, 48.01% also included Podtrac, 32.23% also included Podsights, 14.88% also included Podscribe, 13.55% also included Adswizz, 6.11% also included Podder, 3.70% also included Magellan AI, 3.60% also included Podcorn, 3.46% also included Gumshoe, 2.89% also included OP3, 2.46% also included Claritas, 1.18% also included ArtsAI, 0.71% also included Spotify, 0.57% also included CoHost Prefix, 0.43% also included United Podcasters, 0.28% also included Blubrry, and 0.09% also included Feedpress.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "41.66%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.00%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "12.51%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "11.33%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "4.88%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.27%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.56%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.42%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.28%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.09%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.11% of new episodes in February, growing 11.89% from last month.

Of these, 19.18% had one other tracker, 18.06% had 4 other trackers, 17.52% had 5 other trackers, 14.58% had 2 other trackers, 13.57% had 3 other trackers, 2.78% had 6 other trackers, 2.14% had 7 other trackers, and 1.12% had 8 other trackers.

51.50% also included Podsights, 47.81% also included Podtrac, 45.46% also included Chartable, 42.04% also included OP3, 34.62% also included Podcorn, 33.28% also included Podscribe, 13.03% also included Spotify, 5.56% also included Magellan AI, 3.90% also included Podroll, 3.74% also included Podder, 2.67% also included Audiotakes, 1.76% also included ArtsAI, 1.50% also included Adswizz, 0.96% also included United Podcasters, 0.96% also included Claritas, 0.43% also included CoHost Prefix, 0.16% also included Veritonic, and 0.11% also included Blubrry.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "42.63%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "27.40%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "19.34%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.72%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.82%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.18%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.53%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.32%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.21%" >}}
10. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.21%" >}}
---

### 18. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.09% of new episodes in February, growing 17.36% from last month.

Of these, 52.51% had one other tracker, 19.79% had 4 other trackers, 10.69% had 3 other trackers, 6.86% had 5 other trackers, 6.33% had 2 other trackers, 2.18% had 7 other trackers, and 1.19% had 6 other trackers.

53.50% also included Adswizz, 45.78% also included Podscribe, 40.17% also included Podsights, 29.22% also included Podtrac, 23.94% also included Chartable, 15.77% also included Magellan AI, 11.48% also included ArtsAI, 8.05% also included Spotify, 3.30% also included Gumshoe, and 1.85% also included Veritonic.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "19.53%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "13.59%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.85%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.17%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.91%" >}}
6. {{< a "https://kostenlos-hosten.de/" "Podcastbude" >}} {{< span "weak" "1.72%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.99%" >}}
8. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.79%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.53%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.20%" >}}
---

### 19. [Firstory](https://firstory.me/)

Firstory was found on 0.07% of new episodes in February, shrinking 14.17% from last month.

Of these, 71.08% had one other tracker.

71.08% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.74%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.26%" >}}
---

### 20. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.06% of new episodes in February, growing 3.91% from last month.

Of these, 55.28% had 6 other trackers, 11.47% had 5 other trackers, 10.66% had 7 other trackers, 10.57% had 4 other trackers, 3.88% had 2 other trackers, 3.16% had 8 other trackers, 2.53% had one other tracker, and 2.26% had 3 other trackers.

95.75% also included Podtrac, 86.54% also included Podscribe, 84.64% also included Chartable, 84.55% also included Podsights, 64.68% also included Magellan AI, 55.01% also included ArtsAI, 34.51% also included Claritas, 24.84% also included Adswizz, 13.64% also included Spotify, 2.53% also included Audiotakes, 1.36% also included Podder, and 0.27% also included Gumshoe.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "60.43%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "22.58%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.05%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "5.24%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.53%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.63%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.99%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.36%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.09%" >}}
---

### 21. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in February, growing 7.60% from last month.

Of these, 26.29% had one other tracker, 23.28% had 2 other trackers, and 3.45% had 3 other trackers.

40.09% also included Chartable, 16.81% also included Podtrac, 8.19% also included Adswizz, 7.33% also included Podder, 6.90% also included Podsights, and 3.88% also included Podcorn.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "35.34%" >}}
2. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "17.24%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "12.93%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "8.62%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "8.62%" >}}
6. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "8.19%" >}}
7. {{< a "https://www.blogtalkradio.com/" "Blog Talk Radio" >}} {{< span "weak" "4.31%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.88%" >}}
9. {{< a "https://kostenlos-hosten.de/" "Podcastbude" >}} {{< span "weak" "0.86%" >}}
---

### 22. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in February, growing 7.70% from last month.

Of these, 28.57% had one other tracker, 3.01% had 2 other trackers, and 3.01% had 5 other trackers.

23.31% also included Chartable, 14.29% also included Podtrac, 6.02% also included Podsights, 3.01% also included Podcorn, and 3.01% also included Podder.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "35.34%" >}}
2. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "16.54%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "15.04%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "9.77%" >}}
5. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "6.02%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.02%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "5.26%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.01%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.01%" >}}
---

### 23. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in February, growing 6.19% from last month.

Of these, 35.29% had one other tracker, 22.55% had 4 other trackers, 17.65% had 3 other trackers, and 7.84% had 2 other trackers.

51.96% also included Chartable, 49.02% also included Podsights, 22.55% also included Podscribe, 22.55% also included Magellan AI, 17.65% also included Gumshoe, 12.75% also included Podtrac, 8.82% also included Podroll, and 8.82% also included Podder.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "26.47%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "25.49%" >}}
3. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "20.59%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "17.65%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.84%" >}}
6. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.96%" >}}
---

### 24. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in February, shrinking 6.30% from last month.

Of these, 47.78% had one other tracker, and 21.11% had 2 other trackers.

64.44% also included Chartable, 22.22% also included Podtrac, and 3.33% also included Podcorn.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "37.78%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "21.11%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "16.67%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "11.11%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.44%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.33%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.33%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.22%" >}}
---

### 25. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on <0.01% of new episodes in February, shrinking 72.35% from last month.

Of these, 58.62% had one other tracker, 10.34% had 2 other trackers, and 3.45% had 3 other trackers.

51.72% also included Podcorn, 20.69% also included Chartable, 10.34% also included Podsights, 3.45% also included Blubrry, and 3.45% also included Podtrac.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "79.31%" >}}
2. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "10.34%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "6.90%" >}}
4. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "3.45%" >}}
---

### 26. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on <0.01% of new episodes in February, growing 32.64% from last month.

Of these, 38.46% had 3 other trackers, 30.77% had 8 other trackers, and 7.69% had 2 other trackers.

76.92% also included Chartable, 61.54% also included Podtrac, 53.85% also included Podsights, 46.15% also included Podroll, 38.46% also included Podcorn, 38.46% also included Podder, 30.77% also included OP3, and 30.77% also included Gumshoe.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "46.15%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "23.08%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.08%" >}}
4. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "7.69%" >}}
---

### 27. [Glystn](https://glystn.com/)

Glystn was found on <0.01% of new episodes in February, shrinking 48.99% from last month.

Of these, 57.14% had one other tracker, and 42.86% had 3 other trackers.

100.00% also included Chartable, 42.86% also included Podtrac, and 42.86% also included Podsights.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "57.14%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "42.86%" >}}


---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
