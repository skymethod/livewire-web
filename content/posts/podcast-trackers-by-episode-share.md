---
title: "Top Podcast Tracking Services by Episode Share (August 2024)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2024-08.png
date: 2024-09-01T11:55:00-05:00
lastmod: 2024-09-01T11:55:00-05:00
draft: false
rssrevision: 2024-08
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.7 million in August 2024), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in August, how many
of them included one or more of these tracking services?  Some episodes had as many as *nine* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis. Some services like [Podtrac](https://analytics.podtrac.com/) provide both client-side and log-based measurement,
only their client-side prefix-based measurement is available for public observation here.*

<br><br>

{{< details "_March 2024: Spreaker data_" >}}
_Starting early March, we gained a better signal of when Spreaker releases new episodes, so our crawlers are finding more. This more accurate view seems to have helped Podtrac and Adswizz the most._
{{< /details >}}

<br><br>

{{< details "_September 2023: Spotify for Podcasters data_" >}}
_Starting mid-September, we gained a better signal of when Spotify for Podcasters (formerly Anchor) podcasts release new episodes, so our crawlers are finding more.
Higher share of new episodes on S4P (which typically do not have prefixes) will have led to lower share overall._
{{< /details >}}

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Chartable	Adswizz	Podsights	Blubrry	Podscribe	Podcorn	Podroll	Spotify	Podder	OP3	ArtsAI	Claritas	Feedpress	Gumshoe	Swap.fm	Audiotakes	Veritonic	Médiamétrie	United Podcasters	Podkite	Zencastr	CoHost Prefix	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.00	1.16	2.07		2.09							0.32					0.42										1.61
Oct 2021	4.05	4.09	1.01	1.20	2.11		2.13							0.34					0.54										1.61
Nov 2021	4.07	4.30	1.02	1.25	2.01		2.14							0.32					0.57										0.59
Dec 2021	4.06	4.42	1.24	1.19	1.57		2.27							0.19					0.59										
Jan 2022	4.11	4.45	1.41	1.21	1.56		2.31							0.16					0.63										
Feb 2022	4.15	4.48	1.44	1.25	1.53		2.38							0.17					0.58										
Mar 2022	4.37	4.72	1.51	1.34	1.56		2.40							0.17					0.53										
Apr 2022	4.44	4.71	1.49	1.33	1.55		2.33							0.16					0.51										
May 2022	4.49	4.87	1.58	1.41	1.48		2.26							0.17					0.56										
Jun 2022	4.75	5.10	1.77	1.54	1.50		2.06							0.21					0.62							0.02			
Jul 2022	4.70	5.10	1.89	1.50	1.50		2.16							0.25					0.54							0.02			
Aug 2022	4.83	5.26	2.08	1.73	1.51		2.45					0.10		0.20					0.41							0.01			
Sep 2022	7.53	5.40	2.26	1.74	1.49	0.02	2.45					0.09	0.01	0.21					0.52		0.01					0.02	0.02		
Oct 2022	8.24	5.48	2.35	1.81	1.61	0.07	2.51				0.03	0.10	0.02	0.18					0.50		0.01	0.01				0.02	0.04		
Nov 2022	8.11	5.62	2.37	2.03	1.62	0.15	2.43			0.01	0.04	0.10	0.03	0.18					0.50		0.01	0.01				0.02	0.05		
Dec 2022	8.01	5.54	2.32	1.81	1.61	0.03	2.05			0.04	0.05	0.05	0.02	0.18					0.49		0.01	0.01			0.01	0.02	0.05		
Jan 2023	7.85	5.56	2.35	1.88	1.61	0.20	2.15			0.11	0.07	0.10	0.06	0.18					0.54		0.01	0.01			0.01	0.02	0.06		
Feb 2023	7.58	5.51	2.29	1.92	1.62	0.21	2.30			0.11	0.07	0.10	0.07	0.19					0.49		0.01	0.01			0.01	0.02	0.06	0.03	
Mar 2023	7.79	5.53	2.25	2.03	1.53	0.21	2.22	0.04		0.11	0.08	0.11	0.07	0.18				0.04	0.45		0.01	0.01			0.01	0.02	0.06		
Apr 2023	7.66	5.43	2.26	2.00	1.67	0.21	2.20	0.06		0.15	0.09	0.11	0.07	0.17	0.08			0.05	0.45		0.01	0.01			0.01	0.01			
May 2023	7.58	5.59	2.27	2.04	1.67	0.24	2.28	0.09		0.15	0.09	0.11	0.08	0.19	0.07			0.05	0.45		0.01	0.01		0.01	0.01	0.01			
Jun 2023	8.22	5.83	2.39	2.23	1.64	0.26	1.86	0.10		0.15	0.09	0.12	0.07	0.19	0.08			0.05	0.51		0.01	0.01		0.01	0.01	0.01			
Jul 2023	8.60	5.95	2.38	2.52	1.53	0.27	1.17	0.14	0.01	0.14	0.08	0.11	0.07	0.18	0.06			0.06	0.55		0.01	0.01		0.01	0.01	0.01			
Aug 2023	9.19	6.43	2.72	2.76	1.58	0.36	1.23	0.16	0.03	0.15	0.11	0.12	0.08	0.17	0.07		0.04	0.07	0.53		0.01	0.01		0.02	0.01				
Sep 2023	8.46	5.77	2.49	2.47	1.39	0.37	1.10	0.13	0.05	0.15	0.10	0.12	0.10	0.16	0.07		0.05	0.06	0.58		0.01	0.01		0.02	0.01				
Oct 2023	7.90	5.54	2.29	2.28	1.37	0.39	1.11	0.12	0.08	0.16	0.10	0.12	0.10	0.16	0.08		0.05	0.06	0.50		0.01	0.02		0.03	0.01				
Nov 2023	7.65	5.59	2.25	2.33	1.45	0.47	1.14	0.12	0.11	0.16	0.13	0.12	0.11	0.17	0.10		0.06	0.06	0.33		0.01	0.01		0.03					
Dec 2023	7.48	5.60	2.20	2.19	1.53	0.54	1.12	0.12	0.12	0.16	0.11	0.12	0.11	0.16	0.09		0.06	0.06	0.33		0.01	0.01		0.03					
Jan 2024	7.64	5.61	2.37	2.21	1.55	0.65	1.17	0.11	0.15	0.16	0.13	0.14	0.12	0.17	0.10		0.08	0.06	0.25	0.01	0.01	0.01		0.01					
Feb 2024	7.69	5.58	2.38	2.22	1.52	0.69	1.21	0.12	0.22	0.17	0.16	0.13	0.13	0.17	0.11		0.09	0.06	0.22	0.01	0.01	0.01							
Mar 2024	9.01	5.46	2.53	2.19	1.54	0.69	1.14	0.12	0.25	0.16	0.14	0.12	0.14	0.16	0.10		0.09	0.06	0.22	0.01	0.01	0.01							
Apr 2024	10.78	5.47	2.53	2.16	1.51	0.73	1.24	0.34	0.27	0.17	0.18	0.13	0.15	0.15	0.11		0.07	0.07	0.19	0.01	0.01	0.01	0.01						
May 2024	11.59	5.63	2.75	2.24	1.50	0.83	1.20	0.36	0.30	0.16	0.18	0.14	0.15	0.15	0.11		0.06	0.07	0.09	0.01	0.01	0.01	0.01						
Jun 2024	11.54	6.06	2.88	2.34	1.52	0.91	0.71	0.37	0.32	0.15	0.20	0.16	0.16	0.15	0.11	0.03	0.07	0.07	0.10	0.01	0.01	0.01	0.01						
Jul 2024	12.34	6.80	2.83	2.45	1.65	1.01	0.71	0.43	0.34	0.15	0.20	0.17	0.18	0.15	0.12	0.06	0.09	0.07	0.09	0.01	0.01	0.01	0.01						
Aug 2024	14.22	6.72	2.96	2.48	1.70	1.11	0.81	0.45	0.35	0.35	0.19	0.18	0.18	0.14	0.12	0.12	0.11	0.08	0.08	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} are the clear top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podsights	Blubrry	Podscribe	Podcorn	Podroll	Spotify	Podder	OP3	ArtsAI	Claritas	Feedpress	Gumshoe	Swap.fm	Audiotakes	Veritonic	Médiamétrie	United Podcasters	Podkite	Zencastr	CoHost Prefix	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	1.00	1.16	2.07		2.09							0.32					0.42										1.61
Oct 2021	1.01	1.20	2.11		2.13							0.34					0.54										1.61
Nov 2021	1.02	1.25	2.01		2.14							0.32					0.57										0.59
Dec 2021	1.24	1.19	1.57		2.27							0.19					0.59										
Jan 2022	1.41	1.21	1.56		2.31							0.16					0.63										
Feb 2022	1.44	1.25	1.53		2.38							0.17					0.58										
Mar 2022	1.51	1.34	1.56		2.40							0.17					0.53										
Apr 2022	1.49	1.33	1.55		2.33							0.16					0.51										
May 2022	1.58	1.41	1.48		2.26							0.17					0.56										
Jun 2022	1.77	1.54	1.50		2.06							0.21					0.62							0.02			
Jul 2022	1.89	1.50	1.50		2.16							0.25					0.54							0.02			
Aug 2022	2.08	1.73	1.51		2.45					0.10		0.20					0.41							0.01			
Sep 2022	2.26	1.74	1.49	0.02	2.45					0.09	0.01	0.21					0.52		0.01					0.02	0.02		
Oct 2022	2.35	1.81	1.61	0.07	2.51				0.03	0.10	0.02	0.18					0.50		0.01	0.01				0.02	0.04		
Nov 2022	2.37	2.03	1.62	0.15	2.43			0.01	0.04	0.10	0.03	0.18					0.50		0.01	0.01				0.02	0.05		
Dec 2022	2.32	1.81	1.61	0.03	2.05			0.04	0.05	0.05	0.02	0.18					0.49		0.01	0.01			0.01	0.02	0.05		
Jan 2023	2.35	1.88	1.61	0.20	2.15			0.11	0.07	0.10	0.06	0.18					0.54		0.01	0.01			0.01	0.02	0.06		
Feb 2023	2.29	1.92	1.62	0.21	2.30			0.11	0.07	0.10	0.07	0.19					0.49		0.01	0.01			0.01	0.02	0.06	0.03	
Mar 2023	2.25	2.03	1.53	0.21	2.22	0.04		0.11	0.08	0.11	0.07	0.18				0.04	0.45		0.01	0.01			0.01	0.02	0.06		
Apr 2023	2.26	2.00	1.67	0.21	2.20	0.06		0.15	0.09	0.11	0.07	0.17	0.08			0.05	0.45		0.01	0.01			0.01	0.01			
May 2023	2.27	2.04	1.67	0.24	2.28	0.09		0.15	0.09	0.11	0.08	0.19	0.07			0.05	0.45		0.01	0.01		0.01	0.01	0.01			
Jun 2023	2.39	2.23	1.64	0.26	1.86	0.10		0.15	0.09	0.12	0.07	0.19	0.08			0.05	0.51		0.01	0.01		0.01	0.01	0.01			
Jul 2023	2.38	2.52	1.53	0.27	1.17	0.14	0.01	0.14	0.08	0.11	0.07	0.18	0.06			0.06	0.55		0.01	0.01		0.01	0.01	0.01			
Aug 2023	2.72	2.76	1.58	0.36	1.23	0.16	0.03	0.15	0.11	0.12	0.08	0.17	0.07		0.04	0.07	0.53		0.01	0.01		0.02	0.01				
Sep 2023	2.49	2.47	1.39	0.37	1.10	0.13	0.05	0.15	0.10	0.12	0.10	0.16	0.07		0.05	0.06	0.58		0.01	0.01		0.02	0.01				
Oct 2023	2.29	2.28	1.37	0.39	1.11	0.12	0.08	0.16	0.10	0.12	0.10	0.16	0.08		0.05	0.06	0.50		0.01	0.02		0.03	0.01				
Nov 2023	2.25	2.33	1.45	0.47	1.14	0.12	0.11	0.16	0.13	0.12	0.11	0.17	0.10		0.06	0.06	0.33		0.01	0.01		0.03					
Dec 2023	2.20	2.19	1.53	0.54	1.12	0.12	0.12	0.16	0.11	0.12	0.11	0.16	0.09		0.06	0.06	0.33		0.01	0.01		0.03					
Jan 2024	2.37	2.21	1.55	0.65	1.17	0.11	0.15	0.16	0.13	0.14	0.12	0.17	0.10		0.08	0.06	0.25	0.01	0.01	0.01		0.01					
Feb 2024	2.38	2.22	1.52	0.69	1.21	0.12	0.22	0.17	0.16	0.13	0.13	0.17	0.11		0.09	0.06	0.22	0.01	0.01	0.01							
Mar 2024	2.53	2.19	1.54	0.69	1.14	0.12	0.25	0.16	0.14	0.12	0.14	0.16	0.10		0.09	0.06	0.22	0.01	0.01	0.01							
Apr 2024	2.53	2.16	1.51	0.73	1.24	0.34	0.27	0.17	0.18	0.13	0.15	0.15	0.11		0.07	0.07	0.19	0.01	0.01	0.01	0.01						
May 2024	2.75	2.24	1.50	0.83	1.20	0.36	0.30	0.16	0.18	0.14	0.15	0.15	0.11		0.06	0.07	0.09	0.01	0.01	0.01	0.01						
Jun 2024	2.88	2.34	1.52	0.91	0.71	0.37	0.32	0.15	0.20	0.16	0.16	0.15	0.11	0.03	0.07	0.07	0.10	0.01	0.01	0.01	0.01						
Jul 2024	2.83	2.45	1.65	1.01	0.71	0.43	0.34	0.15	0.20	0.17	0.18	0.15	0.12	0.06	0.09	0.07	0.09	0.01	0.01	0.01	0.01						
Aug 2024	2.96	2.48	1.70	1.11	0.81	0.45	0.35	0.35	0.19	0.18	0.18	0.14	0.12	0.12	0.11	0.08	0.08	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

### Overall

At least one tracker was found on 22.95% of new episodes in August, growing 8.56% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "39.47%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.54%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.39%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.29%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.89%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.73%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.92%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.60%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.52%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.30%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of August 2024.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 14.22% of new episodes in August, growing 15.26% from last month.

Of these, 15.01% had one other tracker, 10.20% had 2 other trackers, 2.12% had 3 other trackers, 0.98% had 4 other trackers, 0.92% had 5 other trackers, 0.39% had 6 other trackers, 0.26% had 7 other trackers, and 0.03% had 8 other trackers.

18.99% also included Chartable, 11.30% also included Podsights, 5.29% also included Podscribe, 4.91% also included Adswizz, 2.43% also included Podroll, 2.07% also included Podcorn, 1.86% also included Podder, 1.55% also included Spotify, 1.54% also included Magellan AI, 0.84% also included ArtsAI, 0.77% also included Claritas, 0.73% also included OP3, 0.52% also included Gumshoe, 0.52% also included Veritonic, 0.48% also included Audiotakes, 0.43% also included Swap.fm, 0.32% also included Blubrry, 0.03% also included Feedpress, 0.02% also included CoHost Prefix, 0.02% also included Podkite, 0.02% also included United Podcasters, 0.01% also included Zencastr, 0.01% also included Médiamétrie, and 0.01% also included AdBarker.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "63.44%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.80%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.59%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.01%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.42%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.91%" >}}
7. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.29%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.21%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.10%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.90%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 7.45% of new episodes in August, shrinking 1.10% from last month.

Of these, 41.79% also included Podtrac, 10.57% also included Podscribe, 6.99% also included Adswizz, 4.41% also included Magellan AI, 2.51% also included Podcorn, 2.34% also included ArtsAI, 2.20% also included Podder, 2.17% also included Claritas, 2.10% also included Podroll, 1.54% also included Swap.fm, 1.42% also included Gumshoe, 1.39% also included Audiotakes, 1.30% also included OP3, 1.12% also included Veritonic, 0.73% also included Firstory, 0.37% also included Blubrry, 0.10% also included United Podcasters, 0.07% also included CoHost Prefix, 0.06% also included Podkite, 0.03% also included Zencastr, 0.03% also included AdBarker, 0.02% also included Feedpress, <0.01% also included Voxalyze, and <0.01% also included Glystn.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "28.73%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "28.14%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.05%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.48%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.33%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.70%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.52%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.37%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.26%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.23%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 6.72% of new episodes in August, shrinking 1.12% from last month.

Of these, 27.76% had one other tracker, 19.02% had 2 other trackers, 4.78% had 3 other trackers, 2.42% had 4 other trackers, 1.76% had 5 other trackers, 0.95% had 6 other trackers, 0.49% had 7 other trackers, and 0.06% had 8 other trackers.

40.15% also included Podtrac, 26.90% also included Podsights, 8.89% also included Podscribe, 6.68% also included Adswizz, 4.20% also included Spotify, 4.11% also included Magellan AI, 2.21% also included ArtsAI, 2.20% also included Podroll, 2.13% also included Claritas, 1.98% also included Podcorn, 1.97% also included Podder, 1.67% also included Swap.fm, 1.05% also included Veritonic, 0.90% also included Audiotakes, 0.89% also included Gumshoe, 0.80% also included Firstory, 0.80% also included OP3, 0.36% also included Blubrry, 0.12% also included United Podcasters, 0.07% also included CoHost Prefix, 0.06% also included Podkite, 0.03% also included Zencastr, 0.03% also included AdBarker, 0.03% also included Feedpress, 0.01% also included Voxalyze, and <0.01% also included Glystn.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "28.42%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "26.76%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.01%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.77%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.51%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.00%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.51%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.48%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.47%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.11%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.96% of new episodes in August, growing 4.60% from last month.

Of these, 18.55% had one other tracker, 12.73% had 2 other trackers, 2.53% had 3 other trackers, 0.98% had 4 other trackers, 0.74% had 5 other trackers, 0.51% had 7 other trackers, 0.35% had 6 other trackers, and 0.11% had 8 other trackers.

23.61% also included Podtrac, 15.19% also included Chartable, 9.88% also included Podroll, 5.44% also included Podsights, 3.33% also included Podscribe, 1.45% also included Claritas, 1.38% also included ArtsAI, 1.35% also included Magellan AI, 1.09% also included Blubrry, 1.01% also included Spotify, 0.72% also included Veritonic, 0.54% also included Podder, 0.40% also included Audiotakes, 0.26% also included Podcorn, 0.06% also included Swap.fm, 0.04% also included Gumshoe, 0.03% also included OP3, and 0.02% also included United Podcasters.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "44.39%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "11.81%" >}}
3. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "8.44%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "7.95%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "6.78%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.77%" >}}
7. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "5.06%" >}}
8. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.91%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.34%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.01%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.48% of new episodes in August, growing 1.20% from last month.

Of these, 35.76% had 2 other trackers, 29.51% had one other tracker, 11.40% had 3 other trackers, 6.69% had 4 other trackers, 5.76% had 5 other trackers, 2.60% had 6 other trackers, 1.35% had 7 other trackers, and 0.16% had 8 other trackers.

72.98% also included Chartable, 64.82% also included Podtrac, 22.38% also included Podscribe, 10.68% also included Magellan AI, 6.49% also included Adswizz, 5.32% also included Claritas, 5.12% also included ArtsAI, 4.67% also included Podder, 3.44% also included Spotify, 3.33% also included Swap.fm, 3.08% also included Audiotakes, 2.98% also included Podcorn, 2.93% also included Gumshoe, 2.87% also included Podroll, 2.69% also included Veritonic, 2.47% also included OP3, 0.31% also included Blubrry, 0.23% also included United Podcasters, 0.13% also included CoHost Prefix, 0.09% also included Podkite, 0.05% also included Zencastr, 0.01% also included Feedpress, and 0.01% also included Voxalyze.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "57.52%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "25.14%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.34%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.30%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.50%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.37%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.19%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.13%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.05%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.00%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.70% of new episodes in August, growing 2.88% from last month.

Of these, 5.64% had one other tracker, 0.97% had 2 other trackers, 0.08% had 3 other trackers, 0.07% had 4 other trackers, 0.02% had 6 other trackers, 0.01% had 7 other trackers, and 0.01% had 5 other trackers.

2.65% also included Podtrac, 1.89% also included Adswizz, 1.41% also included Chartable, 0.96% also included Feedpress, 0.45% also included Podsights, 0.30% also included Podcorn, 0.24% also included Podscribe, 0.20% also included OP3, 0.09% also included Spotify, 0.05% also included Podder, 0.05% also included Magellan AI, 0.03% also included Podroll, 0.02% also included Audiotakes, and 0.02% also included Veritonic.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "39.12%" >}}
2. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "9.42%" >}}
3. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "6.62%" >}}
4. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "3.31%" >}}
5. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.26%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.26%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.72%" >}}
8. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.52%" >}}
9. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.37%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.83%" >}}
---

### 6. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 1.11% of new episodes in August, growing 9.98% from last month.

Of these, 25.03% had one other tracker, 16.78% had 2 other trackers, 16.09% had 3 other trackers, 14.21% had 4 other trackers, 13.41% had 5 other trackers, 6.14% had 6 other trackers, 3.56% had 7 other trackers, and 0.33% had 8 other trackers.

67.42% also included Podtrac, 53.58% also included Chartable, 49.73% also included Podsights, 25.87% also included Magellan AI, 14.42% also included Spotify, 14.20% also included ArtsAI, 14.12% also included Claritas, 9.14% also included Audiotakes, 8.82% also included Adswizz, 7.79% also included Podder, 6.80% also included Podcorn, 5.74% also included Veritonic, 5.47% also included Gumshoe, 3.96% also included Swap.fm, 3.79% also included OP3, 3.51% also included Podroll, 0.36% also included Blubrry, 0.28% also included United Podcasters, 0.05% also included Zencastr, 0.05% also included Feedpress, 0.02% also included CoHost Prefix, and 0.01% also included AdBarker.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "50.73%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "16.12%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.69%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.75%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.66%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.40%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.09%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.04%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.58%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.13%" >}}
---

### 7. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.81% of new episodes in August, growing 14.18% from last month.

Of these, 30.33% had one other tracker, 6.21% had 2 other trackers, 4.73% had 5 other trackers, 4.29% had 3 other trackers, 1.35% had 4 other trackers, 0.61% had 6 other trackers, 0.08% had 8 other trackers, and 0.07% had 7 other trackers.

36.36% also included Podtrac, 16.42% also included Chartable, 9.35% also included Podscribe, 9.11% also included Podsights, 6.75% also included OP3, 6.65% also included Gumshoe, 0.93% also included Adswizz, 0.90% also included Podder, 0.83% also included Podroll, 0.64% also included Blubrry, 0.38% also included Spotify, 0.31% also included Swap.fm, 0.28% also included Magellan AI, 0.25% also included Feedpress, 0.09% also included United Podcasters, 0.06% also included AdBarker, 0.06% also included CoHost Prefix, 0.05% also included Podkite, 0.03% also included Voxalyze, and 0.03% also included Audiotakes.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "21.87%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "18.28%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "13.47%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "11.02%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "8.52%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "8.31%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "4.73%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.27%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.00%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.69%" >}}
---

### 8. [Podroll](https://podroll.fm/)

Podroll was found on 0.45% of new episodes in August, growing 4.88% from last month.

Of these, 73.16% had 2 other trackers, 10.71% had one other tracker, 5.86% had 3 other trackers, 5.57% had 4 other trackers, 1.37% had 5 other trackers, 0.90% had 6 other trackers, 0.84% had 7 other trackers, and 0.14% had 8 other trackers.

77.43% also included Podtrac, 65.49% also included Adswizz, 33.13% also included Chartable, 15.93% also included Podsights, 8.77% also included Podscribe, 3.83% also included Swap.fm, 2.09% also included Magellan AI, 1.86% also included Claritas, 1.50% also included Podcorn, 1.50% also included Podder, 1.08% also included Gumshoe, 1.01% also included Spotify, 0.91% also included OP3, 0.64% also included ArtsAI, 0.37% also included Audiotakes, 0.28% also included CoHost Prefix, 0.24% also included United Podcasters, and 0.11% also included Blubrry.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "64.84%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "20.11%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.07%" >}}
4. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "2.99%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.46%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.12%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.88%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.45%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.39%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.34%" >}}
---

### 9. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.35% of new episodes in August, growing 5.25% from last month.

Of these, 45.53% had 2 other trackers, 14.10% had one other tracker, 12.98% had 3 other trackers, 8.52% had 7 other trackers, 7.24% had 6 other trackers, 6.24% had 4 other trackers, 2.46% had 5 other trackers, and 1.03% had 8 other trackers.

80.05% also included Chartable, 62.37% also included Podtrac, 45.58% also included Podscribe, 24.18% also included Podsights, 20.65% also included Magellan AI, 17.02% also included ArtsAI, 8.45% also included Adswizz, 8.15% also included Veritonic, 7.94% also included Audiotakes, 7.77% also included Claritas, 3.64% also included Gumshoe, 3.11% also included Podder, 1.28% also included Podroll, 0.88% also included Podcorn, 0.72% also included OP3, 0.42% also included Blubrry, 0.40% also included Swap.fm, and 0.08% also included United Podcasters.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "50.79%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "13.60%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "7.87%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.96%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.72%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.58%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.96%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.85%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.66%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.48%" >}}
---

### 10. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.35% of new episodes in August, growing 6.71% from last month.

Of these, 26.00% had 5 other trackers, 24.31% had 4 other trackers, 13.61% had 3 other trackers, 13.60% had 6 other trackers, 9.62% had 7 other trackers, 6.42% had 2 other trackers, 4.26% had one other tracker, and 0.96% had 8 other trackers.

82.35% also included Podscribe, 78.91% also included Chartable, 75.57% also included Podsights, 62.38% also included Podtrac, 34.74% also included Claritas, 26.14% also included ArtsAI, 20.80% also included Spotify, 14.38% also included Veritonic, 13.98% also included Podder, 13.63% also included Audiotakes, 11.37% also included Adswizz, 2.67% also included Podroll, 2.05% also included Gumshoe, 1.11% also included Swap.fm, 0.65% also included Podcorn, 0.57% also included United Podcasters, 0.23% also included Blubrry, and 0.23% also included OP3.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "61.07%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.65%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.97%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.64%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.52%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.15%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.72%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.25%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.23%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.23%" >}}
---

### 11. [Podder](https://www.podderapp.com/)

Podder was found on 0.35% of new episodes in August, growing 126.68% from last month.

Of these, 44.72% had one other tracker, 12.24% had 2 other trackers, 10.92% had 4 other trackers, 10.13% had 3 other trackers, 9.31% had 5 other trackers, 3.42% had 6 other trackers, 1.04% had 7 other trackers, and 0.10% had 8 other trackers.

75.91% also included Podtrac, 37.89% also included Chartable, 33.18% also included Podsights, 24.89% also included Podscribe, 14.04% also included Magellan AI, 7.89% also included Audiotakes, 5.57% also included ArtsAI, 4.61% also included Adswizz, 3.15% also included Spotify, 2.10% also included Podcorn, 1.92% also included Podroll, 1.85% also included Claritas, 1.70% also included OP3, 1.70% also included Gumshoe, 0.52% also included Podkite, 0.44% also included Veritonic, 0.39% also included United Podcasters, 0.25% also included Blubrry, 0.22% also included Swap.fm, and 0.22% also included CoHost Prefix.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "44.55%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "36.34%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.93%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.14%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.37%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.50%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.40%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "1.26%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.96%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.49%" >}}
---

### 12. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.19% of new episodes in August, shrinking 4.65% from last month.

Of these, 22.25% had one other tracker, 19.27% had 5 other trackers, 8.71% had 2 other trackers, 8.25% had 3 other trackers, 5.52% had 4 other trackers, 2.76% had 6 other trackers, 0.18% had 8 other trackers, and 0.12% had 7 other trackers.

53.72% also included Podtrac, 31.62% also included Podsights, 28.29% also included Podcorn, 28.04% also included Gumshoe, 27.92% also included Chartable, 21.85% also included Podscribe, 3.07% also included Podder, 2.09% also included Podroll, 1.76% also included Blubrry, 1.31% also included Spotify, 0.42% also included Magellan AI, 0.39% also included Adswizz, 0.27% also included Claritas, 0.27% also included Feedpress, 0.24% also included Swap.fm, 0.18% also included CoHost Prefix, 0.15% also included Audiotakes, and 0.15% also included ArtsAI.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "37.00%" >}}
2. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "8.25%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.64%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "4.28%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.19%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.43%" >}}
7. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "2.76%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.49%" >}}
9. {{< a "https://rssblue.com/" "RSS Blue" >}} {{< span "weak" "2.00%" >}}
10. {{< a "https://letscast.fm/" "LetsCast.fm" >}} {{< span "weak" "1.97%" >}}
---

### 13. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.18% of new episodes in August, growing 10.21% from last month.

Of these, 20.81% had 5 other trackers, 20.17% had 7 other trackers, 18.95% had 6 other trackers, 14.47% had 4 other trackers, 13.64% had 3 other trackers, 8.74% had 2 other trackers, 1.82% had 8 other trackers, and 1.34% had one other tracker.

86.30% also included Podscribe, 80.86% also included Chartable, 69.17% also included Podsights, 65.46% also included Podtrac, 49.90% also included Magellan AI, 32.75% also included Spotify, 29.45% also included Claritas, 22.28% also included Adswizz, 21.90% also included Veritonic, 18.50% also included Audiotakes, 10.60% also included Podder, 2.05% also included Swap.fm, 1.57% also included Podroll, 0.16% also included OP3, and 0.16% also included Gumshoe.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "39.05%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "16.23%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "13.92%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.70%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "9.60%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "7.11%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.70%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.09%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.86%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.48%" >}}
---

### 14. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.18% of new episodes in August, growing 0.35% from last month.

Of these, 32.51% had 5 other trackers, 22.24% had 6 other trackers, 17.05% had 4 other trackers, 10.37% had 7 other trackers, 5.63% had 3 other trackers, 5.23% had one other tracker, and 4.71% had 2 other trackers.

88.25% also included Podscribe, 80.06% also included Chartable, 73.91% also included Podsights, 68.18% also included Magellan AI, 61.47% also included Podtrac, 30.27% also included ArtsAI, 23.99% also included Adswizz, 16.52% also included Veritonic, 15.37% also included Spotify, 4.64% also included Podroll, 3.62% also included Podder, 1.18% also included Swap.fm, 0.30% also included OP3, 0.26% also included Audiotakes, and 0.26% also included Gumshoe.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "49.72%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "18.72%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.38%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.29%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "5.82%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.13%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.12%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.79%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.46%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.23%" >}}
---

### 15. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.14% of new episodes in August, shrinking 4.19% from last month.

Of these, 15.62% had one other tracker, and 1.35% had 2 other trackers.

11.41% also included Blubrry, 3.27% also included Podtrac, 1.39% also included Podcorn, 1.27% also included Chartable, 0.41% also included Podscribe, 0.37% also included OP3, and 0.20% also included Podsights.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "58.94%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "10.51%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.36%" >}}
4. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.97%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.94%" >}}
6. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "2.70%" >}}
7. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.23%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.15%" >}}
9. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.98%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.98%" >}}
---

### 16. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.12% of new episodes in August, growing 5.57% from last month.

Of these, 34.84% had 5 other trackers, 15.26% had 4 other trackers, 12.60% had one other tracker, 12.31% had 3 other trackers, 12.12% had 2 other trackers, 3.71% had 6 other trackers, 0.29% had 8 other trackers, and 0.19% had 7 other trackers.

60.03% also included Podtrac, 58.84% also included Podsights, 49.33% also included Podscribe, 48.34% also included Chartable, 43.92% also included OP3, 43.68% also included Podcorn, 10.41% also included Spotify, 5.80% also included Magellan AI, 4.80% also included Podder, 3.90% also included Podroll, 2.04% also included Audiotakes, 1.00% also included Adswizz, 0.81% also included United Podcasters, 0.67% also included Swap.fm, 0.38% also included Claritas, 0.38% also included Veritonic, 0.29% also included CoHost Prefix, and 0.24% also included ArtsAI.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "44.20%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "27.66%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "18.49%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.94%" >}}
5. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.28%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.24%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.33%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.19%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.19%" >}}
10. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.19%" >}}
---

### 17. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.12% of new episodes in August, growing 83.35% from last month.

Of these, 36.71% had 3 other trackers, 21.68% had 2 other trackers, 19.84% had 4 other trackers, 12.75% had one other tracker, 2.53% had 5 other trackers, 2.38% had 6 other trackers, 1.54% had 7 other trackers, and 0.25% had 8 other trackers.

94.74% also included Chartable, 69.79% also included Podsights, 51.54% also included Podtrac, 37.25% also included Podscribe, 14.43% also included Podroll, 3.27% also included Magellan AI, 3.17% also included ArtsAI, 2.13% also included Podcorn, 1.79% also included Claritas, 1.59% also included Adswizz, 1.19% also included Spotify, 1.19% also included United Podcasters, 0.69% also included Veritonic, 0.69% also included Gumshoe, 0.64% also included Podder, 0.55% also included Audiotakes, 0.40% also included OP3, and 0.20% also included Zencastr.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "86.61%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.24%" >}}
3. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "2.08%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.79%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.39%" >}}
6. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.69%" >}}
7. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.20%" >}}
---

### 18. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.11% of new episodes in August, growing 24.19% from last month.

Of these, 30.77% had 4 other trackers, 19.38% had 3 other trackers, 19.28% had 5 other trackers, 16.51% had 6 other trackers, 5.54% had 2 other trackers, 3.33% had one other tracker, and 2.62% had 7 other trackers.

89.03% also included Podscribe, 66.56% also included Podsights, 59.90% also included Podtrac, 52.62% also included Chartable, 41.69% also included Magellan AI, 29.64% also included ArtsAI, 24.46% also included Spotify, 24.05% also included Podder, 10.36% also included Adswizz, 4.41% also included Veritonic, 2.21% also included Gumshoe, 1.44% also included Podroll, 1.38% also included United Podcasters, 0.56% also included Swap.fm, 0.41% also included Claritas, 0.26% also included Blubrry, 0.26% also included OP3, and 0.21% also included Podcorn.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "38.10%" >}}
2. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "29.74%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "12.51%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.41%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.18%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.36%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.31%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.64%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "1.54%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.21%" >}}
---

### 19. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.08% of new episodes in August, growing 14.62% from last month.

Of these, 33.96% had 7 other trackers, 20.33% had 6 other trackers, 14.45% had 4 other trackers, 8.99% had 2 other trackers, 8.71% had 5 other trackers, 7.61% had 3 other trackers, and 3.94% had 8 other trackers.

86.72% also included Podtrac, 82.99% also included Chartable, 78.42% also included Podsights, 75.38% also included Podscribe, 59.34% also included Magellan AI, 47.30% also included ArtsAI, 34.72% also included Claritas, 33.89% also included Spotify, 25.03% also included Adswizz, 5.95% also included Audiotakes, 1.80% also included Podder, 0.97% also included Swap.fm, 0.55% also included Gumshoe, and 0.35% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "65.01%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "20.82%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.22%" >}}
4. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.73%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.97%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.80%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.69%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.28%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.21%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.21%" >}}
---

### 20. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.08% of new episodes in August, shrinking 10.30% from last month.

Of these, 2.12% had one other tracker.

2.12% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "37.94%" >}}
2. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "33.00%" >}}
3. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "26.16%" >}}
---

### 21. [Firstory](https://firstory.me/)

Firstory was found on 0.07% of new episodes in August, growing 1.56% from last month.

Of these, 80.65% had one other tracker.

80.65% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "100.00%" >}}
---

### 22. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in August, growing 19.49% from last month.

Of these, 25.40% had one other tracker, 23.81% had 3 other trackers, 16.93% had 5 other trackers, 8.99% had 2 other trackers, 4.76% had 6 other trackers, 4.23% had 4 other trackers, and 2.65% had 8 other trackers.

69.84% also included Chartable, 50.79% also included Podsights, 28.57% also included Podscribe, 24.87% also included Podtrac, 17.99% also included Magellan AI, 14.29% also included Audiotakes, 12.70% also included Swap.fm, 12.17% also included Podder, 9.52% also included Podroll, 8.99% also included Gumshoe, 6.88% also included Podcorn, 4.23% also included Adswizz, 2.65% also included Spotify, and 2.65% also included Zencastr.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "54.50%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "14.29%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.99%" >}}
4. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "7.94%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.23%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.70%" >}}
7. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "2.12%" >}}
8. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "2.12%" >}}
9. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.06%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.06%" >}}
---

### 23. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in August, growing 7.42% from last month.

Of these, 24.86% had one other tracker, 13.87% had 4 other trackers, 5.78% had 2 other trackers, 4.05% had 5 other trackers, and 1.73% had 3 other trackers.

41.62% also included Chartable, 31.79% also included Podtrac, 21.97% also included Podsights, 17.92% also included Podder, and 4.05% also included Podcorn.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "28.32%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "24.86%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "12.14%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "9.83%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "8.09%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.78%" >}}
7. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "5.20%" >}}
8. {{< a "https://azure.microsoft.com/en-us/services/storage/blobs/" "Microsoft Azure Blob Storage" >}} {{< span "weak" "2.89%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.89%" >}}
---

### 24. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in August, shrinking 5.56% from last month.

Of these, 13.07% had one other tracker, 11.11% had 2 other trackers, 3.27% had 5 other trackers, 1.96% had 4 other trackers, and 1.31% had 6 other trackers.

22.22% also included Chartable, 20.26% also included Podtrac, 12.42% also included Podsights, 6.54% also included Podscribe, 3.27% also included United Podcasters, and 2.61% also included Swap.fm.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "35.95%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "19.61%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "14.38%" >}}
4. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "11.76%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.88%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.58%" >}}
7. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "3.27%" >}}
8. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "2.61%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.96%" >}}
---

### 25. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.01% of new episodes in August, shrinking 0.18% from last month.

Of these, 43.24% had 3 other trackers, 22.52% had one other tracker, 6.31% had 2 other trackers, 5.41% had 4 other trackers, and 5.41% had 8 other trackers.

76.58% also included Chartable, 50.45% also included Podtrac, 50.45% also included Podsights, 18.92% also included Podroll, 11.71% also included Podder, 7.21% also included Podcorn, 5.41% also included OP3, 5.41% also included Gumshoe, and 3.60% also included Podscribe.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "45.95%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "15.32%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "8.11%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.31%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "6.31%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "6.31%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.31%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.50%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.90%" >}}
---

### 26. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in August, shrinking 12.83% from last month.

Of these, 34.43% had 2 other trackers, 19.67% had one other tracker, and 3.28% had 4 other trackers.

52.46% also included Chartable, 32.79% also included Podtrac, 13.11% also included Podcorn, and 3.28% also included Podscribe.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "52.46%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "14.75%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "14.75%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "8.20%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.92%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.28%" >}}
7. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "1.64%" >}}
---

### 27. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on <0.01% of new episodes in August, shrinking 12.15% from last month.

Of these, 43.75% had one other tracker, and 18.75% had 2 other trackers.

37.50% also included Chartable, 25.00% also included Podcorn, and 18.75% also included Podsights.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "50.00%" >}}
2. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "18.75%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "18.75%" >}}
4. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "12.50%" >}}
---

### 28. [Glystn](https://glystn.com/)

Glystn was found on <0.01% of new episodes in August, shrinking 16.55% from last month.

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
*Updated 2024-09-01, with data for the month of August 2024.*

*Updated 2024-08-01, with data for the month of July 2024.*

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
 - [Podcast Tracker Rankings by Episode Share (July 2024)](/archive/podcast-trackers-by-episode-share-july-2024/)
 - [Podcast Tracker Rankings by Episode Share (June 2024)](/archive/podcast-trackers-by-episode-share-june-2024/)
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/podcast-trackers-by-episode-share.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
