---
title: "Top Podcast Tracking Services by Episode Share (May 2025)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-may-2025"
images:
- trackers-2025-05.png
date: 2025-06-01T11:28:00-04:00
lastmod: 2025-06-01T11:28:00-04:00
draft: false
rssrevision: 2025-05
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.8 million in May 2025), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in May, how many
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

{{< details "_September 2023: Spotify for Creators data_" >}}
_Starting mid-September, we gained a better signal of when Spotify for Creators (formerly Spotify for Podcasters, formerly Anchor) podcasts release new episodes, so our crawlers are finding more.
Higher share of new episodes on S4P (which typically do not have prefixes) will have led to lower share overall._
{{< /details >}}

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Adswizz	Podsights	Podscribe	Blubrry	Chartable	Podcorn	Spotify	Podroll	Audiotakes	OP3	Swap.fm	Claritas	Podder	ArtsAI	Feedpress	Gumshoe	Veritonic	RSS Insight	Médiamétrie	United Podcasters	CoHost Prefix	Podkite	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
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
Aug 2022	4.83	2.08	1.73		1.51	5.26	2.45								0.10	0.20				0.41							0.01			
Sep 2022	7.53	2.26	1.74	0.02	1.49	5.40	2.45						0.01		0.09	0.21				0.52			0.01				0.02	0.02		
Oct 2022	8.24	2.35	1.81	0.07	1.61	5.48	2.51				0.03		0.02		0.10	0.18				0.50			0.01	0.01			0.02	0.04		
Nov 2022	8.11	2.37	2.03	0.15	1.62	5.62	2.43				0.04		0.03	0.01	0.10	0.18				0.50			0.01	0.01			0.02	0.05		
Dec 2022	8.01	2.32	1.81	0.03	1.61	5.54	2.05				0.05		0.02	0.04	0.05	0.18				0.49			0.01	0.01		0.01	0.02	0.05		
Jan 2023	7.85	2.35	1.88	0.20	1.61	5.56	2.15				0.07		0.06	0.11	0.10	0.18				0.54			0.01	0.01		0.01	0.02	0.06		
Feb 2023	7.58	2.29	1.92	0.21	1.62	5.51	2.30				0.07		0.07	0.11	0.10	0.19				0.49			0.01	0.01		0.01	0.02	0.06	0.03	
Mar 2023	7.79	2.25	2.03	0.21	1.53	5.53	2.22		0.04		0.08		0.07	0.11	0.11	0.18		0.04		0.45			0.01	0.01		0.01	0.02	0.06		
Apr 2023	7.66	2.26	2.00	0.21	1.67	5.43	2.20		0.06		0.09		0.07	0.15	0.11	0.17	0.08	0.05		0.45			0.01	0.01		0.01	0.01			
May 2023	7.58	2.27	2.04	0.24	1.67	5.59	2.28		0.09		0.09		0.08	0.15	0.11	0.19	0.07	0.05		0.45			0.01	0.01	0.01	0.01	0.01			
Jun 2023	8.22	2.39	2.23	0.26	1.64	5.83	1.86		0.10		0.09		0.07	0.15	0.12	0.19	0.08	0.05		0.51			0.01	0.01	0.01	0.01	0.01			
Jul 2023	8.60	2.38	2.52	0.27	1.53	5.95	1.17	0.01	0.14		0.08		0.07	0.14	0.11	0.18	0.06	0.06		0.55			0.01	0.01	0.01	0.01	0.01			
Aug 2023	9.19	2.72	2.76	0.36	1.58	6.43	1.23	0.03	0.16	0.04	0.11		0.08	0.15	0.12	0.17	0.07	0.07		0.53			0.01	0.01	0.02	0.01				
Sep 2023	8.46	2.49	2.47	0.37	1.39	5.77	1.10	0.05	0.13	0.05	0.10		0.10	0.15	0.12	0.16	0.07	0.06		0.58			0.01	0.01	0.02	0.01				
Oct 2023	7.90	2.29	2.28	0.39	1.37	5.54	1.11	0.08	0.12	0.05	0.10		0.10	0.16	0.12	0.16	0.08	0.06		0.50			0.01	0.02	0.03	0.01				
Nov 2023	7.65	2.25	2.33	0.47	1.45	5.59	1.14	0.11	0.12	0.06	0.13		0.11	0.16	0.12	0.17	0.10	0.06		0.33			0.01	0.01	0.03					
Dec 2023	7.48	2.20	2.19	0.54	1.53	5.60	1.12	0.12	0.12	0.06	0.11		0.11	0.16	0.12	0.16	0.09	0.06		0.33			0.01	0.01	0.03					
Jan 2024	7.64	2.37	2.21	0.65	1.55	5.61	1.17	0.15	0.11	0.08	0.13		0.12	0.16	0.14	0.17	0.10	0.06		0.25	0.01		0.01	0.01	0.01					
Feb 2024	7.69	2.38	2.22	0.69	1.52	5.58	1.21	0.22	0.12	0.09	0.16		0.13	0.17	0.13	0.17	0.11	0.06		0.22	0.01		0.01	0.01						
Mar 2024	9.01	2.53	2.19	0.69	1.54	5.46	1.14	0.25	0.12	0.09	0.14		0.14	0.16	0.12	0.16	0.10	0.06		0.22	0.01		0.01	0.01						
Apr 2024	10.78	2.53	2.16	0.73	1.51	5.47	1.24	0.27	0.34	0.07	0.18		0.15	0.17	0.13	0.15	0.11	0.07		0.19	0.01	0.01	0.01	0.01						
May 2024	11.59	2.75	2.24	0.83	1.50	5.63	1.20	0.30	0.36	0.06	0.18		0.15	0.16	0.14	0.15	0.11	0.07		0.09	0.01	0.01	0.01	0.01						
Jun 2024	11.54	2.88	2.34	0.91	1.52	6.06	0.71	0.32	0.37	0.07	0.20	0.03	0.16	0.15	0.16	0.15	0.11	0.07		0.10	0.01	0.01	0.01	0.01						
Jul 2024	12.34	2.83	2.45	1.01	1.65	6.80	0.71	0.34	0.43	0.09	0.20	0.06	0.18	0.15	0.17	0.15	0.12	0.07		0.09	0.01	0.01	0.01	0.01						
Aug 2024	14.22	2.96	2.48	1.11	1.70	6.72	0.81	0.35	0.45	0.11	0.19	0.12	0.18	0.35	0.18	0.14	0.12	0.08		0.08	0.01	0.01	0.01	0.01						
Sep 2024	12.95	3.13	2.26	1.18	1.44	5.99	0.72	0.35	0.44	0.13	0.24	0.12	0.18	0.42	0.18	0.15	0.13	0.08		0.07	0.01	0.01	0.01	0.01						
Oct 2024	12.24	3.23	2.35	1.23	1.53	5.49	0.66	0.40	0.43	0.14	0.27	0.17	0.19	0.39	0.18	0.14	0.12	0.09		0.09	0.01	0.01	0.01	0.01						
Nov 2024	11.86	3.21	2.31	1.27	1.52	4.66	0.63	0.44	0.43	0.14	0.29	0.19	0.21	0.41	0.17	0.11	0.12	0.08		0.10	0.01	0.01	0.01	0.01						
Dec 2024	12.56	3.06	2.13	1.29	1.40	2.29	0.62	0.45	0.43	0.15	0.29	0.24	0.21	0.54	0.18	0.09	0.12	0.08		0.09	0.01	0.01	0.01	0.01						
Jan 2025	12.62	2.92	1.73	1.31	1.36	1.54	0.66	0.41	0.46	0.16	0.34	0.27	0.21	0.54	0.19	0.12	0.13	0.08		0.04	0.01	0.01	0.01	0.01						
Feb 2025	12.47	2.74	1.70	1.25	1.45	1.43	0.66	0.36	0.46	0.16	0.33	0.28	0.22	0.48	0.18	0.14	0.12	0.08		0.01	0.01	0.01	0.01	0.01						
Mar 2025	12.18	2.87	1.51	1.28	1.25	1.18	0.67	0.33	0.47	0.25	0.33	0.27	0.21	0.36	0.18	0.14	0.13	0.07	0.04	0.01	0.01	0.01	0.01	0.01						
Apr 2025	12.35	2.97	1.64	1.53	1.26	1.28	0.68	0.44	0.48	0.41	0.34	0.30	0.23	0.33	0.19	0.13	0.12	0.08	0.03	0.02	0.01	0.01	0.01	0.01						
May 2025	12.48	2.97	1.74	1.61	1.40	1.31	0.64	0.46	0.46	0.40	0.39	0.33	0.24	0.22	0.20	0.13	0.12	0.07	0.05	0.02	0.02	0.01	0.01							
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} are the clear top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podsights	Podscribe	Blubrry	Podcorn	Spotify	Podroll	Audiotakes	OP3	Swap.fm	Claritas	Podder	ArtsAI	Feedpress	Gumshoe	Veritonic	RSS Insight	Médiamétrie	United Podcasters	CoHost Prefix	Podkite	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
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
Aug 2022	2.08	1.73		1.51	2.45								0.10	0.20				0.41							0.01			
Sep 2022	2.26	1.74	0.02	1.49	2.45						0.01		0.09	0.21				0.52			0.01				0.02	0.02		
Oct 2022	2.35	1.81	0.07	1.61	2.51				0.03		0.02		0.10	0.18				0.50			0.01	0.01			0.02	0.04		
Nov 2022	2.37	2.03	0.15	1.62	2.43				0.04		0.03	0.01	0.10	0.18				0.50			0.01	0.01			0.02	0.05		
Dec 2022	2.32	1.81	0.03	1.61	2.05				0.05		0.02	0.04	0.05	0.18				0.49			0.01	0.01		0.01	0.02	0.05		
Jan 2023	2.35	1.88	0.20	1.61	2.15				0.07		0.06	0.11	0.10	0.18				0.54			0.01	0.01		0.01	0.02	0.06		
Feb 2023	2.29	1.92	0.21	1.62	2.30				0.07		0.07	0.11	0.10	0.19				0.49			0.01	0.01		0.01	0.02	0.06	0.03	
Mar 2023	2.25	2.03	0.21	1.53	2.22		0.04		0.08		0.07	0.11	0.11	0.18		0.04		0.45			0.01	0.01		0.01	0.02	0.06		
Apr 2023	2.26	2.00	0.21	1.67	2.20		0.06		0.09		0.07	0.15	0.11	0.17	0.08	0.05		0.45			0.01	0.01		0.01	0.01			
May 2023	2.27	2.04	0.24	1.67	2.28		0.09		0.09		0.08	0.15	0.11	0.19	0.07	0.05		0.45			0.01	0.01	0.01	0.01	0.01			
Jun 2023	2.39	2.23	0.26	1.64	1.86		0.10		0.09		0.07	0.15	0.12	0.19	0.08	0.05		0.51			0.01	0.01	0.01	0.01	0.01			
Jul 2023	2.38	2.52	0.27	1.53	1.17	0.01	0.14		0.08		0.07	0.14	0.11	0.18	0.06	0.06		0.55			0.01	0.01	0.01	0.01	0.01			
Aug 2023	2.72	2.76	0.36	1.58	1.23	0.03	0.16	0.04	0.11		0.08	0.15	0.12	0.17	0.07	0.07		0.53			0.01	0.01	0.02	0.01				
Sep 2023	2.49	2.47	0.37	1.39	1.10	0.05	0.13	0.05	0.10		0.10	0.15	0.12	0.16	0.07	0.06		0.58			0.01	0.01	0.02	0.01				
Oct 2023	2.29	2.28	0.39	1.37	1.11	0.08	0.12	0.05	0.10		0.10	0.16	0.12	0.16	0.08	0.06		0.50			0.01	0.02	0.03	0.01				
Nov 2023	2.25	2.33	0.47	1.45	1.14	0.11	0.12	0.06	0.13		0.11	0.16	0.12	0.17	0.10	0.06		0.33			0.01	0.01	0.03					
Dec 2023	2.20	2.19	0.54	1.53	1.12	0.12	0.12	0.06	0.11		0.11	0.16	0.12	0.16	0.09	0.06		0.33			0.01	0.01	0.03					
Jan 2024	2.37	2.21	0.65	1.55	1.17	0.15	0.11	0.08	0.13		0.12	0.16	0.14	0.17	0.10	0.06		0.25	0.01		0.01	0.01	0.01					
Feb 2024	2.38	2.22	0.69	1.52	1.21	0.22	0.12	0.09	0.16		0.13	0.17	0.13	0.17	0.11	0.06		0.22	0.01		0.01	0.01						
Mar 2024	2.53	2.19	0.69	1.54	1.14	0.25	0.12	0.09	0.14		0.14	0.16	0.12	0.16	0.10	0.06		0.22	0.01		0.01	0.01						
Apr 2024	2.53	2.16	0.73	1.51	1.24	0.27	0.34	0.07	0.18		0.15	0.17	0.13	0.15	0.11	0.07		0.19	0.01	0.01	0.01	0.01						
May 2024	2.75	2.24	0.83	1.50	1.20	0.30	0.36	0.06	0.18		0.15	0.16	0.14	0.15	0.11	0.07		0.09	0.01	0.01	0.01	0.01						
Jun 2024	2.88	2.34	0.91	1.52	0.71	0.32	0.37	0.07	0.20	0.03	0.16	0.15	0.16	0.15	0.11	0.07		0.10	0.01	0.01	0.01	0.01						
Jul 2024	2.83	2.45	1.01	1.65	0.71	0.34	0.43	0.09	0.20	0.06	0.18	0.15	0.17	0.15	0.12	0.07		0.09	0.01	0.01	0.01	0.01						
Aug 2024	2.96	2.48	1.11	1.70	0.81	0.35	0.45	0.11	0.19	0.12	0.18	0.35	0.18	0.14	0.12	0.08		0.08	0.01	0.01	0.01	0.01						
Sep 2024	3.13	2.26	1.18	1.44	0.72	0.35	0.44	0.13	0.24	0.12	0.18	0.42	0.18	0.15	0.13	0.08		0.07	0.01	0.01	0.01	0.01						
Oct 2024	3.23	2.35	1.23	1.53	0.66	0.40	0.43	0.14	0.27	0.17	0.19	0.39	0.18	0.14	0.12	0.09		0.09	0.01	0.01	0.01	0.01						
Nov 2024	3.21	2.31	1.27	1.52	0.63	0.44	0.43	0.14	0.29	0.19	0.21	0.41	0.17	0.11	0.12	0.08		0.10	0.01	0.01	0.01	0.01						
Dec 2024	3.06	2.13	1.29	1.40	0.62	0.45	0.43	0.15	0.29	0.24	0.21	0.54	0.18	0.09	0.12	0.08		0.09	0.01	0.01	0.01	0.01						
Jan 2025	2.92	1.73	1.31	1.36	0.66	0.41	0.46	0.16	0.34	0.27	0.21	0.54	0.19	0.12	0.13	0.08		0.04	0.01	0.01	0.01	0.01						
Feb 2025	2.74	1.70	1.25	1.45	0.66	0.36	0.46	0.16	0.33	0.28	0.22	0.48	0.18	0.14	0.12	0.08		0.01	0.01	0.01	0.01	0.01						
Mar 2025	2.87	1.51	1.28	1.25	0.67	0.33	0.47	0.25	0.33	0.27	0.21	0.36	0.18	0.14	0.13	0.07	0.04	0.01	0.01	0.01	0.01	0.01						
Apr 2025	2.97	1.64	1.53	1.26	0.68	0.44	0.48	0.41	0.34	0.30	0.23	0.33	0.19	0.13	0.12	0.08	0.03	0.02	0.01	0.01	0.01	0.01						
May 2025	2.97	1.74	1.61	1.40	0.64	0.46	0.46	0.40	0.39	0.33	0.24	0.22	0.20	0.13	0.12	0.07	0.05	0.02	0.02	0.01	0.01							
{{< /graph >}}

---

### Overall

At least one tracker was found on 18.45% of new episodes in May, growing 2.07% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "42.70%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.62%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.42%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.45%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.69%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.27%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.08%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.36%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.28%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.20%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of May 2025.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 12.48% of new episodes in May, growing 1.03% from last month.

Of these, 10.63% had one other tracker, 7.60% had 2 other trackers, 1.39% had 3 other trackers, 1.36% had 4 other trackers, 0.93% had 5 other trackers, 0.45% had 6 other trackers, 0.20% had 7 other trackers, and 0.02% had 8 other trackers.

8.86% also included Podsights, 6.41% also included Adswizz, 6.09% also included Podscribe, 5.36% also included Chartable, 3.12% also included Podroll, 2.27% also included Spotify, 2.23% also included Magellan AI, 1.54% also included Swap.fm, 1.31% also included Podcorn, 1.25% also included Claritas, 1.25% also included Blubrry, 1.21% also included OP3, 0.97% also included ArtsAI, 0.71% also included Audiotakes, 0.55% also included Gumshoe, 0.53% also included Podder, 0.42% also included Veritonic, 0.08% also included CoHost Prefix, 0.05% also included United Podcasters, 0.04% also included Feedpress, 0.02% also included Podkite, 0.01% also included Médiamétrie, 0.01% also included AdBarker, and <0.01% also included Zencastr.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "62.99%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "8.91%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.05%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.14%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.04%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.29%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.60%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.03%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.83%" >}}
10. {{< a "https://portal.rozhlas.cz/" "Cesky rozhlas" >}} {{< span "weak" "0.64%" >}}
---

### 2. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.97% of new episodes in May, shrinking 0.01% from last month.

Of these, 15.39% had 2 other trackers, 14.38% had one other tracker, 8.25% had 3 other trackers, 2.28% had 4 other trackers, 1.09% had 5 other trackers, 0.62% had 6 other trackers, 0.31% had 7 other trackers, and 0.04% had 8 other trackers.

26.96% also included Podtrac, 14.47% also included Podscribe, 12.26% also included Magellan AI, 11.87% also included Podroll, 8.76% also included Audiotakes, 3.59% also included Podsights, 2.44% also included Swap.fm, 2.37% also included Spotify, 2.09% also included Claritas, 1.23% also included Blubrry, 1.17% also included ArtsAI, 1.06% also included Chartable, 0.89% also included Podder, 0.61% also included OP3, 0.50% also included Veritonic, 0.24% also included Podcorn, 0.09% also included Gumshoe, and 0.05% also included United Podcasters.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "61.64%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "5.57%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "5.46%" >}}
4. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "5.42%" >}}
5. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "5.37%" >}}
6. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "3.75%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.42%" >}}
8. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "2.11%" >}}
9. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.39%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.86%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 2.60% of new episodes in May, growing 4.52% from last month.

Of these, 56.09% also included Podtrac, 28.86% also included Podscribe, 13.95% also included Magellan AI, 7.87% also included Claritas, 7.84% also included Adswizz, 7.42% also included Swap.fm, 5.93% also included ArtsAI, 4.82% also included Audiotakes, 3.15% also included Podcorn, 3.14% also included Gumshoe, 2.89% also included Podroll, 2.85% also included OP3, 2.39% also included Veritonic, 1.58% also included Podder, 0.42% also included Blubrry, 0.32% also included United Podcasters, 0.26% also included CoHost Prefix, 0.07% also included Feedpress, 0.03% also included Podkite, 0.02% also included Firstory, 0.01% also included Zencastr, and <0.01% also included AdBarker.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "57.08%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.75%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.79%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.94%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.58%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.88%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.56%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.37%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.15%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.98%" >}}
---

### 3. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.74% of new episodes in May, growing 5.80% from last month.

Of these, 35.43% had one other tracker, 22.48% had 2 other trackers, 10.78% had 4 other trackers, 9.19% had 3 other trackers, 6.76% had 5 other trackers, 2.83% had 6 other trackers, 1.07% had 7 other trackers, and 0.11% had 8 other trackers.

63.70% also included Podtrac, 40.86% also included Chartable, 30.44% also included Podscribe, 15.87% also included Magellan AI, 9.38% also included Swap.fm, 6.69% also included Claritas, 6.14% also included Adswizz, 5.67% also included ArtsAI, 5.31% also included Audiotakes, 4.73% also included Spotify, 4.14% also included Podcorn, 3.91% also included Gumshoe, 3.90% also included OP3, 3.11% also included Veritonic, 2.96% also included Podroll, 2.10% also included Podder, 0.44% also included Blubrry, 0.35% also included CoHost Prefix, 0.34% also included United Podcasters, 0.11% also included Feedpress, 0.03% also included Podkite, and 0.01% also included Zencastr.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "61.71%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "21.58%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.72%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.67%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.01%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.48%" >}}
7. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.27%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.20%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.14%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.61%" >}}
---

### 4. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 1.61% of new episodes in May, growing 4.74% from last month.

Of these, 24.32% had 3 other trackers, 19.58% had one other tracker, 16.06% had 4 other trackers, 12.81% had 2 other trackers, 9.40% had 5 other trackers, 4.02% had 6 other trackers, 1.53% had 7 other trackers, and 0.12% had 8 other trackers.

47.35% also included Podtrac, 42.51% also included Magellan AI, 32.92% also included Podsights, 26.75% also included Adswizz, 24.57% also included Audiotakes, 16.66% also included Chartable, 15.95% also included Spotify, 14.20% also included Claritas, 11.18% also included ArtsAI, 8.10% also included Swap.fm, 4.81% also included Podcorn, 4.23% also included Gumshoe, 4.18% also included Podroll, 3.76% also included OP3, 3.55% also included Veritonic, 3.33% also included Podder, 0.40% also included United Podcasters, 0.38% also included CoHost Prefix, 0.25% also included Blubrry, 0.06% also included AdBarker, 0.01% also included Podkite, and 0.01% also included Zencastr.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "39.12%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "24.99%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.71%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.76%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.74%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.68%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.08%" >}}
8. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "2.96%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.33%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.58%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.40% of new episodes in May, growing 11.00% from last month.

Of these, 15.07% had one other tracker, 0.62% had 2 other trackers, 0.15% had 3 other trackers, 0.13% had 4 other trackers, 0.04% had 5 other trackers, and 0.02% had 6 other trackers.

11.18% also included Podtrac, 2.60% also included Adswizz, 1.34% also included Feedpress, 0.54% also included Podsights, 0.48% also included OP3, 0.29% also included Podcorn, 0.28% also included Podscribe, 0.21% also included Swap.fm, 0.21% also included Podder, 0.17% also included Chartable, 0.12% also included Spotify, 0.11% also included Magellan AI, 0.04% also included ArtsAI, 0.04% also included Podkite, 0.01% also included Audiotakes, and 0.01% also included Veritonic.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "48.70%" >}}
2. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "4.92%" >}}
3. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.64%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.67%" >}}
5. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "2.48%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.72%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.33%" >}}
8. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.06%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.70%" >}}
10. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "0.60%" >}}
---

### 6. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 1.31% of new episodes in May, growing 2.11% from last month.

Of these, 34.28% had 2 other trackers, 22.25% had one other tracker, 7.49% had 4 other trackers, 7.13% had 3 other trackers, 3.40% had 5 other trackers, 2.36% had 6 other trackers, 0.24% had 7 other trackers, and 0.02% had 8 other trackers.

54.24% also included Podsights, 51.12% also included Podtrac, 20.45% also included Podscribe, 10.66% also included Spotify, 10.14% also included Swap.fm, 9.75% also included Magellan AI, 4.41% also included Claritas, 2.77% also included Podroll, 2.40% also included Adswizz, 1.68% also included Podder, 1.52% also included Veritonic, 1.16% also included ArtsAI, 1.09% also included Gumshoe, 0.90% also included Podcorn, 0.90% also included Audiotakes, 0.78% also included OP3, 0.44% also included CoHost Prefix, 0.37% also included United Podcasters, 0.18% also included Blubrry, 0.14% also included Feedpress, 0.05% also included Firstory, 0.02% also included Zencastr, 0.02% also included Podkite, and 0.01% also included AdBarker.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "85.26%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.80%" >}}
3. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.08%" >}}
4. {{< a "https://cloud.google.com/" "Google Cloud" >}} {{< span "weak" "0.53%" >}}
5. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.50%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.50%" >}}
7. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.38%" >}}
8. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "0.30%" >}}
9. {{< a "https://www.wideorbit.com/" "WideOrbit" >}} {{< span "weak" "0.29%" >}}
10. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.23%" >}}
---

### 7. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.95% of new episodes in May, growing 5.92% from last month.

Of these, 29.86% had 3 other trackers, 17.58% had 4 other trackers, 9.85% had 5 other trackers, 7.00% had 2 other trackers, 5.98% had 6 other trackers, 5.54% had one other tracker, 2.37% had 7 other trackers, and 0.13% had 8 other trackers.

71.61% also included Podscribe, 38.18% also included Adswizz, 33.39% also included Audiotakes, 29.22% also included Podtrac, 28.92% also included Podsights, 19.40% also included Claritas, 13.70% also included Spotify, 13.39% also included Chartable, 11.31% also included ArtsAI, 8.42% also included Swap.fm, 5.43% also included Veritonic, 4.21% also included Podroll, 2.37% also included Podder, 1.27% also included Gumshoe, 0.82% also included OP3, 0.28% also included United Podcasters, 0.17% also included Blubrry, 0.08% also included Podcorn, and 0.02% also included CoHost Prefix.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "35.13%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.38%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "13.15%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.66%" >}}
5. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "6.79%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.36%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.34%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "2.55%" >}}
9. {{< a "https://www.americanpublicmedia.org/" "American Public Media" >}} {{< span "weak" "1.45%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.09%" >}}
---

### 8. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.64% of new episodes in May, shrinking 5.84% from last month.

Of these, 11.96% had one other tracker, 6.46% had 2 other trackers, 6.16% had 5 other trackers, 2.73% had 4 other trackers, 1.87% had 3 other trackers, 0.83% had 6 other trackers, 0.11% had 8 other trackers, and 0.07% had 7 other trackers.

25.45% also included Podtrac, 12.23% also included OP3, 12.02% also included Podscribe, 11.20% also included Podsights, 8.02% also included Gumshoe, 2.16% also included Podroll, 1.84% also included Chartable, 1.47% also included Spotify, 1.35% also included Podder, 1.11% also included Adswizz, 0.64% also included Blubrry, 0.21% also included Swap.fm, 0.18% also included United Podcasters, 0.16% also included AdBarker, 0.12% also included Feedpress, 0.11% also included Magellan AI, 0.07% also included Podkite, 0.06% also included CoHost Prefix, 0.05% also included Zencastr, and 0.04% also included Audiotakes.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "22.09%" >}}
2. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "12.77%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "11.96%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "11.13%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "7.79%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "6.95%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.19%" >}}
8. {{< a "https://www.wideorbit.com/" "WideOrbit" >}} {{< span "weak" "4.14%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.08%" >}}
10. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "2.33%" >}}
---

### 9. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.46% of new episodes in May, growing 5.46% from last month.

Of these, 31.55% had 2 other trackers, 14.79% had 4 other trackers, 9.05% had 5 other trackers, 8.86% had 6 other trackers, 7.77% had 3 other trackers, 7.73% had one other tracker, 4.20% had 7 other trackers, and 0.33% had 8 other trackers.

61.63% also included Podtrac, 55.78% also included Podscribe, 30.37% also included Chartable, 28.43% also included Magellan AI, 26.24% also included Claritas, 17.90% also included ArtsAI, 17.87% also included Podsights, 15.36% also included Adswizz, 9.88% also included Audiotakes, 5.08% also included Veritonic, 3.39% also included Podroll, 3.15% also included Gumshoe, 2.39% also included Swap.fm, 2.17% also included OP3, 2.06% also included Podcorn, 1.33% also included Podder, 0.36% also included Blubrry, 0.32% also included United Podcasters, and 0.04% also included CoHost Prefix.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "40.16%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "18.90%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "14.32%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "11.67%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.61%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.13%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.86%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.64%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.25%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.01%" >}}
---

### 10. [Podroll](https://podroll.fm/)

Podroll was found on 0.46% of new episodes in May, shrinking 5.04% from last month.

Of these, 72.78% had 2 other trackers, 7.74% had one other tracker, 6.63% had 4 other trackers, 3.86% had 3 other trackers, 3.56% had 6 other trackers, 2.33% had 5 other trackers, 0.76% had 7 other trackers, and 0.15% had 8 other trackers.

85.03% also included Podtrac, 77.07% also included Adswizz, 14.68% also included Podscribe, 11.25% also included Podsights, 8.77% also included Magellan AI, 7.91% also included Chartable, 5.95% also included Swap.fm, 4.57% also included Audiotakes, 3.99% also included Claritas, 3.40% also included Spotify, 3.03% also included Podcorn, 1.39% also included OP3, 0.96% also included ArtsAI, 0.91% also included Gumshoe, 0.84% also included United Podcasters, 0.47% also included Podder, 0.36% also included CoHost Prefix, and 0.35% also included Veritonic.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "77.14%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.01%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.43%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.88%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "1.74%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.94%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.85%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.38%" >}}
9. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "0.26%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.20%" >}}
---

### 11. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.40% of new episodes in May, shrinking 2.55% from last month.

Of these, 65.46% had 3 other trackers, 19.46% had 4 other trackers, 7.06% had 5 other trackers, 5.22% had 2 other trackers, 1.50% had 6 other trackers, 0.52% had one other tracker, and 0.14% had 7 other trackers.

99.09% also included Podscribe, 79.93% also included Magellan AI, 65.32% also included Adswizz, 23.16% also included Podsights, 22.39% also included Podtrac, 13.76% also included ArtsAI, 11.39% also included Spotify, 5.25% also included Podroll, 2.96% also included Chartable, 2.18% also included Swap.fm, 2.08% also included Veritonic, 1.09% also included Gumshoe, 0.91% also included Podder, 0.44% also included OP3, 0.35% also included United Podcasters, 0.13% also included Claritas, 0.06% also included Podcorn, and 0.03% also included Blubrry.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "65.79%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "13.66%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.98%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.88%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.72%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.33%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.76%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.44%" >}}
9. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.37%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.07%" >}}
---

### 12. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.39% of new episodes in May, growing 15.57% from last month.

Of these, 19.66% had one other tracker, 10.31% had 5 other trackers, 8.53% had 2 other trackers, 3.66% had 4 other trackers, 3.23% had 3 other trackers, 1.51% had 6 other trackers, 0.53% had 7 other trackers, and 0.10% had 8 other trackers.

38.52% also included Podtrac, 19.99% also included Podcorn, 17.27% also included Podsights, 15.36% also included Podscribe, 14.15% also included Gumshoe, 4.65% also included Adswizz, 2.58% also included Chartable, 2.54% also included Spotify, 1.98% also included Magellan AI, 1.71% also included Blubrry, 1.71% also included Podder, 1.62% also included Podroll, 1.25% also included Swap.fm, 0.82% also included Claritas, 0.56% also included ArtsAI, 0.44% also included Audiotakes, 0.34% also included CoHost Prefix, 0.30% also included Podkite, 0.16% also included United Podcasters, 0.11% also included Feedpress, and 0.06% also included Zencastr.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "23.41%" >}}
2. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "18.23%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "6.40%" >}}
4. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "4.74%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.45%" >}}
6. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "4.00%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.37%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.94%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.66%" >}}
10. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.64%" >}}
---

### 13. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.33% of new episodes in May, growing 10.09% from last month.

Of these, 27.73% had 2 other trackers, 17.25% had 4 other trackers, 16.63% had 3 other trackers, 16.09% had one other tracker, 12.11% had 5 other trackers, 1.85% had 6 other trackers, 1.50% had 7 other trackers, and 0.09% had 8 other trackers.

58.99% also included Podtrac, 49.84% also included Podsights, 40.58% also included Chartable, 39.82% also included Podscribe, 24.54% also included Magellan AI, 22.20% also included Adswizz, 9.95% also included ArtsAI, 8.33% also included Podroll, 6.33% also included Claritas, 3.36% also included Spotify, 2.66% also included Audiotakes, 1.50% also included OP3, 1.41% also included United Podcasters, 1.33% also included Gumshoe, 0.91% also included Blubrry, 0.67% also included Veritonic, 0.41% also included Podcorn, 0.34% also included Podder, and 0.03% also included Zencastr.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "57.71%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "22.20%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.52%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.69%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "4.55%" >}}
6. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.17%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.14%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.02%" >}}
---

### 14. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.24% of new episodes in May, growing 0.80% from last month.

Of these, 30.73% had 4 other trackers, 23.74% had 5 other trackers, 21.47% had 6 other trackers, 9.00% had 7 other trackers, 8.33% had 3 other trackers, 3.75% had 2 other trackers, 1.53% had one other tracker, and 0.52% had 8 other trackers.

96.54% also included Podscribe, 78.26% also included Magellan AI, 66.24% also included Podtrac, 51.01% also included Spotify, 49.18% also included Podsights, 40.37% also included ArtsAI, 26.29% also included Adswizz, 24.41% also included Chartable, 17.87% also included Veritonic, 8.76% also included Swap.fm, 7.73% also included Podroll, 1.57% also included Podder, 1.36% also included OP3, 0.93% also included Gumshoe, 0.52% also included CoHost Prefix, 0.38% also included United Podcasters, and 0.21% also included Audiotakes.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "38.20%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "26.15%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "22.21%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.94%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.42%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.21%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.21%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.19%" >}}
9. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.17%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.14%" >}}
---

### 15. [Podder](https://www.podderapp.com/)

Podder was found on 0.22% of new episodes in May, shrinking 32.22% from last month.

Of these, 16.25% had 2 other trackers, 12.11% had one other tracker, 8.02% had 3 other trackers, 6.85% had 4 other trackers, 3.76% had 5 other trackers, 0.89% had 6 other trackers, and 0.18% had 8 other trackers.

30.05% also included Podtrac, 24.28% also included Podscribe, 16.56% also included Podsights, 12.01% also included Adswizz, 10.25% also included Magellan AI, 9.97% also included Chartable, 3.94% also included Podcorn, 3.04% also included OP3, 2.76% also included Spotify, 1.69% also included Claritas, 1.64% also included Audiotakes, 1.53% also included Gumshoe, 1.33% also included Blubrry, 0.97% also included Podroll, 0.59% also included ArtsAI, 0.51% also included Swap.fm, 0.28% also included United Podcasters, 0.18% also included CoHost Prefix, and 0.10% also included Podkite.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "44.29%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "17.81%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.88%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "8.36%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.58%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.58%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.50%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.96%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.77%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.72%" >}}
---

### 16. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.20% of new episodes in May, growing 1.12% from last month.

Of these, 36.27% had 4 other trackers, 23.95% had 5 other trackers, 10.70% had 7 other trackers, 8.92% had 6 other trackers, 8.89% had 2 other trackers, 7.62% had 3 other trackers, 2.86% had one other tracker, and 0.63% had 8 other trackers.

91.89% also included Podscribe, 61.80% also included Podtrac, 55.19% also included Magellan AI, 50.40% also included Podsights, 48.82% also included Claritas, 42.07% also included Spotify, 28.04% also included Audiotakes, 17.80% also included Adswizz, 16.65% also included Swap.fm, 16.07% also included Veritonic, 7.76% also included Chartable, 2.25% also included Podroll, 1.13% also included OP3, 0.66% also included Podder, 0.46% also included United Podcasters, 0.32% also included Blubrry, 0.26% also included Gumshoe, and 0.20% also included CoHost Prefix.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.60%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "27.58%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "17.66%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "13.04%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "9.09%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.31%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.26%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.20%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.14%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.12%" >}}
---

### 17. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.13% of new episodes in May, shrinking 0.75% from last month.

Of these, 19.43% had one other tracker, and 1.42% had 2 other trackers.

14.29% also included Blubrry, 4.20% also included Podtrac, 1.42% also included Podsights, 1.42% also included Chartable, 0.60% also included Podcorn, and 0.34% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "55.21%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "10.77%" >}}
3. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "6.05%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.38%" >}}
5. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "3.00%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.92%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.57%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.67%" >}}
9. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.50%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.29%" >}}
---

### 18. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.12% of new episodes in May, shrinking 5.06% from last month.

Of these, 33.24% had 5 other trackers, 14.64% had 4 other trackers, 14.45% had one other tracker, 9.20% had 2 other trackers, 7.08% had 3 other trackers, 5.54% had 6 other trackers, 1.35% had 7 other trackers, and 0.34% had 8 other trackers.

58.38% also included Podtrac, 58.04% also included Podsights, 58.04% also included Podscribe, 47.50% also included OP3, 44.03% also included Podcorn, 12.38% also included Spotify, 12.19% also included Chartable, 10.36% also included Magellan AI, 3.71% also included Audiotakes, 3.71% also included Swap.fm, 3.56% also included Podroll, 2.89% also included Podder, 2.55% also included CoHost Prefix, 2.22% also included Adswizz, 1.88% also included Claritas, 1.54% also included Veritonic, 0.82% also included United Podcasters, and 0.43% also included ArtsAI.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "49.23%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "22.01%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "20.38%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.94%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.55%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.73%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.58%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.19%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.19%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.10%" >}}
---

### 19. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.07% of new episodes in May, shrinking 13.08% from last month.

Of these, 29.00% had 7 other trackers, 27.24% had 6 other trackers, 19.53% had 5 other trackers, 12.41% had 3 other trackers, 5.03% had 4 other trackers, 1.84% had 8 other trackers, 0.75% had 2 other trackers, and 0.34% had one other tracker.

84.66% also included Podscribe, 80.39% also included Podsights, 78.54% also included Podtrac, 76.95% also included Magellan AI, 62.78% also included Claritas, 46.69% also included ArtsAI, 34.70% also included Spotify, 29.59% also included Chartable, 22.13% also included Adswizz, 12.32% also included Audiotakes, 3.27% also included Swap.fm, 2.68% also included Gumshoe, 2.35% also included Podroll, 0.50% also included United Podcasters, 0.34% also included CoHost Prefix, and 0.17% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "67.81%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "21.96%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.52%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.02%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.10%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.42%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.34%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.34%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.25%" >}}
10. {{< a "https://www.thisamericanlife.org/" "This American Life" >}} {{< span "weak" "0.08%" >}}
---

### 20. [RSS Insight](https://www.rssinsight.com/)

RSS Insight was found on 0.05% of new episodes in May, growing 54.19% from last month.

For episodes that used RSS Insight, here are the top underlying podcast hosts:

1. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "100.00%" >}}
---

### 21. [Firstory](https://firstory.me/)

Firstory was found on 0.04% of new episodes in May, shrinking 2.98% from last month.

Of these, 1.54% had one other tracker.

1.54% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.72%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.28%" >}}
---

### 22. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.02% of new episodes in May, growing 22.35% from last month.

Of these, 8.94% had one other tracker.

8.94% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "100.00%" >}}
---

### 23. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.02% of new episodes in May, growing 8.08% from last month.

Of these, 29.20% had one other tracker, 20.80% had 3 other trackers, 14.60% had 4 other trackers, 11.68% had 6 other trackers, 8.39% had 5 other trackers, 4.38% had 2 other trackers, 1.82% had 8 other trackers, and 0.36% had 7 other trackers.

41.61% also included Podscribe, 40.51% also included Podtrac, 38.69% also included Podsights, 31.39% also included Chartable, 29.93% also included Swap.fm, 24.82% also included Podroll, 17.15% also included Magellan AI, 9.49% also included Spotify, 9.49% also included Adswizz, 9.12% also included Audiotakes, 7.30% also included Podcorn, 6.20% also included Gumshoe, 5.84% also included ArtsAI, 5.84% also included Claritas, 4.01% also included Podder, 4.01% also included OP3, 2.19% also included Veritonic, and 0.36% also included Zencastr.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "51.09%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "12.41%" >}}
3. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "9.12%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.76%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.30%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "2.92%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.55%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.19%" >}}
9. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "1.82%" >}}
10. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "1.46%" >}}
---

### 24. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.01% of new episodes in May, shrinking 6.98% from last month.

Of these, 25.73% had one other tracker, 19.50% had 5 other trackers, 19.09% had 4 other trackers, 7.88% had 2 other trackers, 2.90% had 6 other trackers, 2.90% had 8 other trackers, 1.66% had 3 other trackers, and 1.66% had 7 other trackers.

74.27% also included Podtrac, 45.23% also included Podsights, 44.40% also included Podscribe, 42.32% also included Chartable, 21.99% also included Gumshoe, 12.03% also included Podroll, 9.96% also included OP3, 9.13% also included Claritas, 2.90% also included Podcorn, 2.90% also included Podder, 2.90% also included ArtsAI, 1.66% also included Magellan AI, 1.66% also included Veritonic, and 1.24% also included Spotify.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "45.64%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "13.69%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "9.54%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "6.22%" >}}
5. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "5.81%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "4.98%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.56%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.49%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.66%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.24%" >}}
---

### 25. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in May, growing 1.05% from last month.

Of these, 30.38% had one other tracker, 2.53% had 2 other trackers, 2.53% had 4 other trackers, and 2.53% had 5 other trackers.

21.52% also included Podtrac, 13.29% also included OP3, 5.70% also included Blubrry, 5.06% also included Podcorn, 5.06% also included Podsights, 2.53% also included Podscribe, 2.53% also included Chartable, and 2.53% also included Podder.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "21.52%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "16.46%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "15.19%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "14.56%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "8.23%" >}}
6. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "5.70%" >}}
7. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "5.70%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.70%" >}}
9. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "5.06%" >}}
10. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "1.27%" >}}
---

### 26. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in May, growing 19.39% from last month.

Of these, 22.50% had 3 other trackers, and 15.00% had one other tracker.

35.00% also included Podtrac, 22.50% also included Podscribe, 22.50% also included Podcorn, and 2.50% also included Chartable.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "46.25%" >}}
2. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "18.75%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "11.25%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "10.00%" >}}
5. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "6.25%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.00%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.50%" >}}
---

### 27. [Zencastr](https://zencastr.com/)

Zencastr was found on <0.01% of new episodes in May, shrinking 13.82% from last month.

Of these, 12.99% had one other tracker, 5.19% had 2 other trackers, 1.30% had 6 other trackers, and 1.30% had 7 other trackers.

11.69% also included Podtrac, 7.79% also included Podcorn, 6.49% also included Chartable, 5.19% also included OP3, 2.60% also included Podscribe, 2.60% also included Swap.fm, 2.60% also included Podsights, and 1.30% also included United Podcasters.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "27.27%" >}}
2. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "16.88%" >}}
3. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "15.58%" >}}
4. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "11.69%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.09%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.09%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "6.49%" >}}
8. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "2.60%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.30%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2025-05.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
