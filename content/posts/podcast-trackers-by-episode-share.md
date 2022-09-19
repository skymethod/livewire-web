---
title: "Top Podcast Tracking Services by Episode Share (August 2022)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2022-08.png
date: 2022-08-31T20:05:00-05:00
lastmod: 2022-08-31T20:05:00-05:00
draft: false
rssrevision: 2022-08
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.6 million in August 2022), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in August, how many
of them included one or more of these tracking services?  Some episodes had as many as *six* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Chartable	Podtrac	Podcorn	Adswizz	Podsights	Blubrry	Médiamétrie	Feedpress	ArtsAI	Zippycast	FeedBurner
Sep 2021	4.06	4.16	2.09	1.00	1.16	2.07	0.42	0.32			1.61
Oct 2021	4.09	4.05	2.13	1.01	1.20	2.11	0.54	0.34			1.61
Nov 2021	4.30	4.07	2.14	1.02	1.25	2.01	0.57	0.32			0.59
Dec 2021	4.42	4.06	2.27	1.24	1.19	1.57	0.59	0.19			
Jan 2022	4.45	4.11	2.31	1.41	1.21	1.56	0.63	0.16			
Feb 2022	4.48	4.15	2.38	1.44	1.25	1.53	0.58	0.17			
Mar 2022	4.72	4.37	2.40	1.51	1.34	1.56	0.53	0.17			
Apr 2022	4.71	4.44	2.33	1.49	1.33	1.55	0.51	0.16			
May 2022	4.87	4.49	2.26	1.58	1.41	1.48	0.56	0.17			
Jun 2022	5.10	4.75	2.06	1.77	1.54	1.50	0.62	0.21		0.02	
Jul 2022	5.10	4.70	2.16	1.89	1.50	1.50	0.54	0.25		0.02	
Aug 2022	5.26	4.83	2.45	2.08	1.73	1.51	0.41	0.20	0.10	0.01	
{{< /graph >}}

---

### Overall

At least one tracker was found on 13.92% of new episodes in August, growing 4.09% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.44%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.71%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "10.57%" >}}
4. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "8.45%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.16%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.24%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.79%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.74%" >}}
9. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "3.57%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.92%" >}}
---

### [Spotify (Chartable & Podsights)](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/)

At least one Spotify tracker was found on 5.66% of new episodes in August, growing 4.56% from last month.

Of these, 38.50% also included Podtrac, 5.67% also included Adswizz, 4.87% also included Podcorn, 1.63% also included ArtsAI, 1.17% also included Firstory, 0.45% also included Blubrry, 0.25% also included Magellan AI, 0.09% also included AdBarker, 0.07% also included Veritonic, 0.06% also included Feedpress, 0.06% also included Zippycast, 0.04% also included Backtracks, 0.02% also included Podder, and 0.02% also included Podkite.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "26.19%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.90%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.56%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.50%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.00%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.94%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.73%" >}}
8. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.67%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.66%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.62%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of August 2022.

---

### 1. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.26% of new episodes in August, growing 3.26% from last month.

Of these, 32.79% had one other tracker, 17.61% had 2 other trackers, 3.53% had 3 other trackers, 0.09% had 4 other trackers, and <0.01% had 5 other trackers.

39.30% also included Podtrac, 25.29% also included Podsights, 5.79% also included Adswizz, 4.75% also included Podcorn, 1.58% also included ArtsAI, 1.26% also included Firstory, 0.42% also included Blubrry, 0.27% also included Magellan AI, 0.09% also included AdBarker, 0.08% also included Veritonic, 0.07% also included Feedpress, 0.04% also included Backtracks, 0.02% also included Podder, 0.02% also included Podkite, and 0.01% also included Zippycast.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "25.15%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.34%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.92%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.24%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.16%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.15%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.92%" >}}
8. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.88%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.81%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.78%" >}}
---

### 2. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 4.83% of new episodes in August, growing 2.70% from last month.

Of these, 32.18% had one other tracker, 18.54% had 2 other trackers, 3.81% had 3 other trackers, 0.10% had 4 other trackers, and 0.01% had 5 other trackers.

42.86% also included Chartable, 22.66% also included Podsights, 10.58% also included Adswizz, 1.79% also included Podcorn, 1.49% also included ArtsAI, 1.11% also included Blubrry, 0.16% also included Backtracks, 0.12% also included Feedpress, 0.08% also included Veritonic, 0.08% also included Médiamétrie, 0.08% also included Zippycast, 0.06% also included AdBarker, 0.03% also included Magellan AI, 0.01% also included Podkite, 0.01% also included Podder, and 0.01% also included Firstory.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "21.84%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.01%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "13.98%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "6.08%" >}}
5. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "4.53%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.04%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.97%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.96%" >}}
9. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "2.60%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.05%" >}}
---

### 3. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 2.45% of new episodes in August, growing 13.64% from last month.

Of these, 9.52% had one other tracker, 2.33% had 2 other trackers, 0.61% had 3 other trackers, 0.04% had 4 other trackers, and 0.01% had 5 other trackers.

10.20% also included Chartable, 3.53% also included Podtrac, 1.85% also included Podsights, 0.27% also included Blubrry, 0.17% also included Magellan AI, 0.10% also included AdBarker, 0.03% also included Adswizz, 0.02% also included Backtracks, 0.01% also included Podkite, and 0.01% also included Podder.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "53.02%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "20.24%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.27%" >}}
4. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "4.54%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.62%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.62%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.27%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.90%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.68%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.89%" >}}
---

### 4. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.08% of new episodes in August, growing 10.21% from last month.

Of these, 24.88% had one other tracker, 5.50% had 3 other trackers, 2.98% had 2 other trackers, and 0.16% had 4 other trackers.

24.58% also included Podtrac, 14.67% also included Chartable, 8.21% also included Podsights, 0.25% also included ArtsAI, 0.23% also included Blubrry, 0.03% also included Podcorn, and 0.01% also included Veritonic.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "31.64%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "19.55%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "14.40%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "10.94%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.81%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "4.74%" >}}
7. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "3.50%" >}}
8. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "3.22%" >}}
9. {{< a "https://www.bbc.co.uk/" "BBC" >}} {{< span "weak" "1.73%" >}}
10. {{< a "https://kostenlos-hosten.de/" "Podcastbude" >}} {{< span "weak" "1.16%" >}}
---

### 5. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.73% of new episodes in August, growing 15.18% from last month.

Of these, 50.98% had 2 other trackers, 23.23% had one other tracker, 10.78% had 3 other trackers, 0.27% had 4 other trackers, and 0.01% had 5 other trackers.

77.17% also included Chartable, 63.41% also included Podtrac, 9.90% also included Adswizz, 4.41% also included ArtsAI, 2.63% also included Podcorn, 0.44% also included Blubrry, 0.41% also included Magellan AI, 0.18% also included Zippycast, 0.08% also included Veritonic, 0.02% also included Backtracks, 0.02% also included AdBarker, and <0.01% also included Podkite.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "41.73%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "28.99%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "7.07%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.12%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.63%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.41%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.73%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.30%" >}}
9. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.28%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.04%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.51% of new episodes in August, growing 0.97% from last month.

Of these, 4.66% had one other tracker, 0.71% had 2 other trackers, 0.25% had 3 other trackers, 0.04% had 4 other trackers, and 0.02% had 5 other trackers.

3.54% also included Podtrac, 1.45% also included Chartable, 0.82% also included Feedpress, 0.50% also included Podsights, 0.43% also included Podcorn, 0.31% also included Adswizz, and 0.02% also included AdBarker.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "77.79%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "4.79%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.59%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.22%" >}}
5. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.61%" >}}
6. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.28%" >}}
7. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.16%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.90%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.90%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.66%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.41% of new episodes in August, shrinking 24.71% from last month.

Of these, 0.97% had one other tracker.

0.97% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "44.02%" >}}
2. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "33.06%" >}}
3. {{< a "https://www.rcf.fr/" "RCF" >}} {{< span "weak" "9.47%" >}}
4. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "7.02%" >}}
5. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "5.08%" >}}
6. {{< a "https://www.streamakaci.com/" "Streamakaci" >}} {{< span "weak" "0.60%" >}}
7. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "0.31%" >}}
---

### 8. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.20% of new episodes in August, shrinking 20.72% from last month.

Of these, 10.81% had one other tracker, and 0.03% had 2 other trackers.

6.23% also included Blubrry, 2.81% also included Podtrac, and 1.83% also included Chartable.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "70.32%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.91%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.64%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.09%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.05%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.77%" >}}
7. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.10%" >}}
8. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.92%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.76%" >}}
10. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "0.73%" >}}
---

### 9. [Firstory](https://firstory.me/)

Firstory was found on 0.10% of new episodes in August, shrinking 4.07% from last month.

Of these, 63.72% had one other tracker, and 0.24% had 2 other trackers.

63.95% also included Chartable, and 0.24% also included Podtrac.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.59%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.41%" >}}
---

### 10. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.10% of new episodes in August, growing 48.82% from last month.

Of these, 57.56% had 3 other trackers, 21.16% had 2 other trackers, 15.19% had one other tracker, and 3.58% had 4 other trackers.

85.81% also included Chartable, 78.34% also included Podsights, 74.26% also included Podtrac, 5.40% also included Adswizz, and 0.69% also included Veritonic.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "40.99%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "38.98%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "13.31%" >}}
4. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.77%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.51%" >}}
6. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.44%" >}}
---

### 11. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.02% of new episodes in August, shrinking 8.06% from last month.

Of these, 69.78% had 2 other trackers, and 17.63% had one other tracker.

82.37% also included Chartable, 41.73% also included Podsights, 24.46% also included Podcorn, and 8.63% also included Podtrac.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "37.41%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "36.33%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "19.42%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.32%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.52%" >}}
---

### 12. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.01% of new episodes in August, growing 29.17% from last month.

Of these, 66.09% had one other tracker, and 2.61% had 4 other trackers.

53.91% also included Podtrac, 15.65% also included Chartable, 4.35% also included Podcorn, and 2.61% also included Podsights.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "49.13%" >}}
2. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "26.96%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "6.09%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "4.35%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.61%" >}}
6. {{< a "https://www.subsplash.com/" "Subsplash" >}} {{< span "weak" "1.30%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.30%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.87%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.43%" >}}
---

### 13. [Zippycast](https://zippycast.io/)

Zippycast was found on 0.01% of new episodes in August, shrinking 31.00% from last month.

Of these, 24.41% had 2 other trackers, and 6.57% had one other tracker.

28.64% also included Podtrac, 24.41% also included Podsights, and 2.35% also included Chartable.

For episodes that used Zippycast, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.58%" >}}
2. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "24.88%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "20.66%" >}}
4. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "19.25%" >}}
5. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "4.23%" >}}
6. {{< a "https://podcloud.fr/" "podCloud" >}} {{< span "weak" "1.41%" >}}
---

### 14. [AdBarker](https://adbarker.com/)

AdBarker was found on 0.01% of new episodes in August, growing 19.84% from last month.

Of these, 57.60% had 2 other trackers, 8.00% had one other tracker, and 3.20% had 5 other trackers.

63.20% also included Chartable, 35.20% also included Podtrac, 32.80% also included Podcorn, 4.80% also included Podsights, and 3.20% also included Blubrry.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "35.20%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "30.40%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "16.00%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "8.00%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.80%" >}}
6. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "4.00%" >}}
7. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "1.60%" >}}
---

### 15. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on <0.01% of new episodes in August, growing 4.54% from last month.

Of these, 28.95% had one other tracker, 2.63% had 2 other trackers, and 1.32% had 3 other trackers.

22.37% also included Chartable, 7.89% also included Podcorn, 6.58% also included Podtrac, and 1.32% also included Podsights.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "27.63%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "14.47%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.84%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "10.53%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "9.21%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "7.89%" >}}
7. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.95%" >}}
8. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "3.95%" >}}
9. {{< a "http://www.npo.nl/" "Nederlandse Publieke Omroep" >}} {{< span "weak" "3.95%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.32%" >}}
---

### 16. [Veritonic](https://www.veritonic.com/)

Veritonic was found on <0.01% of new episodes in August, growing 56.61% from last month.

Of these, 65.15% had 2 other trackers, 22.73% had 4 other trackers, and 12.12% had 3 other trackers.

100.00% also included Podtrac, 100.00% also included Chartable, 34.85% also included Podsights, 16.67% also included ArtsAI, and 6.06% also included Adswizz.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "74.24%" >}}
2. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "25.76%" >}}
---

### 17. [Podder](https://www.podderapp.com/)

Podder was found on <0.01% of new episodes in August, growing 44.44% from last month.

Of these, 48.57% had one other tracker, and 14.29% had 2 other trackers.

51.43% also included Chartable, 14.29% also included Podtrac, and 11.43% also included Podcorn.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "34.29%" >}}
2. {{< a "https://sounder.fm/" "Sounder" >}} {{< span "weak" "25.71%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "14.29%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "14.29%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.43%" >}}


---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
