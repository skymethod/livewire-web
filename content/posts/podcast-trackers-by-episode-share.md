---
title: "Top Podcast Tracking Services by Episode Share (October 2022)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2022-10.png
date: 2022-11-02T15:30:00-05:00
lastmod: 2022-11-02T15:30:00-05:00
draft: false
rssrevision: 2022-10
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.7 million in October 2022), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in October, how many
of them included one or more of these tracking services?  Some episodes had as many as *six* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Chartable	Podcorn	Adswizz	Podsights	Blubrry	Médiamétrie	Feedpress	ArtsAI	Podscribe	Gumball	OP3	Zippycast	Claritas	Podkite	Zencastr	FeedBurner
Sep 2021	4.16	4.06	2.09	1.00	1.16	2.07	0.42	0.32									1.61
Oct 2021	4.05	4.09	2.13	1.01	1.20	2.11	0.54	0.34									1.61
Nov 2021	4.07	4.30	2.14	1.02	1.25	2.01	0.57	0.32									0.59
Dec 2021	4.06	4.42	2.27	1.24	1.19	1.57	0.59	0.19									
Jan 2022	4.11	4.45	2.31	1.41	1.21	1.56	0.63	0.16									
Feb 2022	4.15	4.48	2.38	1.44	1.25	1.53	0.58	0.17									
Mar 2022	4.37	4.72	2.40	1.51	1.34	1.56	0.53	0.17									
Apr 2022	4.44	4.71	2.33	1.49	1.33	1.55	0.51	0.16									
May 2022	4.49	4.87	2.26	1.58	1.41	1.48	0.56	0.17									
Jun 2022	4.75	5.10	2.06	1.77	1.54	1.50	0.62	0.21					0.02				
Jul 2022	4.70	5.10	2.16	1.89	1.50	1.50	0.54	0.25					0.02				
Aug 2022	4.83	5.26	2.45	2.08	1.73	1.51	0.41	0.20	0.10				0.01				
Sep 2022	7.53	5.40	2.45	2.26	1.74	1.49	0.52	0.21	0.09	0.02	0.02		0.02	0.01	0.01		
Oct 2022	8.24	5.48	2.51	2.35	1.81	1.61	0.50	0.18	0.10	0.07	0.04	0.03	0.02	0.02	0.01	0.01	
{{< /graph >}}

---

### Overall

At least one tracker was found on 17.69% of new episodes in October, growing 4.58% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "22.98%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.22%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.47%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "8.24%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "6.99%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.06%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.71%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "3.22%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.51%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.22%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of October 2022.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 8.24% of new episodes in October, growing 9.45% from last month.

Of these, 22.56% had one other tracker, 11.68% had 2 other trackers, 2.03% had 3 other trackers, 0.55% had 4 other trackers, and 0.22% had 5 other trackers.

29.07% also included Chartable, 14.52% also included Podsights, 6.15% also included Adswizz, 1.93% also included Podcorn, 0.87% also included ArtsAI, 0.79% also included Podscribe, 0.60% also included Blubrry, 0.31% also included Gumball, 0.30% also included OP3, 0.19% also included Feedpress, 0.15% also included Claritas, 0.10% also included Backtracks, 0.09% also included Magellan AI, 0.05% also included Médiamétrie, 0.05% also included Veritonic, 0.04% also included AdBarker, 0.04% also included Zippycast, 0.01% also included Podder, 0.01% also included Podkite, <0.01% also included Firstory, and <0.01% also included Zencastr.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "48.42%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "14.80%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.30%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.98%" >}}
5. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.66%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.96%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.95%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.76%" >}}
9. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "1.41%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.27%" >}}
---

### [Spotify (Chartable & Podsights)](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/)

At least one Spotify tracker was found on 5.95% of new episodes in October, growing 2.61% from last month.

Of these, 42.88% also included Podtrac, 5.63% also included Adswizz, 4.85% also included Podcorn, 1.60% also included ArtsAI, 1.22% also included Podscribe, 1.05% also included Firstory, 0.64% also included Gumball, 0.48% also included Blubrry, 0.47% also included OP3, 0.34% also included Claritas, 0.24% also included Magellan AI, 0.09% also included AdBarker, 0.07% also included Veritonic, 0.04% also included Zippycast, 0.03% also included Feedpress, 0.03% also included Podkite, 0.03% also included Podder, 0.03% also included Zencastr, and 0.02% also included Backtracks.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "25.74%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.76%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.03%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.50%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.75%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.73%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.65%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.61%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.37%" >}}
10. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "2.36%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.48% of new episodes in October, growing 1.51% from last month.

Of these, 34.56% had one other tracker, 18.19% had 2 other trackers, 3.22% had 3 other trackers, 0.51% had 4 other trackers, and 0.33% had 5 other trackers.

43.74% also included Podtrac, 24.49% also included Podsights, 5.81% also included Adswizz, 4.42% also included Podcorn, 1.61% also included ArtsAI, 1.28% also included Podscribe, 1.14% also included Firstory, 0.42% also included Blubrry, 0.36% also included Claritas, 0.30% also included Gumball, 0.25% also included Magellan AI, 0.14% also included OP3, 0.09% also included AdBarker, 0.07% also included Veritonic, 0.04% also included Feedpress, 0.03% also included Podder, 0.03% also included Podkite, 0.02% also included Backtracks, 0.01% also included Zencastr, and <0.01% also included Zippycast.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "25.06%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.09%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.40%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.31%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.04%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.01%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.84%" >}}
8. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "2.57%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.55%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.54%" >}}
---

### 3. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 2.51% of new episodes in October, growing 2.55% from last month.

Of these, 10.38% had one other tracker, 2.37% had 2 other trackers, 0.79% had 3 other trackers, 0.71% had 4 other trackers, and 0.21% had 5 other trackers.

9.64% also included Chartable, 6.34% also included Podtrac, 2.70% also included Podsights, 1.00% also included Gumball, 0.97% also included OP3, 0.25% also included Blubrry, 0.16% also included Magellan AI, 0.09% also included AdBarker, 0.08% also included Backtracks, 0.05% also included Podkite, 0.05% also included Adswizz, 0.02% also included Zencastr, and 0.02% also included Podder.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "51.09%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "22.65%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.62%" >}}
4. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "4.78%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.67%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.63%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.48%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.42%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.31%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.75%" >}}
---

### 4. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.35% of new episodes in October, growing 2.54% from last month.

Of these, 23.18% had one other tracker, 4.91% had 3 other trackers, 2.65% had 2 other trackers, 0.26% had 4 other trackers, and 0.07% had 5 other trackers.

21.58% also included Podtrac, 13.56% also included Chartable, 7.35% also included Podsights, 1.32% also included Blubrry, 0.43% also included ArtsAI, 0.22% also included Podscribe, 0.05% also included Claritas, 0.05% also included Podcorn, 0.02% also included Gumball, 0.01% also included Veritonic, 0.01% also included Feedpress, and <0.01% also included Podkite.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "29.32%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "16.73%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.58%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "9.15%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "8.52%" >}}
6. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "5.39%" >}}
7. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.81%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "4.14%" >}}
9. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "1.76%" >}}
10. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.71%" >}}
---

### 5. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.81% of new episodes in October, growing 4.41% from last month.

Of these, 51.03% had 2 other trackers, 20.46% had one other tracker, 9.47% had 3 other trackers, 2.48% had 4 other trackers, and 1.00% had 5 other trackers.

73.93% also included Chartable, 65.96% also included Podtrac, 9.51% also included Adswizz, 4.18% also included ArtsAI, 3.74% also included Podcorn, 3.18% also included Podscribe, 1.92% also included Gumball, 1.34% also included OP3, 0.97% also included Claritas, 0.39% also included Blubrry, 0.34% also included Magellan AI, 0.12% also included Zippycast, 0.09% also included Zencastr, 0.07% also included Veritonic, 0.04% also included Podkite, 0.02% also included Podder, 0.01% also included Backtracks, and 0.01% also included AdBarker.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "42.92%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "28.61%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "6.55%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.06%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.15%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.01%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.31%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.66%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.13%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.91%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.61% of new episodes in October, growing 7.70% from last month.

Of these, 6.07% had one other tracker, 0.77% had 2 other trackers, 0.15% had 3 other trackers, 0.02% had 4 other trackers, and 0.01% had 5 other trackers.

3.10% also included Podtrac, 1.93% also included Adswizz, 1.44% also included Chartable, 0.86% also included Feedpress, 0.44% also included Podsights, 0.39% also included Podcorn, 0.02% also included Zencastr, 0.01% also included AdBarker, 0.01% also included OP3, and <0.01% also included Podscribe.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "76.96%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "4.24%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.35%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.90%" >}}
5. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.45%" >}}
6. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.18%" >}}
7. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "1.14%" >}}
8. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.13%" >}}
9. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "0.97%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.87%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.50% of new episodes in October, shrinking 2.43% from last month.

Of these, 0.84% had one other tracker.

0.84% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "37.15%" >}}
2. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "35.72%" >}}
3. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "10.98%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "9.49%" >}}
5. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "5.83%" >}}
6. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "0.48%" >}}
---

### 8. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.18% of new episodes in October, shrinking 12.77% from last month.

Of these, 15.39% had one other tracker, and 0.99% had 2 other trackers.

8.62% also included Podtrac, 7.54% also included Blubrry, 1.12% also included Chartable, and 0.10% also included Adswizz.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "66.78%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "10.70%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.63%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.28%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.26%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.92%" >}}
7. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.31%" >}}
8. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "1.02%" >}}
9. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.99%" >}}
10. {{< a "https://www.subsplash.com/" "Subsplash" >}} {{< span "weak" "0.86%" >}}
---

### 9. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.10% of new episodes in October, growing 4.73% from last month.

Of these, 29.96% had 3 other trackers, 23.76% had 2 other trackers, 22.22% had 4 other trackers, 12.88% had 5 other trackers, and 7.21% had one other tracker.

88.89% also included Chartable, 76.36% also included Podsights, 72.64% also included Podtrac, 35.58% also included Podscribe, 13.59% also included Claritas, 10.11% also included Adswizz, and 0.77% also included Veritonic.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "41.49%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "32.39%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "14.30%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.62%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.72%" >}}
6. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.47%" >}}
---

### 10. [Firstory](https://firstory.me/)

Firstory was found on 0.09% of new episodes in October, shrinking 5.07% from last month.

Of these, 65.41% had one other tracker, and 0.25% had 2 other trackers.

65.66% also included Chartable, and 0.25% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.50%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.50%" >}}
---

### 11. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.07% of new episodes in October, growing 279.98% from last month.

Of these, 34.16% had 4 other trackers, 29.86% had 3 other trackers, 16.72% had 5 other trackers, 12.26% had 2 other trackers, and 5.41% had one other tracker.

95.14% also included Chartable, 88.38% also included Podtrac, 78.26% also included Podsights, 47.93% also included ArtsAI, 18.87% also included Claritas, 7.01% also included Adswizz, 4.06% also included Veritonic, and 0.08% also included Blubrry.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "47.13%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "44.19%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "7.64%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.40%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.40%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.24%" >}}
---

### 12. [Gumball](https://gumball.fm/)

Gumball was found on 0.04% of new episodes in October, growing 141.06% from last month.

Of these, 38.83% had 4 other trackers, 24.60% had 2 other trackers, 10.64% had 5 other trackers, 9.57% had one other tracker, and 7.45% had 3 other trackers.

79.12% also included Podsights, 58.78% also included Podtrac, 57.05% also included Podcorn, 55.19% also included OP3, 37.77% also included Chartable, 1.20% also included Adswizz, and 0.53% also included Podkite.

For episodes that used Gumball, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "57.98%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.08%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "11.57%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.72%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.79%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.86%" >}}
---

### 13. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.03% of new episodes in October, growing 943.00% from last month.

Of these, 51.14% had 4 other trackers, 14.01% had 5 other trackers, 8.41% had 3 other trackers, 8.06% had 2 other trackers, and 2.10% had one other tracker.

74.96% also included Podtrac, 72.85% also included Podsights, 72.68% also included Gumball, 72.33% also included Podcorn, 23.47% also included Chartable, 0.70% also included Podkite, 0.70% also included Podder, and 0.35% also included Blubrry.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "83.01%" >}}
2. {{< a "https://podnews.net/" "Podnews" >}} {{< span "weak" "7.36%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "1.05%" >}}
4. {{< a "https://www.digitalocean.com/products/spaces/" "DigitalOcean Spaces" >}} {{< span "weak" "0.53%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.35%" >}}
6. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "0.35%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.35%" >}}
8. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "0.18%" >}}
---

### 14. [Zippycast](https://zippycast.io/)

Zippycast was found on 0.02% of new episodes in October, growing 8.91% from last month.

Of these, 9.60% had 2 other trackers, and 4.55% had one other tracker.

13.13% also included Podtrac, 9.60% also included Podsights, and 1.01% also included Chartable.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "35.35%" >}}
2. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "21.21%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "17.17%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "17.17%" >}}
5. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "7.07%" >}}
6. {{< a "https://podcloud.fr/" "podCloud" >}} {{< span "weak" "2.02%" >}}
---

### 15. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.02% of new episodes in October, growing 122.17% from last month.

Of these, 52.79% had 5 other trackers, 19.55% had 2 other trackers, 18.44% had 3 other trackers, 2.79% had 4 other trackers, and 1.68% had one other tracker.

93.58% also included Chartable, 83.52% also included Podsights, 66.20% also included Podscribe, 64.25% also included ArtsAI, 58.10% also included Podtrac, and 5.59% also included Adswizz.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "89.39%" >}}
2. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "5.31%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.31%" >}}
---

### 16. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.02% of new episodes in October, shrinking 11.88% from last month.

Of these, 48.98% had 2 other trackers, 26.19% had one other tracker, and 20.07% had 3 other trackers.

80.61% also included Chartable, 44.56% also included Podtrac, 36.05% also included Podsights, and 23.13% also included Podcorn.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "44.56%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.95%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "18.03%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.42%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.04%" >}}
---

### 17. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.01% of new episodes in October, growing 6.73% from last month.

Of these, 57.08% had one other tracker, 12.83% had 2 other trackers, and 1.77% had 4 other trackers.

65.04% also included Podtrac, 15.04% also included Podcorn, 7.96% also included Chartable, and 1.77% also included Podsights.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "46.46%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "15.04%" >}}
3. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "13.72%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.42%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.54%" >}}
6. {{< a "https://www.subsplash.com/" "Subsplash" >}} {{< span "weak" "2.21%" >}}
7. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "0.88%" >}}
8. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.88%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.88%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.44%" >}}
---

### 18. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in October, growing 41.34% from last month.

Of these, 19.86% had one other tracker, 6.16% had 5 other trackers, 2.05% had 2 other trackers, 0.68% had 3 other trackers, and 0.68% had 4 other trackers.

17.81% also included Chartable, 13.70% also included Podcorn, 10.96% also included Podtrac, 7.53% also included Podsights, 3.42% also included Podder, 2.74% also included OP3, 2.74% also included Gumball, and 0.68% also included Adswizz.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.45%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "23.29%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "17.81%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "6.16%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "6.16%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.42%" >}}
7. {{< a "https://analytics.podtrac.com/" "Podtrac" >}} {{< span "weak" "2.05%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.05%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.37%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.37%" >}}
---

### 19. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in October, shrinking 3.19% from last month.

Of these, 66.39% had 2 other trackers, 10.08% had one other tracker, and 3.36% had 5 other trackers.

73.95% also included Chartable, 47.06% also included Podtrac, 31.93% also included Podcorn, 3.36% also included Blubrry, and 3.36% also included Podsights.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "37.82%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "34.45%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "15.13%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "4.20%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.20%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.20%" >}}
---

### 20. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in October, growing 99.10% from last month.

Of these, 9.17% had 2 other trackers, 8.26% had one other tracker, 4.59% had 3 other trackers, and 3.67% had 4 other trackers.

25.69% also included Podsights, 12.84% also included Chartable, 8.26% also included Podcorn, 4.59% also included Blubrry, and 3.67% also included Podtrac.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "71.56%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "13.76%" >}}
3. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "4.59%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.67%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.67%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.83%" >}}
7. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "0.92%" >}}
---

### 21. [Veritonic](https://www.veritonic.com/)

Veritonic was found on <0.01% of new episodes in October, shrinking 9.73% from last month.

Of these, 62.32% had 3 other trackers, 18.84% had 5 other trackers, 11.59% had 2 other trackers, and 7.25% had 4 other trackers.

100.00% also included Podtrac, 100.00% also included Chartable, 73.91% also included Podscribe, 33.33% also included Podsights, 18.84% also included ArtsAI, and 7.25% also included Adswizz.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "73.91%" >}}
2. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "26.09%" >}}
---

### 22. [Podder](https://www.podderapp.com/)

Podder was found on <0.01% of new episodes in October, growing 16.57% from last month.

Of these, 25.42% had one other tracker, 15.25% had 2 other trackers, 8.47% had 5 other trackers, and 6.78% had 3 other trackers.

49.15% also included Chartable, 33.90% also included Podtrac, 11.86% also included Podcorn, 8.47% also included Podkite, 8.47% also included Podsights, and 6.78% also included OP3.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "40.68%" >}}
2. {{< a "https://sounder.fm/" "Sounder" >}} {{< span "weak" "18.64%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "16.95%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.47%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.08%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.08%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.39%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.69%" >}}


---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
 - [Podcast Tracker Rankings by Episode Share (September 2022)](/archive/podcast-trackers-by-episode-share-august-2022/)
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
