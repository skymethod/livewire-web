---
title: "Top Podcast Tracking Services by Episode Share (February 2023)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-february-2023"
images:
- trackers-2023-02.png
date: 2023-03-01T16:33:00-06:00
lastmod: 2023-03-01T16:33:00-06:00
draft: false
rssrevision: 2023-02
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.6 million in February 2023), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in December, how many
of them included one or more of these tracking services?  Some episodes had as many as *six* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Chartable	Podcorn	Adswizz	Podsights	Blubrry	Médiamétrie	Podscribe	Feedpress	Podder	ArtsAI	OP3	Claritas	Gumball	Vpixl	Zippycast	Podkite	Glystn	Zencastr	FeedBurner
Sep 2021	4.16	4.06	2.09	1.00	1.16	2.07	0.42		0.32											1.61
Oct 2021	4.05	4.09	2.13	1.01	1.20	2.11	0.54		0.34											1.61
Nov 2021	4.07	4.30	2.14	1.02	1.25	2.01	0.57		0.32											0.59
Dec 2021	4.06	4.42	2.27	1.24	1.19	1.57	0.59		0.19											
Jan 2022	4.11	4.45	2.31	1.41	1.21	1.56	0.63		0.16											
Feb 2022	4.15	4.48	2.38	1.44	1.25	1.53	0.58		0.17											
Mar 2022	4.37	4.72	2.40	1.51	1.34	1.56	0.53		0.17											
Apr 2022	4.44	4.71	2.33	1.49	1.33	1.55	0.51		0.16											
May 2022	4.49	4.87	2.26	1.58	1.41	1.48	0.56		0.17											
Jun 2022	4.75	5.10	2.06	1.77	1.54	1.50	0.62		0.21							0.02				
Jul 2022	4.70	5.10	2.16	1.89	1.50	1.50	0.54		0.25							0.02				
Aug 2022	4.83	5.26	2.45	2.08	1.73	1.51	0.41		0.20		0.10					0.01				
Sep 2022	7.53	5.40	2.45	2.26	1.74	1.49	0.52	0.02	0.21		0.09		0.01	0.02		0.02	0.01			
Oct 2022	8.24	5.48	2.51	2.35	1.81	1.61	0.50	0.07	0.18		0.10	0.03	0.02	0.04		0.02	0.01		0.01	
Nov 2022	8.11	5.62	2.43	2.37	2.03	1.62	0.50	0.15	0.18	0.01	0.10	0.04	0.03	0.05		0.02	0.01		0.01	
Dec 2022	8.01	5.54	2.05	2.32	1.81	1.61	0.49	0.03	0.18	0.04	0.05	0.05	0.02	0.05		0.02	0.01	0.01	0.01	
Jan 2023	7.85	5.56	2.15	2.35	1.88	1.61	0.54	0.20	0.18	0.11	0.10	0.07	0.06	0.06		0.02	0.01	0.01	0.01	
Feb 2023	7.58	5.51	2.30	2.29	1.92	1.62	0.49	0.21	0.19	0.11	0.10	0.07	0.07	0.06	0.03	0.02	0.01	0.01	0.01	
{{< /graph >}}

---

### Overall

At least one tracker was found on 17.06% of new episodes in February, shrinking 0.76% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "21.37%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.16%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "8.61%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.39%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.18%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "4.52%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.89%" >}}
8. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.36%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.32%" >}}
10. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.11%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of February 2023.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 7.58% of new episodes in February, shrinking 3.46% from last month.

Of these, 23.19% had one other tracker, 11.44% had 2 other trackers, 1.73% had 3 other trackers, 1.08% had 4 other trackers, 0.56% had 5 other trackers, 0.22% had 6 other trackers, and 0.01% had 7 other trackers.

30.06% also included Chartable, 14.11% also included Podsights, 6.11% also included Adswizz, 2.03% also included Podcorn, 1.53% also included Podscribe, 1.08% also included Podder, 0.99% also included ArtsAI, 0.68% also included Claritas, 0.63% also included Blubrry, 0.60% also included Magellan AI, 0.55% also included OP3, 0.50% also included Gumball, 0.39% also included Vpixl, 0.13% also included Backtracks, 0.12% also included Feedpress, 0.09% also included Glystn, 0.06% also included Médiamétrie, 0.03% also included Zippycast, 0.03% also included Veritonic, 0.02% also included AdBarker, 0.02% also included Podkite, <0.01% also included Zencastr, and <0.01% also included Firstory.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "47.10%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "15.54%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.91%" >}}
4. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "3.05%" >}}
5. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.87%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.73%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.21%" >}}
8. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "1.50%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.47%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.47%" >}}
---

### [Spotify (Chartable & Podsights)](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/)

At least one Spotify tracker was found on 6.16% of new episodes in February, growing 0.01% from last month.

Of these, 39.23% also included Podtrac, 8.12% also included Adswizz, 4.65% also included Podcorn, 3.15% also included Podscribe, 1.63% also included ArtsAI, 1.60% also included Podder, 1.11% also included Claritas, 0.99% also included Magellan AI, 0.91% also included Firstory, 0.85% also included Gumball, 0.80% also included OP3, 0.50% also included Vpixl, 0.42% also included Blubrry, 0.12% also included Glystn, 0.07% also included Backtracks, 0.06% also included AdBarker, 0.06% also included Feedpress, 0.05% also included Podkite, 0.04% also included Veritonic, 0.04% also included Zippycast, and 0.02% also included Zencastr.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "27.38%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "21.38%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.36%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.22%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.59%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.31%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.78%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.71%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.31%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.26%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.51% of new episodes in February, shrinking 0.76% from last month.

Of these, 33.69% had one other tracker, 16.72% had 2 other trackers, 2.70% had 3 other trackers, 1.08% had 4 other trackers, 0.83% had 5 other trackers, 0.30% had 6 other trackers, and 0.02% had 7 other trackers.

41.33% also included Podtrac, 23.07% also included Podsights, 5.35% also included Adswizz, 4.29% also included Podcorn, 3.06% also included Podscribe, 1.65% also included ArtsAI, 1.48% also included Podder, 1.17% also included Claritas, 1.06% also included Magellan AI, 1.01% also included Firstory, 0.54% also included Vpixl, 0.42% also included Blubrry, 0.38% also included Gumball, 0.34% also included OP3, 0.13% also included Glystn, 0.08% also included Backtracks, 0.07% also included AdBarker, 0.06% also included Feedpress, 0.05% also included Podkite, 0.05% also included Veritonic, 0.02% also included Zencastr, and <0.01% also included Zippycast.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "28.40%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "18.04%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.75%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.35%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.98%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.63%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.01%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.55%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.48%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.41%" >}}
---

### 3. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 2.30% of new episodes in February, growing 7.25% from last month.

Of these, 11.03% had one other tracker, 2.39% had 2 other trackers, 1.21% had 4 other trackers, 0.71% had 3 other trackers, 0.32% had 5 other trackers, 0.02% had 6 other trackers, and 0.02% had 7 other trackers.

10.28% also included Chartable, 6.70% also included Podtrac, 3.21% also included Podsights, 1.63% also included OP3, 1.63% also included Gumball, 0.36% also included Blubrry, 0.34% also included Podder, 0.13% also included Podscribe, 0.10% also included AdBarker, 0.10% also included Adswizz, 0.09% also included Backtracks, 0.05% also included Podkite, 0.02% also included Zencastr, and 0.02% also included Magellan AI.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "56.01%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "15.56%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "6.48%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.70%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.65%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.08%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.24%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.14%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.08%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.90%" >}}
---

### 4. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.29% of new episodes in February, shrinking 2.46% from last month.

Of these, 31.24% had one other tracker, 4.03% had 2 other trackers, 2.32% had 3 other trackers, 0.76% had 5 other trackers, 0.27% had 4 other trackers, 0.08% had 6 other trackers, and 0.02% had 7 other trackers.

20.23% also included Podtrac, 14.51% also included Podsights, 12.88% also included Chartable, 1.59% also included Blubrry, 0.90% also included ArtsAI, 0.76% also included Claritas, 0.71% also included Podscribe, 0.10% also included Podcorn, 0.03% also included Podder, 0.02% also included Magellan AI, 0.02% also included Gumball, 0.01% also included Vpixl, 0.01% also included OP3, <0.01% also included Podkite, and <0.01% also included Veritonic.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "29.93%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "17.60%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.37%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "9.00%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "8.26%" >}}
6. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "5.58%" >}}
7. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.80%" >}}
8. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "2.57%" >}}
9. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.71%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.60%" >}}
---

### 5. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.92% of new episodes in February, growing 2.09% from last month.

Of these, 42.51% had 2 other trackers, 28.73% had one other tracker, 7.80% had 3 other trackers, 4.12% had 4 other trackers, 2.46% had 5 other trackers, 0.86% had 6 other trackers, and 0.05% had 7 other trackers.

66.38% also included Chartable, 55.83% also included Podtrac, 17.34% also included Adswizz, 8.03% also included Podscribe, 4.29% also included ArtsAI, 3.85% also included Podcorn, 3.25% also included Podder, 3.21% also included Claritas, 2.62% also included Magellan AI, 2.48% also included Gumball, 2.04% also included OP3, 1.54% also included Vpixl, 0.21% also included Blubrry, 0.13% also included Zippycast, 0.10% also included Backtracks, 0.07% also included Zencastr, 0.07% also included Podkite, 0.02% also included AdBarker, and 0.01% also included Veritonic.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "40.37%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "36.49%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.02%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.93%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.02%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.23%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.93%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.22%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.21%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.12%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.62% of new episodes in February, growing 0.57% from last month.

Of these, 6.66% had one other tracker, 0.55% had 2 other trackers, 0.07% had 3 other trackers, 0.07% had 4 other trackers, and 0.02% had 5 other trackers.

2.97% also included Podtrac, 2.25% also included Adswizz, 1.42% also included Chartable, 0.80% also included Feedpress, 0.52% also included Podcorn, 0.25% also included Podsights, 0.07% also included OP3, 0.05% also included Podder, 0.02% also included AdBarker, and 0.01% also included Zencastr.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "47.55%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.64%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.32%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.04%" >}}
5. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "2.04%" >}}
6. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "1.79%" >}}
7. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.54%" >}}
8. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.25%" >}}
9. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.21%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "0.84%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.49% of new episodes in February, shrinking 9.56% from last month.

Of these, 0.95% had one other tracker.

0.95% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "36.69%" >}}
2. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "33.46%" >}}
3. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "11.90%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "10.10%" >}}
5. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "6.67%" >}}
6. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "0.79%" >}}
---

### 8. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.21% of new episodes in February, growing 5.43% from last month.

Of these, 21.01% had 4 other trackers, 17.73% had 3 other trackers, 17.49% had one other tracker, 15.08% had 5 other trackers, 12.32% had 2 other trackers, 7.41% had 6 other trackers, and 0.23% had 7 other trackers.

78.67% also included Chartable, 71.64% also included Podsights, 54.11% also included Podtrac, 31.04% also included ArtsAI, 23.42% also included Claritas, 16.39% also included Magellan AI, 13.95% also included Vpixl, 7.59% also included Adswizz, 1.39% also included Podcorn, 0.93% also included Podder, 0.73% also included Veritonic, 0.67% also included OP3, and 0.35% also included Gumball.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "50.16%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "24.93%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "11.65%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.81%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.56%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.03%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.92%" >}}
8. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "0.23%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.23%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.17%" >}}
---

### 9. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.19% of new episodes in February, growing 6.56% from last month.

Of these, 11.60% had one other tracker, and 0.89% had 2 other trackers.

6.80% also included Blubrry, 4.77% also included Podtrac, and 1.81% also included Chartable.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "47.27%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "10.06%" >}}
3. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "8.84%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.56%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.64%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.76%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.84%" >}}
8. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "1.31%" >}}
9. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.28%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.08%" >}}
---

### 10. [Podder](https://www.podderapp.com/)

Podder was found on 0.11% of new episodes in February, shrinking 4.11% from last month.

Of these, 38.27% had 2 other trackers, 31.01% had 3 other trackers, 11.32% had one other tracker, 9.47% had 4 other trackers, 1.86% had 5 other trackers, 1.10% had 6 other trackers, and 0.46% had 7 other trackers.

76.13% also included Chartable, 76.02% also included Podtrac, 57.90% also included Podsights, 8.48% also included Magellan AI, 7.20% also included Podcorn, 3.43% also included OP3, 2.61% also included Gumball, 1.86% also included Podscribe, 0.87% also included Claritas, 0.70% also included Blubrry, 0.70% also included Podkite, 0.64% also included Adswizz, 0.64% also included ArtsAI, 0.58% also included Vpixl, 0.12% also included AdBarker, and 0.06% also included Backtracks.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "78.34%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "10.16%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "4.65%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.45%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.16%" >}}
6. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.81%" >}}
7. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.70%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.58%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.46%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.29%" >}}
---

### 11. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.10% of new episodes in February, growing 1.89% from last month.

Of these, 37.80% had 5 other trackers, 20.86% had 2 other trackers, 15.41% had 3 other trackers, 14.98% had 6 other trackers, 5.99% had 4 other trackers, 3.30% had one other tracker, and 0.49% had 7 other trackers.

88.99% also included Chartable, 80.61% also included Podsights, 73.76% also included Podtrac, 65.32% also included Podscribe, 32.11% also included Claritas, 26.54% also included Vpixl, 20.12% also included Adswizz, 9.42% also included Magellan AI, and 0.67% also included Podder.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "32.66%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "31.38%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "14.37%" >}}
4. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "9.42%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.87%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.63%" >}}
7. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "0.49%" >}}
8. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.18%" >}}
---

### 12. [Firstory](https://firstory.me/)

Firstory was found on 0.08% of new episodes in February, shrinking 4.18% from last month.

Of these, 66.69% had one other tracker, and 0.30% had 2 other trackers.

66.99% also included Chartable, and 0.30% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.40%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.60%" >}}
---

### 13. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.08% of new episodes in February, growing 18.32% from last month.

Of these, 11.18% had one other tracker, 2.20% had 2 other trackers, 2.05% had 3 other trackers, and 0.39% had 4 other trackers.

12.44% also included Podtrac, 5.67% also included Chartable, 2.68% also included Podcorn, 2.44% also included Podsights, and 0.08% also included Podder.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://www.rferl.org/" "Radio Free Europe and Radio Liberty" >}} {{< span "weak" "80.08%" >}}
2. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "7.17%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.33%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.52%" >}}
5. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "1.50%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.26%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.63%" >}}
8. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "0.39%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.24%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.16%" >}}
---

### 14. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.07% of new episodes in February, growing 8.07% from last month.

Of these, 32.68% had 4 other trackers, 12.45% had 3 other trackers, 9.23% had 5 other trackers, 8.21% had 2 other trackers, 7.11% had one other tracker, 0.76% had 6 other trackers, and 0.68% had 7 other trackers.

56.39% also included Podtrac, 53.01% also included Podsights, 51.14% also included Gumball, 51.06% also included Podcorn, 25.49% also included Chartable, 5.00% also included Podder, 1.95% also included Podscribe, 1.52% also included Blubrry, 1.02% also included Podkite, 0.34% also included Magellan AI, and 0.17% also included Adswizz.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "67.65%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "4.49%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.32%" >}}
4. {{< a "https://podnews.net/" "Podnews" >}} {{< span "weak" "3.39%" >}}
5. {{< a "https://changelog.com/" "Changelog" >}} {{< span "weak" "2.03%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.86%" >}}
7. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "1.10%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.02%" >}}
9. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "0.76%" >}}
10. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.51%" >}}
---

### 15. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.07% of new episodes in February, growing 8.14% from last month.

Of these, 28.77% had 4 other trackers, 23.14% had 6 other trackers, 19.15% had 5 other trackers, 18.33% had 3 other trackers, 8.71% had 2 other trackers, 0.73% had 7 other trackers, and 0.36% had one other tracker.

93.92% also included Chartable, 89.38% also included Podsights, 74.95% also included Podtrac, 73.14% also included Podscribe, 47.64% also included ArtsAI, 25.32% also included Adswizz, 11.34% also included Magellan AI, 10.34% also included Vpixl, 1.36% also included Podder, and 0.09% also included Podkite.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "40.74%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "26.77%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "12.79%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.26%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.90%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.99%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.82%" >}}
8. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "0.73%" >}}
---

### 16. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.07% of new episodes in February, shrinking 4.59% from last month.

Of these, 35.12% had 4 other trackers, 18.29% had 2 other trackers, 16.74% had 3 other trackers, 14.19% had one other tracker, 10.10% had 6 other trackers, 2.82% had 5 other trackers, and 0.73% had 7 other trackers.

85.35% also included Chartable, 73.25% also included Podsights, 65.97% also included Podtrac, 51.32% also included Podscribe, 14.01% also included ArtsAI, 13.28% also included Podder, 11.37% also included Claritas, 2.73% also included Veritonic, 2.27% also included Vpixl, 0.73% also included Adswizz, 0.64% also included Podcorn, and 0.36% also included OP3.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "62.24%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "18.20%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "11.46%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.73%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.73%" >}}
6. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "0.73%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.55%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.36%" >}}
---

### 17. [Gumball](https://gumball.fm/)

Gumball was found on 0.06% of new episodes in February, shrinking 0.11% from last month.

Of these, 39.12% had 4 other trackers, 19.14% had 2 other trackers, 14.12% had 3 other trackers, 11.40% had 5 other trackers, 6.59% had one other tracker, 0.94% had 6 other trackers, and 0.84% had 7 other trackers.

79.71% also included Podsights, 63.28% also included Podtrac, 63.18% also included OP3, 62.76% also included Podcorn, 35.25% also included Chartable, 4.71% also included Podder, 1.26% also included Podscribe, 1.26% also included Podkite, and 0.84% also included Adswizz.

For episodes that used Gumball, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "65.59%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "13.39%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.21%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.65%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.20%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.09%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.88%" >}}
---

### 18. [Vpixl](https://vpixl.com/)

Vpixl was found on 0.03% of new episodes in February, growing 525.08% from last month.

Of these, 64.99% had 5 other trackers, 22.94% had 6 other trackers, 6.64% had 4 other trackers, 2.82% had 3 other trackers, 1.61% had 2 other trackers, and 1.01% had one other tracker.

96.58% also included Podscribe, 95.98% also included Podtrac, 95.98% also included Chartable, 95.37% also included Podsights, 87.32% also included ArtsAI, 22.94% also included Claritas, 5.03% also included Magellan AI, 2.01% also included Podder, and 0.60% also included Adswizz.

For episodes that used Vpixl, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "87.93%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.44%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.02%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.60%" >}}
---

### 19. [Zippycast](https://zippycast.io/)

Zippycast was found on 0.02% of new episodes in February, shrinking 17.13% from last month.

Of these, 12.23% had 2 other trackers, and 2.19% had one other tracker.

13.17% also included Podtrac, 12.23% also included Podsights, and 1.25% also included Chartable.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "29.47%" >}}
2. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "21.00%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "20.69%" >}}
4. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "15.67%" >}}
5. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "9.40%" >}}
6. {{< a "https://podcloud.fr/" "podCloud" >}} {{< span "weak" "2.51%" >}}
---

### 20. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in February, growing 15.66% from last month.

Of these, 30.00% had one other tracker, 6.67% had 5 other trackers, 6.67% had 7 other trackers, 2.50% had 2 other trackers, 0.83% had 3 other trackers, and 0.83% had 4 other trackers.

37.50% also included Chartable, 20.00% also included Podtrac, 16.67% also included Podsights, 15.00% also included Podcorn, 10.00% also included OP3, 10.00% also included Podder, 10.00% also included Gumball, 0.83% also included Claritas, and 0.83% also included Adswizz.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "24.17%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "19.17%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "19.17%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.50%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "6.67%" >}}
6. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "6.67%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.67%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.33%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.67%" >}}
10. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "0.83%" >}}
---

### 21. [Glystn](https://glystn.com/)

Glystn was found on 0.01% of new episodes in February, shrinking 9.37% from last month.

Of these, 96.55% had 2 other trackers, and 3.45% had one other tracker.

100.00% also included Chartable, and 96.55% also included Podtrac.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "96.55%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.45%" >}}
---

### 22. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in February, shrinking 13.74% from last month.

Of these, 57.61% had 2 other trackers, 9.78% had one other tracker, and 5.43% had 5 other trackers.

67.39% also included Chartable, 40.22% also included Podcorn, 31.52% also included Podtrac, 5.43% also included Blubrry, 5.43% also included Podsights, and 2.17% also included Podder.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "40.22%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "19.57%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "18.48%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "9.78%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.52%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.43%" >}}
---

### 23. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in February, shrinking 7.99% from last month.

Of these, 10.99% had one other tracker, 8.79% had 2 other trackers, 4.40% had 3 other trackers, and 4.40% had 4 other trackers.

24.18% also included Podsights, 17.58% also included Chartable, 8.79% also included Podcorn, 5.49% also included Podtrac, and 3.30% also included Blubrry.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "64.84%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "19.78%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.40%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.40%" >}}
5. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "2.20%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.10%" >}}
---

### 24. [Veritonic](https://www.veritonic.com/)

Veritonic was found on <0.01% of new episodes in February, growing 34.64% from last month.

Of these, 59.57% had 4 other trackers, 19.15% had 2 other trackers, 6.38% had 3 other trackers, and 2.13% had one other tracker.

87.23% also included Chartable, 85.11% also included Podtrac, 63.83% also included Magellan AI, 53.19% also included Podscribe, 6.38% also included Podsights, and 2.13% also included Adswizz.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "63.83%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "21.28%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.51%" >}}
4. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.13%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2023-02.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
