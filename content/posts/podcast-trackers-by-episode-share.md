---
title: "Top Podcast Tracking Services by Episode Share (July 2025)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2025-07.png
date: 2025-08-02T15:20:00-04:00
lastmod: 2025-08-02T15:20:00-04:00
draft: false
rssrevision: 2025-07
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.6 million in July 2025), 
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
Month	Podtrac	Adswizz	Podscribe	Podsights	Chartable	Blubrry	Claritas	Podcorn	Spotify	Podroll	Swap.fm	OP3	ArtsAI	Podder	Feedpress	Gumshoe	Veritonic	United Podcasters	Médiamétrie	CoHost Prefix	Podkite	Audiotakes	RSS Insight	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	1.00		1.16	4.06	2.07		2.09							0.32				0.42											1.61
Oct 2021	4.05	1.01		1.20	4.09	2.11		2.13							0.34				0.54											1.61
Nov 2021	4.07	1.02		1.25	4.30	2.01		2.14							0.32				0.57											0.59
Dec 2021	4.06	1.24		1.19	4.42	1.57		2.27							0.19				0.59											
Jan 2022	4.11	1.41		1.21	4.45	1.56		2.31							0.16				0.63											
Feb 2022	4.15	1.44		1.25	4.48	1.53		2.38							0.17				0.58											
Mar 2022	4.37	1.51		1.34	4.72	1.56		2.40							0.17				0.53											
Apr 2022	4.44	1.49		1.33	4.71	1.55		2.33							0.16				0.51											
May 2022	4.49	1.58		1.41	4.87	1.48		2.26							0.17				0.56											
Jun 2022	4.75	1.77		1.54	5.10	1.50		2.06							0.21				0.62								0.02			
Jul 2022	4.70	1.89		1.50	5.10	1.50		2.16							0.25				0.54								0.02			
Aug 2022	4.83	2.08		1.73	5.26	1.51		2.45					0.10		0.20				0.41								0.01			
Sep 2022	7.53	2.26	0.02	1.74	5.40	1.49	0.01	2.45					0.09		0.21				0.52		0.01						0.02	0.02		
Oct 2022	8.24	2.35	0.07	1.81	5.48	1.61	0.02	2.51				0.03	0.10		0.18				0.50		0.01			0.01			0.02	0.04		
Nov 2022	8.11	2.37	0.15	2.03	5.62	1.62	0.03	2.43				0.04	0.10	0.01	0.18				0.50		0.01			0.01			0.02	0.05		
Dec 2022	8.01	2.32	0.03	1.81	5.54	1.61	0.02	2.05				0.05	0.05	0.04	0.18				0.49		0.01			0.01		0.01	0.02	0.05		
Jan 2023	7.85	2.35	0.20	1.88	5.56	1.61	0.06	2.15				0.07	0.10	0.11	0.18				0.54		0.01			0.01		0.01	0.02	0.06		
Feb 2023	7.58	2.29	0.21	1.92	5.51	1.62	0.07	2.30				0.07	0.10	0.11	0.19				0.49		0.01			0.01		0.01	0.02	0.06	0.03	
Mar 2023	7.79	2.25	0.21	2.03	5.53	1.53	0.07	2.22		0.04		0.08	0.11	0.11	0.18		0.04		0.45		0.01			0.01		0.01	0.02	0.06		
Apr 2023	7.66	2.26	0.21	2.00	5.43	1.67	0.07	2.20		0.06		0.09	0.11	0.15	0.17	0.08	0.05		0.45		0.01			0.01		0.01	0.01			
May 2023	7.58	2.27	0.24	2.04	5.59	1.67	0.08	2.28		0.09		0.09	0.11	0.15	0.19	0.07	0.05		0.45		0.01			0.01	0.01	0.01	0.01			
Jun 2023	8.22	2.39	0.26	2.23	5.83	1.64	0.07	1.86		0.10		0.09	0.12	0.15	0.19	0.08	0.05		0.51		0.01			0.01	0.01	0.01	0.01			
Jul 2023	8.60	2.38	0.27	2.52	5.95	1.53	0.07	1.17	0.01	0.14		0.08	0.11	0.14	0.18	0.06	0.06		0.55		0.01			0.01	0.01	0.01	0.01			
Aug 2023	9.19	2.72	0.36	2.76	6.43	1.58	0.08	1.23	0.03	0.16		0.11	0.12	0.15	0.17	0.07	0.07		0.53		0.01	0.04		0.01	0.02	0.01				
Sep 2023	8.46	2.49	0.37	2.47	5.77	1.39	0.10	1.10	0.05	0.13		0.10	0.12	0.15	0.16	0.07	0.06		0.58		0.01	0.05		0.01	0.02	0.01				
Oct 2023	7.90	2.29	0.39	2.28	5.54	1.37	0.10	1.11	0.08	0.12		0.10	0.12	0.16	0.16	0.08	0.06		0.50		0.01	0.05		0.02	0.03	0.01				
Nov 2023	7.65	2.25	0.47	2.33	5.59	1.45	0.11	1.14	0.11	0.12		0.13	0.12	0.16	0.17	0.10	0.06		0.33		0.01	0.06		0.01	0.03					
Dec 2023	7.48	2.20	0.54	2.19	5.60	1.53	0.11	1.12	0.12	0.12		0.11	0.12	0.16	0.16	0.09	0.06		0.33		0.01	0.06		0.01	0.03					
Jan 2024	7.64	2.37	0.65	2.21	5.61	1.55	0.12	1.17	0.15	0.11		0.13	0.14	0.16	0.17	0.10	0.06	0.01	0.25		0.01	0.08		0.01	0.01					
Feb 2024	7.69	2.38	0.69	2.22	5.58	1.52	0.13	1.21	0.22	0.12		0.16	0.13	0.17	0.17	0.11	0.06	0.01	0.22		0.01	0.09		0.01						
Mar 2024	9.01	2.53	0.69	2.19	5.46	1.54	0.14	1.14	0.25	0.12		0.14	0.12	0.16	0.16	0.10	0.06	0.01	0.22		0.01	0.09		0.01						
Apr 2024	10.78	2.53	0.73	2.16	5.47	1.51	0.15	1.24	0.27	0.34		0.18	0.13	0.17	0.15	0.11	0.07	0.01	0.19	0.01	0.01	0.07		0.01						
May 2024	11.59	2.75	0.83	2.24	5.63	1.50	0.15	1.20	0.30	0.36		0.18	0.14	0.16	0.15	0.11	0.07	0.01	0.09	0.01	0.01	0.06		0.01						
Jun 2024	11.54	2.88	0.91	2.34	6.06	1.52	0.16	0.71	0.32	0.37	0.03	0.20	0.16	0.15	0.15	0.11	0.07	0.01	0.10	0.01	0.01	0.07		0.01						
Jul 2024	12.34	2.83	1.01	2.45	6.80	1.65	0.18	0.71	0.34	0.43	0.06	0.20	0.17	0.15	0.15	0.12	0.07	0.01	0.09	0.01	0.01	0.09		0.01						
Aug 2024	14.22	2.96	1.11	2.48	6.72	1.70	0.18	0.81	0.35	0.45	0.12	0.19	0.18	0.35	0.14	0.12	0.08	0.01	0.08	0.01	0.01	0.11		0.01						
Sep 2024	12.95	3.13	1.18	2.26	5.99	1.44	0.18	0.72	0.35	0.44	0.12	0.24	0.18	0.42	0.15	0.13	0.08	0.01	0.07	0.01	0.01	0.13		0.01						
Oct 2024	12.24	3.23	1.23	2.35	5.49	1.53	0.19	0.66	0.40	0.43	0.17	0.27	0.18	0.39	0.14	0.12	0.09	0.01	0.09	0.01	0.01	0.14		0.01						
Nov 2024	11.86	3.21	1.27	2.31	4.66	1.52	0.21	0.63	0.44	0.43	0.19	0.29	0.17	0.41	0.11	0.12	0.08	0.01	0.10	0.01	0.01	0.14		0.01						
Dec 2024	12.56	3.06	1.29	2.13	2.29	1.40	0.21	0.62	0.45	0.43	0.24	0.29	0.18	0.54	0.09	0.12	0.08	0.01	0.09	0.01	0.01	0.15		0.01						
Jan 2025	12.62	2.92	1.31	1.73	1.54	1.36	0.21	0.66	0.41	0.46	0.27	0.34	0.19	0.54	0.12	0.13	0.08	0.01	0.04	0.01	0.01	0.16		0.01						
Feb 2025	12.47	2.74	1.25	1.70	1.43	1.45	0.22	0.66	0.36	0.46	0.28	0.33	0.18	0.48	0.14	0.12	0.08	0.01	0.01	0.01	0.01	0.16		0.01						
Mar 2025	12.18	2.87	1.28	1.51	1.18	1.25	0.21	0.67	0.33	0.47	0.27	0.33	0.18	0.36	0.14	0.13	0.07	0.01	0.01	0.01	0.01	0.25	0.04	0.01						
Apr 2025	12.35	2.97	1.53	1.64	1.28	1.26	0.23	0.68	0.44	0.48	0.30	0.34	0.19	0.33	0.13	0.12	0.08	0.01	0.02	0.01	0.01	0.41	0.03	0.01						
May 2025	12.48	2.97	1.61	1.74	1.31	1.40	0.24	0.64	0.46	0.46	0.33	0.39	0.20	0.22	0.13	0.12	0.07	0.02	0.02	0.01	0.01	0.40	0.05							
Jun 2025	12.99	2.73	1.65	1.70	1.30	1.34	0.26	0.65	0.47	0.46	0.35	0.39	0.21	0.20	0.13	0.12	0.07	0.02	0.02	0.01	0.01	0.40	0.04							
Jul 2025	13.83	2.87	1.76	1.71	1.30	1.16	0.72	0.66	0.50	0.48	0.39	0.33	0.23	0.20	0.13	0.12	0.07	0.02	0.01	0.01	0.01									
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} have historically been the top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podscribe	Podsights	Blubrry	Claritas	Podcorn	Spotify	Podroll	Swap.fm	OP3	ArtsAI	Podder	Feedpress	Gumshoe	Veritonic	United Podcasters	Médiamétrie	CoHost Prefix	Podkite	Audiotakes	RSS Insight	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	1.00		1.16	2.07		2.09							0.32				0.42											1.61
Oct 2021	1.01		1.20	2.11		2.13							0.34				0.54											1.61
Nov 2021	1.02		1.25	2.01		2.14							0.32				0.57											0.59
Dec 2021	1.24		1.19	1.57		2.27							0.19				0.59											
Jan 2022	1.41		1.21	1.56		2.31							0.16				0.63											
Feb 2022	1.44		1.25	1.53		2.38							0.17				0.58											
Mar 2022	1.51		1.34	1.56		2.40							0.17				0.53											
Apr 2022	1.49		1.33	1.55		2.33							0.16				0.51											
May 2022	1.58		1.41	1.48		2.26							0.17				0.56											
Jun 2022	1.77		1.54	1.50		2.06							0.21				0.62								0.02			
Jul 2022	1.89		1.50	1.50		2.16							0.25				0.54								0.02			
Aug 2022	2.08		1.73	1.51		2.45					0.10		0.20				0.41								0.01			
Sep 2022	2.26	0.02	1.74	1.49	0.01	2.45					0.09		0.21				0.52		0.01						0.02	0.02		
Oct 2022	2.35	0.07	1.81	1.61	0.02	2.51				0.03	0.10		0.18				0.50		0.01			0.01			0.02	0.04		
Nov 2022	2.37	0.15	2.03	1.62	0.03	2.43				0.04	0.10	0.01	0.18				0.50		0.01			0.01			0.02	0.05		
Dec 2022	2.32	0.03	1.81	1.61	0.02	2.05				0.05	0.05	0.04	0.18				0.49		0.01			0.01		0.01	0.02	0.05		
Jan 2023	2.35	0.20	1.88	1.61	0.06	2.15				0.07	0.10	0.11	0.18				0.54		0.01			0.01		0.01	0.02	0.06		
Feb 2023	2.29	0.21	1.92	1.62	0.07	2.30				0.07	0.10	0.11	0.19				0.49		0.01			0.01		0.01	0.02	0.06	0.03	
Mar 2023	2.25	0.21	2.03	1.53	0.07	2.22		0.04		0.08	0.11	0.11	0.18		0.04		0.45		0.01			0.01		0.01	0.02	0.06		
Apr 2023	2.26	0.21	2.00	1.67	0.07	2.20		0.06		0.09	0.11	0.15	0.17	0.08	0.05		0.45		0.01			0.01		0.01	0.01			
May 2023	2.27	0.24	2.04	1.67	0.08	2.28		0.09		0.09	0.11	0.15	0.19	0.07	0.05		0.45		0.01			0.01	0.01	0.01	0.01			
Jun 2023	2.39	0.26	2.23	1.64	0.07	1.86		0.10		0.09	0.12	0.15	0.19	0.08	0.05		0.51		0.01			0.01	0.01	0.01	0.01			
Jul 2023	2.38	0.27	2.52	1.53	0.07	1.17	0.01	0.14		0.08	0.11	0.14	0.18	0.06	0.06		0.55		0.01			0.01	0.01	0.01	0.01			
Aug 2023	2.72	0.36	2.76	1.58	0.08	1.23	0.03	0.16		0.11	0.12	0.15	0.17	0.07	0.07		0.53		0.01	0.04		0.01	0.02	0.01				
Sep 2023	2.49	0.37	2.47	1.39	0.10	1.10	0.05	0.13		0.10	0.12	0.15	0.16	0.07	0.06		0.58		0.01	0.05		0.01	0.02	0.01				
Oct 2023	2.29	0.39	2.28	1.37	0.10	1.11	0.08	0.12		0.10	0.12	0.16	0.16	0.08	0.06		0.50		0.01	0.05		0.02	0.03	0.01				
Nov 2023	2.25	0.47	2.33	1.45	0.11	1.14	0.11	0.12		0.13	0.12	0.16	0.17	0.10	0.06		0.33		0.01	0.06		0.01	0.03					
Dec 2023	2.20	0.54	2.19	1.53	0.11	1.12	0.12	0.12		0.11	0.12	0.16	0.16	0.09	0.06		0.33		0.01	0.06		0.01	0.03					
Jan 2024	2.37	0.65	2.21	1.55	0.12	1.17	0.15	0.11		0.13	0.14	0.16	0.17	0.10	0.06	0.01	0.25		0.01	0.08		0.01	0.01					
Feb 2024	2.38	0.69	2.22	1.52	0.13	1.21	0.22	0.12		0.16	0.13	0.17	0.17	0.11	0.06	0.01	0.22		0.01	0.09		0.01						
Mar 2024	2.53	0.69	2.19	1.54	0.14	1.14	0.25	0.12		0.14	0.12	0.16	0.16	0.10	0.06	0.01	0.22		0.01	0.09		0.01						
Apr 2024	2.53	0.73	2.16	1.51	0.15	1.24	0.27	0.34		0.18	0.13	0.17	0.15	0.11	0.07	0.01	0.19	0.01	0.01	0.07		0.01						
May 2024	2.75	0.83	2.24	1.50	0.15	1.20	0.30	0.36		0.18	0.14	0.16	0.15	0.11	0.07	0.01	0.09	0.01	0.01	0.06		0.01						
Jun 2024	2.88	0.91	2.34	1.52	0.16	0.71	0.32	0.37	0.03	0.20	0.16	0.15	0.15	0.11	0.07	0.01	0.10	0.01	0.01	0.07		0.01						
Jul 2024	2.83	1.01	2.45	1.65	0.18	0.71	0.34	0.43	0.06	0.20	0.17	0.15	0.15	0.12	0.07	0.01	0.09	0.01	0.01	0.09		0.01						
Aug 2024	2.96	1.11	2.48	1.70	0.18	0.81	0.35	0.45	0.12	0.19	0.18	0.35	0.14	0.12	0.08	0.01	0.08	0.01	0.01	0.11		0.01						
Sep 2024	3.13	1.18	2.26	1.44	0.18	0.72	0.35	0.44	0.12	0.24	0.18	0.42	0.15	0.13	0.08	0.01	0.07	0.01	0.01	0.13		0.01						
Oct 2024	3.23	1.23	2.35	1.53	0.19	0.66	0.40	0.43	0.17	0.27	0.18	0.39	0.14	0.12	0.09	0.01	0.09	0.01	0.01	0.14		0.01						
Nov 2024	3.21	1.27	2.31	1.52	0.21	0.63	0.44	0.43	0.19	0.29	0.17	0.41	0.11	0.12	0.08	0.01	0.10	0.01	0.01	0.14		0.01						
Dec 2024	3.06	1.29	2.13	1.40	0.21	0.62	0.45	0.43	0.24	0.29	0.18	0.54	0.09	0.12	0.08	0.01	0.09	0.01	0.01	0.15		0.01						
Jan 2025	2.92	1.31	1.73	1.36	0.21	0.66	0.41	0.46	0.27	0.34	0.19	0.54	0.12	0.13	0.08	0.01	0.04	0.01	0.01	0.16		0.01						
Feb 2025	2.74	1.25	1.70	1.45	0.22	0.66	0.36	0.46	0.28	0.33	0.18	0.48	0.14	0.12	0.08	0.01	0.01	0.01	0.01	0.16		0.01						
Mar 2025	2.87	1.28	1.51	1.25	0.21	0.67	0.33	0.47	0.27	0.33	0.18	0.36	0.14	0.13	0.07	0.01	0.01	0.01	0.01	0.25	0.04	0.01						
Apr 2025	2.97	1.53	1.64	1.26	0.23	0.68	0.44	0.48	0.30	0.34	0.19	0.33	0.13	0.12	0.08	0.01	0.02	0.01	0.01	0.41	0.03	0.01						
May 2025	2.97	1.61	1.74	1.40	0.24	0.64	0.46	0.46	0.33	0.39	0.20	0.22	0.13	0.12	0.07	0.02	0.02	0.01	0.01	0.40	0.05							
Jun 2025	2.73	1.65	1.70	1.34	0.26	0.65	0.47	0.46	0.35	0.39	0.21	0.20	0.13	0.12	0.07	0.02	0.02	0.01	0.01	0.40	0.04							
Jul 2025	2.87	1.76	1.71	1.16	0.72	0.66	0.50	0.48	0.39	0.33	0.23	0.20	0.13	0.12	0.07	0.02	0.01	0.01	0.01									
{{< /graph >}}

---

### Overall

At least one tracker was found on 19.38% of new episodes in July, growing 4.79% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "47.36%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.07%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "9.98%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.81%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.95%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.78%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.01%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.29%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.29%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.26%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of July 2025.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 13.83% of new episodes in July, growing 6.11% from last month.

Of these, 9.24% had one other tracker, 6.93% had 2 other trackers, 1.44% had 3 other trackers, 1.23% had 4 other trackers, 1.02% had 5 other trackers, 0.49% had 6 other trackers, 0.19% had 7 other trackers, 0.03% had 8 other trackers, and 0.01% had 9 other trackers.

8.00% also included Podsights, 6.00% also included Podscribe, 5.93% also included Adswizz, 4.96% also included Chartable, 2.89% also included Podroll, 2.52% also included Magellan AI, 2.31% also included Spotify, 2.07% also included Claritas, 1.54% also included Swap.fm, 1.15% also included Podcorn, 1.03% also included ArtsAI, 0.97% also included Blubrry, 0.93% also included OP3, 0.50% also included Gumshoe, 0.46% also included Podder, 0.43% also included Veritonic, 0.07% also included CoHost Prefix, 0.05% also included United Podcasters, 0.04% also included Feedpress, 0.02% also included Podkite, 0.01% also included Médiamétrie, 0.01% also included AdBarker, and <0.01% also included Podcards.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "66.16%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "8.10%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.38%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.04%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.05%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.79%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.47%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.85%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.57%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.50%" >}}
---

### 2. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.87% of new episodes in July, growing 4.77% from last month.

Of these, 16.69% had 2 other trackers, 13.92% had one other tracker, 9.44% had 3 other trackers, 2.41% had 4 other trackers, 1.60% had 5 other trackers, 0.66% had 6 other trackers, 0.30% had 7 other trackers, and 0.11% had 8 other trackers.

28.59% also included Podtrac, 16.71% also included Podscribe, 14.00% also included Magellan AI, 12.85% also included Podroll, 12.65% also included Claritas, 3.24% also included Podsights, 3.14% also included Spotify, 2.85% also included Swap.fm, 1.40% also included ArtsAI, 1.13% also included Chartable, 1.04% also included Blubrry, 0.86% also included Podder, 0.67% also included Veritonic, 0.65% also included OP3, 0.34% also included Podcorn, 0.06% also included Gumshoe, and 0.04% also included United Podcasters.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "64.05%" >}}
2. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "6.86%" >}}
3. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "5.25%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "4.91%" >}}
5. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "4.53%" >}}
6. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "3.03%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.81%" >}}
8. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "2.22%" >}}
9. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.33%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.76%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 2.59% of new episodes in July, growing 3.06% from last month.

Of these, 57.33% also included Podtrac, 31.70% also included Podscribe, 16.96% also included Magellan AI, 14.35% also included Claritas, 9.09% also included Swap.fm, 8.10% also included Adswizz, 6.98% also included ArtsAI, 3.20% also included Podcorn, 3.19% also included Gumshoe, 3.03% also included OP3, 2.92% also included Podroll, 2.71% also included Veritonic, 1.45% also included Podder, 0.37% also included United Podcasters, 0.32% also included CoHost Prefix, 0.26% also included Blubrry, 0.07% also included Feedpress, 0.06% also included Podkite, 0.03% also included Firstory, 0.01% also included Zencastr, <0.01% also included AdBarker, and <0.01% also included Podcards.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "56.99%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "16.36%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.81%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.35%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.78%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.94%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.66%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.36%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.05%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.94%" >}}
---

### 3. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 1.76% of new episodes in July, growing 9.00% from last month.

Of these, 24.09% had 3 other trackers, 20.35% had one other tracker, 15.02% had 4 other trackers, 12.86% had 2 other trackers, 10.46% had 5 other trackers, 4.43% had 6 other trackers, 1.50% had 7 other trackers, 0.20% had 8 other trackers, and 0.04% had 9 other trackers.

47.10% also included Podtrac, 45.20% also included Magellan AI, 40.01% also included Claritas, 31.98% also included Podsights, 27.18% also included Adswizz, 17.09% also included Spotify, 16.46% also included Chartable, 11.60% also included ArtsAI, 9.30% also included Swap.fm, 4.52% also included Podcorn, 4.12% also included Podroll, 4.11% also included Gumshoe, 3.76% also included OP3, 3.50% also included Veritonic, 2.84% also included Podder, 0.42% also included CoHost Prefix, 0.41% also included United Podcasters, 0.18% also included Blubrry, 0.02% also included Podkite, and <0.01% also included Podcards.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "37.71%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "25.78%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.13%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.13%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.54%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.86%" >}}
7. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "3.29%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.97%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.49%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.24%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.71% of new episodes in July, growing 2.39% from last month.

Of these, 33.52% had one other tracker, 22.79% had 2 other trackers, 10.59% had 4 other trackers, 9.96% had 3 other trackers, 7.89% had 5 other trackers, 3.60% had 6 other trackers, 1.23% had 7 other trackers, 0.20% had 8 other trackers, and 0.04% had 9 other trackers.

64.92% also included Podtrac, 41.57% also included Chartable, 33.06% also included Podscribe, 18.61% also included Magellan AI, 13.30% also included Claritas, 11.27% also included Swap.fm, 6.91% also included ArtsAI, 5.68% also included Spotify, 5.45% also included Adswizz, 4.20% also included Podcorn, 4.07% also included OP3, 4.05% also included Gumshoe, 3.55% also included Veritonic, 3.12% also included Podroll, 1.98% also included Podder, 0.43% also included CoHost Prefix, 0.40% also included United Podcasters, 0.31% also included Blubrry, 0.11% also included Feedpress, 0.05% also included Podkite, and <0.01% also included Podcards.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "62.86%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "20.13%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.82%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.82%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.16%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.60%" >}}
7. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.43%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.03%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.95%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.66%" >}}
---

### 5. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 1.30% of new episodes in July, growing 2.02% from last month.

Of these, 34.27% had 2 other trackers, 21.53% had one other tracker, 7.86% had 3 other trackers, 7.52% had 4 other trackers, 4.57% had 5 other trackers, 2.67% had 6 other trackers, 0.29% had 7 other trackers, and 0.02% had 8 other trackers.

54.38% also included Podsights, 52.61% also included Podtrac, 22.25% also included Podscribe, 13.08% also included Magellan AI, 11.97% also included Swap.fm, 11.38% also included Spotify, 5.50% also included Claritas, 2.89% also included Podroll, 2.48% also included Adswizz, 1.48% also included Podder, 1.42% also included Veritonic, 1.28% also included ArtsAI, 1.24% also included Gumshoe, 0.79% also included OP3, 0.76% also included Podcorn, 0.50% also included CoHost Prefix, 0.42% also included United Podcasters, 0.15% also included Feedpress, 0.06% also included Blubrry, 0.05% also included Firstory, 0.02% also included Podkite, 0.02% also included Zencastr, 0.01% also included AdBarker, and <0.01% also included Podcards.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "84.74%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.34%" >}}
3. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.30%" >}}
4. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.50%" >}}
5. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "0.49%" >}}
6. {{< a "https://cloud.google.com/" "Google Cloud" >}} {{< span "weak" "0.40%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.39%" >}}
8. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.24%" >}}
9. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.23%" >}}
10. {{< a "https://podetize.com/" "Podetize" >}} {{< span "weak" "0.20%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.16% of new episodes in July, shrinking 2.42% from last month.

Of these, 15.05% had one other tracker, 0.59% had 2 other trackers, 0.26% had 3 other trackers, 0.12% had 4 other trackers, 0.03% had 5 other trackers, and 0.01% had 6 other trackers.

11.58% also included Podtrac, 2.57% also included Adswizz, 1.42% also included Feedpress, 0.46% also included Podsights, 0.34% also included Swap.fm, 0.28% also included Podscribe, 0.27% also included OP3, 0.21% also included Podcorn, 0.17% also included Podder, 0.12% also included Magellan AI, 0.09% also included Spotify, 0.07% also included Chartable, 0.05% also included Podkite, 0.02% also included ArtsAI, 0.01% also included Claritas, and 0.01% also included Veritonic.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "49.37%" >}}
2. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "5.43%" >}}
3. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.75%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.73%" >}}
5. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "2.34%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.99%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.18%" >}}
8. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "0.92%" >}}
9. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "0.69%" >}}
10. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.65%" >}}
---

### 7. [Magellan AI](https://www.magellan.ai/prefix)

Magellan AI was found on 1.09% of new episodes in July, growing 12.00% from last month.

Of these, 29.37% had 3 other trackers, 16.48% had 4 other trackers, 12.05% had 5 other trackers, 8.54% had one other tracker, 7.71% had 2 other trackers, 5.96% had 6 other trackers, 2.24% had 7 other trackers, and 0.29% had 8 other trackers.

72.95% also included Podscribe, 52.74% also included Claritas, 36.75% also included Adswizz, 31.90% also included Podtrac, 29.06% also included Podsights, 15.62% also included Chartable, 14.98% also included Spotify, 11.89% also included ArtsAI, 11.16% also included Swap.fm, 5.31% also included Veritonic, 4.55% also included Podroll, 2.01% also included Podder, 1.33% also included Gumshoe, 0.87% also included OP3, 0.51% also included United Podcasters, 0.18% also included Podcorn, 0.13% also included Blubrry, and 0.05% also included CoHost Prefix.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "34.26%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "27.02%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "12.80%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.88%" >}}
5. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "5.88%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.91%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.60%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.95%" >}}
9. {{< a "https://www.americanpublicmedia.org/" "American Public Media" >}} {{< span "weak" "1.29%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.15%" >}}
---

### 8. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.72% of new episodes in July, growing 10.30% from last month.

Of these, 42.50% had 3 other trackers, 22.98% had 4 other trackers, 14.90% had 5 other trackers, 8.55% had 6 other trackers, 5.67% had 2 other trackers, 3.35% had 7 other trackers, 1.03% had one other tracker, and 0.44% had 8 other trackers.

98.22% also included Podscribe, 80.20% also included Magellan AI, 50.51% also included Adswizz, 39.91% also included Podtrac, 31.57% also included Podsights, 27.55% also included Spotify, 24.06% also included ArtsAI, 9.98% also included Chartable, 7.95% also included Veritonic, 5.47% also included Podroll, 5.36% also included Swap.fm, 1.32% also included Podder, 0.93% also included OP3, 0.92% also included Gumshoe, 0.37% also included United Podcasters, 0.22% also included CoHost Prefix, 0.02% also included Blubrry, and 0.02% also included Podcorn.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "50.75%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "21.97%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.29%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "7.26%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.56%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.50%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.93%" >}}
8. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.24%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.22%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.11%" >}}
---

### 9. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.66% of new episodes in July, growing 1.97% from last month.

Of these, 12.76% had one other tracker, 5.61% had 5 other trackers, 4.03% had 2 other trackers, 2.21% had 4 other trackers, 2.07% had 3 other trackers, 1.55% had 6 other trackers, 0.12% had 9 other trackers, 0.08% had 7 other trackers, and 0.05% had 8 other trackers.

24.26% also included Podtrac, 12.14% also included Podscribe, 10.91% also included Podsights, 9.74% also included OP3, 7.85% also included Gumshoe, 2.70% also included Spotify, 2.13% also included Podroll, 1.50% also included Chartable, 1.49% also included Adswizz, 1.11% also included Podder, 0.38% also included Blubrry, 0.30% also included Magellan AI, 0.20% also included Feedpress, 0.12% also included Swap.fm, 0.12% also included CoHost Prefix, 0.11% also included Podkite, 0.11% also included United Podcasters, 0.03% also included Zencastr, and 0.02% also included Claritas.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "23.84%" >}}
2. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "12.08%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "11.54%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "11.22%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "7.56%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.37%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.51%" >}}
8. {{< a "https://www.wideorbit.com/" "WideOrbit" >}} {{< span "weak" "5.50%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.52%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.50%" >}}
---

### 10. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.50% of new episodes in July, growing 7.49% from last month.

Of these, 30.82% had 2 other trackers, 13.82% had 4 other trackers, 12.54% had 5 other trackers, 9.96% had 6 other trackers, 7.91% had 3 other trackers, 7.06% had one other tracker, 4.00% had 7 other trackers, 0.68% had 8 other trackers, and 0.15% had 9 other trackers.

63.33% also included Podtrac, 59.67% also included Podscribe, 39.18% also included Claritas, 32.41% also included Magellan AI, 29.37% also included Chartable, 19.17% also included Podsights, 18.77% also included ArtsAI, 17.86% also included Adswizz, 5.58% also included Veritonic, 3.88% also included OP3, 3.63% also included Podroll, 3.52% also included Podcorn, 3.52% also included Gumshoe, 2.92% also included Swap.fm, 1.40% also included Podder, 0.25% also included United Podcasters, 0.23% also included CoHost Prefix, 0.20% also included Blubrry, and 0.06% also included Podkite.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "39.18%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "16.94%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "15.84%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "12.41%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.90%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.59%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.75%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.21%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.13%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.83%" >}}
---

### 11. [Podroll](https://podroll.fm/)

Podroll was found on 0.48% of new episodes in July, growing 3.32% from last month.

Of these, 72.59% had 2 other trackers, 7.53% had one other tracker, 7.17% had 4 other trackers, 4.39% had 6 other trackers, 3.86% had 3 other trackers, 1.61% had 5 other trackers, 0.51% had 7 other trackers, 0.16% had 9 other trackers, and 0.07% had 8 other trackers.

83.34% also included Podtrac, 76.82% also included Adswizz, 15.14% also included Podscribe, 11.10% also included Podsights, 10.37% also included Magellan AI, 8.20% also included Claritas, 7.85% also included Chartable, 7.14% also included Swap.fm, 3.82% also included Spotify, 2.91% also included Podcorn, 1.57% also included OP3, 1.08% also included Gumshoe, 1.04% also included United Podcasters, 0.99% also included ArtsAI, 0.76% also included Podder, 0.41% also included CoHost Prefix, 0.32% also included Veritonic, and 0.01% also included Podkite.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "76.88%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.89%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.66%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.81%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "1.61%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.13%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.08%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.42%" >}}
9. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "0.20%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.12%" >}}
---

### 12. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.39% of new episodes in July, growing 14.56% from last month.

Of these, 27.83% had 2 other trackers, 16.73% had one other tracker, 16.19% had 3 other trackers, 14.43% had 5 other trackers, 14.03% had 4 other trackers, 2.77% had 6 other trackers, 1.35% had 7 other trackers, and 0.06% had 8 other trackers.

54.42% also included Podtrac, 48.96% also included Podsights, 41.79% also included Podscribe, 39.76% also included Chartable, 31.07% also included Magellan AI, 20.84% also included Adswizz, 10.00% also included ArtsAI, 9.81% also included Claritas, 8.73% also included Podroll, 3.75% also included Spotify, 1.56% also included OP3, 1.47% also included United Podcasters, 1.35% also included Gumshoe, 1.00% also included Blubrry, 0.66% also included Veritonic, 0.43% also included Podder, 0.19% also included Podcorn, and 0.02% also included Podcards.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "61.28%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "20.81%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.31%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.12%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "3.98%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.21%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.14%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.14%" >}}
---

### 13. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.33% of new episodes in July, shrinking 11.44% from last month.

Of these, 18.98% had one other tracker, 11.89% had 5 other trackers, 5.86% had 2 other trackers, 4.01% had 3 other trackers, 3.80% had 6 other trackers, 3.52% had 4 other trackers, 0.32% had 7 other trackers, 0.23% had 9 other trackers, and 0.02% had 8 other trackers.

38.54% also included Podtrac, 20.78% also included Podsights, 19.85% also included Podscribe, 19.13% also included Podcorn, 16.54% also included Gumshoe, 5.86% also included Spotify, 5.54% also included Adswizz, 3.10% also included Chartable, 2.84% also included Magellan AI, 2.25% also included Podroll, 2.00% also included Claritas, 1.95% also included Podder, 1.83% also included Swap.fm, 0.95% also included Blubrry, 0.93% also included ArtsAI, 0.55% also included CoHost Prefix, 0.45% also included Podkite, 0.21% also included United Podcasters, 0.13% also included Feedpress, and 0.06% also included Zencastr.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "25.97%" >}}
2. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "12.23%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "8.58%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.01%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.37%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.27%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.91%" >}}
8. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "2.27%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.06%" >}}
10. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.98%" >}}
---

### 14. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.23% of new episodes in July, growing 9.31% from last month.

Of these, 33.51% had 4 other trackers, 22.96% had 5 other trackers, 10.38% had 7 other trackers, 10.11% had 6 other trackers, 9.83% had 2 other trackers, 8.80% had 3 other trackers, 2.97% had one other tracker, and 1.39% had 8 other trackers.

89.84% also included Podscribe, 75.90% also included Claritas, 62.83% also included Podtrac, 57.05% also included Magellan AI, 51.80% also included Podsights, 41.64% also included Spotify, 17.68% also included Adswizz, 17.24% also included Swap.fm, 15.91% also included Veritonic, 7.33% also included Chartable, 2.08% also included Podroll, 1.36% also included OP3, 0.64% also included Podder, 0.36% also included United Podcasters, 0.28% also included CoHost Prefix, 0.22% also included Gumshoe, and 0.11% also included Blubrry.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "28.35%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "26.54%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "17.60%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "15.52%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "9.86%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.78%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.14%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.11%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.11%" >}}
---

### 15. [Podder](https://www.podderapp.com/)

Podder was found on 0.20% of new episodes in July, growing 3.85% from last month.

Of these, 16.68% had 2 other trackers, 11.31% had one other tracker, 7.72% had 4 other trackers, 6.30% had 3 other trackers, 4.08% had 5 other trackers, 1.05% had 6 other trackers, 0.37% had 9 other trackers, 0.22% had 7 other trackers, and 0.03% had 8 other trackers.

31.42% also included Podtrac, 24.44% also included Podscribe, 16.47% also included Podsights, 12.08% also included Adswizz, 10.72% also included Magellan AI, 9.45% also included Chartable, 4.63% also included Claritas, 3.55% also included Podcorn, 3.46% also included Spotify, 3.18% also included OP3, 1.79% also included Podroll, 1.79% also included Gumshoe, 0.96% also included Blubrry, 0.83% also included Swap.fm, 0.71% also included ArtsAI, 0.37% also included CoHost Prefix, 0.22% also included United Podcasters, and 0.19% also included Podkite.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "46.96%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "17.21%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.97%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "8.22%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.58%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.27%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.90%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.22%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.74%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.71%" >}}
---

### 16. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.13% of new episodes in July, shrinking 2.97% from last month.

Of these, 18.56% had one other tracker, and 1.48% had 2 other trackers.

12.83% also included Blubrry, 4.05% also included Podtrac, 1.48% also included Podsights, 1.48% also included Chartable, 1.04% also included Podcorn, 0.35% also included OP3, and 0.30% also included CoHost Prefix.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "55.58%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "10.02%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.53%" >}}
4. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "5.08%" >}}
5. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.81%" >}}
6. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "2.71%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.62%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.78%" >}}
9. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.09%" >}}
10. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "1.09%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.12% of new episodes in July, growing 1.37% from last month.

Of these, 34.28% had 5 other trackers, 13.32% had 4 other trackers, 11.76% had one other tracker, 9.04% had 2 other trackers, 7.33% had 6 other trackers, 7.22% had 3 other trackers, 1.34% had 7 other trackers, 0.64% had 9 other trackers, and 0.05% had 8 other trackers.

61.34% also included Podscribe, 58.66% also included Podtrac, 58.45% also included Podsights, 46.79% also included OP3, 43.64% also included Podcorn, 15.03% also included Spotify, 13.69% also included Chartable, 12.30% also included Magellan AI, 5.61% also included Claritas, 4.49% also included Swap.fm, 4.39% also included Podroll, 3.58% also included CoHost Prefix, 3.10% also included Podder, 1.55% also included Adswizz, 1.55% also included Veritonic, 1.02% also included United Podcasters, 0.43% also included ArtsAI, and 0.05% also included Podkite.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "48.61%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.37%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "21.18%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.35%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.87%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.18%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.70%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.27%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.21%" >}}
10. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.16%" >}}
---

### 18. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.07% of new episodes in July, growing 8.69% from last month.

Of these, 29.40% had 7 other trackers, 25.43% had 6 other trackers, 18.88% had 5 other trackers, 15.60% had 3 other trackers, 4.40% had 4 other trackers, 4.31% had 8 other trackers, 0.95% had 2 other trackers, and 0.34% had one other tracker.

84.22% also included Podscribe, 82.50% also included Podsights, 81.55% also included Podtrac, 79.05% also included Magellan AI, 77.84% also included Claritas, 49.40% also included ArtsAI, 38.45% also included Spotify, 26.38% also included Adswizz, 25.17% also included Chartable, 3.53% also included Swap.fm, 2.50% also included Gumshoe, 2.07% also included Podroll, 0.52% also included United Podcasters, 0.52% also included CoHost Prefix, and 0.17% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "62.67%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "26.21%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.74%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.93%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.90%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.52%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.43%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.26%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.26%" >}}
10. {{< a "https://www.thisamericanlife.org/" "This American Life" >}} {{< span "weak" "0.09%" >}}
---

### 19. [Firstory](https://firstory.me/)

Firstory was found on 0.04% of new episodes in July, growing 1.18% from last month.

Of these, 1.63% had one other tracker.

1.63% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.85%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.15%" >}}
---

### 20. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.02% of new episodes in July, growing 9.57% from last month.

Of these, 23.99% had 3 other trackers, 23.25% had one other tracker, 14.76% had 6 other trackers, 14.02% had 4 other trackers, 11.44% had 2 other trackers, 6.27% had 5 other trackers, and 1.48% had 8 other trackers.

42.80% also included Podtrac, 41.70% also included Podscribe, 40.22% also included Podsights, 33.58% also included Swap.fm, 32.84% also included Magellan AI, 32.10% also included Chartable, 29.15% also included Podroll, 15.50% also included Claritas, 7.38% also included Spotify, 7.01% also included Gumshoe, 5.90% also included Adswizz, 4.80% also included ArtsAI, 4.06% also included Podcorn, 4.06% also included OP3, 2.58% also included Podder, and 2.21% also included Veritonic.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "49.08%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "11.44%" >}}
3. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "10.70%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.49%" >}}
5. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "5.17%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.17%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.17%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.21%" >}}
9. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "1.85%" >}}
10. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "0.74%" >}}
---

### 21. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.01% of new episodes in July, shrinking 27.65% from last month.

Of these, 10.18% had one other tracker.

10.18% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "100.00%" >}}
---

### 22. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.01% of new episodes in July, growing 9.98% from last month.

Of these, 23.64% had 5 other trackers, 19.09% had one other tracker, 18.64% had 4 other trackers, 7.27% had 2 other trackers, 5.45% had 9 other trackers, 4.55% had 6 other trackers, 2.73% had 7 other trackers, and 1.82% had 3 other trackers.

72.73% also included Podtrac, 52.73% also included Podsights, 52.73% also included Podscribe, 47.27% also included Chartable, 30.45% also included Gumshoe, 14.09% also included Podroll, 13.18% also included OP3, 11.36% also included Claritas, 8.18% also included Spotify, 5.45% also included Podcorn, 5.45% also included Podder, 4.55% also included ArtsAI, 3.64% also included Magellan AI, 2.73% also included Feedpress, and 2.73% also included Veritonic.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "53.64%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "9.09%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "8.18%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.27%" >}}
5. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "4.55%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.18%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.73%" >}}
8. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "2.73%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.82%" >}}
10. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.82%" >}}
---

### 23. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in July, growing 18.28% from last month.

Of these, 30.77% had one other tracker, 5.92% had 5 other trackers, 4.73% had 2 other trackers, and 0.59% had 8 other trackers.

26.04% also included Podtrac, 14.20% also included OP3, 8.28% also included Podsights, 6.51% also included Podcorn, 5.33% also included Blubrry, 3.55% also included Podscribe, 3.55% also included Podder, 2.96% also included Chartable, 2.96% also included Spotify, 0.59% also included Podroll, and 0.59% also included Gumshoe.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "24.85%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "15.38%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "14.79%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "13.61%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "8.28%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.28%" >}}
7. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "5.33%" >}}
8. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "4.73%" >}}
9. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "2.37%" >}}
10. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "1.78%" >}}
---

### 24. [Zencastr](https://zencastr.com/)

Zencastr was found on <0.01% of new episodes in July, shrinking 8.97% from last month.

Of these, 6.56% had one other tracker, and 4.92% had 2 other trackers.

6.56% also included Chartable, 4.92% also included OP3, and 4.92% also included Podcorn.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "32.79%" >}}
2. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "19.67%" >}}
3. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "14.75%" >}}
4. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "14.75%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "13.11%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.92%" >}}
---

### 25. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in July, shrinking 2.35% from last month.

Of these, 29.41% had one other tracker.

25.49% also included Podtrac, and 3.92% also included Chartable.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "39.22%" >}}
2. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "19.61%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "13.73%" >}}
4. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "9.80%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.88%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.92%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.92%" >}}
---

### 26. [Podcards](https://pod.cards/)

Podcards was found on <0.01% of new episodes in July, shrinking 83.09% from last month.

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
