---
title: "Top Podcast Tracking Services by Episode Share (December 2023)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-december-2023"
images:
- trackers-2023-12.png
date: 2024-01-01T18:00:00-06:00
lastmod: 2024-01-01T18:00:00-06:00
draft: false
rssrevision: 2023-12
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.7 million in December 2023), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in December, how many
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
Month	Podtrac	Chartable	Adswizz	Podsights	Blubrry	Podcorn	Podscribe	Médiamétrie	Podder	Feedpress	Podroll	ArtsAI	Spotify	OP3	Claritas	Gumshoe	Audiotakes	Veritonic	Voxalyze	Zencastr	Podkite	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.00	1.16	2.07	2.09		0.42		0.32																1.61
Oct 2021	4.05	4.09	1.01	1.20	2.11	2.13		0.54		0.34																1.61
Nov 2021	4.07	4.30	1.02	1.25	2.01	2.14		0.57		0.32																0.59
Dec 2021	4.06	4.42	1.24	1.19	1.57	2.27		0.59		0.19																
Jan 2022	4.11	4.45	1.41	1.21	1.56	2.31		0.63		0.16																
Feb 2022	4.15	4.48	1.44	1.25	1.53	2.38		0.58		0.17																
Mar 2022	4.37	4.72	1.51	1.34	1.56	2.40		0.53		0.17																
Apr 2022	4.44	4.71	1.49	1.33	1.55	2.33		0.51		0.16																
May 2022	4.49	4.87	1.58	1.41	1.48	2.26		0.56		0.17																
Jun 2022	4.75	5.10	1.77	1.54	1.50	2.06		0.62		0.21													0.02			
Jul 2022	4.70	5.10	1.89	1.50	1.50	2.16		0.54		0.25													0.02			
Aug 2022	4.83	5.26	2.08	1.73	1.51	2.45		0.41		0.20		0.10											0.01			
Sep 2022	7.53	5.40	2.26	1.74	1.49	2.45	0.02	0.52		0.21		0.09			0.01						0.01		0.02	0.02		
Oct 2022	8.24	5.48	2.35	1.81	1.61	2.51	0.07	0.50		0.18		0.10		0.03	0.02					0.01	0.01		0.02	0.04		
Nov 2022	8.11	5.62	2.37	2.03	1.62	2.43	0.15	0.50	0.01	0.18		0.10		0.04	0.03					0.01	0.01		0.02	0.05		
Dec 2022	8.01	5.54	2.32	1.81	1.61	2.05	0.03	0.49	0.04	0.18		0.05		0.05	0.02					0.01	0.01	0.01	0.02	0.05		
Jan 2023	7.85	5.56	2.35	1.88	1.61	2.15	0.20	0.54	0.11	0.18		0.10		0.07	0.06					0.01	0.01	0.01	0.02	0.06		
Feb 2023	7.58	5.51	2.29	1.92	1.62	2.30	0.21	0.49	0.11	0.19		0.10		0.07	0.07					0.01	0.01	0.01	0.02	0.06	0.03	
Mar 2023	7.79	5.53	2.25	2.03	1.53	2.22	0.21	0.45	0.11	0.18	0.04	0.11		0.08	0.07			0.04		0.01	0.01	0.01	0.02	0.06		
Apr 2023	7.66	5.43	2.26	2.00	1.67	2.20	0.21	0.45	0.15	0.17	0.06	0.11		0.09	0.07	0.08		0.05		0.01	0.01	0.01	0.01			
May 2023	7.58	5.59	2.27	2.04	1.67	2.28	0.24	0.45	0.15	0.19	0.09	0.11		0.09	0.08	0.07		0.05	0.01	0.01	0.01	0.01	0.01			
Jun 2023	8.22	5.83	2.39	2.23	1.64	1.86	0.26	0.51	0.15	0.19	0.10	0.12		0.09	0.07	0.08		0.05	0.01	0.01	0.01	0.01	0.01			
Jul 2023	8.60	5.95	2.38	2.52	1.53	1.17	0.27	0.55	0.14	0.18	0.14	0.11	0.01	0.08	0.07	0.06		0.06	0.01	0.01	0.01	0.01	0.01			
Aug 2023	9.19	6.43	2.72	2.76	1.58	1.23	0.36	0.53	0.15	0.17	0.16	0.12	0.03	0.11	0.08	0.07	0.04	0.07	0.02	0.01	0.01	0.01				
Sep 2023	8.46	5.77	2.49	2.47	1.39	1.10	0.37	0.58	0.15	0.16	0.13	0.12	0.05	0.10	0.10	0.07	0.05	0.06	0.02	0.01	0.01	0.01				
Oct 2023	7.90	5.54	2.29	2.28	1.37	1.11	0.39	0.50	0.16	0.16	0.12	0.12	0.08	0.10	0.10	0.08	0.05	0.06	0.03	0.02	0.01	0.01				
Nov 2023	7.65	5.59	2.25	2.33	1.45	1.14	0.47	0.33	0.16	0.17	0.12	0.12	0.11	0.13	0.11	0.10	0.06	0.06	0.03	0.01	0.01					
Dec 2023	7.48	5.60	2.20	2.19	1.53	1.12	0.54	0.33	0.16	0.16	0.12	0.12	0.12	0.11	0.11	0.09	0.06	0.06	0.03	0.01	0.01					
{{< /graph >}}

---

### Overall

At least one tracker was found on 15.66% of new episodes in December, shrinking 0.43% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "20.51%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "16.05%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.56%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.78%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.75%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.65%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "3.09%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.67%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.96%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.94%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of December 2023.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 7.48% of new episodes in December, shrinking 2.30% from last month.

Of these, 23.53% had one other tracker, 12.31% had 2 other trackers, 2.72% had 3 other trackers, 1.61% had 4 other trackers, 0.72% had 5 other trackers, 0.56% had 6 other trackers, 0.14% had 7 other trackers, 0.01% had 8 other trackers, and <0.01% had 9 other trackers.

32.83% also included Chartable, 18.19% also included Podsights, 4.26% also included Podscribe, 4.26% also included Adswizz, 2.04% also included Magellan AI, 1.66% also included Podcorn, 1.34% also included Podder, 1.11% also included ArtsAI, 0.86% also included OP3, 0.78% also included Claritas, 0.74% also included Podroll, 0.62% also included Gumshoe, 0.62% also included Veritonic, 0.53% also included Spotify, 0.51% also included Blubrry, 0.11% also included Audiotakes, 0.10% also included Voxalyze, 0.09% also included Feedpress, 0.03% also included Médiamétrie, 0.03% also included Zencastr, 0.01% also included Podkite, 0.01% also included AdBarker, 0.01% also included Glystn, 0.01% also included CoHost Prefix, and <0.01% also included Firstory.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "41.89%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "20.50%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.65%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.77%" >}}
5. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.50%" >}}
6. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.23%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.92%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.77%" >}}
9. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "1.28%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.26%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 6.22% of new episodes in December, shrinking 1.31% from last month.

Of these, 43.94% also included Podtrac, 7.09% also included Podscribe, 5.49% also included Adswizz, 3.68% also included Magellan AI, 2.35% also included Podcorn, 2.10% also included Podder, 1.86% also included ArtsAI, 1.63% also included Claritas, 1.39% also included Podroll, 1.15% also included Gumshoe, 0.92% also included Firstory, 0.90% also included OP3, 0.86% also included Veritonic, 0.54% also included Audiotakes, 0.31% also included Blubrry, 0.28% also included Voxalyze, 0.08% also included Zencastr, 0.08% also included Feedpress, 0.06% also included AdBarker, 0.03% also included Podkite, 0.01% also included Glystn, and 0.01% also included CoHost Prefix.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.50%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.34%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.33%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.28%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.26%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.02%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.76%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.70%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.53%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.25%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.60% of new episodes in December, growing 0.19% from last month.

Of these, 34.45% had one other tracker, 17.46% had 2 other trackers, 4.10% had 3 other trackers, 2.44% had 4 other trackers, 0.79% had 5 other trackers, 0.75% had 6 other trackers, 0.16% had 7 other trackers, 0.01% had 8 other trackers, and <0.01% had 9 other trackers.

43.81% also included Podtrac, 28.71% also included Podsights, 5.79% also included Podscribe, 5.16% also included Adswizz, 3.44% also included Magellan AI, 2.11% also included Podcorn, 2.09% also included Podder, 1.61% also included ArtsAI, 1.43% also included Claritas, 1.38% also included Podroll, 1.36% also included Spotify, 1.02% also included Firstory, 0.78% also included Gumshoe, 0.77% also included Veritonic, 0.56% also included OP3, 0.30% also included Voxalyze, 0.27% also included Audiotakes, 0.26% also included Blubrry, 0.08% also included Feedpress, 0.08% also included Zencastr, 0.06% also included AdBarker, 0.03% also included Podkite, 0.01% also included Glystn, and 0.01% also included CoHost Prefix.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.71%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.43%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.54%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.21%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.60%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.25%" >}}
7. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.81%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.67%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.57%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.47%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.20% of new episodes in December, shrinking 2.15% from last month.

Of these, 19.57% had one other tracker, 3.04% had 2 other trackers, 2.63% had 3 other trackers, 0.53% had 6 other trackers, 0.49% had 4 other trackers, 0.38% had 5 other trackers, and 0.25% had 7 other trackers.

14.46% also included Podtrac, 13.14% also included Chartable, 5.66% also included Podsights, 1.77% also included Blubrry, 1.45% also included Podscribe, 1.34% also included Audiotakes, 1.02% also included ArtsAI, 0.96% also included Claritas, 0.79% also included Podroll, 0.64% also included Veritonic, 0.38% also included Spotify, 0.29% also included Magellan AI, 0.22% also included OP3, 0.13% also included Podcorn, 0.06% also included Podder, 0.04% also included Gumshoe, and 0.02% also included Zencastr.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "34.49%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "13.81%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "10.91%" >}}
4. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "9.02%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "7.43%" >}}
6. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "6.17%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.55%" >}}
8. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.42%" >}}
9. {{< a "https://www.julephosting.de/" "Julep Hosting" >}} {{< span "weak" "1.38%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.35%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.19% of new episodes in December, shrinking 5.76% from last month.

Of these, 38.16% had 2 other trackers, 31.15% had one other tracker, 9.67% had 3 other trackers, 6.91% had 4 other trackers, 2.82% had 5 other trackers, 1.92% had 6 other trackers, 0.42% had 7 other trackers, 0.02% had 8 other trackers, and 0.01% had 9 other trackers.

73.31% also included Chartable, 61.97% also included Podtrac, 16.30% also included Podscribe, 9.21% also included Magellan AI, 5.68% also included Adswizz, 4.54% also included Podder, 4.27% also included ArtsAI, 3.62% also included Claritas, 2.32% also included Gumshoe, 2.25% also included Podcorn, 2.14% also included Veritonic, 2.14% also included Podroll, 1.62% also included Spotify, 1.49% also included OP3, 1.33% also included Audiotakes, 0.31% also included Voxalyze, 0.24% also included Blubrry, 0.10% also included Feedpress, 0.03% also included Zencastr, 0.02% also included Podkite, 0.02% also included Glystn, and 0.01% also included CoHost Prefix.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "58.39%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "23.55%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.75%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.34%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.01%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.76%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.50%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.21%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.97%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.90%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.53% of new episodes in December, growing 5.60% from last month.

Of these, 6.38% had one other tracker, 0.56% had 2 other trackers, 0.06% had 3 other trackers, 0.05% had 4 other trackers, and <0.01% had 6 other trackers.

2.55% also included Adswizz, 2.48% also included Podtrac, 1.03% also included Feedpress, 0.96% also included Chartable, 0.34% also included Podsights, 0.23% also included Podcorn, 0.12% also included Podscribe, 0.06% also included OP3, 0.05% also included Podroll, 0.03% also included Podder, 0.01% also included Claritas, 0.01% also included Gumshoe, <0.01% also included Voxalyze, <0.01% also included Audiotakes, <0.01% also included Magellan AI, <0.01% also included ArtsAI, and <0.01% also included Veritonic.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "38.39%" >}}
2. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "8.27%" >}}
3. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "7.36%" >}}
4. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.03%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.18%" >}}
6. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.54%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.50%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.26%" >}}
9. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.20%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "0.92%" >}}
---

### 6. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 1.12% of new episodes in December, shrinking 1.81% from last month.

Of these, 10.86% had one other tracker, 3.75% had 2 other trackers, 1.41% had 5 other trackers, 1.34% had 4 other trackers, 1.07% had 3 other trackers, 0.18% had 6 other trackers, 0.12% had 7 other trackers, 0.04% had 8 other trackers, and 0.02% had 9 other trackers.

11.07% also included Podtrac, 10.55% also included Chartable, 4.42% also included Podsights, 3.14% also included Gumshoe, 2.83% also included OP3, 1.65% also included Podscribe, 0.78% also included Voxalyze, 0.63% also included Podder, 0.31% also included Blubrry, 0.31% also included Podroll, 0.25% also included Adswizz, 0.13% also included Spotify, 0.09% also included Feedpress, 0.07% also included Zencastr, 0.06% also included Podkite, 0.05% also included Magellan AI, 0.03% also included AdBarker, and 0.01% also included CoHost Prefix.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "42.57%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "12.23%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "12.06%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.38%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "5.29%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.71%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.68%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.46%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.57%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.20%" >}}
---

### 7. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.54% of new episodes in December, growing 14.74% from last month.

Of these, 21.48% had one other tracker, 20.64% had 4 other trackers, 18.73% had 3 other trackers, 14.00% had 2 other trackers, 9.54% had 5 other trackers, 8.14% had 6 other trackers, 1.91% had 7 other trackers, and 0.03% had 9 other trackers.

65.77% also included Podsights, 59.61% also included Chartable, 58.61% also included Podtrac, 30.51% also included Magellan AI, 16.56% also included Claritas, 16.17% also included ArtsAI, 10.83% also included Spotify, 8.49% also included Veritonic, 6.09% also included Audiotakes, 5.86% also included Adswizz, 4.97% also included Gumshoe, 4.79% also included Podder, 3.78% also included Podroll, 3.39% also included Podcorn, 2.68% also included OP3, 0.34% also included Blubrry, and 0.03% also included Voxalyze.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "55.15%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.73%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "7.96%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.38%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.72%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.07%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.11%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.75%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.13%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.07%" >}}
---

### 8. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.33% of new episodes in December, growing 0.35% from last month.

Of these, 0.65% had one other tracker.

0.65% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "53.16%" >}}
2. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "18.23%" >}}
3. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "10.55%" >}}
4. {{< a "https://soundcast.fm/" "SoundCast" >}} {{< span "weak" "8.29%" >}}
5. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "3.91%" >}}
6. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "3.35%" >}}
7. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "1.54%" >}}
---

### 9. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.24% of new episodes in December, growing 19.26% from last month.

Of these, 43.16% had 4 other trackers, 14.69% had 3 other trackers, 14.39% had 5 other trackers, 11.27% had 6 other trackers, 8.79% had 2 other trackers, 3.99% had one other tracker, and 2.81% had 7 other trackers.

85.34% also included Podsights, 81.32% also included Chartable, 70.10% also included Podscribe, 64.40% also included Podtrac, 22.29% also included Claritas, 20.34% also included Podder, 16.65% also included ArtsAI, 11.42% also included Veritonic, 9.34% also included Podroll, 8.74% also included Spotify, 3.29% also included Audiotakes, 2.71% also included Adswizz, 1.31% also included Gumshoe, 0.25% also included Podcorn, and 0.03% also included Blubrry.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "74.19%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.43%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.90%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.60%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.26%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.31%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.75%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.20%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.13%" >}}
10. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.13%" >}}
---

### 10. [Podder](https://www.podderapp.com/)

Podder was found on 0.16% of new episodes in December, growing 1.83% from last month.

Of these, 22.15% had 3 other trackers, 18.22% had 4 other trackers, 15.40% had 2 other trackers, 12.45% had one other tracker, 11.72% had 5 other trackers, 1.80% had 6 other trackers, 0.97% had 7 other trackers, 0.29% had 8 other trackers, and 0.11% had 9 other trackers.

71.03% also included Chartable, 60.82% also included Podtrac, 60.50% also included Podsights, 29.22% also included Magellan AI, 15.80% also included Podscribe, 8.08% also included Podroll, 4.29% also included Podcorn, 3.17% also included Claritas, 2.89% also included OP3, 2.06% also included Gumshoe, 1.52% also included ArtsAI, 0.76% also included Adswizz, 0.76% also included Veritonic, 0.47% also included Voxalyze, 0.29% also included Spotify, 0.25% also included Blubrry, 0.14% also included Podkite, and 0.07% also included CoHost Prefix.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "70.09%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "7.54%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.66%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.00%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.68%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.57%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.41%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.23%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.83%" >}}
10. {{< a "https://www.thepodops.com/" "PodOps" >}} {{< span "weak" "0.58%" >}}
---

### 11. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.16% of new episodes in December, shrinking 2.01% from last month.

Of these, 15.84% had one other tracker, 1.31% had 2 other trackers, and 0.11% had 3 other trackers.

9.67% also included Blubrry, 4.25% also included Podtrac, 2.80% also included Chartable, 1.31% also included Podsights, 0.62% also included Podcorn, and 0.15% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "48.76%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.79%" >}}
3. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "6.83%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.58%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.47%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.34%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.29%" >}}
8. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "2.29%" >}}
9. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.89%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.74%" >}}
---

### 12. [Podroll](https://podroll.fm/)

Podroll was found on 0.12% of new episodes in December, shrinking 0.80% from last month.

Of these, 19.53% had 3 other trackers, 19.38% had 2 other trackers, 18.45% had 4 other trackers, 11.61% had one other tracker, 3.84% had 5 other trackers, 1.92% had 7 other trackers, 1.43% had 6 other trackers, 0.39% had 8 other trackers, and 0.15% had 9 other trackers.

64.04% also included Chartable, 45.65% also included Podtrac, 38.81% also included Podsights, 18.30% also included Magellan AI, 17.02% also included Podscribe, 14.41% also included Adswizz, 11.02% also included Podder, 4.03% also included Gumshoe, 3.49% also included Claritas, 2.95% also included OP3, 2.85% also included Podcorn, 2.71% also included Voxalyze, 1.43% also included ArtsAI, 0.79% also included Spotify, 0.69% also included Blubrry, and 0.20% also included CoHost Prefix.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "42.65%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "17.81%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.41%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "11.31%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "5.41%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.59%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.72%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.52%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.52%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.18%" >}}
---

### 13. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.12% of new episodes in December, shrinking 0.62% from last month.

Of these, 27.56% had 6 other trackers, 19.12% had 3 other trackers, 15.69% had 4 other trackers, 15.49% had 2 other trackers, 11.97% had 5 other trackers, 6.95% had 7 other trackers, and 2.38% had one other tracker.

78.30% also included Podsights, 75.37% also included Chartable, 73.49% also included Podscribe, 69.27% also included Podtrac, 32.92% also included Magellan AI, 30.34% also included Claritas, 26.07% also included Veritonic, 18.77% also included Adswizz, 10.33% also included Spotify, 7.30% also included Audiotakes, 2.09% also included Podder, 1.59% also included Gumshoe, 1.44% also included Podroll, and 0.05% also included Blubrry.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "31.88%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "22.29%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "13.60%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.43%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "8.79%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.64%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.28%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.39%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.09%" >}}
10. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.20%" >}}
---

### 14. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.12% of new episodes in December, growing 10.42% from last month.

Of these, 27.31% had one other tracker, 25.65% had 2 other trackers, 22.79% had 3 other trackers, 9.96% had 4 other trackers, 4.07% had 6 other trackers, 4.02% had 7 other trackers, and 2.57% had 5 other trackers.

64.29% also included Chartable, 49.85% also included Podscribe, 33.50% also included Podtrac, 30.08% also included Podsights, 17.51% also included Magellan AI, 16.95% also included Claritas, 11.07% also included Gumshoe, 10.46% also included ArtsAI, 7.14% also included Adswizz, 4.28% also included Audiotakes, 3.12% also included Veritonic, 1.56% also included OP3, 1.26% also included Podcorn, 0.80% also included Podroll, and 0.40% also included Podder.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "28.17%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "19.77%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "13.13%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.81%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.39%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.14%" >}}
7. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "5.33%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.48%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.52%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.36%" >}}
---

### 15. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.11% of new episodes in December, shrinking 10.97% from last month.

Of these, 26.79% had one other tracker, 13.66% had 5 other trackers, 13.19% had 2 other trackers, 11.11% had 4 other trackers, 3.84% had 3 other trackers, 1.66% had 6 other trackers, 0.42% had 8 other trackers, 0.36% had 7 other trackers, and 0.16% had 9 other trackers.

56.28% also included Podtrac, 28.50% also included Podsights, 27.67% also included Podcorn, 27.47% also included Chartable, 25.96% also included Gumshoe, 12.72% also included Podscribe, 4.15% also included Adswizz, 4.15% also included Podder, 3.12% also included Podroll, 2.02% also included Voxalyze, 1.61% also included Spotify, 0.78% also included Blubrry, and 0.21% also included Feedpress.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "38.32%" >}}
2. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "13.66%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.61%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.53%" >}}
5. {{< a "https://letscast.fm/" "LetsCast.fm" >}} {{< span "weak" "3.27%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.17%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.12%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.12%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.60%" >}}
10. {{< a "https://podnews.net/" "Podnews" >}} {{< span "weak" "2.08%" >}}
---

### 16. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.11% of new episodes in December, shrinking 2.38% from last month.

Of these, 26.59% had 4 other trackers, 19.35% had 6 other trackers, 17.65% had 5 other trackers, 14.64% had 3 other trackers, 7.89% had 7 other trackers, 7.24% had 2 other trackers, and 4.66% had one other tracker.

83.06% also included Podscribe, 73.90% also included Chartable, 73.30% also included Podsights, 54.00% also included Podtrac, 48.68% also included Magellan AI, 33.50% also included ArtsAI, 19.41% also included Adswizz, 18.48% also included Spotify, 15.63% also included Veritonic, 4.82% also included Podder, 3.89% also included Podroll, 0.22% also included Gumshoe, and 0.16% also included Blubrry.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "42.16%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "22.09%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "13.38%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.27%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "7.68%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.45%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.54%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.27%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.16%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.09% of new episodes in December, shrinking 10.81% from last month.

Of these, 19.57% had 4 other trackers, 18.48% had 5 other trackers, 18.14% had 2 other trackers, 13.34% had 3 other trackers, 10.97% had one other tracker, 4.27% had 6 other trackers, 1.69% had 7 other trackers, 0.54% had 8 other trackers, and 0.20% had 9 other trackers.

57.96% also included Podsights, 52.81% also included Podtrac, 49.83% also included Chartable, 40.08% also included Podcorn, 33.85% also included OP3, 30.81% also included Podscribe, 14.90% also included Spotify, 5.55% also included Podroll, 3.86% also included Podder, 3.52% also included Magellan AI, 3.39% also included Audiotakes, 2.17% also included ArtsAI, 1.22% also included Voxalyze, 1.02% also included Adswizz, 0.27% also included Claritas, 0.20% also included Veritonic, and 0.14% also included Blubrry.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "34.39%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.47%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "23.90%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.77%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.35%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.15%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.61%" >}}
8. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.34%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.27%" >}}
10. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.27%" >}}
---

### 18. [Firstory](https://firstory.me/)

Firstory was found on 0.08% of new episodes in December, growing 6.00% from last month.

Of these, 68.77% had one other tracker, and 0.21% had 2 other trackers.

68.98% also included Chartable, and 0.21% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.57%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.43%" >}}
---

### 19. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.06% of new episodes in December, growing 15.73% from last month.

Of these, 46.73% had one other tracker, 15.82% had 4 other trackers, 15.27% had 2 other trackers, 13.62% had 3 other trackers, 4.14% had 5 other trackers, 3.13% had 6 other trackers, and 0.18% had 7 other trackers.

51.24% also included Podscribe, 45.54% also included Adswizz, 45.17% also included Podsights, 23.55% also included Chartable, 13.52% also included ArtsAI, 12.60% also included Podtrac, 12.05% also included Magellan AI, 7.82% also included Spotify, 5.98% also included Veritonic, 4.60% also included Gumshoe, and 0.09% also included Blubrry.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "22.82%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "17.30%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.74%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.86%" >}}
5. {{< a "https://kostenlos-hosten.de/" "Podcastbude" >}} {{< span "weak" "1.75%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.75%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.74%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.46%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.28%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.18%" >}}
---

### 20. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.06% of new episodes in December, shrinking 9.81% from last month.

Of these, 53.23% had 6 other trackers, 12.90% had 4 other trackers, 11.83% had 5 other trackers, 6.88% had 3 other trackers, 6.56% had 7 other trackers, 4.09% had 2 other trackers, and 3.55% had one other tracker.

84.95% also included Podsights, 83.66% also included Podtrac, 83.55% also included Podscribe, 78.49% also included Chartable, 56.45% also included ArtsAI, 48.92% also included Magellan AI, 30.65% also included Claritas, 25.38% also included Adswizz, 6.99% also included Audiotakes, 6.67% also included Spotify, 2.26% also included Podder, 0.32% also included Gumshoe, and 0.11% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "52.80%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "23.12%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "13.01%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.70%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.69%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.83%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.43%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.32%" >}}
---

### 21. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on 0.03% of new episodes in December, shrinking 1.44% from last month.

Of these, 26.40% had one other tracker, 20.81% had 2 other trackers, 13.87% had 3 other trackers, 5.78% had 4 other trackers, 1.54% had 8 other trackers, 0.77% had 6 other trackers, 0.58% had 9 other trackers, and 0.19% had 5 other trackers.

55.30% also included Chartable, 28.32% also included Podcorn, 25.24% also included Podtrac, 22.16% also included Podsights, 10.60% also included Podroll, 7.51% also included OP3, 3.47% also included Gumshoe, 2.50% also included Podder, 0.58% also included Podscribe, and 0.19% also included Blubrry.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "18.11%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "16.18%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "15.61%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "12.33%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "10.98%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.44%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "8.67%" >}}
8. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "3.08%" >}}
9. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "1.35%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.96%" >}}
---

### 22. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in December, shrinking 10.01% from last month.

Of these, 39.80% had one other tracker, 11.22% had 2 other trackers, and 2.04% had 3 other trackers.

36.73% also included Chartable, 16.33% also included Podtrac, 6.63% also included Podcorn, 5.61% also included Podsights, and 3.06% also included Adswizz.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "100.00%" >}}
---

### 23. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in December, shrinking 2.47% from last month.

Of these, 33.88% had one other tracker, 3.31% had 2 other trackers, and 3.31% had 5 other trackers.

24.79% also included Chartable, 13.22% also included Podtrac, 9.09% also included Podcorn, 6.61% also included Podsights, and 3.31% also included Podder.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "42.15%" >}}
2. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "12.40%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "9.92%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "8.26%" >}}
5. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "6.61%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.79%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.13%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.31%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.31%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.83%" >}}
---

### 24. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in December, shrinking 4.51% from last month.

Of these, 50.00% had one other tracker, and 20.93% had 2 other trackers.

67.44% also included Chartable, 17.44% also included Podtrac, and 6.98% also included Podcorn.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "39.53%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "19.77%" >}}
3. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "15.12%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "13.95%" >}}
5. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "5.81%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.49%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.33%" >}}
---

### 25. [Zippycast](https://zippycast.io/)

Zippycast was found on <0.01% of new episodes in December, growing 1.31% from last month.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "81.48%" >}}
2. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "18.52%" >}}
---

### 26. [Glystn](https://glystn.com/)

Glystn was found on <0.01% of new episodes in December, growing 0.44% from last month.

Of these, 66.67% had 3 other trackers, and 33.33% had one other tracker.

100.00% also included Chartable, 66.67% also included Podtrac, and 66.67% also included Podsights.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "66.67%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "33.33%" >}}
---

### 27. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on <0.01% of new episodes in December, shrinking 0.26% from last month.

Of these, 90.91% had 3 other trackers.

90.91% also included Chartable, 72.73% also included Podtrac, 36.36% also included Podsights, 36.36% also included Podroll, 18.18% also included Podcorn, and 18.18% also included Podder.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "36.36%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "36.36%" >}}
3. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "18.18%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.09%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2023-12.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
