---
title: "Top Podcast Tracking Services by Episode Share (December 2022)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2022-12.png
date: 2023-01-01T16:52:00-06:00
lastmod: 2023-01-01T16:52:00-06:00
draft: false
rssrevision: 2022-12
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.6 million in December 2022), 
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
Month	Podtrac	Chartable	Adswizz	Podcorn	Podsights	Blubrry	Médiamétrie	Feedpress	Gumball	OP3	ArtsAI	Podder	Podscribe	Zippycast	Claritas	Glystn	Zencastr	Podkite	FeedBurner
Sep 2021	4.16	4.06	1.00	2.09	1.16	2.07	0.42	0.32											1.61
Oct 2021	4.05	4.09	1.01	2.13	1.20	2.11	0.54	0.34											1.61
Nov 2021	4.07	4.30	1.02	2.14	1.25	2.01	0.57	0.32											0.59
Dec 2021	4.06	4.42	1.24	2.27	1.19	1.57	0.59	0.19											
Jan 2022	4.11	4.45	1.41	2.31	1.21	1.56	0.63	0.16											
Feb 2022	4.15	4.48	1.44	2.38	1.25	1.53	0.58	0.17											
Mar 2022	4.37	4.72	1.51	2.40	1.34	1.56	0.53	0.17											
Apr 2022	4.44	4.71	1.49	2.33	1.33	1.55	0.51	0.16											
May 2022	4.49	4.87	1.58	2.26	1.41	1.48	0.56	0.17											
Jun 2022	4.75	5.10	1.77	2.06	1.54	1.50	0.62	0.21						0.02					
Jul 2022	4.70	5.10	1.89	2.16	1.50	1.50	0.54	0.25						0.02					
Aug 2022	4.83	5.26	2.08	2.45	1.73	1.51	0.41	0.20			0.10			0.01					
Sep 2022	7.53	5.40	2.26	2.45	1.74	1.49	0.52	0.21	0.02		0.09		0.02	0.02	0.01			0.01	
Oct 2022	8.24	5.48	2.35	2.51	1.81	1.61	0.50	0.18	0.04	0.03	0.10		0.07	0.02	0.02		0.01	0.01	
Nov 2022	8.11	5.62	2.37	2.43	2.03	1.62	0.50	0.18	0.05	0.04	0.10	0.01	0.15	0.02	0.03		0.01	0.01	
Dec 2022	8.01	5.54	2.32	2.05	1.81	1.61	0.49	0.18	0.05	0.05	0.05	0.04	0.03	0.02	0.02	0.01	0.01	0.01	
{{< /graph >}}

---

### Overall

At least one tracker was found on 17.09% of new episodes in December, shrinking 3.36% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "23.00%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.86%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.92%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "7.89%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "7.08%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.20%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.12%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.51%" >}}
9. {{< a "https://analytics.podtrac.com/" "Podtrac" >}} {{< span "weak" "2.03%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.01%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of December 2022.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 8.01% of new episodes in December, shrinking 1.32% from last month.

Of these, 22.95% had one other tracker, 11.60% had 2 other trackers, 1.96% had 3 other trackers, 0.45% had 4 other trackers, 0.11% had 5 other trackers, 0.01% had 6 other trackers, and 0.01% had 7 other trackers.

29.75% also included Chartable, 13.34% also included Podsights, 6.03% also included Adswizz, 1.99% also included Podcorn, 0.62% also included Blubrry, 0.44% also included ArtsAI, 0.42% also included Gumball, 0.42% also included OP3, 0.38% also included Podder, 0.24% also included Podscribe, 0.17% also included Magellan AI, 0.17% also included Feedpress, 0.15% also included Claritas, 0.13% also included Backtracks, 0.09% also included Glystn, 0.07% also included Médiamétrie, 0.04% also included Zippycast, 0.03% also included AdBarker, 0.01% also included Podkite, 0.01% also included Veritonic, <0.01% also included Firstory, and <0.01% also included Zencastr.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "48.07%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "14.59%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.72%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.03%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.88%" >}}
6. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.37%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.94%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.69%" >}}
9. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "1.56%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.27%" >}}
---

### [Spotify (Chartable & Podsights)](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/)

At least one Spotify tracker was found on 6.13% of new episodes in December, shrinking 2.48% from last month.

Of these, 40.76% also included Podtrac, 7.89% also included Adswizz, 4.58% also included Podcorn, 1.15% also included Firstory, 0.74% also included Gumball, 0.71% also included ArtsAI, 0.59% also included Podder, 0.59% also included OP3, 0.51% also included Podscribe, 0.48% also included Blubrry, 0.25% also included Magellan AI, 0.23% also included Claritas, 0.13% also included Glystn, 0.08% also included Backtracks, 0.07% also included AdBarker, 0.05% also included Zippycast, 0.04% also included Feedpress, 0.04% also included Zencastr, 0.03% also included Podkite, and 0.02% also included Veritonic.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "25.99%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.34%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.77%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.05%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.72%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.39%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.99%" >}}
8. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.59%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.58%" >}}
10. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "2.44%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.54% of new episodes in December, shrinking 1.39% from last month.

Of these, 34.67% had one other tracker, 17.28% had 2 other trackers, 2.82% had 3 other trackers, 0.30% had 4 other trackers, 0.14% had 5 other trackers, 0.01% had 6 other trackers, and 0.01% had 7 other trackers.

42.97% also included Podtrac, 22.18% also included Podsights, 5.44% also included Adswizz, 4.19% also included Podcorn, 1.27% also included Firstory, 0.72% also included ArtsAI, 0.52% also included Podder, 0.49% also included Podscribe, 0.46% also included Blubrry, 0.32% also included Gumball, 0.27% also included Magellan AI, 0.26% also included Claritas, 0.18% also included OP3, 0.14% also included Glystn, 0.09% also included Backtracks, 0.08% also included AdBarker, 0.05% also included Feedpress, 0.03% also included Podkite, 0.02% also included Veritonic, 0.02% also included Zencastr, and <0.01% also included Zippycast.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "26.82%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.24%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.23%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.08%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.07%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.72%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.28%" >}}
8. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.86%" >}}
9. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "2.70%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.43%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.32% of new episodes in December, shrinking 2.22% from last month.

Of these, 28.34% had one other tracker, 4.32% had 3 other trackers, 3.30% had 2 other trackers, 0.37% had 4 other trackers, 0.04% had 5 other trackers, and 0.01% had 6 other trackers.

20.81% also included Podtrac, 13.94% also included Podsights, 13.02% also included Chartable, 1.18% also included Blubrry, 0.22% also included ArtsAI, 0.19% also included Claritas, 0.14% also included Podcorn, 0.09% also included Podscribe, 0.04% also included Podder, 0.02% also included Gumball, and 0.01% also included Veritonic.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "29.89%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "14.84%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "9.73%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.53%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "9.38%" >}}
6. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "6.07%" >}}
7. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.24%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "4.07%" >}}
9. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "2.01%" >}}
10. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.53%" >}}
---

### 4. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 2.05% of new episodes in December, shrinking 15.80% from last month.

Of these, 12.08% had one other tracker, 2.86% had 2 other trackers, 1.07% had 4 other trackers, 0.90% had 3 other trackers, 0.32% had 5 other trackers, 0.02% had 6 other trackers, and 0.02% had 7 other trackers.

11.32% also included Chartable, 7.78% also included Podtrac, 3.35% also included Podsights, 1.54% also included Gumball, 1.49% also included OP3, 0.23% also included Blubrry, 0.22% also included Magellan AI, 0.20% also included Podder, 0.15% also included Adswizz, 0.12% also included Backtracks, 0.12% also included AdBarker, 0.06% also included Podkite, 0.04% also included Podscribe, and 0.03% also included Zencastr.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "57.41%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "10.40%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "6.61%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.59%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "4.23%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.38%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.59%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.57%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.35%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.05%" >}}
---

### 5. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.81% of new episodes in December, shrinking 10.79% from last month.

Of these, 47.87% had 2 other trackers, 26.15% had one other tracker, 8.49% had 3 other trackers, 2.01% had 4 other trackers, 0.52% had 5 other trackers, 0.03% had 6 other trackers, and 0.02% had 7 other trackers.

67.77% also included Chartable, 58.88% also included Podtrac, 17.81% also included Adswizz, 3.79% also included Podcorn, 2.32% also included Gumball, 1.70% also included OP3, 1.51% also included ArtsAI, 1.48% also included Podder, 1.26% also included Podscribe, 0.63% also included Claritas, 0.40% also included Magellan AI, 0.29% also included Blubrry, 0.15% also included Zippycast, 0.14% also included Zencastr, 0.13% also included Backtracks, 0.05% also included Podkite, 0.03% also included Veritonic, and 0.02% also included AdBarker.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "38.40%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "34.15%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "6.05%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.11%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.83%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.23%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.90%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.59%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.16%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.96%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.61% of new episodes in December, shrinking 0.63% from last month.

Of these, 5.81% had one other tracker, 0.77% had 2 other trackers, 0.09% had 3 other trackers, 0.04% had 4 other trackers, and 0.02% had 5 other trackers.

3.05% also included Podtrac, 1.70% also included Adswizz, 1.57% also included Chartable, 0.74% also included Feedpress, 0.33% also included Podsights, 0.29% also included Podcorn, 0.06% also included Podder, 0.05% also included Zencastr, 0.03% also included OP3, 0.02% also included AdBarker, 0.01% also included Podscribe, and <0.01% also included Podkite.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "74.95%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.52%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.72%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.98%" >}}
5. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.47%" >}}
6. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.42%" >}}
7. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "1.20%" >}}
8. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.19%" >}}
9. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.15%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "0.90%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.49% of new episodes in December, shrinking 0.80% from last month.

Of these, 1.11% had one other tracker.

1.11% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "39.34%" >}}
2. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "38.71%" >}}
3. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "10.71%" >}}
4. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "6.14%" >}}
5. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "4.19%" >}}
6. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "0.42%" >}}
7. {{< a "https://analytics.podtrac.com/" "Podtrac" >}} {{< span "weak" "0.01%" >}}
---

### 8. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.18% of new episodes in December, shrinking 0.82% from last month.

Of these, 13.38% had one other tracker, and 1.33% had 2 other trackers.

7.71% also included Podtrac, 6.81% also included Blubrry, and 1.51% also included Chartable.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "63.20%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "13.63%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.20%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.73%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.19%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "1.97%" >}}
7. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "1.15%" >}}
8. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.15%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.08%" >}}
10. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "1.08%" >}}
---

### 9. [Firstory](https://firstory.me/)

Firstory was found on 0.11% of new episodes in December, growing 10.60% from last month.

Of these, 65.30% had one other tracker, and 0.23% had 2 other trackers.

65.54% also included Chartable, and 0.23% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.53%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.47%" >}}
---

### 10. [Gumball](https://gumball.fm/)

Gumball was found on 0.05% of new episodes in December, growing 12.36% from last month.

Of these, 37.25% had 4 other trackers, 23.05% had 2 other trackers, 10.94% had 5 other trackers, 10.24% had 3 other trackers, 7.22% had one other tracker, 0.81% had 6 other trackers, and 0.81% had 7 other trackers.

77.88% also included Podsights, 62.75% also included Podtrac, 58.32% also included Podcorn, 57.16% also included OP3, 33.06% also included Chartable, 6.75% also included Podder, 1.28% also included Podkite, 1.05% also included Adswizz, and 0.12% also included Podscribe.

For episodes that used Gumball, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "61.12%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "16.41%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.24%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.89%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.89%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.21%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.23%" >}}
---

### 11. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.05% of new episodes in December, growing 12.38% from last month.

Of these, 42.55% had 4 other trackers, 12.50% had 5 other trackers, 10.11% had 3 other trackers, 8.24% had 2 other trackers, 6.12% had one other tracker, 0.93% had 6 other trackers, and 0.93% had 7 other trackers.

70.48% also included Podtrac, 65.43% also included Podsights, 65.29% also included Gumball, 64.63% also included Podcorn, 21.01% also included Chartable, 7.31% also included Podder, 1.46% also included Podkite, 1.06% also included Podscribe, and 1.06% also included Blubrry.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "76.06%" >}}
2. {{< a "https://podnews.net/" "Podnews" >}} {{< span "weak" "5.85%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.72%" >}}
4. {{< a "https://changelog.com/" "Changelog" >}} {{< span "weak" "2.39%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.39%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.06%" >}}
7. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "0.66%" >}}
8. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.53%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.53%" >}}
10. {{< a "https://www.digitalocean.com/products/spaces/" "DigitalOcean Spaces" >}} {{< span "weak" "0.40%" >}}
---

### 12. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.05% of new episodes in December, shrinking 53.56% from last month.

Of these, 35.28% had 2 other trackers, 29.31% had 3 other trackers, 17.10% had 4 other trackers, 6.38% had 5 other trackers, 6.24% had one other tracker, and 0.41% had 6 other trackers.

86.43% also included Chartable, 75.98% also included Podtrac, 59.29% also included Podsights, 21.30% also included Podscribe, 12.89% also included Claritas, 10.99% also included Adswizz, and 0.54% also included Podder.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "56.31%" >}}
2. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "16.96%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "13.30%" >}}
4. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "9.91%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.31%" >}}
6. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "1.22%" >}}
---

### 13. [Podder](https://www.podderapp.com/)

Podder was found on 0.04% of new episodes in December, growing 572.00% from last month.

Of these, 39.62% had 3 other trackers, 28.87% had 2 other trackers, 12.67% had one other tracker, 4.27% had 5 other trackers, 2.50% had 4 other trackers, 1.03% had 6 other trackers, and 1.03% had 7 other trackers.

70.54% also included Podtrac, 67.16% also included Chartable, 62.74% also included Podsights, 9.57% also included Podcorn, 8.54% also included Gumball, 8.10% also included OP3, 2.21% also included Blubrry, 2.21% also included Adswizz, 1.62% also included Podkite, 0.74% also included Podscribe, and 0.59% also included ArtsAI.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "68.34%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "16.35%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.24%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.95%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.65%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.21%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.62%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.59%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.59%" >}}
10. {{< a "https://sounder.fm/" "Sounder" >}} {{< span "weak" "0.29%" >}}
---

### 14. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.03% of new episodes in December, shrinking 77.52% from last month.

Of these, 26.63% had 3 other trackers, 23.19% had 4 other trackers, 19.38% had one other tracker, 13.22% had 2 other trackers, 6.88% had 5 other trackers, and 0.54% had 6 other trackers.

78.62% also included Chartable, 66.12% also included Podsights, 54.53% also included Podtrac, 28.44% also included ArtsAI, 15.76% also included Claritas, 5.80% also included Adswizz, 2.54% also included Podcorn, 1.45% also included OP3, 1.27% also included Veritonic, 0.91% also included Podder, 0.54% also included Blubrry, and 0.18% also included Gumball.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "40.58%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "36.23%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.33%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.07%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.26%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.17%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.81%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.36%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.18%" >}}
---

### 15. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.02% of new episodes in December, growing 4.08% from last month.

Of these, 39.84% had one other tracker, 38.79% had 2 other trackers, and 17.41% had 3 other trackers.

62.01% also included Chartable, 58.58% also included Podtrac, 30.34% also included Podsights, and 18.73% also included Podcorn.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "58.58%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.75%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "12.40%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.64%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.64%" >}}
---

### 16. [Zippycast](https://zippycast.io/)

Zippycast was found on 0.02% of new episodes in December, shrinking 5.69% from last month.

Of these, 12.68% had 2 other trackers, and 2.88% had one other tracker.

14.41% also included Podtrac, 12.68% also included Podsights, and 1.15% also included Chartable.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "27.67%" >}}
2. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "22.77%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "20.46%" >}}
4. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "17.29%" >}}
5. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "9.80%" >}}
6. {{< a "https://podcloud.fr/" "podCloud" >}} {{< span "weak" "2.02%" >}}
---

### 17. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.02% of new episodes in December, growing 14.32% from last month.

Of these, 54.90% had one other tracker, 12.94% had 3 other trackers, 12.55% had 2 other trackers, and 1.96% had 4 other trackers.

65.10% also included Podtrac, 31.37% also included Chartable, 15.29% also included Podcorn, and 14.90% also included Podsights.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "35.29%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "25.10%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "14.12%" >}}
4. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "8.63%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.31%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.75%" >}}
7. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "1.57%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.78%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.78%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.78%" >}}
---

### 18. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.02% of new episodes in December, shrinking 51.80% from last month.

Of these, 40.56% had 3 other trackers, 28.51% had 4 other trackers, 18.47% had 5 other trackers, 2.01% had 2 other trackers, 1.20% had 6 other trackers, and 0.80% had one other tracker.

90.76% also included Chartable, 75.50% also included Podtrac, 73.09% also included Podsights, 38.15% also included ArtsAI, 34.94% also included Podscribe, and 27.71% also included Adswizz.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "42.57%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "20.48%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "19.28%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "9.64%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.43%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.61%" >}}
---

### 19. [Glystn](https://glystn.com/)

Glystn was found on 0.01% of new episodes in December, shrinking 11.62% from last month.

Of these, 96.75% had 2 other trackers, and 3.25% had one other tracker.

100.00% also included Chartable, and 96.75% also included Podtrac.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "96.75%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.25%" >}}
---

### 20. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in December, growing 1.50% from last month.

Of these, 14.29% had one other tracker, 11.76% had 2 other trackers, 5.88% had 3 other trackers, and 3.36% had 4 other trackers.

33.61% also included Podsights, 12.61% also included Chartable, 10.08% also included Blubrry, 9.24% also included Podcorn, and 3.36% also included Podtrac.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "58.82%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "18.49%" >}}
3. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "10.08%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.20%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.36%" >}}
6. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "2.52%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.52%" >}}
---

### 21. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in December, shrinking 4.26% from last month.

Of these, 61.70% had 2 other trackers, 11.70% had one other tracker, and 5.32% had 5 other trackers.

71.28% also included Chartable, 40.43% also included Podcorn, 39.36% also included Podtrac, 5.32% also included Blubrry, and 5.32% also included Podsights.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "42.55%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "22.34%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "15.96%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "8.51%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.32%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.19%" >}}
7. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "2.13%" >}}
---

### 22. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in December, shrinking 9.93% from last month.

Of these, 31.76% had one other tracker, 9.41% had 5 other trackers, and 8.24% had 7 other trackers.

31.76% also included Chartable, 24.71% also included Podcorn, 22.35% also included Podtrac, 17.65% also included Podsights, 12.94% also included OP3, 12.94% also included Podder, 12.94% also included Gumball, and 1.18% also included Blubrry.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "28.24%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "25.88%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "20.00%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "7.06%" >}}
5. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "7.06%" >}}
6. {{< a "https://analytics.podtrac.com/" "Podtrac" >}} {{< span "weak" "4.71%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.53%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.35%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "1.18%" >}}
---

### 23. [Veritonic](https://www.veritonic.com/)

Veritonic was found on <0.01% of new episodes in December, shrinking 69.59% from last month.

Of these, 60.00% had 3 other trackers, 20.00% had 4 other trackers, and 10.00% had 2 other trackers.

90.00% also included Podtrac, 90.00% also included Chartable, 45.00% also included Podsights, 35.00% also included Podscribe, and 20.00% also included Adswizz.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "70.00%" >}}
2. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "20.00%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.00%" >}}


---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
