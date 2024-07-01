---
title: "Top Podcast Tracking Services by Episode Share (May 2024)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-may-2024"
images:
- trackers-2024-05.png
date: 2024-06-01T11:30:00-05:00
lastmod: 2024-06-01T11:30:00-05:00
draft: false
rssrevision: 2024-05
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.9 million in May 2024), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in May, how many
of them included one or more of these tracking services?  Some episodes had as many as *nine* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

### A special note for March/April 2024 {#spreaker}
_We now have a better signal of when Spreaker releases new episodes, so our crawlers are finding more, starting early-March. This more accurate view seems to have helped Podtrac and Adswizz the most in this month's share rankings._

### A special note for September/October 2023 {#s4p}
_We now have a better signal of when Spotify for Podcasters (formerly Anchor) podcasts release new episodes, so our crawlers are finding more, starting mid-September._

_October was the first full month where this new signal was incorporated for the entire month, so should be a good baseline going forward.  It's likely that we were undercounting S4P prior to this,
in general our goal is to observe and validate every change to every podcast._

_Higher share of new episodes on S4P (which typically do not have prefixes) leads to lower share overall for all prefixes over these two months, but should be stable going forward now that we have a more accurate baseline._

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Chartable	Adswizz	Podsights	Blubrry	Podcorn	Podscribe	Podroll	Spotify	OP3	Podder	Claritas	Feedpress	ArtsAI	Gumshoe	Médiamétrie	Veritonic	Audiotakes	Zencastr	United Podcasters	Podkite	CoHost Prefix	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.00	1.16	2.07	2.09							0.32			0.42												1.61
Oct 2021	4.05	4.09	1.01	1.20	2.11	2.13							0.34			0.54												1.61
Nov 2021	4.07	4.30	1.02	1.25	2.01	2.14							0.32			0.57												0.59
Dec 2021	4.06	4.42	1.24	1.19	1.57	2.27							0.19			0.59												
Jan 2022	4.11	4.45	1.41	1.21	1.56	2.31							0.16			0.63												
Feb 2022	4.15	4.48	1.44	1.25	1.53	2.38							0.17			0.58												
Mar 2022	4.37	4.72	1.51	1.34	1.56	2.40							0.17			0.53												
Apr 2022	4.44	4.71	1.49	1.33	1.55	2.33							0.16			0.51												
May 2022	4.49	4.87	1.58	1.41	1.48	2.26							0.17			0.56												
Jun 2022	4.75	5.10	1.77	1.54	1.50	2.06							0.21			0.62									0.02			
Jul 2022	4.70	5.10	1.89	1.50	1.50	2.16							0.25			0.54									0.02			
Aug 2022	4.83	5.26	2.08	1.73	1.51	2.45							0.20	0.10		0.41									0.01			
Sep 2022	7.53	5.40	2.26	1.74	1.49	2.45	0.02					0.01	0.21	0.09		0.52					0.01				0.02	0.02		
Oct 2022	8.24	5.48	2.35	1.81	1.61	2.51	0.07			0.03		0.02	0.18	0.10		0.50			0.01		0.01				0.02	0.04		
Nov 2022	8.11	5.62	2.37	2.03	1.62	2.43	0.15			0.04	0.01	0.03	0.18	0.10		0.50			0.01		0.01				0.02	0.05		
Dec 2022	8.01	5.54	2.32	1.81	1.61	2.05	0.03			0.05	0.04	0.02	0.18	0.05		0.49			0.01		0.01			0.01	0.02	0.05		
Jan 2023	7.85	5.56	2.35	1.88	1.61	2.15	0.20			0.07	0.11	0.06	0.18	0.10		0.54			0.01		0.01			0.01	0.02	0.06		
Feb 2023	7.58	5.51	2.29	1.92	1.62	2.30	0.21			0.07	0.11	0.07	0.19	0.10		0.49			0.01		0.01			0.01	0.02	0.06	0.03	
Mar 2023	7.79	5.53	2.25	2.03	1.53	2.22	0.21	0.04		0.08	0.11	0.07	0.18	0.11		0.45	0.04		0.01		0.01			0.01	0.02	0.06		
Apr 2023	7.66	5.43	2.26	2.00	1.67	2.20	0.21	0.06		0.09	0.15	0.07	0.17	0.11	0.08	0.45	0.05		0.01		0.01			0.01	0.01			
May 2023	7.58	5.59	2.27	2.04	1.67	2.28	0.24	0.09		0.09	0.15	0.08	0.19	0.11	0.07	0.45	0.05		0.01		0.01		0.01	0.01	0.01			
Jun 2023	8.22	5.83	2.39	2.23	1.64	1.86	0.26	0.10		0.09	0.15	0.07	0.19	0.12	0.08	0.51	0.05		0.01		0.01		0.01	0.01	0.01			
Jul 2023	8.60	5.95	2.38	2.52	1.53	1.17	0.27	0.14	0.01	0.08	0.14	0.07	0.18	0.11	0.06	0.55	0.06		0.01		0.01		0.01	0.01	0.01			
Aug 2023	9.19	6.43	2.72	2.76	1.58	1.23	0.36	0.16	0.03	0.11	0.15	0.08	0.17	0.12	0.07	0.53	0.07	0.04	0.01		0.01		0.02	0.01				
Sep 2023	8.46	5.77	2.49	2.47	1.39	1.10	0.37	0.13	0.05	0.10	0.15	0.10	0.16	0.12	0.07	0.58	0.06	0.05	0.01		0.01		0.02	0.01				
Oct 2023	7.90	5.54	2.29	2.28	1.37	1.11	0.39	0.12	0.08	0.10	0.16	0.10	0.16	0.12	0.08	0.50	0.06	0.05	0.02		0.01		0.03	0.01				
Nov 2023	7.65	5.59	2.25	2.33	1.45	1.14	0.47	0.12	0.11	0.13	0.16	0.11	0.17	0.12	0.10	0.33	0.06	0.06	0.01		0.01		0.03					
Dec 2023	7.48	5.60	2.20	2.19	1.53	1.12	0.54	0.12	0.12	0.11	0.16	0.11	0.16	0.12	0.09	0.33	0.06	0.06	0.01		0.01		0.03					
Jan 2024	7.64	5.61	2.37	2.21	1.55	1.17	0.65	0.11	0.15	0.13	0.16	0.12	0.17	0.14	0.10	0.25	0.06	0.08	0.01	0.01	0.01		0.01					
Feb 2024	7.69	5.58	2.38	2.22	1.52	1.21	0.69	0.12	0.22	0.16	0.17	0.13	0.17	0.13	0.11	0.22	0.06	0.09	0.01	0.01	0.01							
Mar 2024	9.01	5.46	2.53	2.19	1.54	1.14	0.69	0.12	0.25	0.14	0.16	0.14	0.16	0.12	0.10	0.22	0.06	0.09	0.01	0.01	0.01							
Apr 2024	10.78	5.47	2.53	2.16	1.51	1.24	0.73	0.34	0.27	0.18	0.17	0.15	0.15	0.13	0.11	0.19	0.07	0.07	0.01	0.01	0.01	0.01						
May 2024	11.59	5.63	2.75	2.24	1.50	1.20	0.83	0.36	0.30	0.18	0.16	0.15	0.15	0.14	0.11	0.09	0.07	0.06	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} are the clear top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podsights	Blubrry	Podcorn	Podscribe	Podroll	Spotify	OP3	Podder	Claritas	Feedpress	ArtsAI	Gumshoe	Médiamétrie	Veritonic	Audiotakes	Zencastr	United Podcasters	Podkite	CoHost Prefix	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	1.00	1.16	2.07	2.09							0.32			0.42												1.61
Oct 2021	1.01	1.20	2.11	2.13							0.34			0.54												1.61
Nov 2021	1.02	1.25	2.01	2.14							0.32			0.57												0.59
Dec 2021	1.24	1.19	1.57	2.27							0.19			0.59												
Jan 2022	1.41	1.21	1.56	2.31							0.16			0.63												
Feb 2022	1.44	1.25	1.53	2.38							0.17			0.58												
Mar 2022	1.51	1.34	1.56	2.40							0.17			0.53												
Apr 2022	1.49	1.33	1.55	2.33							0.16			0.51												
May 2022	1.58	1.41	1.48	2.26							0.17			0.56												
Jun 2022	1.77	1.54	1.50	2.06							0.21			0.62									0.02			
Jul 2022	1.89	1.50	1.50	2.16							0.25			0.54									0.02			
Aug 2022	2.08	1.73	1.51	2.45							0.20	0.10		0.41									0.01			
Sep 2022	2.26	1.74	1.49	2.45	0.02					0.01	0.21	0.09		0.52					0.01				0.02	0.02		
Oct 2022	2.35	1.81	1.61	2.51	0.07			0.03		0.02	0.18	0.10		0.50			0.01		0.01				0.02	0.04		
Nov 2022	2.37	2.03	1.62	2.43	0.15			0.04	0.01	0.03	0.18	0.10		0.50			0.01		0.01				0.02	0.05		
Dec 2022	2.32	1.81	1.61	2.05	0.03			0.05	0.04	0.02	0.18	0.05		0.49			0.01		0.01			0.01	0.02	0.05		
Jan 2023	2.35	1.88	1.61	2.15	0.20			0.07	0.11	0.06	0.18	0.10		0.54			0.01		0.01			0.01	0.02	0.06		
Feb 2023	2.29	1.92	1.62	2.30	0.21			0.07	0.11	0.07	0.19	0.10		0.49			0.01		0.01			0.01	0.02	0.06	0.03	
Mar 2023	2.25	2.03	1.53	2.22	0.21	0.04		0.08	0.11	0.07	0.18	0.11		0.45	0.04		0.01		0.01			0.01	0.02	0.06		
Apr 2023	2.26	2.00	1.67	2.20	0.21	0.06		0.09	0.15	0.07	0.17	0.11	0.08	0.45	0.05		0.01		0.01			0.01	0.01			
May 2023	2.27	2.04	1.67	2.28	0.24	0.09		0.09	0.15	0.08	0.19	0.11	0.07	0.45	0.05		0.01		0.01		0.01	0.01	0.01			
Jun 2023	2.39	2.23	1.64	1.86	0.26	0.10		0.09	0.15	0.07	0.19	0.12	0.08	0.51	0.05		0.01		0.01		0.01	0.01	0.01			
Jul 2023	2.38	2.52	1.53	1.17	0.27	0.14	0.01	0.08	0.14	0.07	0.18	0.11	0.06	0.55	0.06		0.01		0.01		0.01	0.01	0.01			
Aug 2023	2.72	2.76	1.58	1.23	0.36	0.16	0.03	0.11	0.15	0.08	0.17	0.12	0.07	0.53	0.07	0.04	0.01		0.01		0.02	0.01				
Sep 2023	2.49	2.47	1.39	1.10	0.37	0.13	0.05	0.10	0.15	0.10	0.16	0.12	0.07	0.58	0.06	0.05	0.01		0.01		0.02	0.01				
Oct 2023	2.29	2.28	1.37	1.11	0.39	0.12	0.08	0.10	0.16	0.10	0.16	0.12	0.08	0.50	0.06	0.05	0.02		0.01		0.03	0.01				
Nov 2023	2.25	2.33	1.45	1.14	0.47	0.12	0.11	0.13	0.16	0.11	0.17	0.12	0.10	0.33	0.06	0.06	0.01		0.01		0.03					
Dec 2023	2.20	2.19	1.53	1.12	0.54	0.12	0.12	0.11	0.16	0.11	0.16	0.12	0.09	0.33	0.06	0.06	0.01		0.01		0.03					
Jan 2024	2.37	2.21	1.55	1.17	0.65	0.11	0.15	0.13	0.16	0.12	0.17	0.14	0.10	0.25	0.06	0.08	0.01	0.01	0.01		0.01					
Feb 2024	2.38	2.22	1.52	1.21	0.69	0.12	0.22	0.16	0.17	0.13	0.17	0.13	0.11	0.22	0.06	0.09	0.01	0.01	0.01							
Mar 2024	2.53	2.19	1.54	1.14	0.69	0.12	0.25	0.14	0.16	0.14	0.16	0.12	0.10	0.22	0.06	0.09	0.01	0.01	0.01							
Apr 2024	2.53	2.16	1.51	1.24	0.73	0.34	0.27	0.18	0.17	0.15	0.15	0.13	0.11	0.19	0.07	0.07	0.01	0.01	0.01	0.01						
May 2024	2.75	2.24	1.50	1.20	0.83	0.36	0.30	0.18	0.16	0.15	0.15	0.14	0.11	0.09	0.07	0.06	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

### Overall

At least one tracker was found on 19.77% of new episodes in May, growing 5.30% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "34.60%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.88%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.40%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.89%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.96%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.94%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.82%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.10%" >}}
9. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.85%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.63%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of May 2024.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 11.59% of new episodes in May, growing 7.50% from last month.

Of these, 14.23% had one other tracker, 11.48% had 2 other trackers, 2.09% had 3 other trackers, 0.96% had 5 other trackers, 0.88% had 4 other trackers, 0.35% had 6 other trackers, 0.24% had 7 other trackers, and 0.03% had 8 other trackers.

20.54% also included Chartable, 12.57% also included Podsights, 5.03% also included Adswizz, 5.00% also included Podscribe, 2.58% also included Podroll, 1.67% also included Spotify, 1.64% also included Magellan AI, 1.48% also included Podcorn, 0.91% also included ArtsAI, 0.89% also included Claritas, 0.88% also included Podder, 0.77% also included OP3, 0.55% also included Gumshoe, 0.54% also included Veritonic, 0.34% also included Blubrry, 0.30% also included Audiotakes, 0.05% also included Feedpress, 0.03% also included CoHost Prefix, 0.02% also included Médiamétrie, 0.02% also included Zencastr, 0.01% also included United Podcasters, 0.01% also included Podkite, and 0.01% also included AdBarker.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "58.62%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.00%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.16%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.24%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.95%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.99%" >}}
7. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.52%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.45%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.36%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.09%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 6.29% of new episodes in May, growing 3.33% from last month.

Of these, 43.82% also included Podtrac, 10.12% also included Podscribe, 7.12% also included Adswizz, 4.15% also included Magellan AI, 2.66% also included Podcorn, 2.30% also included Claritas, 2.23% also included ArtsAI, 1.90% also included Podroll, 1.78% also included Podder, 1.50% also included OP3, 1.45% also included Gumshoe, 1.06% also included Veritonic, 0.88% also included Audiotakes, 0.79% also included Firstory, 0.33% also included Blubrry, 0.10% also included United Podcasters, 0.09% also included CoHost Prefix, 0.05% also included Zencastr, 0.04% also included Podkite, 0.04% also included Feedpress, 0.03% also included AdBarker, 0.01% also included Voxalyze, and <0.01% also included Glystn.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.91%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "22.06%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.36%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.96%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.29%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.22%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.86%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.72%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.35%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.22%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.63% of new episodes in May, growing 2.83% from last month.

Of these, 29.71% had one other tracker, 21.00% had 2 other trackers, 4.42% had 3 other trackers, 1.92% had 5 other trackers, 1.87% had 4 other trackers, 0.81% had 6 other trackers, 0.42% had 7 other trackers, and 0.07% had 8 other trackers.

42.30% also included Podtrac, 28.89% also included Podsights, 8.64% also included Podscribe, 6.67% also included Adswizz, 4.38% also included Spotify, 4.03% also included Magellan AI, 2.28% also included Claritas, 2.22% also included Podcorn, 2.18% also included ArtsAI, 2.04% also included Podroll, 1.74% also included Podder, 1.05% also included OP3, 1.02% also included Veritonic, 0.94% also included Gumshoe, 0.88% also included Firstory, 0.51% also included Audiotakes, 0.28% also included Blubrry, 0.10% also included CoHost Prefix, 0.10% also included United Podcasters, 0.04% also included Zencastr, 0.04% also included Feedpress, 0.04% also included Podkite, 0.04% also included AdBarker, 0.01% also included Voxalyze, and <0.01% also included Glystn.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.23%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "21.45%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.46%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.20%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.61%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.56%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.89%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.61%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.53%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.48%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.75% of new episodes in May, growing 8.83% from last month.

Of these, 17.16% had one other tracker, 12.27% had 2 other trackers, 2.15% had 3 other trackers, 0.46% had 4 other trackers, 0.44% had 5 other trackers, 0.31% had 6 other trackers, 0.30% had 7 other trackers, and 0.12% had 8 other trackers.

21.16% also included Podtrac, 13.64% also included Chartable, 8.98% also included Podroll, 5.32% also included Podsights, 1.80% also included Podscribe, 1.03% also included Blubrry, 1.00% also included ArtsAI, 0.89% also included Claritas, 0.74% also included OP3, 0.66% also included Magellan AI, 0.64% also included Spotify, 0.54% also included Veritonic, 0.36% also included Podcorn, 0.14% also included Podder, 0.11% also included Audiotakes, 0.06% also included Gumshoe, and 0.02% also included United Podcasters.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "44.43%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "11.66%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "8.63%" >}}
4. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "7.31%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "6.29%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.03%" >}}
7. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "4.91%" >}}
8. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.73%" >}}
9. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.20%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.16%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.24% of new episodes in May, growing 3.73% from last month.

Of these, 37.96% had 2 other trackers, 31.46% had one other tracker, 9.42% had 3 other trackers, 5.88% had 5 other trackers, 5.03% had 4 other trackers, 2.20% had 6 other trackers, 1.06% had 7 other trackers, and 0.17% had 8 other trackers.

72.47% also included Chartable, 64.92% also included Podtrac, 20.72% also included Podscribe, 10.28% also included Magellan AI, 6.52% also included Adswizz, 5.79% also included Claritas, 4.92% also included ArtsAI, 3.64% also included Podder, 3.20% also included Spotify, 2.79% also included Gumshoe, 2.66% also included Podcorn, 2.44% also included Veritonic, 2.12% also included Podroll, 2.09% also included OP3, 1.88% also included Audiotakes, 0.25% also included Blubrry, 0.19% also included United Podcasters, 0.13% also included CoHost Prefix, 0.06% also included Feedpress, 0.05% also included Zencastr, 0.03% also included Podkite, and 0.01% also included Voxalyze.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "57.21%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "25.02%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.61%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.13%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.38%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.39%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.34%" >}}
8. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.10%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.00%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.93%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.50% of new episodes in May, shrinking 0.59% from last month.

Of these, 6.02% had one other tracker, 0.70% had 2 other trackers, 0.11% had 3 other trackers, 0.06% had 4 other trackers, 0.02% had 6 other trackers, and 0.01% had 5 other trackers.

2.60% also included Podtrac, 1.90% also included Adswizz, 1.16% also included Feedpress, 1.05% also included Chartable, 0.37% also included Podsights, 0.33% also included OP3, 0.25% also included Podcorn, 0.22% also included Podscribe, 0.07% also included Magellan AI, 0.06% also included Spotify, 0.04% also included Podder, 0.03% also included Podroll, 0.02% also included ArtsAI, 0.01% also included Audiotakes, and 0.01% also included Veritonic.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "38.93%" >}}
2. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "7.51%" >}}
3. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "6.70%" >}}
4. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "3.02%" >}}
5. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "2.97%" >}}
6. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "2.61%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.53%" >}}
8. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.80%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.68%" >}}
10. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "0.96%" >}}
---

### 6. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 1.20% of new episodes in May, shrinking 3.21% from last month.

Of these, 12.35% had one other tracker, 3.87% had 2 other trackers, 2.39% had 5 other trackers, 2.17% had 3 other trackers, 0.87% had 4 other trackers, 0.32% had 6 other trackers, 0.06% had 8 other trackers, and 0.02% had 7 other trackers.

14.27% also included Podtrac, 10.40% also included Chartable, 4.96% also included Podsights, 4.62% also included Podscribe, 3.76% also included Gumshoe, 3.73% also included OP3, 0.81% also included Adswizz, 0.52% also included Podder, 0.31% also included Blubrry, 0.31% also included Podroll, 0.20% also included Feedpress, 0.19% also included Spotify, 0.15% also included Magellan AI, 0.09% also included CoHost Prefix, 0.04% also included AdBarker, 0.04% also included Zencastr, 0.04% also included United Podcasters, 0.04% also included Veritonic, 0.02% also included Podkite, and 0.02% also included Voxalyze.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "45.54%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.02%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "8.87%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.23%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.09%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "5.01%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.99%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.98%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.68%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.40%" >}}
---

### 7. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.83% of new episodes in May, growing 14.12% from last month.

Of these, 22.19% had one other tracker, 19.07% had 2 other trackers, 18.04% had 3 other trackers, 15.42% had 5 other trackers, 11.36% had 4 other trackers, 5.94% had 6 other trackers, 3.33% had 7 other trackers, and 0.40% had 8 other trackers.

69.49% also included Podtrac, 58.27% also included Chartable, 55.69% also included Podsights, 26.11% also included Magellan AI, 16.40% also included Claritas, 14.91% also included Spotify, 14.37% also included ArtsAI, 6.86% also included Audiotakes, 6.66% also included Podcorn, 6.48% also included Veritonic, 5.94% also included Adswizz, 5.81% also included Gumshoe, 4.49% also included Podder, 3.89% also included OP3, 3.00% also included Podroll, 0.40% also included Blubrry, 0.28% also included United Podcasters, 0.06% also included Feedpress, and 0.04% also included Zencastr.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "51.10%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "15.49%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.55%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "5.35%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.76%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.74%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.54%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.21%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.61%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.46%" >}}
---

### 8. [Podroll](https://podroll.fm/)

Podroll was found on 0.36% of new episodes in May, growing 6.71% from last month.

Of these, 76.54% had 2 other trackers, 9.01% had 3 other trackers, 7.98% had one other tracker, 2.06% had 4 other trackers, 1.21% had 5 other trackers, 0.84% had 6 other trackers, 0.19% had 8 other trackers, and 0.17% had 7 other trackers.

82.01% also included Podtrac, 67.86% also included Adswizz, 31.45% also included Chartable, 13.09% also included Podsights, 6.87% also included Podscribe, 1.51% also included Podder, 1.41% also included Gumshoe, 1.38% also included Magellan AI, 1.26% also included Claritas, 1.16% also included OP3, 1.01% also included Podcorn, 0.37% also included ArtsAI, 0.20% also included CoHost Prefix, 0.19% also included United Podcasters, 0.17% also included Spotify, 0.11% also included Blubrry, and 0.06% also included Audiotakes.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "67.40%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "18.12%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.74%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.80%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "2.53%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.17%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.76%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.56%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.53%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.26%" >}}
---

### 9. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.30% of new episodes in May, growing 11.31% from last month.

Of these, 48.43% had 2 other trackers, 15.36% had one other tracker, 13.40% had 3 other trackers, 7.48% had 7 other trackers, 6.72% had 6 other trackers, 3.93% had 4 other trackers, 2.40% had 5 other trackers, and 1.06% had 8 other trackers.

82.46% also included Chartable, 64.61% also included Podtrac, 41.65% also included Podscribe, 24.01% also included Podsights, 18.11% also included Magellan AI, 15.76% also included ArtsAI, 8.07% also included Veritonic, 7.34% also included Claritas, 5.88% also included Adswizz, 5.74% also included Audiotakes, 4.19% also included Gumshoe, 1.32% also included Podder, 0.80% also included OP3, 0.75% also included Podcorn, 0.30% also included Blubrry, 0.21% also included Podroll, and 0.09% also included United Podcasters.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "49.88%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "16.11%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.51%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "6.96%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.70%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.74%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.39%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.84%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.36%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.30%" >}}
---

### 10. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.28% of new episodes in May, growing 1.48% from last month.

Of these, 29.05% had 5 other trackers, 22.25% had 4 other trackers, 13.34% had 6 other trackers, 12.87% had 3 other trackers, 8.97% had 7 other trackers, 7.21% had 2 other trackers, 4.46% had one other tracker, and 1.14% had 8 other trackers.

83.07% also included Podsights, 81.70% also included Chartable, 78.52% also included Podscribe, 68.59% also included Podtrac, 39.69% also included Claritas, 23.39% also included ArtsAI, 19.50% also included Spotify, 14.87% also included Veritonic, 14.10% also included Podder, 8.33% also included Audiotakes, 6.54% also included Adswizz, 1.95% also included Gumshoe, 1.82% also included Podroll, 0.66% also included Podcorn, 0.51% also included United Podcasters, 0.39% also included Blubrry, and 0.07% also included OP3.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "64.79%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.43%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.84%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.48%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.69%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.66%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.84%" >}}
8. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.30%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.19%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.19%" >}}
---

### 11. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.18% of new episodes in May, growing 3.73% from last month.

Of these, 23.79% had one other tracker, 19.16% had 2 other trackers, 15.35% had 5 other trackers, 5.77% had 4 other trackers, 5.49% had 3 other trackers, 1.99% had 6 other trackers, 0.37% had 8 other trackers, and 0.11% had 7 other trackers.

48.95% also included Podtrac, 32.46% also included Chartable, 25.61% also included Podsights, 24.56% also included Podcorn, 23.79% also included Gumshoe, 17.74% also included Podscribe, 11.20% also included Adswizz, 2.76% also included Podder, 2.70% also included Blubrry, 2.30% also included Podroll, 1.31% also included Spotify, 0.26% also included CoHost Prefix, 0.23% also included Feedpress, 0.11% also included Magellan AI, and 0.11% also included ArtsAI.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "34.11%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "11.48%" >}}
3. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "6.11%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.58%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.52%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.35%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.64%" >}}
8. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "2.62%" >}}
9. {{< a "https://vodio.fr/" "Vodio" >}} {{< span "weak" "2.36%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.19%" >}}
---

### 12. [Podder](https://www.podderapp.com/)

Podder was found on 0.16% of new episodes in May, shrinking 5.21% from last month.

Of these, 24.67% had one other tracker, 16.78% had 3 other trackers, 14.52% had 5 other trackers, 12.40% had 2 other trackers, 10.69% had 4 other trackers, 4.25% had 6 other trackers, 0.42% had 7 other trackers, and 0.42% had 8 other trackers.

63.03% also included Podtrac, 60.71% also included Chartable, 50.63% also included Podsights, 24.25% also included Magellan AI, 23.22% also included Podscribe, 3.90% also included Podcorn, 3.61% also included Claritas, 3.41% also included Podroll, 3.12% also included OP3, 2.87% also included Gumshoe, 2.45% also included Spotify, 2.42% also included Adswizz, 1.51% also included ArtsAI, 0.39% also included Blubrry, 0.35% also included Veritonic, 0.32% also included Zencastr, 0.29% also included United Podcasters, 0.29% also included CoHost Prefix, and 0.23% also included Podkite.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "56.65%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "13.91%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.38%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "7.15%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.38%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.19%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.16%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.87%" >}}
9. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "0.64%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.58%" >}}
---

### 13. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.15% of new episodes in May, growing 3.12% from last month.

Of these, 38.32% had 5 other trackers, 22.29% had 6 other trackers, 16.57% had 4 other trackers, 7.16% had 7 other trackers, 6.45% had 3 other trackers, 5.95% had 2 other trackers, and 1.38% had one other tracker.

88.50% also included Podscribe, 83.97% also included Podsights, 82.89% also included Chartable, 71.23% also included Magellan AI, 66.42% also included Podtrac, 29.92% also included ArtsAI, 15.87% also included Adswizz, 14.18% also included Spotify, 14.18% also included Veritonic, 3.76% also included Podder, 2.96% also included Podroll, 0.30% also included Feedpress, and 0.17% also included Gumshoe.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "58.42%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.22%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.02%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.61%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.41%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "5.34%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.18%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.30%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.24%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.20%" >}}
---

### 14. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.15% of new episodes in May, shrinking 1.20% from last month.

Of these, 16.47% had one other tracker, 0.95% had 2 other trackers, and 0.31% had 5 other trackers.

11.44% also included Blubrry, 3.51% also included Podtrac, 1.57% also included Podcorn, 1.57% also included Chartable, 0.95% also included Podsights, 0.31% also included Podscribe, 0.31% also included Claritas, and 0.27% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "48.60%" >}}
2. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "8.34%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.03%" >}}
4. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "5.34%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.94%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.21%" >}}
7. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "2.11%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.97%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.77%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.16%" >}}
---

### 15. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.14% of new episodes in May, growing 8.16% from last month.

Of these, 28.10% had 5 other trackers, 18.82% had 7 other trackers, 17.98% had 3 other trackers, 14.55% had 6 other trackers, 10.11% had 4 other trackers, 7.30% had 2 other trackers, 2.20% had 8 other trackers, and 0.79% had one other tracker.

85.30% also included Chartable, 83.32% also included Podscribe, 76.71% also included Podsights, 73.46% also included Podtrac, 45.11% also included Magellan AI, 32.72% also included Spotify, 32.14% also included Claritas, 24.20% also included Veritonic, 19.07% also included Adswizz, 11.88% also included Audiotakes, 1.70% also included Podder, 0.94% also included Podroll, 0.18% also included Blubrry, 0.14% also included OP3, and 0.07% also included Gumshoe.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "35.68%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.51%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.83%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.73%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.55%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "6.54%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.81%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.26%" >}}
9. {{< a "https://swap.fm/" "swap.fm" >}} {{< span "weak" "0.69%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.61%" >}}
---

### 16. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.11% of new episodes in May, growing 2.48% from last month.

Of these, 29.39% had 5 other trackers, 15.66% had 2 other trackers, 15.57% had 4 other trackers, 13.11% had 3 other trackers, 11.69% had one other tracker, 3.31% had 6 other trackers, 0.62% had 8 other trackers, and 0.19% had 7 other trackers.

57.69% also included Podtrac, 56.98% also included Podsights, 48.23% also included Chartable, 44.16% also included Podscribe, 41.22% also included Podcorn, 39.61% also included OP3, 11.41% also included Spotify, 4.92% also included Magellan AI, 4.69% also included Podroll, 4.21% also included Podder, 1.51% also included Adswizz, 1.04% also included Audiotakes, 1.04% also included United Podcasters, 0.43% also included CoHost Prefix, 0.24% also included Claritas, 0.24% also included Veritonic, and 0.09% also included ArtsAI.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "39.75%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "28.06%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "20.78%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.81%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.85%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.99%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.57%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.38%" >}}
9. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.28%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.24%" >}}
---

### 17. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.09% of new episodes in May, shrinking 50.67% from last month.

Of these, 2.63% had one other tracker.

2.63% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "41.63%" >}}
2. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "34.86%" >}}
3. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "19.19%" >}}
---

### 18. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.07% of new episodes in May, growing 0.45% from last month.

Of these, 34.23% had 7 other trackers, 20.46% had 6 other trackers, 12.92% had 4 other trackers, 11.15% had 5 other trackers, 8.08% had 2 other trackers, 7.69% had 3 other trackers, 4.69% had 8 other trackers, and 0.31% had one other tracker.

92.92% also included Podtrac, 84.69% also included Chartable, 81.00% also included Podsights, 80.08% also included Podscribe, 61.08% also included Magellan AI, 51.54% also included ArtsAI, 35.69% also included Spotify, 32.46% also included Claritas, 21.92% also included Adswizz, 3.38% also included Audiotakes, 0.85% also included Podder, 0.69% also included Podcorn, 0.38% also included Gumshoe, and 0.23% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "63.92%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "19.31%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.15%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "5.00%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.62%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.31%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.85%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.38%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.38%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.08%" >}}
---

### 19. [Firstory](https://firstory.me/)

Firstory was found on 0.06% of new episodes in May, shrinking 3.25% from last month.

Of these, 76.70% had one other tracker.

76.70% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.60%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.40%" >}}
---

### 20. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.06% of new episodes in May, shrinking 17.79% from last month.

Of these, 33.36% had 4 other trackers, 26.76% had 3 other trackers, 15.93% had 5 other trackers, 12.24% had 6 other trackers, 8.10% had 2 other trackers, and 1.58% had one other tracker.

97.01% also included Podscribe, 71.39% also included Podsights, 58.01% also included Podtrac, 48.94% also included Chartable, 39.17% also included Magellan AI, 29.05% also included Spotify, 28.96% also included ArtsAI, 5.19% also included Adswizz, 3.87% also included Veritonic, 1.94% also included Gumshoe, 0.44% also included United Podcasters, 0.35% also included Podroll, and 0.26% also included Blubrry.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "36.88%" >}}
2. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "34.24%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "13.91%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.43%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.17%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.82%" >}}
7. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "2.02%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.32%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.32%" >}}
10. {{< a "https://swap.fm/" "swap.fm" >}} {{< span "weak" "0.44%" >}}
---

### 21. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in May, shrinking 16.28% from last month.

Of these, 17.95% had one other tracker, 14.87% had 2 other trackers, 2.56% had 4 other trackers, 1.54% had 5 other trackers, and 1.03% had 3 other trackers.

24.10% also included Chartable, 18.46% also included Podtrac, 10.26% also included Podsights, 5.13% also included Podcorn, 5.13% also included Podder, 3.08% also included Podscribe, and 2.56% also included United Podcasters.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "39.49%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "21.03%" >}}
3. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "11.79%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "11.79%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.15%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.10%" >}}
7. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "2.56%" >}}
8. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "2.56%" >}}
9. {{< a "https://www.blogtalkradio.com/" "Blog Talk Radio" >}} {{< span "weak" "0.51%" >}}
---

### 22. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in May, growing 19.32% from last month.

Of these, 40.72% had one other tracker, 16.77% had 3 other trackers, 16.77% had 4 other trackers, 7.19% had 2 other trackers, 6.59% had 5 other trackers, and 2.99% had 6 other trackers.

64.07% also included Chartable, 49.10% also included Podsights, 26.95% also included Podscribe, 19.76% also included Podtrac, 16.17% also included Magellan AI, 13.17% also included Gumshoe, 7.78% also included Podroll, 6.59% also included Adswizz, 5.39% also included Podcorn, 5.39% also included Podder, 2.99% also included Spotify, 2.99% also included Audiotakes, and 2.99% also included Zencastr.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "36.53%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "16.77%" >}}
3. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "16.77%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.78%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.59%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.99%" >}}
7. {{< a "https://swap.fm/" "swap.fm" >}} {{< span "weak" "3.59%" >}}
8. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.80%" >}}
9. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "1.20%" >}}
---

### 23. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in May, shrinking 2.97% from last month.

Of these, 29.14% had one other tracker, 5.96% had 2 other trackers, 2.65% had 5 other trackers, and 1.99% had 4 other trackers.

29.14% also included Chartable, 17.88% also included Podtrac, 7.95% also included Podsights, 4.64% also included Podder, and 2.65% also included Podcorn.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "36.42%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "15.23%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "13.91%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "13.25%" >}}
5. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "5.96%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.96%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.97%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.97%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.32%" >}}
---

### 24. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.01% of new episodes in May, growing 6.00% from last month.

Of these, 35.48% had 2 other trackers, 34.68% had 3 other trackers, 10.48% had one other tracker, and 7.26% had 8 other trackers.

87.10% also included Chartable, 59.68% also included Podtrac, 46.77% also included Podsights, 16.94% also included Podcorn, 11.29% also included Podroll, 7.26% also included OP3, 7.26% also included Podder, and 7.26% also included Gumshoe.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "40.32%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.74%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "14.52%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "11.29%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "8.87%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.65%" >}}
7. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "0.81%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.81%" >}}
---

### 25. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in May, shrinking 17.36% from last month.

Of these, 30.49% had 2 other trackers, 20.73% had one other tracker, and 1.22% had 3 other trackers.

47.56% also included Chartable, 25.61% also included Podtrac, and 12.20% also included Podcorn.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "42.68%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "20.73%" >}}
3. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "12.20%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "9.76%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.10%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.88%" >}}
7. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "3.66%" >}}
---

### 26. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on <0.01% of new episodes in May, shrinking 9.89% from last month.

Of these, 50.00% had one other tracker, and 25.00% had 2 other trackers.

50.00% also included Chartable, 25.00% also included Podcorn, and 25.00% also included Podsights.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "56.25%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "25.00%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "18.75%" >}}
---

### 27. [Glystn](https://glystn.com/)

Glystn was found on <0.01% of new episodes in May, shrinking 23.41% from last month.

Of these, 100.00% had one other tracker.

100.00% also included Chartable.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "100.00%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
*Updated 2024-06-01, with data for the month of May 2024.*

*Updated 2024-05-01, with data for the month of April 2024.*

*Updated 2024-04-01, with data for the month of March 2024.*

*Updated 2024-03-02, with data for the month of February 2024.*

*Updated 2024-02-02, with data for the month of January 2024.*

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
 - [Podcast Tracker Rankings by Episode Share (April 2024)](/archive/podcast-trackers-by-episode-share-april-2024/)
 - [Podcast Tracker Rankings by Episode Share (March 2024)](/archive/podcast-trackers-by-episode-share-march-2024/)
 - [Podcast Tracker Rankings by Episode Share (February 2024)](/archive/podcast-trackers-by-episode-share-february-2024/)
 - [Podcast Tracker Rankings by Episode Share (January 2024)](/archive/podcast-trackers-by-episode-share-january-2024/)
 - [Podcast Tracker Rankings by Episode Share (December 2023)](/archive/podcast-trackers-by-episode-share-december-2023/)
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2024-05.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
