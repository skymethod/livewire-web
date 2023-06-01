---
title: "Top Podcast Tracking Services by Episode Share (April 2023)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-april-2023"
images:
- trackers-2023-04.png
date: 2023-05-04T18:26:00-05:00
lastmod: 2023-05-04T18:26:00-05:00
draft: false
rssrevision: 2023-04
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.7 million in April 2023), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in April, how many
of them included one or more of these tracking services?  Some episodes had as many as *eight* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Chartable	Adswizz	Podcorn	Podsights	Blubrry	Médiamétrie	Podscribe	Feedpress	Podder	ArtsAI	OP3	Gumshoe	Claritas	Podroll	Veritonic	Zippycast	Zencastr	Glystn	Podkite	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.00	2.09	1.16	2.07	0.42		0.32														1.61
Oct 2021	4.05	4.09	1.01	2.13	1.20	2.11	0.54		0.34														1.61
Nov 2021	4.07	4.30	1.02	2.14	1.25	2.01	0.57		0.32														0.59
Dec 2021	4.06	4.42	1.24	2.27	1.19	1.57	0.59		0.19														
Jan 2022	4.11	4.45	1.41	2.31	1.21	1.56	0.63		0.16														
Feb 2022	4.15	4.48	1.44	2.38	1.25	1.53	0.58		0.17														
Mar 2022	4.37	4.72	1.51	2.40	1.34	1.56	0.53		0.17														
Apr 2022	4.44	4.71	1.49	2.33	1.33	1.55	0.51		0.16														
May 2022	4.49	4.87	1.58	2.26	1.41	1.48	0.56		0.17														
Jun 2022	4.75	5.10	1.77	2.06	1.54	1.50	0.62		0.21								0.02						
Jul 2022	4.70	5.10	1.89	2.16	1.50	1.50	0.54		0.25								0.02						
Aug 2022	4.83	5.26	2.08	2.45	1.73	1.51	0.41		0.20		0.10						0.01						
Sep 2022	7.53	5.40	2.26	2.45	1.74	1.49	0.52	0.02	0.21		0.09			0.01			0.02			0.01	0.02		
Oct 2022	8.24	5.48	2.35	2.51	1.81	1.61	0.50	0.07	0.18		0.10	0.03		0.02			0.02	0.01		0.01	0.04		
Nov 2022	8.11	5.62	2.37	2.43	2.03	1.62	0.50	0.15	0.18	0.01	0.10	0.04		0.03			0.02	0.01		0.01	0.05		
Dec 2022	8.01	5.54	2.32	2.05	1.81	1.61	0.49	0.03	0.18	0.04	0.05	0.05		0.02			0.02	0.01	0.01	0.01	0.05		
Jan 2023	7.85	5.56	2.35	2.15	1.88	1.61	0.54	0.20	0.18	0.11	0.10	0.07		0.06			0.02	0.01	0.01	0.01	0.06		
Feb 2023	7.58	5.51	2.29	2.30	1.92	1.62	0.49	0.21	0.19	0.11	0.10	0.07		0.07			0.02	0.01	0.01	0.01	0.06	0.03	
Mar 2023	7.79	5.53	2.25	2.22	2.03	1.53	0.45	0.21	0.18	0.11	0.11	0.08		0.07	0.04	0.04	0.02	0.01	0.01	0.01	0.06		
Apr 2023	7.66	5.43	2.26	2.20	2.00	1.67	0.45	0.21	0.17	0.15	0.11	0.09	0.08	0.07	0.06	0.05	0.01	0.01	0.01	0.01			
{{< /graph >}}

---

### Overall

At least one tracker was found on 16.88% of new episodes in April, shrinking 1.00% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "22.06%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.26%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.99%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "8.00%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.02%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.99%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.69%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.50%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.42%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.13%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of April 2023.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 7.66% of new episodes in April, shrinking 1.67% from last month.

Of these, 22.28% had one other tracker, 11.41% had 2 other trackers, 1.84% had 3 other trackers, 1.05% had 4 other trackers, 0.56% had 5 other trackers, 0.19% had 6 other trackers, and 0.17% had 7 other trackers.

29.27% also included Chartable, 14.13% also included Podsights, 6.22% also included Adswizz, 1.98% also included Podcorn, 1.43% also included Podscribe, 1.41% also included Podder, 1.05% also included ArtsAI, 0.78% also included OP3, 0.71% also included Gumshoe, 0.69% also included Claritas, 0.64% also included Blubrry, 0.54% also included Veritonic, 0.48% also included Magellan AI, 0.15% also included Feedpress, 0.11% also included Podroll, 0.11% also included Glystn, 0.10% also included Backtracks, 0.05% also included Médiamétrie, 0.05% also included Voxalyze, 0.03% also included AdBarker, 0.02% also included Zippycast, 0.02% also included Podkite, 0.01% also included Zencastr, and <0.01% also included Firstory.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "47.76%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "16.53%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.62%" >}}
4. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "3.14%" >}}
5. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.52%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.50%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.80%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.65%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.45%" >}}
10. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "1.44%" >}}
---

### [Spotify (Chartable & Podsights)](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/)

At least one Spotify tracker was found on 6.01% of new episodes in April, shrinking 3.16% from last month.

Of these, 39.69% also included Podtrac, 7.34% also included Adswizz, 4.58% also included Podcorn, 3.19% also included Podscribe, 2.22% also included Podder, 1.73% also included ArtsAI, 1.16% also included Claritas, 1.11% also included Gumshoe, 1.03% also included OP3, 1.03% also included Magellan AI, 0.89% also included Firstory, 0.76% also included Veritonic, 0.73% also included Podroll, 0.39% also included Blubrry, 0.14% also included Glystn, 0.07% also included AdBarker, 0.06% also included Feedpress, 0.05% also included Zencastr, 0.04% also included Voxalyze, 0.03% also included Zippycast, 0.03% also included Podkite, and 0.02% also included Backtracks.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.43%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "23.25%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.03%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.19%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.50%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.07%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.98%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.48%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.30%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.23%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.43% of new episodes in April, shrinking 1.74% from last month.

Of these, 35.64% had one other tracker, 17.15% had 2 other trackers, 2.95% had 3 other trackers, 1.05% had 4 other trackers, 0.81% had 5 other trackers, 0.27% had 6 other trackers, and 0.24% had 7 other trackers.

41.26% also included Podtrac, 26.12% also included Podsights, 5.77% also included Adswizz, 4.00% also included Podcorn, 3.05% also included Podscribe, 2.06% also included Podder, 1.72% also included ArtsAI, 1.19% also included Claritas, 1.09% also included Magellan AI, 0.98% also included Firstory, 0.73% also included Veritonic, 0.72% also included Podroll, 0.44% also included Gumshoe, 0.37% also included OP3, 0.37% also included Blubrry, 0.16% also included Glystn, 0.08% also included AdBarker, 0.07% also included Feedpress, 0.04% also included Voxalyze, 0.04% also included Zencastr, 0.03% also included Podkite, 0.02% also included Backtracks, and <0.01% also included Zippycast.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.57%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.56%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.31%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.30%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.85%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.32%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.67%" >}}
8. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.55%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.45%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.31%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.26% of new episodes in April, growing 0.26% from last month.

Of these, 32.08% had one other tracker, 3.86% had 2 other trackers, 2.15% had 3 other trackers, 0.56% had 5 other trackers, 0.55% had 7 other trackers, 0.35% had 6 other trackers, and 0.32% had 4 other trackers.

21.10% also included Podtrac, 13.89% also included Chartable, 11.51% also included Podsights, 4.00% also included Blubrry, 1.43% also included Podscribe, 1.41% also included ArtsAI, 1.23% also included Claritas, 0.55% also included Magellan AI, 0.51% also included Podroll, 0.47% also included Veritonic, 0.13% also included Podcorn, 0.03% also included Podder, 0.01% also included OP3, and <0.01% also included Gumshoe.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "29.46%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "18.10%" >}}
3. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "8.98%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "8.65%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.32%" >}}
6. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "5.66%" >}}
7. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "5.44%" >}}
8. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.71%" >}}
9. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.52%" >}}
10. {{< a "https://www.bbc.co.uk/" "BBC" >}} {{< span "weak" "1.38%" >}}
---

### 4. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 2.20% of new episodes in April, shrinking 1.07% from last month.

Of these, 10.67% had one other tracker, 2.06% had 2 other trackers, 1.80% had 4 other trackers, 0.68% had 3 other trackers, 0.48% had 5 other trackers, 0.02% had 6 other trackers, and 0.02% had 7 other trackers.

9.89% also included Chartable, 6.91% also included Podtrac, 3.75% also included Podsights, 2.33% also included OP3, 2.32% also included Gumshoe, 0.48% also included Podder, 0.26% also included Blubrry, 0.14% also included Adswizz, 0.11% also included AdBarker, 0.09% also included Zencastr, 0.09% also included Podroll, 0.09% also included Voxalyze, 0.08% also included Backtracks, 0.08% also included Feedpress, 0.05% also included Podkite, 0.02% also included Magellan AI, and 0.02% also included Podscribe.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "53.40%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "19.11%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "6.64%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.64%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.75%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.22%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.11%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.65%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.99%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.82%" >}}
---

### 5. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.00% of new episodes in April, shrinking 1.18% from last month.

Of these, 41.36% had 2 other trackers, 28.92% had one other tracker, 8.04% had 3 other trackers, 4.51% had 4 other trackers, 2.38% had 5 other trackers, 0.74% had 6 other trackers, and 0.64% had 7 other trackers.

70.87% also included Chartable, 54.07% also included Podtrac, 12.97% also included Adswizz, 8.03% also included Podscribe, 4.65% also included Podder, 4.33% also included ArtsAI, 4.11% also included Podcorn, 3.24% also included Claritas, 3.09% also included Gumshoe, 2.74% also included Magellan AI, 2.61% also included OP3, 2.12% also included Veritonic, 1.25% also included Podroll, 0.21% also included Blubrry, 0.10% also included Zencastr, 0.09% also included Zippycast, 0.09% also included Voxalyze, 0.05% also included Podkite, 0.01% also included AdBarker, and <0.01% also included Backtracks.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "41.48%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "36.80%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.74%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.62%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.31%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.12%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.74%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.13%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.09%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.02%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.67% of new episodes in April, growing 8.52% from last month.

Of these, 9.42% had one other tracker, 0.56% had 2 other trackers, 0.06% had 3 other trackers, 0.04% had 5 other trackers, 0.04% had 4 other trackers, and <0.01% had 6 other trackers.

5.42% also included Adswizz, 2.95% also included Podtrac, 1.22% also included Chartable, 0.72% also included Feedpress, 0.34% also included Podcorn, 0.25% also included Podsights, 0.09% also included Podder, 0.08% also included OP3, 0.02% also included AdBarker, 0.01% also included Podscribe, 0.01% also included Zencastr, <0.01% also included Podroll, <0.01% also included Magellan AI, and <0.01% also included ArtsAI.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "40.47%" >}}
2. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "5.75%" >}}
3. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "4.86%" >}}
4. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "4.79%" >}}
5. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.19%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.39%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.73%" >}}
8. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.33%" >}}
9. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.25%" >}}
10. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.16%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.45% of new episodes in April, shrinking 0.17% from last month.

Of these, 0.94% had one other tracker.

0.94% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "38.57%" >}}
2. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "32.70%" >}}
3. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "11.68%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "10.64%" >}}
5. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "5.23%" >}}
6. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "0.79%" >}}
---

### 8. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.21% of new episodes in April, shrinking 0.99% from last month.

Of these, 18.95% had 3 other trackers, 18.87% had 4 other trackers, 16.36% had 5 other trackers, 13.99% had one other tracker, 11.14% had 2 other trackers, 6.81% had 6 other trackers, and 5.91% had 7 other trackers.

78.66% also included Chartable, 76.34% also included Podsights, 51.89% also included Podtrac, 35.53% also included ArtsAI, 28.40% also included Claritas, 18.84% also included Magellan AI, 17.97% also included Veritonic, 15.27% also included Adswizz, 6.59% also included Podroll, 2.12% also included Podder, 0.38% also included OP3, 0.33% also included Gumshoe, 0.22% also included Podcorn, and 0.05% also included Blubrry.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "48.57%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.36%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.37%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.59%" >}}
5. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "5.91%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.59%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.16%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.90%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.49%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.44%" >}}
---

### 9. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.17% of new episodes in April, shrinking 5.85% from last month.

Of these, 13.97% had one other tracker, and 1.27% had 2 other trackers.

6.94% also included Blubrry, 6.50% also included Podtrac, 2.10% also included Chartable, and 0.97% also included Podcorn.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "46.18%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.57%" >}}
3. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "9.50%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.40%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.67%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.63%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.97%" >}}
8. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.80%" >}}
9. {{< a "https://www.subsplash.com/" "Subsplash" >}} {{< span "weak" "0.97%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.97%" >}}
---

### 10. [Podder](https://www.podderapp.com/)

Podder was found on 0.15% of new episodes in April, growing 35.22% from last month.

Of these, 43.62% had 2 other trackers, 30.82% had 3 other trackers, 7.78% had 4 other trackers, 6.52% had one other tracker, 2.49% had 5 other trackers, 0.61% had 6 other trackers, and 0.31% had 7 other trackers.

74.89% also included Chartable, 72.25% also included Podtrac, 62.25% also included Podsights, 6.98% also included Podcorn, 5.48% also included Magellan AI, 3.95% also included OP3, 2.99% also included Podscribe, 2.84% also included Gumshoe, 1.00% also included ArtsAI, 0.96% also included Blubrry, 0.46% also included Podkite, 0.46% also included Adswizz, 0.46% also included Claritas, 0.31% also included Veritonic, 0.15% also included Voxalyze, 0.15% also included AdBarker, and 0.04% also included Backtracks.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "78.11%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "7.74%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "4.18%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.68%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.18%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.46%" >}}
7. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.73%" >}}
8. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.65%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.50%" >}}
10. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.46%" >}}
---

### 11. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.11% of new episodes in April, shrinking 2.65% from last month.

Of these, 32.68% had 5 other trackers, 18.33% had 2 other trackers, 16.86% had 3 other trackers, 13.20% had 6 other trackers, 11.84% had 7 other trackers, 3.82% had 4 other trackers, and 2.07% had one other tracker.

88.87% also included Chartable, 82.43% also included Podsights, 76.27% also included Podtrac, 71.19% also included Podscribe, 35.52% also included Claritas, 30.28% also included Adswizz, 30.01% also included Veritonic, 14.02% also included Magellan AI, 1.42% also included Podder, and 0.05% also included Blubrry.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.71%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "24.82%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "12.60%" >}}
4. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "11.84%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "9.33%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.78%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.53%" >}}
8. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.22%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.16%" >}}
---

### 12. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.09% of new episodes in April, growing 7.11% from last month.

Of these, 42.06% had 4 other trackers, 11.26% had 5 other trackers, 8.01% had 2 other trackers, 7.29% had 3 other trackers, 6.32% had one other tracker, 0.52% had 6 other trackers, and 0.52% had 7 other trackers.

67.38% also included Podtrac, 59.31% also included Podsights, 57.94% also included Podcorn, 57.29% also included Gumshoe, 23.11% also included Chartable, 6.71% also included Podder, 1.43% also included Blubrry, 0.91% also included Podscribe, 0.65% also included Podkite, 0.33% also included Magellan AI, 0.26% also included Adswizz, and 0.20% also included Backtracks.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "68.29%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.45%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.13%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.60%" >}}
5. {{< a "https://podnews.net/" "Podnews" >}} {{< span "weak" "2.54%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.69%" >}}
7. {{< a "https://changelog.com/" "Changelog" >}} {{< span "weak" "1.43%" >}}
8. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.43%" >}}
9. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.11%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.91%" >}}
---

### 13. [Firstory](https://firstory.me/)

Firstory was found on 0.08% of new episodes in April, shrinking 2.64% from last month.

Of these, 64.46% had one other tracker, and 0.28% had 2 other trackers.

64.74% also included Chartable, and 0.28% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.17%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.83%" >}}
---

### 14. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.08% of new episodes in April, growing 18.43% from last month.

Of these, 48.48% had 4 other trackers, 18.01% had 2 other trackers, 12.54% had 5 other trackers, 7.29% had 3 other trackers, 4.33% had one other tracker, 0.61% had 6 other trackers, and 0.61% had 7 other trackers.

82.07% also included Podsights, 71.66% also included Podtrac, 67.48% also included Podcorn, 66.87% also included OP3, 31.31% also included Chartable, 5.62% also included Podder, 0.91% also included Podscribe, 0.76% also included Podkite, and 0.08% also included Adswizz.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "68.92%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.93%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "7.75%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.85%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.43%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.90%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.14%" >}}
---

### 15. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.07% of new episodes in April, growing 0.87% from last month.

Of these, 26.20% had 4 other trackers, 17.39% had 7 other trackers, 16.59% had 5 other trackers, 15.46% had 3 other trackers, 15.14% had 6 other trackers, 5.85% had 2 other trackers, and 2.72% had one other tracker.

90.63% also included Podsights, 90.54% also included Chartable, 83.57% also included Podscribe, 73.96% also included Podtrac, 52.16% also included ArtsAI, 38.86% also included Adswizz, 18.67% also included Magellan AI, 11.78% also included Veritonic, and 0.96% also included Podder.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "37.50%" >}}
2. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "17.39%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "15.38%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.66%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "9.70%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.65%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.77%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.96%" >}}
---

### 16. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.07% of new episodes in April, shrinking 2.99% from last month.

Of these, 31.95% had 4 other trackers, 19.27% had 3 other trackers, 17.64% had 7 other trackers, 13.41% had one other tracker, 12.03% had 2 other trackers, 2.60% had 5 other trackers, and 0.81% had 6 other trackers.

83.90% also included Chartable, 77.89% also included Podsights, 56.26% also included Podscribe, 52.60% also included Podtrac, 20.89% also included ArtsAI, 18.94% also included Claritas, 18.78% also included Podroll, 17.64% also included Adswizz, 11.63% also included Podder, 4.72% also included Veritonic, 0.73% also included Podcorn, 0.41% also included OP3, and 0.08% also included Blubrry.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "55.85%" >}}
2. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "17.64%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "10.89%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.29%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.96%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.98%" >}}
7. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.65%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.41%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.33%" >}}
---

### 17. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.07% of new episodes in April, shrinking 5.66% from last month.

Of these, 9.33% had one other tracker, 1.60% had 4 other trackers, 0.92% had 3 other trackers, and 0.34% had 2 other trackers.

11.18% also included Podtrac, 2.52% also included Podcorn, 2.18% also included Podroll, 1.51% also included Voxalyze, 1.34% also included Chartable, 0.25% also included OP3, 0.08% also included Podsights, and 0.08% also included Podder.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://www.rferl.org/" "Radio Free Europe and Radio Liberty" >}} {{< span "weak" "83.28%" >}}
2. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "7.82%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.61%" >}}
4. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.26%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.92%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.50%" >}}
7. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "0.34%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.25%" >}}
9. {{< a "https://www.subsplash.com/" "Subsplash" >}} {{< span "weak" "0.17%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.17%" >}}
---

### 18. [Podroll](https://podroll.fm/)

Podroll was found on 0.06% of new episodes in April, growing 65.28% from last month.

Of these, 57.76% had one other tracker, 22.99% had 4 other trackers, 10.82% had 3 other trackers, and 6.32% had 2 other trackers.

65.52% also included Chartable, 41.86% also included Podsights, 23.18% also included Podscribe, 22.13% also included Magellan AI, 19.25% also included Adswizz, 14.66% also included Podtrac, 3.26% also included Podcorn, 2.49% also included Backtracks, 1.72% also included Voxalyze, 0.67% also included Zencastr, and 0.10% also included Blubrry.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "52.68%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "19.44%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "18.97%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.08%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.49%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.67%" >}}
7. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "0.48%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.19%" >}}
---

### 19. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.05% of new episodes in April, growing 5.34% from last month.

Of these, 51.56% had 5 other trackers, 20.10% had 6 other trackers, 16.73% had 4 other trackers, 4.87% had 3 other trackers, 3.62% had 2 other trackers, and 2.00% had one other tracker.

92.26% also included Podsights, 90.26% also included Podtrac, 86.14% also included Chartable, 82.40% also included Podscribe, 68.66% also included ArtsAI, 22.85% also included Adswizz, 18.35% also included Claritas, 7.24% also included Magellan AI, and 1.00% also included Podder.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "58.68%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "23.72%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.74%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "8.61%" >}}
---

### 20. [Zippycast](https://zippycast.io/)

Zippycast was found on 0.01% of new episodes in April, shrinking 11.88% from last month.

Of these, 12.24% had 2 other trackers, and 2.86% had one other tracker.

13.47% also included Podtrac, 12.24% also included Podsights, and 1.63% also included Chartable.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "29.80%" >}}
2. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "27.35%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "25.71%" >}}
4. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "14.69%" >}}
5. {{< a "https://podcloud.fr/" "podCloud" >}} {{< span "weak" "2.04%" >}}
6. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "0.41%" >}}
---

### 21. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in April, growing 29.74% from last month.

Of these, 37.89% had one other tracker, 7.45% had 2 other trackers, 5.59% had 4 other trackers, and 2.48% had 3 other trackers.

21.74% also included Podcorn, 21.74% also included Podsights, 21.74% also included Chartable, 11.80% also included Podtrac, 4.35% also included Podroll, and 1.24% also included Blubrry.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "35.40%" >}}
2. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "33.54%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "21.12%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.45%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.48%" >}}
---

### 22. [Glystn](https://glystn.com/)

Glystn was found on 0.01% of new episodes in April, growing 2.43% from last month.

Of these, 97.35% had 2 other trackers, and 2.65% had one other tracker.

100.00% also included Chartable, and 97.35% also included Podtrac.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "97.35%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.65%" >}}
---

### 23. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in April, growing 7.18% from last month.

Of these, 60.75% had 2 other trackers, 9.35% had one other tracker, and 4.67% had 5 other trackers.

67.29% also included Chartable, 38.32% also included Podcorn, 35.51% also included Podtrac, 4.67% also included Blubrry, 4.67% also included Podsights, and 3.74% also included Podder.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "37.38%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "23.36%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "16.82%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "7.48%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "6.54%" >}}
6. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "4.67%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.74%" >}}
---

### 24. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in April, shrinking 17.86% from last month.

Of these, 20.95% had one other tracker, 7.62% had 7 other trackers, 5.71% had 5 other trackers, and 3.81% had 2 other trackers.

22.86% also included Chartable, 21.90% also included Podtrac, 18.10% also included Podcorn, 17.14% also included Podsights, 11.43% also included Podder, 9.52% also included OP3, and 9.52% also included Gumshoe.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "27.62%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "18.10%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "15.24%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "12.38%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "7.62%" >}}
6. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "7.62%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.81%" >}}
8. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.90%" >}}
9. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "0.95%" >}}
---

### 25. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on <0.01% of new episodes in April, growing 423.29% from last month.

Of these, 36.14% had 3 other trackers, 26.51% had 4 other trackers, 18.07% had one other tracker, and 8.43% had 2 other trackers.

74.70% also included Podtrac, 50.60% also included Chartable, 39.76% also included Podcorn, 36.14% also included Podsights, 21.69% also included Backtracks, 21.69% also included Podroll, and 4.82% also included Podder.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "44.58%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "25.30%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "13.25%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.43%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "4.82%" >}}
6. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "2.41%" >}}
7. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "1.20%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2023-04.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
