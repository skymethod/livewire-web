---
title: "Top Podcast Tracking Services by Episode Share (March 2023)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2023-03.png
date: 2023-04-01T14:36:00-05:00
lastmod: 2023-04-01T14:36:00-05:00
draft: false
rssrevision: 2023-03
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.9 million in March 2023), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in December, how many
of them included one or more of these tracking services?  Some episodes had as many as *eight* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Chartable	Adswizz	Podcorn	Podsights	Blubrry	Médiamétrie	Podscribe	Feedpress	Podder	ArtsAI	OP3	Claritas	Gumball	Veritonic	Podroll	Zippycast	Glystn	Podkite	Zencastr	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.00	2.09	1.16	2.07	0.42		0.32													1.61
Oct 2021	4.05	4.09	1.01	2.13	1.20	2.11	0.54		0.34													1.61
Nov 2021	4.07	4.30	1.02	2.14	1.25	2.01	0.57		0.32													0.59
Dec 2021	4.06	4.42	1.24	2.27	1.19	1.57	0.59		0.19													
Jan 2022	4.11	4.45	1.41	2.31	1.21	1.56	0.63		0.16													
Feb 2022	4.15	4.48	1.44	2.38	1.25	1.53	0.58		0.17													
Mar 2022	4.37	4.72	1.51	2.40	1.34	1.56	0.53		0.17													
Apr 2022	4.44	4.71	1.49	2.33	1.33	1.55	0.51		0.16													
May 2022	4.49	4.87	1.58	2.26	1.41	1.48	0.56		0.17													
Jun 2022	4.75	5.10	1.77	2.06	1.54	1.50	0.62		0.21								0.02					
Jul 2022	4.70	5.10	1.89	2.16	1.50	1.50	0.54		0.25								0.02					
Aug 2022	4.83	5.26	2.08	2.45	1.73	1.51	0.41		0.20		0.10						0.01					
Sep 2022	7.53	5.40	2.26	2.45	1.74	1.49	0.52	0.02	0.21		0.09		0.01	0.02			0.02		0.01			
Oct 2022	8.24	5.48	2.35	2.51	1.81	1.61	0.50	0.07	0.18		0.10	0.03	0.02	0.04			0.02		0.01	0.01		
Nov 2022	8.11	5.62	2.37	2.43	2.03	1.62	0.50	0.15	0.18	0.01	0.10	0.04	0.03	0.05			0.02		0.01	0.01		
Dec 2022	8.01	5.54	2.32	2.05	1.81	1.61	0.49	0.03	0.18	0.04	0.05	0.05	0.02	0.05			0.02	0.01	0.01	0.01		
Jan 2023	7.85	5.56	2.35	2.15	1.88	1.61	0.54	0.20	0.18	0.11	0.10	0.07	0.06	0.06			0.02	0.01	0.01	0.01		
Feb 2023	7.58	5.51	2.29	2.30	1.92	1.62	0.49	0.21	0.19	0.11	0.10	0.07	0.07	0.06			0.02	0.01	0.01	0.01	0.03	
Mar 2023	7.79	5.53	2.25	2.22	2.03	1.53	0.45	0.21	0.18	0.11	0.11	0.08	0.07	0.06	0.04	0.04	0.02	0.01	0.01	0.01		
{{< /graph >}}

---

### Overall

At least one tracker was found on 17.04% of new episodes in March, shrinking 0.06% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "22.60%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.50%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.21%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "8.20%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.13%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "4.03%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.81%" >}}
8. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.43%" >}}
9. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.30%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.21%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of March 2023.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 7.79% of new episodes in March, growing 2.72% from last month.

Of these, 23.05% had one other tracker, 10.92% had 2 other trackers, 1.65% had 3 other trackers, 0.89% had 4 other trackers, 0.54% had 5 other trackers, 0.23% had 6 other trackers, and 0.14% had 7 other trackers.

29.24% also included Chartable, 13.48% also included Podsights, 6.18% also included Adswizz, 1.91% also included Podcorn, 1.38% also included Podscribe, 1.06% also included Podder, 1.05% also included ArtsAI, 0.68% also included Claritas, 0.63% also included Blubrry, 0.62% also included OP3, 0.54% also included Gumball, 0.52% also included Veritonic, 0.49% also included Magellan AI, 0.15% also included Feedpress, 0.12% also included Podroll, 0.11% also included Backtracks, 0.11% also included Glystn, 0.06% also included Médiamétrie, 0.03% also included Zippycast, 0.02% also included AdBarker, 0.02% also included Podkite, 0.01% also included Zencastr, and <0.01% also included Firstory.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "48.55%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "15.39%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.92%" >}}
4. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "3.20%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.63%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.58%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.91%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.49%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.48%" >}}
10. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "1.40%" >}}
---

### [Spotify (Chartable & Podsights)](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/)

At least one Spotify tracker was found on 6.21% of new episodes in March, growing 0.83% from last month.

Of these, 38.85% also included Podtrac, 7.95% also included Adswizz, 4.49% also included Podcorn, 3.09% also included Podscribe, 1.71% also included ArtsAI, 1.61% also included Podder, 1.13% also included Claritas, 1.03% also included Magellan AI, 0.91% also included Firstory, 0.91% also included Gumball, 0.87% also included OP3, 0.70% also included Veritonic, 0.40% also included Blubrry, 0.31% also included Podroll, 0.14% also included Glystn, 0.06% also included AdBarker, 0.06% also included Feedpress, 0.04% also included Podkite, 0.04% also included Backtracks, 0.03% also included Zippycast, and 0.03% also included Zencastr.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "27.58%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "23.34%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.12%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.35%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.46%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.26%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.79%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.50%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.26%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.23%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.53% of new episodes in March, growing 0.23% from last month.

Of these, 35.66% had one other tracker, 16.38% had 2 other trackers, 2.75% had 3 other trackers, 0.93% had 4 other trackers, 0.82% had 5 other trackers, 0.32% had 6 other trackers, and 0.19% had 7 other trackers.

41.20% also included Podtrac, 24.29% also included Podsights, 5.81% also included Adswizz, 4.12% also included Podcorn, 3.03% also included Podscribe, 1.78% also included ArtsAI, 1.52% also included Podder, 1.22% also included Claritas, 1.10% also included Magellan AI, 1.03% also included Firstory, 0.74% also included Veritonic, 0.42% also included Gumball, 0.38% also included OP3, 0.38% also included Blubrry, 0.33% also included Podroll, 0.15% also included Glystn, 0.07% also included AdBarker, 0.06% also included Feedpress, 0.04% also included Backtracks, 0.04% also included Podkite, 0.02% also included Zencastr, and <0.01% also included Zippycast.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "28.97%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.61%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.50%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.52%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.87%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.61%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.71%" >}}
8. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.54%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.48%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.30%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.25% of new episodes in March, shrinking 1.79% from last month.

Of these, 32.91% had one other tracker, 4.07% had 2 other trackers, 2.04% had 3 other trackers, 0.65% had 5 other trackers, 0.45% had 7 other trackers, 0.32% had 4 other trackers, and 0.29% had 6 other trackers.

21.38% also included Podtrac, 14.26% also included Chartable, 13.49% also included Podsights, 2.22% also included Blubrry, 1.37% also included ArtsAI, 1.22% also included Podscribe, 1.15% also included Claritas, 0.55% also included Podroll, 0.45% also included Magellan AI, 0.44% also included Veritonic, 0.04% also included Podcorn, 0.03% also included Podder, 0.01% also included Gumball, and 0.01% also included OP3.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "30.28%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "18.40%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.42%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "8.43%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "7.71%" >}}
6. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "5.50%" >}}
7. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.66%" >}}
8. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "3.78%" >}}
9. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.54%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.46%" >}}
---

### 4. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 2.22% of new episodes in March, shrinking 3.64% from last month.

Of these, 11.24% had one other tracker, 2.11% had 2 other trackers, 1.24% had 4 other trackers, 0.79% had 3 other trackers, 0.44% had 5 other trackers, 0.02% had 7 other trackers, and 0.02% had 6 other trackers.

10.27% also included Chartable, 6.69% also included Podtrac, 3.33% also included Podsights, 1.83% also included OP3, 1.82% also included Gumball, 0.42% also included Podder, 0.33% also included Blubrry, 0.11% also included AdBarker, 0.08% also included Backtracks, 0.07% also included Podroll, 0.06% also included Zencastr, 0.06% also included Podkite, 0.05% also included Podscribe, 0.05% also included Feedpress, 0.04% also included Adswizz, and 0.03% also included Magellan AI.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "54.91%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "17.58%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "6.65%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.75%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.28%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.27%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.14%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.94%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.06%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.84%" >}}
---

### 5. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.03% of new episodes in March, growing 5.68% from last month.

Of these, 39.60% had 2 other trackers, 28.91% had one other tracker, 7.63% had 3 other trackers, 3.61% had 4 other trackers, 2.33% had 5 other trackers, 0.87% had 6 other trackers, and 0.52% had 7 other trackers.

66.28% also included Chartable, 51.83% also included Podtrac, 14.99% also included Adswizz, 7.92% also included Podscribe, 4.32% also included ArtsAI, 3.65% also included Podcorn, 3.19% also included Claritas, 3.16% also included Podder, 2.84% also included Magellan AI, 2.53% also included Gumball, 2.09% also included OP3, 2.01% also included Veritonic, 0.65% also included Podroll, 0.22% also included Blubrry, 0.11% also included Zippycast, 0.09% also included Zencastr, 0.06% also included Podkite, 0.04% also included Backtracks, and 0.02% also included AdBarker.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "39.36%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "38.60%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.76%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.42%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.05%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.20%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.86%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.07%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.05%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.00%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.53% of new episodes in March, shrinking 5.35% from last month.

Of these, 7.80% had one other tracker, 0.58% had 2 other trackers, 0.07% had 3 other trackers, 0.06% had 4 other trackers, and 0.04% had 5 other trackers.

3.25% also included Adswizz, 3.19% also included Podtrac, 1.37% also included Chartable, 0.83% also included Feedpress, 0.47% also included Podcorn, 0.30% also included Podsights, 0.08% also included OP3, 0.07% also included Podder, 0.02% also included AdBarker, and 0.01% also included Zencastr.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "44.72%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.52%" >}}
3. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "2.58%" >}}
4. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "2.47%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.47%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.07%" >}}
7. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.55%" >}}
8. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.35%" >}}
9. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.26%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.00%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.45% of new episodes in March, shrinking 8.29% from last month.

Of these, 1.00% had one other tracker.

1.00% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "36.73%" >}}
2. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "31.89%" >}}
3. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "13.22%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "11.00%" >}}
5. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "5.94%" >}}
6. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "0.79%" >}}
---

### 8. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.21% of new episodes in March, shrinking 0.96% from last month.

Of these, 21.63% had 3 other trackers, 15.77% had 4 other trackers, 15.22% had 5 other trackers, 14.79% had one other tracker, 10.66% had 2 other trackers, 8.07% had 6 other trackers, and 4.75% had 7 other trackers.

78.65% also included Chartable, 75.38% also included Podsights, 50.35% also included Podtrac, 35.24% also included ArtsAI, 26.84% also included Claritas, 19.19% also included Magellan AI, 17.38% also included Veritonic, 12.90% also included Adswizz, 3.32% also included Podroll, 1.28% also included Podder, 0.53% also included Podcorn, 0.50% also included OP3, and 0.33% also included Gumball.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "48.09%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "22.43%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "11.09%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.21%" >}}
5. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "4.78%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.02%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.41%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.58%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.48%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.35%" >}}
---

### 9. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.18% of new episodes in March, shrinking 3.81% from last month.

Of these, 14.15% had one other tracker, and 1.03% had 2 other trackers.

7.00% also included Blubrry, 6.59% also included Podtrac, 1.93% also included Chartable, 0.59% also included Podcorn, and 0.09% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "44.67%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "10.93%" >}}
3. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "9.37%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.03%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.83%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.81%" >}}
7. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "1.90%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.79%" >}}
9. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.61%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.26%" >}}
---

### 10. [Podder](https://www.podderapp.com/)

Podder was found on 0.11% of new episodes in March, growing 2.93% from last month.

Of these, 37.48% had 2 other trackers, 31.19% had 3 other trackers, 10.15% had one other tracker, 10.15% had 4 other trackers, 2.80% had 5 other trackers, 0.82% had 6 other trackers, and 0.44% had 7 other trackers.

76.11% also included Chartable, 74.85% also included Podtrac, 57.88% also included Podsights, 8.51% also included Podcorn, 8.37% also included Magellan AI, 4.93% also included OP3, 3.53% also included Gumball, 2.47% also included Podscribe, 1.02% also included Blubrry, 0.68% also included Adswizz, 0.68% also included ArtsAI, 0.68% also included Claritas, 0.63% also included Podkite, 0.48% also included Veritonic, 0.24% also included Backtracks, and 0.24% also included AdBarker.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "74.52%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "11.07%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.56%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.51%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.21%" >}}
6. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "1.02%" >}}
7. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.73%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.73%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.53%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.48%" >}}
---

### 11. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.11% of new episodes in March, growing 5.79% from last month.

Of these, 32.56% had 5 other trackers, 19.28% had 2 other trackers, 15.41% had 6 other trackers, 15.16% had 3 other trackers, 9.37% had 7 other trackers, 4.56% had 4 other trackers, and 2.28% had one other tracker.

90.98% also included Chartable, 81.02% also included Podsights, 75.87% also included Podtrac, 69.43% also included Podscribe, 35.23% also included Claritas, 28.84% also included Veritonic, 28.59% also included Adswizz, 14.72% also included Magellan AI, and 0.69% also included Podder.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.48%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "27.30%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "12.49%" >}}
4. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "9.51%" >}}
5. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "9.42%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.87%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.49%" >}}
8. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.25%" >}}
9. {{< a "https://cloud.google.com/" "Google Cloud" >}} {{< span "weak" "0.20%" >}}
---

### 12. [Firstory](https://firstory.me/)

Firstory was found on 0.08% of new episodes in March, growing 1.56% from last month.

Of these, 66.71% had one other tracker, and 0.25% had 2 other trackers.

66.96% also included Chartable, and 0.25% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.31%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.69%" >}}
---

### 13. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.08% of new episodes in March, growing 11.55% from last month.

Of these, 31.75% had 4 other trackers, 11.06% had 5 other trackers, 10.80% had 3 other trackers, 8.72% had 2 other trackers, 7.16% had one other tracker, 0.59% had 7 other trackers, and 0.46% had 6 other trackers.

58.75% also included Podtrac, 51.53% also included Podsights, 49.64% also included Gumball, 49.25% also included Podcorn, 25.70% also included Chartable, 6.64% also included Podder, 1.50% also included Blubrry, 1.30% also included Podscribe, 0.85% also included Podkite, 0.33% also included Magellan AI, 0.26% also included Backtracks, 0.20% also included Adswizz, and 0.20% also included Feedpress.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "64.54%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.90%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.90%" >}}
4. {{< a "https://podnews.net/" "Podnews" >}} {{< span "weak" "2.99%" >}}
5. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "2.28%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.28%" >}}
7. {{< a "https://changelog.com/" "Changelog" >}} {{< span "weak" "1.76%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.56%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.37%" >}}
10. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.11%" >}}
---

### 14. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.07% of new episodes in March, growing 6.08% from last month.

Of these, 26.27% had 3 other trackers, 24.06% had 4 other trackers, 13.91% had 7 other trackers, 12.58% had one other tracker, 12.51% had 2 other trackers, 5.00% had 6 other trackers, and 2.72% had 5 other trackers.

83.81% also included Chartable, 79.10% also included Podsights, 56.14% also included Podscribe, 52.39% also included Podtrac, 21.85% also included ArtsAI, 19.35% also included Claritas, 13.98% also included Adswizz, 12.73% also included Podder, 9.64% also included Podroll, 3.31% also included Veritonic, 0.88% also included Podcorn, 0.37% also included OP3, and 0.07% also included Podkite.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "57.91%" >}}
2. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "13.98%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "10.67%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.45%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.15%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.66%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.59%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.29%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.29%" >}}
---

### 15. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.07% of new episodes in March, shrinking 8.76% from last month.

Of these, 9.62% had one other tracker, 3.11% had 3 other trackers, 0.89% had 2 other trackers, and 0.15% had 4 other trackers.

11.98% also included Podtrac, 3.25% also included Chartable, 2.44% also included Podcorn, 1.92% also included Podroll, 1.04% also included Podsights, 0.37% also included Podder, and 0.30% also included OP3.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://www.rferl.org/" "Radio Free Europe and Radio Liberty" >}} {{< span "weak" "82.10%" >}}
2. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "7.54%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.51%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.63%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.41%" >}}
6. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "1.26%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.59%" >}}
8. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "0.37%" >}}
9. {{< a "https://www.subsplash.com/" "Subsplash" >}} {{< span "weak" "0.30%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.15%" >}}
---

### 16. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.07% of new episodes in March, growing 3.13% from last month.

Of these, 25.49% had 4 other trackers, 19.53% had 6 other trackers, 16.21% had 3 other trackers, 15.91% had 5 other trackers, 14.25% had 7 other trackers, 7.16% had 2 other trackers, and 0.68% had one other tracker.

94.65% also included Chartable, 91.10% also included Podsights, 80.47% also included Podscribe, 75.04% also included Podtrac, 53.62% also included ArtsAI, 36.35% also included Adswizz, 19.83% also included Magellan AI, 10.03% also included Veritonic, and 1.06% also included Podder.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "36.88%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.14%" >}}
3. {{< a "https://empirestreaming.com/" "Empire Streaming" >}} {{< span "weak" "14.33%" >}}
4. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "10.33%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.88%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.15%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.94%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.36%" >}}
---

### 17. [Gumball](https://gumball.fm/)

Gumball was found on 0.06% of new episodes in March, growing 6.78% from last month.

Of these, 39.46% had 4 other trackers, 19.90% had 2 other trackers, 13.94% had 5 other trackers, 12.43% had 3 other trackers, 5.04% had one other tracker, 0.76% had 7 other trackers, and 0.59% had 6 other trackers.

80.52% also included Podsights, 65.58% also included Podtrac, 64.06% also included OP3, 63.48% also included Podcorn, 36.19% also included Chartable, 6.13% also included Podder, 1.09% also included Podscribe, 1.09% also included Podkite, and 0.34% also included Adswizz.

For episodes that used Gumball, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "66.33%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "14.19%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.82%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.88%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.76%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.51%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.51%" >}}
---

### 18. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.04% of new episodes in March, growing 28.41% from last month.

Of these, 51.17% had 5 other trackers, 23.80% had 6 other trackers, 16.69% had 4 other trackers, 3.31% had 2 other trackers, 3.07% had 3 other trackers, and 1.23% had one other tracker.

93.87% also included Chartable, 93.74% also included Podtrac, 93.13% also included Podsights, 84.79% also included Podscribe, 71.41% also included ArtsAI, 22.45% also included Adswizz, 16.32% also included Claritas, 5.52% also included Magellan AI, and 1.23% also included Podder.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "64.05%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "22.82%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.24%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "5.52%" >}}
5. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.12%" >}}
---

### 19. [Podroll](https://podroll.fm/)

Podroll was found on 0.04% of new episodes in March, growing 694.87% from last month.

Of these, 56.13% had one other tracker, 20.09% had 3 other trackers, 17.28% had 4 other trackers, and 3.84% had 2 other trackers.

49.78% also included Chartable, 36.34% also included Podsights, 33.97% also included Adswizz, 25.41% also included Podtrac, 19.50% also included Podscribe, 19.35% also included Magellan AI, 4.58% also included Podcorn, 3.84% also included Backtracks, and 0.44% also included Zencastr.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "54.95%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "33.97%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "10.04%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.59%" >}}
5. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "0.44%" >}}
---

### 20. [Zippycast](https://zippycast.io/)

Zippycast was found on 0.02% of new episodes in March, shrinking 19.93% from last month.

Of these, 13.42% had 2 other trackers, and 2.68% had one other tracker.

14.77% also included Podtrac, 13.42% also included Podsights, and 1.34% also included Chartable.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "32.89%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "24.50%" >}}
3. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "23.49%" >}}
4. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "14.77%" >}}
5. {{< a "https://podcloud.fr/" "podCloud" >}} {{< span "weak" "3.02%" >}}
6. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "1.34%" >}}
---

### 21. [Glystn](https://glystn.com/)

Glystn was found on 0.01% of new episodes in March, growing 16.74% from last month.

Of these, 97.47% had 2 other trackers, and 2.53% had one other tracker.

100.00% also included Chartable, and 97.47% also included Podtrac.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "97.47%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.53%" >}}
---

### 22. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in March, shrinking 2.15% from last month.

Of these, 27.01% had one other tracker, 6.57% had 7 other trackers, 5.84% had 5 other trackers, 3.65% had 2 other trackers, and 0.73% had 3 other trackers.

29.93% also included Chartable, 18.98% also included Podtrac, 16.79% also included Podcorn, 16.79% also included Podsights, 9.49% also included OP3, 9.49% also included Podder, 9.49% also included Gumball, and 0.73% also included Magellan AI.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "21.90%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "18.98%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "17.52%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "8.76%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "6.57%" >}}
6. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "6.57%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.11%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.65%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.65%" >}}
10. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "1.46%" >}}
---

### 23. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in March, growing 25.27% from last month.

Of these, 25.56% had one other tracker, 8.27% had 2 other trackers, 6.02% had 4 other trackers, and 3.01% had 3 other trackers.

25.56% also included Podsights, 18.80% also included Chartable, 18.05% also included Podcorn, 9.02% also included Podtrac, 2.26% also included Podroll, and 1.50% also included Blubrry.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "48.87%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "26.32%" >}}
3. {{< a "https://zencastr.com/" "Zencastr" >}} {{< span "weak" "9.02%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.27%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.76%" >}}
6. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "2.26%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.75%" >}}
---

### 24. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in March, shrinking 0.32% from last month.

Of these, 61.68% had 2 other trackers, 6.54% had 5 other trackers, and 4.67% had one other tracker.

67.29% also included Chartable, 42.06% also included Podcorn, 33.64% also included Podtrac, 6.54% also included Blubrry, 6.54% also included Podsights, and 4.67% also included Podder.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "37.38%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "18.69%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "16.82%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "12.15%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "8.41%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.54%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
