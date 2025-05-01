---
title: "Top Podcast Tracking Services by Episode Share (March 2025)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-march-2025"
images:
- trackers-2025-03.png
date: 2025-04-05T16:00:00-04:00
lastmod: 2025-04-05T16:00:00-04:00
draft: false
rssrevision: 2025-03
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.6 million in March 2025), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in March, how many
of them included one or more of these tracking services?  Some episodes had as many as *ten* of these redirecting trackers!

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

{{< details "_September 2023: Spotify for Creators data_" >}}
_Starting mid-September, we gained a better signal of when Spotify for Creators (formerly Spotify for Podcasters, formerly Anchor) podcasts release new episodes, so our crawlers are finding more.
Higher share of new episodes on S4P (which typically do not have prefixes) will have led to lower share overall._
{{< /details >}}

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Adswizz	Podsights	Podscribe	Blubrry	Chartable	Podcorn	Podroll	Podder	OP3	Spotify	Swap.fm	Audiotakes	Claritas	ArtsAI	Feedpress	Gumshoe	Veritonic	RSS Insight	CoHost Prefix	Médiamétrie	United Podcasters	Podkite	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	1.00	1.16		2.07	4.06	2.09									0.32					0.42									1.61
Oct 2021	4.05	1.01	1.20		2.11	4.09	2.13									0.34					0.54									1.61
Nov 2021	4.07	1.02	1.25		2.01	4.30	2.14									0.32					0.57									0.59
Dec 2021	4.06	1.24	1.19		1.57	4.42	2.27									0.19					0.59									
Jan 2022	4.11	1.41	1.21		1.56	4.45	2.31									0.16					0.63									
Feb 2022	4.15	1.44	1.25		1.53	4.48	2.38									0.17					0.58									
Mar 2022	4.37	1.51	1.34		1.56	4.72	2.40									0.17					0.53									
Apr 2022	4.44	1.49	1.33		1.55	4.71	2.33									0.16					0.51									
May 2022	4.49	1.58	1.41		1.48	4.87	2.26									0.17					0.56									
Jun 2022	4.75	1.77	1.54		1.50	5.10	2.06									0.21					0.62						0.02			
Jul 2022	4.70	1.89	1.50		1.50	5.10	2.16									0.25					0.54						0.02			
Aug 2022	4.83	2.08	1.73		1.51	5.26	2.45								0.10	0.20					0.41						0.01			
Sep 2022	7.53	2.26	1.74	0.02	1.49	5.40	2.45							0.01	0.09	0.21					0.52		0.01				0.02	0.02		
Oct 2022	8.24	2.35	1.81	0.07	1.61	5.48	2.51			0.03				0.02	0.10	0.18					0.50		0.01	0.01			0.02	0.04		
Nov 2022	8.11	2.37	2.03	0.15	1.62	5.62	2.43		0.01	0.04				0.03	0.10	0.18					0.50		0.01	0.01			0.02	0.05		
Dec 2022	8.01	2.32	1.81	0.03	1.61	5.54	2.05		0.04	0.05				0.02	0.05	0.18					0.49		0.01	0.01		0.01	0.02	0.05		
Jan 2023	7.85	2.35	1.88	0.20	1.61	5.56	2.15		0.11	0.07				0.06	0.10	0.18					0.54		0.01	0.01		0.01	0.02	0.06		
Feb 2023	7.58	2.29	1.92	0.21	1.62	5.51	2.30		0.11	0.07				0.07	0.10	0.19					0.49		0.01	0.01		0.01	0.02	0.06	0.03	
Mar 2023	7.79	2.25	2.03	0.21	1.53	5.53	2.22	0.04	0.11	0.08				0.07	0.11	0.18		0.04			0.45		0.01	0.01		0.01	0.02	0.06		
Apr 2023	7.66	2.26	2.00	0.21	1.67	5.43	2.20	0.06	0.15	0.09				0.07	0.11	0.17	0.08	0.05			0.45		0.01	0.01		0.01	0.01			
May 2023	7.58	2.27	2.04	0.24	1.67	5.59	2.28	0.09	0.15	0.09				0.08	0.11	0.19	0.07	0.05			0.45		0.01	0.01	0.01	0.01	0.01			
Jun 2023	8.22	2.39	2.23	0.26	1.64	5.83	1.86	0.10	0.15	0.09				0.07	0.12	0.19	0.08	0.05			0.51		0.01	0.01	0.01	0.01	0.01			
Jul 2023	8.60	2.38	2.52	0.27	1.53	5.95	1.17	0.14	0.14	0.08	0.01			0.07	0.11	0.18	0.06	0.06			0.55		0.01	0.01	0.01	0.01	0.01			
Aug 2023	9.19	2.72	2.76	0.36	1.58	6.43	1.23	0.16	0.15	0.11	0.03		0.04	0.08	0.12	0.17	0.07	0.07			0.53		0.01	0.01	0.02	0.01				
Sep 2023	8.46	2.49	2.47	0.37	1.39	5.77	1.10	0.13	0.15	0.10	0.05		0.05	0.10	0.12	0.16	0.07	0.06			0.58		0.01	0.01	0.02	0.01				
Oct 2023	7.90	2.29	2.28	0.39	1.37	5.54	1.11	0.12	0.16	0.10	0.08		0.05	0.10	0.12	0.16	0.08	0.06			0.50		0.01	0.02	0.03	0.01				
Nov 2023	7.65	2.25	2.33	0.47	1.45	5.59	1.14	0.12	0.16	0.13	0.11		0.06	0.11	0.12	0.17	0.10	0.06			0.33		0.01	0.01	0.03					
Dec 2023	7.48	2.20	2.19	0.54	1.53	5.60	1.12	0.12	0.16	0.11	0.12		0.06	0.11	0.12	0.16	0.09	0.06			0.33		0.01	0.01	0.03					
Jan 2024	7.64	2.37	2.21	0.65	1.55	5.61	1.17	0.11	0.16	0.13	0.15		0.08	0.12	0.14	0.17	0.10	0.06			0.25	0.01	0.01	0.01	0.01					
Feb 2024	7.69	2.38	2.22	0.69	1.52	5.58	1.21	0.12	0.17	0.16	0.22		0.09	0.13	0.13	0.17	0.11	0.06			0.22	0.01	0.01	0.01						
Mar 2024	9.01	2.53	2.19	0.69	1.54	5.46	1.14	0.12	0.16	0.14	0.25		0.09	0.14	0.12	0.16	0.10	0.06			0.22	0.01	0.01	0.01						
Apr 2024	10.78	2.53	2.16	0.73	1.51	5.47	1.24	0.34	0.17	0.18	0.27		0.07	0.15	0.13	0.15	0.11	0.07		0.01	0.19	0.01	0.01	0.01						
May 2024	11.59	2.75	2.24	0.83	1.50	5.63	1.20	0.36	0.16	0.18	0.30		0.06	0.15	0.14	0.15	0.11	0.07		0.01	0.09	0.01	0.01	0.01						
Jun 2024	11.54	2.88	2.34	0.91	1.52	6.06	0.71	0.37	0.15	0.20	0.32	0.03	0.07	0.16	0.16	0.15	0.11	0.07		0.01	0.10	0.01	0.01	0.01						
Jul 2024	12.34	2.83	2.45	1.01	1.65	6.80	0.71	0.43	0.15	0.20	0.34	0.06	0.09	0.18	0.17	0.15	0.12	0.07		0.01	0.09	0.01	0.01	0.01						
Aug 2024	14.22	2.96	2.48	1.11	1.70	6.72	0.81	0.45	0.35	0.19	0.35	0.12	0.11	0.18	0.18	0.14	0.12	0.08		0.01	0.08	0.01	0.01	0.01						
Sep 2024	12.95	3.13	2.26	1.18	1.44	5.99	0.72	0.44	0.42	0.24	0.35	0.12	0.13	0.18	0.18	0.15	0.13	0.08		0.01	0.07	0.01	0.01	0.01						
Oct 2024	12.24	3.23	2.35	1.23	1.53	5.49	0.66	0.43	0.39	0.27	0.40	0.17	0.14	0.19	0.18	0.14	0.12	0.09		0.01	0.09	0.01	0.01	0.01						
Nov 2024	11.86	3.21	2.31	1.27	1.52	4.66	0.63	0.43	0.41	0.29	0.44	0.19	0.14	0.21	0.17	0.11	0.12	0.08		0.01	0.10	0.01	0.01	0.01						
Dec 2024	12.56	3.06	2.13	1.29	1.40	2.29	0.62	0.43	0.54	0.29	0.45	0.24	0.15	0.21	0.18	0.09	0.12	0.08		0.01	0.09	0.01	0.01	0.01						
Jan 2025	12.62	2.92	1.73	1.31	1.36	1.54	0.66	0.46	0.54	0.34	0.41	0.27	0.16	0.21	0.19	0.12	0.13	0.08		0.01	0.04	0.01	0.01	0.01						
Feb 2025	12.47	2.74	1.70	1.25	1.45	1.43	0.66	0.46	0.48	0.33	0.36	0.28	0.16	0.22	0.18	0.14	0.12	0.08		0.01	0.01	0.01	0.01	0.01						
Mar 2025	12.18	2.87	1.51	1.28	1.25	1.18	0.67	0.47	0.36	0.33	0.33	0.27	0.25	0.21	0.18	0.14	0.13	0.07	0.04	0.01	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} are the clear top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podsights	Podscribe	Blubrry	Podcorn	Podroll	Podder	OP3	Spotify	Swap.fm	Audiotakes	Claritas	ArtsAI	Feedpress	Gumshoe	Veritonic	RSS Insight	CoHost Prefix	Médiamétrie	United Podcasters	Podkite	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	1.00	1.16		2.07	2.09									0.32					0.42									1.61
Oct 2021	1.01	1.20		2.11	2.13									0.34					0.54									1.61
Nov 2021	1.02	1.25		2.01	2.14									0.32					0.57									0.59
Dec 2021	1.24	1.19		1.57	2.27									0.19					0.59									
Jan 2022	1.41	1.21		1.56	2.31									0.16					0.63									
Feb 2022	1.44	1.25		1.53	2.38									0.17					0.58									
Mar 2022	1.51	1.34		1.56	2.40									0.17					0.53									
Apr 2022	1.49	1.33		1.55	2.33									0.16					0.51									
May 2022	1.58	1.41		1.48	2.26									0.17					0.56									
Jun 2022	1.77	1.54		1.50	2.06									0.21					0.62						0.02			
Jul 2022	1.89	1.50		1.50	2.16									0.25					0.54						0.02			
Aug 2022	2.08	1.73		1.51	2.45								0.10	0.20					0.41						0.01			
Sep 2022	2.26	1.74	0.02	1.49	2.45							0.01	0.09	0.21					0.52		0.01				0.02	0.02		
Oct 2022	2.35	1.81	0.07	1.61	2.51			0.03				0.02	0.10	0.18					0.50		0.01	0.01			0.02	0.04		
Nov 2022	2.37	2.03	0.15	1.62	2.43		0.01	0.04				0.03	0.10	0.18					0.50		0.01	0.01			0.02	0.05		
Dec 2022	2.32	1.81	0.03	1.61	2.05		0.04	0.05				0.02	0.05	0.18					0.49		0.01	0.01		0.01	0.02	0.05		
Jan 2023	2.35	1.88	0.20	1.61	2.15		0.11	0.07				0.06	0.10	0.18					0.54		0.01	0.01		0.01	0.02	0.06		
Feb 2023	2.29	1.92	0.21	1.62	2.30		0.11	0.07				0.07	0.10	0.19					0.49		0.01	0.01		0.01	0.02	0.06	0.03	
Mar 2023	2.25	2.03	0.21	1.53	2.22	0.04	0.11	0.08				0.07	0.11	0.18		0.04			0.45		0.01	0.01		0.01	0.02	0.06		
Apr 2023	2.26	2.00	0.21	1.67	2.20	0.06	0.15	0.09				0.07	0.11	0.17	0.08	0.05			0.45		0.01	0.01		0.01	0.01			
May 2023	2.27	2.04	0.24	1.67	2.28	0.09	0.15	0.09				0.08	0.11	0.19	0.07	0.05			0.45		0.01	0.01	0.01	0.01	0.01			
Jun 2023	2.39	2.23	0.26	1.64	1.86	0.10	0.15	0.09				0.07	0.12	0.19	0.08	0.05			0.51		0.01	0.01	0.01	0.01	0.01			
Jul 2023	2.38	2.52	0.27	1.53	1.17	0.14	0.14	0.08	0.01			0.07	0.11	0.18	0.06	0.06			0.55		0.01	0.01	0.01	0.01	0.01			
Aug 2023	2.72	2.76	0.36	1.58	1.23	0.16	0.15	0.11	0.03		0.04	0.08	0.12	0.17	0.07	0.07			0.53		0.01	0.01	0.02	0.01				
Sep 2023	2.49	2.47	0.37	1.39	1.10	0.13	0.15	0.10	0.05		0.05	0.10	0.12	0.16	0.07	0.06			0.58		0.01	0.01	0.02	0.01				
Oct 2023	2.29	2.28	0.39	1.37	1.11	0.12	0.16	0.10	0.08		0.05	0.10	0.12	0.16	0.08	0.06			0.50		0.01	0.02	0.03	0.01				
Nov 2023	2.25	2.33	0.47	1.45	1.14	0.12	0.16	0.13	0.11		0.06	0.11	0.12	0.17	0.10	0.06			0.33		0.01	0.01	0.03					
Dec 2023	2.20	2.19	0.54	1.53	1.12	0.12	0.16	0.11	0.12		0.06	0.11	0.12	0.16	0.09	0.06			0.33		0.01	0.01	0.03					
Jan 2024	2.37	2.21	0.65	1.55	1.17	0.11	0.16	0.13	0.15		0.08	0.12	0.14	0.17	0.10	0.06			0.25	0.01	0.01	0.01	0.01					
Feb 2024	2.38	2.22	0.69	1.52	1.21	0.12	0.17	0.16	0.22		0.09	0.13	0.13	0.17	0.11	0.06			0.22	0.01	0.01	0.01						
Mar 2024	2.53	2.19	0.69	1.54	1.14	0.12	0.16	0.14	0.25		0.09	0.14	0.12	0.16	0.10	0.06			0.22	0.01	0.01	0.01						
Apr 2024	2.53	2.16	0.73	1.51	1.24	0.34	0.17	0.18	0.27		0.07	0.15	0.13	0.15	0.11	0.07		0.01	0.19	0.01	0.01	0.01						
May 2024	2.75	2.24	0.83	1.50	1.20	0.36	0.16	0.18	0.30		0.06	0.15	0.14	0.15	0.11	0.07		0.01	0.09	0.01	0.01	0.01						
Jun 2024	2.88	2.34	0.91	1.52	0.71	0.37	0.15	0.20	0.32	0.03	0.07	0.16	0.16	0.15	0.11	0.07		0.01	0.10	0.01	0.01	0.01						
Jul 2024	2.83	2.45	1.01	1.65	0.71	0.43	0.15	0.20	0.34	0.06	0.09	0.18	0.17	0.15	0.12	0.07		0.01	0.09	0.01	0.01	0.01						
Aug 2024	2.96	2.48	1.11	1.70	0.81	0.45	0.35	0.19	0.35	0.12	0.11	0.18	0.18	0.14	0.12	0.08		0.01	0.08	0.01	0.01	0.01						
Sep 2024	3.13	2.26	1.18	1.44	0.72	0.44	0.42	0.24	0.35	0.12	0.13	0.18	0.18	0.15	0.13	0.08		0.01	0.07	0.01	0.01	0.01						
Oct 2024	3.23	2.35	1.23	1.53	0.66	0.43	0.39	0.27	0.40	0.17	0.14	0.19	0.18	0.14	0.12	0.09		0.01	0.09	0.01	0.01	0.01						
Nov 2024	3.21	2.31	1.27	1.52	0.63	0.43	0.41	0.29	0.44	0.19	0.14	0.21	0.17	0.11	0.12	0.08		0.01	0.10	0.01	0.01	0.01						
Dec 2024	3.06	2.13	1.29	1.40	0.62	0.43	0.54	0.29	0.45	0.24	0.15	0.21	0.18	0.09	0.12	0.08		0.01	0.09	0.01	0.01	0.01						
Jan 2025	2.92	1.73	1.31	1.36	0.66	0.46	0.54	0.34	0.41	0.27	0.16	0.21	0.19	0.12	0.13	0.08		0.01	0.04	0.01	0.01	0.01						
Feb 2025	2.74	1.70	1.25	1.45	0.66	0.46	0.48	0.33	0.36	0.28	0.16	0.22	0.18	0.14	0.12	0.08		0.01	0.01	0.01	0.01	0.01						
Mar 2025	2.87	1.51	1.28	1.25	0.67	0.47	0.36	0.33	0.33	0.27	0.25	0.21	0.18	0.14	0.13	0.07	0.04	0.01	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

### Overall

At least one tracker was found on 17.60% of new episodes in March, shrinking 1.95% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "46.40%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "11.79%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "9.57%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.97%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.37%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.14%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.80%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.52%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.43%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.16%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of March 2025.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 12.18% of new episodes in March, shrinking 2.49% from last month.

Of these, 9.62% had one other tracker, 7.35% had 2 other trackers, 1.24% had 5 other trackers, 1.23% had 4 other trackers, 1.19% had 3 other trackers, 0.30% had 6 other trackers, 0.18% had 7 other trackers, and 0.02% had 8 other trackers.

8.18% also included Podsights, 6.44% also included Adswizz, 5.25% also included Podscribe, 4.74% also included Chartable, 3.32% also included Podroll, 2.05% also included Magellan AI, 1.82% also included Podder, 1.54% also included Spotify, 1.46% also included Swap.fm, 1.33% also included Podcorn, 1.12% also included OP3, 1.08% also included Claritas, 0.99% also included Blubrry, 0.89% also included ArtsAI, 0.67% also included Audiotakes, 0.66% also included Gumshoe, 0.52% also included Veritonic, 0.07% also included CoHost Prefix, 0.05% also included Feedpress, 0.03% also included United Podcasters, 0.01% also included Podkite, 0.01% also included Médiamétrie, 0.01% also included AdBarker, and <0.01% also included Zencastr.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "66.91%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "7.76%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.52%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.82%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.57%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.00%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.80%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.02%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.50%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.50%" >}}
---

### 2. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.87% of new episodes in March, growing 4.67% from last month.

Of these, 17.17% had 2 other trackers, 12.42% had one other tracker, 4.09% had 3 other trackers, 2.07% had 4 other trackers, 1.80% had 5 other trackers, 0.49% had 6 other trackers, and 0.30% had 7 other trackers.

27.29% also included Podtrac, 12.92% also included Podroll, 10.82% also included Podscribe, 8.04% also included Magellan AI, 4.52% also included Audiotakes, 3.60% also included Podsights, 2.69% also included Swap.fm, 2.58% also included Spotify, 2.56% also included Claritas, 1.56% also included ArtsAI, 1.44% also included Blubrry, 0.80% also included Chartable, 0.72% also included Veritonic, 0.66% also included Podder, 0.61% also included OP3, 0.49% also included Podcorn, 0.08% also included Gumshoe, and 0.03% also included United Podcasters.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "68.46%" >}}
2. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "5.71%" >}}
3. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "4.53%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "3.65%" >}}
5. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "3.60%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.32%" >}}
7. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "2.13%" >}}
8. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "1.79%" >}}
9. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.40%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.88%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 2.26% of new episodes in March, shrinking 11.44% from last month.

Of these, 56.09% also included Podtrac, 30.87% also included Podscribe, 15.01% also included Magellan AI, 8.59% also included Adswizz, 8.09% also included Claritas, 6.98% also included Swap.fm, 6.23% also included ArtsAI, 4.86% also included Audiotakes, 4.05% also included Gumshoe, 4.00% also included Podcorn, 3.55% also included OP3, 3.25% also included Podder, 3.16% also included Veritonic, 2.81% also included Podroll, 0.41% also included Blubrry, 0.31% also included United Podcasters, 0.30% also included CoHost Prefix, 0.10% also included Feedpress, 0.03% also included Podkite, 0.02% also included Firstory, 0.01% also included AdBarker, and 0.01% also included Zencastr.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "57.34%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "13.60%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.15%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.21%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.42%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.11%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.90%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.44%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.28%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.13%" >}}
---

### 3. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.51% of new episodes in March, shrinking 8.47% from last month.

Of these, 30.96% had one other tracker, 24.59% had 2 other trackers, 11.79% had 4 other trackers, 10.16% had 3 other trackers, 8.64% had 5 other trackers, 2.79% had 6 other trackers, 1.12% had 7 other trackers, and 0.15% had 8 other trackers.

65.85% also included Podtrac, 42.78% also included Chartable, 33.72% also included Podscribe, 16.75% also included Magellan AI, 8.83% also included Swap.fm, 7.22% also included Claritas, 7.18% also included ArtsAI, 6.84% also included Adswizz, 5.52% also included Audiotakes, 5.25% also included Podcorn, 5.06% also included Gumshoe, 4.95% also included OP3, 4.24% also included Spotify, 4.06% also included Podder, 3.90% also included Veritonic, 3.27% also included Podroll, 0.41% also included Blubrry, 0.38% also included CoHost Prefix, 0.34% also included United Podcasters, 0.16% also included Feedpress, and 0.03% also included Podkite.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "62.43%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "16.62%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.78%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.40%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.38%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.68%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.58%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.28%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.08%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.06%" >}}
---

### 4. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 1.28% of new episodes in March, growing 5.42% from last month.

Of these, 17.83% had one other tracker, 17.82% had 3 other trackers, 17.62% had 4 other trackers, 14.94% had 2 other trackers, 13.91% had 5 other trackers, 3.46% had 6 other trackers, 1.75% had 7 other trackers, and 0.18% had 8 other trackers.

50.02% also included Podtrac, 39.92% also included Podsights, 38.98% also included Magellan AI, 24.32% also included Adswizz, 18.89% also included Audiotakes, 18.78% also included Chartable, 16.24% also included Spotify, 15.92% also included Claritas, 12.29% also included ArtsAI, 7.34% also included Swap.fm, 6.63% also included Podcorn, 6.04% also included Gumshoe, 5.92% also included Podder, 5.36% also included OP3, 4.56% also included Veritonic, 3.24% also included Podroll, 0.47% also included CoHost Prefix, 0.44% also included United Podcasters, 0.27% also included Blubrry, 0.02% also included Podkite, and 0.02% also included AdBarker.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "38.76%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "21.78%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "9.92%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.54%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.50%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "4.35%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.23%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.55%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.76%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.49%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.25% of new episodes in March, shrinking 2.67% from last month.

Of these, 14.17% had one other tracker, 0.64% had 2 other trackers, 0.32% had 3 other trackers, 0.09% had 4 other trackers, 0.04% had 6 other trackers, and 0.02% had 5 other trackers.

9.59% also included Podtrac, 3.31% also included Adswizz, 1.49% also included Feedpress, 0.54% also included OP3, 0.49% also included Podsights, 0.39% also included Podcorn, 0.37% also included Swap.fm, 0.27% also included Podscribe, 0.21% also included Chartable, 0.21% also included Podder, 0.10% also included Spotify, 0.10% also included Magellan AI, 0.02% also included Podkite, 0.02% also included ArtsAI, 0.01% also included Audiotakes, and 0.01% also included Veritonic.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "47.21%" >}}
2. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "3.97%" >}}
3. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.61%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.59%" >}}
5. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.91%" >}}
6. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "1.53%" >}}
7. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.31%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.27%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.08%" >}}
10. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.07%" >}}
---

### 6. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 1.18% of new episodes in March, shrinking 16.13% from last month.

Of these, 32.22% had 2 other trackers, 21.55% had one other tracker, 8.17% had 3 other trackers, 7.33% had 4 other trackers, 3.10% had 5 other trackers, 1.95% had 6 other trackers, 0.29% had 7 other trackers, and 0.16% had 8 other trackers.

54.89% also included Podsights, 48.96% also included Podtrac, 20.36% also included Podscribe, 10.10% also included Swap.fm, 9.62% also included Magellan AI, 6.54% also included Spotify, 4.03% also included Claritas, 3.00% also included Podroll, 2.32% also included Veritonic, 2.14% also included Podder, 1.95% also included Adswizz, 1.39% also included ArtsAI, 1.11% also included Gumshoe, 1.08% also included Podcorn, 0.77% also included Audiotakes, 0.74% also included OP3, 0.51% also included CoHost Prefix, 0.33% also included United Podcasters, 0.22% also included Blubrry, 0.20% also included Feedpress, 0.03% also included Firstory, 0.02% also included Podkite, 0.02% also included AdBarker, and 0.02% also included Zencastr.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "83.76%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.48%" >}}
3. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.63%" >}}
4. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.57%" >}}
5. {{< a "https://cloud.google.com/" "Google Cloud" >}} {{< span "weak" "0.53%" >}}
6. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "0.38%" >}}
7. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.35%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.34%" >}}
9. {{< a "https://www.wideorbit.com/" "WideOrbit" >}} {{< span "weak" "0.33%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.25%" >}}
---

### 7. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.67% of new episodes in March, growing 2.58% from last month.

Of these, 12.10% had one other tracker, 7.91% had 5 other trackers, 5.50% had 2 other trackers, 2.38% had 4 other trackers, 1.87% had 3 other trackers, 0.17% had 6 other trackers, 0.11% had 8 other trackers, and 0.05% had 7 other trackers.

24.16% also included Podtrac, 12.62% also included Podscribe, 11.81% also included Podsights, 11.19% also included OP3, 9.44% also included Gumshoe, 3.05% also included Podroll, 2.10% also included Adswizz, 1.89% also included Chartable, 1.41% also included Podder, 0.75% also included Spotify, 0.73% also included Blubrry, 0.23% also included Swap.fm, 0.17% also included Magellan AI, 0.10% also included United Podcasters, 0.07% also included Podkite, 0.07% also included Feedpress, 0.06% also included Audiotakes, 0.06% also included CoHost Prefix, 0.05% also included AdBarker, and 0.02% also included Zencastr.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "23.96%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "12.51%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "11.54%" >}}
4. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "10.70%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "7.85%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.27%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "6.85%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.36%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.72%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.09%" >}}
---

### 8. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.64% of new episodes in March, growing 10.75% from last month.

Of these, 23.57% had 3 other trackers, 22.31% had 4 other trackers, 15.34% had 5 other trackers, 10.87% had 2 other trackers, 5.88% had 6 other trackers, 5.07% had one other tracker, 3.15% had 7 other trackers, and 0.24% had 8 other trackers.

77.25% also included Podscribe, 39.30% also included Podsights, 38.78% also included Podtrac, 35.81% also included Adswizz, 26.50% also included Audiotakes, 26.02% also included Claritas, 18.92% also included Spotify, 17.58% also included Chartable, 15.43% also included ArtsAI, 9.00% also included Swap.fm, 7.52% also included Veritonic, 4.26% also included Podder, 3.00% also included Podroll, 1.60% also included Gumshoe, 0.91% also included OP3, 0.38% also included United Podcasters, 0.19% also included Blubrry, 0.17% also included Podcorn, and 0.11% also included CoHost Prefix.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "32.47%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.01%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.75%" >}}
4. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "6.22%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.40%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.21%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.15%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "3.14%" >}}
9. {{< a "https://www.americanpublicmedia.org/" "American Public Media" >}} {{< span "weak" "1.49%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.47%" >}}
---

### 9. [Podroll](https://podroll.fm/)

Podroll was found on 0.47% of new episodes in March, growing 3.15% from last month.

Of these, 78.26% had 2 other trackers, 8.41% had one other tracker, 4.35% had 3 other trackers, 3.65% had 4 other trackers, 1.60% had 5 other trackers, 1.35% had 6 other trackers, 0.42% had 7 other trackers, and 0.16% had 8 other trackers.

85.64% also included Podtrac, 78.66% also included Adswizz, 10.48% also included Podsights, 8.77% also included Podscribe, 7.51% also included Chartable, 5.10% also included Swap.fm, 4.34% also included Podcorn, 4.10% also included Magellan AI, 1.77% also included Audiotakes, 1.60% also included Claritas, 1.10% also included ArtsAI, 1.00% also included OP3, 0.79% also included Spotify, 0.74% also included Gumshoe, 0.35% also included United Podcasters, 0.35% also included Veritonic, 0.33% also included Podder, and 0.30% also included CoHost Prefix.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "78.81%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.16%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.31%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.25%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "1.71%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.92%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.76%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.49%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.16%" >}}
10. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "0.16%" >}}
---

### 10. [Podder](https://www.podderapp.com/)

Podder was found on 0.36% of new episodes in March, shrinking 23.12% from last month.

Of these, 41.68% had one other tracker, 9.30% had 4 other trackers, 9.21% had 2 other trackers, 4.91% had 5 other trackers, 4.73% had 3 other trackers, 0.90% had 6 other trackers, 0.12% had 8 other trackers, and 0.09% had 7 other trackers.

61.12% also included Podtrac, 20.83% also included Podscribe, 16.89% also included Podsights, 9.26% also included Audiotakes, 7.56% also included Magellan AI, 6.94% also included Chartable, 5.24% also included Adswizz, 3.28% also included ArtsAI, 3.17% also included Spotify, 2.61% also included Podcorn, 1.54% also included OP3, 1.28% also included Gumshoe, 1.14% also included Claritas, 0.72% also included Blubrry, 0.43% also included Podroll, 0.43% also included Swap.fm, 0.32% also included Veritonic, 0.12% also included CoHost Prefix, 0.10% also included United Podcasters, and 0.05% also included Podkite.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "41.77%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "25.73%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.35%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.72%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.66%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.68%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "1.88%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.79%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.45%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.49%" >}}
---

### 11. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.33% of new episodes in March, growing 2.30% from last month.

Of these, 20.27% had one other tracker, 16.43% had 5 other trackers, 6.69% had 2 other trackers, 4.02% had 4 other trackers, 3.04% had 3 other trackers, 0.48% had 6 other trackers, 0.17% had 7 other trackers, and 0.13% had 8 other trackers.

40.79% also included Podtrac, 22.47% also included Podcorn, 22.38% also included Podsights, 20.45% also included Podscribe, 19.60% also included Gumshoe, 5.21% also included Adswizz, 2.61% also included Chartable, 2.02% also included Blubrry, 1.76% also included Magellan AI, 1.67% also included Podder, 1.41% also included Podroll, 1.37% also included Spotify, 1.32% also included Swap.fm, 0.87% also included ArtsAI, 0.67% also included Claritas, 0.48% also included Podkite, 0.48% also included Audiotakes, 0.31% also included CoHost Prefix, 0.11% also included Feedpress, 0.07% also included United Podcasters, and 0.04% also included Zencastr.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "29.03%" >}}
2. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "10.17%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.37%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "6.08%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.24%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.61%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.06%" >}}
8. {{< a "https://vodio.fr/" "Vodio" >}} {{< span "weak" "2.33%" >}}
9. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "2.11%" >}}
10. {{< a "https://radiolaser.fr/" "Radio Laser" >}} {{< span "weak" "2.11%" >}}
---

### 12. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.33% of new episodes in March, shrinking 5.96% from last month.

Of these, 25.82% had 2 other trackers, 16.55% had 5 other trackers, 14.82% had 4 other trackers, 10.59% had one other tracker, 7.95% had 3 other trackers, 5.79% had 7 other trackers, 4.24% had 6 other trackers, and 0.56% had 8 other trackers.

62.72% also included Podscribe, 56.58% also included Podtrac, 36.88% also included Magellan AI, 29.01% also included Claritas, 23.29% also included Chartable, 22.38% also included Adswizz, 19.40% also included Podsights, 17.17% also included ArtsAI, 11.04% also included Audiotakes, 7.29% also included Veritonic, 3.64% also included Gumshoe, 3.49% also included Podder, 1.52% also included Podcorn, 1.39% also included OP3, 1.12% also included Podroll, 1.05% also included Swap.fm, 0.39% also included Blubrry, and 0.21% also included United Podcasters.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.56%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "21.31%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "16.57%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.18%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.52%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.29%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.67%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.71%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.52%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.56%" >}}
---

### 13. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.27% of new episodes in March, growing 1.17% from last month.

Of these, 31.37% had 2 other trackers, 17.74% had 3 other trackers, 17.08% had 4 other trackers, 15.88% had one other tracker, 9.61% had 5 other trackers, 2.76% had 6 other trackers, 0.89% had 7 other trackers, and 0.11% had 8 other trackers.

65.47% also included Podtrac, 49.07% also included Podsights, 43.76% also included Chartable, 34.44% also included Podscribe, 28.43% also included Adswizz, 21.32% also included Magellan AI, 8.84% also included Podroll, 6.24% also included ArtsAI, 2.92% also included Claritas, 2.73% also included Audiotakes, 1.71% also included Blubrry, 1.62% also included OP3, 1.28% also included Spotify, 1.23% also included Gumshoe, 0.87% also included Veritonic, 0.68% also included United Podcasters, 0.57% also included Podcorn, 0.57% also included Podder, and 0.18% also included CoHost Prefix.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "54.03%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "28.04%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.91%" >}}
4. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "4.90%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.82%" >}}
6. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.50%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.36%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.18%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.16%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.09%" >}}
---

### 14. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.25% of new episodes in March, growing 53.46% from last month.

Of these, 46.39% had 3 other trackers, 27.65% had 4 other trackers, 13.93% had 5 other trackers, 7.50% had 2 other trackers, 2.37% had 6 other trackers, 0.65% had one other tracker, and 0.35% had 7 other trackers.

98.06% also included Podscribe, 69.40% also included Magellan AI, 52.68% also included Adswizz, 33.92% also included Podsights, 33.24% also included Podtrac, 19.49% also included ArtsAI, 14.83% also included Spotify, 13.67% also included Podder, 3.70% also included Chartable, 3.40% also included Podroll, 3.02% also included Swap.fm, 2.82% also included Veritonic, 1.64% also included Gumshoe, 0.73% also included United Podcasters, 0.65% also included OP3, 0.20% also included Claritas, 0.18% also included Podcorn, and 0.08% also included Blubrry.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "52.46%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "18.01%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "17.30%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.41%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.12%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.23%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.93%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.65%" >}}
9. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.45%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.25%" >}}
---

### 15. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.21% of new episodes in March, growing 1.74% from last month.

Of these, 31.71% had 5 other trackers, 29.07% had 4 other trackers, 14.58% had 6 other trackers, 7.45% had 7 other trackers, 6.81% had 2 other trackers, 6.40% had 3 other trackers, 2.09% had one other tracker, and 0.73% had 8 other trackers.

95.46% also included Podscribe, 78.73% also included Magellan AI, 61.91% also included Podtrac, 51.24% also included Podsights, 45.04% also included Spotify, 34.57% also included ArtsAI, 34.45% also included Adswizz, 22.32% also included Chartable, 19.32% also included Veritonic, 3.72% also included Swap.fm, 3.55% also included Podroll, 1.95% also included Podder, 1.19% also included Gumshoe, 1.05% also included OP3, 0.38% also included CoHost Prefix, 0.23% also included Audiotakes, and 0.06% also included United Podcasters.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "36.98%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "30.78%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "14.49%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.37%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.17%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.49%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.55%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.26%" >}}
9. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.23%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.20%" >}}
---

### 16. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.18% of new episodes in March, shrinking 1.20% from last month.

Of these, 29.02% had 5 other trackers, 25.34% had 4 other trackers, 11.78% had 6 other trackers, 11.54% had 7 other trackers, 9.48% had 2 other trackers, 6.44% had 3 other trackers, 5.27% had one other tracker, and 0.88% had 8 other trackers.

89.63% also included Podscribe, 62.00% also included Podsights, 61.89% also included Podtrac, 56.79% also included Magellan AI, 42.04% also included Claritas, 32.41% also included Spotify, 27.39% also included Audiotakes, 25.55% also included Adswizz, 19.67% also included Veritonic, 9.70% also included Swap.fm, 9.34% also included Chartable, 6.79% also included Podder, 2.97% also included Podroll, 1.66% also included OP3, 0.32% also included Gumshoe, 0.18% also included Blubrry, 0.11% also included CoHost Prefix, and 0.07% also included United Podcasters.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.01%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "20.06%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "18.40%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "13.77%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.05%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "5.17%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.91%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.28%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.18%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.18%" >}}
---

### 17. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.14% of new episodes in March, growing 1.77% from last month.

Of these, 18.28% had one other tracker, and 1.66% had 2 other trackers.

13.18% also included Blubrry, 4.49% also included Podtrac, 1.66% also included Podsights, 1.66% also included Chartable, 0.35% also included Podcorn, and 0.26% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "56.50%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "9.95%" >}}
3. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "5.67%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.97%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.18%" >}}
6. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "2.88%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.36%" >}}
8. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.53%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.48%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.48%" >}}
---

### 18. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.13% of new episodes in March, growing 2.57% from last month.

Of these, 42.30% had 5 other trackers, 13.69% had 4 other trackers, 13.20% had one other tracker, 10.71% had 2 other trackers, 5.38% had 3 other trackers, 1.32% had 7 other trackers, 1.12% had 6 other trackers, and 0.34% had 8 other trackers.

63.28% also included Podtrac, 60.93% also included Podscribe, 60.34% also included Podsights, 51.74% also included OP3, 50.02% also included Podcorn, 10.32% also included Chartable, 9.49% also included Spotify, 8.12% also included Magellan AI, 3.67% also included Podder, 3.18% also included Audiotakes, 2.84% also included CoHost Prefix, 2.74% also included Podroll, 2.64% also included Swap.fm, 2.00% also included Claritas, 1.86% also included Adswizz, 1.52% also included Veritonic, 0.64% also included United Podcasters, and 0.44% also included ArtsAI.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "53.50%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "18.88%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "18.09%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.35%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.20%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.42%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.54%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.24%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.24%" >}}
10. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.24%" >}}
---

### 19. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.07% of new episodes in March, shrinking 7.28% from last month.

Of these, 28.56% had 7 other trackers, 25.46% had 6 other trackers, 16.83% had 5 other trackers, 15.83% had 3 other trackers, 5.86% had 2 other trackers, 3.85% had 4 other trackers, 2.09% had 8 other trackers, and 0.42% had one other tracker.

85.68% also included Podtrac, 79.65% also included Podsights, 78.64% also included Podscribe, 65.49% also included Magellan AI, 55.61% also included Claritas, 46.57% also included ArtsAI, 37.02% also included Chartable, 32.58% also included Spotify, 27.89% also included Adswizz, 9.38% also included Audiotakes, 3.18% also included Swap.fm, 2.60% also included Gumshoe, 2.26% also included Podroll, 1.59% also included Podder, 0.25% also included Blubrry, and 0.25% also included CoHost Prefix.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "63.57%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "23.62%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.85%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.85%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.26%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.09%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.84%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.34%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.34%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.25%" >}}
---

### 20. [RSS Insight](https://www.rssinsight.com/)

RSS Insight was found on 0.04% of new episodes in March, growing 109.36% from last month.

For episodes that used RSS Insight, here are the top underlying podcast hosts:

1. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "100.00%" >}}
---

### 21. [Firstory](https://firstory.me/)

Firstory was found on 0.04% of new episodes in March, growing 4.41% from last month.

Of these, 0.89% had one other tracker.

0.89% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.55%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.45%" >}}
---

### 22. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.01% of new episodes in March, growing 7.65% from last month.

Of these, 22.37% had one other tracker, 18.72% had 4 other trackers, 17.35% had 5 other trackers, 6.39% had 2 other trackers, 3.65% had 6 other trackers, 3.20% had 8 other trackers, 2.28% had 3 other trackers, and 1.37% had 7 other trackers.

61.19% also included Podtrac, 44.29% also included Chartable, 44.29% also included Podscribe, 42.47% also included Podsights, 26.48% also included Gumshoe, 10.50% also included Podroll, 7.76% also included OP3, 5.94% also included Claritas, 5.02% also included Magellan AI, 3.65% also included Swap.fm, 3.20% also included Podcorn, 3.20% also included Podder, 1.37% also included ArtsAI, and 1.37% also included Veritonic.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "48.40%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "16.89%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.87%" >}}
4. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "5.94%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.94%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "5.02%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.28%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.91%" >}}
9. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "0.46%" >}}
---

### 23. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.01% of new episodes in March, growing 2.23% from last month.

Of these, 12.71% had one other tracker.

12.71% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "100.00%" >}}
---

### 24. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in March, growing 9.66% from last month.

Of these, 28.05% had one other tracker, 22.56% had 4 other trackers, 15.24% had 3 other trackers, 9.76% had 2 other trackers, 7.93% had 6 other trackers, 7.32% had 5 other trackers, and 3.05% had 8 other trackers.

55.49% also included Podscribe, 51.22% also included Podsights, 38.41% also included Chartable, 31.10% also included Podtrac, 24.39% also included Magellan AI, 18.29% also included Swap.fm, 17.68% also included Audiotakes, 16.46% also included Podroll, 9.15% also included Adswizz, 7.93% also included Gumshoe, 6.71% also included Podcorn, 6.71% also included Spotify, 3.66% also included Podder, 2.44% also included OP3, 1.22% also included ArtsAI, and 1.22% also included Claritas.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "48.78%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "15.24%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.15%" >}}
4. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "8.54%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.71%" >}}
6. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "3.05%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.44%" >}}
8. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "2.44%" >}}
9. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "2.44%" >}}
10. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.22%" >}}
---

### 25. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in March, shrinking 6.31% from last month.

Of these, 30.15% had one other tracker, 3.68% had 4 other trackers, 2.94% had 2 other trackers, and 2.21% had 5 other trackers.

19.12% also included OP3, 19.12% also included Podtrac, 5.88% also included Podcorn, 5.15% also included Podsights, 3.68% also included Podscribe, 3.68% also included Blubrry, 2.94% also included Chartable, and 2.21% also included Podder.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "25.00%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "19.12%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "14.71%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "13.24%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.29%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.88%" >}}
7. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "3.68%" >}}
8. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.68%" >}}
9. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "2.94%" >}}
10. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "1.47%" >}}
---

### 26. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in March, shrinking 26.91% from last month.

Of these, 12.79% had one other tracker, and 2.33% had 2 other trackers.

9.30% also included Podtrac, 3.49% also included Chartable, 2.33% also included OP3, and 2.33% also included Podcorn.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "32.56%" >}}
2. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "19.77%" >}}
3. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "16.28%" >}}
4. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "9.30%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.30%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.14%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.33%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.33%" >}}
---

### 27. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in March, growing 3.26% from last month.

Of these, 25.37% had one other tracker, and 7.46% had 3 other trackers.

28.36% also included Podtrac, 7.46% also included Podscribe, 7.46% also included Podcorn, and 4.48% also included Chartable.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "43.28%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "14.93%" >}}
3. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "13.43%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "8.96%" >}}
5. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "7.46%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.46%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.48%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
*Updated 2025-04-05, with data for the month of March 2025.*

*Updated 2025-03-01, with data for the month of February 2025.*

*Updated 2025-02-03, with data for the month of January 2025.*

*Updated 2025-01-02, with data for the month of December 2024.*

*Updated 2024-12-01, with data for the month of November 2024.*

*Updated 2024-11-06, with data for the month of October 2024.*

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

*Updated 2023-11-02, with data for the month of October 2023. Improved accuracy in observing Spotify for Creators podcasts: more S4C new episodes leads to lower share of prefixed episodes overall.*

*Updated 2023-10-01, with data for the month of September 2023. Improved accuracy in observing Spotify for Creators podcasts: more S4C new episodes leads to lower share of prefixed episodes overall.*

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
 - [Podcast Tracker Rankings by Episode Share (February 2025)](/archive/podcast-trackers-by-episode-share-february-2025/)
 - [Podcast Tracker Rankings by Episode Share (January 2025)](/archive/podcast-trackers-by-episode-share-january-2025/)
 - [Podcast Tracker Rankings by Episode Share (December 2024)](/archive/podcast-trackers-by-episode-share-december-2024/)
 - [Podcast Tracker Rankings by Episode Share (November 2024)](/archive/podcast-trackers-by-episode-share-november-2024/)
 - [Podcast Tracker Rankings by Episode Share (October 2024)](/archive/podcast-trackers-by-episode-share-october-2024/)
 - [Podcast Tracker Rankings by Episode Share (September 2024)](/archive/podcast-trackers-by-episode-share-september-2024/)
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2025-03.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
