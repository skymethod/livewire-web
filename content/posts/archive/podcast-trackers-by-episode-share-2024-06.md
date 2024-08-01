---
title: "Top Podcast Tracking Services by Episode Share (June 2024)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-june-2024"
images:
- trackers-2024-06.png
date: 2024-07-01T17:29:00-05:00
lastmod: 2024-07-01T17:29:00-05:00
draft: false
rssrevision: 2024-06
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.8 million in June 2024), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in June, how many
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
Month	Podtrac	Chartable	Adswizz	Podsights	Blubrry	Podscribe	Podcorn	Podroll	Spotify	OP3	Claritas	ArtsAI	Feedpress	Podder	Gumshoe	Médiamétrie	Audiotakes	Veritonic	Swap.fm	Zencastr	Podkite	United Podcasters	CoHost Prefix	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.00	1.16	2.07		2.09						0.32			0.42													1.61
Oct 2021	4.05	4.09	1.01	1.20	2.11		2.13						0.34			0.54													1.61
Nov 2021	4.07	4.30	1.02	1.25	2.01		2.14						0.32			0.57													0.59
Dec 2021	4.06	4.42	1.24	1.19	1.57		2.27						0.19			0.59													
Jan 2022	4.11	4.45	1.41	1.21	1.56		2.31						0.16			0.63													
Feb 2022	4.15	4.48	1.44	1.25	1.53		2.38						0.17			0.58													
Mar 2022	4.37	4.72	1.51	1.34	1.56		2.40						0.17			0.53													
Apr 2022	4.44	4.71	1.49	1.33	1.55		2.33						0.16			0.51													
May 2022	4.49	4.87	1.58	1.41	1.48		2.26						0.17			0.56													
Jun 2022	4.75	5.10	1.77	1.54	1.50		2.06						0.21			0.62										0.02			
Jul 2022	4.70	5.10	1.89	1.50	1.50		2.16						0.25			0.54										0.02			
Aug 2022	4.83	5.26	2.08	1.73	1.51		2.45					0.10	0.20			0.41										0.01			
Sep 2022	7.53	5.40	2.26	1.74	1.49	0.02	2.45				0.01	0.09	0.21			0.52					0.01					0.02	0.02		
Oct 2022	8.24	5.48	2.35	1.81	1.61	0.07	2.51			0.03	0.02	0.10	0.18			0.50				0.01	0.01					0.02	0.04		
Nov 2022	8.11	5.62	2.37	2.03	1.62	0.15	2.43			0.04	0.03	0.10	0.18	0.01		0.50				0.01	0.01					0.02	0.05		
Dec 2022	8.01	5.54	2.32	1.81	1.61	0.03	2.05			0.05	0.02	0.05	0.18	0.04		0.49				0.01	0.01				0.01	0.02	0.05		
Jan 2023	7.85	5.56	2.35	1.88	1.61	0.20	2.15			0.07	0.06	0.10	0.18	0.11		0.54				0.01	0.01				0.01	0.02	0.06		
Feb 2023	7.58	5.51	2.29	1.92	1.62	0.21	2.30			0.07	0.07	0.10	0.19	0.11		0.49				0.01	0.01				0.01	0.02	0.06	0.03	
Mar 2023	7.79	5.53	2.25	2.03	1.53	0.21	2.22	0.04		0.08	0.07	0.11	0.18	0.11		0.45		0.04		0.01	0.01				0.01	0.02	0.06		
Apr 2023	7.66	5.43	2.26	2.00	1.67	0.21	2.20	0.06		0.09	0.07	0.11	0.17	0.15	0.08	0.45		0.05		0.01	0.01				0.01	0.01			
May 2023	7.58	5.59	2.27	2.04	1.67	0.24	2.28	0.09		0.09	0.08	0.11	0.19	0.15	0.07	0.45		0.05		0.01	0.01			0.01	0.01	0.01			
Jun 2023	8.22	5.83	2.39	2.23	1.64	0.26	1.86	0.10		0.09	0.07	0.12	0.19	0.15	0.08	0.51		0.05		0.01	0.01			0.01	0.01	0.01			
Jul 2023	8.60	5.95	2.38	2.52	1.53	0.27	1.17	0.14	0.01	0.08	0.07	0.11	0.18	0.14	0.06	0.55		0.06		0.01	0.01			0.01	0.01	0.01			
Aug 2023	9.19	6.43	2.72	2.76	1.58	0.36	1.23	0.16	0.03	0.11	0.08	0.12	0.17	0.15	0.07	0.53	0.04	0.07		0.01	0.01			0.02	0.01				
Sep 2023	8.46	5.77	2.49	2.47	1.39	0.37	1.10	0.13	0.05	0.10	0.10	0.12	0.16	0.15	0.07	0.58	0.05	0.06		0.01	0.01			0.02	0.01				
Oct 2023	7.90	5.54	2.29	2.28	1.37	0.39	1.11	0.12	0.08	0.10	0.10	0.12	0.16	0.16	0.08	0.50	0.05	0.06		0.02	0.01			0.03	0.01				
Nov 2023	7.65	5.59	2.25	2.33	1.45	0.47	1.14	0.12	0.11	0.13	0.11	0.12	0.17	0.16	0.10	0.33	0.06	0.06		0.01	0.01			0.03					
Dec 2023	7.48	5.60	2.20	2.19	1.53	0.54	1.12	0.12	0.12	0.11	0.11	0.12	0.16	0.16	0.09	0.33	0.06	0.06		0.01	0.01			0.03					
Jan 2024	7.64	5.61	2.37	2.21	1.55	0.65	1.17	0.11	0.15	0.13	0.12	0.14	0.17	0.16	0.10	0.25	0.08	0.06		0.01	0.01	0.01		0.01					
Feb 2024	7.69	5.58	2.38	2.22	1.52	0.69	1.21	0.12	0.22	0.16	0.13	0.13	0.17	0.17	0.11	0.22	0.09	0.06		0.01	0.01	0.01							
Mar 2024	9.01	5.46	2.53	2.19	1.54	0.69	1.14	0.12	0.25	0.14	0.14	0.12	0.16	0.16	0.10	0.22	0.09	0.06		0.01	0.01	0.01							
Apr 2024	10.78	5.47	2.53	2.16	1.51	0.73	1.24	0.34	0.27	0.18	0.15	0.13	0.15	0.17	0.11	0.19	0.07	0.07		0.01	0.01	0.01	0.01						
May 2024	11.59	5.63	2.75	2.24	1.50	0.83	1.20	0.36	0.30	0.18	0.15	0.14	0.15	0.16	0.11	0.09	0.06	0.07		0.01	0.01	0.01	0.01						
Jun 2024	11.54	6.06	2.88	2.34	1.52	0.91	0.71	0.37	0.32	0.20	0.16	0.16	0.15	0.15	0.11	0.10	0.07	0.07	0.03	0.01	0.01	0.01	0.01											
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} are the clear top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podsights	Blubrry	Podscribe	Podcorn	Podroll	Spotify	OP3	Claritas	ArtsAI	Feedpress	Podder	Gumshoe	Médiamétrie	Audiotakes	Veritonic	Swap.fm	Zencastr	Podkite	United Podcasters	CoHost Prefix	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	1.00	1.16	2.07		2.09						0.32			0.42													1.61
Oct 2021	1.01	1.20	2.11		2.13						0.34			0.54													1.61
Nov 2021	1.02	1.25	2.01		2.14						0.32			0.57													0.59
Dec 2021	1.24	1.19	1.57		2.27						0.19			0.59													
Jan 2022	1.41	1.21	1.56		2.31						0.16			0.63													
Feb 2022	1.44	1.25	1.53		2.38						0.17			0.58													
Mar 2022	1.51	1.34	1.56		2.40						0.17			0.53													
Apr 2022	1.49	1.33	1.55		2.33						0.16			0.51													
May 2022	1.58	1.41	1.48		2.26						0.17			0.56													
Jun 2022	1.77	1.54	1.50		2.06						0.21			0.62										0.02			
Jul 2022	1.89	1.50	1.50		2.16						0.25			0.54										0.02			
Aug 2022	2.08	1.73	1.51		2.45					0.10	0.20			0.41										0.01			
Sep 2022	2.26	1.74	1.49	0.02	2.45				0.01	0.09	0.21			0.52					0.01					0.02	0.02		
Oct 2022	2.35	1.81	1.61	0.07	2.51			0.03	0.02	0.10	0.18			0.50				0.01	0.01					0.02	0.04		
Nov 2022	2.37	2.03	1.62	0.15	2.43			0.04	0.03	0.10	0.18	0.01		0.50				0.01	0.01					0.02	0.05		
Dec 2022	2.32	1.81	1.61	0.03	2.05			0.05	0.02	0.05	0.18	0.04		0.49				0.01	0.01				0.01	0.02	0.05		
Jan 2023	2.35	1.88	1.61	0.20	2.15			0.07	0.06	0.10	0.18	0.11		0.54				0.01	0.01				0.01	0.02	0.06		
Feb 2023	2.29	1.92	1.62	0.21	2.30			0.07	0.07	0.10	0.19	0.11		0.49				0.01	0.01				0.01	0.02	0.06	0.03	
Mar 2023	2.25	2.03	1.53	0.21	2.22	0.04		0.08	0.07	0.11	0.18	0.11		0.45		0.04		0.01	0.01				0.01	0.02	0.06		
Apr 2023	2.26	2.00	1.67	0.21	2.20	0.06		0.09	0.07	0.11	0.17	0.15	0.08	0.45		0.05		0.01	0.01				0.01	0.01			
May 2023	2.27	2.04	1.67	0.24	2.28	0.09		0.09	0.08	0.11	0.19	0.15	0.07	0.45		0.05		0.01	0.01			0.01	0.01	0.01			
Jun 2023	2.39	2.23	1.64	0.26	1.86	0.10		0.09	0.07	0.12	0.19	0.15	0.08	0.51		0.05		0.01	0.01			0.01	0.01	0.01			
Jul 2023	2.38	2.52	1.53	0.27	1.17	0.14	0.01	0.08	0.07	0.11	0.18	0.14	0.06	0.55		0.06		0.01	0.01			0.01	0.01	0.01			
Aug 2023	2.72	2.76	1.58	0.36	1.23	0.16	0.03	0.11	0.08	0.12	0.17	0.15	0.07	0.53	0.04	0.07		0.01	0.01			0.02	0.01				
Sep 2023	2.49	2.47	1.39	0.37	1.10	0.13	0.05	0.10	0.10	0.12	0.16	0.15	0.07	0.58	0.05	0.06		0.01	0.01			0.02	0.01				
Oct 2023	2.29	2.28	1.37	0.39	1.11	0.12	0.08	0.10	0.10	0.12	0.16	0.16	0.08	0.50	0.05	0.06		0.02	0.01			0.03	0.01				
Nov 2023	2.25	2.33	1.45	0.47	1.14	0.12	0.11	0.13	0.11	0.12	0.17	0.16	0.10	0.33	0.06	0.06		0.01	0.01			0.03					
Dec 2023	2.20	2.19	1.53	0.54	1.12	0.12	0.12	0.11	0.11	0.12	0.16	0.16	0.09	0.33	0.06	0.06		0.01	0.01			0.03					
Jan 2024	2.37	2.21	1.55	0.65	1.17	0.11	0.15	0.13	0.12	0.14	0.17	0.16	0.10	0.25	0.08	0.06		0.01	0.01	0.01		0.01					
Feb 2024	2.38	2.22	1.52	0.69	1.21	0.12	0.22	0.16	0.13	0.13	0.17	0.17	0.11	0.22	0.09	0.06		0.01	0.01	0.01							
Mar 2024	2.53	2.19	1.54	0.69	1.14	0.12	0.25	0.14	0.14	0.12	0.16	0.16	0.10	0.22	0.09	0.06		0.01	0.01	0.01							
Apr 2024	2.53	2.16	1.51	0.73	1.24	0.34	0.27	0.18	0.15	0.13	0.15	0.17	0.11	0.19	0.07	0.07		0.01	0.01	0.01	0.01						
May 2024	2.75	2.24	1.50	0.83	1.20	0.36	0.30	0.18	0.15	0.14	0.15	0.16	0.11	0.09	0.06	0.07		0.01	0.01	0.01	0.01						
Jun 2024	2.88	2.34	1.52	0.91	0.71	0.37	0.32	0.20	0.16	0.16	0.15	0.15	0.11	0.10	0.07	0.07	0.03	0.01	0.01	0.01	0.01												
{{< /graph >}}

---

### Overall

At least one tracker was found on 19.76% of new episodes in June, shrinking 0.02% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "34.06%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.24%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.29%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.98%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.91%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.90%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.17%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.84%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.66%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.56%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of June 2024.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 11.54% of new episodes in June, shrinking 0.47% from last month.

Of these, 14.68% had one other tracker, 11.88% had 2 other trackers, 2.21% had 3 other trackers, 0.99% had 5 other trackers, 0.96% had 4 other trackers, 0.37% had 6 other trackers, 0.25% had 7 other trackers, and 0.04% had 8 other trackers.

21.21% also included Chartable, 13.09% also included Podsights, 5.48% also included Podscribe, 5.00% also included Adswizz, 2.61% also included Podroll, 1.71% also included Magellan AI, 1.71% also included Spotify, 1.59% also included Podcorn, 0.94% also included ArtsAI, 0.94% also included Claritas, 0.88% also included OP3, 0.84% also included Podder, 0.57% also included Gumshoe, 0.53% also included Veritonic, 0.36% also included Audiotakes, 0.35% also included Blubrry, 0.14% also included Swap.fm, 0.04% also included Feedpress, 0.02% also included Médiamétrie, 0.02% also included CoHost Prefix, 0.02% also included Podkite, 0.02% also included United Podcasters, 0.01% also included Zencastr, and 0.01% also included AdBarker.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "58.01%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.34%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.43%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.20%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.93%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.04%" >}}
7. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.52%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.46%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.45%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.06%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 6.75% of new episodes in June, growing 7.30% from last month.

Of these, 41.88% also included Podtrac, 9.85% also included Podscribe, 6.67% also included Adswizz, 4.05% also included Magellan AI, 2.50% also included Podcorn, 2.25% also included Claritas, 2.21% also included ArtsAI, 1.96% also included Podroll, 1.56% also included Podder, 1.44% also included OP3, 1.38% also included Gumshoe, 1.02% also included Audiotakes, 0.99% also included Veritonic, 0.73% also included Firstory, 0.51% also included Swap.fm, 0.30% also included Blubrry, 0.09% also included United Podcasters, 0.06% also included CoHost Prefix, 0.06% also included Podkite, 0.03% also included Zencastr, 0.03% also included AdBarker, 0.02% also included Feedpress, 0.01% also included Voxalyze, and <0.01% also included Glystn.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.58%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "26.26%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.88%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.60%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.28%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.99%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.80%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.56%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.18%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.13%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 6.06% of new episodes in June, growing 7.62% from last month.

Of these, 27.80% had one other tracker, 20.34% had 2 other trackers, 4.31% had 3 other trackers, 1.90% had 4 other trackers, 1.81% had 5 other trackers, 0.83% had 6 other trackers, 0.41% had 7 other trackers, and 0.07% had 8 other trackers.

40.39% also included Podtrac, 28.01% also included Podsights, 8.42% also included Podscribe, 6.08% also included Adswizz, 4.33% also included Spotify, 3.89% also included Magellan AI, 2.22% also included Claritas, 2.15% also included ArtsAI, 2.10% also included Podroll, 2.05% also included Podcorn, 1.50% also included Podder, 0.96% also included OP3, 0.93% also included Veritonic, 0.84% also included Gumshoe, 0.82% also included Firstory, 0.60% also included Audiotakes, 0.56% also included Swap.fm, 0.27% also included Blubrry, 0.10% also included United Podcasters, 0.07% also included CoHost Prefix, 0.06% also included Podkite, 0.03% also included AdBarker, 0.03% also included Zencastr, 0.03% also included Feedpress, 0.01% also included Voxalyze, and <0.01% also included Glystn.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "27.81%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "26.02%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.93%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.81%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.56%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.35%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.72%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.45%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.43%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.35%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.88% of new episodes in June, growing 4.50% from last month.

Of these, 16.69% had one other tracker, 11.18% had 2 other trackers, 2.15% had 3 other trackers, 0.49% had 4 other trackers, 0.35% had 5 other trackers, 0.35% had 6 other trackers, 0.34% had 7 other trackers, and 0.12% had 8 other trackers.

20.05% also included Podtrac, 12.80% also included Chartable, 8.47% also included Podroll, 5.49% also included Podsights, 1.93% also included Podscribe, 1.12% also included ArtsAI, 1.01% also included Blubrry, 0.89% also included Claritas, 0.67% also included Magellan AI, 0.63% also included Spotify, 0.54% also included Veritonic, 0.43% also included OP3, 0.27% also included Podcorn, 0.13% also included Audiotakes, 0.10% also included Podder, 0.04% also included Swap.fm, 0.04% also included Gumshoe, 0.02% also included United Podcasters, and <0.01% also included Feedpress.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "42.90%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "11.42%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "8.33%" >}}
4. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "8.21%" >}}
5. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "7.35%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.90%" >}}
7. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "5.14%" >}}
8. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.92%" >}}
9. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "1.22%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.21%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.34% of new episodes in June, growing 4.41% from last month.

Of these, 37.86% had 2 other trackers, 30.79% had one other tracker, 9.71% had 3 other trackers, 5.79% had 5 other trackers, 5.19% had 4 other trackers, 2.28% had 6 other trackers, 1.06% had 7 other trackers, and 0.17% had 8 other trackers.

72.41% also included Chartable, 64.44% also included Podtrac, 20.59% also included Podscribe, 10.15% also included Magellan AI, 6.75% also included Adswizz, 5.78% also included Claritas, 4.95% also included ArtsAI, 3.33% also included Spotify, 3.22% also included Podder, 2.80% also included Gumshoe, 2.67% also included Podcorn, 2.43% also included Podroll, 2.33% also included Audiotakes, 2.33% also included OP3, 2.30% also included Veritonic, 0.69% also included Swap.fm, 0.20% also included Blubrry, 0.19% also included United Podcasters, 0.13% also included CoHost Prefix, 0.08% also included Podkite, 0.04% also included Zencastr, 0.03% also included Feedpress, and <0.01% also included Voxalyze.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "56.66%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "26.35%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.51%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.08%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.38%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.38%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.28%" >}}
8. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.04%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.03%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.94%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.52% of new episodes in June, growing 0.82% from last month.

Of these, 6.05% had one other tracker, 0.65% had 2 other trackers, 0.12% had 3 other trackers, 0.07% had 4 other trackers, 0.02% had 5 other trackers, and 0.02% had 6 other trackers.

2.68% also included Podtrac, 1.92% also included Adswizz, 1.20% also included Feedpress, 1.07% also included Chartable, 0.32% also included OP3, 0.31% also included Podsights, 0.23% also included Podcorn, 0.21% also included Podscribe, 0.06% also included Spotify, 0.06% also included Magellan AI, 0.04% also included Podder, 0.03% also included Podroll, 0.02% also included Audiotakes, 0.02% also included Veritonic, and 0.01% also included ArtsAI.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "37.76%" >}}
2. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "11.35%" >}}
3. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "6.91%" >}}
4. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "2.75%" >}}
5. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "2.73%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.07%" >}}
7. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.92%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.72%" >}}
9. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.02%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "0.97%" >}}
---

### 6. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 0.91% of new episodes in June, growing 8.64% from last month.

Of these, 23.72% had one other tracker, 18.33% had 2 other trackers, 17.79% had 3 other trackers, 14.79% had 5 other trackers, 11.52% had 4 other trackers, 5.95% had 6 other trackers, 3.25% had 7 other trackers, and 0.39% had 8 other trackers.

69.76% also included Podtrac, 56.25% also included Chartable, 53.19% also included Podsights, 25.37% also included Magellan AI, 16.13% also included Claritas, 14.69% also included ArtsAI, 14.66% also included Spotify, 7.81% also included Audiotakes, 7.39% also included Podcorn, 6.14% also included Adswizz, 5.89% also included Veritonic, 5.69% also included Gumshoe, 4.02% also included OP3, 3.70% also included Podder, 3.03% also included Podroll, 0.84% also included Swap.fm, 0.35% also included Blubrry, 0.29% also included United Podcasters, 0.06% also included Zencastr, 0.03% also included Feedpress, and 0.01% also included AdBarker.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "49.60%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "18.62%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.76%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.92%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.04%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.64%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.36%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.21%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.66%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.38%" >}}
---

### 7. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.71% of new episodes in June, shrinking 41.03% from last month.

Of these, 20.34% had one other tracker, 6.35% had 2 other trackers, 4.46% had 3 other trackers, 4.40% had 5 other trackers, 1.65% had 4 other trackers, 0.60% had 6 other trackers, 0.09% had 8 other trackers, and 0.03% had 7 other trackers.

25.87% also included Podtrac, 17.50% also included Chartable, 9.44% also included Podscribe, 8.81% also included Podsights, 7.06% also included OP3, 6.87% also included Gumshoe, 1.09% also included Adswizz, 0.76% also included Podder, 0.59% also included Podroll, 0.48% also included Blubrry, 0.27% also included Spotify, 0.25% also included Magellan AI, 0.16% also included Feedpress, 0.11% also included CoHost Prefix, 0.09% also included Swap.fm, 0.06% also included AdBarker, 0.05% also included United Podcasters, 0.03% also included Podkite, and 0.03% also included Voxalyze.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "20.22%" >}}
2. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "15.32%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "12.24%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "11.22%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "8.82%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "8.21%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.34%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "5.34%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.69%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.52%" >}}
---

### 8. [Podroll](https://podroll.fm/)

Podroll was found on 0.37% of new episodes in June, growing 2.52% from last month.

Of these, 75.95% had 2 other trackers, 9.01% had 3 other trackers, 8.90% had one other tracker, 2.22% had 4 other trackers, 1.22% had 5 other trackers, 0.92% had 6 other trackers, 0.34% had 7 other trackers, and 0.17% had 8 other trackers.

80.56% also included Podtrac, 65.29% also included Adswizz, 34.08% also included Chartable, 15.24% also included Podsights, 7.36% also included Podscribe, 1.47% also included Claritas, 1.39% also included Podder, 1.32% also included Magellan AI, 1.22% also included Gumshoe, 1.12% also included Podcorn, 1.09% also included OP3, 0.70% also included ArtsAI, 0.31% also included Spotify, 0.28% also included Swap.fm, 0.23% also included CoHost Prefix, 0.14% also included United Podcasters, 0.12% also included Blubrry, 0.12% also included Audiotakes, and 0.02% also included Feedpress.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "64.80%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "19.76%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.56%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.97%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "2.37%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.19%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.89%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.54%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.41%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.38%" >}}
---

### 9. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.32% of new episodes in June, growing 5.51% from last month.

Of these, 48.25% had 2 other trackers, 14.82% had one other tracker, 12.21% had 3 other trackers, 7.41% had 7 other trackers, 7.21% had 6 other trackers, 4.85% had 4 other trackers, 2.46% had 5 other trackers, and 1.10% had 8 other trackers.

83.16% also included Chartable, 62.45% also included Podtrac, 42.17% also included Podscribe, 24.74% also included Podsights, 18.84% also included Magellan AI, 16.95% also included ArtsAI, 7.88% also included Claritas, 7.68% also included Veritonic, 6.47% also included Audiotakes, 5.74% also included Adswizz, 3.84% also included Gumshoe, 1.38% also included Podder, 0.85% also included OP3, 0.60% also included Podcorn, 0.36% also included Podroll, 0.29% also included Blubrry, 0.20% also included Swap.fm, and 0.04% also included United Podcasters.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "51.89%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "14.62%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.46%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "6.85%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.67%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.15%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.12%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.57%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.49%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.34%" >}}
---

### 10. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.29% of new episodes in June, growing 5.36% from last month.

Of these, 28.90% had 5 other trackers, 21.66% had 4 other trackers, 13.45% had 3 other trackers, 13.24% had 6 other trackers, 8.75% had 7 other trackers, 7.23% had 2 other trackers, 4.98% had one other tracker, and 1.17% had 8 other trackers.

81.29% also included Podsights, 80.47% also included Chartable, 78.66% also included Podscribe, 67.51% also included Podtrac, 40.19% also included Claritas, 24.68% also included ArtsAI, 20.31% also included Spotify, 14.16% also included Veritonic, 12.46% also included Podder, 9.16% also included Audiotakes, 6.56% also included Adswizz, 1.97% also included Gumshoe, 1.68% also included Podroll, 0.61% also included Podcorn, 0.59% also included United Podcasters, 0.29% also included Blubrry, 0.29% also included Swap.fm, and 0.10% also included OP3.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "64.09%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.65%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "7.26%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.01%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.13%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.86%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.78%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.29%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.23%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.16%" >}}
---

### 11. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.20% of new episodes in June, growing 6.94% from last month.

Of these, 24.32% had one other tracker, 15.77% had 5 other trackers, 14.01% had 2 other trackers, 7.62% had 3 other trackers, 5.96% had 4 other trackers, 2.10% had 6 other trackers, 0.29% had 8 other trackers, and 0.03% had 7 other trackers.

52.03% also included Podtrac, 29.75% also included Chartable, 27.85% also included Podsights, 25.61% also included Podcorn, 23.77% also included Gumshoe, 18.66% also included Podscribe, 6.36% also included Adswizz, 2.45% also included Blubrry, 2.25% also included Podder, 2.07% also included Podroll, 1.37% also included Spotify, 0.26% also included CoHost Prefix, 0.20% also included Feedpress, 0.15% also included Magellan AI, 0.15% also included ArtsAI, 0.06% also included Swap.fm, and 0.03% also included Claritas.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "34.22%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.54%" >}}
3. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "5.55%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.28%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.08%" >}}
6. {{< a "https://radiolaser.fr/" "Radio Laser" >}} {{< span "weak" "4.44%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.50%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.15%" >}}
9. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "2.54%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.13%" >}}
---

### 12. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.16% of new episodes in June, growing 5.08% from last month.

Of these, 38.12% had 5 other trackers, 21.89% had 6 other trackers, 17.22% had 4 other trackers, 8.05% had 7 other trackers, 6.22% had 2 other trackers, 5.59% had 3 other trackers, and 1.19% had one other tracker.

89.99% also included Podscribe, 83.24% also included Podsights, 82.82% also included Chartable, 72.31% also included Magellan AI, 66.76% also included Podtrac, 30.25% also included ArtsAI, 15.71% also included Adswizz, 15.28% also included Spotify, 13.88% also included Veritonic, 3.41% also included Podder, 3.37% also included Podroll, 0.28% also included Swap.fm, 0.14% also included Gumshoe, 0.07% also included Feedpress, and 0.04% also included OP3.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "58.78%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.12%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.08%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.77%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.45%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "5.24%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.05%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.74%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.32%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.28%" >}}
---

### 13. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.16% of new episodes in June, growing 9.45% from last month.

Of these, 24.90% had 5 other trackers, 18.23% had 7 other trackers, 16.89% had 3 other trackers, 16.02% had 6 other trackers, 11.67% had 4 other trackers, 8.70% had 2 other trackers, 2.17% had 8 other trackers, and 1.09% had one other tracker.

84.56% also included Podscribe, 82.57% also included Chartable, 73.65% also included Podsights, 69.08% also included Podtrac, 45.81% also included Magellan AI, 33.93% also included Spotify, 31.21% also included Claritas, 21.71% also included Veritonic, 20.44% also included Adswizz, 13.85% also included Audiotakes, 1.67% also included Podroll, 1.49% also included Podder, 1.05% also included Swap.fm, 0.18% also included OP3, 0.18% also included Gumshoe, and 0.11% also included Blubrry.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "36.68%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.72%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.69%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.73%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.18%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "6.85%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.88%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.09%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.05%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.76%" >}}
---

### 14. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.15% of new episodes in June, growing 0.35% from last month.

Of these, 15.76% had one other tracker, 0.82% had 2 other trackers, and 0.07% had 5 other trackers.

11.85% also included Blubrry, 3.13% also included Podtrac, 1.01% also included Chartable, 0.75% also included Podcorn, 0.41% also included Podsights, 0.26% also included OP3, 0.19% also included Podscribe, 0.07% also included Claritas, 0.07% also included Adswizz, and 0.04% also included Podroll.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "51.56%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.42%" >}}
3. {{< a "https://95bfm.com/" "95bFM" >}} {{< span "weak" "5.89%" >}}
4. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "5.48%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.92%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.24%" >}}
7. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "2.05%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.75%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.12%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.04%" >}}
---

### 15. [Podder](https://www.podderapp.com/)

Podder was found on 0.15% of new episodes in June, shrinking 5.08% from last month.

Of these, 24.67% had one other tracker, 16.03% had 3 other trackers, 13.42% had 5 other trackers, 11.93% had 4 other trackers, 11.74% had 2 other trackers, 4.21% had 6 other trackers, 0.37% had 7 other trackers, and 0.37% had 8 other trackers.

63.06% also included Podtrac, 59.34% also included Chartable, 49.24% also included Podsights, 23.78% also included Magellan AI, 21.88% also included Podscribe, 3.62% also included Claritas, 3.50% also included Podcorn, 3.39% also included Podroll, 2.87% also included OP3, 2.83% also included Spotify, 2.42% also included Gumshoe, 1.79% also included Adswizz, 1.53% also included ArtsAI, 0.93% also included Podkite, 0.60% also included United Podcasters, 0.41% also included Veritonic, 0.37% also included Blubrry, and 0.34% also included CoHost Prefix.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "55.72%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "14.05%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.13%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "7.38%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.43%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.98%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.50%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.39%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.63%" >}}
10. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "0.48%" >}}
---

### 16. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.11% of new episodes in June, shrinking 0.08% from last month.

Of these, 31.74% had 5 other trackers, 16.91% had 4 other trackers, 15.24% had 2 other trackers, 11.97% had 3 other trackers, 9.83% had one other tracker, 3.69% had 6 other trackers, 0.52% had 8 other trackers, and 0.05% had 7 other trackers.

60.35% also included Podtrac, 59.68% also included Podsights, 47.03% also included Podscribe, 46.51% also included Chartable, 44.43% also included Podcorn, 42.35% also included OP3, 11.03% also included Spotify, 5.25% also included Magellan AI, 4.16% also included Podroll, 3.38% also included Podder, 1.72% also included Audiotakes, 1.09% also included Adswizz, 0.78% also included United Podcasters, 0.47% also included CoHost Prefix, 0.31% also included Swap.fm, 0.26% also included ArtsAI, 0.21% also included Claritas, and 0.21% also included Veritonic.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "42.77%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "27.32%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "19.88%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.24%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.35%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.14%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.57%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.21%" >}}
9. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.21%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.10%" >}}
---

### 17. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.10% of new episodes in June, growing 10.21% from last month.

Of these, 2.68% had one other tracker.

2.68% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "39.71%" >}}
2. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "35.64%" >}}
3. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "20.41%" >}}
---

### 18. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.07% of new episodes in June, growing 23.48% from last month.

Of these, 29.29% had 3 other trackers, 29.29% had 4 other trackers, 16.84% had 5 other trackers, 13.16% had 6 other trackers, 7.67% had 2 other trackers, 1.10% had one other tracker, and 0.70% had 7 other trackers.

97.10% also included Podscribe, 74.71% also included Podsights, 57.48% also included Podtrac, 49.49% also included Chartable, 36.73% also included Magellan AI, 29.91% also included ArtsAI, 27.96% also included Spotify, 5.01% also included Adswizz, 4.86% also included Veritonic, 2.58% also included Gumshoe, 1.96% also included United Podcasters, 0.70% also included Swap.fm, 0.63% also included Podroll, and 0.39% also included Blubrry.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "37.20%" >}}
2. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "35.24%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "13.47%" >}}
4. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.45%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.45%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.58%" >}}
7. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "2.27%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.25%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.94%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.16%" >}}
---

### 19. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.07% of new episodes in June, growing 1.31% from last month.

Of these, 33.61% had 7 other trackers, 19.43% had 6 other trackers, 13.09% had 4 other trackers, 10.76% had 5 other trackers, 8.51% had 2 other trackers, 7.42% had 3 other trackers, and 5.00% had 8 other trackers.

89.99% also included Podtrac, 82.15% also included Chartable, 78.57% also included Podsights, 78.07% also included Podscribe, 60.47% also included Magellan AI, 49.96% also included ArtsAI, 35.36% also included Spotify, 32.94% also included Claritas, 22.60% also included Adswizz, 5.17% also included Audiotakes, 0.92% also included Podder, 0.42% also included Blubrry, 0.42% also included Swap.fm, and 0.33% also included Gumshoe.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "65.64%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "20.10%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "5.00%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.92%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.59%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.08%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.75%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.33%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.33%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.25%" >}}
---

### 20. [Firstory](https://firstory.me/)

Firstory was found on 0.06% of new episodes in June, shrinking 2.20% from last month.

Of these, 77.79% had one other tracker.

77.79% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.82%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.18%" >}}
---

### 21. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.03% of new episodes in June, growing 117.54% from last month.

Of these, 40.30% had 2 other trackers, 27.63% had one other tracker, 12.01% had 3 other trackers, 10.20% had 4 other trackers, 2.96% had 6 other trackers, 2.80% had 7 other trackers, 2.30% had 5 other trackers, and 0.16% had 8 other trackers.

98.19% also included Chartable, 46.88% also included Podsights, 44.90% also included Podtrac, 21.88% also included Podscribe, 4.77% also included ArtsAI, 3.45% also included Adswizz, 2.96% also included Podroll, 2.47% also included Magellan AI, 1.81% also included Podcorn, 1.81% also included Spotify, 1.48% also included Audiotakes, 1.32% also included Claritas, 0.99% also included United Podcasters, 0.99% also included Gumshoe, 0.82% also included Veritonic, 0.33% also included OP3, and 0.16% also included Zencastr.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "76.64%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "18.42%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.45%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.32%" >}}
5. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.16%" >}}
---

### 22. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in June, shrinking 12.12% from last month.

Of these, 10.90% had one other tracker, 10.26% had 2 other trackers, 3.21% had 5 other trackers, and 2.56% had 4 other trackers.

19.87% also included Chartable, 17.31% also included Podtrac, 11.54% also included Podsights, 5.77% also included Podscribe, 2.56% also included United Podcasters, and 0.64% also included Swap.fm.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.33%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "20.51%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "15.38%" >}}
4. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "12.82%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.49%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.49%" >}}
7. {{< a "https://www.blogtalkradio.com/" "Blog Talk Radio" >}} {{< span "weak" "3.85%" >}}
8. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "2.56%" >}}
9. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "2.56%" >}}
---

### 23. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in June, growing 10.57% from last month.

Of these, 26.32% had one other tracker, 13.82% had 4 other trackers, 6.58% had 2 other trackers, 2.63% had 5 other trackers, and 1.32% had 3 other trackers.

42.11% also included Chartable, 30.26% also included Podtrac, 20.39% also included Podsights, 16.45% also included Podder, and 2.63% also included Podcorn.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "29.61%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "25.66%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "12.50%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "11.18%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.92%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.92%" >}}
7. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "5.26%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.63%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.32%" >}}
---

### 24. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in June, shrinking 1.34% from last month.

Of these, 34.67% had one other tracker, 24.67% had 5 other trackers, 17.33% had 3 other trackers, 10.00% had 2 other trackers, 4.00% had 4 other trackers, 0.67% had 7 other trackers, and 0.67% had 8 other trackers.

67.33% also included Chartable, 52.67% also included Podsights, 30.67% also included Podscribe, 24.67% also included Podtrac, 20.00% also included Magellan AI, 16.67% also included Audiotakes, 10.67% also included Podder, 10.00% also included Gumshoe, 6.00% also included Podroll, 5.33% also included Adswizz, 4.00% also included Podcorn, 4.00% also included Swap.fm, 2.67% also included Zencastr, and 1.33% also included Spotify.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "44.00%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "16.67%" >}}
3. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "13.33%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.00%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.33%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.33%" >}}
7. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "2.67%" >}}
8. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "2.67%" >}}
---

### 25. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.01% of new episodes in June, shrinking 18.50% from last month.

Of these, 42.39% had 3 other trackers, 15.22% had one other tracker, 14.13% had 2 other trackers, and 9.78% had 8 other trackers.

79.35% also included Chartable, 56.52% also included Podsights, 52.17% also included Podtrac, 16.30% also included Podroll, 15.22% also included Podcorn, 9.78% also included OP3, 9.78% also included Podder, and 9.78% also included Gumshoe.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "47.83%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "18.48%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "11.96%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.96%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.52%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.17%" >}}
7. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "1.09%" >}}
---

### 26. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in June, shrinking 0.87% from last month.

Of these, 27.03% had 2 other trackers, 22.97% had one other tracker, and 2.70% had 4 other trackers.

48.65% also included Chartable, 27.03% also included Podtrac, 9.46% also included Podcorn, and 2.70% also included Podscribe.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "45.95%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "18.92%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "12.16%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "8.11%" >}}
5. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "5.41%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.41%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.05%" >}}
---

### 27. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on <0.01% of new episodes in June, growing 16.71% from last month.

Of these, 47.06% had one other tracker, and 11.76% had 2 other trackers.

35.29% also included Chartable, 23.53% also included Podcorn, and 11.76% also included Podsights.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "41.18%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.53%" >}}
3. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "17.65%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "17.65%" >}}
---

### 28. [Glystn](https://glystn.com/)

Glystn was found on <0.01% of new episodes in June, growing 9.84% from last month.

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
*Updated 2024-07-01, with data for the month of June 2024.*

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
 - [Podcast Tracker Rankings by Episode Share (May 2024)](/archive/podcast-trackers-by-episode-share-may-2024/)
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2024-06.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
