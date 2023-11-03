---
title: "Top Podcast Tracking Services by Episode Share (October 2023)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2023-10.png
date: 2023-11-02T13:15:00-05:00
lastmod: 2023-11-02T13:09:00-05:00
draft: false
rssrevision: 2023-10
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

We already did the work of analyzing _every single new podcast episode published_ (about 2.0 million in October 2023), 
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

_Higher share of new episodes on S4P (which typically do not have prefixes) leads to lower share overall for all prefixes over the last two months, but should be stable going forward now that we have a more accurate baseline._

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Chartable	Adswizz	Podsights	Blubrry	Podcorn	Médiamétrie	Podscribe	Podder	Feedpress	Podroll	ArtsAI	OP3	Claritas	Spotify	Gumshoe	Veritonic	Audiotakes	Voxalyze	Zencastr	Podkite	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.00	1.16	2.07	2.09	0.42			0.32																1.61
Oct 2021	4.05	4.09	1.01	1.20	2.11	2.13	0.54			0.34																1.61
Nov 2021	4.07	4.30	1.02	1.25	2.01	2.14	0.57			0.32																0.59
Dec 2021	4.06	4.42	1.24	1.19	1.57	2.27	0.59			0.19																
Jan 2022	4.11	4.45	1.41	1.21	1.56	2.31	0.63			0.16																
Feb 2022	4.15	4.48	1.44	1.25	1.53	2.38	0.58			0.17																
Mar 2022	4.37	4.72	1.51	1.34	1.56	2.40	0.53			0.17																
Apr 2022	4.44	4.71	1.49	1.33	1.55	2.33	0.51			0.16																
May 2022	4.49	4.87	1.58	1.41	1.48	2.26	0.56			0.17																
Jun 2022	4.75	5.10	1.77	1.54	1.50	2.06	0.62			0.21													0.02			
Jul 2022	4.70	5.10	1.89	1.50	1.50	2.16	0.54			0.25													0.02			
Aug 2022	4.83	5.26	2.08	1.73	1.51	2.45	0.41			0.20		0.10											0.01			
Sep 2022	7.53	5.40	2.26	1.74	1.49	2.45	0.52	0.02		0.21		0.09		0.01							0.01		0.02	0.02		
Oct 2022	8.24	5.48	2.35	1.81	1.61	2.51	0.50	0.07		0.18		0.10	0.03	0.02						0.01	0.01		0.02	0.04		
Nov 2022	8.11	5.62	2.37	2.03	1.62	2.43	0.50	0.15	0.01	0.18		0.10	0.04	0.03						0.01	0.01		0.02	0.05		
Dec 2022	8.01	5.54	2.32	1.81	1.61	2.05	0.49	0.03	0.04	0.18		0.05	0.05	0.02						0.01	0.01	0.01	0.02	0.05		
Jan 2023	7.85	5.56	2.35	1.88	1.61	2.15	0.54	0.20	0.11	0.18		0.10	0.07	0.06						0.01	0.01	0.01	0.02	0.06		
Feb 2023	7.58	5.51	2.29	1.92	1.62	2.30	0.49	0.21	0.11	0.19		0.10	0.07	0.07						0.01	0.01	0.01	0.02	0.06	0.03	
Mar 2023	7.79	5.53	2.25	2.03	1.53	2.22	0.45	0.21	0.11	0.18	0.04	0.11	0.08	0.07			0.04			0.01	0.01	0.01	0.02	0.06		
Apr 2023	7.66	5.43	2.26	2.00	1.67	2.20	0.45	0.21	0.15	0.17	0.06	0.11	0.09	0.07		0.08	0.05			0.01	0.01	0.01	0.01			
May 2023	7.58	5.59	2.27	2.04	1.67	2.28	0.45	0.24	0.15	0.19	0.09	0.11	0.09	0.08		0.07	0.05		0.01	0.01	0.01	0.01	0.01			
Jun 2023	8.22	5.83	2.39	2.23	1.64	1.86	0.51	0.26	0.15	0.19	0.10	0.12	0.09	0.07		0.08	0.05		0.01	0.01	0.01	0.01	0.01			
Jul 2023	8.60	5.95	2.38	2.52	1.53	1.17	0.55	0.27	0.14	0.18	0.14	0.11	0.08	0.07	0.01	0.06	0.06		0.01	0.01	0.01	0.01	0.01			
Aug 2023	9.19	6.43	2.72	2.76	1.58	1.23	0.53	0.36	0.15	0.17	0.16	0.12	0.11	0.08	0.03	0.07	0.07	0.04	0.02	0.01	0.01	0.01				
Sep 2023	8.46	5.77	2.49	2.47	1.39	1.10	0.58	0.37	0.15	0.16	0.13	0.12	0.10	0.10	0.05	0.07	0.06	0.05	0.02	0.01	0.01	0.01				
Oct 2023	7.90	5.54	2.29	2.28	1.37	1.11	0.50	0.39	0.16	0.16	0.12	0.12	0.10	0.10	0.08	0.08	0.06	0.05	0.03	0.02	0.01	0.01				
{{< /graph >}}

---

### Overall

At least one tracker was found on 16.05% of new episodes in October, shrinking 5.15% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "21.49%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "15.55%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.71%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.27%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.69%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.57%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "3.00%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.53%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.28%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.98%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of October 2023.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 7.90% of new episodes in October, shrinking 6.68% from last month.

Of these, 24.21% had one other tracker, 11.18% had 2 other trackers, 2.45% had 3 other trackers, 1.01% had 4 other trackers, 0.85% had 5 other trackers, 0.34% had 6 other trackers, 0.11% had 7 other trackers, 0.01% had 8 other trackers, and <0.01% had 9 other trackers.

31.20% also included Chartable, 17.17% also included Podsights, 4.49% also included Adswizz, 2.53% also included Podscribe, 1.52% also included Podcorn, 1.24% also included Podder, 1.21% also included Magellan AI, 1.02% also included ArtsAI, 0.85% also included Podroll, 0.77% also included OP3, 0.69% also included Claritas, 0.65% also included Veritonic, 0.54% also included Gumshoe, 0.49% also included Blubrry, 0.37% also included Spotify, 0.11% also included Voxalyze, 0.08% also included Feedpress, 0.08% also included Glystn, 0.04% also included Audiotakes, 0.03% also included Médiamétrie, 0.02% also included Zencastr, 0.02% also included Podkite, 0.02% also included AdBarker, and <0.01% also included Firstory.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "42.67%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "19.44%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "12.86%" >}}
4. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.62%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.55%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.33%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.00%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.61%" >}}
9. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "1.30%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.26%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 6.31% of new episodes in October, shrinking 5.16% from last month.

Of these, 44.61% also included Podtrac, 6.50% also included Adswizz, 5.41% also included Podscribe, 2.34% also included Magellan AI, 2.25% also included Podcorn, 1.98% also included Podder, 1.84% also included ArtsAI, 1.55% also included Claritas, 1.48% also included Podroll, 1.02% also included Gumshoe, 0.92% also included Veritonic, 0.89% also included OP3, 0.86% also included Firstory, 0.38% also included Blubrry, 0.36% also included Audiotakes, 0.23% also included Voxalyze, 0.10% also included Glystn, 0.08% also included Zencastr, 0.06% also included Feedpress, 0.06% also included AdBarker, and 0.03% also included Podkite.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.82%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "22.44%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.35%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.21%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.14%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.96%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.69%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.68%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.25%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.13%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.54% of new episodes in October, shrinking 3.93% from last month.

Of these, 36.50% had one other tracker, 16.97% had 2 other trackers, 3.99% had 3 other trackers, 1.55% had 4 other trackers, 1.05% had 5 other trackers, 0.45% had 6 other trackers, 0.13% had 7 other trackers, 0.01% had 8 other trackers, and <0.01% had 9 other trackers.

44.45% also included Podtrac, 27.68% also included Podsights, 5.17% also included Adswizz, 4.52% also included Podscribe, 2.12% also included Magellan AI, 2.03% also included Podder, 1.94% also included Podcorn, 1.67% also included ArtsAI, 1.53% also included Podroll, 1.42% also included Claritas, 1.01% also included Spotify, 0.98% also included Firstory, 0.87% also included Veritonic, 0.61% also included Gumshoe, 0.50% also included OP3, 0.33% also included Blubrry, 0.25% also included Voxalyze, 0.16% also included Audiotakes, 0.11% also included Glystn, 0.08% also included Zencastr, 0.07% also included Feedpress, 0.06% also included AdBarker, and 0.03% also included Podkite.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.05%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.32%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.76%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.28%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.59%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.37%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.70%" >}}
8. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.56%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.48%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.40%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.29% of new episodes in October, shrinking 7.88% from last month.

Of these, 23.38% had one other tracker, 2.75% had 2 other trackers, 2.50% had 3 other trackers, 0.50% had 6 other trackers, 0.41% had 4 other trackers, 0.40% had 5 other trackers, and 0.23% had 7 other trackers.

15.49% also included Podtrac, 12.52% also included Chartable, 8.67% also included Podsights, 1.41% also included Podscribe, 1.30% also included Blubrry, 1.13% also included Audiotakes, 1.03% also included ArtsAI, 0.88% also included Claritas, 0.69% also included Veritonic, 0.69% also included Podroll, 0.25% also included Magellan AI, 0.21% also included Spotify, 0.16% also included OP3, 0.15% also included Podcorn, 0.08% also included Podder, and 0.03% also included Gumshoe.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "30.44%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "15.97%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.27%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "9.96%" >}}
5. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "8.55%" >}}
6. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "8.53%" >}}
7. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "3.84%" >}}
8. {{< a "https://www.mediastre.am/" "mediastream" >}} {{< span "weak" "1.42%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.42%" >}}
10. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.39%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.28% of new episodes in October, shrinking 7.94% from last month.

Of these, 36.91% had one other tracker, 35.05% had 2 other trackers, 9.09% had 3 other trackers, 4.76% had 4 other trackers, 3.30% had 5 other trackers, 1.11% had 6 other trackers, 0.31% had 7 other trackers, 0.03% had 8 other trackers, and 0.01% had 9 other trackers.

67.42% also included Chartable, 59.57% also included Podtrac, 12.15% also included Podscribe, 8.73% also included Adswizz, 5.84% also included Magellan AI, 4.38% also included Podder, 4.17% also included ArtsAI, 3.28% also included Claritas, 2.49% also included Podcorn, 2.21% also included Veritonic, 2.21% also included Gumshoe, 2.06% also included Podroll, 1.61% also included OP3, 1.11% also included Spotify, 0.95% also included Audiotakes, 0.32% also included Voxalyze, 0.27% also included Blubrry, 0.07% also included Zencastr, 0.07% also included Feedpress, 0.03% also included Podkite, and <0.01% also included Glystn.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "51.18%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "31.25%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.64%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.25%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.15%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.77%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.44%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.98%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.90%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.86%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.37% of new episodes in October, shrinking 1.66% from last month.

Of these, 6.44% had one other tracker, 0.68% had 2 other trackers, 0.08% had 3 other trackers, 0.07% had 4 other trackers, and 0.01% had 6 other trackers.

2.85% also included Podtrac, 2.18% also included Adswizz, 1.35% also included Chartable, 0.93% also included Feedpress, 0.44% also included Podsights, 0.26% also included Podcorn, 0.15% also included Podscribe, 0.06% also included OP3, 0.03% also included Podder, 0.02% also included Podroll, 0.01% also included Spotify, 0.01% also included Voxalyze, 0.01% also included Claritas, 0.01% also included Audiotakes, 0.01% also included Magellan AI, 0.01% also included ArtsAI, and 0.01% also included Veritonic.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "43.22%" >}}
2. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "7.35%" >}}
3. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.26%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.19%" >}}
5. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.82%" >}}
6. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.51%" >}}
7. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.08%" >}}
8. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.07%" >}}
9. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.97%" >}}
10. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.81%" >}}
---

### 6. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 1.11% of new episodes in October, growing 1.32% from last month.

Of these, 9.78% had one other tracker, 3.49% had 2 other trackers, 1.73% had 5 other trackers, 1.38% had 4 other trackers, 1.10% had 3 other trackers, 0.11% had 6 other trackers, 0.08% had 7 other trackers, 0.07% had 8 other trackers, and 0.01% had 9 other trackers.

10.79% also included Podtrac, 9.70% also included Chartable, 5.11% also included Podsights, 3.28% also included Gumshoe, 3.13% also included OP3, 1.69% also included Podscribe, 0.67% also included Podder, 0.43% also included Podroll, 0.31% also included Blubrry, 0.30% also included Adswizz, 0.29% also included Voxalyze, 0.10% also included Zencastr, 0.09% also included Magellan AI, 0.07% also included Podkite, 0.07% also included Spotify, and 0.04% also included AdBarker.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "42.95%" >}}
2. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "11.56%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.55%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.73%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "5.70%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "5.13%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.65%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.29%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.70%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.38%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.50% of new episodes in October, shrinking 14.51% from last month.

Of these, 0.49% had one other tracker.

0.49% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "36.93%" >}}
2. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "35.47%" >}}
3. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "11.22%" >}}
4. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "6.88%" >}}
5. {{< a "https://soundcast.fm/" "SoundCast" >}} {{< span "weak" "5.87%" >}}
6. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "1.92%" >}}
7. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "1.33%" >}}
---

### 8. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.39% of new episodes in October, growing 5.71% from last month.

Of these, 20.96% had 3 other trackers, 17.72% had 2 other trackers, 16.16% had 5 other trackers, 15.25% had 4 other trackers, 13.68% had one other tracker, 7.20% had 6 other trackers, 2.20% had 7 other trackers, 0.04% had 9 other trackers, and 0.01% had 8 other trackers.

71.63% also included Podsights, 64.93% also included Chartable, 51.69% also included Podtrac, 22.45% also included ArtsAI, 22.06% also included Magellan AI, 21.39% also included Claritas, 13.09% also included Veritonic, 8.35% also included Adswizz, 6.98% also included Spotify, 6.03% also included Gumshoe, 5.77% also included Audiotakes, 5.16% also included Podroll, 4.86% also included Podcorn, 4.05% also included Podder, 3.76% also included OP3, 0.54% also included Blubrry, 0.06% also included Podkite, and 0.06% also included Voxalyze.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "46.36%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "12.84%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "9.23%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.67%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.91%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.59%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.09%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.81%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.72%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.97%" >}}
---

### 9. [Podder](https://www.podderapp.com/)

Podder was found on 0.16% of new episodes in October, growing 2.44% from last month.

Of these, 24.83% had 3 other trackers, 18.44% had 4 other trackers, 16.89% had 2 other trackers, 10.79% had one other tracker, 8.92% had 5 other trackers, 2.21% had 6 other trackers, 1.01% had 7 other trackers, 0.47% had 8 other trackers, and 0.09% had 9 other trackers.

71.24% also included Chartable, 63.14% also included Podsights, 62.07% also included Podtrac, 27.52% also included Magellan AI, 9.90% also included Podscribe, 9.40% also included Podroll, 4.68% also included Podcorn, 3.89% also included Claritas, 3.35% also included OP3, 2.44% also included Gumshoe, 1.42% also included ArtsAI, 1.23% also included Adswizz, 0.73% also included Veritonic, 0.66% also included Voxalyze, 0.25% also included Blubrry, 0.22% also included Spotify, 0.16% also included Podkite, and 0.16% also included Feedpress.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "71.75%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "8.13%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.70%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.64%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.54%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.48%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.99%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.58%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.76%" >}}
10. {{< a "https://www.thepodops.com/" "PodOps" >}} {{< span "weak" "0.22%" >}}
---

### 10. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.16% of new episodes in October, shrinking 2.96% from last month.

Of these, 13.21% had one other tracker, 1.17% had 2 other trackers, and 0.03% had 3 other trackers.

8.08% also included Blubrry, 3.87% also included Podtrac, 2.44% also included Chartable, 0.98% also included Podsights, 0.16% also included Podder, and 0.13% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "47.50%" >}}
2. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "9.41%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.03%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.96%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.94%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.96%" >}}
7. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "2.12%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.03%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.55%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.01%" >}}
---

### 11. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.16% of new episodes in October, growing 25.03% from last month.

Of these, 35.85% had 4 other trackers, 18.83% had 3 other trackers, 15.49% had 5 other trackers, 11.28% had 2 other trackers, 7.65% had 6 other trackers, 6.79% had one other tracker, and 3.22% had 7 other trackers.

84.93% also included Podsights, 75.11% also included Chartable, 60.80% also included Podtrac, 54.37% also included Podscribe, 27.72% also included Podder, 24.54% also included Claritas, 13.80% also included ArtsAI, 13.10% also included Podroll, 8.92% also included Veritonic, 4.49% also included Spotify, 3.60% also included Adswizz, 2.20% also included Audiotakes, 0.70% also included Gumshoe, 0.61% also included Podcorn, 0.16% also included Voxalyze, and 0.06% also included Blubrry.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "71.22%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "7.46%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.44%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.35%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.00%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.03%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.89%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.25%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.19%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.16%" >}}
---

### 12. [Podroll](https://podroll.fm/)

Podroll was found on 0.12% of new episodes in October, shrinking 3.83% from last month.

Of these, 26.72% had 2 other trackers, 18.61% had 4 other trackers, 18.17% had 3 other trackers, 11.52% had one other tracker, 3.24% had 5 other trackers, 1.99% had 6 other trackers, 1.50% had 7 other trackers, 0.57% had 8 other trackers, and 0.12% had 9 other trackers.

69.10% also included Chartable, 54.74% also included Podtrac, 38.16% also included Podsights, 16.67% also included Magellan AI, 16.18% also included Podscribe, 12.85% also included Adswizz, 12.04% also included Podder, 3.85% also included Podcorn, 3.73% also included Voxalyze, 3.49% also included Claritas, 2.96% also included Gumshoe, 2.43% also included OP3, 1.46% also included ArtsAI, 0.32% also included Spotify, and 0.20% also included Blubrry.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "42.54%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "23.88%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "14.60%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.75%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.64%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.99%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.50%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.26%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.49%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.24%" >}}
---

### 13. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.12% of new episodes in October, shrinking 0.77% from last month.

Of these, 28.17% had 5 other trackers, 19.23% had 3 other trackers, 15.46% had 2 other trackers, 14.87% had 4 other trackers, 14.44% had 6 other trackers, 5.89% had 7 other trackers, and 1.10% had one other tracker.

80.56% also included Podsights, 78.70% also included Chartable, 73.53% also included Podscribe, 68.57% also included Podtrac, 30.37% also included Claritas, 28.89% also included Veritonic, 19.95% also included Adswizz, 18.34% also included Magellan AI, 8.51% also included Spotify, 5.84% also included Audiotakes, 1.91% also included Podder, 1.52% also included Podroll, 1.10% also included Gumshoe, and 0.08% also included Blubrry.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.35%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "22.79%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "12.11%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.97%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.26%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "8.22%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.74%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.19%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.21%" >}}
10. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.17%" >}}
---

### 14. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.10% of new episodes in October, growing 4.71% from last month.

Of these, 24.56% had one other tracker, 17.76% had 5 other trackers, 13.60% had 4 other trackers, 12.49% had 2 other trackers, 2.63% had 3 other trackers, 1.15% had 6 other trackers, 0.72% had 8 other trackers, 0.43% had 7 other trackers, and 0.14% had 9 other trackers.

58.31% also included Podtrac, 35.23% also included Podsights, 33.37% also included Podcorn, 32.41% also included Gumshoe, 26.66% also included Chartable, 13.93% also included Podscribe, 5.07% also included Podder, 3.54% also included Adswizz, 3.02% also included Voxalyze, 2.87% also included Podroll, 1.96% also included Spotify, 0.77% also included Blubrry, 0.24% also included Podkite, and 0.19% also included Feedpress.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "43.80%" >}}
2. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "13.60%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.83%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.59%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.35%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.92%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.78%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.15%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.11%" >}}
10. {{< a "https://letscast.fm/" "LetsCast.fm" >}} {{< span "weak" "1.77%" >}}
---

### 15. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.10% of new episodes in October, growing 1.27% from last month.

Of these, 19.71% had 4 other trackers, 18.01% had 6 other trackers, 17.62% had 5 other trackers, 16.36% had 3 other trackers, 15.73% had 2 other trackers, 6.99% had 7 other trackers, and 3.35% had one other tracker.

80.29% also included Podscribe, 76.50% also included Chartable, 72.67% also included Podsights, 52.91% also included Podtrac, 37.38% also included Magellan AI, 34.81% also included ArtsAI, 19.61% also included Adswizz, 15.05% also included Veritonic, 8.30% also included Spotify, 5.97% also included Podder, 4.17% also included Podroll, and 0.15% also included Blubrry.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "39.37%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "24.42%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "14.17%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.37%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "7.23%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.74%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.36%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.15%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.15%" >}}
10. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "0.05%" >}}
---

### 16. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.08% of new episodes in October, growing 52.28% from last month.

Of these, 34.78% had one other tracker, 24.63% had 2 other trackers, 23.95% had 3 other trackers, 5.75% had 6 other trackers, 3.59% had 7 other trackers, 2.17% had 5 other trackers, and 1.67% had 4 other trackers.

69.74% also included Chartable, 36.14% also included Podtrac, 33.42% also included Podscribe, 31.19% also included Podsights, 12.44% also included ArtsAI, 11.51% also included Gumshoe, 10.58% also included Claritas, 8.73% also included Magellan AI, 5.94% also included Adswizz, 5.14% also included Veritonic, 3.59% also included Audiotakes, 2.54% also included OP3, 0.93% also included Podcorn, 0.50% also included Podroll, 0.43% also included Podder, and 0.25% also included Blubrry.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.53%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "26.18%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.24%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.24%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.62%" >}}
6. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "5.38%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.70%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.53%" >}}
9. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.48%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.05%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.08% of new episodes in October, growing 12.89% from last month.

Of these, 24.82% had 5 other trackers, 20.31% had 4 other trackers, 18.88% had 2 other trackers, 9.73% had 3 other trackers, 9.67% had one other tracker, 3.27% had 6 other trackers, 1.11% had 7 other trackers, 0.98% had 8 other trackers, and 0.20% had 9 other trackers.

65.84% also included Podsights, 55.65% also included Podtrac, 47.62% also included Podcorn, 44.22% also included OP3, 43.89% also included Chartable, 30.44% also included Podscribe, 12.15% also included Spotify, 5.03% also included Podder, 4.77% also included Podroll, 2.68% also included Audiotakes, 1.70% also included Voxalyze, 1.70% also included ArtsAI, 1.44% also included Magellan AI, 0.91% also included Adswizz, 0.59% also included Veritonic, and 0.33% also included Podkite.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "45.26%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "26.39%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "23.06%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.81%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.31%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.59%" >}}
7. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.26%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.20%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.13%" >}}
---

### 18. [Firstory](https://firstory.me/)

Firstory was found on 0.08% of new episodes in October, shrinking 4.86% from last month.

Of these, 71.65% had one other tracker, and 0.07% had 2 other trackers.

71.72% also included Chartable, and 0.07% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.80%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.20%" >}}
---

### 19. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.06% of new episodes in October, growing 3.71% from last month.

Of these, 40.47% had 5 other trackers, 25.40% had 6 other trackers, 13.91% had 4 other trackers, 6.08% had 7 other trackers, 5.50% had 3 other trackers, 5.08% had 2 other trackers, and 3.00% had one other tracker.

85.93% also included Podtrac, 84.26% also included Podscribe, 83.93% also included Podsights, 80.02% also included Chartable, 56.79% also included ArtsAI, 26.56% also included Adswizz, 25.81% also included Claritas, 23.31% also included Magellan AI, 6.91% also included Spotify, 6.16% also included Audiotakes, 1.92% also included Podder, 0.75% also included Gumshoe, and 0.17% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "54.04%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "24.31%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "11.24%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.91%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.33%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.00%" >}}
---

### 20. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.05% of new episodes in October, growing 8.75% from last month.

Of these, 51.88% had one other tracker, 16.30% had 2 other trackers, 15.22% had 3 other trackers, 8.50% had 4 other trackers, 4.05% had 5 other trackers, and 2.57% had 6 other trackers.

51.19% also included Adswizz, 44.07% also included Podscribe, 42.69% also included Podsights, 17.39% also included Chartable, 13.64% also included ArtsAI, 7.31% also included Veritonic, 6.82% also included Magellan AI, 6.72% also included Podtrac, 5.73% also included Spotify, 4.05% also included Gumshoe, and 0.20% also included Blubrry.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "25.10%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "14.13%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.94%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.17%" >}}
5. {{< a "https://kostenlos-hosten.de/" "Podcastbude" >}} {{< span "weak" "1.58%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.79%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.59%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.49%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.40%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.30%" >}}
---

### 21. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on 0.03% of new episodes in October, growing 23.77% from last month.

Of these, 23.27% had one other tracker, 21.73% had 3 other trackers, 9.04% had 4 other trackers, 4.04% had 2 other trackers, 2.88% had 8 other trackers, 0.77% had 6 other trackers, 0.58% had 9 other trackers, 0.38% had 5 other trackers, and 0.19% had 7 other trackers.

54.23% also included Chartable, 33.08% also included Podtrac, 27.88% also included Podsights, 17.69% also included Podroll, 12.31% also included Podcorn, 12.12% also included OP3, 5.00% also included Gumshoe, 4.04% also included Podder, 0.96% also included Podscribe, 0.96% also included Magellan AI, and 0.58% also included Blubrry.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.23%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "13.46%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "12.69%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "11.92%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "10.77%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.04%" >}}
7. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "4.04%" >}}
8. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "3.08%" >}}
9. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.15%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.15%" >}}
---

### 22. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.02% of new episodes in October, growing 14.19% from last month.

Of these, 30.79% had one other tracker, 7.95% had 2 other trackers, and 4.30% had 3 other trackers.

31.13% also included Chartable, 10.60% also included Podtrac, 10.60% also included Podsights, and 7.28% also included Podcorn.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "100.00%" >}}
---

### 23. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in October, growing 2.27% from last month.

Of these, 31.25% had one other tracker, 3.91% had 5 other trackers, 3.91% had 6 other trackers, and 3.13% had 2 other trackers.

23.44% also included Chartable, 18.75% also included Podtrac, 11.72% also included Podcorn, 10.94% also included Podsights, 3.91% also included Podscribe, 3.91% also included OP3, 3.91% also included Podder, and 3.91% also included Gumshoe.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "43.75%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "14.06%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "10.16%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.81%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "6.25%" >}}
6. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "6.25%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.91%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.13%" >}}
9. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.78%" >}}
---

### 24. [Glystn](https://glystn.com/)

Glystn was found on 0.01% of new episodes in October, shrinking 27.89% from last month.

Of these, 94.35% had 2 other trackers, 4.03% had one other tracker, and 1.61% had 3 other trackers.

100.00% also included Chartable, 95.97% also included Podtrac, and 1.61% also included Podsights.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "95.97%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.03%" >}}
---

### 25. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in October, shrinking 14.02% from last month.

Of these, 42.16% had one other tracker, and 29.41% had 2 other trackers.

68.63% also included Chartable, 23.53% also included Podtrac, and 8.82% also included Podcorn.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "39.22%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "23.53%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "17.65%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "13.73%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.94%" >}}
6. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "0.98%" >}}
7. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "0.98%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.98%" >}}
---

### 26. [Zippycast](https://zippycast.io/)

Zippycast was found on <0.01% of new episodes in October, growing 35.82% from last month.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "82.35%" >}}
2. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "17.65%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
