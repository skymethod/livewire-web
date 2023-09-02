---
title: "Top Podcast Tracking Services by Episode Share (August 2023)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2023-08.png
date: 2023-09-01T19:22:00-05:00
lastmod: 2023-09-01T19:22:00-05:00
draft: false
rssrevision: 2023-08
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.7 million in August 2023), 
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
Month	Podtrac	Chartable	Podsights	Adswizz	Blubrry	Podcorn	Médiamétrie	Podscribe	Feedpress	Podroll	Podder	ArtsAI	OP3	Claritas	Gumshoe	Veritonic	Audiotakes	Spotify	Voxalyze	Zencastr	Glystn	Podkite	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.16	1.00	2.07	2.09	0.42		0.32																	1.61
Oct 2021	4.05	4.09	1.20	1.01	2.11	2.13	0.54		0.34																	1.61
Nov 2021	4.07	4.30	1.25	1.02	2.01	2.14	0.57		0.32																	0.59
Dec 2021	4.06	4.42	1.19	1.24	1.57	2.27	0.59		0.19																	
Jan 2022	4.11	4.45	1.21	1.41	1.56	2.31	0.63		0.16																	
Feb 2022	4.15	4.48	1.25	1.44	1.53	2.38	0.58		0.17																	
Mar 2022	4.37	4.72	1.34	1.51	1.56	2.40	0.53		0.17																	
Apr 2022	4.44	4.71	1.33	1.49	1.55	2.33	0.51		0.16																	
May 2022	4.49	4.87	1.41	1.58	1.48	2.26	0.56		0.17																	
Jun 2022	4.75	5.10	1.54	1.77	1.50	2.06	0.62		0.21														0.02			
Jul 2022	4.70	5.10	1.50	1.89	1.50	2.16	0.54		0.25														0.02			
Aug 2022	4.83	5.26	1.73	2.08	1.51	2.45	0.41		0.20			0.10											0.01			
Sep 2022	7.53	5.40	1.74	2.26	1.49	2.45	0.52	0.02	0.21			0.09		0.01								0.01	0.02	0.02		
Oct 2022	8.24	5.48	1.81	2.35	1.61	2.51	0.50	0.07	0.18			0.10	0.03	0.02						0.01		0.01	0.02	0.04		
Nov 2022	8.11	5.62	2.03	2.37	1.62	2.43	0.50	0.15	0.18		0.01	0.10	0.04	0.03						0.01		0.01	0.02	0.05		
Dec 2022	8.01	5.54	1.81	2.32	1.61	2.05	0.49	0.03	0.18		0.04	0.05	0.05	0.02						0.01	0.01	0.01	0.02	0.05		
Jan 2023	7.85	5.56	1.88	2.35	1.61	2.15	0.54	0.20	0.18		0.11	0.10	0.07	0.06						0.01	0.01	0.01	0.02	0.06		
Feb 2023	7.58	5.51	1.92	2.29	1.62	2.30	0.49	0.21	0.19		0.11	0.10	0.07	0.07						0.01	0.01	0.01	0.02	0.06	0.03	
Mar 2023	7.79	5.53	2.03	2.25	1.53	2.22	0.45	0.21	0.18	0.04	0.11	0.11	0.08	0.07		0.04				0.01	0.01	0.01	0.02	0.06		
Apr 2023	7.66	5.43	2.00	2.26	1.67	2.20	0.45	0.21	0.17	0.06	0.15	0.11	0.09	0.07	0.08	0.05				0.01	0.01	0.01	0.01			
May 2023	7.58	5.59	2.04	2.27	1.67	2.28	0.45	0.24	0.19	0.09	0.15	0.11	0.09	0.08	0.07	0.05			0.01	0.01	0.01	0.01	0.01			
Jun 2023	8.22	5.83	2.23	2.39	1.64	1.86	0.51	0.26	0.19	0.10	0.15	0.12	0.09	0.07	0.08	0.05			0.01	0.01	0.01	0.01	0.01			
Jul 2023	8.60	5.95	2.52	2.38	1.53	1.17	0.55	0.27	0.18	0.14	0.14	0.11	0.08	0.07	0.06	0.06		0.01	0.01	0.01	0.01	0.01	0.01			
Aug 2023	9.19	6.43	2.76	2.72	1.58	1.23	0.53	0.36	0.17	0.16	0.15	0.12	0.11	0.08	0.07	0.07	0.04	0.03	0.02	0.01	0.01	0.01				
{{< /graph >}}

---

### Overall

At least one tracker was found on 18.53% of new episodes in August, growing 6.01% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "22.50%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "15.16%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.92%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.43%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.61%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.59%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.70%" >}}
8. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.64%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.47%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.97%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of August 2023.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 9.19% of new episodes in August, growing 6.53% from last month.

Of these, 25.26% had one other tracker, 11.82% had 2 other trackers, 2.04% had 3 other trackers, 0.88% had 4 other trackers, 0.64% had 5 other trackers, 0.21% had 6 other trackers, 0.06% had 7 other trackers, and 0.01% had 8 other trackers.

30.51% also included Chartable, 16.49% also included Podsights, 6.47% also included Adswizz, 1.82% also included Podscribe, 1.52% also included Podcorn, 1.15% also included Podder, 0.94% also included ArtsAI, 0.79% also included Podroll, 0.69% also included OP3, 0.60% also included Veritonic, 0.52% also included Magellan AI, 0.51% also included Blubrry, 0.48% also included Gumshoe, 0.47% also included Claritas, 0.10% also included Feedpress, 0.09% also included Voxalyze, 0.08% also included Glystn, 0.07% also included Spotify, 0.03% also included Podkite, 0.03% also included Audiotakes, 0.02% also included Médiamétrie, 0.02% also included AdBarker, 0.01% also included Zencastr, and <0.01% also included Firstory.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "44.37%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "18.62%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "12.16%" >}}
4. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "3.04%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.59%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.31%" >}}
7. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "2.17%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.72%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.37%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.12%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 7.42% of new episodes in August, growing 7.44% from last month.

Of these, 42.48% also included Podtrac, 6.70% also included Adswizz, 4.36% also included Podscribe, 2.10% also included Podcorn, 1.73% also included Podder, 1.63% also included ArtsAI, 1.55% also included Podroll, 1.09% also included Magellan AI, 0.99% also included Claritas, 0.87% also included Veritonic, 0.85% also included Gumshoe, 0.83% also included Firstory, 0.78% also included OP3, 0.50% also included Blubrry, 0.19% also included Audiotakes, 0.16% also included Voxalyze, 0.10% also included Glystn, 0.06% also included AdBarker, 0.06% also included Feedpress, 0.04% also included Podkite, and 0.03% also included Zencastr.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.24%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "24.45%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.15%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.52%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.05%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.05%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.47%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.37%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.25%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.13%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 6.43% of new episodes in August, growing 7.74% from last month.

Of these, 35.98% had one other tracker, 17.67% had 2 other trackers, 3.18% had 3 other trackers, 1.38% had 4 other trackers, 0.86% had 5 other trackers, 0.25% had 6 other trackers, 0.07% had 7 other trackers, and 0.01% had 8 other trackers.

43.61% also included Podtrac, 27.73% also included Podsights, 4.87% also included Adswizz, 3.82% also included Podscribe, 1.88% also included Podcorn, 1.67% also included Podder, 1.60% also included ArtsAI, 1.49% also included Podroll, 1.14% also included Magellan AI, 0.96% also included Firstory, 0.89% also included Claritas, 0.82% also included Veritonic, 0.49% also included Blubrry, 0.48% also included Gumshoe, 0.47% also included OP3, 0.23% also included Spotify, 0.19% also included Voxalyze, 0.12% also included Glystn, 0.09% also included Audiotakes, 0.07% also included AdBarker, 0.07% also included Feedpress, 0.04% also included Podkite, and 0.03% also included Zencastr.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "32.29%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "21.78%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.66%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.68%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.57%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.56%" >}}
7. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.59%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.57%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.42%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.24%" >}}
---

### 3. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.76% of new episodes in August, growing 9.49% from last month.

Of these, 36.20% had one other tracker, 35.94% had 2 other trackers, 7.41% had 3 other trackers, 3.76% had 4 other trackers, 2.35% had 5 other trackers, 0.58% had 6 other trackers, 0.17% had 7 other trackers, and 0.03% had 8 other trackers.

64.52% also included Chartable, 54.86% also included Podtrac, 10.02% also included Adswizz, 9.33% also included Podscribe, 3.50% also included Podder, 3.46% also included ArtsAI, 2.51% also included Magellan AI, 2.50% also included Podroll, 2.28% also included Podcorn, 2.27% also included Claritas, 2.06% also included Veritonic, 2.03% also included Gumshoe, 1.34% also included OP3, 0.51% also included Audiotakes, 0.26% also included Voxalyze, 0.24% also included Spotify, 0.20% also included Blubrry, 0.08% also included Podkite, 0.04% also included Zencastr, and 0.03% also included Feedpress.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "48.81%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "34.91%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.42%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.99%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.91%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.82%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.36%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.89%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.87%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.84%" >}}
---

### 4. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.72% of new episodes in August, growing 13.92% from last month.

Of these, 31.88% had one other tracker, 2.34% had 2 other trackers, 2.27% had 3 other trackers, 0.50% had 6 other trackers, 0.43% had 5 other trackers, 0.33% had 4 other trackers, and 0.18% had 7 other trackers.

21.90% also included Podtrac, 11.54% also included Chartable, 10.20% also included Podsights, 1.29% also included Blubrry, 1.17% also included Podscribe, 1.07% also included ArtsAI, 1.04% also included Audiotakes, 0.89% also included Claritas, 0.68% also included Veritonic, 0.60% also included Podroll, 0.16% also included Magellan AI, 0.15% also included Spotify, 0.13% also included Podcorn, 0.12% also included OP3, 0.09% also included Podder, 0.02% also included Gumshoe, and <0.01% also included Feedpress.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "24.36%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "18.04%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "12.74%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "10.64%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "7.99%" >}}
6. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "6.21%" >}}
7. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "3.55%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "3.37%" >}}
9. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "1.42%" >}}
10. {{< a "https://www.julephosting.de/" "Julep Hosting" >}} {{< span "weak" "1.41%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.58% of new episodes in August, growing 2.63% from last month.

Of these, 7.32% had one other tracker, 0.58% had 2 other trackers, 0.09% had 3 other trackers, and 0.05% had 4 other trackers.

2.96% also included Podtrac, 2.23% also included Adswizz, 2.02% also included Chartable, 0.86% also included Feedpress, 0.36% also included Podsights, 0.32% also included Podcorn, 0.08% also included Podscribe, 0.06% also included OP3, 0.02% also included Podder, 0.02% also included Spotify, 0.02% also included Claritas, <0.01% also included Voxalyze, and <0.01% also included Magellan AI.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "42.41%" >}}
2. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "7.79%" >}}
3. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.83%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.21%" >}}
5. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.87%" >}}
6. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.86%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.71%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.45%" >}}
9. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.18%" >}}
10. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.10%" >}}
---

### 6. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 1.23% of new episodes in August, growing 4.15% from last month.

Of these, 10.60% had one other tracker, 3.31% had 2 other trackers, 1.58% had 4 other trackers, 1.43% had 5 other trackers, 1.23% had 3 other trackers, 0.08% had 6 other trackers, 0.06% had 8 other trackers, and 0.02% had 7 other trackers.

11.39% also included Podtrac, 9.86% also included Chartable, 5.13% also included Podsights, 3.03% also included Gumshoe, 2.86% also included OP3, 0.80% also included Podscribe, 0.72% also included Podder, 0.41% also included Podroll, 0.41% also included Blubrry, 0.29% also included Adswizz, 0.21% also included Voxalyze, 0.19% also included Podkite, 0.05% also included Zencastr, 0.05% also included AdBarker, 0.04% also included Magellan AI, and <0.01% also included Spotify.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "40.43%" >}}
2. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "12.83%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.49%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "9.19%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "6.05%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.92%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.65%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.47%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.66%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.41%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.53% of new episodes in August, shrinking 3.26% from last month.

Of these, 0.37% had one other tracker.

0.37% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "43.44%" >}}
2. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "35.62%" >}}
3. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "9.02%" >}}
4. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "5.93%" >}}
5. {{< a "https://soundcast.fm/" "SoundCast" >}} {{< span "weak" "4.20%" >}}
6. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "1.03%" >}}
7. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "0.60%" >}}
---

### 8. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.36% of new episodes in August, growing 30.76% from last month.

Of these, 19.14% had 3 other trackers, 18.33% had one other tracker, 18.21% had 2 other trackers, 16.67% had 4 other trackers, 14.95% had 5 other trackers, 4.71% had 6 other trackers, 1.40% had 7 other trackers, and 0.02% had 8 other trackers.

72.12% also included Podsights, 68.69% also included Chartable, 46.78% also included Podtrac, 24.52% also included ArtsAI, 17.52% also included Claritas, 15.22% also included Veritonic, 13.95% also included Magellan AI, 8.92% also included Adswizz, 6.70% also included Podroll, 3.66% also included Audiotakes, 3.41% also included Spotify, 2.76% also included Podcorn, 2.76% also included Gumshoe, 2.32% also included Podder, 2.10% also included OP3, 0.37% also included Blubrry, 0.03% also included Podkite, and 0.02% also included Voxalyze.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "44.72%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.21%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.74%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.03%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.53%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.23%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.12%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.67%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.34%" >}}
10. {{< a "https://twit.tv/" "TWiT" >}} {{< span "weak" "0.85%" >}}
---

### 9. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.17% of new episodes in August, shrinking 5.82% from last month.

Of these, 13.06% had one other tracker, 1.41% had 2 other trackers, and 0.17% had 3 other trackers.

7.85% also included Blubrry, 5.41% also included Podtrac, 2.55% also included Chartable, 0.41% also included Podsights, 0.14% also included OP3, and 0.03% also included Adswizz.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "49.36%" >}}
2. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "9.89%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.68%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.82%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.93%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.10%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.14%" >}}
8. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.34%" >}}
9. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.10%" >}}
10. {{< a "https://www.subsplash.com/" "Subsplash" >}} {{< span "weak" "1.03%" >}}
---

### 10. [Podroll](https://podroll.fm/)

Podroll was found on 0.16% of new episodes in August, growing 13.06% from last month.

Of these, 31.54% had 2 other trackers, 19.80% had one other tracker, 17.50% had 4 other trackers, 13.36% had 3 other trackers, 1.35% had 5 other trackers, 0.64% had 7 other trackers, 0.41% had 8 other trackers, and 0.38% had 6 other trackers.

60.41% also included Chartable, 45.58% also included Podtrac, 43.62% also included Podsights, 15.09% also included Podscribe, 13.77% also included Magellan AI, 10.69% also included Podder, 10.24% also included Adswizz, 3.20% also included Podcorn, 2.30% also included Gumshoe, 1.84% also included Voxalyze, 1.24% also included ArtsAI, 0.94% also included Claritas, 0.60% also included OP3, and 0.26% also included Zencastr.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "49.42%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "22.43%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "14.15%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.88%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.51%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.75%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.53%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.45%" >}}
9. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "0.26%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.23%" >}}
---

### 11. [Podder](https://www.podderapp.com/)

Podder was found on 0.15% of new episodes in August, growing 7.11% from last month.

Of these, 34.52% had 3 other trackers, 22.36% had 2 other trackers, 13.72% had 4 other trackers, 12.24% had one other tracker, 3.49% had 5 other trackers, 0.70% had 6 other trackers, 0.46% had 8 other trackers, and 0.27% had 7 other trackers.

69.66% also included Chartable, 68.50% also included Podtrac, 62.81% also included Podsights, 11.00% also included Podroll, 7.13% also included Magellan AI, 5.73% also included Podcorn, 5.39% also included Podscribe, 3.56% also included OP3, 2.21% also included Gumshoe, 1.94% also included ArtsAI, 1.55% also included Adswizz, 1.16% also included Podkite, 0.85% also included Claritas, 0.50% also included Voxalyze, 0.39% also included Veritonic, 0.19% also included Blubrry, and 0.04% also included Spotify.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "71.21%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "9.49%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.87%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.84%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.29%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.94%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.52%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.85%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.58%" >}}
10. {{< a "https://www.thepodops.com/" "PodOps" >}} {{< span "weak" "0.35%" >}}
---

### 12. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.12% of new episodes in August, growing 13.54% from last month.

Of these, 32.96% had 5 other trackers, 21.67% had 3 other trackers, 19.34% had 2 other trackers, 11.63% had 6 other trackers, 8.00% had 4 other trackers, 4.07% had 7 other trackers, and 1.31% had one other tracker.

83.42% also included Chartable, 77.56% also included Podsights, 71.16% also included Podscribe, 70.43% also included Podtrac, 32.72% also included Veritonic, 24.14% also included Claritas, 23.61% also included Adswizz, 6.06% also included Magellan AI, 5.53% also included Spotify, 2.42% also included Podder, 1.60% also included Podroll, and 1.45% also included Audiotakes.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.39%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "27.58%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "14.40%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "11.88%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "9.94%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.89%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.89%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.50%" >}}
9. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.24%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.19%" >}}
---

### 13. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.11% of new episodes in August, growing 40.38% from last month.

Of these, 28.41% had one other tracker, 17.06% had 4 other trackers, 14.09% had 5 other trackers, 9.28% had 2 other trackers, 3.75% had 3 other trackers, 0.95% had 6 other trackers, 0.67% had 8 other trackers, and 0.22% had 7 other trackers.

59.34% also included Podtrac, 34.62% also included Podsights, 32.89% also included Podcorn, 32.66% also included Gumshoe, 28.52% also included Chartable, 7.05% also included Podscribe, 5.15% also included Podder, 2.96% also included Adswizz, 2.46% also included Voxalyze, 1.62% also included Spotify, 0.89% also included Podroll, 0.84% also included Blubrry, 0.34% also included Podkite, and 0.22% also included Feedpress.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "45.30%" >}}
2. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "14.93%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.97%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.30%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.19%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.91%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.91%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.18%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.79%" >}}
10. {{< a "https://letscast.fm/" "LetsCast.fm" >}} {{< span "weak" "1.68%" >}}
---

### 14. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.09% of new episodes in August, growing 27.88% from last month.

Of these, 42.88% had 4 other trackers, 15.39% had one other tracker, 15.27% had 2 other trackers, 13.00% had 3 other trackers, 5.76% had 5 other trackers, 3.69% had 6 other trackers, and 2.78% had 7 other trackers.

79.17% also included Chartable, 75.16% also included Podsights, 54.01% also included Podscribe, 51.68% also included Podtrac, 23.67% also included Podroll, 11.90% also included Podder, 8.15% also included Veritonic, 8.09% also included ArtsAI, 6.34% also included Claritas, 4.59% also included Adswizz, 2.39% also included Spotify, 0.78% also included Audiotakes, 0.58% also included Podcorn, 0.26% also included Voxalyze, and 0.06% also included Blubrry.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "68.37%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "11.77%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.02%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.27%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.95%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.72%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "2.01%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.58%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.19%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.06%" >}}
---

### 15. [Firstory](https://firstory.me/)

Firstory was found on 0.09% of new episodes in August, growing 5.67% from last month.

Of these, 67.87% had one other tracker, and 0.26% had 2 other trackers.

68.14% also included Chartable, and 0.26% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.74%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.26%" >}}
---

### 16. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.08% of new episodes in August, growing 12.78% from last month.

Of these, 20.82% had 4 other trackers, 18.80% had 3 other trackers, 17.72% had 5 other trackers, 16.16% had 6 other trackers, 13.36% had 2 other trackers, 6.29% had 7 other trackers, and 5.21% had one other tracker.

81.66% also included Podsights, 81.51% also included Podscribe, 74.36% also included Chartable, 56.72% also included Podtrac, 38.69% also included ArtsAI, 31.47% also included Adswizz, 19.97% also included Veritonic, 7.61% also included Magellan AI, 5.28% also included Spotify, 1.94% also included Podroll, 1.71% also included Podder, and 0.31% also included Blubrry.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "31.78%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.79%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "17.79%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "11.66%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "11.34%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.29%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "2.41%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.54%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.31%" >}}
10. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "0.08%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.07% of new episodes in August, growing 19.78% from last month.

Of these, 24.18% had 4 other trackers, 22.91% had 2 other trackers, 21.31% had 5 other trackers, 12.45% had one other tracker, 6.23% had 3 other trackers, 1.36% had 6 other trackers, 0.96% had 8 other trackers, and 0.32% had 7 other trackers.

75.10% also included Podsights, 58.98% also included Podtrac, 49.56% also included Podcorn, 46.61% also included OP3, 41.50% also included Chartable, 13.17% also included Podscribe, 4.87% also included Podroll, 4.55% also included Podder, 0.96% also included Voxalyze, 0.88% also included Spotify, 0.88% also included Adswizz, 0.72% also included Veritonic, and 0.48% also included Podkite.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "47.17%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "19.95%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "13.09%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "12.37%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.31%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.20%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.88%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.56%" >}}
9. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.24%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.08%" >}}
---

### 18. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.07% of new episodes in August, growing 16.42% from last month.

Of these, 44.92% had 5 other trackers, 20.40% had 6 other trackers, 15.18% had 4 other trackers, 7.19% had 3 other trackers, 4.58% had 2 other trackers, 3.23% had 7 other trackers, and 2.16% had one other tracker.

85.62% also included Podsights, 82.75% also included Podtrac, 81.85% also included Podscribe, 79.34% also included Chartable, 60.65% also included ArtsAI, 27.85% also included Adswizz, 23.09% also included Claritas, 11.32% also included Magellan AI, 6.11% also included Spotify, 2.96% also included Audiotakes, 0.90% also included Podder, and 0.81% also included Gumshoe.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "51.66%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "23.90%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "11.95%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.03%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.58%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.52%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.36%" >}}
---

### 19. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.04% of new episodes in August, growing 807.37% from last month.

Of these, 67.04% had one other tracker, 15.08% had 2 other trackers, 11.17% had 3 other trackers, 6.01% had 4 other trackers, and 0.70% had 5 other trackers.

65.78% also included Adswizz, 32.68% also included Podsights, 30.59% also included Podscribe, 12.85% also included Chartable, 5.73% also included Podtrac, 4.61% also included Veritonic, 4.19% also included ArtsAI, 1.68% also included Magellan AI, and 0.14% also included Spotify.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "14.94%" >}}
2. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "13.27%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.05%" >}}
4. {{< a "https://kostenlos-hosten.de/" "Podcastbude" >}} {{< span "weak" "3.35%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.98%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.70%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.14%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.14%" >}}
---

### 20. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.03% of new episodes in August, growing 330.50% from last month.

Of these, 46.35% had one other tracker, 15.45% had 2 other trackers, 11.37% had 5 other trackers, 10.30% had 6 other trackers, 5.15% had 3 other trackers, 1.93% had 7 other trackers, and 1.29% had 4 other trackers.

52.15% also included Chartable, 43.78% also included Podscribe, 24.46% also included ArtsAI, 24.03% also included Podtrac, 23.39% also included Podsights, 15.02% also included Adswizz, 14.59% also included Claritas, 14.59% also included Veritonic, 7.94% also included Magellan AI, 6.22% also included OP3, 2.36% also included Gumshoe, 0.86% also included Blubrry, 0.21% also included Podcorn, 0.21% also included Audiotakes, and 0.21% also included Podder.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "46.14%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "17.81%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "11.80%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.01%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.65%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.36%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.93%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.50%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "1.50%" >}}
10. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.64%" >}}
---

### 21. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on 0.02% of new episodes in August, growing 39.29% from last month.

Of these, 24.34% had 3 other trackers, 19.35% had one other tracker, 10.56% had 4 other trackers, 10.26% had 2 other trackers, and 3.52% had 8 other trackers.

58.65% also included Chartable, 39.88% also included Podtrac, 35.48% also included Podsights, 14.37% also included Podroll, 12.90% also included OP3, 12.90% also included Podcorn, 3.81% also included Podder, 3.52% also included Gumshoe, 1.17% also included Magellan AI, 0.29% also included Podscribe, and 0.29% also included Blubrry.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.72%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "19.65%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "15.25%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "10.56%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "10.26%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "5.57%" >}}
7. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "1.76%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.47%" >}}
9. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "1.17%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.59%" >}}
---

### 22. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in August, growing 25.21% from last month.

Of these, 24.40% had one other tracker, 3.35% had 4 other trackers, 2.39% had 2 other trackers, and 0.48% had 3 other trackers.

16.27% also included Chartable, 10.05% also included Podtrac, 9.09% also included Podsights, 5.26% also included Podcorn, and 3.35% also included Podroll.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "100.00%" >}}
---

### 23. [Glystn](https://glystn.com/)

Glystn was found on 0.01% of new episodes in August, growing 12.45% from last month.

Of these, 95.97% had 2 other trackers, and 4.03% had one other tracker.

100.00% also included Chartable, and 95.97% also included Podtrac.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "95.97%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.03%" >}}
---

### 24. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in August, shrinking 5.86% from last month.

Of these, 25.00% had one other tracker, 21.67% had 5 other trackers, 4.17% had 2 other trackers, 3.33% had 7 other trackers, and 1.67% had 6 other trackers.

38.33% also included Chartable, 36.67% also included Podtrac, 32.50% also included Podcorn, 30.83% also included Podsights, 25.00% also included Podder, 5.00% also included OP3, 5.00% also included Gumshoe, and 1.67% also included Podscribe.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "28.33%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "25.00%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "10.83%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "10.00%" >}}
5. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "7.50%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.50%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.17%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.33%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.83%" >}}
---

### 25. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in August, growing 1.65% from last month.

Of these, 41.28% had one other tracker, and 32.11% had 2 other trackers.

68.81% also included Chartable, 27.52% also included Podtrac, and 9.17% also included Podcorn.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "35.78%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "29.36%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "15.60%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "8.26%" >}}
5. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "4.59%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.75%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.83%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.83%" >}}
---

### 26. [Zippycast](https://zippycast.io/)

Zippycast was found on <0.01% of new episodes in August, shrinking 66.36% from last month.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "53.06%" >}}
2. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "40.82%" >}}
3. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "6.12%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
