---
title: "Top Podcast Tracking Services by Episode Share (August 2025)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-august-2025"
images:
- trackers-2025-08.png
date: 2025-09-01T10:52:00-04:00
lastmod: 2025-09-01T10:52:00-04:00
draft: false
rssrevision: 2025-08
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.5 million in August 2025), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in July, how many
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
Month	Podtrac	Adswizz	Podscribe	Podsights	Blubrry	Chartable	Claritas	Podcorn	Spotify	Podroll	Swap.fm	OP3	Podder	ArtsAI	Gumshoe	Feedpress	Veritonic	United Podcasters	CoHost Prefix	Médiamétrie	Podkite	Audiotakes	RSS Insight	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	1.00		1.16	2.07	4.06		2.09								0.32				0.42										1.61
Oct 2021	4.05	1.01		1.20	2.11	4.09		2.13								0.34				0.54										1.61
Nov 2021	4.07	1.02		1.25	2.01	4.30		2.14								0.32				0.57										0.59
Dec 2021	4.06	1.24		1.19	1.57	4.42		2.27								0.19				0.59										
Jan 2022	4.11	1.41		1.21	1.56	4.45		2.31								0.16				0.63										
Feb 2022	4.15	1.44		1.25	1.53	4.48		2.38								0.17				0.58										
Mar 2022	4.37	1.51		1.34	1.56	4.72		2.40								0.17				0.53										
Apr 2022	4.44	1.49		1.33	1.55	4.71		2.33								0.16				0.51										
May 2022	4.49	1.58		1.41	1.48	4.87		2.26								0.17				0.56										
Jun 2022	4.75	1.77		1.54	1.50	5.10		2.06								0.21				0.62							0.02			
Jul 2022	4.70	1.89		1.50	1.50	5.10		2.16								0.25				0.54							0.02			
Aug 2022	4.83	2.08		1.73	1.51	5.26		2.45						0.10		0.20				0.41							0.01			
Sep 2022	7.53	2.26	0.02	1.74	1.49	5.40	0.01	2.45						0.09		0.21				0.52	0.01						0.02	0.02		
Oct 2022	8.24	2.35	0.07	1.81	1.61	5.48	0.02	2.51				0.03		0.10		0.18				0.50	0.01			0.01			0.02	0.04		
Nov 2022	8.11	2.37	0.15	2.03	1.62	5.62	0.03	2.43				0.04	0.01	0.10		0.18				0.50	0.01			0.01			0.02	0.05		
Dec 2022	8.01	2.32	0.03	1.81	1.61	5.54	0.02	2.05				0.05	0.04	0.05		0.18				0.49	0.01			0.01		0.01	0.02	0.05		
Jan 2023	7.85	2.35	0.20	1.88	1.61	5.56	0.06	2.15				0.07	0.11	0.10		0.18				0.54	0.01			0.01		0.01	0.02	0.06		
Feb 2023	7.58	2.29	0.21	1.92	1.62	5.51	0.07	2.30				0.07	0.11	0.10		0.19				0.49	0.01			0.01		0.01	0.02	0.06	0.03	
Mar 2023	7.79	2.25	0.21	2.03	1.53	5.53	0.07	2.22		0.04		0.08	0.11	0.11		0.18	0.04			0.45	0.01			0.01		0.01	0.02	0.06		
Apr 2023	7.66	2.26	0.21	2.00	1.67	5.43	0.07	2.20		0.06		0.09	0.15	0.11	0.08	0.17	0.05			0.45	0.01			0.01		0.01	0.01			
May 2023	7.58	2.27	0.24	2.04	1.67	5.59	0.08	2.28		0.09		0.09	0.15	0.11	0.07	0.19	0.05			0.45	0.01			0.01	0.01	0.01	0.01			
Jun 2023	8.22	2.39	0.26	2.23	1.64	5.83	0.07	1.86		0.10		0.09	0.15	0.12	0.08	0.19	0.05			0.51	0.01			0.01	0.01	0.01	0.01			
Jul 2023	8.60	2.38	0.27	2.52	1.53	5.95	0.07	1.17	0.01	0.14		0.08	0.14	0.11	0.06	0.18	0.06			0.55	0.01			0.01	0.01	0.01	0.01			
Aug 2023	9.19	2.72	0.36	2.76	1.58	6.43	0.08	1.23	0.03	0.16		0.11	0.15	0.12	0.07	0.17	0.07			0.53	0.01	0.04		0.01	0.02	0.01				
Sep 2023	8.46	2.49	0.37	2.47	1.39	5.77	0.10	1.10	0.05	0.13		0.10	0.15	0.12	0.07	0.16	0.06			0.58	0.01	0.05		0.01	0.02	0.01				
Oct 2023	7.90	2.29	0.39	2.28	1.37	5.54	0.10	1.11	0.08	0.12		0.10	0.16	0.12	0.08	0.16	0.06			0.50	0.01	0.05		0.02	0.03	0.01				
Nov 2023	7.65	2.25	0.47	2.33	1.45	5.59	0.11	1.14	0.11	0.12		0.13	0.16	0.12	0.10	0.17	0.06			0.33	0.01	0.06		0.01	0.03					
Dec 2023	7.48	2.20	0.54	2.19	1.53	5.60	0.11	1.12	0.12	0.12		0.11	0.16	0.12	0.09	0.16	0.06			0.33	0.01	0.06		0.01	0.03					
Jan 2024	7.64	2.37	0.65	2.21	1.55	5.61	0.12	1.17	0.15	0.11		0.13	0.16	0.14	0.10	0.17	0.06	0.01		0.25	0.01	0.08		0.01	0.01					
Feb 2024	7.69	2.38	0.69	2.22	1.52	5.58	0.13	1.21	0.22	0.12		0.16	0.17	0.13	0.11	0.17	0.06	0.01		0.22	0.01	0.09		0.01						
Mar 2024	9.01	2.53	0.69	2.19	1.54	5.46	0.14	1.14	0.25	0.12		0.14	0.16	0.12	0.10	0.16	0.06	0.01		0.22	0.01	0.09		0.01						
Apr 2024	10.78	2.53	0.73	2.16	1.51	5.47	0.15	1.24	0.27	0.34		0.18	0.17	0.13	0.11	0.15	0.07	0.01	0.01	0.19	0.01	0.07		0.01						
May 2024	11.59	2.75	0.83	2.24	1.50	5.63	0.15	1.20	0.30	0.36		0.18	0.16	0.14	0.11	0.15	0.07	0.01	0.01	0.09	0.01	0.06		0.01						
Jun 2024	11.54	2.88	0.91	2.34	1.52	6.06	0.16	0.71	0.32	0.37	0.03	0.20	0.15	0.16	0.11	0.15	0.07	0.01	0.01	0.10	0.01	0.07		0.01						
Jul 2024	12.34	2.83	1.01	2.45	1.65	6.80	0.18	0.71	0.34	0.43	0.06	0.20	0.15	0.17	0.12	0.15	0.07	0.01	0.01	0.09	0.01	0.09		0.01						
Aug 2024	14.22	2.96	1.11	2.48	1.70	6.72	0.18	0.81	0.35	0.45	0.12	0.19	0.35	0.18	0.12	0.14	0.08	0.01	0.01	0.08	0.01	0.11		0.01						
Sep 2024	12.95	3.13	1.18	2.26	1.44	5.99	0.18	0.72	0.35	0.44	0.12	0.24	0.42	0.18	0.13	0.15	0.08	0.01	0.01	0.07	0.01	0.13		0.01						
Oct 2024	12.24	3.23	1.23	2.35	1.53	5.49	0.19	0.66	0.40	0.43	0.17	0.27	0.39	0.18	0.12	0.14	0.09	0.01	0.01	0.09	0.01	0.14		0.01						
Nov 2024	11.86	3.21	1.27	2.31	1.52	4.66	0.21	0.63	0.44	0.43	0.19	0.29	0.41	0.17	0.12	0.11	0.08	0.01	0.01	0.10	0.01	0.14		0.01						
Dec 2024	12.56	3.06	1.29	2.13	1.40	2.29	0.21	0.62	0.45	0.43	0.24	0.29	0.54	0.18	0.12	0.09	0.08	0.01	0.01	0.09	0.01	0.15		0.01						
Jan 2025	12.62	2.92	1.31	1.73	1.36	1.54	0.21	0.66	0.41	0.46	0.27	0.34	0.54	0.19	0.13	0.12	0.08	0.01	0.01	0.04	0.01	0.16		0.01						
Feb 2025	12.47	2.74	1.25	1.70	1.45	1.43	0.22	0.66	0.36	0.46	0.28	0.33	0.48	0.18	0.12	0.14	0.08	0.01	0.01	0.01	0.01	0.16		0.01						
Mar 2025	12.18	2.87	1.28	1.51	1.25	1.18	0.21	0.67	0.33	0.47	0.27	0.33	0.36	0.18	0.13	0.14	0.07	0.01	0.01	0.01	0.01	0.25	0.04	0.01						
Apr 2025	12.35	2.97	1.53	1.64	1.26	1.28	0.23	0.68	0.44	0.48	0.30	0.34	0.33	0.19	0.12	0.13	0.08	0.01	0.01	0.02	0.01	0.41	0.03	0.01						
May 2025	12.48	2.97	1.61	1.74	1.40	1.31	0.24	0.64	0.46	0.46	0.33	0.39	0.22	0.20	0.12	0.13	0.07	0.02	0.01	0.02	0.01	0.40	0.05							
Jun 2025	12.99	2.73	1.65	1.70	1.34	1.30	0.26	0.65	0.47	0.46	0.35	0.39	0.20	0.21	0.12	0.13	0.07	0.02	0.01	0.02	0.01	0.40	0.04							
Jul 2025	13.83	2.87	1.76	1.71	1.16	1.30	0.72	0.66	0.50	0.48	0.39	0.33	0.20	0.23	0.12	0.13	0.07	0.02	0.01	0.01	0.01									
Aug 2025	14.30	3.24	1.95	1.83	1.35	1.32	0.79	0.67	0.54	0.49	0.37	0.35	0.21	0.20	0.14	0.14	0.08	0.02	0.02	0.01	0.01									
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} have historically been the top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podscribe	Podsights	Blubrry	Claritas	Podcorn	Spotify	Podroll	Swap.fm	OP3	Podder	ArtsAI	Gumshoe	Feedpress	Veritonic	United Podcasters	CoHost Prefix	Médiamétrie	Podkite	Audiotakes	RSS Insight	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	1.00		1.16	2.07		2.09								0.32				0.42										1.61
Oct 2021	1.01		1.20	2.11		2.13								0.34				0.54										1.61
Nov 2021	1.02		1.25	2.01		2.14								0.32				0.57										0.59
Dec 2021	1.24		1.19	1.57		2.27								0.19				0.59										
Jan 2022	1.41		1.21	1.56		2.31								0.16				0.63										
Feb 2022	1.44		1.25	1.53		2.38								0.17				0.58										
Mar 2022	1.51		1.34	1.56		2.40								0.17				0.53										
Apr 2022	1.49		1.33	1.55		2.33								0.16				0.51										
May 2022	1.58		1.41	1.48		2.26								0.17				0.56										
Jun 2022	1.77		1.54	1.50		2.06								0.21				0.62							0.02			
Jul 2022	1.89		1.50	1.50		2.16								0.25				0.54							0.02			
Aug 2022	2.08		1.73	1.51		2.45						0.10		0.20				0.41							0.01			
Sep 2022	2.26	0.02	1.74	1.49	0.01	2.45						0.09		0.21				0.52	0.01						0.02	0.02		
Oct 2022	2.35	0.07	1.81	1.61	0.02	2.51				0.03		0.10		0.18				0.50	0.01			0.01			0.02	0.04		
Nov 2022	2.37	0.15	2.03	1.62	0.03	2.43				0.04	0.01	0.10		0.18				0.50	0.01			0.01			0.02	0.05		
Dec 2022	2.32	0.03	1.81	1.61	0.02	2.05				0.05	0.04	0.05		0.18				0.49	0.01			0.01		0.01	0.02	0.05		
Jan 2023	2.35	0.20	1.88	1.61	0.06	2.15				0.07	0.11	0.10		0.18				0.54	0.01			0.01		0.01	0.02	0.06		
Feb 2023	2.29	0.21	1.92	1.62	0.07	2.30				0.07	0.11	0.10		0.19				0.49	0.01			0.01		0.01	0.02	0.06	0.03	
Mar 2023	2.25	0.21	2.03	1.53	0.07	2.22		0.04		0.08	0.11	0.11		0.18	0.04			0.45	0.01			0.01		0.01	0.02	0.06		
Apr 2023	2.26	0.21	2.00	1.67	0.07	2.20		0.06		0.09	0.15	0.11	0.08	0.17	0.05			0.45	0.01			0.01		0.01	0.01			
May 2023	2.27	0.24	2.04	1.67	0.08	2.28		0.09		0.09	0.15	0.11	0.07	0.19	0.05			0.45	0.01			0.01	0.01	0.01	0.01			
Jun 2023	2.39	0.26	2.23	1.64	0.07	1.86		0.10		0.09	0.15	0.12	0.08	0.19	0.05			0.51	0.01			0.01	0.01	0.01	0.01			
Jul 2023	2.38	0.27	2.52	1.53	0.07	1.17	0.01	0.14		0.08	0.14	0.11	0.06	0.18	0.06			0.55	0.01			0.01	0.01	0.01	0.01			
Aug 2023	2.72	0.36	2.76	1.58	0.08	1.23	0.03	0.16		0.11	0.15	0.12	0.07	0.17	0.07			0.53	0.01	0.04		0.01	0.02	0.01				
Sep 2023	2.49	0.37	2.47	1.39	0.10	1.10	0.05	0.13		0.10	0.15	0.12	0.07	0.16	0.06			0.58	0.01	0.05		0.01	0.02	0.01				
Oct 2023	2.29	0.39	2.28	1.37	0.10	1.11	0.08	0.12		0.10	0.16	0.12	0.08	0.16	0.06			0.50	0.01	0.05		0.02	0.03	0.01				
Nov 2023	2.25	0.47	2.33	1.45	0.11	1.14	0.11	0.12		0.13	0.16	0.12	0.10	0.17	0.06			0.33	0.01	0.06		0.01	0.03					
Dec 2023	2.20	0.54	2.19	1.53	0.11	1.12	0.12	0.12		0.11	0.16	0.12	0.09	0.16	0.06			0.33	0.01	0.06		0.01	0.03					
Jan 2024	2.37	0.65	2.21	1.55	0.12	1.17	0.15	0.11		0.13	0.16	0.14	0.10	0.17	0.06	0.01		0.25	0.01	0.08		0.01	0.01					
Feb 2024	2.38	0.69	2.22	1.52	0.13	1.21	0.22	0.12		0.16	0.17	0.13	0.11	0.17	0.06	0.01		0.22	0.01	0.09		0.01						
Mar 2024	2.53	0.69	2.19	1.54	0.14	1.14	0.25	0.12		0.14	0.16	0.12	0.10	0.16	0.06	0.01		0.22	0.01	0.09		0.01						
Apr 2024	2.53	0.73	2.16	1.51	0.15	1.24	0.27	0.34		0.18	0.17	0.13	0.11	0.15	0.07	0.01	0.01	0.19	0.01	0.07		0.01						
May 2024	2.75	0.83	2.24	1.50	0.15	1.20	0.30	0.36		0.18	0.16	0.14	0.11	0.15	0.07	0.01	0.01	0.09	0.01	0.06		0.01						
Jun 2024	2.88	0.91	2.34	1.52	0.16	0.71	0.32	0.37	0.03	0.20	0.15	0.16	0.11	0.15	0.07	0.01	0.01	0.10	0.01	0.07		0.01						
Jul 2024	2.83	1.01	2.45	1.65	0.18	0.71	0.34	0.43	0.06	0.20	0.15	0.17	0.12	0.15	0.07	0.01	0.01	0.09	0.01	0.09		0.01						
Aug 2024	2.96	1.11	2.48	1.70	0.18	0.81	0.35	0.45	0.12	0.19	0.35	0.18	0.12	0.14	0.08	0.01	0.01	0.08	0.01	0.11		0.01						
Sep 2024	3.13	1.18	2.26	1.44	0.18	0.72	0.35	0.44	0.12	0.24	0.42	0.18	0.13	0.15	0.08	0.01	0.01	0.07	0.01	0.13		0.01						
Oct 2024	3.23	1.23	2.35	1.53	0.19	0.66	0.40	0.43	0.17	0.27	0.39	0.18	0.12	0.14	0.09	0.01	0.01	0.09	0.01	0.14		0.01						
Nov 2024	3.21	1.27	2.31	1.52	0.21	0.63	0.44	0.43	0.19	0.29	0.41	0.17	0.12	0.11	0.08	0.01	0.01	0.10	0.01	0.14		0.01						
Dec 2024	3.06	1.29	2.13	1.40	0.21	0.62	0.45	0.43	0.24	0.29	0.54	0.18	0.12	0.09	0.08	0.01	0.01	0.09	0.01	0.15		0.01						
Jan 2025	2.92	1.31	1.73	1.36	0.21	0.66	0.41	0.46	0.27	0.34	0.54	0.19	0.13	0.12	0.08	0.01	0.01	0.04	0.01	0.16		0.01						
Feb 2025	2.74	1.25	1.70	1.45	0.22	0.66	0.36	0.46	0.28	0.33	0.48	0.18	0.12	0.14	0.08	0.01	0.01	0.01	0.01	0.16		0.01						
Mar 2025	2.87	1.28	1.51	1.25	0.21	0.67	0.33	0.47	0.27	0.33	0.36	0.18	0.13	0.14	0.07	0.01	0.01	0.01	0.01	0.25	0.04	0.01						
Apr 2025	2.97	1.53	1.64	1.26	0.23	0.68	0.44	0.48	0.30	0.34	0.33	0.19	0.12	0.13	0.08	0.01	0.01	0.02	0.01	0.41	0.03	0.01						
May 2025	2.97	1.61	1.74	1.40	0.24	0.64	0.46	0.46	0.33	0.39	0.22	0.20	0.12	0.13	0.07	0.02	0.01	0.02	0.01	0.40	0.05							
Jun 2025	2.73	1.65	1.70	1.34	0.26	0.65	0.47	0.46	0.35	0.39	0.20	0.21	0.12	0.13	0.07	0.02	0.01	0.02	0.01	0.40	0.04							
Jul 2025	2.87	1.76	1.71	1.16	0.72	0.66	0.50	0.48	0.39	0.33	0.20	0.23	0.12	0.13	0.07	0.02	0.01	0.01	0.01									
Aug 2025	3.24	1.95	1.83	1.35	0.79	0.67	0.54	0.49	0.37	0.35	0.21	0.20	0.14	0.14	0.08	0.02	0.02	0.01	0.01									
{{< /graph >}}

---

### Overall

At least one tracker was found on 20.41% of new episodes in August, growing 5.30% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "46.01%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.58%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.10%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.14%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.11%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.83%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.89%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.40%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.27%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.18%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of August 2025.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 14.30% of new episodes in August, growing 3.39% from last month.

Of these, 9.84% had one other tracker, 6.84% had 2 other trackers, 1.38% had 3 other trackers, 1.27% had 4 other trackers, 1.07% had 5 other trackers, 0.65% had 6 other trackers, 0.15% had 7 other trackers, <0.01% had 9 other trackers, and <0.01% had 8 other trackers.

8.45% also included Podsights, 6.29% also included Podscribe, 5.94% also included Adswizz, 4.95% also included Chartable, 2.85% also included Podroll, 2.67% also included Magellan AI, 2.37% also included Spotify, 2.12% also included Claritas, 1.35% also included Swap.fm, 1.29% also included Podcorn, 1.13% also included Blubrry, 1.05% also included OP3, 0.93% also included ArtsAI, 0.64% also included Gumshoe, 0.46% also included Veritonic, 0.45% also included Podder, 0.07% also included CoHost Prefix, 0.05% also included Feedpress, 0.05% also included United Podcasters, 0.02% also included Podkite, 0.01% also included AdBarker, <0.01% also included Médiamétrie, and <0.01% also included Podcards.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "65.45%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "8.31%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.80%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.85%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.14%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.67%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.64%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.72%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.67%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.52%" >}}
---

### 2. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 3.24% of new episodes in August, growing 13.07% from last month.

Of these, 15.28% had 2 other trackers, 13.99% had one other tracker, 9.23% had 3 other trackers, 2.66% had 4 other trackers, 1.28% had 5 other trackers, 0.58% had 6 other trackers, and 0.04% had 7 other trackers.

26.21% also included Podtrac, 16.77% also included Podscribe, 13.50% also included Magellan AI, 12.15% also included Claritas, 11.61% also included Podroll, 3.34% also included Podsights, 2.87% also included Spotify, 1.64% also included Swap.fm, 1.08% also included Blubrry, 0.99% also included Chartable, 0.90% also included Podder, 0.84% also included ArtsAI, 0.51% also included OP3, 0.29% also included Podcorn, 0.29% also included Veritonic, 0.05% also included Gumshoe, and 0.04% also included United Podcasters.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "63.73%" >}}
2. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "5.71%" >}}
3. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "5.67%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "5.01%" >}}
5. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "4.87%" >}}
6. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "3.54%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.00%" >}}
8. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "2.69%" >}}
9. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.38%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.95%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 2.73% of new episodes in August, growing 5.62% from last month.

Of these, 58.14% also included Podtrac, 32.54% also included Podscribe, 18.18% also included Magellan AI, 14.10% also included Claritas, 8.52% also included Swap.fm, 8.49% also included Adswizz, 5.82% also included ArtsAI, 3.79% also included Podcorn, 3.69% also included Gumshoe, 3.60% also included OP3, 2.77% also included Veritonic, 2.73% also included Podroll, 1.47% also included Podder, 0.49% also included Blubrry, 0.37% also included CoHost Prefix, 0.34% also included United Podcasters, 0.08% also included Feedpress, 0.06% also included Podkite, 0.03% also included Firstory, 0.01% also included Zencastr, <0.01% also included AdBarker, and <0.01% also included Podcards.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "56.27%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.80%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.44%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.45%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.08%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.76%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.38%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.26%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.10%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.04%" >}}
---

### 3. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 1.95% of new episodes in August, growing 10.86% from last month.

Of these, 24.22% had 3 other trackers, 20.40% had one other tracker, 14.49% had 4 other trackers, 13.60% had 2 other trackers, 9.46% had 5 other trackers, 5.27% had 6 other trackers, 1.13% had 7 other trackers, 0.02% had 9 other trackers, and 0.02% had 8 other trackers.

46.00% also included Podtrac, 45.34% also included Magellan AI, 39.71% also included Claritas, 31.43% also included Podsights, 27.81% also included Adswizz, 16.71% also included Spotify, 15.20% also included Chartable, 9.30% also included ArtsAI, 8.24% also included Swap.fm, 4.84% also included Podcorn, 4.72% also included Gumshoe, 4.31% also included OP3, 3.89% also included Podroll, 3.74% also included Veritonic, 2.98% also included Podder, 0.48% also included CoHost Prefix, 0.36% also included United Podcasters, 0.31% also included Blubrry, 0.03% also included Podkite, and <0.01% also included Podcards.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "37.23%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "26.14%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.49%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.98%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.35%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.67%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.37%" >}}
8. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "3.21%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.27%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.54%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.83% of new episodes in August, growing 7.20% from last month.

Of these, 33.98% had one other tracker, 22.57% had 2 other trackers, 10.64% had 4 other trackers, 9.04% had 3 other trackers, 7.74% had 5 other trackers, 4.73% had 6 other trackers, 1.20% had 7 other trackers, 0.03% had 9 other trackers, and 0.02% had 8 other trackers.

66.09% also included Podtrac, 39.42% also included Chartable, 33.61% also included Podscribe, 19.20% also included Magellan AI, 13.11% also included Claritas, 10.41% also included Swap.fm, 6.11% also included Spotify, 5.92% also included Adswizz, 5.73% also included ArtsAI, 5.06% also included Podcorn, 4.88% also included Gumshoe, 4.88% also included OP3, 3.83% also included Veritonic, 2.93% also included Podroll, 1.97% also included Podder, 0.56% also included Blubrry, 0.39% also included United Podcasters, 0.38% also included CoHost Prefix, 0.12% also included Feedpress, 0.05% also included Podkite, and <0.01% also included Podcards.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "61.02%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "21.67%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.72%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.57%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.97%" >}}
6. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.29%" >}}
7. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.29%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.28%" >}}
9. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.03%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.70%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.35% of new episodes in August, growing 16.73% from last month.

Of these, 15.31% had one other tracker, 0.90% had 2 other trackers, 0.22% had 3 other trackers, 0.07% had 4 other trackers, 0.07% had 5 other trackers, and 0.02% had 6 other trackers.

11.89% also included Podtrac, 2.58% also included Adswizz, 1.45% also included Feedpress, 0.76% also included Podsights, 0.45% also included Podscribe, 0.25% also included OP3, 0.23% also included Podcorn, 0.19% also included Swap.fm, 0.18% also included Magellan AI, 0.16% also included Chartable, 0.15% also included Podder, 0.13% also included Spotify, 0.07% also included ArtsAI, 0.04% also included Podkite, 0.01% also included Claritas, and 0.01% also included Veritonic.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "46.96%" >}}
2. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "5.10%" >}}
3. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "4.02%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.80%" >}}
5. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "2.69%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.60%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.34%" >}}
8. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.15%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.87%" >}}
10. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "0.74%" >}}
---

### 6. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 1.32% of new episodes in August, growing 1.22% from last month.

Of these, 35.14% had 2 other trackers, 22.71% had one other tracker, 8.31% had 3 other trackers, 7.20% had 4 other trackers, 4.58% had 5 other trackers, 2.84% had 6 other trackers, 0.34% had 7 other trackers, and <0.01% had 8 other trackers.

54.61% also included Podsights, 53.67% also included Podtrac, 22.51% also included Podscribe, 15.69% also included Magellan AI, 12.00% also included Swap.fm, 11.63% also included Spotify, 5.60% also included Claritas, 2.75% also included Podroll, 2.43% also included Adswizz, 1.65% also included Podder, 1.59% also included Veritonic, 1.09% also included Gumshoe, 1.02% also included ArtsAI, 0.79% also included OP3, 0.78% also included Podcorn, 0.44% also included CoHost Prefix, 0.41% also included United Podcasters, 0.16% also included Blubrry, 0.16% also included Feedpress, 0.05% also included Firstory, 0.02% also included Podkite, 0.02% also included Zencastr, 0.01% also included AdBarker, and <0.01% also included Podcards.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "86.17%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.86%" >}}
3. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.61%" >}}
4. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.56%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.43%" >}}
6. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "0.40%" >}}
7. {{< a "https://cloud.google.com/" "Google Cloud" >}} {{< span "weak" "0.40%" >}}
8. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.30%" >}}
9. {{< a "https://www.wideorbit.com/" "WideOrbit" >}} {{< span "weak" "0.21%" >}}
10. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "0.15%" >}}
---

### 7. [Magellan AI](https://www.magellan.ai/prefix)

Magellan AI was found on 1.22% of new episodes in August, growing 11.42% from last month.

Of these, 30.94% had 3 other trackers, 16.65% had 4 other trackers, 11.34% had 5 other trackers, 10.39% had one other tracker, 8.03% had 2 other trackers, 5.58% had 6 other trackers, 1.66% had 7 other trackers, and 0.01% had 8 other trackers.

72.81% also included Podscribe, 52.52% also included Claritas, 35.96% also included Adswizz, 31.34% also included Podtrac, 28.84% also included Podsights, 17.02% also included Chartable, 13.09% also included Spotify, 11.34% also included Swap.fm, 9.38% also included ArtsAI, 5.24% also included Veritonic, 5.09% also included Podroll, 1.81% also included Podder, 1.23% also included Gumshoe, 0.83% also included OP3, 0.59% also included United Podcasters, 0.25% also included Podcorn, 0.21% also included CoHost Prefix, and 0.20% also included Blubrry.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "33.13%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.91%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "12.01%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.51%" >}}
5. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "5.25%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.61%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.37%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "2.40%" >}}
9. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.19%" >}}
10. {{< a "https://www.americanpublicmedia.org/" "American Public Media" >}} {{< span "weak" "1.16%" >}}
---

### 8. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.79% of new episodes in August, growing 9.93% from last month.

Of these, 45.39% had 3 other trackers, 22.00% had 4 other trackers, 13.67% had 5 other trackers, 8.13% had 6 other trackers, 6.46% had 2 other trackers, 2.47% had 7 other trackers, and 1.30% had one other tracker.

98.31% also included Podscribe, 80.95% also included Magellan AI, 49.88% also included Adswizz, 38.38% also included Podtrac, 30.37% also included Podsights, 24.48% also included Spotify, 19.70% also included ArtsAI, 9.36% also included Chartable, 8.04% also included Veritonic, 5.45% also included Podroll, 3.97% also included Swap.fm, 1.20% also included Podder, 1.04% also included Gumshoe, 0.78% also included OP3, 0.50% also included CoHost Prefix, 0.33% also included United Podcasters, 0.11% also included Podcorn, and 0.02% also included Blubrry.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "50.11%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "22.70%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.58%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "6.64%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.39%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.43%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.33%" >}}
8. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.28%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.21%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.12%" >}}
---

### 9. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.67% of new episodes in August, growing 2.36% from last month.

Of these, 12.86% had one other tracker, 5.07% had 5 other trackers, 4.90% had 6 other trackers, 4.10% had 2 other trackers, 2.26% had 4 other trackers, 2.16% had 3 other trackers, 0.08% had 7 other trackers, 0.07% had 9 other trackers, and 0.05% had 8 other trackers.

27.43% also included Podtrac, 14.07% also included Podscribe, 13.77% also included Podsights, 12.79% also included OP3, 10.62% also included Gumshoe, 5.89% also included Spotify, 2.21% also included Podroll, 1.55% also included Podder, 1.53% also included Chartable, 1.42% also included Adswizz, 0.47% also included Blubrry, 0.45% also included Magellan AI, 0.14% also included Swap.fm, 0.13% also included Claritas, 0.12% also included Podkite, 0.12% also included United Podcasters, 0.10% also included Feedpress, 0.07% also included CoHost Prefix, and 0.04% also included Zencastr.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "23.19%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "14.18%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "11.64%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "10.62%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.32%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.88%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "6.83%" >}}
8. {{< a "https://www.wideorbit.com/" "WideOrbit" >}} {{< span "weak" "5.84%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.65%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.27%" >}}
---

### 10. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.54% of new episodes in August, growing 7.83% from last month.

Of these, 31.87% had 2 other trackers, 13.15% had 4 other trackers, 13.12% had 6 other trackers, 10.96% had 5 other trackers, 7.83% had 3 other trackers, 6.19% had one other tracker, 2.96% had 7 other trackers, 0.08% had 9 other trackers, and 0.02% had 8 other trackers.

62.28% also included Podtrac, 59.97% also included Podscribe, 35.49% also included Claritas, 29.26% also included Magellan AI, 28.18% also included Chartable, 20.52% also included Podsights, 17.09% also included Adswizz, 14.72% also included ArtsAI, 7.83% also included OP3, 7.27% also included Podcorn, 7.17% also included Gumshoe, 3.84% also included Veritonic, 3.12% also included Podroll, 2.11% also included Swap.fm, 1.31% also included Podder, 0.56% also included CoHost Prefix, 0.31% also included Blubrry, 0.16% also included United Podcasters, and 0.06% also included Podkite.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "36.90%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "16.55%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "16.08%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "11.73%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "7.77%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.85%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.30%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.87%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.18%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.55%" >}}
---

### 11. [Podroll](https://podroll.fm/)

Podroll was found on 0.49% of new episodes in August, growing 2.29% from last month.

Of these, 72.54% had 2 other trackers, 7.48% had 4 other trackers, 7.30% had one other tracker, 4.46% had 6 other trackers, 3.87% had 3 other trackers, 1.72% had 5 other trackers, 0.63% had 7 other trackers, 0.09% had 9 other trackers, and 0.07% had 8 other trackers.

83.17% also included Podtrac, 76.72% also included Adswizz, 15.50% also included Podscribe, 12.64% also included Magellan AI, 10.93% also included Podsights, 8.77% also included Claritas, 7.40% also included Chartable, 7.34% also included Swap.fm, 3.46% also included Spotify, 3.02% also included Podcorn, 1.38% also included OP3, 1.01% also included United Podcasters, 1.00% also included Gumshoe, 0.95% also included Podder, 0.91% also included ArtsAI, 0.53% also included Veritonic, 0.27% also included CoHost Prefix, and 0.04% also included Podkite.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "76.78%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.70%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.21%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.62%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "1.57%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.13%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.96%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.36%" >}}
9. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "0.23%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.16%" >}}
---

### 12. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.37% of new episodes in August, shrinking 5.70% from last month.

Of these, 24.08% had 2 other trackers, 19.75% had one other tracker, 17.39% had 3 other trackers, 15.18% had 4 other trackers, 13.86% had 5 other trackers, 3.18% had 6 other trackers, 1.08% had 7 other trackers, and 0.04% had 8 other trackers.

52.20% also included Podtrac, 51.44% also included Podsights, 43.53% also included Podscribe, 42.81% also included Chartable, 37.32% also included Magellan AI, 14.35% also included Adswizz, 9.73% also included Podroll, 8.47% also included Claritas, 7.43% also included ArtsAI, 3.11% also included Spotify, 1.47% also included United Podcasters, 1.43% also included Gumshoe, 1.39% also included OP3, 0.88% also included Veritonic, 0.71% also included Blubrry, 0.44% also included Podder, 0.25% also included Podcorn, and 0.02% also included Podcards.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "67.17%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "13.65%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.40%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.28%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "4.54%" >}}
6. {{< a "https://www.washingtonpost.com/" "The Washington Post" >}} {{< span "weak" "0.51%" >}}
7. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.21%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.14%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.11%" >}}
---

### 13. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.35% of new episodes in August, growing 4.35% from last month.

Of these, 17.30% had one other tracker, 10.73% had 5 other trackers, 10.07% had 6 other trackers, 6.83% had 2 other trackers, 3.80% had 3 other trackers, 3.30% had 4 other trackers, 0.13% had 9 other trackers, 0.11% had 7 other trackers, and 0.06% had 8 other trackers.

43.25% also included Podtrac, 25.56% also included Podsights, 24.64% also included Podcorn, 24.15% also included Podscribe, 21.72% also included Gumshoe, 12.23% also included Spotify, 4.72% also included Adswizz, 2.98% also included Chartable, 2.88% also included Magellan AI, 1.95% also included Podroll, 1.78% also included Podder, 1.76% also included Claritas, 1.48% also included Swap.fm, 0.95% also included Blubrry, 0.62% also included ArtsAI, 0.52% also included Podkite, 0.47% also included CoHost Prefix, 0.17% also included United Podcasters, 0.15% also included Feedpress, and 0.07% also included Zencastr.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "32.13%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "8.33%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.79%" >}}
4. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "7.77%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.67%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.21%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.34%" >}}
8. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "2.23%" >}}
9. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "2.00%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.39%" >}}
---

### 14. [Podder](https://www.podderapp.com/)

Podder was found on 0.21% of new episodes in August, growing 1.50% from last month.

Of these, 17.46% had 2 other trackers, 11.48% had one other tracker, 7.90% had 4 other trackers, 6.79% had 3 other trackers, 4.50% had 5 other trackers, 1.42% had 6 other trackers, 0.44% had 7 other trackers, 0.22% had 9 other trackers, and 0.09% had 8 other trackers.

30.86% also included Podtrac, 28.03% also included Podscribe, 17.33% also included Podsights, 14.12% also included Adswizz, 10.60% also included Magellan AI, 10.47% also included Chartable, 5.00% also included Podcorn, 4.56% also included Claritas, 3.43% also included Spotify, 2.99% also included OP3, 2.33% also included Gumshoe, 2.23% also included Podroll, 1.01% also included Blubrry, 0.94% also included ArtsAI, 0.79% also included Swap.fm, 0.22% also included Podkite, 0.22% also included CoHost Prefix, and 0.03% also included United Podcasters.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "44.01%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "17.24%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "14.66%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "8.97%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.34%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.71%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.42%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.23%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.72%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.63%" >}}
---

### 15. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.20% of new episodes in August, shrinking 10.48% from last month.

Of these, 35.42% had 4 other trackers, 19.46% had 5 other trackers, 11.89% had 3 other trackers, 11.83% had 6 other trackers, 9.20% had 7 other trackers, 9.04% had 2 other trackers, and 3.08% had one other tracker.

89.20% also included Podscribe, 76.35% also included Claritas, 65.16% also included Podtrac, 56.03% also included Magellan AI, 51.41% also included Podsights, 39.33% also included Spotify, 14.74% also included Veritonic, 13.49% also included Swap.fm, 13.37% also included Adswizz, 6.60% also included Chartable, 2.18% also included Podroll, 1.06% also included OP3, 0.96% also included Podder, 0.45% also included Blubrry, 0.35% also included United Podcasters, 0.26% also included CoHost Prefix, and 0.19% also included Gumshoe.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "28.33%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "25.96%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "18.88%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "13.30%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "9.46%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.01%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.77%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.13%" >}}
9. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.13%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.03%" >}}
---

### 16. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.14% of new episodes in August, growing 18.71% from last month.

Of these, 27.28% had 5 other trackers, 22.25% had 6 other trackers, 11.55% had 4 other trackers, 10.24% had one other tracker, 7.36% had 2 other trackers, 5.87% had 3 other trackers, 1.26% had 7 other trackers, 0.33% had 9 other trackers, and 0.14% had 8 other trackers.

65.83% also included Podscribe, 64.94% also included Podtrac, 63.64% also included Podsights, 54.00% also included OP3, 50.88% also included Podcorn, 27.84% also included Spotify, 10.66% also included Magellan AI, 10.29% also included Chartable, 5.87% also included Claritas, 3.77% also included Swap.fm, 3.49% also included Podroll, 3.45% also included Podder, 3.12% also included CoHost Prefix, 1.40% also included Veritonic, 1.26% also included Adswizz, 0.65% also included United Podcasters, 0.28% also included ArtsAI, and 0.14% also included Podkite.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "55.26%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "20.39%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "17.36%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.75%" >}}
5. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.54%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.44%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.65%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.19%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.19%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.19%" >}}
---

### 17. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.14% of new episodes in August, growing 6.56% from last month.

Of these, 20.20% had one other tracker, and 1.58% had 2 other trackers.

14.36% also included Blubrry, 4.98% also included Podtrac, 1.58% also included Podsights, 1.58% also included Chartable, 0.48% also included Podcorn, and 0.38% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "55.86%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "11.78%" >}}
3. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "6.22%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.55%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.97%" >}}
6. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "2.58%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.77%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.63%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.48%" >}}
10. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "1.15%" >}}
---

### 18. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.08% of new episodes in August, growing 7.98% from last month.

Of these, 32.59% had 5 other trackers, 24.01% had 6 other trackers, 23.84% had 7 other trackers, 10.81% had 4 other trackers, 6.60% had 3 other trackers, 0.66% had 2 other trackers, and 0.58% had one other tracker.

92.24% also included Podscribe, 88.37% also included Podsights, 83.83% also included Podtrac, 80.61% also included Magellan AI, 80.20% also included Claritas, 37.95% also included ArtsAI, 26.57% also included Chartable, 26.40% also included Spotify, 11.80% also included Adswizz, 4.13% also included Swap.fm, 3.30% also included Podroll, 2.48% also included Gumshoe, 0.50% also included United Podcasters, 0.33% also included CoHost Prefix, and 0.17% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "77.39%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "11.63%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.28%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.64%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.90%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.33%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.33%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.25%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.17%" >}}
10. {{< a "https://www.thisamericanlife.org/" "This American Life" >}} {{< span "weak" "0.08%" >}}
---

### 19. [Firstory](https://firstory.me/)

Firstory was found on 0.04% of new episodes in August, growing 1.06% from last month.

Of these, 1.66% had one other tracker.

1.66% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "100.00%" >}}
---

### 20. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.02% of new episodes in August, shrinking 0.46% from last month.

Of these, 21.07% had 3 other trackers, 19.92% had one other tracker, 14.94% had 2 other trackers, 14.56% had 4 other trackers, 12.26% had 6 other trackers, 10.73% had 5 other trackers, and 0.77% had 8 other trackers.

42.15% also included Magellan AI, 41.38% also included Podsights, 41.00% also included Podscribe, 39.08% also included Podtrac, 31.80% also included Chartable, 31.80% also included Swap.fm, 29.12% also included Podroll, 15.33% also included Claritas, 7.66% also included Adswizz, 5.36% also included Gumshoe, 4.98% also included Spotify, 4.60% also included Podcorn, 4.21% also included ArtsAI, 3.45% also included OP3, 2.30% also included Veritonic, and 0.38% also included Podder.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "51.34%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.96%" >}}
3. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "9.58%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "9.20%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.90%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.83%" >}}
7. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "3.45%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.68%" >}}
9. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "1.53%" >}}
10. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "1.15%" >}}
---

### 21. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.02% of new episodes in August, growing 10.87% from last month.

Of these, 34.32% had 4 other trackers, 20.76% had 5 other trackers, 12.29% had one other tracker, 8.05% had 2 other trackers, 2.97% had 9 other trackers, 2.54% had 6 other trackers, 1.69% had 7 other trackers, and 1.27% had 3 other trackers.

62.71% also included Podtrac, 61.44% also included Podscribe, 44.49% also included Podsights, 37.71% also included Chartable, 28.39% also included Gumshoe, 25.42% also included Claritas, 19.92% also included Spotify, 16.95% also included Magellan AI, 10.59% also included OP3, 8.47% also included Podroll, 3.39% also included ArtsAI, 2.97% also included Podcorn, 2.97% also included Podder, and 1.69% also included Veritonic.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "46.61%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "16.95%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "8.47%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "6.78%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "6.78%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "3.39%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.97%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.12%" >}}
9. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.69%" >}}
10. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.27%" >}}
---

### 22. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.01% of new episodes in August, shrinking 4.42% from last month.

Of these, 3.83% had one other tracker.

3.83% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "100.00%" >}}
---

### 23. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in August, shrinking 8.27% from last month.

Of these, 30.00% had one other tracker, 6.00% had 5 other trackers, 5.33% had 2 other trackers, and 2.00% had 8 other trackers.

24.00% also included Podtrac, 18.67% also included OP3, 10.00% also included Podsights, 8.00% also included Podcorn, 6.00% also included Blubrry, 5.33% also included Podscribe, 4.67% also included Podder, 3.33% also included Spotify, 2.67% also included Chartable, 2.00% also included Podroll, and 2.00% also included Gumshoe.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "25.33%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "15.33%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "14.00%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "12.00%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.67%" >}}
6. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "6.67%" >}}
7. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "6.00%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "6.00%" >}}
9. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "4.67%" >}}
10. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "0.67%" >}}
---

### 24. [Zencastr](https://zencastr.com/)

Zencastr was found on <0.01% of new episodes in August, shrinking 1.73% from last month.

Of these, 6.90% had one other tracker, and 6.90% had 2 other trackers.

6.90% also included OP3, 6.90% also included Podcorn, and 6.90% also included Chartable.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "29.31%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "18.97%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "18.97%" >}}
4. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "15.52%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "13.79%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.45%" >}}
---

### 25. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in August, shrinking 12.86% from last month.

Of these, 34.88% had one other tracker.

30.23% also included Podtrac, and 4.65% also included Chartable.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "46.51%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "25.58%" >}}
3. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "13.95%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.65%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.65%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.65%" >}}
---

### 26. [Podcards](https://pod.cards/)

Podcards was found on <0.01% of new episodes in August, growing 3.35% from last month.

Of these, 100.00% had 5 other trackers.

100.00% also included Podscribe, 100.00% also included Swap.fm, 100.00% also included Podtrac, 100.00% also included Podsights, and 100.00% also included Chartable.

For episodes that used Podcards, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "100.00%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2025-08.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
