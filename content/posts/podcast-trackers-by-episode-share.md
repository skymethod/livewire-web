---
title: "Top Podcast Tracking Services by Episode Share (October 2025)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2025-10.png
date: 2025-11-01T12:16:00-04:00
lastmod: 2025-11-01T12:16:00-04:00
draft: false
rssrevision: 2025-10
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.5 million in October 2025), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in October, how many
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
Month	Podtrac	Adswizz	Podscribe	Podsights	Blubrry	Chartable	Podcorn	Podroll	Claritas	Spotify	OP3	Swap.fm	ArtsAI	Podder	Feedpress	Gumshoe	Veritonic	CoHost Prefix	United Podcasters	Podkite	Médiamétrie	Audiotakes	RSS Insight	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	1.00		1.16	2.07	4.06	2.09								0.32						0.42									1.61
Oct 2021	4.05	1.01		1.20	2.11	4.09	2.13								0.34						0.54									1.61
Nov 2021	4.07	1.02		1.25	2.01	4.30	2.14								0.32						0.57									0.59
Dec 2021	4.06	1.24		1.19	1.57	4.42	2.27								0.19						0.59									
Jan 2022	4.11	1.41		1.21	1.56	4.45	2.31								0.16						0.63									
Feb 2022	4.15	1.44		1.25	1.53	4.48	2.38								0.17						0.58									
Mar 2022	4.37	1.51		1.34	1.56	4.72	2.40								0.17						0.53									
Apr 2022	4.44	1.49		1.33	1.55	4.71	2.33								0.16						0.51									
May 2022	4.49	1.58		1.41	1.48	4.87	2.26								0.17						0.56									
Jun 2022	4.75	1.77		1.54	1.50	5.10	2.06								0.21						0.62						0.02			
Jul 2022	4.70	1.89		1.50	1.50	5.10	2.16								0.25						0.54						0.02			
Aug 2022	4.83	2.08		1.73	1.51	5.26	2.45						0.10		0.20						0.41						0.01			
Sep 2022	7.53	2.26	0.02	1.74	1.49	5.40	2.45		0.01				0.09		0.21					0.01	0.52						0.02	0.02		
Oct 2022	8.24	2.35	0.07	1.81	1.61	5.48	2.51		0.02		0.03		0.10		0.18					0.01	0.50			0.01			0.02	0.04		
Nov 2022	8.11	2.37	0.15	2.03	1.62	5.62	2.43		0.03		0.04		0.10	0.01	0.18					0.01	0.50			0.01			0.02	0.05		
Dec 2022	8.01	2.32	0.03	1.81	1.61	5.54	2.05		0.02		0.05		0.05	0.04	0.18					0.01	0.49			0.01		0.01	0.02	0.05		
Jan 2023	7.85	2.35	0.20	1.88	1.61	5.56	2.15		0.06		0.07		0.10	0.11	0.18					0.01	0.54			0.01		0.01	0.02	0.06		
Feb 2023	7.58	2.29	0.21	1.92	1.62	5.51	2.30		0.07		0.07		0.10	0.11	0.19					0.01	0.49			0.01		0.01	0.02	0.06	0.03	
Mar 2023	7.79	2.25	0.21	2.03	1.53	5.53	2.22	0.04	0.07		0.08		0.11	0.11	0.18		0.04			0.01	0.45			0.01		0.01	0.02	0.06		
Apr 2023	7.66	2.26	0.21	2.00	1.67	5.43	2.20	0.06	0.07		0.09		0.11	0.15	0.17	0.08	0.05			0.01	0.45			0.01		0.01	0.01			
May 2023	7.58	2.27	0.24	2.04	1.67	5.59	2.28	0.09	0.08		0.09		0.11	0.15	0.19	0.07	0.05			0.01	0.45			0.01	0.01	0.01	0.01			
Jun 2023	8.22	2.39	0.26	2.23	1.64	5.83	1.86	0.10	0.07		0.09		0.12	0.15	0.19	0.08	0.05			0.01	0.51			0.01	0.01	0.01	0.01			
Jul 2023	8.60	2.38	0.27	2.52	1.53	5.95	1.17	0.14	0.07	0.01	0.08		0.11	0.14	0.18	0.06	0.06			0.01	0.55			0.01	0.01	0.01	0.01			
Aug 2023	9.19	2.72	0.36	2.76	1.58	6.43	1.23	0.16	0.08	0.03	0.11		0.12	0.15	0.17	0.07	0.07			0.01	0.53	0.04		0.01	0.02	0.01				
Sep 2023	8.46	2.49	0.37	2.47	1.39	5.77	1.10	0.13	0.10	0.05	0.10		0.12	0.15	0.16	0.07	0.06			0.01	0.58	0.05		0.01	0.02	0.01				
Oct 2023	7.90	2.29	0.39	2.28	1.37	5.54	1.11	0.12	0.10	0.08	0.10		0.12	0.16	0.16	0.08	0.06			0.01	0.50	0.05		0.02	0.03	0.01				
Nov 2023	7.65	2.25	0.47	2.33	1.45	5.59	1.14	0.12	0.11	0.11	0.13		0.12	0.16	0.17	0.10	0.06			0.01	0.33	0.06		0.01	0.03					
Dec 2023	7.48	2.20	0.54	2.19	1.53	5.60	1.12	0.12	0.11	0.12	0.11		0.12	0.16	0.16	0.09	0.06			0.01	0.33	0.06		0.01	0.03					
Jan 2024	7.64	2.37	0.65	2.21	1.55	5.61	1.17	0.11	0.12	0.15	0.13		0.14	0.16	0.17	0.10	0.06		0.01	0.01	0.25	0.08		0.01	0.01					
Feb 2024	7.69	2.38	0.69	2.22	1.52	5.58	1.21	0.12	0.13	0.22	0.16		0.13	0.17	0.17	0.11	0.06		0.01	0.01	0.22	0.09		0.01						
Mar 2024	9.01	2.53	0.69	2.19	1.54	5.46	1.14	0.12	0.14	0.25	0.14		0.12	0.16	0.16	0.10	0.06		0.01	0.01	0.22	0.09		0.01						
Apr 2024	10.78	2.53	0.73	2.16	1.51	5.47	1.24	0.34	0.15	0.27	0.18		0.13	0.17	0.15	0.11	0.07	0.01	0.01	0.01	0.19	0.07		0.01						
May 2024	11.59	2.75	0.83	2.24	1.50	5.63	1.20	0.36	0.15	0.30	0.18		0.14	0.16	0.15	0.11	0.07	0.01	0.01	0.01	0.09	0.06		0.01						
Jun 2024	11.54	2.88	0.91	2.34	1.52	6.06	0.71	0.37	0.16	0.32	0.20	0.03	0.16	0.15	0.15	0.11	0.07	0.01	0.01	0.01	0.10	0.07		0.01						
Jul 2024	12.34	2.83	1.01	2.45	1.65	6.80	0.71	0.43	0.18	0.34	0.20	0.06	0.17	0.15	0.15	0.12	0.07	0.01	0.01	0.01	0.09	0.09		0.01						
Aug 2024	14.22	2.96	1.11	2.48	1.70	6.72	0.81	0.45	0.18	0.35	0.19	0.12	0.18	0.35	0.14	0.12	0.08	0.01	0.01	0.01	0.08	0.11		0.01						
Sep 2024	12.95	3.13	1.18	2.26	1.44	5.99	0.72	0.44	0.18	0.35	0.24	0.12	0.18	0.42	0.15	0.13	0.08	0.01	0.01	0.01	0.07	0.13		0.01						
Oct 2024	12.24	3.23	1.23	2.35	1.53	5.49	0.66	0.43	0.19	0.40	0.27	0.17	0.18	0.39	0.14	0.12	0.09	0.01	0.01	0.01	0.09	0.14		0.01						
Nov 2024	11.86	3.21	1.27	2.31	1.52	4.66	0.63	0.43	0.21	0.44	0.29	0.19	0.17	0.41	0.11	0.12	0.08	0.01	0.01	0.01	0.10	0.14		0.01						
Dec 2024	12.56	3.06	1.29	2.13	1.40	2.29	0.62	0.43	0.21	0.45	0.29	0.24	0.18	0.54	0.09	0.12	0.08	0.01	0.01	0.01	0.09	0.15		0.01						
Jan 2025	12.62	2.92	1.31	1.73	1.36	1.54	0.66	0.46	0.21	0.41	0.34	0.27	0.19	0.54	0.12	0.13	0.08	0.01	0.01	0.01	0.04	0.16		0.01						
Feb 2025	12.47	2.74	1.25	1.70	1.45	1.43	0.66	0.46	0.22	0.36	0.33	0.28	0.18	0.48	0.14	0.12	0.08	0.01	0.01	0.01	0.01	0.16		0.01						
Mar 2025	12.18	2.87	1.28	1.51	1.25	1.18	0.67	0.47	0.21	0.33	0.33	0.27	0.18	0.36	0.14	0.13	0.07	0.01	0.01	0.01	0.01	0.25	0.04	0.01						
Apr 2025	12.35	2.97	1.53	1.64	1.26	1.28	0.68	0.48	0.23	0.44	0.34	0.30	0.19	0.33	0.13	0.12	0.08	0.01	0.01	0.01	0.02	0.41	0.03	0.01						
May 2025	12.48	2.97	1.61	1.74	1.40	1.31	0.64	0.46	0.24	0.46	0.39	0.33	0.20	0.22	0.13	0.12	0.07	0.01	0.02	0.01	0.02	0.40	0.05							
Jun 2025	12.99	2.73	1.65	1.70	1.34	1.30	0.65	0.46	0.26	0.47	0.39	0.35	0.21	0.20	0.13	0.12	0.07	0.01	0.02	0.01	0.02	0.40	0.04							
Jul 2025	13.83	2.87	1.76	1.71	1.16	1.30	0.66	0.48	0.72	0.50	0.33	0.39	0.23	0.20	0.13	0.12	0.07	0.01	0.02	0.01	0.01									
Aug 2025	14.30	3.24	1.95	1.83	1.35	1.32	0.67	0.49	0.79	0.54	0.35	0.37	0.20	0.21	0.14	0.14	0.08	0.02	0.02	0.01	0.01									
Sep 2025	14.56	3.37	1.98	1.46	1.17	1.16	0.64	0.55	0.58	0.53	0.37	0.33	0.21	0.20	0.14	0.13	0.08	0.02	0.02	0.01	0.01									
Oct 2025	15.39	3.28	2.02	1.39	1.16	1.00	0.65	0.57	0.52	0.50	0.39	0.35	0.21	0.18	0.14	0.13	0.08	0.02	0.01	0.01										
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} have historically been the top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podscribe	Podsights	Blubrry	Podcorn	Podroll	Claritas	Spotify	OP3	Swap.fm	ArtsAI	Podder	Feedpress	Gumshoe	Veritonic	CoHost Prefix	United Podcasters	Podkite	Médiamétrie	Audiotakes	RSS Insight	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	1.00		1.16	2.07	2.09								0.32						0.42									1.61
Oct 2021	1.01		1.20	2.11	2.13								0.34						0.54									1.61
Nov 2021	1.02		1.25	2.01	2.14								0.32						0.57									0.59
Dec 2021	1.24		1.19	1.57	2.27								0.19						0.59									
Jan 2022	1.41		1.21	1.56	2.31								0.16						0.63									
Feb 2022	1.44		1.25	1.53	2.38								0.17						0.58									
Mar 2022	1.51		1.34	1.56	2.40								0.17						0.53									
Apr 2022	1.49		1.33	1.55	2.33								0.16						0.51									
May 2022	1.58		1.41	1.48	2.26								0.17						0.56									
Jun 2022	1.77		1.54	1.50	2.06								0.21						0.62						0.02			
Jul 2022	1.89		1.50	1.50	2.16								0.25						0.54						0.02			
Aug 2022	2.08		1.73	1.51	2.45						0.10		0.20						0.41						0.01			
Sep 2022	2.26	0.02	1.74	1.49	2.45		0.01				0.09		0.21					0.01	0.52						0.02	0.02		
Oct 2022	2.35	0.07	1.81	1.61	2.51		0.02		0.03		0.10		0.18					0.01	0.50			0.01			0.02	0.04		
Nov 2022	2.37	0.15	2.03	1.62	2.43		0.03		0.04		0.10	0.01	0.18					0.01	0.50			0.01			0.02	0.05		
Dec 2022	2.32	0.03	1.81	1.61	2.05		0.02		0.05		0.05	0.04	0.18					0.01	0.49			0.01		0.01	0.02	0.05		
Jan 2023	2.35	0.20	1.88	1.61	2.15		0.06		0.07		0.10	0.11	0.18					0.01	0.54			0.01		0.01	0.02	0.06		
Feb 2023	2.29	0.21	1.92	1.62	2.30		0.07		0.07		0.10	0.11	0.19					0.01	0.49			0.01		0.01	0.02	0.06	0.03	
Mar 2023	2.25	0.21	2.03	1.53	2.22	0.04	0.07		0.08		0.11	0.11	0.18		0.04			0.01	0.45			0.01		0.01	0.02	0.06		
Apr 2023	2.26	0.21	2.00	1.67	2.20	0.06	0.07		0.09		0.11	0.15	0.17	0.08	0.05			0.01	0.45			0.01		0.01	0.01			
May 2023	2.27	0.24	2.04	1.67	2.28	0.09	0.08		0.09		0.11	0.15	0.19	0.07	0.05			0.01	0.45			0.01	0.01	0.01	0.01			
Jun 2023	2.39	0.26	2.23	1.64	1.86	0.10	0.07		0.09		0.12	0.15	0.19	0.08	0.05			0.01	0.51			0.01	0.01	0.01	0.01			
Jul 2023	2.38	0.27	2.52	1.53	1.17	0.14	0.07	0.01	0.08		0.11	0.14	0.18	0.06	0.06			0.01	0.55			0.01	0.01	0.01	0.01			
Aug 2023	2.72	0.36	2.76	1.58	1.23	0.16	0.08	0.03	0.11		0.12	0.15	0.17	0.07	0.07			0.01	0.53	0.04		0.01	0.02	0.01				
Sep 2023	2.49	0.37	2.47	1.39	1.10	0.13	0.10	0.05	0.10		0.12	0.15	0.16	0.07	0.06			0.01	0.58	0.05		0.01	0.02	0.01				
Oct 2023	2.29	0.39	2.28	1.37	1.11	0.12	0.10	0.08	0.10		0.12	0.16	0.16	0.08	0.06			0.01	0.50	0.05		0.02	0.03	0.01				
Nov 2023	2.25	0.47	2.33	1.45	1.14	0.12	0.11	0.11	0.13		0.12	0.16	0.17	0.10	0.06			0.01	0.33	0.06		0.01	0.03					
Dec 2023	2.20	0.54	2.19	1.53	1.12	0.12	0.11	0.12	0.11		0.12	0.16	0.16	0.09	0.06			0.01	0.33	0.06		0.01	0.03					
Jan 2024	2.37	0.65	2.21	1.55	1.17	0.11	0.12	0.15	0.13		0.14	0.16	0.17	0.10	0.06		0.01	0.01	0.25	0.08		0.01	0.01					
Feb 2024	2.38	0.69	2.22	1.52	1.21	0.12	0.13	0.22	0.16		0.13	0.17	0.17	0.11	0.06		0.01	0.01	0.22	0.09		0.01						
Mar 2024	2.53	0.69	2.19	1.54	1.14	0.12	0.14	0.25	0.14		0.12	0.16	0.16	0.10	0.06		0.01	0.01	0.22	0.09		0.01						
Apr 2024	2.53	0.73	2.16	1.51	1.24	0.34	0.15	0.27	0.18		0.13	0.17	0.15	0.11	0.07	0.01	0.01	0.01	0.19	0.07		0.01						
May 2024	2.75	0.83	2.24	1.50	1.20	0.36	0.15	0.30	0.18		0.14	0.16	0.15	0.11	0.07	0.01	0.01	0.01	0.09	0.06		0.01						
Jun 2024	2.88	0.91	2.34	1.52	0.71	0.37	0.16	0.32	0.20	0.03	0.16	0.15	0.15	0.11	0.07	0.01	0.01	0.01	0.10	0.07		0.01						
Jul 2024	2.83	1.01	2.45	1.65	0.71	0.43	0.18	0.34	0.20	0.06	0.17	0.15	0.15	0.12	0.07	0.01	0.01	0.01	0.09	0.09		0.01						
Aug 2024	2.96	1.11	2.48	1.70	0.81	0.45	0.18	0.35	0.19	0.12	0.18	0.35	0.14	0.12	0.08	0.01	0.01	0.01	0.08	0.11		0.01						
Sep 2024	3.13	1.18	2.26	1.44	0.72	0.44	0.18	0.35	0.24	0.12	0.18	0.42	0.15	0.13	0.08	0.01	0.01	0.01	0.07	0.13		0.01						
Oct 2024	3.23	1.23	2.35	1.53	0.66	0.43	0.19	0.40	0.27	0.17	0.18	0.39	0.14	0.12	0.09	0.01	0.01	0.01	0.09	0.14		0.01						
Nov 2024	3.21	1.27	2.31	1.52	0.63	0.43	0.21	0.44	0.29	0.19	0.17	0.41	0.11	0.12	0.08	0.01	0.01	0.01	0.10	0.14		0.01						
Dec 2024	3.06	1.29	2.13	1.40	0.62	0.43	0.21	0.45	0.29	0.24	0.18	0.54	0.09	0.12	0.08	0.01	0.01	0.01	0.09	0.15		0.01						
Jan 2025	2.92	1.31	1.73	1.36	0.66	0.46	0.21	0.41	0.34	0.27	0.19	0.54	0.12	0.13	0.08	0.01	0.01	0.01	0.04	0.16		0.01						
Feb 2025	2.74	1.25	1.70	1.45	0.66	0.46	0.22	0.36	0.33	0.28	0.18	0.48	0.14	0.12	0.08	0.01	0.01	0.01	0.01	0.16		0.01						
Mar 2025	2.87	1.28	1.51	1.25	0.67	0.47	0.21	0.33	0.33	0.27	0.18	0.36	0.14	0.13	0.07	0.01	0.01	0.01	0.01	0.25	0.04	0.01						
Apr 2025	2.97	1.53	1.64	1.26	0.68	0.48	0.23	0.44	0.34	0.30	0.19	0.33	0.13	0.12	0.08	0.01	0.01	0.01	0.02	0.41	0.03	0.01						
May 2025	2.97	1.61	1.74	1.40	0.64	0.46	0.24	0.46	0.39	0.33	0.20	0.22	0.13	0.12	0.07	0.01	0.02	0.01	0.02	0.40	0.05							
Jun 2025	2.73	1.65	1.70	1.34	0.65	0.46	0.26	0.47	0.39	0.35	0.21	0.20	0.13	0.12	0.07	0.01	0.02	0.01	0.02	0.40	0.04							
Jul 2025	2.87	1.76	1.71	1.16	0.66	0.48	0.72	0.50	0.33	0.39	0.23	0.20	0.13	0.12	0.07	0.01	0.02	0.01	0.01									
Aug 2025	3.24	1.95	1.83	1.35	0.67	0.49	0.79	0.54	0.35	0.37	0.20	0.21	0.14	0.14	0.08	0.02	0.02	0.01	0.01									
Sep 2025	3.37	1.98	1.46	1.17	0.64	0.55	0.58	0.53	0.37	0.33	0.21	0.20	0.14	0.13	0.08	0.02	0.02	0.01	0.01									
Oct 2025	3.28	2.02	1.39	1.16	0.65	0.57	0.52	0.50	0.39	0.35	0.21	0.18	0.14	0.13	0.08	0.02	0.01	0.01										
{{< /graph >}}

---

### Overall

At least one tracker was found on 21.13% of new episodes in October, growing 3.68% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "53.08%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.97%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "7.87%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.67%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.74%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.55%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.82%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.56%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.27%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.21%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of October 2025.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 15.39% of new episodes in October, growing 5.62% from last month.

Of these, 6.75% had one other tracker, 6.19% had 2 other trackers, 1.20% had 3 other trackers, 1.18% had 4 other trackers, 1.01% had 5 other trackers, 0.47% had 6 other trackers, 0.14% had 7 other trackers, and <0.01% had 9 other trackers.

5.93% also included Podsights, 5.49% also included Podscribe, 5.46% also included Adswizz, 3.61% also included Chartable, 3.05% also included Podroll, 2.50% also included Magellan AI, 2.08% also included Claritas, 1.97% also included Spotify, 1.21% also included Podcorn, 1.06% also included Swap.fm, 1.00% also included OP3, 0.87% also included ArtsAI, 0.64% also included Blubrry, 0.52% also included Gumshoe, 0.45% also included Veritonic, 0.39% also included Podder, 0.05% also included CoHost Prefix, 0.04% also included Feedpress, 0.04% also included United Podcasters, 0.01% also included Podkite, 0.01% also included AdBarker, and 0.01% also included Zencastr.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "72.71%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "6.11%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.13%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.44%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.82%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.49%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.72%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.43%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.43%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.38%" >}}
---

### 2. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 3.28% of new episodes in October, shrinking 0.42% from last month.

Of these, 26.43% had 2 other trackers, 13.88% had one other tracker, 3.02% had 3 other trackers, 1.46% had 4 other trackers, 1.33% had 5 other trackers, and 0.65% had 6 other trackers.

25.64% also included Podtrac, 20.16% also included Podscribe, 17.34% also included Magellan AI, 13.50% also included Podroll, 3.94% also included Spotify, 3.40% also included Claritas, 2.33% also included Podsights, 1.11% also included Chartable, 1.01% also included Blubrry, 0.88% also included OP3, 0.78% also included Podder, 0.71% also included ArtsAI, 0.63% also included Swap.fm, 0.31% also included Veritonic, 0.29% also included Podcorn, 0.06% also included United Podcasters, 0.04% also included Gumshoe, 0.01% also included CoHost Prefix, and <0.01% also included Feedpress.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "80.32%" >}}
2. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "3.95%" >}}
3. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "3.73%" >}}
4. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "2.05%" >}}
5. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.53%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.23%" >}}
7. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.22%" >}}
8. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "1.19%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.70%" >}}
10. {{< a "https://www.julephosting.de/" "Julep Hosting" >}} {{< span "weak" "0.64%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 2.18% of new episodes in October, shrinking 6.08% from last month.

Of these, 57.26% also included Podtrac, 40.87% also included Podscribe, 23.25% also included Magellan AI, 17.92% also included Claritas, 11.10% also included Adswizz, 9.74% also included Swap.fm, 7.57% also included ArtsAI, 4.41% also included Podcorn, 4.15% also included Gumshoe, 4.03% also included OP3, 3.63% also included Podroll, 3.59% also included Veritonic, 1.92% also included Podder, 0.41% also included CoHost Prefix, 0.39% also included Blubrry, 0.26% also included United Podcasters, 0.12% also included Feedpress, 0.06% also included Podkite, 0.02% also included Zencastr, 0.01% also included AdBarker, and <0.01% also included Firstory.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "56.23%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "11.74%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.70%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.12%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.03%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.27%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.53%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.21%" >}}
9. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.10%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.06%" >}}
---

### 3. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 2.02% of new episodes in October, growing 1.77% from last month.

Of these, 30.11% had 2 other trackers, 18.70% had one other tracker, 13.38% had 3 other trackers, 12.72% had 4 other trackers, 9.23% had 5 other trackers, 4.11% had 6 other trackers, 1.11% had 7 other trackers, and 0.03% had 9 other trackers.

48.81% also included Magellan AI, 41.90% also included Podtrac, 32.78% also included Adswizz, 29.15% also included Podsights, 25.14% also included Claritas, 17.09% also included Spotify, 11.87% also included Chartable, 9.13% also included ArtsAI, 8.28% also included Swap.fm, 4.77% also included Podroll, 4.34% also included Podcorn, 4.20% also included OP3, 4.04% also included Gumshoe, 3.80% also included Veritonic, 2.53% also included Podder, 0.45% also included CoHost Prefix, 0.27% also included United Podcasters, 0.21% also included Blubrry, 0.02% also included Podkite, 0.01% also included Zencastr, and <0.01% also included AdBarker.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "32.90%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "31.63%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.41%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.72%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.18%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.56%" >}}
7. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "3.40%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.21%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.18%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.13%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.39% of new episodes in October, shrinking 4.87% from last month.

Of these, 26.02% had 2 other trackers, 22.71% had one other tracker, 13.51% had 4 other trackers, 10.77% had 3 other trackers, 9.99% had 5 other trackers, 4.70% had 6 other trackers, 1.61% had 7 other trackers, and 0.04% had 9 other trackers.

65.53% also included Podtrac, 42.15% also included Podscribe, 38.62% also included Chartable, 24.56% also included Magellan AI, 17.21% also included Claritas, 12.91% also included Swap.fm, 7.70% also included ArtsAI, 6.60% also included Spotify, 6.08% also included Podcorn, 5.69% also included Gumshoe, 5.48% also included Adswizz, 5.46% also included OP3, 5.24% also included Veritonic, 4.00% also included Podroll, 2.40% also included Podder, 0.45% also included Blubrry, 0.35% also included CoHost Prefix, 0.23% also included United Podcasters, 0.18% also included Feedpress, 0.05% also included Podkite, and 0.01% also included Zencastr.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "65.68%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "12.82%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "5.64%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.83%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.65%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.71%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.55%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.24%" >}}
9. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.17%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.81%" >}}
---

### 5. [Magellan AI](https://www.magellan.ai/prefix)

Magellan AI was found on 1.33% of new episodes in October, growing 6.23% from last month.

Of these, 31.60% had 2 other trackers, 14.07% had 3 other trackers, 13.09% had 4 other trackers, 13.04% had one other tracker, 10.61% had 5 other trackers, 4.45% had 6 other trackers, and 1.54% had 7 other trackers.

73.95% also included Podscribe, 42.72% also included Adswizz, 28.94% also included Podtrac, 27.50% also included Claritas, 25.73% also included Podsights, 13.60% also included Chartable, 13.31% also included Spotify, 10.65% also included Swap.fm, 8.57% also included ArtsAI, 5.77% also included Podroll, 5.06% also included Veritonic, 1.88% also included Podder, 1.44% also included OP3, 1.15% also included Gumshoe, 0.35% also included United Podcasters, 0.31% also included Podcorn, 0.27% also included CoHost Prefix, and 0.13% also included Blubrry.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "40.77%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "27.16%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.88%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.83%" >}}
5. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "4.65%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.43%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.18%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.71%" >}}
9. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.16%" >}}
10. {{< a "https://www.americanpublicmedia.org/" "American Public Media" >}} {{< span "weak" "0.72%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.16% of new episodes in October, shrinking 1.25% from last month.

Of these, 12.77% had one other tracker, 0.96% had 2 other trackers, 0.26% had 3 other trackers, 0.04% had 4 other trackers, and 0.03% had 5 other trackers.

8.56% also included Podtrac, 2.85% also included Adswizz, 1.81% also included Feedpress, 0.59% also included OP3, 0.54% also included Podsights, 0.36% also included Podscribe, 0.33% also included Podcorn, 0.22% also included Podder, 0.15% also included Magellan AI, 0.13% also included Chartable, 0.12% also included Spotify, 0.09% also included Swap.fm, 0.05% also included Podkite, and 0.02% also included ArtsAI.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "49.95%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "4.42%" >}}
3. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "3.46%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.81%" >}}
5. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.73%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.23%" >}}
7. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.03%" >}}
8. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "1.00%" >}}
9. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "0.90%" >}}
10. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "0.78%" >}}
---

### 7. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 1.00% of new episodes in October, shrinking 13.33% from last month.

Of these, 36.56% had 2 other trackers, 19.71% had one other tracker, 8.82% had 3 other trackers, 8.22% had 4 other trackers, 4.73% had 5 other trackers, 2.76% had 6 other trackers, and 0.42% had 7 other trackers.

55.47% also included Podtrac, 53.70% also included Podsights, 23.86% also included Podscribe, 18.04% also included Magellan AI, 11.95% also included Swap.fm, 11.12% also included Spotify, 5.84% also included Claritas, 3.63% also included Adswizz, 3.26% also included Podroll, 1.83% also included Podder, 1.34% also included Veritonic, 1.33% also included ArtsAI, 1.23% also included Gumshoe, 0.80% also included Podcorn, 0.64% also included OP3, 0.44% also included CoHost Prefix, 0.31% also included United Podcasters, 0.26% also included Feedpress, 0.15% also included Blubrry, 0.03% also included Zencastr, 0.03% also included Podkite, 0.02% also included AdBarker, and 0.01% also included Firstory.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "83.58%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.41%" >}}
3. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.31%" >}}
4. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "0.64%" >}}
5. {{< a "https://cloud.google.com/" "Google Cloud" >}} {{< span "weak" "0.55%" >}}
6. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.52%" >}}
7. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "0.28%" >}}
8. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.26%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.23%" >}}
10. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.21%" >}}
---

### 8. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.65% of new episodes in October, growing 0.44% from last month.

Of these, 15.12% had one other tracker, 5.24% had 5 other trackers, 3.81% had 2 other trackers, 3.20% had 6 other trackers, 2.90% had 4 other trackers, 2.89% had 3 other trackers, 0.14% had 7 other trackers, and 0.09% had 9 other trackers.

28.91% also included Podtrac, 13.55% also included Podscribe, 13.11% also included Podsights, 12.11% also included OP3, 9.62% also included Gumshoe, 4.31% also included Spotify, 2.60% also included Podroll, 1.45% also included Adswizz, 1.44% also included Podder, 1.25% also included Chartable, 0.63% also included Magellan AI, 0.58% also included Blubrry, 0.27% also included Swap.fm, 0.16% also included Feedpress, 0.10% also included Podkite, 0.09% also included CoHost Prefix, 0.05% also included Zencastr, 0.04% also included United Podcasters, and 0.01% also included AdBarker.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "26.31%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "14.10%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "9.79%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.15%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.76%" >}}
6. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "7.66%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "6.48%" >}}
8. {{< a "https://www.wideorbit.com/" "WideOrbit" >}} {{< span "weak" "5.67%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.12%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.57%" >}}
---

### 9. [Podroll](https://podroll.fm/)

Podroll was found on 0.57% of new episodes in October, growing 3.80% from last month.

Of these, 71.56% had 2 other trackers, 8.87% had 3 other trackers, 6.17% had one other tracker, 4.30% had 4 other trackers, 4.13% had 6 other trackers, 1.15% had 5 other trackers, 0.52% had 7 other trackers, and 0.10% had 9 other trackers.

81.97% also included Podtrac, 77.32% also included Adswizz, 16.80% also included Podscribe, 13.41% also included Magellan AI, 9.75% also included Podsights, 6.70% also included Swap.fm, 5.72% also included Chartable, 4.86% also included Claritas, 3.24% also included Spotify, 2.93% also included Podcorn, 1.47% also included OP3, 1.19% also included ArtsAI, 0.80% also included United Podcasters, 0.79% also included Gumshoe, 0.45% also included Podder, 0.43% also included Veritonic, and 0.40% also included CoHost Prefix.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "77.34%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.98%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.85%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.21%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "1.63%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.12%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.61%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.57%" >}}
9. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "0.33%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.10%" >}}
---

### 10. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.52% of new episodes in October, shrinking 9.93% from last month.

Of these, 28.34% had 4 other trackers, 22.29% had 5 other trackers, 21.47% had 3 other trackers, 11.01% had 6 other trackers, 10.53% had 2 other trackers, 3.76% had 7 other trackers, and 2.19% had one other tracker.

97.59% also included Podscribe, 70.47% also included Magellan AI, 61.76% also included Podtrac, 46.21% also included Podsights, 38.44% also included Spotify, 27.74% also included ArtsAI, 21.49% also included Adswizz, 12.84% also included Veritonic, 11.28% also included Chartable, 5.74% also included Swap.fm, 5.36% also included Podroll, 1.77% also included OP3, 1.48% also included Podder, 1.46% also included Gumshoe, 0.79% also included CoHost Prefix, and 0.38% also included United Podcasters.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.09%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "21.59%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "15.85%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "11.02%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.03%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.22%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.76%" >}}
8. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.38%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.36%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.25%" >}}
---

### 11. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.50% of new episodes in October, shrinking 4.83% from last month.

Of these, 35.02% had 2 other trackers, 15.75% had 4 other trackers, 11.74% had 5 other trackers, 11.08% had 6 other trackers, 8.80% had 3 other trackers, 5.82% had one other tracker, 3.62% had 7 other trackers, and 0.12% had 9 other trackers.

68.35% also included Podscribe, 60.25% also included Podtrac, 39.60% also included Claritas, 35.14% also included Magellan AI, 25.64% also included Adswizz, 22.12% also included Chartable, 18.27% also included Podsights, 16.22% also included ArtsAI, 6.61% also included OP3, 5.81% also included Gumshoe, 5.53% also included Podcorn, 4.56% also included Veritonic, 3.68% also included Podroll, 2.36% also included Swap.fm, 1.30% also included Podder, 0.80% also included CoHost Prefix, 0.28% also included Blubrry, 0.24% also included United Podcasters, and 0.07% also included Podkite.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "32.04%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "24.77%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "13.60%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.52%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "6.94%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.67%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.53%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.53%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.11%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.73%" >}}
---

### 12. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.39% of new episodes in October, growing 6.57% from last month.

Of these, 19.51% had one other tracker, 10.02% had 5 other trackers, 6.54% had 2 other trackers, 5.88% had 6 other trackers, 4.46% had 3 other trackers, 4.37% had 4 other trackers, 0.19% had 7 other trackers, and 0.15% had 9 other trackers.

39.28% also included Podtrac, 21.71% also included Podscribe, 20.08% also included Podcorn, 19.51% also included Podsights, 17.47% also included Gumshoe, 8.54% also included Spotify, 7.42% also included Adswizz, 4.91% also included Magellan AI, 2.36% also included Claritas, 2.15% also included Podroll, 1.76% also included Blubrry, 1.64% also included Chartable, 1.46% also included Swap.fm, 1.36% also included Podder, 0.64% also included ArtsAI, 0.58% also included CoHost Prefix, 0.41% also included Podkite, 0.08% also included United Podcasters, 0.08% also included Feedpress, and 0.03% also included Zencastr.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "29.44%" >}}
2. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "11.59%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.49%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.56%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.73%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.00%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.85%" >}}
8. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "2.12%" >}}
9. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "2.08%" >}}
10. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "1.95%" >}}
---

### 13. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.35% of new episodes in October, growing 7.20% from last month.

Of these, 22.27% had one other tracker, 21.44% had 2 other trackers, 17.35% had 3 other trackers, 14.02% had 4 other trackers, 13.39% had 5 other trackers, 2.73% had 6 other trackers, and 0.81% had 7 other trackers.

51.30% also included Podsights, 47.55% also included Podscribe, 46.72% also included Podtrac, 40.37% also included Magellan AI, 34.14% also included Chartable, 10.93% also included Podroll, 8.50% also included Claritas, 6.88% also included ArtsAI, 5.90% also included Adswizz, 3.39% also included Spotify, 1.62% also included OP3, 1.38% also included United Podcasters, 1.38% also included Gumshoe, 0.94% also included Veritonic, 0.49% also included Podcorn, 0.47% also included Podder, 0.30% also included Blubrry, and 0.06% also included Zencastr.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "67.71%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.91%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.63%" >}}
4. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "5.31%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.20%" >}}
6. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "0.66%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.23%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.17%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.17%" >}}
---

### 14. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.21% of new episodes in October, shrinking 0.35% from last month.

Of these, 30.09% had 4 other trackers, 19.31% had 5 other trackers, 16.30% had 3 other trackers, 11.71% had 6 other trackers, 10.11% had 2 other trackers, 9.02% had 7 other trackers, and 3.14% had one other tracker.

89.28% also included Podscribe, 69.91% also included Claritas, 65.00% also included Podtrac, 55.34% also included Magellan AI, 52.13% also included Podsights, 39.69% also included Spotify, 15.46% also included Veritonic, 11.71% also included Swap.fm, 11.23% also included Adswizz, 6.48% also included Chartable, 3.30% also included Podroll, 1.22% also included OP3, 0.64% also included Podder, 0.55% also included United Podcasters, 0.38% also included CoHost Prefix, 0.13% also included Gumshoe, and 0.10% also included Blubrry.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.87%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "27.94%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "16.97%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "11.26%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.07%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.14%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.58%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.13%" >}}
9. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.03%" >}}
---

### 15. [Podder](https://www.podderapp.com/)

Podder was found on 0.18% of new episodes in October, shrinking 9.70% from last month.

Of these, 17.61% had one other tracker, 17.54% had 2 other trackers, 9.25% had 4 other trackers, 7.25% had 3 other trackers, 5.44% had 5 other trackers, 0.33% had 9 other trackers, 0.22% had 7 other trackers, and 0.07% had 6 other trackers.

33.93% also included Podtrac, 28.56% also included Podscribe, 18.72% also included Podsights, 14.39% also included Adswizz, 13.98% also included Magellan AI, 10.28% also included Chartable, 5.22% also included Podcorn, 4.29% also included Claritas, 3.66% also included Spotify, 2.96% also included OP3, 2.52% also included Gumshoe, 1.44% also included Podroll, 1.41% also included Blubrry, 0.92% also included Swap.fm, 0.74% also included ArtsAI, 0.33% also included CoHost Prefix, 0.18% also included Podkite, and 0.07% also included United Podcasters.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "37.92%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "17.06%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "14.35%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.91%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.74%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.29%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.11%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.66%" >}}
9. {{< a "https://cloud.google.com/" "Google Cloud" >}} {{< span "weak" "2.52%" >}}
10. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.89%" >}}
---

### 16. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.14% of new episodes in October, shrinking 3.04% from last month.

Of these, 20.96% had one other tracker, and 1.89% had 2 other trackers.

15.39% also included Blubrry, 4.45% also included Podtrac, 1.89% also included Podsights, 1.89% also included Chartable, 0.77% also included Podcorn, 0.24% also included OP3, and 0.10% also included Adswizz.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "60.70%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "11.33%" >}}
3. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "7.02%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "3.78%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.19%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.65%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.55%" >}}
8. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "1.31%" >}}
9. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "1.02%" >}}
10. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "0.97%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.13% of new episodes in October, growing 3.77% from last month.

Of these, 29.14% had 5 other trackers, 15.53% had 6 other trackers, 12.54% had 4 other trackers, 10.88% had one other tracker, 7.84% had 2 other trackers, 6.98% had 3 other trackers, 1.42% had 7 other trackers, and 0.46% had 9 other trackers.

62.27% also included Podscribe, 61.76% also included Podtrac, 60.75% also included Podsights, 52.15% also included OP3, 47.60% also included Podcorn, 22.41% also included Spotify, 11.73% also included Magellan AI, 9.46% also included Chartable, 5.82% also included Claritas, 3.69% also included Swap.fm, 3.44% also included Podroll, 3.44% also included Podder, 2.48% also included CoHost Prefix, 1.67% also included Veritonic, 1.01% also included Adswizz, 0.66% also included United Podcasters, and 0.20% also included ArtsAI.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "52.50%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "20.33%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "19.52%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.73%" >}}
5. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.92%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.16%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.96%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.35%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.25%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.15%" >}}
---

### 18. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.08% of new episodes in October, growing 5.14% from last month.

Of these, 38.68% had 5 other trackers, 25.30% had 7 other trackers, 16.28% had 6 other trackers, 11.68% had 4 other trackers, 7.33% had 3 other trackers, 0.08% had one other tracker, and 0.08% had 2 other trackers.

93.39% also included Podscribe, 89.12% also included Podsights, 84.93% also included Podtrac, 82.11% also included Magellan AI, 81.31% also included Claritas, 38.84% also included ArtsAI, 28.04% also included Spotify, 16.44% also included Chartable, 12.41% also included Adswizz, 4.03% also included Swap.fm, 2.98% also included Podroll, 2.66% also included Gumshoe, 0.56% also included CoHost Prefix, and 0.32% also included United Podcasters.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "76.95%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.41%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.12%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.77%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.37%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.48%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.40%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.32%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.08%" >}}
---

### 19. [Firstory](https://firstory.me/)

Firstory was found on 0.03% of new episodes in October, shrinking 13.21% from last month.

Of these, 0.22% had one other tracker.

0.22% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.78%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.22%" >}}
---

### 20. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.02% of new episodes in October, growing 3.66% from last month.

Of these, 29.72% had 4 other trackers, 14.46% had one other tracker, 14.46% had 2 other trackers, 12.05% had 5 other trackers, 3.61% had 9 other trackers, 2.81% had 6 other trackers, 2.81% had 7 other trackers, and 1.20% had 3 other trackers.

55.02% also included Podscribe, 48.59% also included Podtrac, 29.72% also included Podsights, 26.51% also included Chartable, 24.90% also included Claritas, 24.50% also included Spotify, 21.69% also included Magellan AI, 19.68% also included Gumshoe, 14.06% also included Podroll, 13.65% also included OP3, 4.82% also included ArtsAI, 3.61% also included Podcorn, 3.61% also included Podder, 2.81% also included Veritonic, and 2.01% also included Adswizz.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "31.73%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "20.88%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.65%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.23%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "7.23%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.02%" >}}
7. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "5.22%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.41%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.01%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.20%" >}}
---

### 21. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in October, shrinking 4.28% from last month.

Of these, 24.77% had one other tracker, 22.97% had 3 other trackers, 17.12% had 2 other trackers, 13.06% had 6 other trackers, 5.86% had 4 other trackers, 4.50% had 5 other trackers, and 2.25% had 7 other trackers.

36.94% also included Podtrac, 36.49% also included Podscribe, 32.88% also included Swap.fm, 31.98% also included Magellan AI, 31.08% also included Podroll, 22.07% also included Podsights, 21.17% also included Chartable, 13.51% also included Claritas, 13.06% also included Adswizz, 8.11% also included Spotify, 7.66% also included ArtsAI, 5.86% also included Gumshoe, 2.25% also included OP3, 1.80% also included Podcorn, 1.80% also included Veritonic, 0.90% also included Podder, and 0.45% also included Zencastr.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "43.69%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "15.32%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "13.06%" >}}
4. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "10.36%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "4.50%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "3.60%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.15%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.70%" >}}
9. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "2.25%" >}}
10. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "0.90%" >}}
---

### 22. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in October, shrinking 12.25% from last month.

Of these, 32.89% had one other tracker, 3.36% had 2 other trackers, 3.36% had 4 other trackers, and 3.36% had 5 other trackers.

21.48% also included Podtrac, 16.11% also included OP3, 6.71% also included Podcorn, 6.71% also included Podsights, 6.04% also included Blubrry, 3.36% also included Podscribe, 3.36% also included Spotify, 3.36% also included Podder, and 2.68% also included Chartable.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "32.89%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "16.11%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "14.09%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "13.42%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.72%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "6.04%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.36%" >}}
8. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "2.68%" >}}
9. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "1.34%" >}}
10. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "1.34%" >}}
---

### 23. [Zencastr](https://zencastr.com/)

Zencastr was found on <0.01% of new episodes in October, shrinking 12.68% from last month.

Of these, 18.18% had one other tracker, 3.03% had 2 other trackers, 1.52% had 5 other trackers, 1.52% had 6 other trackers, and 1.52% had 7 other trackers.

18.18% also included Podtrac, 7.58% also included Podcorn, 7.58% also included Chartable, 4.55% also included Podscribe, 4.55% also included Swap.fm, 4.55% also included Podsights, 3.03% also included OP3, and 1.52% also included United Podcasters.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "30.30%" >}}
2. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "21.21%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.12%" >}}
4. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "10.61%" >}}
5. {{< a "https://www.digitalocean.com/products/spaces/" "DigitalOcean Spaces" >}} {{< span "weak" "7.58%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.06%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "6.06%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "6.06%" >}}
---

### 24. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in October, shrinking 5.18% from last month.

Of these, 29.63% had one other tracker, and 1.85% had 3 other trackers.

25.93% also included Podtrac, 5.56% also included Chartable, 1.85% also included Podscribe, and 1.85% also included Podcorn.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "35.19%" >}}
2. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "27.78%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "14.81%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.41%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.56%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.56%" >}}
7. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "3.70%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
*Updated 2025-11-01, with data for the month of October 2025.*

*Updated 2025-10-01, with data for the month of September 2025.*

*Updated 2025-09-01, with data for the month of August 2025.*

*Updated 2025-08-02, with data for the month of July 2025.*

*Updated 2025-07-01, with data for the month of June 2025.*

*Updated 2025-06-01, with data for the month of May 2025.*

*Updated 2025-05-01, with data for the month of April 2025.*

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
 - [Podcast Tracker Rankings by Episode Share (September 2025)](/archive/podcast-trackers-by-episode-share-september-2025/)
 - [Podcast Tracker Rankings by Episode Share (August 2025)](/archive/podcast-trackers-by-episode-share-august-2025/)
 - [Podcast Tracker Rankings by Episode Share (July 2025)](/archive/podcast-trackers-by-episode-share-july-2025/)
 - [Podcast Tracker Rankings by Episode Share (June 2025)](/archive/podcast-trackers-by-episode-share-june-2025/)
 - [Podcast Tracker Rankings by Episode Share (May 2025)](/archive/podcast-trackers-by-episode-share-may-2025/)
 - [Podcast Tracker Rankings by Episode Share (April 2025)](/archive/podcast-trackers-by-episode-share-april-2025/)
 - [Podcast Tracker Rankings by Episode Share (March 2025)](/archive/podcast-trackers-by-episode-share-march-2025/)
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/podcast-trackers-by-episode-share.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
