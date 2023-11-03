---
title: "Top Podcast Tracking Services by Episode Share (September 2023)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-september-2023"
images:
- trackers-2023-09.png
date: 2023-10-01T11:34:00-05:00
lastmod: 2023-10-01T11:34:00-05:00
draft: false
rssrevision: 2023-09
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.8 million in September 2023), 
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

_A special note for September: all share numbers appear lower since we improved our Spotify for Podcasters (formerly Anchor) observation system this month to better reflect reality. More new episodes on S4P (typically without prefixes) leads to lower share overall for all prefixes._

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Chartable	Adswizz	Podsights	Blubrry	Podcorn	Médiamétrie	Podscribe	Feedpress	Podder	Podroll	ArtsAI	Claritas	OP3	Gumshoe	Veritonic	Spotify	Audiotakes	Voxalyze	Zencastr	Glystn	Podkite	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.00	1.16	2.07	2.09	0.42		0.32																	1.61
Oct 2021	4.05	4.09	1.01	1.20	2.11	2.13	0.54		0.34																	1.61
Nov 2021	4.07	4.30	1.02	1.25	2.01	2.14	0.57		0.32																	0.59
Dec 2021	4.06	4.42	1.24	1.19	1.57	2.27	0.59		0.19																	
Jan 2022	4.11	4.45	1.41	1.21	1.56	2.31	0.63		0.16																	
Feb 2022	4.15	4.48	1.44	1.25	1.53	2.38	0.58		0.17																	
Mar 2022	4.37	4.72	1.51	1.34	1.56	2.40	0.53		0.17																	
Apr 2022	4.44	4.71	1.49	1.33	1.55	2.33	0.51		0.16																	
May 2022	4.49	4.87	1.58	1.41	1.48	2.26	0.56		0.17																	
Jun 2022	4.75	5.10	1.77	1.54	1.50	2.06	0.62		0.21														0.02			
Jul 2022	4.70	5.10	1.89	1.50	1.50	2.16	0.54		0.25														0.02			
Aug 2022	4.83	5.26	2.08	1.73	1.51	2.45	0.41		0.20			0.10											0.01			
Sep 2022	7.53	5.40	2.26	1.74	1.49	2.45	0.52	0.02	0.21			0.09	0.01									0.01	0.02	0.02		
Oct 2022	8.24	5.48	2.35	1.81	1.61	2.51	0.50	0.07	0.18			0.10	0.02	0.03						0.01		0.01	0.02	0.04		
Nov 2022	8.11	5.62	2.37	2.03	1.62	2.43	0.50	0.15	0.18	0.01		0.10	0.03	0.04						0.01		0.01	0.02	0.05		
Dec 2022	8.01	5.54	2.32	1.81	1.61	2.05	0.49	0.03	0.18	0.04		0.05	0.02	0.05						0.01	0.01	0.01	0.02	0.05		
Jan 2023	7.85	5.56	2.35	1.88	1.61	2.15	0.54	0.20	0.18	0.11		0.10	0.06	0.07						0.01	0.01	0.01	0.02	0.06		
Feb 2023	7.58	5.51	2.29	1.92	1.62	2.30	0.49	0.21	0.19	0.11		0.10	0.07	0.07						0.01	0.01	0.01	0.02	0.06	0.03	
Mar 2023	7.79	5.53	2.25	2.03	1.53	2.22	0.45	0.21	0.18	0.11	0.04	0.11	0.07	0.08		0.04				0.01	0.01	0.01	0.02	0.06		
Apr 2023	7.66	5.43	2.26	2.00	1.67	2.20	0.45	0.21	0.17	0.15	0.06	0.11	0.07	0.09	0.08	0.05				0.01	0.01	0.01	0.01			
May 2023	7.58	5.59	2.27	2.04	1.67	2.28	0.45	0.24	0.19	0.15	0.09	0.11	0.08	0.09	0.07	0.05			0.01	0.01	0.01	0.01	0.01			
Jun 2023	8.22	5.83	2.39	2.23	1.64	1.86	0.51	0.26	0.19	0.15	0.10	0.12	0.07	0.09	0.08	0.05			0.01	0.01	0.01	0.01	0.01			
Jul 2023	8.60	5.95	2.38	2.52	1.53	1.17	0.55	0.27	0.18	0.14	0.14	0.11	0.07	0.08	0.06	0.06	0.01		0.01	0.01	0.01	0.01	0.01			
Aug 2023	9.19	6.43	2.72	2.76	1.58	1.23	0.53	0.36	0.17	0.15	0.16	0.12	0.08	0.11	0.07	0.07	0.03	0.04	0.02	0.01	0.01	0.01				
Sep 2023	8.46	5.77	2.49	2.47	1.39	1.10	0.58	0.37	0.16	0.15	0.13	0.12	0.10	0.10	0.07	0.06	0.05	0.05	0.02	0.01	0.01	0.01				
{{< /graph >}}

---

### Overall

At least one tracker was found on 16.92% of new episodes in September, shrinking 8.72% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "22.36%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "15.20%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.34%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.91%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.47%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.47%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.65%" >}}
8. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.39%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.37%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.99%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of September 2023.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 8.46% of new episodes in September, shrinking 7.91% from last month.

Of these, 25.26% had one other tracker, 11.30% had 2 other trackers, 2.24% had 3 other trackers, 0.90% had 4 other trackers, 0.77% had 5 other trackers, 0.27% had 6 other trackers, 0.07% had 7 other trackers, 0.01% had 8 other trackers, and <0.01% had 9 other trackers.

30.36% also included Chartable, 17.22% also included Podsights, 5.71% also included Adswizz, 2.22% also included Podscribe, 1.45% also included Podcorn, 1.18% also included Podder, 0.98% also included ArtsAI, 0.85% also included Magellan AI, 0.83% also included Podroll, 0.68% also included OP3, 0.66% also included Claritas, 0.59% also included Veritonic, 0.49% also included Blubrry, 0.47% also included Gumshoe, 0.17% also included Spotify, 0.10% also included Glystn, 0.09% also included Voxalyze, 0.05% also included Feedpress, 0.03% also included Audiotakes, 0.03% also included Médiamétrie, 0.02% also included Zencastr, 0.02% also included AdBarker, 0.01% also included Podkite, and <0.01% also included Firstory.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "43.73%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "18.69%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "12.87%" >}}
4. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.67%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.53%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.29%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.87%" >}}
8. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "1.75%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.54%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.12%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 6.65% of new episodes in September, shrinking 10.42% from last month.

Of these, 44.62% also included Podtrac, 6.65% also included Adswizz, 4.93% also included Podscribe, 2.11% also included Podcorn, 1.89% also included Podder, 1.74% also included ArtsAI, 1.71% also included Magellan AI, 1.57% also included Podroll, 1.43% also included Claritas, 0.85% also included Gumshoe, 0.84% also included Firstory, 0.84% also included Veritonic, 0.81% also included OP3, 0.37% also included Blubrry, 0.27% also included Audiotakes, 0.19% also included Voxalyze, 0.13% also included Glystn, 0.06% also included Zencastr, 0.06% also included AdBarker, 0.05% also included Feedpress, and 0.02% also included Podkite.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.74%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "23.71%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.03%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.92%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.01%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.90%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.52%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.41%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.21%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "1.97%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.77% of new episodes in September, shrinking 10.25% from last month.

Of these, 36.36% had one other tracker, 17.51% had 2 other trackers, 3.68% had 3 other trackers, 1.40% had 4 other trackers, 1.04% had 5 other trackers, 0.33% had 6 other trackers, 0.08% had 7 other trackers, 0.01% had 8 other trackers, and <0.01% had 9 other trackers.

44.52% also included Podtrac, 27.95% also included Podsights, 4.97% also included Adswizz, 4.23% also included Podscribe, 1.89% also included Podcorn, 1.85% also included Podder, 1.68% also included ArtsAI, 1.62% also included Magellan AI, 1.57% also included Podroll, 1.31% also included Claritas, 0.97% also included Firstory, 0.79% also included Veritonic, 0.54% also included Spotify, 0.51% also included Gumshoe, 0.50% also included OP3, 0.34% also included Blubrry, 0.21% also included Voxalyze, 0.15% also included Glystn, 0.11% also included Audiotakes, 0.07% also included AdBarker, 0.06% also included Zencastr, 0.06% also included Feedpress, and 0.02% also included Podkite.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "32.77%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "21.17%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.51%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.11%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.51%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.35%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.55%" >}}
8. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.55%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.27%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.23%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.49% of new episodes in September, shrinking 8.40% from last month.

Of these, 28.00% had one other tracker, 2.48% had 2 other trackers, 2.41% had 3 other trackers, 0.47% had 6 other trackers, 0.34% had 5 other trackers, 0.31% had 4 other trackers, and 0.21% had 7 other trackers.

19.44% also included Podtrac, 11.52% also included Chartable, 9.28% also included Podsights, 1.25% also included Podscribe, 1.11% also included Audiotakes, 1.07% also included Blubrry, 0.97% also included ArtsAI, 0.80% also included Claritas, 0.65% also included Podroll, 0.60% also included Veritonic, 0.18% also included Spotify, 0.18% also included Magellan AI, 0.16% also included OP3, 0.12% also included Podcorn, 0.08% also included Podder, and 0.02% also included Gumshoe.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "27.40%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "16.27%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.65%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "10.17%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "9.34%" >}}
6. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.46%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "3.70%" >}}
8. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "3.64%" >}}
9. {{< a "https://www.mediastre.am/" "mediastream" >}} {{< span "weak" "1.43%" >}}
10. {{< a "https://www.julephosting.de/" "Julep Hosting" >}} {{< span "weak" "1.39%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.47% of new episodes in September, shrinking 10.53% from last month.

Of these, 38.68% had one other tracker, 35.31% had 2 other trackers, 8.15% had 3 other trackers, 4.00% had 4 other trackers, 2.93% had 5 other trackers, 0.79% had 6 other trackers, 0.20% had 7 other trackers, 0.03% had 8 other trackers, and 0.01% had 9 other trackers.

65.25% also included Chartable, 58.94% also included Podtrac, 10.74% also included Podscribe, 9.34% also included Adswizz, 4.10% also included Magellan AI, 3.97% also included Podder, 3.76% also included ArtsAI, 3.03% also included Claritas, 2.40% also included Podroll, 2.20% also included Podcorn, 1.98% also included Veritonic, 1.96% also included Gumshoe, 1.36% also included OP3, 0.69% also included Audiotakes, 0.50% also included Spotify, 0.28% also included Voxalyze, 0.21% also included Blubrry, 0.04% also included Zencastr, 0.04% also included Feedpress, and 0.02% also included Podkite.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "49.60%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "34.04%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.42%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.86%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.87%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.70%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.31%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.93%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.85%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.80%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.39% of new episodes in September, shrinking 11.71% from last month.

Of these, 6.44% had one other tracker, 0.63% had 2 other trackers, 0.09% had 3 other trackers, and 0.04% had 4 other trackers.

2.97% also included Podtrac, 1.92% also included Adswizz, 1.42% also included Chartable, 0.90% also included Feedpress, 0.37% also included Podsights, 0.31% also included Podcorn, 0.11% also included Podscribe, 0.07% also included OP3, 0.02% also included Spotify, 0.01% also included Voxalyze, 0.01% also included Claritas, 0.01% also included Magellan AI, and <0.01% also included Podder.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "42.22%" >}}
2. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "7.51%" >}}
3. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.42%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.32%" >}}
5. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.77%" >}}
6. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.59%" >}}
7. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.21%" >}}
8. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.18%" >}}
9. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.99%" >}}
10. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.78%" >}}
---

### 6. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 1.10% of new episodes in September, shrinking 10.58% from last month.

Of these, 10.62% had one other tracker, 3.46% had 2 other trackers, 1.57% had 5 other trackers, 1.35% had 4 other trackers, 1.19% had 3 other trackers, 0.11% had 6 other trackers, 0.06% had 8 other trackers, 0.01% had 9 other trackers, and 0.01% had 7 other trackers.

11.23% also included Podtrac, 9.95% also included Chartable, 4.95% also included Podsights, 3.08% also included Gumshoe, 2.90% also included OP3, 1.18% also included Podscribe, 0.65% also included Podder, 0.48% also included Podroll, 0.40% also included Blubrry, 0.28% also included Adswizz, 0.27% also included Voxalyze, 0.10% also included Magellan AI, 0.07% also included Podkite, 0.07% also included AdBarker, 0.06% also included Zencastr, and 0.01% also included Spotify.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "40.53%" >}}
2. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "12.50%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.71%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "9.10%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "5.81%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.95%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.78%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.50%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.99%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.45%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.58% of new episodes in September, growing 9.71% from last month.

Of these, 0.45% had one other tracker.

0.45% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "37.93%" >}}
2. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "37.18%" >}}
3. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "8.58%" >}}
4. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "7.46%" >}}
5. {{< a "https://soundcast.fm/" "SoundCast" >}} {{< span "weak" "5.33%" >}}
6. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "2.00%" >}}
7. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "1.04%" >}}
---

### 8. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.37% of new episodes in September, growing 2.17% from last month.

Of these, 22.78% had 3 other trackers, 17.41% had 2 other trackers, 16.10% had 5 other trackers, 14.70% had 4 other trackers, 14.46% had one other tracker, 6.07% had 6 other trackers, 1.67% had 7 other trackers, and 0.04% had 9 other trackers.

72.71% also included Podsights, 66.89% also included Chartable, 51.47% also included Podtrac, 23.31% also included ArtsAI, 21.13% also included Claritas, 17.71% also included Magellan AI, 13.58% also included Veritonic, 8.54% also included Adswizz, 5.76% also included Podroll, 5.37% also included Spotify, 4.69% also included Audiotakes, 3.88% also included Podder, 3.59% also included Gumshoe, 3.56% also included Podcorn, 2.69% also included OP3, 0.43% also included Blubrry, 0.04% also included Podkite, and 0.04% also included Voxalyze.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "47.76%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "14.13%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "9.18%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.14%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.95%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.14%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.30%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.01%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.84%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.94%" >}}
---

### 9. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.16% of new episodes in September, shrinking 6.34% from last month.

Of these, 11.41% had one other tracker, 0.80% had 2 other trackers, and 0.07% had 3 other trackers.

7.73% also included Blubrry, 2.61% also included Podtrac, 2.01% also included Chartable, 0.67% also included Podsights, 0.13% also included OP3, and 0.07% also included Podder.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "48.53%" >}}
2. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "8.77%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.63%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.33%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.35%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.55%" >}}
7. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "2.21%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.84%" >}}
9. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.37%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.94%" >}}
---

### 10. [Podder](https://www.podderapp.com/)

Podder was found on 0.15% of new episodes in September, shrinking 0.05% from last month.

Of these, 26.98% had 3 other trackers, 20.07% had 2 other trackers, 17.32% had 4 other trackers, 11.53% had one other tracker, 7.34% had 5 other trackers, 1.87% had 6 other trackers, 0.53% had 7 other trackers, 0.42% had 8 other trackers, and 0.11% had 9 other trackers.

69.17% also included Chartable, 65.01% also included Podtrac, 63.74% also included Podsights, 19.54% also included Magellan AI, 11.04% also included Podroll, 9.21% also included Podscribe, 5.57% also included Claritas, 4.62% also included Podcorn, 3.42% also included OP3, 2.19% also included Gumshoe, 1.59% also included ArtsAI, 1.31% also included Adswizz, 0.60% also included Voxalyze, 0.56% also included Veritonic, 0.11% also included Podkite, 0.07% also included Spotify, 0.07% also included Feedpress, and 0.04% also included Blubrry.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "72.59%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "8.01%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.23%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.77%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.60%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.32%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.98%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.67%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.60%" >}}
10. {{< a "https://www.thepodops.com/" "PodOps" >}} {{< span "weak" "0.14%" >}}
---

### 11. [Podroll](https://podroll.fm/)

Podroll was found on 0.13% of new episodes in September, shrinking 19.31% from last month.

Of these, 28.48% had 2 other trackers, 21.82% had 3 other trackers, 18.29% had 4 other trackers, 13.84% had one other tracker, 3.14% had 5 other trackers, 1.44% had 6 other trackers, 1.02% had 7 other trackers, 0.51% had 8 other trackers, and 0.13% had 9 other trackers.

70.63% also included Chartable, 54.92% also included Podtrac, 46.26% also included Podsights, 16.43% also included Podscribe, 14.98% also included Magellan AI, 13.29% also included Podder, 12.56% also included Adswizz, 4.12% also included Podcorn, 3.82% also included Claritas, 3.57% also included Voxalyze, 2.89% also included Gumshoe, 1.36% also included ArtsAI, 1.02% also included OP3, and 0.30% also included Zencastr.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "51.70%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.48%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "11.46%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.91%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.74%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.27%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.15%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.10%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.55%" >}}
10. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "0.30%" >}}
---

### 12. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.13% of new episodes in September, growing 35.73% from last month.

Of these, 34.04% had 4 other trackers, 17.69% had 3 other trackers, 15.83% had 5 other trackers, 11.45% had 2 other trackers, 10.75% had one other tracker, 6.07% had 6 other trackers, and 2.65% had 7 other trackers.

80.96% also included Podsights, 74.63% also included Chartable, 57.29% also included Podtrac, 51.60% also included Podscribe, 24.02% also included Podder, 22.03% also included Claritas, 15.31% also included Podroll, 11.45% also included ArtsAI, 9.41% also included Veritonic, 3.69% also included Spotify, 3.60% also included Adswizz, 1.60% also included Audiotakes, 0.87% also included Podcorn, 0.26% also included Gumshoe, 0.17% also included Voxalyze, and 0.09% also included Blubrry.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "68.60%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.85%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "7.37%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.59%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.73%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.86%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.08%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.35%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.30%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.17%" >}}
---

### 13. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.12% of new episodes in September, shrinking 3.58% from last month.

Of these, 29.83% had 5 other trackers, 22.32% had 3 other trackers, 16.83% had 2 other trackers, 12.31% had 4 other trackers, 11.44% had 6 other trackers, 4.76% had 7 other trackers, and 1.69% had one other tracker.

81.43% also included Chartable, 78.18% also included Podsights, 71.68% also included Podscribe, 69.67% also included Podtrac, 29.55% also included Veritonic, 25.53% also included Claritas, 20.31% also included Adswizz, 12.08% also included Magellan AI, 7.23% also included Spotify, 3.43% also included Audiotakes, 2.06% also included Podder, and 1.46% also included Podroll.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.58%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "25.21%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "12.90%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.75%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "8.83%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.80%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.28%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.14%" >}}
9. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.18%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.18%" >}}
---

### 14. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.10% of new episodes in September, growing 32.14% from last month.

Of these, 18.78% had 4 other trackers, 18.41% had 5 other trackers, 18.08% had 3 other trackers, 15.89% had 2 other trackers, 15.09% had 6 other trackers, 5.78% had one other tracker, and 5.51% had 7 other trackers.

75.98% also included Podscribe, 74.21% also included Chartable, 73.78% also included Podsights, 54.68% also included Podtrac, 29.86% also included ArtsAI, 27.18% also included Magellan AI, 19.64% also included Adswizz, 14.87% also included Veritonic, 8.45% also included Podder, 4.82% also included Podroll, 4.44% also included Spotify, and 0.16% also included Blubrry.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "42.43%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.28%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "14.18%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.63%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "7.54%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.17%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.34%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.21%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.16%" >}}
10. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "0.05%" >}}
---

### 15. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.10% of new episodes in September, shrinking 6.72% from last month.

Of these, 25.91% had one other tracker, 16.09% had 5 other trackers, 14.29% had 4 other trackers, 12.33% had 2 other trackers, 2.84% had 3 other trackers, 1.20% had 6 other trackers, 0.65% had 8 other trackers, 0.16% had 9 other trackers, and 0.11% had 7 other trackers.

57.77% also included Podtrac, 33.82% also included Podsights, 31.91% also included Podcorn, 31.81% also included Gumshoe, 28.91% also included Chartable, 9.87% also included Podscribe, 5.29% also included Podder, 4.09% also included Adswizz, 3.06% also included Voxalyze, 2.13% also included Spotify, 1.31% also included Podroll, 1.04% also included Blubrry, 0.22% also included Feedpress, and 0.16% also included Podkite.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "43.92%" >}}
2. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "13.80%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.04%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.87%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.82%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.89%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.56%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.07%" >}}
9. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "2.02%" >}}
10. {{< a "https://letscast.fm/" "LetsCast.fm" >}} {{< span "weak" "1.69%" >}}
---

### 16. [Firstory](https://firstory.me/)

Firstory was found on 0.08% of new episodes in September, shrinking 12.24% from last month.

Of these, 70.24% had one other tracker, and 0.27% had 2 other trackers.

70.51% also included Chartable, and 0.27% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.59%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.41%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.07% of new episodes in September, shrinking 9.51% from last month.

Of these, 25.04% had 5 other trackers, 22.31% had 2 other trackers, 20.55% had 4 other trackers, 10.75% had one other tracker, 7.95% had 3 other trackers, 1.77% had 6 other trackers, 0.96% had 8 other trackers, 0.24% had 9 other trackers, and 0.16% had 7 other trackers.

71.43% also included Podsights, 58.43% also included Podtrac, 49.92% also included Podcorn, 46.79% also included OP3, 43.18% also included Chartable, 19.34% also included Podscribe, 5.46% also included Podroll, 5.38% also included Spotify, 4.98% also included Podder, 1.61% also included Voxalyze, 0.56% also included Adswizz, 0.48% also included Magellan AI, 0.40% also included Veritonic, and 0.24% also included Podkite.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "48.39%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "20.55%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "17.34%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.74%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.93%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.20%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.72%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.72%" >}}
9. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.40%" >}}
---

### 18. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.06% of new episodes in September, shrinking 13.01% from last month.

Of these, 41.82% had 5 other trackers, 25.38% had 6 other trackers, 12.31% had 4 other trackers, 6.58% had 3 other trackers, 5.73% had 7 other trackers, 4.23% had 2 other trackers, and 2.82% had one other tracker.

85.90% also included Podtrac, 85.81% also included Podscribe, 84.49% also included Podsights, 79.32% also included Chartable, 60.71% also included ArtsAI, 26.13% also included Claritas, 25.75% also included Adswizz, 20.39% also included Magellan AI, 7.33% also included Spotify, 3.95% also included Audiotakes, 1.50% also included Podder, and 0.47% also included Gumshoe.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "55.08%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "23.31%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "11.28%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.17%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.54%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.44%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.09%" >}}
---

### 19. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.05% of new episodes in September, growing 90.38% from last month.

Of these, 42.46% had one other tracker, 23.08% had 2 other trackers, 8.62% had 3 other trackers, 7.69% had 5 other trackers, 5.64% had 6 other trackers, 2.36% had 7 other trackers, and 2.15% had 4 other trackers.

58.46% also included Chartable, 37.03% also included Podscribe, 27.69% also included Podtrac, 23.49% also included Podsights, 16.21% also included ArtsAI, 8.72% also included Magellan AI, 8.51% also included Adswizz, 8.51% also included Claritas, 8.00% also included Veritonic, 6.87% also included Gumshoe, 4.00% also included OP3, 3.49% also included Audiotakes, 0.51% also included Blubrry, 0.21% also included Podcorn, and 0.21% also included Podder.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "46.26%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "11.69%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.85%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "8.31%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.10%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.36%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.82%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.33%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.82%" >}}
10. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "0.72%" >}}
---

### 20. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.05% of new episodes in September, growing 8.66% from last month.

Of these, 60.23% had one other tracker, 17.78% had 2 other trackers, 10.99% had 3 other trackers, 6.67% had 4 other trackers, and 3.74% had 5 other trackers.

59.30% also included Adswizz, 36.84% also included Podscribe, 36.49% also included Podsights, 13.57% also included Chartable, 8.77% also included ArtsAI, 5.96% also included Podtrac, 4.91% also included Veritonic, 4.33% also included Magellan AI, and 3.98% also included Spotify.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "18.25%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "14.74%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.74%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.04%" >}}
5. {{< a "https://kostenlos-hosten.de/" "Podcastbude" >}} {{< span "weak" "0.94%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.47%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.47%" >}}
---

### 21. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on 0.02% of new episodes in September, growing 3.00% from last month.

Of these, 28.50% had 3 other trackers, 21.24% had one other tracker, 9.59% had 4 other trackers, 3.11% had 2 other trackers, 3.11% had 8 other trackers, 1.30% had 6 other trackers, and 0.78% had 9 other trackers.

56.74% also included Chartable, 38.34% also included Podtrac, 33.42% also included Podsights, 21.76% also included Podroll, 14.51% also included OP3, 13.99% also included Podcorn, 5.18% also included Gumshoe, 4.40% also included Podder, 1.04% also included Magellan AI, 0.78% also included Podscribe, and 0.78% also included Blubrry.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "32.90%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "15.54%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "12.18%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "12.18%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "10.10%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "7.25%" >}}
7. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "3.89%" >}}
8. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "2.59%" >}}
9. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "1.04%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.78%" >}}
---

### 22. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in September, growing 5.80% from last month.

Of these, 30.86% had one other tracker, 6.17% had 2 other trackers, 2.47% had 4 other trackers, and 0.82% had 3 other trackers.

26.75% also included Chartable, 12.76% also included Podtrac, 8.23% also included Podsights, 4.94% also included Podcorn, and 2.88% also included Podroll.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "100.00%" >}}
---

### 23. [Glystn](https://glystn.com/)

Glystn was found on 0.01% of new episodes in September, growing 15.94% from last month.

Of these, 97.47% had 2 other trackers, and 2.53% had one other tracker.

100.00% also included Chartable, and 97.47% also included Podtrac.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "97.47%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.53%" >}}
---

### 24. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in September, shrinking 12.80% from last month.

Of these, 32.17% had one other tracker, 3.48% had 2 other trackers, 2.61% had 5 other trackers, and 2.61% had 6 other trackers.

20.00% also included Chartable, 15.65% also included Podtrac, 13.04% also included Podcorn, 8.70% also included Podsights, 2.61% also included Podscribe, 2.61% also included OP3, 2.61% also included Podder, and 2.61% also included Gumshoe.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "40.00%" >}}
2. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "12.17%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "11.30%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "9.57%" >}}
5. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "7.83%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.83%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.48%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.48%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.87%" >}}
---

### 25. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in September, shrinking 9.01% from last month.

Of these, 41.28% had one other tracker, and 33.03% had 2 other trackers.

67.89% also included Chartable, 25.69% also included Podtrac, and 13.76% also included Podcorn.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "34.86%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "22.94%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "18.35%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "14.68%" >}}
5. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "3.67%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.67%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.83%" >}}
---

### 26. [Zippycast](https://zippycast.io/)

Zippycast was found on <0.01% of new episodes in September, shrinking 57.29% from last month.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "56.52%" >}}
2. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "26.09%" >}}
3. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "17.39%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2023-09.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
