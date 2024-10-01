---
title: "Top Podcast Tracking Services by Episode Share (September 2024)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2024-09.png
date: 2024-10-01T15:43:00-05:00
lastmod: 2024-10-01T15:43:00-05:00
draft: false
rssrevision: 2024-09
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.7 million in September 2024), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in September, how many
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
Month	Podtrac	Chartable	Adswizz	Podsights	Blubrry	Podscribe	Podcorn	Podroll	Podder	Spotify	OP3	Claritas	ArtsAI	Feedpress	Audiotakes	Gumshoe	Swap.fm	Veritonic	Médiamétrie	Podkite	CoHost Prefix	United Podcasters	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
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
Aug 2022	4.83	5.26	2.08	1.73	1.51		2.45						0.10	0.20					0.41							0.01			
Sep 2022	7.53	5.40	2.26	1.74	1.49	0.02	2.45					0.01	0.09	0.21					0.52	0.01						0.02	0.02		
Oct 2022	8.24	5.48	2.35	1.81	1.61	0.07	2.51				0.03	0.02	0.10	0.18					0.50	0.01			0.01			0.02	0.04		
Nov 2022	8.11	5.62	2.37	2.03	1.62	0.15	2.43		0.01		0.04	0.03	0.10	0.18					0.50	0.01			0.01			0.02	0.05		
Dec 2022	8.01	5.54	2.32	1.81	1.61	0.03	2.05		0.04		0.05	0.02	0.05	0.18					0.49	0.01			0.01		0.01	0.02	0.05		
Jan 2023	7.85	5.56	2.35	1.88	1.61	0.20	2.15		0.11		0.07	0.06	0.10	0.18					0.54	0.01			0.01		0.01	0.02	0.06		
Feb 2023	7.58	5.51	2.29	1.92	1.62	0.21	2.30		0.11		0.07	0.07	0.10	0.19					0.49	0.01			0.01		0.01	0.02	0.06	0.03	
Mar 2023	7.79	5.53	2.25	2.03	1.53	0.21	2.22	0.04	0.11		0.08	0.07	0.11	0.18				0.04	0.45	0.01			0.01		0.01	0.02	0.06		
Apr 2023	7.66	5.43	2.26	2.00	1.67	0.21	2.20	0.06	0.15		0.09	0.07	0.11	0.17		0.08		0.05	0.45	0.01			0.01		0.01	0.01			
May 2023	7.58	5.59	2.27	2.04	1.67	0.24	2.28	0.09	0.15		0.09	0.08	0.11	0.19		0.07		0.05	0.45	0.01			0.01	0.01	0.01	0.01			
Jun 2023	8.22	5.83	2.39	2.23	1.64	0.26	1.86	0.10	0.15		0.09	0.07	0.12	0.19		0.08		0.05	0.51	0.01			0.01	0.01	0.01	0.01			
Jul 2023	8.60	5.95	2.38	2.52	1.53	0.27	1.17	0.14	0.14	0.01	0.08	0.07	0.11	0.18		0.06		0.06	0.55	0.01			0.01	0.01	0.01	0.01			
Aug 2023	9.19	6.43	2.72	2.76	1.58	0.36	1.23	0.16	0.15	0.03	0.11	0.08	0.12	0.17	0.04	0.07		0.07	0.53	0.01			0.01	0.02	0.01				
Sep 2023	8.46	5.77	2.49	2.47	1.39	0.37	1.10	0.13	0.15	0.05	0.10	0.10	0.12	0.16	0.05	0.07		0.06	0.58	0.01			0.01	0.02	0.01				
Oct 2023	7.90	5.54	2.29	2.28	1.37	0.39	1.11	0.12	0.16	0.08	0.10	0.10	0.12	0.16	0.05	0.08		0.06	0.50	0.01			0.02	0.03	0.01				
Nov 2023	7.65	5.59	2.25	2.33	1.45	0.47	1.14	0.12	0.16	0.11	0.13	0.11	0.12	0.17	0.06	0.10		0.06	0.33	0.01			0.01	0.03					
Dec 2023	7.48	5.60	2.20	2.19	1.53	0.54	1.12	0.12	0.16	0.12	0.11	0.11	0.12	0.16	0.06	0.09		0.06	0.33	0.01			0.01	0.03					
Jan 2024	7.64	5.61	2.37	2.21	1.55	0.65	1.17	0.11	0.16	0.15	0.13	0.12	0.14	0.17	0.08	0.10		0.06	0.25	0.01		0.01	0.01	0.01					
Feb 2024	7.69	5.58	2.38	2.22	1.52	0.69	1.21	0.12	0.17	0.22	0.16	0.13	0.13	0.17	0.09	0.11		0.06	0.22	0.01		0.01	0.01						
Mar 2024	9.01	5.46	2.53	2.19	1.54	0.69	1.14	0.12	0.16	0.25	0.14	0.14	0.12	0.16	0.09	0.10		0.06	0.22	0.01		0.01	0.01						
Apr 2024	10.78	5.47	2.53	2.16	1.51	0.73	1.24	0.34	0.17	0.27	0.18	0.15	0.13	0.15	0.07	0.11		0.07	0.19	0.01	0.01	0.01	0.01						
May 2024	11.59	5.63	2.75	2.24	1.50	0.83	1.20	0.36	0.16	0.30	0.18	0.15	0.14	0.15	0.06	0.11		0.07	0.09	0.01	0.01	0.01	0.01						
Jun 2024	11.54	6.06	2.88	2.34	1.52	0.91	0.71	0.37	0.15	0.32	0.20	0.16	0.16	0.15	0.07	0.11	0.03	0.07	0.10	0.01	0.01	0.01	0.01						
Jul 2024	12.34	6.80	2.83	2.45	1.65	1.01	0.71	0.43	0.15	0.34	0.20	0.18	0.17	0.15	0.09	0.12	0.06	0.07	0.09	0.01	0.01	0.01	0.01						
Aug 2024	14.22	6.72	2.96	2.48	1.70	1.11	0.81	0.45	0.35	0.35	0.19	0.18	0.18	0.14	0.11	0.12	0.12	0.08	0.08	0.01	0.01	0.01	0.01						
Sep 2024	12.95	5.99	3.13	2.26	1.44	1.18	0.72	0.44	0.42	0.35	0.24	0.18	0.18	0.15	0.13	0.13	0.12	0.08	0.07	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} are the clear top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podsights	Blubrry	Podscribe	Podcorn	Podroll	Podder	Spotify	OP3	Claritas	ArtsAI	Feedpress	Audiotakes	Gumshoe	Swap.fm	Veritonic	Médiamétrie	Podkite	CoHost Prefix	United Podcasters	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
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
Aug 2022	2.08	1.73	1.51		2.45						0.10	0.20					0.41							0.01			
Sep 2022	2.26	1.74	1.49	0.02	2.45					0.01	0.09	0.21					0.52	0.01						0.02	0.02		
Oct 2022	2.35	1.81	1.61	0.07	2.51				0.03	0.02	0.10	0.18					0.50	0.01			0.01			0.02	0.04		
Nov 2022	2.37	2.03	1.62	0.15	2.43		0.01		0.04	0.03	0.10	0.18					0.50	0.01			0.01			0.02	0.05		
Dec 2022	2.32	1.81	1.61	0.03	2.05		0.04		0.05	0.02	0.05	0.18					0.49	0.01			0.01		0.01	0.02	0.05		
Jan 2023	2.35	1.88	1.61	0.20	2.15		0.11		0.07	0.06	0.10	0.18					0.54	0.01			0.01		0.01	0.02	0.06		
Feb 2023	2.29	1.92	1.62	0.21	2.30		0.11		0.07	0.07	0.10	0.19					0.49	0.01			0.01		0.01	0.02	0.06	0.03	
Mar 2023	2.25	2.03	1.53	0.21	2.22	0.04	0.11		0.08	0.07	0.11	0.18				0.04	0.45	0.01			0.01		0.01	0.02	0.06		
Apr 2023	2.26	2.00	1.67	0.21	2.20	0.06	0.15		0.09	0.07	0.11	0.17		0.08		0.05	0.45	0.01			0.01		0.01	0.01			
May 2023	2.27	2.04	1.67	0.24	2.28	0.09	0.15		0.09	0.08	0.11	0.19		0.07		0.05	0.45	0.01			0.01	0.01	0.01	0.01			
Jun 2023	2.39	2.23	1.64	0.26	1.86	0.10	0.15		0.09	0.07	0.12	0.19		0.08		0.05	0.51	0.01			0.01	0.01	0.01	0.01			
Jul 2023	2.38	2.52	1.53	0.27	1.17	0.14	0.14	0.01	0.08	0.07	0.11	0.18		0.06		0.06	0.55	0.01			0.01	0.01	0.01	0.01			
Aug 2023	2.72	2.76	1.58	0.36	1.23	0.16	0.15	0.03	0.11	0.08	0.12	0.17	0.04	0.07		0.07	0.53	0.01			0.01	0.02	0.01				
Sep 2023	2.49	2.47	1.39	0.37	1.10	0.13	0.15	0.05	0.10	0.10	0.12	0.16	0.05	0.07		0.06	0.58	0.01			0.01	0.02	0.01				
Oct 2023	2.29	2.28	1.37	0.39	1.11	0.12	0.16	0.08	0.10	0.10	0.12	0.16	0.05	0.08		0.06	0.50	0.01			0.02	0.03	0.01				
Nov 2023	2.25	2.33	1.45	0.47	1.14	0.12	0.16	0.11	0.13	0.11	0.12	0.17	0.06	0.10		0.06	0.33	0.01			0.01	0.03					
Dec 2023	2.20	2.19	1.53	0.54	1.12	0.12	0.16	0.12	0.11	0.11	0.12	0.16	0.06	0.09		0.06	0.33	0.01			0.01	0.03					
Jan 2024	2.37	2.21	1.55	0.65	1.17	0.11	0.16	0.15	0.13	0.12	0.14	0.17	0.08	0.10		0.06	0.25	0.01		0.01	0.01	0.01					
Feb 2024	2.38	2.22	1.52	0.69	1.21	0.12	0.17	0.22	0.16	0.13	0.13	0.17	0.09	0.11		0.06	0.22	0.01		0.01	0.01						
Mar 2024	2.53	2.19	1.54	0.69	1.14	0.12	0.16	0.25	0.14	0.14	0.12	0.16	0.09	0.10		0.06	0.22	0.01		0.01	0.01						
Apr 2024	2.53	2.16	1.51	0.73	1.24	0.34	0.17	0.27	0.18	0.15	0.13	0.15	0.07	0.11		0.07	0.19	0.01	0.01	0.01	0.01						
May 2024	2.75	2.24	1.50	0.83	1.20	0.36	0.16	0.30	0.18	0.15	0.14	0.15	0.06	0.11		0.07	0.09	0.01	0.01	0.01	0.01						
Jun 2024	2.88	2.34	1.52	0.91	0.71	0.37	0.15	0.32	0.20	0.16	0.16	0.15	0.07	0.11	0.03	0.07	0.10	0.01	0.01	0.01	0.01						
Jul 2024	2.83	2.45	1.65	1.01	0.71	0.43	0.15	0.34	0.20	0.18	0.17	0.15	0.09	0.12	0.06	0.07	0.09	0.01	0.01	0.01	0.01						
Aug 2024	2.96	2.48	1.70	1.11	0.81	0.45	0.35	0.35	0.19	0.18	0.18	0.14	0.11	0.12	0.12	0.08	0.08	0.01	0.01	0.01	0.01						
Sep 2024	3.13	2.26	1.44	1.18	0.72	0.44	0.42	0.35	0.24	0.18	0.18	0.15	0.13	0.13	0.12	0.08	0.07	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

### Overall

At least one tracker was found on 21.10% of new episodes in September, shrinking 7.46% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "38.03%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.81%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.71%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.00%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.83%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.75%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.07%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.85%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.51%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.36%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of September 2024.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 12.95% of new episodes in September, shrinking 9.10% from last month.

Of these, 15.31% had one other tracker, 10.63% had 2 other trackers, 2.01% had 3 other trackers, 1.15% had 4 other trackers, 1.11% had 5 other trackers, 0.47% had 6 other trackers, 0.26% had 7 other trackers, 0.03% had 8 other trackers, and <0.01% had 9 other trackers.

19.43% also included Chartable, 11.30% also included Podsights, 5.59% also included Podscribe, 5.57% also included Adswizz, 2.75% also included Podroll, 2.53% also included Podder, 1.74% also included Spotify, 1.69% also included Magellan AI, 1.65% also included Podcorn, 0.93% also included Claritas, 0.90% also included ArtsAI, 0.89% also included OP3, 0.62% also included Gumshoe, 0.59% also included Audiotakes, 0.55% also included Veritonic, 0.48% also included Swap.fm, 0.28% also included Blubrry, 0.05% also included CoHost Prefix, 0.04% also included Feedpress, 0.02% also included Podkite, 0.01% also included Zencastr, 0.01% also included Médiamétrie, 0.01% also included United Podcasters, and 0.01% also included AdBarker.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "61.69%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.73%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.40%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.69%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.83%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.01%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.50%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.26%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.22%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.13%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 6.67% of new episodes in September, shrinking 9.46% from last month.

Of these, 43.77% also included Podtrac, 11.77% also included Podscribe, 7.83% also included Adswizz, 4.90% also included Magellan AI, 2.69% also included Podcorn, 2.61% also included Podder, 2.55% also included ArtsAI, 2.50% also included Claritas, 1.93% also included Podroll, 1.80% also included Swap.fm, 1.78% also included Audiotakes, 1.69% also included Gumshoe, 1.61% also included OP3, 1.19% also included Veritonic, 0.76% also included Firstory, 0.37% also included Blubrry, 0.13% also included CoHost Prefix, 0.10% also included United Podcasters, 0.06% also included Podkite, 0.05% also included Feedpress, 0.04% also included AdBarker, 0.04% also included Zencastr, 0.01% also included Voxalyze, and <0.01% also included Glystn.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.75%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "23.80%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.90%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.86%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.67%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.15%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.87%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.65%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.41%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.28%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.99% of new episodes in September, shrinking 9.86% from last month.

Of these, 29.17% had one other tracker, 19.53% had 2 other trackers, 4.73% had 3 other trackers, 2.68% had 4 other trackers, 2.26% had 5 other trackers, 1.18% had 6 other trackers, 0.50% had 7 other trackers, 0.06% had 8 other trackers, and <0.01% had 9 other trackers.

42.00% also included Podtrac, 27.36% also included Podsights, 9.99% also included Podscribe, 7.61% also included Adswizz, 4.70% also included Magellan AI, 4.61% also included Spotify, 2.53% also included Claritas, 2.45% also included ArtsAI, 2.28% also included Podder, 2.05% also included Podroll, 1.99% also included Podcorn, 1.96% also included Swap.fm, 1.30% also included Audiotakes, 1.14% also included Veritonic, 0.97% also included Gumshoe, 0.92% also included OP3, 0.85% also included Firstory, 0.36% also included Blubrry, 0.14% also included CoHost Prefix, 0.10% also included United Podcasters, 0.07% also included Podkite, 0.05% also included Feedpress, 0.04% also included AdBarker, 0.03% also included Zencastr, 0.01% also included Voxalyze, and <0.01% also included Glystn.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "27.89%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "23.77%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.11%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.06%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.89%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.51%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.80%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.65%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.55%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.29%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 3.13% of new episodes in September, growing 5.58% from last month.

Of these, 16.69% had one other tracker, 12.86% had 2 other trackers, 2.17% had 3 other trackers, 1.74% had 5 other trackers, 0.79% had 4 other trackers, 0.56% had 6 other trackers, 0.37% had 7 other trackers, and 0.10% had 8 other trackers.

23.05% also included Podtrac, 14.55% also included Chartable, 10.09% also included Podroll, 4.72% also included Podscribe, 4.65% also included Podsights, 2.31% also included Magellan AI, 2.25% also included Claritas, 1.35% also included ArtsAI, 1.19% also included Spotify, 0.85% also included Blubrry, 0.75% also included Audiotakes, 0.69% also included Podder, 0.64% also included Veritonic, 0.26% also included Podcorn, 0.06% also included Swap.fm, 0.04% also included Gumshoe, 0.02% also included OP3, 0.01% also included United Podcasters, and 0.01% also included CoHost Prefix.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "49.97%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "9.15%" >}}
3. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "6.97%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "6.71%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "6.36%" >}}
6. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "5.12%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.88%" >}}
8. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.81%" >}}
9. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "1.79%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.20%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.26% of new episodes in September, shrinking 7.62% from last month.

Of these, 35.40% had 2 other trackers, 30.36% had one other tracker, 10.58% had 3 other trackers, 7.26% had 4 other trackers, 5.95% had 5 other trackers, 2.79% had 6 other trackers, 1.31% had 7 other trackers, 0.17% had 8 other trackers, and <0.01% had 9 other trackers.

72.54% also included Chartable, 64.79% also included Podtrac, 22.66% also included Podscribe, 10.09% also included Magellan AI, 6.45% also included Adswizz, 5.40% also included ArtsAI, 5.40% also included Podder, 4.85% also included Claritas, 3.79% also included Swap.fm, 3.49% also included Gumshoe, 3.43% also included Podcorn, 3.26% also included Spotify, 3.20% also included Audiotakes, 3.00% also included OP3, 2.86% also included Podroll, 2.84% also included Veritonic, 0.29% also included Blubrry, 0.28% also included CoHost Prefix, 0.21% also included United Podcasters, 0.06% also included Podkite, 0.05% also included Feedpress, 0.04% also included Zencastr, and 0.01% also included Voxalyze.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "57.42%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "24.70%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.73%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.08%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.06%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.59%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.17%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.11%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.84%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.84%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.44% of new episodes in September, shrinking 6.38% from last month.

Of these, 5.60% had one other tracker, 0.96% had 2 other trackers, 0.17% had 3 other trackers, 0.07% had 4 other trackers, 0.02% had 6 other trackers, and 0.02% had 7 other trackers.

2.56% also included Podtrac, 1.84% also included Adswizz, 1.50% also included Chartable, 1.11% also included Feedpress, 0.46% also included Podsights, 0.36% also included OP3, 0.26% also included Podcorn, 0.25% also included Podscribe, 0.07% also included Spotify, 0.06% also included Podder, 0.05% also included Magellan AI, 0.04% also included Podroll, 0.02% also included Audiotakes, and 0.02% also included Veritonic.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "40.44%" >}}
2. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "6.97%" >}}
3. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "6.68%" >}}
4. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "3.54%" >}}
5. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.02%" >}}
6. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "2.26%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.13%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.65%" >}}
9. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.21%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.77%" >}}
---

### 6. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 1.18% of new episodes in September, growing 8.49% from last month.

Of these, 21.49% had one other tracker, 16.12% had 2 other trackers, 14.83% had 5 other trackers, 13.32% had 3 other trackers, 13.32% had 4 other trackers, 6.32% had 6 other trackers, 2.95% had 7 other trackers, 0.29% had 8 other trackers, and 0.01% had 9 other trackers.

61.40% also included Podtrac, 50.71% also included Chartable, 43.40% also included Podsights, 24.92% also included Magellan AI, 13.82% also included Claritas, 13.70% also included Spotify, 13.01% also included ArtsAI, 12.53% also included Adswizz, 9.67% also included Audiotakes, 9.67% also included Podder, 6.49% also included Podcorn, 5.78% also included Gumshoe, 5.23% also included Veritonic, 4.34% also included OP3, 3.54% also included Swap.fm, 2.94% also included Podroll, 0.31% also included Blubrry, 0.25% also included CoHost Prefix, 0.23% also included United Podcasters, 0.05% also included Feedpress, 0.04% also included Zencastr, and 0.01% also included AdBarker.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "50.44%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "13.65%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.70%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.23%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.50%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.97%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.76%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.16%" >}}
9. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.84%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.43%" >}}
---

### 7. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.72% of new episodes in September, shrinking 11.08% from last month.

Of these, 22.98% had one other tracker, 6.08% had 2 other trackers, 5.93% had 5 other trackers, 4.19% had 3 other trackers, 1.89% had 4 other trackers, 0.63% had 6 other trackers, 0.09% had 7 other trackers, 0.09% had 8 other trackers, and 0.01% had 9 other trackers.

29.69% also included Podtrac, 16.59% also included Chartable, 10.78% also included Podsights, 10.66% also included Podscribe, 8.63% also included OP3, 8.30% also included Gumshoe, 1.12% also included Adswizz, 1.12% also included Podder, 0.90% also included Podroll, 0.55% also included Spotify, 0.51% also included Blubrry, 0.34% also included Magellan AI, 0.32% also included Swap.fm, 0.24% also included Feedpress, 0.13% also included CoHost Prefix, 0.10% also included United Podcasters, 0.07% also included AdBarker, 0.07% also included Podkite, and 0.02% also included Voxalyze.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "19.83%" >}}
2. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "14.47%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "13.39%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "11.94%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "10.60%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "8.98%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.01%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.89%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.22%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.18%" >}}
---

### 8. [Podroll](https://podroll.fm/)

Podroll was found on 0.44% of new episodes in September, shrinking 0.69% from last month.

Of these, 75.83% had 2 other trackers, 8.31% had one other tracker, 6.14% had 3 other trackers, 5.69% had 4 other trackers, 1.30% had 5 other trackers, 0.92% had 6 other trackers, 0.50% had 7 other trackers, 0.15% had 8 other trackers, and 0.01% had 9 other trackers.

80.85% also included Podtrac, 71.73% also included Adswizz, 27.88% also included Chartable, 14.67% also included Podsights, 7.88% also included Podscribe, 4.33% also included Swap.fm, 1.94% also included Magellan AI, 1.58% also included Claritas, 1.47% also included Podcorn, 1.15% also included Podder, 0.94% also included OP3, 0.93% also included Gumshoe, 0.72% also included ArtsAI, 0.70% also included Audiotakes, 0.57% also included Spotify, 0.26% also included CoHost Prefix, 0.19% also included United Podcasters, 0.12% also included Blubrry, and 0.05% also included Veritonic.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "70.92%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "17.14%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.08%" >}}
4. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "2.46%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.94%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.08%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.72%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.45%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.38%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.36%" >}}
---

### 9. [Podder](https://www.podderapp.com/)

Podder was found on 0.42% of new episodes in September, growing 21.56% from last month.

Of these, 51.17% had one other tracker, 11.65% had 4 other trackers, 10.78% had 2 other trackers, 8.29% had 5 other trackers, 7.94% had 3 other trackers, 3.45% had 6 other trackers, 0.58% had 7 other trackers, 0.10% had 8 other trackers, and 0.01% had 9 other trackers.

78.05% also included Podtrac, 32.55% also included Chartable, 29.05% also included Podsights, 27.17% also included Podscribe, 11.14% also included Magellan AI, 8.97% also included Audiotakes, 5.75% also included ArtsAI, 5.16% also included Adswizz, 3.16% also included Spotify, 1.91% also included Podcorn, 1.56% also included Claritas, 1.49% also included Gumshoe, 1.29% also included OP3, 1.20% also included Podroll, 0.52% also included Veritonic, 0.37% also included Swap.fm, 0.33% also included United Podcasters, 0.23% also included Podkite, 0.21% also included Blubrry, and 0.20% also included CoHost Prefix.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "52.79%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.83%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.21%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.33%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.48%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.17%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.15%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.10%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.93%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.35%" >}}
---

### 10. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.35% of new episodes in September, shrinking 0.19% from last month.

Of these, 42.36% had 2 other trackers, 15.87% had one other tracker, 11.58% had 3 other trackers, 8.75% had 6 other trackers, 8.68% had 4 other trackers, 7.42% had 7 other trackers, 2.75% had 5 other trackers, and 0.98% had 8 other trackers.

78.84% also included Chartable, 64.47% also included Podtrac, 46.11% also included Podscribe, 22.60% also included Magellan AI, 21.02% also included Podsights, 15.14% also included ArtsAI, 10.65% also included Adswizz, 9.39% also included Audiotakes, 9.24% also included Claritas, 7.58% also included Veritonic, 3.85% also included Gumshoe, 3.78% also included Podder, 1.14% also included Podcorn, 0.88% also included OP3, 0.71% also included Podroll, 0.34% also included Swap.fm, 0.31% also included Blubrry, and 0.07% also included United Podcasters.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "50.28%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "12.73%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.20%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.19%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.24%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.54%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.15%" >}}
8. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "2.17%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.70%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.56%" >}}
---

### 11. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.35% of new episodes in September, growing 1.86% from last month.

Of these, 30.71% had 5 other trackers, 20.23% had 4 other trackers, 14.88% had 6 other trackers, 13.88% had 3 other trackers, 8.40% had 7 other trackers, 5.83% had 2 other trackers, 4.01% had one other tracker, and 0.92% had 8 other trackers.

84.14% also included Podscribe, 80.50% also included Chartable, 65.24% also included Podsights, 62.73% also included Podtrac, 36.69% also included Claritas, 25.03% also included ArtsAI, 22.67% also included Spotify, 20.73% also included Adswizz, 15.27% also included Audiotakes, 13.72% also included Veritonic, 13.38% also included Podder, 2.45% also included Podroll, 2.24% also included Gumshoe, 0.88% also included Swap.fm, 0.70% also included Podcorn, 0.41% also included United Podcasters, 0.22% also included OP3, and 0.20% also included Blubrry.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "52.36%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "20.18%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.56%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.38%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.27%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.22%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.54%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.29%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.20%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.19%" >}}
---

### 12. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.24% of new episodes in September, growing 25.10% from last month.

Of these, 20.06% had one other tracker, 17.52% had 5 other trackers, 8.19% had 2 other trackers, 7.41% had 3 other trackers, 5.24% had 4 other trackers, 2.05% had 6 other trackers, 0.20% had 7 other trackers, 0.17% had 8 other trackers, and 0.02% had 9 other trackers.

48.44% also included Podtrac, 28.48% also included Podsights, 26.03% also included Podcorn, 25.88% also included Gumshoe, 23.06% also included Chartable, 21.49% also included Podscribe, 2.27% also included Podder, 2.20% also included Blubrry, 1.75% also included Podroll, 1.30% also included Spotify, 0.32% also included Magellan AI, 0.25% also included Adswizz, 0.20% also included Audiotakes, 0.20% also included ArtsAI, 0.20% also included CoHost Prefix, 0.17% also included Swap.fm, 0.17% also included Feedpress, and 0.12% also included Claritas.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "34.07%" >}}
2. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "10.68%" >}}
3. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "6.61%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.32%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.37%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.29%" >}}
7. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "3.02%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.92%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.07%" >}}
10. {{< a "https://radiolaser.fr/" "Radio Laser" >}} {{< span "weak" "1.95%" >}}
---

### 13. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.18% of new episodes in September, growing 4.55% from last month.

Of these, 36.48% had 5 other trackers, 24.04% had 6 other trackers, 15.52% had 4 other trackers, 8.13% had 7 other trackers, 5.34% had one other tracker, 4.92% had 2 other trackers, and 4.54% had 3 other trackers.

88.92% also included Podscribe, 82.67% also included Chartable, 69.91% also included Magellan AI, 65.34% also included Podtrac, 59.70% also included Podsights, 38.42% also included Adswizz, 28.12% also included ArtsAI, 17.65% also included Spotify, 14.77% also included Veritonic, 3.79% also included Podroll, 3.56% also included Podder, 0.81% also included Swap.fm, 0.45% also included Gumshoe, 0.16% also included OP3, and 0.10% also included Audiotakes.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "37.74%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "32.59%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.88%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.94%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "5.57%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.83%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.78%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.58%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.26%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.26%" >}}
---

### 14. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.18% of new episodes in September, shrinking 1.96% from last month.

Of these, 26.22% had 5 other trackers, 18.87% had 6 other trackers, 18.87% had 7 other trackers, 12.35% had 3 other trackers, 11.75% had 4 other trackers, 8.81% had 2 other trackers, 1.79% had 8 other trackers, and 1.22% had one other tracker.

85.50% also included Podscribe, 81.76% also included Chartable, 67.99% also included Podsights, 65.01% also included Podtrac, 48.73% also included Magellan AI, 29.56% also included Spotify, 28.73% also included Claritas, 24.13% also included Audiotakes, 23.60% also included Adswizz, 21.52% also included Veritonic, 13.44% also included Podder, 1.75% also included Podroll, 1.42% also included Swap.fm, 0.26% also included OP3, and 0.13% also included Gumshoe.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "37.44%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "16.68%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "15.99%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.46%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.60%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "6.65%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.42%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.79%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.70%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.23%" >}}
---

### 15. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.15% of new episodes in September, growing 6.82% from last month.

Of these, 14.80% had one other tracker, and 2.22% had 2 other trackers.

10.63% also included Blubrry, 3.89% also included Podtrac, 2.18% also included Chartable, 1.15% also included Podcorn, 0.75% also included Podsights, 0.36% also included Podscribe, and 0.28% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "55.61%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.61%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.12%" >}}
4. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "4.28%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.54%" >}}
6. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.34%" >}}
7. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "2.14%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.59%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.31%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.03%" >}}
---

### 16. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.13% of new episodes in September, growing 17.68% from last month.

Of these, 32.19% had 4 other trackers, 22.29% had 5 other trackers, 15.85% had 3 other trackers, 15.67% had 6 other trackers, 7.43% had 2 other trackers, 2.66% had one other tracker, and 2.03% had 7 other trackers.

86.45% also included Podscribe, 59.16% also included Chartable, 58.31% also included Podtrac, 54.84% also included Podsights, 40.43% also included Magellan AI, 32.82% also included ArtsAI, 28.55% also included Podder, 24.94% also included Spotify, 17.83% also included Adswizz, 3.78% also included Veritonic, 2.34% also included Podroll, 1.89% also included Gumshoe, 1.08% also included United Podcasters, 0.36% also included Swap.fm, 0.36% also included OP3, 0.18% also included Blubrry, and 0.14% also included Claritas.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.89%" >}}
2. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "26.02%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "16.39%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "10.09%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.55%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.34%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.76%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.76%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "1.13%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.09%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.13% of new episodes in September, growing 4.35% from last month.

Of these, 36.82% had 5 other trackers, 16.36% had 4 other trackers, 13.11% had 3 other trackers, 11.34% had 2 other trackers, 11.06% had one other tracker, 3.77% had 6 other trackers, 0.33% had 8 other trackers, 0.28% had 7 other trackers, and 0.05% had 9 other trackers.

63.09% also included Podtrac, 61.79% also included Podsights, 53.32% also included Podscribe, 48.21% also included OP3, 46.68% also included Podcorn, 45.37% also included Chartable, 10.55% also included Spotify, 6.14% also included Magellan AI, 4.88% also included Podder, 3.21% also included Podroll, 1.95% also included Audiotakes, 1.44% also included CoHost Prefix, 1.02% also included Adswizz, 0.65% also included Claritas, 0.60% also included United Podcasters, 0.56% also included Swap.fm, 0.56% also included Veritonic, and 0.19% also included ArtsAI.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "48.68%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "25.57%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "17.29%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.11%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.44%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.93%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.28%" >}}
8. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.28%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.19%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.09%" >}}
---

### 18. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.12% of new episodes in September, growing 9.22% from last month.

Of these, 37.76% had 3 other trackers, 24.83% had 2 other trackers, 18.37% had 4 other trackers, 12.15% had one other tracker, 2.77% had 5 other trackers, 1.99% had 6 other trackers, 0.83% had 7 other trackers, and 0.19% had 8 other trackers.

96.21% also included Chartable, 70.02% also included Podsights, 50.87% also included Podtrac, 34.16% also included Podscribe, 15.60% also included Podroll, 2.53% also included Magellan AI, 2.09% also included ArtsAI, 1.90% also included Podcorn, 1.65% also included Adswizz, 1.26% also included Podder, 1.21% also included Claritas, 1.07% also included United Podcasters, 0.97% also included Spotify, 0.58% also included Gumshoe, 0.39% also included Audiotakes, 0.39% also included Zencastr, 0.34% also included OP3, 0.34% also included Veritonic, and 0.10% also included CoHost Prefix.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "84.99%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.60%" >}}
3. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "2.96%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.12%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.97%" >}}
6. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.68%" >}}
7. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.68%" >}}
---

### 19. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.08% of new episodes in September, shrinking 4.25% from last month.

Of these, 32.16% had 7 other trackers, 22.05% had 6 other trackers, 13.99% had 4 other trackers, 10.62% had 5 other trackers, 9.30% had 2 other trackers, 6.23% had 3 other trackers, and 3.96% had 8 other trackers.

87.84% also included Podtrac, 84.10% also included Chartable, 79.12% also included Podsights, 76.12% also included Podscribe, 59.12% also included Magellan AI, 47.62% also included ArtsAI, 33.41% also included Claritas, 32.75% also included Spotify, 24.54% also included Adswizz, 6.15% also included Audiotakes, 2.71% also included Podder, 0.88% also included Gumshoe, 0.51% also included Swap.fm, 0.29% also included Blubrry, and 0.29% also included Podroll.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "64.69%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "20.88%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.62%" >}}
4. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.30%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.93%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.90%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.95%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.29%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.22%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.22%" >}}
---

### 20. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.07% of new episodes in September, shrinking 11.28% from last month.

Of these, 2.38% had one other tracker.

2.38% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "43.82%" >}}
2. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "32.41%" >}}
3. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "19.57%" >}}
---

### 21. [Firstory](https://firstory.me/)

Firstory was found on 0.06% of new episodes in September, shrinking 6.89% from last month.

Of these, 81.64% had one other tracker.

81.64% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "100.00%" >}}
---

### 22. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in September, shrinking 2.35% from last month.

Of these, 31.14% had one other tracker, 5.99% had 2 other trackers, 4.79% had 4 other trackers, 4.79% had 5 other trackers, and 1.80% had 3 other trackers.

41.32% also included Chartable, 22.16% also included Podtrac, 13.77% also included Podsights, 9.58% also included Podder, and 4.79% also included Podcorn.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "37.72%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "21.56%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "12.57%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "9.58%" >}}
5. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "4.79%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.79%" >}}
7. {{< a "https://azure.microsoft.com/en-us/services/storage/blobs/" "Microsoft Azure Blob Storage" >}} {{< span "weak" "3.59%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.99%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.40%" >}}
---

### 23. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.01% of new episodes in September, growing 47.76% from last month.

Of these, 26.67% had 3 other trackers, 20.61% had 4 other trackers, 15.76% had one other tracker, 10.91% had 2 other trackers, 9.70% had 5 other trackers, 4.24% had 8 other trackers, 1.82% had 6 other trackers, and 0.61% had 9 other trackers.

88.48% also included Chartable, 63.64% also included Podsights, 60.00% also included Podtrac, 30.30% also included Podscribe, 18.79% also included Gumshoe, 11.52% also included Podroll, 9.70% also included Podcorn, 8.48% also included Podder, 4.85% also included OP3, 1.82% also included Adswizz, and 1.21% also included Swap.fm.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "60.61%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "12.73%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "9.70%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "6.06%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.24%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.82%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.82%" >}}
8. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.82%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.21%" >}}
---

### 24. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in September, shrinking 18.48% from last month.

Of these, 25.16% had one other tracker, 18.06% had 3 other trackers, 16.77% had 5 other trackers, 9.68% had 2 other trackers, 5.81% had 4 other trackers, 5.16% had 6 other trackers, and 2.58% had 8 other trackers.

64.52% also included Chartable, 51.61% also included Podsights, 29.03% also included Podscribe, 18.71% also included Podtrac, 15.48% also included Audiotakes, 15.48% also included Magellan AI, 14.84% also included Podder, 14.19% also included Swap.fm, 9.03% also included Podroll, 8.39% also included Gumshoe, 7.74% also included Podcorn, 3.23% also included Adswizz, 2.58% also included Spotify, and 2.58% also included Zencastr.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "43.23%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "15.48%" >}}
3. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "12.26%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.32%" >}}
5. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "3.87%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.23%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.23%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.58%" >}}
9. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "2.58%" >}}
10. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "1.94%" >}}
---

### 25. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in September, growing 3.69% from last month.

Of these, 17.24% had one other tracker, 10.34% had 2 other trackers, 2.76% had 5 other trackers, and 2.76% had 6 other trackers.

22.76% also included Chartable, 21.38% also included Podtrac, 10.34% also included Podsights, 5.52% also included Podscribe, 5.52% also included Swap.fm, and 2.76% also included United Podcasters.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "31.72%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "23.45%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "12.41%" >}}
4. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "11.03%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "8.28%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.83%" >}}
7. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "3.45%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.76%" >}}
9. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "2.07%" >}}
---

### 26. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in September, growing 22.22% from last month.

Of these, 34.67% had 2 other trackers, 21.33% had one other tracker, and 2.67% had 4 other trackers.

54.67% also included Chartable, 32.00% also included Podtrac, 12.00% also included Podcorn, and 2.67% also included Podscribe.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "46.67%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "18.67%" >}}
3. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "13.33%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "8.00%" >}}
5. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "5.33%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.00%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.00%" >}}
---

### 27. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on <0.01% of new episodes in September, shrinking 13.02% from last month.

Of these, 42.86% had one other tracker, and 28.57% had 2 other trackers.

57.14% also included Chartable, 28.57% also included Podsights, and 14.29% also included Podcorn.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "50.00%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "28.57%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "14.29%" >}}
4. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "7.14%" >}}
---

### 28. [Glystn](https://glystn.com/)

Glystn was found on <0.01% of new episodes in September, shrinking 0.60% from last month.

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
*Updated 2024-10-01, with data for the month of September 2024.*

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
 - [Podcast Tracker Rankings by Episode Share (August 2024)](/archive/podcast-trackers-by-episode-share-august-2024/)
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
