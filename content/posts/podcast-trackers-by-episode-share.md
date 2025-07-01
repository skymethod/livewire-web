---
title: "Top Podcast Tracking Services by Episode Share (June 2025)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2025-06.png
date: 2025-07-01T16:51:00-04:00
lastmod: 2025-07-01T16:51:00-04:00
draft: false
rssrevision: 2025-06
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.6 million in June 2025), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in June, how many
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
Month	Podtrac	Adswizz	Podsights	Podscribe	Blubrry	Chartable	Podcorn	Spotify	Podroll	Audiotakes	OP3	Swap.fm	Claritas	ArtsAI	Podder	Feedpress	Gumshoe	Veritonic	RSS Insight	Médiamétrie	United Podcasters	CoHost Prefix	Podkite	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	1.00	1.16		2.07	4.06	2.09									0.32				0.42										1.61
Oct 2021	4.05	1.01	1.20		2.11	4.09	2.13									0.34				0.54										1.61
Nov 2021	4.07	1.02	1.25		2.01	4.30	2.14									0.32				0.57										0.59
Dec 2021	4.06	1.24	1.19		1.57	4.42	2.27									0.19				0.59										
Jan 2022	4.11	1.41	1.21		1.56	4.45	2.31									0.16				0.63										
Feb 2022	4.15	1.44	1.25		1.53	4.48	2.38									0.17				0.58										
Mar 2022	4.37	1.51	1.34		1.56	4.72	2.40									0.17				0.53										
Apr 2022	4.44	1.49	1.33		1.55	4.71	2.33									0.16				0.51										
May 2022	4.49	1.58	1.41		1.48	4.87	2.26									0.17				0.56										
Jun 2022	4.75	1.77	1.54		1.50	5.10	2.06									0.21				0.62							0.02			
Jul 2022	4.70	1.89	1.50		1.50	5.10	2.16									0.25				0.54							0.02			
Aug 2022	4.83	2.08	1.73		1.51	5.26	2.45							0.10		0.20				0.41							0.01			
Sep 2022	7.53	2.26	1.74	0.02	1.49	5.40	2.45						0.01	0.09		0.21				0.52			0.01				0.02	0.02		
Oct 2022	8.24	2.35	1.81	0.07	1.61	5.48	2.51				0.03		0.02	0.10		0.18				0.50			0.01	0.01			0.02	0.04		
Nov 2022	8.11	2.37	2.03	0.15	1.62	5.62	2.43				0.04		0.03	0.10	0.01	0.18				0.50			0.01	0.01			0.02	0.05		
Dec 2022	8.01	2.32	1.81	0.03	1.61	5.54	2.05				0.05		0.02	0.05	0.04	0.18				0.49			0.01	0.01		0.01	0.02	0.05		
Jan 2023	7.85	2.35	1.88	0.20	1.61	5.56	2.15				0.07		0.06	0.10	0.11	0.18				0.54			0.01	0.01		0.01	0.02	0.06		
Feb 2023	7.58	2.29	1.92	0.21	1.62	5.51	2.30				0.07		0.07	0.10	0.11	0.19				0.49			0.01	0.01		0.01	0.02	0.06	0.03	
Mar 2023	7.79	2.25	2.03	0.21	1.53	5.53	2.22		0.04		0.08		0.07	0.11	0.11	0.18		0.04		0.45			0.01	0.01		0.01	0.02	0.06		
Apr 2023	7.66	2.26	2.00	0.21	1.67	5.43	2.20		0.06		0.09		0.07	0.11	0.15	0.17	0.08	0.05		0.45			0.01	0.01		0.01	0.01			
May 2023	7.58	2.27	2.04	0.24	1.67	5.59	2.28		0.09		0.09		0.08	0.11	0.15	0.19	0.07	0.05		0.45			0.01	0.01	0.01	0.01	0.01			
Jun 2023	8.22	2.39	2.23	0.26	1.64	5.83	1.86		0.10		0.09		0.07	0.12	0.15	0.19	0.08	0.05		0.51			0.01	0.01	0.01	0.01	0.01			
Jul 2023	8.60	2.38	2.52	0.27	1.53	5.95	1.17	0.01	0.14		0.08		0.07	0.11	0.14	0.18	0.06	0.06		0.55			0.01	0.01	0.01	0.01	0.01			
Aug 2023	9.19	2.72	2.76	0.36	1.58	6.43	1.23	0.03	0.16	0.04	0.11		0.08	0.12	0.15	0.17	0.07	0.07		0.53			0.01	0.01	0.02	0.01				
Sep 2023	8.46	2.49	2.47	0.37	1.39	5.77	1.10	0.05	0.13	0.05	0.10		0.10	0.12	0.15	0.16	0.07	0.06		0.58			0.01	0.01	0.02	0.01				
Oct 2023	7.90	2.29	2.28	0.39	1.37	5.54	1.11	0.08	0.12	0.05	0.10		0.10	0.12	0.16	0.16	0.08	0.06		0.50			0.01	0.02	0.03	0.01				
Nov 2023	7.65	2.25	2.33	0.47	1.45	5.59	1.14	0.11	0.12	0.06	0.13		0.11	0.12	0.16	0.17	0.10	0.06		0.33			0.01	0.01	0.03					
Dec 2023	7.48	2.20	2.19	0.54	1.53	5.60	1.12	0.12	0.12	0.06	0.11		0.11	0.12	0.16	0.16	0.09	0.06		0.33			0.01	0.01	0.03					
Jan 2024	7.64	2.37	2.21	0.65	1.55	5.61	1.17	0.15	0.11	0.08	0.13		0.12	0.14	0.16	0.17	0.10	0.06		0.25	0.01		0.01	0.01	0.01					
Feb 2024	7.69	2.38	2.22	0.69	1.52	5.58	1.21	0.22	0.12	0.09	0.16		0.13	0.13	0.17	0.17	0.11	0.06		0.22	0.01		0.01	0.01						
Mar 2024	9.01	2.53	2.19	0.69	1.54	5.46	1.14	0.25	0.12	0.09	0.14		0.14	0.12	0.16	0.16	0.10	0.06		0.22	0.01		0.01	0.01						
Apr 2024	10.78	2.53	2.16	0.73	1.51	5.47	1.24	0.27	0.34	0.07	0.18		0.15	0.13	0.17	0.15	0.11	0.07		0.19	0.01	0.01	0.01	0.01						
May 2024	11.59	2.75	2.24	0.83	1.50	5.63	1.20	0.30	0.36	0.06	0.18		0.15	0.14	0.16	0.15	0.11	0.07		0.09	0.01	0.01	0.01	0.01						
Jun 2024	11.54	2.88	2.34	0.91	1.52	6.06	0.71	0.32	0.37	0.07	0.20	0.03	0.16	0.16	0.15	0.15	0.11	0.07		0.10	0.01	0.01	0.01	0.01						
Jul 2024	12.34	2.83	2.45	1.01	1.65	6.80	0.71	0.34	0.43	0.09	0.20	0.06	0.18	0.17	0.15	0.15	0.12	0.07		0.09	0.01	0.01	0.01	0.01						
Aug 2024	14.22	2.96	2.48	1.11	1.70	6.72	0.81	0.35	0.45	0.11	0.19	0.12	0.18	0.18	0.35	0.14	0.12	0.08		0.08	0.01	0.01	0.01	0.01						
Sep 2024	12.95	3.13	2.26	1.18	1.44	5.99	0.72	0.35	0.44	0.13	0.24	0.12	0.18	0.18	0.42	0.15	0.13	0.08		0.07	0.01	0.01	0.01	0.01						
Oct 2024	12.24	3.23	2.35	1.23	1.53	5.49	0.66	0.40	0.43	0.14	0.27	0.17	0.19	0.18	0.39	0.14	0.12	0.09		0.09	0.01	0.01	0.01	0.01						
Nov 2024	11.86	3.21	2.31	1.27	1.52	4.66	0.63	0.44	0.43	0.14	0.29	0.19	0.21	0.17	0.41	0.11	0.12	0.08		0.10	0.01	0.01	0.01	0.01						
Dec 2024	12.56	3.06	2.13	1.29	1.40	2.29	0.62	0.45	0.43	0.15	0.29	0.24	0.21	0.18	0.54	0.09	0.12	0.08		0.09	0.01	0.01	0.01	0.01						
Jan 2025	12.62	2.92	1.73	1.31	1.36	1.54	0.66	0.41	0.46	0.16	0.34	0.27	0.21	0.19	0.54	0.12	0.13	0.08		0.04	0.01	0.01	0.01	0.01						
Feb 2025	12.47	2.74	1.70	1.25	1.45	1.43	0.66	0.36	0.46	0.16	0.33	0.28	0.22	0.18	0.48	0.14	0.12	0.08		0.01	0.01	0.01	0.01	0.01						
Mar 2025	12.18	2.87	1.51	1.28	1.25	1.18	0.67	0.33	0.47	0.25	0.33	0.27	0.21	0.18	0.36	0.14	0.13	0.07	0.04	0.01	0.01	0.01	0.01	0.01						
Apr 2025	12.35	2.97	1.64	1.53	1.26	1.28	0.68	0.44	0.48	0.41	0.34	0.30	0.23	0.19	0.33	0.13	0.12	0.08	0.03	0.02	0.01	0.01	0.01	0.01						
May 2025	12.48	2.97	1.74	1.61	1.40	1.31	0.64	0.46	0.46	0.40	0.39	0.33	0.24	0.20	0.22	0.13	0.12	0.07	0.05	0.02	0.02	0.01	0.01							
Jun 2025	12.99	2.73	1.70	1.65	1.34	1.30	0.65	0.47	0.46	0.40	0.39	0.35	0.26	0.21	0.20	0.13	0.12	0.07	0.04	0.02	0.02	0.01	0.01							
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} have historically been the top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podsights	Podscribe	Blubrry	Podcorn	Spotify	Podroll	Audiotakes	OP3	Swap.fm	Claritas	ArtsAI	Podder	Feedpress	Gumshoe	Veritonic	RSS Insight	Médiamétrie	United Podcasters	CoHost Prefix	Podkite	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	1.00	1.16		2.07	2.09									0.32				0.42										1.61
Oct 2021	1.01	1.20		2.11	2.13									0.34				0.54										1.61
Nov 2021	1.02	1.25		2.01	2.14									0.32				0.57										0.59
Dec 2021	1.24	1.19		1.57	2.27									0.19				0.59										
Jan 2022	1.41	1.21		1.56	2.31									0.16				0.63										
Feb 2022	1.44	1.25		1.53	2.38									0.17				0.58										
Mar 2022	1.51	1.34		1.56	2.40									0.17				0.53										
Apr 2022	1.49	1.33		1.55	2.33									0.16				0.51										
May 2022	1.58	1.41		1.48	2.26									0.17				0.56										
Jun 2022	1.77	1.54		1.50	2.06									0.21				0.62							0.02			
Jul 2022	1.89	1.50		1.50	2.16									0.25				0.54							0.02			
Aug 2022	2.08	1.73		1.51	2.45							0.10		0.20				0.41							0.01			
Sep 2022	2.26	1.74	0.02	1.49	2.45						0.01	0.09		0.21				0.52			0.01				0.02	0.02		
Oct 2022	2.35	1.81	0.07	1.61	2.51				0.03		0.02	0.10		0.18				0.50			0.01	0.01			0.02	0.04		
Nov 2022	2.37	2.03	0.15	1.62	2.43				0.04		0.03	0.10	0.01	0.18				0.50			0.01	0.01			0.02	0.05		
Dec 2022	2.32	1.81	0.03	1.61	2.05				0.05		0.02	0.05	0.04	0.18				0.49			0.01	0.01		0.01	0.02	0.05		
Jan 2023	2.35	1.88	0.20	1.61	2.15				0.07		0.06	0.10	0.11	0.18				0.54			0.01	0.01		0.01	0.02	0.06		
Feb 2023	2.29	1.92	0.21	1.62	2.30				0.07		0.07	0.10	0.11	0.19				0.49			0.01	0.01		0.01	0.02	0.06	0.03	
Mar 2023	2.25	2.03	0.21	1.53	2.22		0.04		0.08		0.07	0.11	0.11	0.18		0.04		0.45			0.01	0.01		0.01	0.02	0.06		
Apr 2023	2.26	2.00	0.21	1.67	2.20		0.06		0.09		0.07	0.11	0.15	0.17	0.08	0.05		0.45			0.01	0.01		0.01	0.01			
May 2023	2.27	2.04	0.24	1.67	2.28		0.09		0.09		0.08	0.11	0.15	0.19	0.07	0.05		0.45			0.01	0.01	0.01	0.01	0.01			
Jun 2023	2.39	2.23	0.26	1.64	1.86		0.10		0.09		0.07	0.12	0.15	0.19	0.08	0.05		0.51			0.01	0.01	0.01	0.01	0.01			
Jul 2023	2.38	2.52	0.27	1.53	1.17	0.01	0.14		0.08		0.07	0.11	0.14	0.18	0.06	0.06		0.55			0.01	0.01	0.01	0.01	0.01			
Aug 2023	2.72	2.76	0.36	1.58	1.23	0.03	0.16	0.04	0.11		0.08	0.12	0.15	0.17	0.07	0.07		0.53			0.01	0.01	0.02	0.01				
Sep 2023	2.49	2.47	0.37	1.39	1.10	0.05	0.13	0.05	0.10		0.10	0.12	0.15	0.16	0.07	0.06		0.58			0.01	0.01	0.02	0.01				
Oct 2023	2.29	2.28	0.39	1.37	1.11	0.08	0.12	0.05	0.10		0.10	0.12	0.16	0.16	0.08	0.06		0.50			0.01	0.02	0.03	0.01				
Nov 2023	2.25	2.33	0.47	1.45	1.14	0.11	0.12	0.06	0.13		0.11	0.12	0.16	0.17	0.10	0.06		0.33			0.01	0.01	0.03					
Dec 2023	2.20	2.19	0.54	1.53	1.12	0.12	0.12	0.06	0.11		0.11	0.12	0.16	0.16	0.09	0.06		0.33			0.01	0.01	0.03					
Jan 2024	2.37	2.21	0.65	1.55	1.17	0.15	0.11	0.08	0.13		0.12	0.14	0.16	0.17	0.10	0.06		0.25	0.01		0.01	0.01	0.01					
Feb 2024	2.38	2.22	0.69	1.52	1.21	0.22	0.12	0.09	0.16		0.13	0.13	0.17	0.17	0.11	0.06		0.22	0.01		0.01	0.01						
Mar 2024	2.53	2.19	0.69	1.54	1.14	0.25	0.12	0.09	0.14		0.14	0.12	0.16	0.16	0.10	0.06		0.22	0.01		0.01	0.01						
Apr 2024	2.53	2.16	0.73	1.51	1.24	0.27	0.34	0.07	0.18		0.15	0.13	0.17	0.15	0.11	0.07		0.19	0.01	0.01	0.01	0.01						
May 2024	2.75	2.24	0.83	1.50	1.20	0.30	0.36	0.06	0.18		0.15	0.14	0.16	0.15	0.11	0.07		0.09	0.01	0.01	0.01	0.01						
Jun 2024	2.88	2.34	0.91	1.52	0.71	0.32	0.37	0.07	0.20	0.03	0.16	0.16	0.15	0.15	0.11	0.07		0.10	0.01	0.01	0.01	0.01						
Jul 2024	2.83	2.45	1.01	1.65	0.71	0.34	0.43	0.09	0.20	0.06	0.18	0.17	0.15	0.15	0.12	0.07		0.09	0.01	0.01	0.01	0.01						
Aug 2024	2.96	2.48	1.11	1.70	0.81	0.35	0.45	0.11	0.19	0.12	0.18	0.18	0.35	0.14	0.12	0.08		0.08	0.01	0.01	0.01	0.01						
Sep 2024	3.13	2.26	1.18	1.44	0.72	0.35	0.44	0.13	0.24	0.12	0.18	0.18	0.42	0.15	0.13	0.08		0.07	0.01	0.01	0.01	0.01						
Oct 2024	3.23	2.35	1.23	1.53	0.66	0.40	0.43	0.14	0.27	0.17	0.19	0.18	0.39	0.14	0.12	0.09		0.09	0.01	0.01	0.01	0.01						
Nov 2024	3.21	2.31	1.27	1.52	0.63	0.44	0.43	0.14	0.29	0.19	0.21	0.17	0.41	0.11	0.12	0.08		0.10	0.01	0.01	0.01	0.01						
Dec 2024	3.06	2.13	1.29	1.40	0.62	0.45	0.43	0.15	0.29	0.24	0.21	0.18	0.54	0.09	0.12	0.08		0.09	0.01	0.01	0.01	0.01						
Jan 2025	2.92	1.73	1.31	1.36	0.66	0.41	0.46	0.16	0.34	0.27	0.21	0.19	0.54	0.12	0.13	0.08		0.04	0.01	0.01	0.01	0.01						
Feb 2025	2.74	1.70	1.25	1.45	0.66	0.36	0.46	0.16	0.33	0.28	0.22	0.18	0.48	0.14	0.12	0.08		0.01	0.01	0.01	0.01	0.01						
Mar 2025	2.87	1.51	1.28	1.25	0.67	0.33	0.47	0.25	0.33	0.27	0.21	0.18	0.36	0.14	0.13	0.07	0.04	0.01	0.01	0.01	0.01	0.01						
Apr 2025	2.97	1.64	1.53	1.26	0.68	0.44	0.48	0.41	0.34	0.30	0.23	0.19	0.33	0.13	0.12	0.08	0.03	0.02	0.01	0.01	0.01	0.01						
May 2025	2.97	1.74	1.61	1.40	0.64	0.46	0.46	0.40	0.39	0.33	0.24	0.20	0.22	0.13	0.12	0.07	0.05	0.02	0.02	0.01	0.01							
Jun 2025	2.73	1.70	1.65	1.34	0.65	0.47	0.46	0.40	0.39	0.35	0.26	0.21	0.20	0.13	0.12	0.07	0.04	0.02	0.02	0.01	0.01							
{{< /graph >}}

---

### Overall

At least one tracker was found on 18.63% of new episodes in June, growing 0.95% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "45.18%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.37%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.58%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.88%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.37%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.53%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.15%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.38%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.27%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.22%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of June 2025.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 12.99% of new episodes in June, growing 4.04% from last month.

Of these, 9.87% had one other tracker, 7.41% had 2 other trackers, 1.31% had 3 other trackers, 1.30% had 4 other trackers, 0.93% had 5 other trackers, 0.49% had 6 other trackers, 0.19% had 7 other trackers, 0.03% had 8 other trackers, and <0.01% had 9 other trackers.

8.45% also included Podsights, 6.17% also included Adswizz, 5.97% also included Podscribe, 5.22% also included Chartable, 2.97% also included Podroll, 2.33% also included Magellan AI, 2.31% also included Spotify, 1.54% also included Swap.fm, 1.31% also included Claritas, 1.23% also included Podcorn, 1.13% also included OP3, 1.11% also included Blubrry, 0.98% also included ArtsAI, 0.67% also included Audiotakes, 0.52% also included Gumshoe, 0.47% also included Podder, 0.43% also included Veritonic, 0.08% also included CoHost Prefix, 0.05% also included United Podcasters, 0.05% also included Feedpress, 0.02% also included Podkite, 0.01% also included Médiamétrie, <0.01% also included AdBarker, and <0.01% also included Zencastr.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "64.69%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "8.54%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.52%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.15%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.05%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.52%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.58%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.93%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.68%" >}}
10. {{< a "https://portal.rozhlas.cz/" "Cesky rozhlas" >}} {{< span "weak" "0.57%" >}}
---

### 2. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.73% of new episodes in June, shrinking 7.98% from last month.

Of these, 16.72% had 2 other trackers, 15.23% had one other tracker, 8.90% had 3 other trackers, 2.52% had 4 other trackers, 1.36% had 5 other trackers, 0.78% had 6 other trackers, 0.33% had 7 other trackers, and 0.10% had 8 other trackers.

29.31% also included Podtrac, 15.99% also included Podscribe, 13.56% also included Magellan AI, 12.98% also included Podroll, 9.48% also included Audiotakes, 3.68% also included Podsights, 2.93% also included Spotify, 2.79% also included Swap.fm, 2.64% also included Claritas, 1.46% also included ArtsAI, 1.35% also included Blubrry, 1.22% also included Chartable, 0.87% also included Podder, 0.69% also included OP3, 0.65% also included Veritonic, 0.28% also included Podcorn, 0.14% also included Gumshoe, and 0.06% also included United Podcasters.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "61.84%" >}}
2. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "6.18%" >}}
3. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "5.34%" >}}
4. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "5.19%" >}}
5. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "5.03%" >}}
6. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "3.32%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.95%" >}}
8. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "2.85%" >}}
9. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.38%" >}}
10. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "0.89%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 2.55% of new episodes in June, shrinking 1.92% from last month.

Of these, 57.08% also included Podtrac, 30.41% also included Podscribe, 15.52% also included Magellan AI, 8.66% also included Claritas, 8.15% also included Adswizz, 8.14% also included Swap.fm, 6.42% also included ArtsAI, 4.99% also included Audiotakes, 3.26% also included Podcorn, 3.08% also included Gumshoe, 2.99% also included Podroll, 2.87% also included OP3, 2.56% also included Veritonic, 1.48% also included Podder, 0.45% also included Blubrry, 0.34% also included United Podcasters, 0.28% also included CoHost Prefix, 0.07% also included Feedpress, 0.04% also included Podkite, 0.03% also included Firstory, 0.02% also included Zencastr, and <0.01% also included AdBarker.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "57.63%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "16.13%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.56%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.05%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.71%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.86%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.59%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.39%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.08%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.95%" >}}
---

### 3. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.70% of new episodes in June, shrinking 2.10% from last month.

Of these, 33.35% had one other tracker, 24.00% had 2 other trackers, 11.27% had 4 other trackers, 9.20% had 3 other trackers, 7.06% had 5 other trackers, 3.37% had 6 other trackers, 1.09% had 7 other trackers, 0.19% had 8 other trackers, and 0.01% had 9 other trackers.

64.54% also included Podtrac, 41.73% also included Chartable, 32.15% also included Podscribe, 17.64% also included Magellan AI, 10.27% also included Swap.fm, 7.36% also included Claritas, 6.35% also included ArtsAI, 5.91% also included Adswizz, 5.67% also included Audiotakes, 5.50% also included Spotify, 4.25% also included Podcorn, 3.90% also included OP3, 3.86% also included Gumshoe, 3.29% also included Veritonic, 3.04% also included Podroll, 1.96% also included Podder, 0.51% also included Blubrry, 0.38% also included CoHost Prefix, 0.37% also included United Podcasters, 0.11% also included Feedpress, 0.03% also included Podkite, and 0.01% also included Zencastr.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "62.79%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.75%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.05%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.75%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.10%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.56%" >}}
7. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.43%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.14%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.02%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.66%" >}}
---

### 4. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 1.65% of new episodes in June, growing 3.00% from last month.

Of these, 23.16% had 3 other trackers, 21.07% had one other tracker, 16.14% had 4 other trackers, 12.66% had 2 other trackers, 9.62% had 5 other trackers, 4.49% had 6 other trackers, 1.54% had 7 other trackers, 0.20% had 8 other trackers, and 0.01% had 9 other trackers.

46.90% also included Podtrac, 44.49% also included Magellan AI, 33.05% also included Podsights, 26.41% also included Adswizz, 24.21% also included Audiotakes, 16.89% also included Chartable, 16.56% also included Spotify, 14.95% also included Claritas, 11.42% also included ArtsAI, 8.57% also included Swap.fm, 4.62% also included Podcorn, 4.54% also included Podroll, 4.18% also included Gumshoe, 3.68% also included OP3, 3.60% also included Veritonic, 2.81% also included Podder, 0.39% also included United Podcasters, 0.39% also included CoHost Prefix, 0.27% also included Blubrry, 0.02% also included Podkite, 0.01% also included Zencastr, and <0.01% also included AdBarker.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "38.83%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "24.89%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.47%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.80%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.61%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.66%" >}}
7. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "3.14%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.05%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.34%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.39%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.34% of new episodes in June, shrinking 4.30% from last month.

Of these, 14.72% had one other tracker, 0.68% had 2 other trackers, 0.18% had 3 other trackers, 0.15% had 4 other trackers, 0.03% had 6 other trackers, and 0.02% had 5 other trackers.

10.80% also included Podtrac, 2.75% also included Adswizz, 1.34% also included Feedpress, 0.64% also included Podsights, 0.50% also included OP3, 0.33% also included Podscribe, 0.25% also included Podcorn, 0.22% also included Swap.fm, 0.17% also included Podder, 0.15% also included Chartable, 0.12% also included Spotify, 0.11% also included Magellan AI, 0.05% also included Podkite, 0.04% also included ArtsAI, 0.01% also included Audiotakes, 0.01% also included Claritas, and 0.01% also included Veritonic.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "46.93%" >}}
2. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "4.58%" >}}
3. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "4.04%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.59%" >}}
5. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "2.11%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.78%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.59%" >}}
8. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "0.93%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.68%" >}}
10. {{< a "https://cloud.google.com/" "Google Cloud" >}} {{< span "weak" "0.68%" >}}
---

### 6. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 1.30% of new episodes in June, shrinking 0.72% from last month.

Of these, 34.96% had 2 other trackers, 21.78% had one other tracker, 8.01% had 4 other trackers, 6.82% had 3 other trackers, 3.93% had 5 other trackers, 2.49% had 6 other trackers, 0.25% had 7 other trackers, and 0.02% had 8 other trackers.

54.62% also included Podsights, 52.18% also included Podtrac, 21.51% also included Podscribe, 11.29% also included Spotify, 11.23% also included Magellan AI, 10.84% also included Swap.fm, 4.63% also included Claritas, 2.73% also included Podroll, 2.56% also included Adswizz, 1.58% also included Podder, 1.47% also included Veritonic, 1.13% also included ArtsAI, 1.09% also included Gumshoe, 0.97% also included Audiotakes, 0.89% also included Podcorn, 0.74% also included OP3, 0.46% also included CoHost Prefix, 0.38% also included United Podcasters, 0.16% also included Blubrry, 0.14% also included Feedpress, 0.06% also included Firstory, 0.04% also included Zencastr, 0.02% also included Podkite, and 0.01% also included AdBarker.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "85.03%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.11%" >}}
3. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.12%" >}}
4. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.54%" >}}
5. {{< a "https://cloud.google.com/" "Google Cloud" >}} {{< span "weak" "0.47%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.42%" >}}
7. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.41%" >}}
8. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "0.34%" >}}
9. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.24%" >}}
10. {{< a "https://podetize.com/" "Podetize" >}} {{< span "weak" "0.23%" >}}
---

### 7. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.99% of new episodes in June, growing 3.91% from last month.

Of these, 28.43% had 3 other trackers, 18.31% had 4 other trackers, 10.76% had 5 other trackers, 7.39% had 2 other trackers, 6.93% had one other tracker, 6.46% had 6 other trackers, 2.36% had 7 other trackers, and 0.28% had 8 other trackers.

74.31% also included Podscribe, 37.40% also included Adswizz, 32.64% also included Audiotakes, 30.56% also included Podtrac, 30.28% also included Podsights, 20.91% also included Claritas, 14.97% also included Spotify, 14.73% also included Chartable, 11.94% also included ArtsAI, 9.02% also included Swap.fm, 5.59% also included Veritonic, 4.60% also included Podroll, 1.76% also included Podder, 1.32% also included Gumshoe, 0.87% also included OP3, 0.36% also included United Podcasters, 0.15% also included Blubrry, 0.09% also included Podcorn, and 0.02% also included CoHost Prefix.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "34.71%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "25.17%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "13.02%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.88%" >}}
5. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "6.68%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.31%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.26%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "2.26%" >}}
9. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.35%" >}}
10. {{< a "https://www.americanpublicmedia.org/" "American Public Media" >}} {{< span "weak" "1.14%" >}}
---

### 8. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.65% of new episodes in June, growing 1.32% from last month.

Of these, 11.73% had one other tracker, 5.70% had 2 other trackers, 5.66% had 5 other trackers, 2.48% had 4 other trackers, 1.77% had 3 other trackers, 1.24% had 6 other trackers, 0.10% had 7 other trackers, 0.08% had 8 other trackers, and 0.04% had 9 other trackers.

24.52% also included Podtrac, 11.73% also included Podscribe, 11.11% also included OP3, 11.09% also included Podsights, 7.55% also included Gumshoe, 2.19% also included Podroll, 2.19% also included Spotify, 1.78% also included Chartable, 1.18% also included Podder, 1.17% also included Adswizz, 0.51% also included Blubrry, 0.16% also included Swap.fm, 0.14% also included Magellan AI, 0.13% also included United Podcasters, 0.12% also included Feedpress, 0.08% also included Podkite, 0.08% also included CoHost Prefix, 0.08% also included Zencastr, 0.01% also included AdBarker, and 0.01% also included Claritas.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "22.44%" >}}
2. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "12.15%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "11.79%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "11.26%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.56%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "7.50%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.90%" >}}
8. {{< a "https://www.wideorbit.com/" "WideOrbit" >}} {{< span "weak" "5.47%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.07%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.22%" >}}
---

### 9. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.47% of new episodes in June, growing 2.74% from last month.

Of these, 31.66% had 2 other trackers, 14.00% had 4 other trackers, 10.74% had 5 other trackers, 10.30% had 6 other trackers, 7.44% had one other tracker, 7.42% had 3 other trackers, 4.39% had 7 other trackers, 0.63% had 8 other trackers, and 0.05% had 9 other trackers.

63.57% also included Podtrac, 58.04% also included Podscribe, 31.42% also included Magellan AI, 31.09% also included Chartable, 28.23% also included Claritas, 19.83% also included Podsights, 18.07% also included ArtsAI, 16.98% also included Adswizz, 9.31% also included Audiotakes, 5.62% also included Veritonic, 4.51% also included Podroll, 3.14% also included OP3, 3.12% also included Gumshoe, 3.02% also included Podcorn, 2.69% also included Swap.fm, 1.39% also included Podder, 0.35% also included Blubrry, 0.29% also included United Podcasters, 0.10% also included CoHost Prefix, and 0.05% also included Podkite.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "41.53%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "15.97%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "15.95%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "11.62%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.86%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.85%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.55%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.40%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.23%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.73%" >}}
---

### 10. [Podroll](https://podroll.fm/)

Podroll was found on 0.46% of new episodes in June, growing 0.50% from last month.

Of these, 71.84% had 2 other trackers, 7.35% had 4 other trackers, 7.29% had one other tracker, 4.81% had 6 other trackers, 3.68% had 3 other trackers, 1.82% had 5 other trackers, 0.74% had 7 other trackers, 0.12% had 8 other trackers, and 0.05% had 9 other trackers.

83.99% also included Podtrac, 77.16% also included Adswizz, 16.34% also included Podscribe, 11.25% also included Podsights, 9.92% also included Magellan AI, 7.73% also included Chartable, 6.57% also included Swap.fm, 4.88% also included Audiotakes, 4.63% also included Spotify, 4.55% also included Claritas, 3.10% also included Podcorn, 1.64% also included OP3, 1.09% also included ArtsAI, 0.93% also included United Podcasters, 0.89% also included Gumshoe, 0.78% also included Podder, 0.32% also included Veritonic, and 0.31% also included CoHost Prefix.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "77.26%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.42%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.43%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.25%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "1.66%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.98%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.97%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.44%" >}}
9. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "0.20%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.13%" >}}
---

### 11. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.40% of new episodes in June, growing 1.52% from last month.

Of these, 63.38% had 3 other trackers, 20.41% had 4 other trackers, 6.79% had 5 other trackers, 6.17% had 2 other trackers, 1.74% had 6 other trackers, 0.77% had one other tracker, and 0.12% had 7 other trackers.

99.06% also included Podscribe, 79.95% also included Magellan AI, 64.09% also included Adswizz, 23.83% also included Podsights, 21.50% also included Podtrac, 14.26% also included ArtsAI, 10.87% also included Spotify, 5.55% also included Podroll, 3.11% also included Chartable, 2.51% also included Swap.fm, 2.15% also included Veritonic, 1.29% also included Gumshoe, 0.83% also included Podder, 0.51% also included OP3, 0.45% also included United Podcasters, 0.12% also included Claritas, and 0.03% also included Blubrry.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "64.53%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "14.27%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.87%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.04%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.51%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.16%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.82%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.39%" >}}
9. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.39%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.02%" >}}
---

### 12. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.39% of new episodes in June, shrinking 1.72% from last month.

Of these, 20.70% had one other tracker, 9.91% had 5 other trackers, 7.74% had 2 other trackers, 3.18% had 3 other trackers, 3.03% had 4 other trackers, 2.45% had 6 other trackers, 0.49% had 7 other trackers, 0.08% had 8 other trackers, and 0.06% had 9 other trackers.

37.93% also included Podtrac, 18.74% also included Podcorn, 17.18% also included Podsights, 15.77% also included Podscribe, 13.84% also included Gumshoe, 4.89% also included Adswizz, 3.83% also included Spotify, 2.50% also included Chartable, 2.23% also included Magellan AI, 1.95% also included Podroll, 1.74% also included Blubrry, 1.73% also included Podder, 1.31% also included Swap.fm, 0.87% also included Claritas, 0.71% also included ArtsAI, 0.54% also included Audiotakes, 0.41% also included CoHost Prefix, 0.29% also included Podkite, 0.13% also included United Podcasters, 0.11% also included Feedpress, and 0.06% also included Zencastr.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "22.89%" >}}
2. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "18.04%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "6.70%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.26%" >}}
5. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "3.85%" >}}
6. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "3.75%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.44%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.07%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.91%" >}}
10. {{< a "https://radiolaser.fr/" "Radio Laser" >}} {{< span "weak" "1.87%" >}}
---

### 13. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.35% of new episodes in June, growing 8.59% from last month.

Of these, 27.99% had 2 other trackers, 16.36% had 4 other trackers, 16.10% had one other tracker, 15.47% had 3 other trackers, 12.38% had 5 other trackers, 2.19% had 6 other trackers, 1.29% had 7 other trackers, and 0.07% had 8 other trackers.

56.23% also included Podtrac, 49.19% also included Podsights, 39.92% also included Podscribe, 39.68% also included Chartable, 25.18% also included Magellan AI, 21.44% also included Adswizz, 9.85% also included ArtsAI, 8.51% also included Podroll, 6.05% also included Claritas, 3.58% also included Spotify, 2.86% also included Audiotakes, 1.43% also included OP3, 1.40% also included United Podcasters, 1.10% also included Gumshoe, 0.83% also included Blubrry, 0.62% also included Veritonic, 0.33% also included Podder, 0.29% also included Podcorn, and 0.07% also included Zencastr.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "59.27%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "21.32%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.18%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.58%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "4.31%" >}}
6. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.17%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.16%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.02%" >}}
---

### 14. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.26% of new episodes in June, growing 8.54% from last month.

Of these, 29.32% had 4 other trackers, 24.17% had 5 other trackers, 21.64% had 6 other trackers, 9.80% had 3 other trackers, 8.82% had 7 other trackers, 2.86% had 2 other trackers, 1.45% had one other tracker, and 1.07% had 8 other trackers.

96.45% also included Podscribe, 80.76% also included Magellan AI, 66.13% also included Podtrac, 51.94% also included Spotify, 48.80% also included Podsights, 40.02% also included ArtsAI, 28.15% also included Adswizz, 23.43% also included Chartable, 17.93% also included Veritonic, 8.37% also included Swap.fm, 8.15% also included Podroll, 1.33% also included Podder, 1.31% also included OP3, 1.03% also included Gumshoe, 0.50% also included CoHost Prefix, 0.33% also included United Podcasters, 0.19% also included Audiotakes, 0.05% also included Blubrry, and 0.02% also included Podcorn.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "37.88%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "27.99%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "21.19%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.51%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.13%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.57%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.21%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.19%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.17%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.10%" >}}
---

### 15. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.21% of new episodes in June, growing 7.28% from last month.

Of these, 33.57% had 4 other trackers, 22.46% had 5 other trackers, 11.61% had 2 other trackers, 10.41% had 7 other trackers, 10.21% had 6 other trackers, 7.76% had 3 other trackers, 2.60% had one other tracker, and 1.31% had 8 other trackers.

90.14% also included Podscribe, 60.66% also included Podtrac, 56.43% also included Magellan AI, 51.53% also included Podsights, 48.96% also included Claritas, 40.68% also included Spotify, 27.50% also included Audiotakes, 19.01% also included Adswizz, 16.68% also included Swap.fm, 16.39% also included Veritonic, 7.00% also included Chartable, 2.39% also included Podroll, 1.31% also included OP3, 0.41% also included United Podcasters, 0.35% also included Podder, 0.29% also included Gumshoe, 0.26% also included Blubrry, and 0.23% also included CoHost Prefix.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.22%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "26.45%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "18.78%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "14.29%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "8.54%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.04%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.26%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.23%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.15%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.03%" >}}
---

### 16. [Podder](https://www.podderapp.com/)

Podder was found on 0.20% of new episodes in June, shrinking 8.82% from last month.

Of these, 16.66% had 2 other trackers, 11.79% had one other tracker, 7.02% had 3 other trackers, 6.99% had 4 other trackers, 3.53% had 5 other trackers, 1.06% had 6 other trackers, 0.15% had 8 other trackers, and 0.12% had 9 other trackers.

30.36% also included Podtrac, 23.13% also included Podscribe, 16.60% also included Podsights, 11.76% also included Adswizz, 10.21% also included Chartable, 8.66% also included Magellan AI, 3.83% also included Podcorn, 3.31% also included OP3, 3.25% also included Spotify, 1.79% also included Podroll, 1.70% also included Claritas, 1.67% also included Audiotakes, 1.37% also included Gumshoe, 1.12% also included Blubrry, 0.58% also included Swap.fm, 0.36% also included ArtsAI, 0.33% also included United Podcasters, 0.27% also included CoHost Prefix, and 0.12% also included Podkite.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "44.74%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "18.57%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.71%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.39%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.89%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.59%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.16%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.92%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.70%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.61%" >}}
---

### 17. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.13% of new episodes in June, growing 2.02% from last month.

Of these, 18.70% had one other tracker, and 1.37% had 2 other trackers.

13.36% also included Blubrry, 4.42% also included Podtrac, 1.37% also included Podsights, 1.37% also included Chartable, 0.59% also included Podcorn, and 0.32% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "55.72%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "10.67%" >}}
3. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "6.25%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.74%" >}}
5. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "3.15%" >}}
6. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.60%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.33%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.69%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.64%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.23%" >}}
---

### 18. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.12% of new episodes in June, growing 0.08% from last month.

Of these, 33.66% had 5 other trackers, 13.78% had one other tracker, 13.00% had 4 other trackers, 9.19% had 2 other trackers, 8.82% had 3 other trackers, 4.85% had 6 other trackers, 1.25% had 7 other trackers, 0.26% had 8 other trackers, and 0.21% had 9 other trackers.

59.08% also included Podscribe, 57.41% also included Podtrac, 56.11% also included Podsights, 45.62% also included OP3, 41.96% also included Podcorn, 12.58% also included Spotify, 12.06% also included Chartable, 11.17% also included Magellan AI, 4.44% also included Audiotakes, 3.50% also included Podroll, 3.34% also included Swap.fm, 3.18% also included Adswizz, 2.92% also included CoHost Prefix, 2.35% also included Podder, 2.24% also included Claritas, 1.46% also included Veritonic, 0.84% also included United Podcasters, and 0.52% also included ArtsAI.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "47.49%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "22.13%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "20.93%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.39%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.18%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.62%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.52%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.26%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.26%" >}}
10. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.21%" >}}
---

### 19. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.07% of new episodes in June, growing 1.62% from last month.

Of these, 30.59% had 7 other trackers, 27.82% had 6 other trackers, 17.98% had 5 other trackers, 13.06% had 3 other trackers, 4.83% had 4 other trackers, 4.03% had 8 other trackers, 0.72% had 2 other trackers, and 0.36% had one other tracker.

87.21% also included Podscribe, 81.93% also included Podsights, 81.13% also included Podtrac, 81.04% also included Magellan AI, 67.26% also included Claritas, 50.27% also included ArtsAI, 38.82% also included Spotify, 28.00% also included Chartable, 25.85% also included Adswizz, 12.70% also included Audiotakes, 3.22% also included Swap.fm, 2.50% also included Gumshoe, 2.15% also included Podroll, 0.81% also included United Podcasters, 0.36% also included CoHost Prefix, and 0.18% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "64.22%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "25.49%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.49%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.95%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.06%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.36%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.36%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.36%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.36%" >}}
10. {{< a "https://www.thisamericanlife.org/" "This American Life" >}} {{< span "weak" "0.27%" >}}
---

### 20. [RSS Insight](https://www.rssinsight.com/)

RSS Insight was found on 0.04% of new episodes in June, shrinking 16.91% from last month.

For episodes that used RSS Insight, here are the top underlying podcast hosts:

1. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "100.00%" >}}
---

### 21. [Firstory](https://firstory.me/)

Firstory was found on 0.04% of new episodes in June, growing 4.80% from last month.

Of these, 1.88% had one other tracker.

1.88% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.28%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.58%" >}}
3. {{< a "https://firstory.me/" "Firstory" >}} {{< span "weak" "0.14%" >}}
---

### 22. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.02% of new episodes in June, shrinking 3.98% from last month.

Of these, 8.20% had one other tracker.

8.20% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "100.00%" >}}
---

### 23. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.02% of new episodes in June, growing 4.09% from last month.

Of these, 30.80% had one other tracker, 23.57% had 3 other trackers, 15.21% had 4 other trackers, 13.69% had 6 other trackers, 4.94% had 5 other trackers, 4.18% had 2 other trackers, 1.52% had 8 other trackers, and 0.76% had 7 other trackers.

43.35% also included Podtrac, 39.92% also included Podscribe, 39.16% also included Podsights, 30.80% also included Swap.fm, 30.42% also included Chartable, 26.62% also included Podroll, 22.05% also included Magellan AI, 11.41% also included Audiotakes, 9.51% also included Adswizz, 8.37% also included Spotify, 6.08% also included Gumshoe, 5.32% also included Podcorn, 5.32% also included ArtsAI, 5.32% also included Claritas, 4.18% also included Podder, 3.42% also included Veritonic, 3.04% also included OP3, and 0.76% also included Zencastr.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "45.63%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "11.79%" >}}
3. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "11.41%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "9.51%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.98%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.56%" >}}
7. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "3.80%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.28%" >}}
9. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "1.52%" >}}
10. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "1.52%" >}}
---

### 24. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.01% of new episodes in June, shrinking 3.26% from last month.

Of these, 24.65% had one other tracker, 20.93% had 5 other trackers, 20.47% had 4 other trackers, 6.05% had 2 other trackers, 3.26% had 6 other trackers, 2.33% had 3 other trackers, 2.33% had 8 other trackers, 1.86% had 7 other trackers, and 1.86% had 9 other trackers.

76.74% also included Podtrac, 49.30% also included Podsights, 48.84% also included Podscribe, 45.12% also included Chartable, 26.05% also included Gumshoe, 12.09% also included OP3, 10.70% also included Podroll, 9.77% also included Claritas, 4.19% also included Podcorn, 4.19% also included Podder, 3.72% also included Spotify, 3.72% also included ArtsAI, 1.86% also included Magellan AI, and 1.86% also included Veritonic.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "49.77%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "12.09%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "7.91%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.44%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "6.51%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "3.72%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.79%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.33%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.86%" >}}
10. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.86%" >}}
---

### 25. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in June, growing 5.70% from last month.

Of these, 29.87% had one other tracker, 5.19% had 5 other trackers, 3.25% had 2 other trackers, and 0.65% had 4 other trackers.

22.73% also included Podtrac, 11.69% also included OP3, 7.79% also included Blubrry, 5.84% also included Podcorn, 5.84% also included Podsights, 3.25% also included Podscribe, 2.60% also included Chartable, 2.60% also included Spotify, and 2.60% also included Podder.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "18.83%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "16.88%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "16.88%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "12.99%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.44%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "7.79%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "7.79%" >}}
8. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "5.19%" >}}
9. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "4.55%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.65%" >}}
---

### 26. [Zencastr](https://zencastr.com/)

Zencastr was found on <0.01% of new episodes in June, growing 1.40% from last month.

Of these, 13.89% had one other tracker, 5.56% had 2 other trackers, 2.78% had 6 other trackers, and 2.78% had 7 other trackers.

13.89% also included Podtrac, 11.11% also included Podcorn, 11.11% also included Chartable, 5.56% also included Podscribe, 5.56% also included Swap.fm, 5.56% also included OP3, 5.56% also included Podsights, and 2.78% also included United Podcasters.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "29.17%" >}}
2. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "16.67%" >}}
3. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "13.89%" >}}
4. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "11.11%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.11%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.72%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "8.33%" >}}
---

### 27. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in June, shrinking 28.16% from last month.

Of these, 20.75% had one other tracker, and 1.89% had 3 other trackers.

18.87% also included Podtrac, 3.77% also included Chartable, 1.89% also included Podscribe, and 1.89% also included Podcorn.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "28.30%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "22.64%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "20.75%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.43%" >}}
5. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "7.55%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "7.55%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.77%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
