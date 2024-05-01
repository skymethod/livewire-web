---
title: "Top Podcast Tracking Services by Episode Share (March 2024)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-march-2024"
images:
- trackers-2024-03.png
date: 2024-04-01T18:17:00-05:00
lastmod: 2024-04-01T18:17:00-05:00
draft: false
rssrevision: 2024-03
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.9 million in March 2024), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in March, how many
of them included one or more of these tracking services?  Some episodes had as many as *nine* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

### A special note for March 2024 {#spreaker}
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
Month	Podtrac	Chartable	Adswizz	Podsights	Blubrry	Podcorn	Podscribe	Spotify	Médiamétrie	Podder	Feedpress	OP3	Claritas	ArtsAI	Podroll	Gumshoe	Audiotakes	Veritonic	Zencastr	Podkite	United Podcasters	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.00	1.16	2.07	2.09			0.42		0.32																1.61
Oct 2021	4.05	4.09	1.01	1.20	2.11	2.13			0.54		0.34																1.61
Nov 2021	4.07	4.30	1.02	1.25	2.01	2.14			0.57		0.32																0.59
Dec 2021	4.06	4.42	1.24	1.19	1.57	2.27			0.59		0.19																
Jan 2022	4.11	4.45	1.41	1.21	1.56	2.31			0.63		0.16																
Feb 2022	4.15	4.48	1.44	1.25	1.53	2.38			0.58		0.17																
Mar 2022	4.37	4.72	1.51	1.34	1.56	2.40			0.53		0.17																
Apr 2022	4.44	4.71	1.49	1.33	1.55	2.33			0.51		0.16																
May 2022	4.49	4.87	1.58	1.41	1.48	2.26			0.56		0.17																
Jun 2022	4.75	5.10	1.77	1.54	1.50	2.06			0.62		0.21													0.02			
Jul 2022	4.70	5.10	1.89	1.50	1.50	2.16			0.54		0.25													0.02			
Aug 2022	4.83	5.26	2.08	1.73	1.51	2.45			0.41		0.20			0.10										0.01			
Sep 2022	7.53	5.40	2.26	1.74	1.49	2.45	0.02		0.52		0.21		0.01	0.09						0.01				0.02	0.02		
Oct 2022	8.24	5.48	2.35	1.81	1.61	2.51	0.07		0.50		0.18	0.03	0.02	0.10					0.01	0.01				0.02	0.04		
Nov 2022	8.11	5.62	2.37	2.03	1.62	2.43	0.15		0.50	0.01	0.18	0.04	0.03	0.10					0.01	0.01				0.02	0.05		
Dec 2022	8.01	5.54	2.32	1.81	1.61	2.05	0.03		0.49	0.04	0.18	0.05	0.02	0.05					0.01	0.01			0.01	0.02	0.05		
Jan 2023	7.85	5.56	2.35	1.88	1.61	2.15	0.20		0.54	0.11	0.18	0.07	0.06	0.10					0.01	0.01			0.01	0.02	0.06		
Feb 2023	7.58	5.51	2.29	1.92	1.62	2.30	0.21		0.49	0.11	0.19	0.07	0.07	0.10					0.01	0.01			0.01	0.02	0.06	0.03	
Mar 2023	7.79	5.53	2.25	2.03	1.53	2.22	0.21		0.45	0.11	0.18	0.08	0.07	0.11	0.04			0.04	0.01	0.01			0.01	0.02	0.06		
Apr 2023	7.66	5.43	2.26	2.00	1.67	2.20	0.21		0.45	0.15	0.17	0.09	0.07	0.11	0.06	0.08		0.05	0.01	0.01			0.01	0.01			
May 2023	7.58	5.59	2.27	2.04	1.67	2.28	0.24		0.45	0.15	0.19	0.09	0.08	0.11	0.09	0.07		0.05	0.01	0.01		0.01	0.01	0.01			
Jun 2023	8.22	5.83	2.39	2.23	1.64	1.86	0.26		0.51	0.15	0.19	0.09	0.07	0.12	0.10	0.08		0.05	0.01	0.01		0.01	0.01	0.01			
Jul 2023	8.60	5.95	2.38	2.52	1.53	1.17	0.27	0.01	0.55	0.14	0.18	0.08	0.07	0.11	0.14	0.06		0.06	0.01	0.01		0.01	0.01	0.01			
Aug 2023	9.19	6.43	2.72	2.76	1.58	1.23	0.36	0.03	0.53	0.15	0.17	0.11	0.08	0.12	0.16	0.07	0.04	0.07	0.01	0.01		0.02	0.01				
Sep 2023	8.46	5.77	2.49	2.47	1.39	1.10	0.37	0.05	0.58	0.15	0.16	0.10	0.10	0.12	0.13	0.07	0.05	0.06	0.01	0.01		0.02	0.01				
Oct 2023	7.90	5.54	2.29	2.28	1.37	1.11	0.39	0.08	0.50	0.16	0.16	0.10	0.10	0.12	0.12	0.08	0.05	0.06	0.02	0.01		0.03	0.01				
Nov 2023	7.65	5.59	2.25	2.33	1.45	1.14	0.47	0.11	0.33	0.16	0.17	0.13	0.11	0.12	0.12	0.10	0.06	0.06	0.01	0.01		0.03					
Dec 2023	7.48	5.60	2.20	2.19	1.53	1.12	0.54	0.12	0.33	0.16	0.16	0.11	0.11	0.12	0.12	0.09	0.06	0.06	0.01	0.01		0.03					
Jan 2024	7.64	5.61	2.37	2.21	1.55	1.17	0.65	0.15	0.25	0.16	0.17	0.13	0.12	0.14	0.11	0.10	0.08	0.06	0.01	0.01	0.01	0.01					
Feb 2024	7.69	5.58	2.38	2.22	1.52	1.21	0.69	0.22	0.22	0.17	0.17	0.16	0.13	0.13	0.12	0.11	0.09	0.06	0.01	0.01	0.01						
Mar 2024	9.01	5.46	2.53	2.19	1.54	1.14	0.69	0.25	0.22	0.16	0.16	0.14	0.14	0.12	0.12	0.10	0.09	0.06	0.01	0.01	0.01						
{{< /graph >}}

---

### Overall

At least one tracker was found on 17.05% of new episodes in March, growing 7.60% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "26.35%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.97%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.35%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.09%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.49%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.29%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "3.09%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.37%" >}}
9. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.95%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.90%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of March 2024.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 9.01% of new episodes in March, growing 17.12% from last month.

Of these, 20.01% had one other tracker, 11.69% had 2 other trackers, 2.48% had 3 other trackers, 1.21% had 4 other trackers, 0.95% had 5 other trackers, 0.39% had 6 other trackers, 0.26% had 7 other trackers, and 0.04% had 8 other trackers.

25.95% also included Chartable, 15.71% also included Podsights, 6.24% also included Adswizz, 4.97% also included Podscribe, 1.93% also included Magellan AI, 1.85% also included Spotify, 1.52% also included Podcorn, 1.16% also included Podder, 1.06% also included ArtsAI, 0.99% also included Claritas, 0.75% also included OP3, 0.66% also included Veritonic, 0.63% also included Podroll, 0.57% also included Gumshoe, 0.40% also included Blubrry, 0.30% also included Audiotakes, 0.06% also included Feedpress, 0.03% also included CoHost Prefix, 0.02% also included Médiamétrie, 0.02% also included Zencastr, 0.02% also included United Podcasters, 0.01% also included AdBarker, and 0.01% also included Podkite.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "48.94%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "14.51%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.06%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.95%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.42%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.38%" >}}
7. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.03%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.93%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.43%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.43%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 6.09% of new episodes in March, shrinking 1.90% from last month.

Of these, 43.99% also included Podtrac, 9.32% also included Podscribe, 6.31% also included Adswizz, 3.99% also included Magellan AI, 2.36% also included Podcorn, 2.16% also included Claritas, 2.02% also included ArtsAI, 1.88% also included Podder, 1.50% also included Podroll, 1.30% also included Gumshoe, 1.12% also included OP3, 1.01% also included Veritonic, 0.85% also included Firstory, 0.77% also included Audiotakes, 0.35% also included Blubrry, 0.10% also included Feedpress, 0.08% also included United Podcasters, 0.07% also included Zencastr, 0.06% also included AdBarker, 0.06% also included CoHost Prefix, 0.04% also included Podkite, 0.01% also included Voxalyze, and <0.01% also included Glystn.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "31.15%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "21.86%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.61%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.99%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.88%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.18%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.18%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.59%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.30%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.20%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.46% of new episodes in March, shrinking 2.13% from last month.

Of these, 29.69% had one other tracker, 20.44% had 2 other trackers, 4.30% had 3 other trackers, 2.20% had 4 other trackers, 1.64% had 5 other trackers, 0.68% had 6 other trackers, 0.39% had 7 other trackers, and 0.07% had 8 other trackers.

42.82% also included Podtrac, 29.34% also included Podsights, 7.87% also included Podscribe, 5.73% also included Adswizz, 3.92% also included Magellan AI, 3.71% also included Spotify, 2.14% also included Claritas, 2.09% also included Podcorn, 1.93% also included Podder, 1.93% also included ArtsAI, 1.61% also included Podroll, 0.97% also included Veritonic, 0.95% also included Firstory, 0.92% also included Gumshoe, 0.73% also included OP3, 0.45% also included Audiotakes, 0.31% also included Blubrry, 0.12% also included Feedpress, 0.07% also included United Podcasters, 0.07% also included Zencastr, 0.06% also included AdBarker, 0.06% also included CoHost Prefix, 0.04% also included Podkite, 0.01% also included Voxalyze, and <0.01% also included Glystn.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.50%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "21.15%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.51%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.24%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.22%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.54%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.04%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.75%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.57%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.44%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.53% of new episodes in March, growing 6.58% from last month.

Of these, 27.63% had one other tracker, 3.11% had 2 other trackers, 2.28% had 3 other trackers, 0.65% had 4 other trackers, 0.52% had 5 other trackers, 0.30% had 6 other trackers, 0.28% had 7 other trackers, and 0.12% had 8 other trackers.

22.20% also included Podtrac, 12.37% also included Chartable, 5.51% also included Podsights, 2.01% also included Podscribe, 1.66% also included Audiotakes, 1.29% also included Blubrry, 0.98% also included ArtsAI, 0.93% also included Claritas, 0.92% also included Spotify, 0.60% also included Veritonic, 0.58% also included Magellan AI, 0.55% also included Podroll, 0.51% also included OP3, 0.39% also included Podcorn, 0.06% also included Podder, 0.06% also included Gumshoe, and 0.02% also included Zencastr.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "42.47%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "12.79%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "9.39%" >}}
4. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "7.93%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.34%" >}}
6. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "5.35%" >}}
7. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "4.53%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.26%" >}}
9. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.20%" >}}
10. {{< a "https://www.julephosting.de/" "Julep Hosting" >}} {{< span "weak" "1.03%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.19% of new episodes in March, shrinking 1.28% from last month.

Of these, 38.30% had 2 other trackers, 31.99% had one other tracker, 9.61% had 3 other trackers, 5.37% had 4 other trackers, 4.80% had 5 other trackers, 1.75% had 6 other trackers, 0.97% had 7 other trackers, and 0.17% had 8 other trackers.

73.02% also included Chartable, 64.50% also included Podtrac, 19.39% also included Podscribe, 9.55% also included Magellan AI, 6.35% also included Adswizz, 5.06% also included Claritas, 4.49% also included ArtsAI, 3.95% also included Podder, 2.53% also included Spotify, 2.43% also included Gumshoe, 2.35% also included Veritonic, 2.25% also included Podcorn, 1.81% also included Audiotakes, 1.63% also included OP3, 1.61% also included Podroll, 0.21% also included Blubrry, 0.17% also included United Podcasters, 0.09% also included Feedpress, 0.07% also included CoHost Prefix, 0.06% also included Zencastr, 0.02% also included Podkite, and 0.01% also included Voxalyze.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "57.37%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "25.63%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.32%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.26%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.02%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.50%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.42%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.12%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.98%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.92%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.54% of new episodes in March, growing 0.69% from last month.

Of these, 6.18% had one other tracker, 0.57% had 2 other trackers, 0.07% had 3 other trackers, 0.02% had 4 other trackers, 0.01% had 6 other trackers, and 0.01% had 5 other trackers.

2.33% also included Podtrac, 2.13% also included Adswizz, 1.09% also included Chartable, 1.05% also included Feedpress, 0.30% also included Podsights, 0.26% also included OP3, 0.26% also included Podcorn, 0.15% also included Podscribe, 0.06% also included Magellan AI, 0.03% also included Podroll, 0.02% also included Spotify, 0.02% also included Podder, 0.01% also included Audiotakes, and 0.01% also included Veritonic.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "38.75%" >}}
2. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "6.64%" >}}
3. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "6.57%" >}}
4. {{< a "https://www.rferl.org/" "Radio Free Europe and Radio Liberty" >}} {{< span "weak" "3.29%" >}}
5. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "3.04%" >}}
6. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "2.86%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.29%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.63%" >}}
9. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.20%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "0.97%" >}}
---

### 6. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 1.14% of new episodes in March, shrinking 5.09% from last month.

Of these, 12.51% had one other tracker, 3.17% had 2 other trackers, 1.62% had 5 other trackers, 1.29% had 3 other trackers, 0.97% had 4 other trackers, 0.36% had 6 other trackers, 0.06% had 8 other trackers, and 0.03% had 7 other trackers.

11.96% also included Podtrac, 10.00% also included Chartable, 4.31% also included Podsights, 3.17% also included Gumshoe, 3.11% also included OP3, 2.23% also included Podscribe, 0.86% also included Adswizz, 0.64% also included Podder, 0.35% also included Blubrry, 0.30% also included Podroll, 0.19% also included Spotify, 0.15% also included Feedpress, 0.07% also included CoHost Prefix, 0.06% also included Voxalyze, 0.06% also included Zencastr, 0.04% also included AdBarker, 0.04% also included Magellan AI, 0.02% also included United Podcasters, and 0.02% also included Podkite.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "45.28%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.41%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "9.78%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.82%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "5.28%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.86%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.58%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.96%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.59%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.28%" >}}
---

### 7. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.69% of new episodes in March, shrinking 1.33% from last month.

Of these, 20.21% had 3 other trackers, 18.31% had one other tracker, 17.43% had 2 other trackers, 15.46% had 4 other trackers, 14.44% had 5 other trackers, 5.81% had 6 other trackers, 3.55% had 7 other trackers, and 0.49% had 8 other trackers.

65.32% also included Podtrac, 62.70% also included Chartable, 62.11% also included Podsights, 28.76% also included Magellan AI, 17.65% also included Claritas, 16.69% also included Spotify, 15.32% also included ArtsAI, 7.73% also included Veritonic, 7.42% also included Adswizz, 6.88% also included Audiotakes, 5.38% also included Gumshoe, 4.75% also included Podder, 4.14% also included OP3, 3.72% also included Podcorn, 2.32% also included Podroll, 0.34% also included Blubrry, 0.25% also included United Podcasters, and 0.06% also included Feedpress.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "56.37%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.00%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.41%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "6.35%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.11%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.25%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.25%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.76%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.75%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.58%" >}}
---

### 8. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.25% of new episodes in March, shrinking 0.81% from last month.

Of these, 27.56% had 5 other trackers, 26.25% had 4 other trackers, 13.86% had 3 other trackers, 10.62% had 6 other trackers, 8.56% had 7 other trackers, 6.81% had 2 other trackers, 4.37% had one other tracker, and 1.23% had 8 other trackers.

83.88% also included Chartable, 82.21% also included Podsights, 77.31% also included Podscribe, 68.22% also included Podtrac, 36.97% also included Claritas, 21.66% also included ArtsAI, 17.85% also included Spotify, 16.22% also included Veritonic, 13.78% also included Podder, 7.80% also included Audiotakes, 5.74% also included Adswizz, 1.99% also included Gumshoe, 1.19% also included Podroll, 0.54% also included United Podcasters, 0.34% also included Blubrry, and 0.18% also included Podcorn.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "63.17%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.95%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.79%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.60%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.54%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.28%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.77%" >}}
8. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.26%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.24%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.16%" >}}
---

### 9. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.25% of new episodes in March, growing 13.27% from last month.

Of these, 53.59% had 2 other trackers, 15.68% had 3 other trackers, 8.69% had 4 other trackers, 7.75% had 7 other trackers, 6.52% had one other tracker, 3.27% had 6 other trackers, 2.09% had 5 other trackers, and 1.25% had 8 other trackers.

80.74% also included Chartable, 66.26% also included Podtrac, 45.53% also included Podscribe, 22.12% also included Podsights, 18.11% also included Magellan AI, 16.46% also included ArtsAI, 9.30% also included Adswizz, 8.63% also included Veritonic, 7.40% also included Claritas, 5.25% also included Gumshoe, 4.33% also included Audiotakes, 4.01% also included OP3, 0.86% also included Podcorn, 0.49% also included Podder, 0.14% also included Blubrry, 0.10% also included United Podcasters, and 0.02% also included Podroll.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "48.42%" >}}
2. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "10.20%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.67%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.36%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.04%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.54%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.48%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.74%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.82%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.43%" >}}
---

### 10. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.22% of new episodes in March, growing 0.95% from last month.

Of these, 0.97% had one other tracker.

0.97% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "66.03%" >}}
2. {{< a "https://soundcast.fm/" "SoundCast" >}} {{< span "weak" "12.92%" >}}
3. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "12.62%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "4.31%" >}}
5. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "2.44%" >}}
6. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "0.07%" >}}
---

### 11. [Podder](https://www.podderapp.com/)

Podder was found on 0.16% of new episodes in March, shrinking 5.28% from last month.

Of these, 21.94% had one other tracker, 20.75% had 3 other trackers, 13.57% had 4 other trackers, 13.28% had 2 other trackers, 12.38% had 5 other trackers, 2.28% had 6 other trackers, 0.48% had 7 other trackers, and 0.42% had 8 other trackers.

65.88% also included Chartable, 65.52% also included Podtrac, 54.17% also included Podsights, 21.94% also included Magellan AI, 20.30% also included Podscribe, 4.59% also included Podcorn, 3.34% also included Podroll, 2.95% also included OP3, 2.76% also included Gumshoe, 1.38% also included Claritas, 0.99% also included Adswizz, 0.99% also included ArtsAI, 0.77% also included Spotify, 0.45% also included Zencastr, 0.35% also included Veritonic, 0.29% also included CoHost Prefix, 0.26% also included United Podcasters, 0.22% also included Blubrry, and 0.13% also included Podkite.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "61.61%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "11.64%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "6.93%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.55%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.98%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.30%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.76%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.48%" >}}
9. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "0.67%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.55%" >}}
---

### 12. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.16% of new episodes in March, shrinking 7.57% from last month.

Of these, 17.21% had one other tracker, 1.21% had 2 other trackers, and 0.26% had 5 other trackers.

10.26% also included Blubrry, 4.03% also included Chartable, 3.67% also included Podtrac, 1.28% also included Podsights, 1.11% also included Podcorn, 0.26% also included Podscribe, 0.26% also included Claritas, and 0.07% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "49.46%" >}}
2. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "8.29%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.74%" >}}
4. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "5.18%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.65%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.10%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.00%" >}}
8. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.74%" >}}
9. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.57%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.51%" >}}
---

### 13. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.14% of new episodes in March, shrinking 9.17% from last month.

Of these, 25.78% had one other tracker, 12.53% had 5 other trackers, 10.84% had 4 other trackers, 10.23% had 2 other trackers, 7.06% had 3 other trackers, 2.74% had 6 other trackers, 0.47% had 8 other trackers, and 0.22% had 7 other trackers.

47.28% also included Podtrac, 28.05% also included Chartable, 25.14% also included Podsights, 24.92% also included Podcorn, 24.05% also included Gumshoe, 19.88% also included Podscribe, 9.11% also included Adswizz, 7.06% also included Spotify, 3.31% also included Podder, 3.10% also included Podroll, 2.84% also included Blubrry, 0.29% also included CoHost Prefix, and 0.07% also included Feedpress.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "35.29%" >}}
2. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "9.72%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.51%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.85%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.64%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.24%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.70%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.52%" >}}
9. {{< a "https://vodio.fr/" "Vodio" >}} {{< span "weak" "2.12%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.91%" >}}
---

### 14. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.14% of new episodes in March, growing 12.59% from last month.

Of these, 37.00% had 5 other trackers, 22.06% had 4 other trackers, 16.39% had 6 other trackers, 7.23% had 3 other trackers, 6.94% had 7 other trackers, 4.58% had one other tracker, and 3.89% had 2 other trackers.

85.57% also included Podscribe, 82.81% also included Chartable, 78.55% also included Podsights, 66.70% also included Magellan AI, 63.25% also included Podtrac, 29.23% also included ArtsAI, 16.65% also included Adswizz, 15.09% also included Veritonic, 13.16% also included Spotify, 1.56% also included Podder, 1.31% also included Podroll, 0.29% also included Feedpress, and 0.15% also included Gumshoe.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "50.89%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "14.39%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "11.20%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.54%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.49%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "5.45%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.20%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.29%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.25%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.22%" >}}
---

### 15. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.12% of new episodes in March, shrinking 5.69% from last month.

Of these, 24.81% had 5 other trackers, 18.99% had 7 other trackers, 18.95% had 3 other trackers, 17.34% had 6 other trackers, 11.64% had 4 other trackers, 5.37% had 2 other trackers, 2.52% had 8 other trackers, and 0.17% had one other tracker.

84.56% also included Chartable, 84.39% also included Podscribe, 79.23% also included Podsights, 76.59% also included Podtrac, 44.38% also included Magellan AI, 33.24% also included Spotify, 33.20% also included Claritas, 27.42% also included Veritonic, 19.94% also included Adswizz, 9.74% also included Audiotakes, 1.28% also included Podder, 0.91% also included Gumshoe, and 0.66% also included Podroll.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "35.51%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.82%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "12.18%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.98%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.74%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "7.47%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.86%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.36%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.74%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.17%" >}}
---

### 16. [Podroll](https://podroll.fm/)

Podroll was found on 0.12% of new episodes in March, shrinking 5.70% from last month.

Of these, 36.51% had 2 other trackers, 25.51% had 3 other trackers, 15.71% had one other tracker, 4.17% had 4 other trackers, 1.38% had 6 other trackers, 0.75% had 5 other trackers, 0.58% had 8 other trackers, and 0.40% had 7 other trackers.

76.13% also included Chartable, 48.76% also included Podtrac, 30.57% also included Podsights, 13.71% also included Podscribe, 12.07% also included Adswizz, 4.61% also included Podder, 3.82% also included OP3, 2.93% also included Podcorn, 2.62% also included Magellan AI, 2.48% also included Gumshoe, 1.60% also included Claritas, 0.71% also included ArtsAI, 0.53% also included CoHost Prefix, 0.40% also included Blubrry, 0.40% also included United Podcasters, and 0.04% also included Spotify.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "44.28%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.61%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "11.89%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.78%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "6.65%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "4.04%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.42%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.24%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.02%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.67%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.10% of new episodes in March, shrinking 12.38% from last month.

Of these, 20.34% had 5 other trackers, 18.68% had 4 other trackers, 16.90% had 2 other trackers, 15.34% had 3 other trackers, 10.98% had one other tracker, 4.14% had 6 other trackers, 1.51% had 7 other trackers, and 0.70% had 8 other trackers.

55.92% also included Podsights, 53.50% also included Podtrac, 52.74% also included Chartable, 38.64% also included Podscribe, 38.00% also included Podcorn, 35.95% also included OP3, 13.83% also included Spotify, 5.33% also included Magellan AI, 4.63% also included Podder, 3.01% also included Podroll, 2.05% also included Audiotakes, 1.67% also included Adswizz, 1.18% also included ArtsAI, 0.91% also included United Podcasters, 0.43% also included CoHost Prefix, 0.22% also included Claritas, and 0.22% also included Veritonic.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "36.54%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.01%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "22.50%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.73%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.88%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.40%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.54%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.32%" >}}
9. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.32%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.22%" >}}
---

### 18. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.09% of new episodes in March, growing 1.32% from last month.

Of these, 45.34% had one other tracker, 22.59% had 4 other trackers, 12.07% had 3 other trackers, 6.55% had 2 other trackers, 5.86% had 5 other trackers, 5.17% had 6 other trackers, and 1.26% had 7 other trackers.

52.76% also included Podscribe, 47.13% also included Adswizz, 44.54% also included Podsights, 30.34% also included Podtrac, 27.30% also included Chartable, 22.24% also included Magellan AI, 13.56% also included ArtsAI, 12.18% also included Spotify, 2.18% also included Gumshoe, 1.84% also included Veritonic, and 0.11% also included Blubrry.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "21.84%" >}}
2. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "17.82%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.93%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.05%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.78%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.55%" >}}
7. {{< a "https://kostenlos-hosten.de/" "Podcastbude" >}} {{< span "weak" "1.38%" >}}
8. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.75%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.52%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.23%" >}}
---

### 19. [Firstory](https://firstory.me/)

Firstory was found on 0.07% of new episodes in March, growing 5.64% from last month.

Of these, 74.72% had one other tracker.

74.72% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.71%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.29%" >}}
---

### 20. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.06% of new episodes in March, shrinking 2.71% from last month.

Of these, 30.98% had 6 other trackers, 30.08% had 7 other trackers, 11.80% had 5 other trackers, 11.07% had 4 other trackers, 5.00% had 8 other trackers, 4.43% had 2 other trackers, 4.34% had 3 other trackers, and 2.05% had one other tracker.

95.33% also included Podtrac, 84.51% also included Podscribe, 84.18% also included Chartable, 82.21% also included Podsights, 65.98% also included Magellan AI, 54.43% also included ArtsAI, 34.59% also included Spotify, 34.02% also included Claritas, 24.43% also included Adswizz, 2.62% also included Audiotakes, 0.90% also included Podder, 0.33% also included Gumshoe, and 0.16% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "59.67%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "21.80%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.03%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.75%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.54%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.89%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.74%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.33%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.25%" >}}
---

### 21. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in March, shrinking 11.72% from last month.

Of these, 24.57% had one other tracker, 16.81% had 2 other trackers, 3.02% had 3 other trackers, and 1.29% had 4 other trackers.

30.17% also included Chartable, 15.52% also included Podtrac, 10.34% also included Podsights, 6.03% also included Podder, 5.60% also included Podcorn, 3.45% also included Adswizz, and 1.29% also included United Podcasters.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "37.07%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "16.81%" >}}
3. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "10.78%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "10.34%" >}}
5. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "8.62%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.47%" >}}
7. {{< a "https://www.blogtalkradio.com/" "Blog Talk Radio" >}} {{< span "weak" "5.17%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.45%" >}}
9. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "1.29%" >}}
---

### 22. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in March, shrinking 2.43% from last month.

Of these, 31.29% had one other tracker, 2.72% had 2 other trackers, and 2.72% had 5 other trackers.

25.85% also included Chartable, 13.61% also included Podtrac, 5.44% also included Podsights, 2.72% also included Podcorn, and 2.72% also included Podder.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "38.78%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "12.93%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "12.93%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "12.24%" >}}
5. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "6.12%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.44%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.44%" >}}
8. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "2.72%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.72%" >}}
10. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.68%" >}}
---

### 23. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in March, growing 23.76% from last month.

Of these, 32.87% had one other tracker, 20.98% had 4 other trackers, 16.08% had 3 other trackers, 7.69% had 2 other trackers, and 3.50% had 6 other trackers.

54.55% also included Chartable, 51.05% also included Podsights, 23.78% also included Podscribe, 20.28% also included Podtrac, 18.88% also included Magellan AI, 11.89% also included Gumshoe, 6.29% also included Podroll, 5.59% also included Podder, 3.50% also included Podcorn, 3.50% also included Spotify, and 2.10% also included Zencastr.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "38.46%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "22.38%" >}}
3. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "20.28%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "11.19%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.59%" >}}
6. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.40%" >}}
7. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "0.70%" >}}
---

### 24. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in March, growing 1.03% from last month.

Of these, 42.72% had one other tracker, 25.24% had 2 other trackers, and 1.94% had 3 other trackers.

66.02% also included Chartable, 24.27% also included Podtrac, and 8.74% also included Podcorn.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "34.95%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "24.27%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "15.53%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "12.62%" >}}
5. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "4.85%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.88%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.91%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "0.97%" >}}
---

### 25. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on <0.01% of new episodes in March, growing 154.65% from last month.

Of these, 46.67% had 2 other trackers, 28.00% had 3 other trackers, 10.67% had 8 other trackers, and 5.33% had one other tracker.

90.67% also included Chartable, 70.67% also included Podtrac, 37.33% also included Podsights, 20.00% also included Podcorn, 16.00% also included Podroll, 12.00% also included Podder, 10.67% also included OP3, and 10.67% also included Gumshoe.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "33.33%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "26.67%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "16.00%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "16.00%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.33%" >}}
6. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "2.67%" >}}
---

### 26. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on <0.01% of new episodes in March, shrinking 26.94% from last month.

Of these, 70.83% had one other tracker, and 16.67% had 2 other trackers.

58.33% also included Podcorn, 29.17% also included Chartable, and 16.67% also included Podsights.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "75.00%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.50%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "8.33%" >}}
4. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "4.17%" >}}
---

### 27. [Glystn](https://glystn.com/)

Glystn was found on <0.01% of new episodes in March, shrinking 49.55% from last month.

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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2024-03.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
