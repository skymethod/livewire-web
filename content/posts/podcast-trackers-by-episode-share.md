---
title: "Top Podcast Tracking Services by Episode Share (September 2025)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2025-09.png
date: 2025-10-01T18:43:00-04:00
lastmod: 2025-10-01T18:43:00-04:00
draft: false
rssrevision: 2025-09
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.5 million in September 2025), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in September, how many
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
Month	Podtrac	Adswizz	Podscribe	Podsights	Blubrry	Chartable	Podcorn	Claritas	Podroll	Spotify	OP3	Swap.fm	ArtsAI	Podder	Feedpress	Gumshoe	Veritonic	CoHost Prefix	United Podcasters	Podkite	Médiamétrie	Audiotakes	RSS Insight	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
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
Sep 2022	7.53	2.26	0.02	1.74	1.49	5.40	2.45	0.01					0.09		0.21					0.01	0.52						0.02	0.02		
Oct 2022	8.24	2.35	0.07	1.81	1.61	5.48	2.51	0.02			0.03		0.10		0.18					0.01	0.50			0.01			0.02	0.04		
Nov 2022	8.11	2.37	0.15	2.03	1.62	5.62	2.43	0.03			0.04		0.10	0.01	0.18					0.01	0.50			0.01			0.02	0.05		
Dec 2022	8.01	2.32	0.03	1.81	1.61	5.54	2.05	0.02			0.05		0.05	0.04	0.18					0.01	0.49			0.01		0.01	0.02	0.05		
Jan 2023	7.85	2.35	0.20	1.88	1.61	5.56	2.15	0.06			0.07		0.10	0.11	0.18					0.01	0.54			0.01		0.01	0.02	0.06		
Feb 2023	7.58	2.29	0.21	1.92	1.62	5.51	2.30	0.07			0.07		0.10	0.11	0.19					0.01	0.49			0.01		0.01	0.02	0.06	0.03	
Mar 2023	7.79	2.25	0.21	2.03	1.53	5.53	2.22	0.07	0.04		0.08		0.11	0.11	0.18		0.04			0.01	0.45			0.01		0.01	0.02	0.06		
Apr 2023	7.66	2.26	0.21	2.00	1.67	5.43	2.20	0.07	0.06		0.09		0.11	0.15	0.17	0.08	0.05			0.01	0.45			0.01		0.01	0.01			
May 2023	7.58	2.27	0.24	2.04	1.67	5.59	2.28	0.08	0.09		0.09		0.11	0.15	0.19	0.07	0.05			0.01	0.45			0.01	0.01	0.01	0.01			
Jun 2023	8.22	2.39	0.26	2.23	1.64	5.83	1.86	0.07	0.10		0.09		0.12	0.15	0.19	0.08	0.05			0.01	0.51			0.01	0.01	0.01	0.01			
Jul 2023	8.60	2.38	0.27	2.52	1.53	5.95	1.17	0.07	0.14	0.01	0.08		0.11	0.14	0.18	0.06	0.06			0.01	0.55			0.01	0.01	0.01	0.01			
Aug 2023	9.19	2.72	0.36	2.76	1.58	6.43	1.23	0.08	0.16	0.03	0.11		0.12	0.15	0.17	0.07	0.07			0.01	0.53	0.04		0.01	0.02	0.01				
Sep 2023	8.46	2.49	0.37	2.47	1.39	5.77	1.10	0.10	0.13	0.05	0.10		0.12	0.15	0.16	0.07	0.06			0.01	0.58	0.05		0.01	0.02	0.01				
Oct 2023	7.90	2.29	0.39	2.28	1.37	5.54	1.11	0.10	0.12	0.08	0.10		0.12	0.16	0.16	0.08	0.06			0.01	0.50	0.05		0.02	0.03	0.01				
Nov 2023	7.65	2.25	0.47	2.33	1.45	5.59	1.14	0.11	0.12	0.11	0.13		0.12	0.16	0.17	0.10	0.06			0.01	0.33	0.06		0.01	0.03					
Dec 2023	7.48	2.20	0.54	2.19	1.53	5.60	1.12	0.11	0.12	0.12	0.11		0.12	0.16	0.16	0.09	0.06			0.01	0.33	0.06		0.01	0.03					
Jan 2024	7.64	2.37	0.65	2.21	1.55	5.61	1.17	0.12	0.11	0.15	0.13		0.14	0.16	0.17	0.10	0.06		0.01	0.01	0.25	0.08		0.01	0.01					
Feb 2024	7.69	2.38	0.69	2.22	1.52	5.58	1.21	0.13	0.12	0.22	0.16		0.13	0.17	0.17	0.11	0.06		0.01	0.01	0.22	0.09		0.01						
Mar 2024	9.01	2.53	0.69	2.19	1.54	5.46	1.14	0.14	0.12	0.25	0.14		0.12	0.16	0.16	0.10	0.06		0.01	0.01	0.22	0.09		0.01						
Apr 2024	10.78	2.53	0.73	2.16	1.51	5.47	1.24	0.15	0.34	0.27	0.18		0.13	0.17	0.15	0.11	0.07	0.01	0.01	0.01	0.19	0.07		0.01						
May 2024	11.59	2.75	0.83	2.24	1.50	5.63	1.20	0.15	0.36	0.30	0.18		0.14	0.16	0.15	0.11	0.07	0.01	0.01	0.01	0.09	0.06		0.01						
Jun 2024	11.54	2.88	0.91	2.34	1.52	6.06	0.71	0.16	0.37	0.32	0.20	0.03	0.16	0.15	0.15	0.11	0.07	0.01	0.01	0.01	0.10	0.07		0.01						
Jul 2024	12.34	2.83	1.01	2.45	1.65	6.80	0.71	0.18	0.43	0.34	0.20	0.06	0.17	0.15	0.15	0.12	0.07	0.01	0.01	0.01	0.09	0.09		0.01						
Aug 2024	14.22	2.96	1.11	2.48	1.70	6.72	0.81	0.18	0.45	0.35	0.19	0.12	0.18	0.35	0.14	0.12	0.08	0.01	0.01	0.01	0.08	0.11		0.01						
Sep 2024	12.95	3.13	1.18	2.26	1.44	5.99	0.72	0.18	0.44	0.35	0.24	0.12	0.18	0.42	0.15	0.13	0.08	0.01	0.01	0.01	0.07	0.13		0.01						
Oct 2024	12.24	3.23	1.23	2.35	1.53	5.49	0.66	0.19	0.43	0.40	0.27	0.17	0.18	0.39	0.14	0.12	0.09	0.01	0.01	0.01	0.09	0.14		0.01						
Nov 2024	11.86	3.21	1.27	2.31	1.52	4.66	0.63	0.21	0.43	0.44	0.29	0.19	0.17	0.41	0.11	0.12	0.08	0.01	0.01	0.01	0.10	0.14		0.01						
Dec 2024	12.56	3.06	1.29	2.13	1.40	2.29	0.62	0.21	0.43	0.45	0.29	0.24	0.18	0.54	0.09	0.12	0.08	0.01	0.01	0.01	0.09	0.15		0.01						
Jan 2025	12.62	2.92	1.31	1.73	1.36	1.54	0.66	0.21	0.46	0.41	0.34	0.27	0.19	0.54	0.12	0.13	0.08	0.01	0.01	0.01	0.04	0.16		0.01						
Feb 2025	12.47	2.74	1.25	1.70	1.45	1.43	0.66	0.22	0.46	0.36	0.33	0.28	0.18	0.48	0.14	0.12	0.08	0.01	0.01	0.01	0.01	0.16		0.01						
Mar 2025	12.18	2.87	1.28	1.51	1.25	1.18	0.67	0.21	0.47	0.33	0.33	0.27	0.18	0.36	0.14	0.13	0.07	0.01	0.01	0.01	0.01	0.25	0.04	0.01						
Apr 2025	12.35	2.97	1.53	1.64	1.26	1.28	0.68	0.23	0.48	0.44	0.34	0.30	0.19	0.33	0.13	0.12	0.08	0.01	0.01	0.01	0.02	0.41	0.03	0.01						
May 2025	12.48	2.97	1.61	1.74	1.40	1.31	0.64	0.24	0.46	0.46	0.39	0.33	0.20	0.22	0.13	0.12	0.07	0.01	0.02	0.01	0.02	0.40	0.05							
Jun 2025	12.99	2.73	1.65	1.70	1.34	1.30	0.65	0.26	0.46	0.47	0.39	0.35	0.21	0.20	0.13	0.12	0.07	0.01	0.02	0.01	0.02	0.40	0.04							
Jul 2025	13.83	2.87	1.76	1.71	1.16	1.30	0.66	0.72	0.48	0.50	0.33	0.39	0.23	0.20	0.13	0.12	0.07	0.01	0.02	0.01	0.01									
Aug 2025	14.30	3.24	1.95	1.83	1.35	1.32	0.67	0.79	0.49	0.54	0.35	0.37	0.20	0.21	0.14	0.14	0.08	0.02	0.02	0.01	0.01									
Sep 2025	14.56	3.37	1.98	1.46	1.17	1.16	0.64	0.58	0.55	0.53	0.37	0.33	0.21	0.20	0.14	0.13	0.08	0.02	0.02	0.01	0.01									
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} have historically been the top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podscribe	Podsights	Blubrry	Podcorn	Claritas	Podroll	Spotify	OP3	Swap.fm	ArtsAI	Podder	Feedpress	Gumshoe	Veritonic	CoHost Prefix	United Podcasters	Podkite	Médiamétrie	Audiotakes	RSS Insight	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
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
Sep 2022	2.26	0.02	1.74	1.49	2.45	0.01					0.09		0.21					0.01	0.52						0.02	0.02		
Oct 2022	2.35	0.07	1.81	1.61	2.51	0.02			0.03		0.10		0.18					0.01	0.50			0.01			0.02	0.04		
Nov 2022	2.37	0.15	2.03	1.62	2.43	0.03			0.04		0.10	0.01	0.18					0.01	0.50			0.01			0.02	0.05		
Dec 2022	2.32	0.03	1.81	1.61	2.05	0.02			0.05		0.05	0.04	0.18					0.01	0.49			0.01		0.01	0.02	0.05		
Jan 2023	2.35	0.20	1.88	1.61	2.15	0.06			0.07		0.10	0.11	0.18					0.01	0.54			0.01		0.01	0.02	0.06		
Feb 2023	2.29	0.21	1.92	1.62	2.30	0.07			0.07		0.10	0.11	0.19					0.01	0.49			0.01		0.01	0.02	0.06	0.03	
Mar 2023	2.25	0.21	2.03	1.53	2.22	0.07	0.04		0.08		0.11	0.11	0.18		0.04			0.01	0.45			0.01		0.01	0.02	0.06		
Apr 2023	2.26	0.21	2.00	1.67	2.20	0.07	0.06		0.09		0.11	0.15	0.17	0.08	0.05			0.01	0.45			0.01		0.01	0.01			
May 2023	2.27	0.24	2.04	1.67	2.28	0.08	0.09		0.09		0.11	0.15	0.19	0.07	0.05			0.01	0.45			0.01	0.01	0.01	0.01			
Jun 2023	2.39	0.26	2.23	1.64	1.86	0.07	0.10		0.09		0.12	0.15	0.19	0.08	0.05			0.01	0.51			0.01	0.01	0.01	0.01			
Jul 2023	2.38	0.27	2.52	1.53	1.17	0.07	0.14	0.01	0.08		0.11	0.14	0.18	0.06	0.06			0.01	0.55			0.01	0.01	0.01	0.01			
Aug 2023	2.72	0.36	2.76	1.58	1.23	0.08	0.16	0.03	0.11		0.12	0.15	0.17	0.07	0.07			0.01	0.53	0.04		0.01	0.02	0.01				
Sep 2023	2.49	0.37	2.47	1.39	1.10	0.10	0.13	0.05	0.10		0.12	0.15	0.16	0.07	0.06			0.01	0.58	0.05		0.01	0.02	0.01				
Oct 2023	2.29	0.39	2.28	1.37	1.11	0.10	0.12	0.08	0.10		0.12	0.16	0.16	0.08	0.06			0.01	0.50	0.05		0.02	0.03	0.01				
Nov 2023	2.25	0.47	2.33	1.45	1.14	0.11	0.12	0.11	0.13		0.12	0.16	0.17	0.10	0.06			0.01	0.33	0.06		0.01	0.03					
Dec 2023	2.20	0.54	2.19	1.53	1.12	0.11	0.12	0.12	0.11		0.12	0.16	0.16	0.09	0.06			0.01	0.33	0.06		0.01	0.03					
Jan 2024	2.37	0.65	2.21	1.55	1.17	0.12	0.11	0.15	0.13		0.14	0.16	0.17	0.10	0.06		0.01	0.01	0.25	0.08		0.01	0.01					
Feb 2024	2.38	0.69	2.22	1.52	1.21	0.13	0.12	0.22	0.16		0.13	0.17	0.17	0.11	0.06		0.01	0.01	0.22	0.09		0.01						
Mar 2024	2.53	0.69	2.19	1.54	1.14	0.14	0.12	0.25	0.14		0.12	0.16	0.16	0.10	0.06		0.01	0.01	0.22	0.09		0.01						
Apr 2024	2.53	0.73	2.16	1.51	1.24	0.15	0.34	0.27	0.18		0.13	0.17	0.15	0.11	0.07	0.01	0.01	0.01	0.19	0.07		0.01						
May 2024	2.75	0.83	2.24	1.50	1.20	0.15	0.36	0.30	0.18		0.14	0.16	0.15	0.11	0.07	0.01	0.01	0.01	0.09	0.06		0.01						
Jun 2024	2.88	0.91	2.34	1.52	0.71	0.16	0.37	0.32	0.20	0.03	0.16	0.15	0.15	0.11	0.07	0.01	0.01	0.01	0.10	0.07		0.01						
Jul 2024	2.83	1.01	2.45	1.65	0.71	0.18	0.43	0.34	0.20	0.06	0.17	0.15	0.15	0.12	0.07	0.01	0.01	0.01	0.09	0.09		0.01						
Aug 2024	2.96	1.11	2.48	1.70	0.81	0.18	0.45	0.35	0.19	0.12	0.18	0.35	0.14	0.12	0.08	0.01	0.01	0.01	0.08	0.11		0.01						
Sep 2024	3.13	1.18	2.26	1.44	0.72	0.18	0.44	0.35	0.24	0.12	0.18	0.42	0.15	0.13	0.08	0.01	0.01	0.01	0.07	0.13		0.01						
Oct 2024	3.23	1.23	2.35	1.53	0.66	0.19	0.43	0.40	0.27	0.17	0.18	0.39	0.14	0.12	0.09	0.01	0.01	0.01	0.09	0.14		0.01						
Nov 2024	3.21	1.27	2.31	1.52	0.63	0.21	0.43	0.44	0.29	0.19	0.17	0.41	0.11	0.12	0.08	0.01	0.01	0.01	0.10	0.14		0.01						
Dec 2024	3.06	1.29	2.13	1.40	0.62	0.21	0.43	0.45	0.29	0.24	0.18	0.54	0.09	0.12	0.08	0.01	0.01	0.01	0.09	0.15		0.01						
Jan 2025	2.92	1.31	1.73	1.36	0.66	0.21	0.46	0.41	0.34	0.27	0.19	0.54	0.12	0.13	0.08	0.01	0.01	0.01	0.04	0.16		0.01						
Feb 2025	2.74	1.25	1.70	1.45	0.66	0.22	0.46	0.36	0.33	0.28	0.18	0.48	0.14	0.12	0.08	0.01	0.01	0.01	0.01	0.16		0.01						
Mar 2025	2.87	1.28	1.51	1.25	0.67	0.21	0.47	0.33	0.33	0.27	0.18	0.36	0.14	0.13	0.07	0.01	0.01	0.01	0.01	0.25	0.04	0.01						
Apr 2025	2.97	1.53	1.64	1.26	0.68	0.23	0.48	0.44	0.34	0.30	0.19	0.33	0.13	0.12	0.08	0.01	0.01	0.01	0.02	0.41	0.03	0.01						
May 2025	2.97	1.61	1.74	1.40	0.64	0.24	0.46	0.46	0.39	0.33	0.20	0.22	0.13	0.12	0.07	0.01	0.02	0.01	0.02	0.40	0.05							
Jun 2025	2.73	1.65	1.70	1.34	0.65	0.26	0.46	0.47	0.39	0.35	0.21	0.20	0.13	0.12	0.07	0.01	0.02	0.01	0.02	0.40	0.04							
Jul 2025	2.87	1.76	1.71	1.16	0.66	0.72	0.48	0.50	0.33	0.39	0.23	0.20	0.13	0.12	0.07	0.01	0.02	0.01	0.01									
Aug 2025	3.24	1.95	1.83	1.35	0.67	0.79	0.49	0.54	0.35	0.37	0.20	0.21	0.14	0.14	0.08	0.02	0.02	0.01	0.01									
Sep 2025	3.37	1.98	1.46	1.17	0.64	0.58	0.55	0.53	0.37	0.33	0.21	0.20	0.14	0.13	0.08	0.02	0.02	0.01	0.01									
{{< /graph >}}

---

### Overall

At least one tracker was found on 20.44% of new episodes in September, growing 0.80% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "49.53%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.98%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "8.77%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.36%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.72%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.55%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.20%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.47%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.28%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.28%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of September 2025.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 14.56% of new episodes in September, growing 1.38% from last month.

Of these, 7.95% had one other tracker, 6.74% had 2 other trackers, 1.28% had 3 other trackers, 1.21% had 4 other trackers, 1.02% had 5 other trackers, 0.53% had 6 other trackers, 0.14% had 7 other trackers, <0.01% had 9 other trackers, and <0.01% had 8 other trackers.

6.59% also included Podsights, 5.91% also included Podscribe, 5.78% also included Adswizz, 4.38% also included Chartable, 3.19% also included Podroll, 2.51% also included Magellan AI, 2.28% also included Spotify, 2.09% also included Claritas, 1.28% also included Podcorn, 1.09% also included Swap.fm, 1.00% also included OP3, 0.91% also included ArtsAI, 0.82% also included Blubrry, 0.53% also included Gumshoe, 0.44% also included Podder, 0.44% also included Veritonic, 0.06% also included CoHost Prefix, 0.05% also included Feedpress, 0.04% also included United Podcasters, 0.02% also included Podkite, 0.01% also included Médiamétrie, 0.01% also included AdBarker, and 0.01% also included Zencastr.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "69.37%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "7.14%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.32%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.12%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.06%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.84%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.66%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.50%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.48%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.45%" >}}
---

### 2. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 3.37% of new episodes in September, growing 3.74% from last month.

Of these, 22.69% had 2 other trackers, 12.72% had one other tracker, 4.58% had 3 other trackers, 1.60% had 4 other trackers, 1.21% had 5 other trackers, and 0.60% had 6 other trackers.

25.00% also included Podtrac, 18.08% also included Podscribe, 14.94% also included Magellan AI, 12.83% also included Podroll, 5.36% also included Claritas, 3.32% also included Spotify, 2.35% also included Podsights, 1.23% also included Blubrry, 1.09% also included Chartable, 0.93% also included Podder, 0.78% also included ArtsAI, 0.73% also included OP3, 0.58% also included Swap.fm, 0.27% also included Podcorn, 0.27% also included Veritonic, 0.05% also included United Podcasters, 0.05% also included Gumshoe, and <0.01% also included CoHost Prefix.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "75.59%" >}}
2. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "5.36%" >}}
3. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "4.25%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "2.59%" >}}
5. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "2.26%" >}}
6. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "2.16%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.47%" >}}
8. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.25%" >}}
9. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "1.07%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.68%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 2.32% of new episodes in September, shrinking 13.59% from last month.

Of these, 57.75% also included Podtrac, 37.07% also included Podscribe, 20.66% also included Magellan AI, 16.31% also included Claritas, 9.80% also included Adswizz, 9.10% also included Swap.fm, 7.02% also included ArtsAI, 3.97% also included Podcorn, 3.83% also included Gumshoe, 3.81% also included OP3, 3.32% also included Podroll, 3.21% also included Veritonic, 1.88% also included Podder, 0.45% also included Blubrry, 0.38% also included CoHost Prefix, 0.31% also included United Podcasters, 0.13% also included Feedpress, 0.07% also included Podkite, 0.02% also included Zencastr, 0.01% also included Firstory, and 0.01% also included AdBarker.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "56.82%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "12.48%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.24%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.84%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.76%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.24%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.50%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.22%" >}}
9. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.09%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.02%" >}}
---

### 3. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 1.98% of new episodes in September, growing 4.06% from last month.

Of these, 24.90% had 2 other trackers, 20.35% had one other tracker, 16.36% had 3 other trackers, 12.73% had 4 other trackers, 8.97% had 5 other trackers, 4.44% had 6 other trackers, 1.08% had 7 other trackers, 0.03% had 9 other trackers, and 0.01% had 8 other trackers.

46.86% also included Magellan AI, 43.45% also included Podtrac, 30.78% also included Adswizz, 28.77% also included Podsights, 28.55% also included Claritas, 16.77% also included Spotify, 13.41% also included Chartable, 9.32% also included ArtsAI, 7.59% also included Swap.fm, 4.22% also included Podcorn, 4.13% also included Podroll, 4.07% also included OP3, 3.95% also included Gumshoe, 3.67% also included Veritonic, 3.01% also included Podder, 0.42% also included CoHost Prefix, 0.26% also included United Podcasters, 0.26% also included Blubrry, 0.03% also included Podkite, and 0.02% also included Zencastr.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.31%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "29.63%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.53%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.66%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.52%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.68%" >}}
7. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "3.48%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.18%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.21%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.16%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.46% of new episodes in September, shrinking 17.78% from last month.

Of these, 26.09% had one other tracker, 25.65% had 2 other trackers, 12.46% had 4 other trackers, 10.33% had 3 other trackers, 9.13% had 5 other trackers, 4.85% had 6 other trackers, 1.46% had 7 other trackers, 0.04% had 9 other trackers, and 0.01% had 8 other trackers.

65.55% also included Podtrac, 42.09% also included Chartable, 38.89% also included Podscribe, 22.43% also included Magellan AI, 15.74% also included Claritas, 11.76% also included Swap.fm, 7.22% also included ArtsAI, 6.49% also included Spotify, 5.48% also included Podcorn, 5.40% also included Adswizz, 5.27% also included OP3, 5.19% also included Gumshoe, 4.71% also included Veritonic, 3.61% also included Podroll, 2.41% also included Podder, 0.50% also included Blubrry, 0.36% also included CoHost Prefix, 0.34% also included United Podcasters, 0.21% also included Feedpress, 0.07% also included Podkite, and 0.02% also included Zencastr.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "64.33%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "15.34%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "5.23%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.40%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.62%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.73%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.63%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.21%" >}}
9. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.16%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.78%" >}}
---

### 5. [Magellan AI](https://www.magellan.ai/prefix)

Magellan AI was found on 1.25% of new episodes in September, growing 5.37% from last month.

Of these, 25.21% had 2 other trackers, 18.65% had 3 other trackers, 13.91% had 4 other trackers, 11.64% had one other tracker, 10.63% had 5 other trackers, 5.05% had 6 other trackers, and 1.54% had 7 other trackers.

74.11% also included Podscribe, 40.22% also included Adswizz, 34.38% also included Claritas, 29.20% also included Podtrac, 26.25% also included Podsights, 15.15% also included Chartable, 13.18% also included Spotify, 10.23% also included Swap.fm, 9.14% also included ArtsAI, 5.34% also included Podroll, 5.05% also included Veritonic, 2.10% also included Podder, 1.23% also included OP3, 1.16% also included Gumshoe, 0.50% also included United Podcasters, 0.30% also included Podcorn, 0.25% also included CoHost Prefix, and 0.14% also included Blubrry.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "38.20%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "27.13%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "11.66%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.59%" >}}
5. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "5.53%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.52%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.35%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.80%" >}}
9. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.16%" >}}
10. {{< a "https://www.americanpublicmedia.org/" "American Public Media" >}} {{< span "weak" "0.74%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.17% of new episodes in September, shrinking 1.77% from last month.

Of these, 14.83% had one other tracker, 1.06% had 2 other trackers, 0.25% had 3 other trackers, 0.05% had 5 other trackers, and 0.04% had 4 other trackers.

10.22% also included Podtrac, 3.52% also included Adswizz, 1.72% also included Feedpress, 0.62% also included Podsights, 0.52% also included OP3, 0.44% also included Podscribe, 0.27% also included Podcorn, 0.18% also included Chartable, 0.18% also included Podder, 0.15% also included Magellan AI, 0.12% also included Spotify, 0.08% also included Swap.fm, 0.05% also included Podkite, and 0.03% also included ArtsAI.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "47.40%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "4.57%" >}}
3. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "4.08%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.79%" >}}
5. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.75%" >}}
6. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "1.51%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.38%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.26%" >}}
9. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.15%" >}}
10. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "0.90%" >}}
---

### 7. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 1.16% of new episodes in September, shrinking 10.68% from last month.

Of these, 36.65% had 2 other trackers, 20.49% had one other tracker, 8.57% had 3 other trackers, 7.66% had 4 other trackers, 4.72% had 5 other trackers, 2.86% had 6 other trackers, and 0.38% had 7 other trackers.

55.20% also included Podtrac, 53.32% also included Podsights, 22.97% also included Podscribe, 16.41% also included Magellan AI, 12.46% also included Spotify, 12.26% also included Swap.fm, 5.84% also included Claritas, 3.19% also included Podroll, 3.17% also included Adswizz, 2.08% also included Podder, 1.72% also included Veritonic, 1.24% also included ArtsAI, 1.01% also included Gumshoe, 0.70% also included OP3, 0.68% also included Podcorn, 0.40% also included CoHost Prefix, 0.34% also included United Podcasters, 0.27% also included Feedpress, 0.18% also included Blubrry, 0.05% also included Zencastr, 0.03% also included Firstory, 0.03% also included Podkite, and 0.01% also included AdBarker.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "84.98%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.63%" >}}
3. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.05%" >}}
4. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "0.54%" >}}
5. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.53%" >}}
6. {{< a "https://cloud.google.com/" "Google Cloud" >}} {{< span "weak" "0.46%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.25%" >}}
8. {{< a "https://www.wideorbit.com/" "WideOrbit" >}} {{< span "weak" "0.20%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.17%" >}}
10. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.17%" >}}
---

### 8. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.64% of new episodes in September, shrinking 2.76% from last month.

Of these, 15.76% had one other tracker, 4.70% had 5 other trackers, 3.77% had 2 other trackers, 3.47% had 6 other trackers, 2.71% had 4 other trackers, 2.67% had 3 other trackers, 0.11% had 7 other trackers, 0.10% had 9 other trackers, and 0.03% had 8 other trackers.

28.92% also included Podtrac, 12.98% also included Podscribe, 12.47% also included Podsights, 11.69% also included OP3, 9.13% also included Gumshoe, 4.58% also included Spotify, 2.41% also included Podroll, 1.52% also included Podder, 1.42% also included Adswizz, 1.22% also included Chartable, 0.57% also included Magellan AI, 0.50% also included Blubrry, 0.23% also included Swap.fm, 0.17% also included Feedpress, 0.14% also included Podkite, 0.13% also included Claritas, 0.10% also included CoHost Prefix, 0.07% also included Zencastr, and 0.03% also included United Podcasters.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "25.56%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "13.45%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.98%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "9.87%" >}}
5. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "8.82%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.58%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "6.15%" >}}
8. {{< a "https://www.wideorbit.com/" "WideOrbit" >}} {{< span "weak" "5.46%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.72%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.66%" >}}
---

### 9. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.58% of new episodes in September, shrinking 25.67% from last month.

Of these, 31.01% had 3 other trackers, 25.94% had 4 other trackers, 18.36% had 5 other trackers, 10.55% had 6 other trackers, 8.82% had 2 other trackers, 3.24% had 7 other trackers, and 1.59% had one other tracker.

98.09% also included Podscribe, 74.70% also included Magellan AI, 52.81% also included Podtrac, 40.00% also included Podsights, 33.70% also included Spotify, 31.36% also included Adswizz, 25.42% also included ArtsAI, 11.72% also included Chartable, 10.92% also included Veritonic, 4.97% also included Podroll, 4.88% also included Swap.fm, 1.78% also included Podder, 1.22% also included Gumshoe, 1.08% also included OP3, 0.62% also included CoHost Prefix, 0.40% also included United Podcasters, and 0.14% also included Podcorn.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "31.48%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.40%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "14.17%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "9.38%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.24%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.02%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.20%" >}}
8. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.33%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.26%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.25%" >}}
---

### 10. [Podroll](https://podroll.fm/)

Podroll was found on 0.55% of new episodes in September, growing 11.84% from last month.

Of these, 74.45% had 2 other trackers, 6.96% had 3 other trackers, 6.22% had one other tracker, 4.79% had 4 other trackers, 3.87% had 6 other trackers, 1.30% had 5 other trackers, 0.50% had 7 other trackers, 0.11% had 9 other trackers, and 0.04% had 8 other trackers.

84.39% also included Podtrac, 78.43% also included Adswizz, 14.83% also included Podscribe, 12.12% also included Magellan AI, 9.59% also included Podsights, 6.70% also included Chartable, 6.42% also included Swap.fm, 5.20% also included Claritas, 3.44% also included Spotify, 2.82% also included Podcorn, 1.44% also included OP3, 0.98% also included ArtsAI, 0.96% also included United Podcasters, 0.82% also included Gumshoe, 0.69% also included Podder, 0.43% also included Veritonic, 0.38% also included CoHost Prefix, and 0.04% also included Podkite.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "78.51%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.26%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.65%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.95%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "1.58%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.14%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.94%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.47%" >}}
9. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "0.24%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.11%" >}}
---

### 11. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.53% of new episodes in September, shrinking 2.28% from last month.

Of these, 36.30% had 2 other trackers, 14.58% had 4 other trackers, 11.67% had 5 other trackers, 10.48% had 6 other trackers, 7.86% had 3 other trackers, 6.50% had one other tracker, 3.22% had 7 other trackers, and 0.12% had 9 other trackers.

62.86% also included Podtrac, 62.72% also included Podscribe, 36.68% also included Claritas, 31.17% also included Magellan AI, 27.21% also included Chartable, 21.17% also included Adswizz, 17.96% also included Podsights, 15.25% also included ArtsAI, 6.68% also included OP3, 6.03% also included Gumshoe, 5.57% also included Podcorn, 4.17% also included Veritonic, 3.58% also included Podroll, 2.20% also included Swap.fm, 1.29% also included Podder, 0.70% also included CoHost Prefix, 0.27% also included Blubrry, 0.17% also included United Podcasters, and 0.06% also included Podkite.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "36.36%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "20.40%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "12.87%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.91%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "6.68%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.59%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.64%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.60%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.99%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.67%" >}}
---

### 12. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.37% of new episodes in September, growing 6.69% from last month.

Of these, 19.32% had one other tracker, 10.13% had 5 other trackers, 6.62% had 6 other trackers, 6.41% had 2 other trackers, 4.86% had 3 other trackers, 3.65% had 4 other trackers, 0.21% had 7 other trackers, 0.17% had 9 other trackers, and 0.06% had 8 other trackers.

39.66% also included Podtrac, 22.01% also included Podscribe, 21.09% also included Podsights, 20.57% also included Podcorn, 17.93% also included Gumshoe, 9.67% also included Spotify, 6.73% also included Adswizz, 4.21% also included Magellan AI, 2.21% also included Chartable, 2.17% also included Podroll, 1.70% also included Claritas, 1.68% also included Swap.fm, 1.66% also included Blubrry, 1.55% also included Podder, 0.84% also included ArtsAI, 0.62% also included CoHost Prefix, 0.60% also included Podkite, 0.13% also included Feedpress, 0.04% also included United Podcasters, and 0.04% also included Zencastr.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "28.81%" >}}
2. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "9.55%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.85%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.37%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "6.23%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.24%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.76%" >}}
8. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "2.51%" >}}
9. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "2.04%" >}}
10. {{< a "https://vodio.fr/" "Vodio" >}} {{< span "weak" "1.70%" >}}
---

### 13. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.33% of new episodes in September, shrinking 7.25% from last month.

Of these, 23.55% had one other tracker, 19.07% had 2 other trackers, 16.54% had 3 other trackers, 15.83% had 4 other trackers, 14.43% had 5 other trackers, 3.35% had 6 other trackers, and 0.86% had 7 other trackers.

52.66% also included Podsights, 48.45% also included Podtrac, 45.92% also included Podscribe, 43.35% also included Chartable, 39.15% also included Magellan AI, 10.81% also included Podroll, 8.59% also included Claritas, 7.11% also included ArtsAI, 5.96% also included Adswizz, 3.55% also included Spotify, 1.88% also included OP3, 1.55% also included Gumshoe, 1.34% also included United Podcasters, 1.13% also included Veritonic, 0.54% also included Podder, 0.46% also included Podcorn, 0.29% also included Blubrry, and 0.10% also included Zencastr.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "69.82%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.91%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.85%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.25%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "4.89%" >}}
6. {{< a "https://www.washingtonpost.com/" "The Washington Post" >}} {{< span "weak" "0.63%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.25%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.19%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.19%" >}}
10. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "0.02%" >}}
---

### 14. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.21% of new episodes in September, growing 2.29% from last month.

Of these, 30.92% had 4 other trackers, 18.54% had 5 other trackers, 16.22% had 3 other trackers, 12.02% had 6 other trackers, 10.13% had 2 other trackers, 8.77% had 7 other trackers, and 3.05% had one other tracker.

89.28% also included Podscribe, 70.87% also included Claritas, 64.38% also included Podtrac, 55.35% also included Magellan AI, 51.18% also included Podsights, 39.06% also included Spotify, 15.03% also included Veritonic, 12.68% also included Adswizz, 11.25% also included Swap.fm, 6.92% also included Chartable, 2.62% also included Podroll, 1.49% also included OP3, 0.70% also included Podder, 0.43% also included United Podcasters, 0.26% also included CoHost Prefix, 0.17% also included Blubrry, and 0.17% also included Gumshoe.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "27.64%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "27.61%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.64%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.71%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.49%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.98%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.73%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.17%" >}}
9. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.03%" >}}
---

### 15. [Podder](https://www.podderapp.com/)

Podder was found on 0.20% of new episodes in September, shrinking 2.85% from last month.

Of these, 18.78% had 2 other trackers, 15.05% had one other tracker, 8.58% had 4 other trackers, 7.33% had 3 other trackers, 5.26% had 5 other trackers, 0.73% had 6 other trackers, 0.42% had 7 other trackers, 0.31% had 9 other trackers, and 0.10% had 8 other trackers.

32.76% also included Podtrac, 30.13% also included Podscribe, 17.85% also included Podsights, 15.81% also included Adswizz, 13.32% also included Magellan AI, 12.18% also included Chartable, 5.19% also included Claritas, 4.95% also included Podcorn, 3.46% also included Spotify, 2.87% also included OP3, 2.32% also included Gumshoe, 1.94% also included Podroll, 1.07% also included Blubrry, 0.90% also included Swap.fm, 0.73% also included ArtsAI, 0.31% also included CoHost Prefix, 0.28% also included Podkite, and 0.07% also included United Podcasters.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "39.64%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "17.71%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "16.08%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "8.20%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.74%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.01%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.59%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.21%" >}}
9. {{< a "https://cloud.google.com/" "Google Cloud" >}} {{< span "weak" "2.14%" >}}
10. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.76%" >}}
---

### 16. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.14% of new episodes in September, growing 6.76% from last month.

Of these, 20.26% had one other tracker, and 2.19% had 2 other trackers.

14.29% also included Blubrry, 4.86% also included Podtrac, 2.19% also included Podsights, 2.19% also included Chartable, 0.78% also included Podcorn, and 0.34% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "57.87%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "10.11%" >}}
3. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "6.80%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.23%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "3.16%" >}}
6. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "2.38%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.70%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.60%" >}}
9. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.51%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "0.97%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.13% of new episodes in September, shrinking 9.40% from last month.

Of these, 27.72% had 5 other trackers, 16.52% had 6 other trackers, 12.55% had 4 other trackers, 12.39% had one other tracker, 7.66% had 2 other trackers, 6.74% had 3 other trackers, 1.63% had 7 other trackers, 0.49% had 9 other trackers, and 0.16% had 8 other trackers.

62.12% also included Podscribe, 61.63% also included Podtrac, 60.38% also included Podsights, 52.12% also included OP3, 46.68% also included Podcorn, 25.38% also included Spotify, 11.58% also included Magellan AI, 9.29% also included Chartable, 5.60% also included Claritas, 4.02% also included Swap.fm, 3.64% also included Podder, 3.59% also included Podroll, 2.66% also included CoHost Prefix, 1.63% also included Veritonic, 1.41% also included Adswizz, 0.82% also included United Podcasters, 0.27% also included ArtsAI, and 0.16% also included Podkite.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "52.39%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "21.09%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "19.02%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.99%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.52%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.36%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.87%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.27%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.27%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.22%" >}}
---

### 18. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.08% of new episodes in September, growing 1.52% from last month.

Of these, 32.63% had 5 other trackers, 25.26% had 7 other trackers, 22.63% had 6 other trackers, 10.70% had 4 other trackers, 7.63% had 3 other trackers, and 0.44% had 2 other trackers.

93.07% also included Podscribe, 88.42% also included Podsights, 82.54% also included Podtrac, 81.05% also included Magellan AI, 80.70% also included Claritas, 39.82% also included ArtsAI, 28.33% also included Spotify, 25.53% also included Chartable, 11.67% also included Adswizz, 4.74% also included Swap.fm, 3.07% also included Podroll, 2.63% also included Gumshoe, 0.44% also included United Podcasters, and 0.35% also included CoHost Prefix.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "76.32%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "11.58%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.05%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.89%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.40%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.53%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.44%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.35%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.26%" >}}
10. {{< a "https://www.thisamericanlife.org/" "This American Life" >}} {{< span "weak" "0.18%" >}}
---

### 19. [Firstory](https://firstory.me/)

Firstory was found on 0.03% of new episodes in September, shrinking 20.72% from last month.

Of these, 0.99% had one other tracker.

0.99% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "100.00%" >}}
---

### 20. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.02% of new episodes in September, growing 5.96% from last month.

Of these, 30.60% had 4 other trackers, 13.79% had one other tracker, 12.93% had 2 other trackers, 12.93% had 5 other trackers, 3.88% had 9 other trackers, 2.59% had 6 other trackers, 2.16% had 3 other trackers, and 1.72% had 7 other trackers.

53.02% also included Podscribe, 53.02% also included Podtrac, 33.19% also included Podsights, 28.88% also included Chartable, 23.28% also included Spotify, 22.41% also included Claritas, 21.12% also included Gumshoe, 19.40% also included Magellan AI, 14.22% also included OP3, 13.36% also included Podroll, 3.88% also included Podcorn, 3.88% also included Podder, 3.45% also included ArtsAI, 1.72% also included Veritonic, and 0.86% also included Adswizz.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.05%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "19.40%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "12.93%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "8.19%" >}}
5. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "6.03%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "6.03%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.45%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.59%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.16%" >}}
10. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.29%" >}}
---

### 21. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.02% of new episodes in September, shrinking 9.73% from last month.

Of these, 21.88% had one other tracker, 21.88% had 2 other trackers, 19.64% had 3 other trackers, 12.50% had 6 other trackers, 9.82% had 5 other trackers, 8.93% had 4 other trackers, and 0.45% had 7 other trackers.

41.07% also included Magellan AI, 40.18% also included Podtrac, 34.38% also included Podroll, 33.93% also included Podscribe, 32.59% also included Podsights, 28.57% also included Swap.fm, 25.89% also included Chartable, 15.18% also included Claritas, 11.61% also included Adswizz, 6.70% also included Gumshoe, 5.80% also included Spotify, 5.80% also included ArtsAI, 2.23% also included Veritonic, 1.34% also included Podcorn, 0.89% also included Podder, 0.89% also included OP3, and 0.45% also included Zencastr.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "48.66%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "11.16%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "11.16%" >}}
4. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "9.82%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.93%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "2.68%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.68%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.79%" >}}
9. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "1.79%" >}}
10. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "0.89%" >}}
---

### 22. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in September, growing 17.85% from last month.

Of these, 32.93% had one other tracker, 3.66% had 2 other trackers, 3.66% had 5 other trackers, 2.44% had 4 other trackers, and 1.83% had 8 other trackers.

21.95% also included Podtrac, 19.51% also included OP3, 8.54% also included Podsights, 7.93% also included Podcorn, 5.49% also included Blubrry, 4.88% also included Podscribe, 4.88% also included Podder, 3.05% also included Chartable, 3.05% also included Spotify, 1.83% also included Podroll, and 1.83% also included Gumshoe.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "31.71%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "16.46%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "15.24%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "12.80%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.93%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "5.49%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.88%" >}}
8. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "2.44%" >}}
9. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "1.83%" >}}
10. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "1.22%" >}}
---

### 23. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.01% of new episodes in September, shrinking 34.61% from last month.

Of these, 10.53% had one other tracker.

10.53% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "100.00%" >}}
---

### 24. [Zencastr](https://zencastr.com/)

Zencastr was found on <0.01% of new episodes in September, growing 36.39% from last month.

Of these, 12.33% had one other tracker, 5.48% had 6 other trackers, 2.74% had 2 other trackers, and 1.37% had 7 other trackers.

15.07% also included Podtrac, 10.96% also included Chartable, 9.59% also included Podcorn, 6.85% also included Podscribe, 6.85% also included Swap.fm, 6.85% also included Podsights, 2.74% also included OP3, and 1.37% also included United Podcasters.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "32.88%" >}}
2. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "17.81%" >}}
3. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "15.07%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "9.59%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "8.22%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.22%" >}}
7. {{< a "https://www.digitalocean.com/products/spaces/" "DigitalOcean Spaces" >}} {{< span "weak" "4.11%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.11%" >}}
---

### 25. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in September, growing 37.85% from last month.

Of these, 29.09% had one other tracker.

25.45% also included Podtrac, and 3.64% also included Chartable.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "38.18%" >}}
2. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "27.27%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "14.55%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.09%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.45%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.64%" >}}
7. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "1.82%" >}}---

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
