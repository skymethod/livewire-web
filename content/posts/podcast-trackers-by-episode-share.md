---
title: "Top Podcast Tracking Services by Episode Share (January 2023)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2023-01.png
date: 2023-02-01T14:22:00-06:00
lastmod: 2023-02-01T14:22:00-06:00
draft: false
rssrevision: 2023-01
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.7 million in January 2023), 
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
Month	Podtrac	Chartable	Adswizz	Podcorn	Podsights	Blubrry	Médiamétrie	Podscribe	Feedpress	Podder	ArtsAI	OP3	Claritas	Gumball	Zippycast	Glystn	Podkite	Zencastr	FeedBurner
Sep 2021	4.16	4.06	1.00	2.09	1.16	2.07	0.42		0.32										1.61
Oct 2021	4.05	4.09	1.01	2.13	1.20	2.11	0.54		0.34										1.61
Nov 2021	4.07	4.30	1.02	2.14	1.25	2.01	0.57		0.32										0.59
Dec 2021	4.06	4.42	1.24	2.27	1.19	1.57	0.59		0.19										
Jan 2022	4.11	4.45	1.41	2.31	1.21	1.56	0.63		0.16										
Feb 2022	4.15	4.48	1.44	2.38	1.25	1.53	0.58		0.17										
Mar 2022	4.37	4.72	1.51	2.40	1.34	1.56	0.53		0.17										
Apr 2022	4.44	4.71	1.49	2.33	1.33	1.55	0.51		0.16										
May 2022	4.49	4.87	1.58	2.26	1.41	1.48	0.56		0.17										
Jun 2022	4.75	5.10	1.77	2.06	1.54	1.50	0.62		0.21						0.02				
Jul 2022	4.70	5.10	1.89	2.16	1.50	1.50	0.54		0.25						0.02				
Aug 2022	4.83	5.26	2.08	2.45	1.73	1.51	0.41		0.20		0.10				0.01				
Sep 2022	7.53	5.40	2.26	2.45	1.74	1.49	0.52	0.02	0.21		0.09		0.01	0.02	0.02		0.01		
Oct 2022	8.24	5.48	2.35	2.51	1.81	1.61	0.50	0.07	0.18		0.10	0.03	0.02	0.04	0.02		0.01	0.01	
Nov 2022	8.11	5.62	2.37	2.43	2.03	1.62	0.50	0.15	0.18	0.01	0.10	0.04	0.03	0.05	0.02		0.01	0.01	
Dec 2022	8.01	5.54	2.32	2.05	1.81	1.61	0.49	0.03	0.18	0.04	0.05	0.05	0.02	0.05	0.02	0.01	0.01	0.01	
Jan 2023	7.85	5.56	2.35	2.15	1.88	1.61	0.54	0.20	0.18	0.11	0.10	0.07	0.06	0.06	0.02	0.01	0.01	0.01	
{{< /graph >}}

---

### Overall

At least one tracker was found on 17.18% of new episodes in January, growing 0.53% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "22.07%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.16%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "8.35%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.90%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.24%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "4.48%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.93%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.42%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.39%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.51%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of January 2023.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 7.85% of new episodes in January, shrinking 1.94% from last month.

Of these, 22.91% had one other tracker, 11.40% had 2 other trackers, 1.98% had 3 other trackers, 1.39% had 4 other trackers, 0.25% had 5 other trackers, 0.12% had 6 other trackers, and 0.01% had 7 other trackers.

30.17% also included Chartable, 13.96% also included Podsights, 6.19% also included Adswizz, 2.01% also included Podcorn, 1.46% also included Podscribe, 1.14% also included Podder, 0.93% also included ArtsAI, 0.68% also included Magellan AI, 0.61% also included Blubrry, 0.58% also included Claritas, 0.49% also included OP3, 0.47% also included Gumball, 0.14% also included Backtracks, 0.10% also included Feedpress, 0.10% also included Glystn, 0.05% also included Médiamétrie, 0.05% also included Zippycast, 0.04% also included AdBarker, 0.02% also included Podkite, 0.02% also included Veritonic, 0.01% also included Zencastr, and <0.01% also included Firstory.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "47.37%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "15.21%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.98%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.96%" >}}
5. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.94%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.74%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.14%" >}}
8. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "1.55%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.40%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.33%" >}}
---

### [Spotify (Chartable & Podsights)](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/)

At least one Spotify tracker was found on 6.16% of new episodes in January, growing 0.47% from last month.

Of these, 40.46% also included Podtrac, 7.77% also included Adswizz, 4.63% also included Podcorn, 3.00% also included Podscribe, 1.71% also included Podder, 1.59% also included ArtsAI, 1.03% also included Magellan AI, 1.01% also included Claritas, 0.95% also included Firstory, 0.85% also included Gumball, 0.73% also included OP3, 0.43% also included Blubrry, 0.13% also included Glystn, 0.08% also included Backtracks, 0.07% also included AdBarker, 0.06% also included Zippycast, 0.06% also included Feedpress, 0.04% also included Podkite, 0.03% also included Zencastr, and 0.03% also included Veritonic.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "27.43%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.31%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.53%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.07%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.57%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.42%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.95%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.65%" >}}
9. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "2.32%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.26%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.56% of new episodes in January, growing 0.22% from last month.

Of these, 33.82% had one other tracker, 16.80% had 2 other trackers, 3.01% had 3 other trackers, 1.59% had 4 other trackers, 0.40% had 5 other trackers, 0.17% had 6 other trackers, and 0.01% had 7 other trackers.

42.64% also included Podtrac, 22.96% also included Podsights, 5.25% also included Adswizz, 4.21% also included Podcorn, 2.96% also included Podscribe, 1.62% also included ArtsAI, 1.55% also included Podder, 1.11% also included Magellan AI, 1.06% also included Claritas, 1.05% also included Firstory, 0.41% also included Blubrry, 0.34% also included Gumball, 0.24% also included OP3, 0.14% also included Glystn, 0.08% also included Backtracks, 0.08% also included AdBarker, 0.06% also included Feedpress, 0.04% also included Podkite, 0.03% also included Veritonic, 0.02% also included Zencastr, and 0.01% also included Zippycast.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "28.39%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.74%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.93%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.16%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.94%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.70%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.23%" >}}
8. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "2.57%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.50%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.38%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.35% of new episodes in January, growing 1.28% from last month.

Of these, 29.83% had one other tracker, 3.44% had 2 other trackers, 2.80% had 3 other trackers, 0.58% had 4 other trackers, 0.45% had 5 other trackers, and 0.03% had 6 other trackers.

20.71% also included Podtrac, 13.37% also included Podsights, 12.43% also included Chartable, 1.33% also included Blubrry, 0.71% also included Claritas, 0.59% also included Podscribe, 0.57% also included ArtsAI, 0.12% also included Podcorn, 0.04% also included Podder, 0.02% also included Gumball, 0.01% also included Veritonic, 0.01% also included Podkite, and <0.01% also included OP3.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "30.20%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "17.49%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "9.52%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.16%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "8.75%" >}}
6. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "5.81%" >}}
7. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.03%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.36%" >}}
9. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "2.24%" >}}
10. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.54%" >}}
---

### 4. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 2.15% of new episodes in January, growing 4.67% from last month.

Of these, 11.66% had one other tracker, 2.60% had 2 other trackers, 1.20% had 4 other trackers, 0.91% had 3 other trackers, 0.33% had 5 other trackers, 0.03% had 6 other trackers, and 0.02% had 7 other trackers.

10.90% also included Chartable, 7.35% also included Podtrac, 3.35% also included Podsights, 1.70% also included Gumball, 1.68% also included OP3, 0.32% also included Podder, 0.31% also included Blubrry, 0.14% also included Magellan AI, 0.14% also included Podscribe, 0.14% also included Adswizz, 0.11% also included AdBarker, 0.09% also included Backtracks, 0.07% also included Podkite, and 0.03% also included Zencastr.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "58.45%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "11.66%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "6.54%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.98%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.83%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.30%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.44%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.24%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.26%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.00%" >}}
---

### 5. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.88% of new episodes in January, growing 3.45% from last month.

Of these, 44.11% had 2 other trackers, 26.00% had one other tracker, 8.85% had 3 other trackers, 5.76% had 4 other trackers, 1.30% had 5 other trackers, 0.50% had 6 other trackers, and 0.03% had 7 other trackers.

67.96% also included Chartable, 58.38% also included Podtrac, 16.73% also included Adswizz, 7.73% also included Podscribe, 4.14% also included ArtsAI, 3.83% also included Podcorn, 3.76% also included Podder, 2.98% also included Claritas, 2.71% also included Magellan AI, 2.54% also included Gumball, 1.99% also included OP3, 0.23% also included Blubrry, 0.19% also included Zippycast, 0.13% also included Backtracks, 0.10% also included Zencastr, 0.07% also included Podkite, 0.01% also included AdBarker, and 0.01% also included Veritonic.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "40.39%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "33.33%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.09%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.99%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.19%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.69%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.30%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.92%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.17%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.17%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.61% of new episodes in January, shrinking 0.13% from last month.

Of these, 6.40% had one other tracker, 0.58% had 2 other trackers, 0.09% had 3 other trackers, 0.02% had 4 other trackers, and 0.02% had 5 other trackers.

2.97% also included Podtrac, 1.94% also included Adswizz, 1.42% also included Chartable, 0.77% also included Feedpress, 0.41% also included Podcorn, 0.26% also included Podsights, 0.10% also included OP3, 0.05% also included Podder, 0.02% also included Zencastr, 0.02% also included Podscribe, 0.02% also included AdBarker, and <0.01% also included Podkite.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "47.79%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.63%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.33%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.06%" >}}
5. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.61%" >}}
6. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "1.51%" >}}
7. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.27%" >}}
8. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.24%" >}}
9. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.21%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "0.79%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.54% of new episodes in January, growing 9.15% from last month.

Of these, 0.78% had one other tracker.

0.78% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "37.07%" >}}
2. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "35.34%" >}}
3. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "11.26%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "9.26%" >}}
5. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "6.21%" >}}
6. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "0.58%" >}}
---

### 8. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.20% of new episodes in January, growing 487.18% from last month.

Of these, 33.13% had 4 other trackers, 18.21% had 3 other trackers, 17.83% had one other tracker, 11.59% had 2 other trackers, 6.83% had 5 other trackers, and 4.34% had 6 other trackers.

80.81% also included Chartable, 71.27% also included Podsights, 56.24% also included Podtrac, 31.11% also included ArtsAI, 21.87% also included Claritas, 16.34% also included Magellan AI, 6.80% also included Adswizz, 1.49% also included Podcorn, 0.68% also included Podder, 0.65% also included Veritonic, 0.62% also included OP3, 0.30% also included Gumball, and 0.15% also included Blubrry.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "49.85%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "26.71%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.52%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.63%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.23%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.87%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.54%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.27%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.21%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.18%" >}}
---

### 9. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.18% of new episodes in January, growing 1.68% from last month.

Of these, 11.79% had one other tracker, and 0.85% had 2 other trackers.

6.96% also included Blubrry, 4.55% also included Podtrac, and 1.97% also included Chartable.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "48.34%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.95%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.61%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.82%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.21%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.14%" >}}
7. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "1.36%" >}}
8. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.32%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.09%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.09%" >}}
---

### 10. [Podder](https://www.podderapp.com/)

Podder was found on 0.11% of new episodes in January, growing 162.64% from last month.

Of these, 38.71% had 2 other trackers, 31.86% had 3 other trackers, 11.02% had 4 other trackers, 10.85% had one other tracker, 2.75% had 5 other trackers, 0.49% had 6 other trackers, and 0.43% had 7 other trackers.

80.02% also included Podtrac, 76.62% also included Chartable, 62.90% also included Podsights, 10.10% also included Magellan AI, 6.16% also included Podcorn, 3.83% also included OP3, 2.97% also included Gumball, 1.24% also included Podscribe, 0.76% also included Blubrry, 0.76% also included Podkite, 0.76% also included Adswizz, 0.70% also included ArtsAI, 0.43% also included Claritas, and 0.38% also included AdBarker.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "82.45%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "9.02%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.62%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.03%" >}}
5. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "1.03%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.76%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.49%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.38%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.32%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.27%" >}}
---

### 11. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.10% of new episodes in January, growing 116.23% from last month.

Of these, 28.76% had 4 other trackers, 21.57% had 2 other trackers, 18.85% had 3 other trackers, 16.56% had 5 other trackers, 8.82% had 6 other trackers, and 3.81% had one other tracker.

89.73% also included Chartable, 77.52% also included Podsights, 72.75% also included Podtrac, 63.26% also included Podscribe, 26.28% also included Claritas, 13.29% also included Adswizz, 10.63% also included Magellan AI, and 0.79% also included Podder.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "36.74%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.72%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "14.32%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.10%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "6.34%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.54%" >}}
7. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.24%" >}}
---

### 12. [Firstory](https://firstory.me/)

Firstory was found on 0.09% of new episodes in January, shrinking 18.98% from last month.

Of these, 66.76% had one other tracker, and 0.35% had 2 other trackers.

67.11% also included Chartable, and 0.35% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.37%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.63%" >}}
---

### 13. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.07% of new episodes in January, growing 64.84% from last month.

Of these, 36.78% had 4 other trackers, 17.85% had 2 other trackers, 15.40% had one other tracker, 14.39% had 3 other trackers, 11.20% had 6 other trackers, and 3.28% had 5 other trackers.

85.52% also included Chartable, 73.99% also included Podtrac, 70.88% also included Podsights, 46.30% also included Podscribe, 15.74% also included Podder, 14.81% also included ArtsAI, 11.70% also included Claritas, 4.21% also included Podcorn, and 1.85% also included Veritonic.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "59.43%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "16.75%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "16.58%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.97%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.09%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.84%" >}}
7. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.34%" >}}
---

### 14. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.07% of new episodes in January, growing 44.31% from last month.

Of these, 32.48% had 4 other trackers, 11.89% had 3 other trackers, 9.49% had 5 other trackers, 8.43% had one other tracker, 8.43% had 2 other trackers, 0.80% had 6 other trackers, and 0.71% had 7 other trackers.

56.26% also included Podtrac, 54.75% also included Podsights, 52.80% also included Podcorn, 52.80% also included Gumball, 19.61% also included Chartable, 6.30% also included Podder, 2.40% also included Blubrry, 1.86% also included Podscribe, 1.24% also included Podkite, and 0.09% also included Adswizz.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "68.86%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.61%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "4.08%" >}}
4. {{< a "https://podnews.net/" "Podnews" >}} {{< span "weak" "3.90%" >}}
5. {{< a "https://changelog.com/" "Changelog" >}} {{< span "weak" "2.57%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.69%" >}}
7. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "0.98%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.71%" >}}
9. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "0.62%" >}}
10. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.53%" >}}
---

### 15. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.07% of new episodes in January, growing 318.02% from last month.

Of these, 13.37% had one other tracker, 3.07% had 3 other trackers, 2.35% had 2 other trackers, and 0.54% had 4 other trackers.

15.90% also included Podtrac, 6.96% also included Chartable, 3.61% also included Podsights, and 2.98% also included Podcorn.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://www.rferl.org/" "Radio Free Europe and Radio Liberty" >}} {{< span "weak" "75.70%" >}}
2. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "9.12%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.87%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.80%" >}}
5. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "1.90%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.90%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.72%" >}}
8. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "0.45%" >}}
9. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.09%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.09%" >}}
---

### 16. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.06% of new episodes in January, growing 306.44% from last month.

Of these, 35.49% had 4 other trackers, 21.41% had 3 other trackers, 19.98% had 5 other trackers, 13.89% had 6 other trackers, 6.76% had 2 other trackers, and 0.67% had one other tracker.

92.86% also included Chartable, 87.92% also included Podsights, 71.36% also included Podtrac, 70.03% also included Podscribe, 41.39% also included ArtsAI, 26.07% also included Adswizz, 13.23% also included Magellan AI, and 0.76% also included Podder.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.92%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "31.87%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "11.99%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.09%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.90%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.66%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.57%" >}}
---

### 17. [Gumball](https://gumball.fm/)

Gumball was found on 0.06% of new episodes in January, growing 10.64% from last month.

Of these, 36.88% had 4 other trackers, 19.45% had 2 other trackers, 14.79% had 3 other trackers, 10.84% had 5 other trackers, 7.90% had one other tracker, 0.91% had 6 other trackers, and 0.81% had 7 other trackers.

79.84% also included Podsights, 62.01% also included Podtrac, 60.99% also included Podcorn, 60.28% also included OP3, 32.02% also included Chartable, 5.57% also included Podder, 1.42% also included Podkite, 1.01% also included Podscribe, and 0.91% also included Adswizz.

For episodes that used Gumball, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "63.63%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "13.48%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.73%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "6.18%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.24%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.74%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.01%" >}}
---

### 18. [Zippycast](https://zippycast.io/)

Zippycast was found on 0.02% of new episodes in January, growing 10.17% from last month.

Of these, 14.86% had 2 other trackers, and 2.52% had one other tracker.

16.12% also included Podtrac, 14.86% also included Podsights, and 1.26% also included Chartable.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "25.44%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "23.93%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "22.17%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "18.39%" >}}
5. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "7.81%" >}}
6. {{< a "https://podcloud.fr/" "podCloud" >}} {{< span "weak" "2.27%" >}}
---

### 19. [Glystn](https://glystn.com/)

Glystn was found on 0.01% of new episodes in January, growing 3.34% from last month.

Of these, 96.21% had 2 other trackers, and 3.79% had one other tracker.

100.00% also included Chartable, and 96.21% also included Podtrac.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "96.21%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.79%" >}}
---

### 20. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in January, growing 12.68% from last month.

Of these, 66.36% had 2 other trackers, 8.18% had one other tracker, and 3.64% had 5 other trackers.

68.18% also included Chartable, 42.73% also included Podtrac, 34.55% also included Podcorn, 6.36% also included Podder, 3.64% also included Blubrry, and 3.64% also included Podsights.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "36.36%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "24.55%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "15.45%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "9.09%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "9.09%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.45%" >}}
---

### 21. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in January, growing 21.22% from last month.

Of these, 26.17% had one other tracker, 10.28% had 5 other trackers, 7.48% had 7 other trackers, 1.87% had 2 other trackers, 1.87% had 4 other trackers, and 0.93% had 3 other trackers.

32.71% also included Chartable, 26.17% also included Podtrac, 22.43% also included Podcorn, 20.56% also included Podsights, 13.08% also included OP3, 13.08% also included Podder, 13.08% also included Gumball, 1.87% also included Adswizz, and 0.93% also included Blubrry.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "24.30%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "21.50%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "14.95%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "8.41%" >}}
5. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "8.41%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.61%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.80%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "1.87%" >}}
9. {{< a "http://www.npo.nl/" "Nederlandse Publieke Omroep" >}} {{< span "weak" "1.87%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.93%" >}}
---

### 22. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in January, shrinking 17.46% from last month.

Of these, 13.73% had 2 other trackers, 12.75% had one other tracker, 4.90% had 3 other trackers, and 3.92% had 4 other trackers.

31.37% also included Podsights, 17.65% also included Chartable, 8.82% also included Podcorn, 6.86% also included Podtrac, and 5.88% also included Blubrry.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "59.80%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "21.57%" >}}
3. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "4.90%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.92%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.92%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.94%" >}}
7. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "1.96%" >}}
---

### 23. [Veritonic](https://www.veritonic.com/)

Veritonic was found on <0.01% of new episodes in January, growing 73.33% from last month.

Of these, 72.22% had 4 other trackers, and 13.89% had one other tracker.

86.11% also included Chartable, 72.22% also included Podtrac, 61.11% also included Podscribe, 61.11% also included Magellan AI, 11.11% also included Podsights, and 11.11% also included Adswizz.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "61.11%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "13.89%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "11.11%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "11.11%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
