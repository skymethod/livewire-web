---
title: "Top Podcast Tracking Services by Episode Share (July 2023)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-july-2023"
images:
- trackers-2023-07.png
date: 2023-08-01T17:18:00-05:00
lastmod: 2023-08-01T17:18:00-05:00
draft: false
rssrevision: 2023-07
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.7 million in July 2023), 
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
Month	Podtrac	Chartable	Podsights	Adswizz	Blubrry	Podcorn	Médiamétrie	Podscribe	Feedpress	Podder	Podroll	ArtsAI	OP3	Claritas	Gumshoe	Veritonic	Voxalyze	Zencastr	Zippycast	Podkite	Glystn	Spotify	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.16	1.00	2.07	2.09	0.42		0.32																1.61
Oct 2021	4.05	4.09	1.20	1.01	2.11	2.13	0.54		0.34																1.61
Nov 2021	4.07	4.30	1.25	1.02	2.01	2.14	0.57		0.32																0.59
Dec 2021	4.06	4.42	1.19	1.24	1.57	2.27	0.59		0.19																
Jan 2022	4.11	4.45	1.21	1.41	1.56	2.31	0.63		0.16																
Feb 2022	4.15	4.48	1.25	1.44	1.53	2.38	0.58		0.17																
Mar 2022	4.37	4.72	1.34	1.51	1.56	2.40	0.53		0.17																
Apr 2022	4.44	4.71	1.33	1.49	1.55	2.33	0.51		0.16																
May 2022	4.49	4.87	1.41	1.58	1.48	2.26	0.56		0.17																
Jun 2022	4.75	5.10	1.54	1.77	1.50	2.06	0.62		0.21										0.02						
Jul 2022	4.70	5.10	1.50	1.89	1.50	2.16	0.54		0.25										0.02						
Aug 2022	4.83	5.26	1.73	2.08	1.51	2.45	0.41		0.20			0.10							0.01						
Sep 2022	7.53	5.40	1.74	2.26	1.49	2.45	0.52	0.02	0.21			0.09		0.01					0.02	0.01			0.02		
Oct 2022	8.24	5.48	1.81	2.35	1.61	2.51	0.50	0.07	0.18			0.10	0.03	0.02				0.01	0.02	0.01			0.04		
Nov 2022	8.11	5.62	2.03	2.37	1.62	2.43	0.50	0.15	0.18	0.01		0.10	0.04	0.03				0.01	0.02	0.01			0.05		
Dec 2022	8.01	5.54	1.81	2.32	1.61	2.05	0.49	0.03	0.18	0.04		0.05	0.05	0.02				0.01	0.02	0.01	0.01		0.05		
Jan 2023	7.85	5.56	1.88	2.35	1.61	2.15	0.54	0.20	0.18	0.11		0.10	0.07	0.06				0.01	0.02	0.01	0.01		0.06		
Feb 2023	7.58	5.51	1.92	2.29	1.62	2.30	0.49	0.21	0.19	0.11		0.10	0.07	0.07				0.01	0.02	0.01	0.01		0.06	0.03	
Mar 2023	7.79	5.53	2.03	2.25	1.53	2.22	0.45	0.21	0.18	0.11	0.04	0.11	0.08	0.07		0.04		0.01	0.02	0.01	0.01		0.06		
Apr 2023	7.66	5.43	2.00	2.26	1.67	2.20	0.45	0.21	0.17	0.15	0.06	0.11	0.09	0.07	0.08	0.05		0.01	0.01	0.01	0.01				
May 2023	7.58	5.59	2.04	2.27	1.67	2.28	0.45	0.24	0.19	0.15	0.09	0.11	0.09	0.08	0.07	0.05	0.01	0.01	0.01	0.01	0.01				
Jun 2023	8.22	5.83	2.23	2.39	1.64	1.86	0.51	0.26	0.19	0.15	0.10	0.12	0.09	0.07	0.08	0.05	0.01	0.01	0.01	0.01	0.01				
Jul 2023	8.60	5.95	2.52	2.38	1.53	1.17	0.55	0.27	0.18	0.14	0.14	0.11	0.08	0.07	0.06	0.06	0.01	0.01	0.01	0.01	0.01	0.01			
{{< /graph >}}

---

### Overall

At least one tracker was found on 17.43% of new episodes in July, shrinking 0.27% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "23.77%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "14.39%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.51%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.35%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.77%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.57%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.70%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.52%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.42%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.16%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of July 2023.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 8.60% of new episodes in July, growing 4.91% from last month.

Of these, 24.05% had one other tracker, 11.49% had 2 other trackers, 1.78% had 3 other trackers, 0.76% had 4 other trackers, 0.54% had 5 other trackers, 0.15% had 6 other trackers, and 0.05% had 7 other trackers.

29.46% also included Chartable, 15.72% also included Podsights, 5.52% also included Adswizz, 1.48% also included Podcorn, 1.26% also included Podscribe, 1.13% also included Podder, 0.85% also included ArtsAI, 0.79% also included Podroll, 0.52% also included Blubrry, 0.50% also included OP3, 0.50% also included Veritonic, 0.42% also included Claritas, 0.41% also included Gumshoe, 0.40% also included Magellan AI, 0.13% also included Feedpress, 0.07% also included Glystn, 0.07% also included Voxalyze, 0.04% also included Médiamétrie, 0.03% also included Podkite, 0.02% also included AdBarker, 0.01% also included Zencastr, 0.01% also included Spotify, <0.01% also included Firstory, and <0.01% also included Zippycast.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "47.21%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "17.76%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.06%" >}}
4. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.83%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.49%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.48%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.56%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.31%" >}}
9. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "1.25%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.08%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 6.89% of new episodes in July, growing 5.79% from last month.

Of these, 41.51% also included Podtrac, 6.64% also included Adswizz, 3.64% also included Podscribe, 2.06% also included Podcorn, 1.73% also included Podder, 1.63% also included Podroll, 1.55% also included ArtsAI, 0.96% also included Claritas, 0.88% also included Magellan AI, 0.84% also included Firstory, 0.80% also included Veritonic, 0.74% also included Gumshoe, 0.68% also included OP3, 0.30% also included Blubrry, 0.13% also included Voxalyze, 0.10% also included Glystn, 0.09% also included Feedpress, 0.06% also included AdBarker, 0.04% also included Podkite, and 0.04% also included Zencastr.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "32.19%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "24.53%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.17%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.43%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.35%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.13%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.52%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.43%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.34%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.23%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.95% of new episodes in July, growing 2.38% from last month.

Of these, 35.39% had one other tracker, 17.38% had 2 other trackers, 2.75% had 3 other trackers, 1.20% had 4 other trackers, 0.80% had 5 other trackers, 0.22% had 6 other trackers, and 0.07% had 7 other trackers.

42.60% also included Podtrac, 26.61% also included Podsights, 4.72% also included Adswizz, 3.25% also included Podscribe, 1.88% also included Podcorn, 1.63% also included Podder, 1.60% also included Podroll, 1.54% also included ArtsAI, 0.97% also included Firstory, 0.94% also included Magellan AI, 0.85% also included Claritas, 0.75% also included Veritonic, 0.42% also included Gumshoe, 0.41% also included OP3, 0.27% also included Blubrry, 0.15% also included Voxalyze, 0.11% also included Glystn, 0.10% also included Feedpress, 0.07% also included AdBarker, 0.04% also included Podkite, 0.03% also included Zencastr, and 0.02% also included Spotify.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "31.44%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "21.37%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.73%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.91%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.67%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.65%" >}}
7. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.71%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.55%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.49%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.40%" >}}
---

### 3. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.52% of new episodes in July, growing 12.85% from last month.

Of these, 36.77% had one other tracker, 35.71% had 2 other trackers, 6.62% had 3 other trackers, 3.48% had 4 other trackers, 2.07% had 5 other trackers, 0.51% had 6 other trackers, and 0.16% had 7 other trackers.

62.92% also included Chartable, 53.74% also included Podtrac, 10.48% also included Adswizz, 7.87% also included Podscribe, 3.49% also included ArtsAI, 3.48% also included Podder, 2.41% also included Podroll, 2.27% also included Claritas, 2.15% also included Podcorn, 2.04% also included Magellan AI, 1.93% also included Veritonic, 1.78% also included Gumshoe, 1.30% also included OP3, 0.21% also included Voxalyze, 0.20% also included Blubrry, 0.09% also included Feedpress, 0.08% also included Podkite, 0.07% also included Zencastr, and 0.04% also included Spotify.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "47.01%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "36.25%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.64%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.90%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.94%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.89%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.24%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.97%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.90%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.88%" >}}
---

### 4. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.38% of new episodes in July, shrinking 0.83% from last month.

Of these, 30.32% had one other tracker, 2.35% had 2 other trackers, 2.19% had 3 other trackers, 0.69% had 5 other trackers, 0.41% had 6 other trackers, 0.36% had 4 other trackers, and 0.16% had 7 other trackers.

20.01% also included Podtrac, 11.81% also included Chartable, 11.10% also included Podsights, 1.53% also included Blubrry, 1.23% also included ArtsAI, 1.23% also included Podscribe, 0.99% also included Claritas, 0.69% also included Veritonic, 0.57% also included Podroll, 0.20% also included Magellan AI, 0.19% also included Podcorn, 0.15% also included Spotify, 0.15% also included Podder, 0.14% also included OP3, 0.02% also included Gumshoe, and 0.01% also included Feedpress.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "25.30%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "17.78%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "13.65%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "11.65%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "8.79%" >}}
6. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.33%" >}}
7. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "4.28%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "3.33%" >}}
9. {{< a "https://www.bbc.co.uk/" "BBC" >}} {{< span "weak" "1.47%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.35%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.53% of new episodes in July, shrinking 1.57% from last month.

Of these, 6.65% had one other tracker, 0.51% had 2 other trackers, 0.08% had 3 other trackers, and 0.03% had 4 other trackers.

2.94% also included Podtrac, 2.37% also included Adswizz, 1.05% also included Chartable, 0.93% also included Feedpress, 0.33% also included Podsights, 0.26% also included Podcorn, 0.06% also included Podscribe, 0.05% also included OP3, 0.02% also included Podder, 0.01% also included Spotify, <0.01% also included Claritas, and <0.01% also included Podroll.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "42.87%" >}}
2. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "7.49%" >}}
3. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.54%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.05%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.00%" >}}
6. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.76%" >}}
7. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.46%" >}}
8. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.23%" >}}
9. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.20%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.19%" >}}
---

### 6. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 1.17% of new episodes in July, shrinking 36.96% from last month.

Of these, 10.81% had one other tracker, 3.12% had 2 other trackers, 1.68% had 4 other trackers, 1.22% had 3 other trackers, 0.91% had 5 other trackers, 0.04% had 6 other trackers, and 0.03% had 7 other trackers.

10.83% also included Podtrac, 9.55% also included Chartable, 4.61% also included Podsights, 2.53% also included OP3, 2.51% also included Gumshoe, 0.68% also included Podder, 0.37% also included Adswizz, 0.34% also included Blubrry, 0.33% also included Podroll, 0.20% also included Podkite, 0.20% also included Podscribe, 0.14% also included Voxalyze, 0.05% also included Zencastr, 0.04% also included Magellan AI, and 0.02% also included AdBarker.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "39.68%" >}}
2. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "13.22%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.48%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "9.84%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "5.81%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.51%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.90%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.55%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.75%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.42%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.55% of new episodes in July, growing 5.81% from last month.

Of these, 0.59% had one other tracker.

0.59% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "45.18%" >}}
2. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "35.40%" >}}
3. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "7.61%" >}}
4. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "4.89%" >}}
5. {{< a "https://soundcast.fm/" "SoundCast" >}} {{< span "weak" "4.85%" >}}
6. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "1.10%" >}}
7. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "0.66%" >}}
---

### 8. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.27% of new episodes in July, growing 3.70% from last month.

Of these, 20.51% had one other tracker, 18.30% had 2 other trackers, 16.88% had 4 other trackers, 16.46% had 3 other trackers, 15.80% had 5 other trackers, 4.02% had 6 other trackers, and 1.37% had 7 other trackers.

72.69% also included Podsights, 71.05% also included Chartable, 39.78% also included Podtrac, 26.98% also included ArtsAI, 20.71% also included Claritas, 16.69% also included Veritonic, 13.48% also included Magellan AI, 10.70% also included Adswizz, 8.13% also included Podroll, 2.01% also included Spotify, 1.57% also included Podder, 1.28% also included Gumshoe, 0.86% also included Podcorn, 0.49% also included OP3, 0.33% also included Blubrry, and 0.02% also included Podkite.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "42.65%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "21.79%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "9.81%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.01%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.97%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.22%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.96%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.41%" >}}
9. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.33%" >}}
10. {{< a "https://twit.tv/" "TWiT" >}} {{< span "weak" "0.99%" >}}
---

### 9. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.18% of new episodes in July, shrinking 1.95% from last month.

Of these, 13.36% had one other tracker, 2.33% had 2 other trackers, and 0.26% had 3 other trackers.

7.75% also included Blubrry, 6.30% also included Podtrac, 3.28% also included Chartable, 1.28% also included Podsights, 0.13% also included OP3, and 0.07% also included Adswizz.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "47.55%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.42%" >}}
3. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "8.24%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.58%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "3.81%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.38%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.94%" >}}
8. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.41%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.38%" >}}
10. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.85%" >}}
---

### 10. [Podder](https://www.podderapp.com/)

Podder was found on 0.14% of new episodes in July, shrinking 4.52% from last month.

Of these, 33.71% had 3 other trackers, 26.66% had 2 other trackers, 12.01% had one other tracker, 11.29% had 4 other trackers, 3.06% had 5 other trackers, 0.92% had 6 other trackers, and 0.25% had 7 other trackers.

68.05% also included Podtrac, 67.67% also included Chartable, 61.00% also included Podsights, 11.34% also included Podroll, 5.54% also included Podcorn, 5.37% also included Magellan AI, 3.48% also included OP3, 2.98% also included Podscribe, 2.43% also included Adswizz, 2.35% also included Gumshoe, 1.81% also included ArtsAI, 1.18% also included Podkite, 0.46% also included Claritas, 0.34% also included Veritonic, and 0.25% also included Blubrry.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "70.95%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "8.90%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "4.20%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.20%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.36%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.32%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.23%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.13%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.25%" >}}
10. {{< a "https://www.thepodops.com/" "PodOps" >}} {{< span "weak" "0.21%" >}}
---

### 11. [Podroll](https://podroll.fm/)

Podroll was found on 0.14% of new episodes in July, growing 41.52% from last month.

Of these, 38.40% had 2 other trackers, 21.78% had one other tracker, 19.76% had 4 other trackers, 11.88% had 3 other trackers, 0.52% had 6 other trackers, and 0.39% had 5 other trackers.

67.84% also included Chartable, 48.56% also included Podtrac, 43.31% also included Podsights, 15.84% also included Podscribe, 15.07% also included Magellan AI, 11.62% also included Podder, 9.73% also included Adswizz, 2.80% also included Podcorn, 1.29% also included Voxalyze, 0.90% also included ArtsAI, 0.69% also included Gumshoe, 0.22% also included Claritas, 0.22% also included OP3, 0.17% also included Zencastr, and 0.04% also included Blubrry.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "63.88%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "18.34%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.21%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.42%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.25%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.73%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.43%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.26%" >}}
9. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.26%" >}}
10. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "0.17%" >}}
---

### 12. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.11% of new episodes in July, shrinking 6.76% from last month.

Of these, 36.53% had 5 other trackers, 20.38% had 3 other trackers, 19.15% had 2 other trackers, 10.08% had 6 other trackers, 7.74% had 4 other trackers, 3.45% had 7 other trackers, and 1.78% had one other tracker.

84.63% also included Chartable, 81.18% also included Podsights, 67.98% also included Podscribe, 67.76% also included Podtrac, 31.35% also included Veritonic, 27.00% also included Adswizz, 25.67% also included Claritas, 6.07% also included Magellan AI, 4.23% also included Spotify, 2.39% also included Podder, and 1.17% also included Podroll.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.06%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "25.39%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "15.98%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.42%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "10.86%" >}}
6. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "3.34%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.61%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.84%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.28%" >}}
10. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.22%" >}}
---

### 13. [Firstory](https://firstory.me/)

Firstory was found on 0.09% of new episodes in July, growing 6.77% from last month.

Of these, 67.28% had one other tracker, and 0.35% had 2 other trackers.

67.63% also included Chartable, and 0.35% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.58%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.42%" >}}
---

### 14. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.08% of new episodes in July, shrinking 17.88% from last month.

Of these, 25.26% had 4 other trackers, 14.85% had one other tracker, 12.23% had 5 other trackers, 10.56% had 2 other trackers, 8.02% had 3 other trackers, 0.64% had 6 other trackers, and 0.48% had 7 other trackers.

57.19% also included Podtrac, 43.13% also included Podsights, 41.22% also included Gumshoe, 39.16% also included Podcorn, 31.85% also included Chartable, 6.59% also included Podder, 4.29% also included Adswizz, 1.75% also included Podscribe, 1.19% also included Voxalyze, 1.03% also included Blubrry, 0.79% also included Podkite, 0.48% also included Magellan AI, 0.40% also included Podroll, and 0.32% also included Feedpress.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "53.61%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.32%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.69%" >}}
4. {{< a "https://letscast.fm/" "LetsCast.fm" >}} {{< span "weak" "4.45%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.34%" >}}
6. {{< a "https://podnews.net/" "Podnews" >}} {{< span "weak" "3.26%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.18%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.30%" >}}
9. {{< a "https://changelog.com/" "Changelog" >}} {{< span "weak" "1.91%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.91%" >}}
---

### 15. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.07% of new episodes in July, shrinking 11.61% from last month.

Of these, 41.51% had 4 other trackers, 17.49% had one other tracker, 16.90% had 2 other trackers, 11.63% had 3 other trackers, 5.02% had 7 other trackers, 3.51% had 5 other trackers, and 2.09% had 6 other trackers.

77.99% also included Chartable, 71.38% also included Podsights, 51.05% also included Podscribe, 48.03% also included Podtrac, 29.29% also included Podroll, 10.71% also included Podder, 9.12% also included ArtsAI, 6.69% also included Claritas, 6.53% also included Adswizz, 5.10% also included Veritonic, 0.67% also included Podcorn, 0.50% also included OP3, and 0.42% also included Spotify.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "62.34%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "16.32%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.19%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.36%" >}}
5. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "5.02%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.51%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.42%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.75%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.75%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.33%" >}}
---

### 16. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.07% of new episodes in July, shrinking 9.15% from last month.

Of these, 24.73% had 5 other trackers, 20.74% had 4 other trackers, 18.26% had 3 other trackers, 16.49% had 2 other trackers, 10.82% had 6 other trackers, 5.50% had 7 other trackers, and 2.93% had one other tracker.

83.95% also included Podsights, 83.07% also included Podscribe, 74.82% also included Chartable, 52.66% also included Podtrac, 40.87% also included ArtsAI, 34.75% also included Adswizz, 16.76% also included Veritonic, 7.09% also included Magellan AI, 5.23% also included Spotify, 0.98% also included Podder, 0.44% also included Podroll, and 0.09% also included Blubrry.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "28.81%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.55%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "17.20%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "13.83%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "11.35%" >}}
6. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "5.32%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.70%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.15%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.09%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.06% of new episodes in July, shrinking 18.36% from last month.

Of these, 28.82% had 4 other trackers, 22.24% had 2 other trackers, 15.09% had 5 other trackers, 12.96% had one other tracker, 7.93% had 3 other trackers, 0.77% had 6 other trackers, and 0.58% had 7 other trackers.

71.86% also included Podsights, 56.29% also included Podtrac, 50.19% also included OP3, 47.20% also included Podcorn, 40.52% also included Chartable, 5.61% also included Podscribe, 5.42% also included Podder, 1.55% also included Podroll, 0.87% also included Podkite, 0.68% also included Adswizz, and 0.48% also included Veritonic.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "50.10%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "14.31%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "14.12%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "13.06%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.74%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.74%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.16%" >}}
8. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.58%" >}}
9. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.10%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.10%" >}}
---

### 18. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.06% of new episodes in July, growing 6.32% from last month.

Of these, 49.95% had 5 other trackers, 16.93% had 4 other trackers, 14.07% had 6 other trackers, 7.30% had 2 other trackers, 7.30% had 3 other trackers, 1.59% had one other tracker, and 0.21% had 7 other trackers.

85.50% also included Podsights, 79.89% also included Podscribe, 78.20% also included Chartable, 75.56% also included Podtrac, 59.58% also included ArtsAI, 28.68% also included Adswizz, 20.00% also included Claritas, 6.46% also included Magellan AI, 6.24% also included Spotify, 0.85% also included Podder, and 0.53% also included Gumshoe.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "48.15%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "27.30%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "14.18%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.61%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.39%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.06%" >}}
7. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.21%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.11%" >}}
---

### 19. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on 0.01% of new episodes in July, growing 69.39% from last month.

Of these, 26.86% had 3 other trackers, 20.66% had one other tracker, 17.36% had 2 other trackers, and 7.44% had 4 other trackers.

59.92% also included Chartable, 40.50% also included Podtrac, 35.54% also included Podsights, 12.40% also included Podroll, 11.16% also included Podcorn, and 6.20% also included OP3.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "35.54%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "26.45%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "12.40%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.16%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "6.61%" >}}
6. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "2.89%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.65%" >}}
8. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "1.24%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.83%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.83%" >}}
---

### 20. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in July, shrinking 3.32% from last month.

Of these, 27.27% had one other tracker, 8.48% had 2 other trackers, 2.42% had 4 other trackers, and 1.82% had 3 other trackers.

20.00% also included Chartable, 18.79% also included Podsights, 12.73% also included Podtrac, 5.45% also included Podcorn, and 2.42% also included Podroll.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "100.00%" >}}
---

### 21. [Zippycast](https://zippycast.io/)

Zippycast was found on 0.01% of new episodes in July, shrinking 38.95% from last month.

Of these, 1.39% had one other tracker.

1.39% also included Podtrac.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "37.50%" >}}
2. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "25.69%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "20.14%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "6.94%" >}}
5. {{< a "https://podcloud.fr/" "podCloud" >}} {{< span "weak" "5.56%" >}}
6. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "4.17%" >}}
---

### 22. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in July, growing 0.31% from last month.

Of these, 24.60% had one other tracker, 18.25% had 5 other trackers, 4.76% had 7 other trackers, 3.17% had 2 other trackers, 0.79% had 4 other trackers, and 0.79% had 6 other trackers.

34.92% also included Podtrac, 32.54% also included Chartable, 30.95% also included Podcorn, 26.98% also included Podsights, 22.22% also included Podder, 7.94% also included OP3, 7.14% also included Gumshoe, and 0.79% also included Podscribe.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "27.78%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "25.40%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "12.70%" >}}
4. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "6.35%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "6.35%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.56%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.76%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.17%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.17%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.79%" >}}
---

### 23. [Glystn](https://glystn.com/)

Glystn was found on 0.01% of new episodes in July, shrinking 19.94% from last month.

Of these, 96.33% had 2 other trackers, and 3.67% had one other tracker.

100.00% also included Chartable, and 96.33% also included Podtrac.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "96.33%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.67%" >}}
---

### 24. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.01% of new episodes in July, growing 407.25% from last month.

Of these, 71.03% had 5 other trackers, 14.95% had one other tracker, and 7.48% had 2 other trackers.

85.05% also included Podscribe, 71.03% also included ArtsAI, 55.14% also included Claritas, 55.14% also included Veritonic, 55.14% also included Adswizz, 22.43% also included Chartable, 18.69% also included Podtrac, 15.89% also included Podsights, 4.67% also included Magellan AI, and 1.87% also included Blubrry.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "58.88%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "15.89%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "9.35%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.54%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.61%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "1.87%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.87%" >}}
---

### 25. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in July, growing 0.50% from last month.

Of these, 41.51% had one other tracker, and 30.19% had 2 other trackers.

67.92% also included Chartable, 30.19% also included Podtrac, and 3.77% also included Podcorn.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "37.74%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "27.36%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "15.09%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "9.43%" >}}
5. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "3.77%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.83%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.89%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.89%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2023-07.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
