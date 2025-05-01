---
title: "Top Podcast Tracking Services by Episode Share (April 2025)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2025-04.png
date: 2025-05-01T16:56:00-04:00
lastmod: 2025-05-01T16:56:00-04:00
draft: false
rssrevision: 2025-04
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.6 million in April 2025), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in April, how many
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
Month	Podtrac	Adswizz	Podsights	Podscribe	Chartable	Blubrry	Podcorn	Podroll	Spotify	Audiotakes	OP3	Podder	Swap.fm	Claritas	ArtsAI	Feedpress	Gumshoe	Veritonic	RSS Insight	Médiamétrie	CoHost Prefix	United Podcasters	Podkite	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	1.00	1.16		4.06	2.07	2.09									0.32				0.42										1.61
Oct 2021	4.05	1.01	1.20		4.09	2.11	2.13									0.34				0.54										1.61
Nov 2021	4.07	1.02	1.25		4.30	2.01	2.14									0.32				0.57										0.59
Dec 2021	4.06	1.24	1.19		4.42	1.57	2.27									0.19				0.59										
Jan 2022	4.11	1.41	1.21		4.45	1.56	2.31									0.16				0.63										
Feb 2022	4.15	1.44	1.25		4.48	1.53	2.38									0.17				0.58										
Mar 2022	4.37	1.51	1.34		4.72	1.56	2.40									0.17				0.53										
Apr 2022	4.44	1.49	1.33		4.71	1.55	2.33									0.16				0.51										
May 2022	4.49	1.58	1.41		4.87	1.48	2.26									0.17				0.56										
Jun 2022	4.75	1.77	1.54		5.10	1.50	2.06									0.21				0.62							0.02			
Jul 2022	4.70	1.89	1.50		5.10	1.50	2.16									0.25				0.54							0.02			
Aug 2022	4.83	2.08	1.73		5.26	1.51	2.45								0.10	0.20				0.41							0.01			
Sep 2022	7.53	2.26	1.74	0.02	5.40	1.49	2.45							0.01	0.09	0.21				0.52			0.01				0.02	0.02		
Oct 2022	8.24	2.35	1.81	0.07	5.48	1.61	2.51				0.03			0.02	0.10	0.18				0.50			0.01	0.01			0.02	0.04		
Nov 2022	8.11	2.37	2.03	0.15	5.62	1.62	2.43				0.04	0.01		0.03	0.10	0.18				0.50			0.01	0.01			0.02	0.05		
Dec 2022	8.01	2.32	1.81	0.03	5.54	1.61	2.05				0.05	0.04		0.02	0.05	0.18				0.49			0.01	0.01		0.01	0.02	0.05		
Jan 2023	7.85	2.35	1.88	0.20	5.56	1.61	2.15				0.07	0.11		0.06	0.10	0.18				0.54			0.01	0.01		0.01	0.02	0.06		
Feb 2023	7.58	2.29	1.92	0.21	5.51	1.62	2.30				0.07	0.11		0.07	0.10	0.19				0.49			0.01	0.01		0.01	0.02	0.06	0.03	
Mar 2023	7.79	2.25	2.03	0.21	5.53	1.53	2.22	0.04			0.08	0.11		0.07	0.11	0.18		0.04		0.45			0.01	0.01		0.01	0.02	0.06		
Apr 2023	7.66	2.26	2.00	0.21	5.43	1.67	2.20	0.06			0.09	0.15		0.07	0.11	0.17	0.08	0.05		0.45			0.01	0.01		0.01	0.01			
May 2023	7.58	2.27	2.04	0.24	5.59	1.67	2.28	0.09			0.09	0.15		0.08	0.11	0.19	0.07	0.05		0.45			0.01	0.01	0.01	0.01	0.01			
Jun 2023	8.22	2.39	2.23	0.26	5.83	1.64	1.86	0.10			0.09	0.15		0.07	0.12	0.19	0.08	0.05		0.51			0.01	0.01	0.01	0.01	0.01			
Jul 2023	8.60	2.38	2.52	0.27	5.95	1.53	1.17	0.14	0.01		0.08	0.14		0.07	0.11	0.18	0.06	0.06		0.55			0.01	0.01	0.01	0.01	0.01			
Aug 2023	9.19	2.72	2.76	0.36	6.43	1.58	1.23	0.16	0.03	0.04	0.11	0.15		0.08	0.12	0.17	0.07	0.07		0.53			0.01	0.01	0.02	0.01				
Sep 2023	8.46	2.49	2.47	0.37	5.77	1.39	1.10	0.13	0.05	0.05	0.10	0.15		0.10	0.12	0.16	0.07	0.06		0.58			0.01	0.01	0.02	0.01				
Oct 2023	7.90	2.29	2.28	0.39	5.54	1.37	1.11	0.12	0.08	0.05	0.10	0.16		0.10	0.12	0.16	0.08	0.06		0.50			0.01	0.02	0.03	0.01				
Nov 2023	7.65	2.25	2.33	0.47	5.59	1.45	1.14	0.12	0.11	0.06	0.13	0.16		0.11	0.12	0.17	0.10	0.06		0.33			0.01	0.01	0.03					
Dec 2023	7.48	2.20	2.19	0.54	5.60	1.53	1.12	0.12	0.12	0.06	0.11	0.16		0.11	0.12	0.16	0.09	0.06		0.33			0.01	0.01	0.03					
Jan 2024	7.64	2.37	2.21	0.65	5.61	1.55	1.17	0.11	0.15	0.08	0.13	0.16		0.12	0.14	0.17	0.10	0.06		0.25		0.01	0.01	0.01	0.01					
Feb 2024	7.69	2.38	2.22	0.69	5.58	1.52	1.21	0.12	0.22	0.09	0.16	0.17		0.13	0.13	0.17	0.11	0.06		0.22		0.01	0.01	0.01						
Mar 2024	9.01	2.53	2.19	0.69	5.46	1.54	1.14	0.12	0.25	0.09	0.14	0.16		0.14	0.12	0.16	0.10	0.06		0.22		0.01	0.01	0.01						
Apr 2024	10.78	2.53	2.16	0.73	5.47	1.51	1.24	0.34	0.27	0.07	0.18	0.17		0.15	0.13	0.15	0.11	0.07		0.19	0.01	0.01	0.01	0.01						
May 2024	11.59	2.75	2.24	0.83	5.63	1.50	1.20	0.36	0.30	0.06	0.18	0.16		0.15	0.14	0.15	0.11	0.07		0.09	0.01	0.01	0.01	0.01						
Jun 2024	11.54	2.88	2.34	0.91	6.06	1.52	0.71	0.37	0.32	0.07	0.20	0.15	0.03	0.16	0.16	0.15	0.11	0.07		0.10	0.01	0.01	0.01	0.01						
Jul 2024	12.34	2.83	2.45	1.01	6.80	1.65	0.71	0.43	0.34	0.09	0.20	0.15	0.06	0.18	0.17	0.15	0.12	0.07		0.09	0.01	0.01	0.01	0.01						
Aug 2024	14.22	2.96	2.48	1.11	6.72	1.70	0.81	0.45	0.35	0.11	0.19	0.35	0.12	0.18	0.18	0.14	0.12	0.08		0.08	0.01	0.01	0.01	0.01						
Sep 2024	12.95	3.13	2.26	1.18	5.99	1.44	0.72	0.44	0.35	0.13	0.24	0.42	0.12	0.18	0.18	0.15	0.13	0.08		0.07	0.01	0.01	0.01	0.01						
Oct 2024	12.24	3.23	2.35	1.23	5.49	1.53	0.66	0.43	0.40	0.14	0.27	0.39	0.17	0.19	0.18	0.14	0.12	0.09		0.09	0.01	0.01	0.01	0.01						
Nov 2024	11.86	3.21	2.31	1.27	4.66	1.52	0.63	0.43	0.44	0.14	0.29	0.41	0.19	0.21	0.17	0.11	0.12	0.08		0.10	0.01	0.01	0.01	0.01						
Dec 2024	12.56	3.06	2.13	1.29	2.29	1.40	0.62	0.43	0.45	0.15	0.29	0.54	0.24	0.21	0.18	0.09	0.12	0.08		0.09	0.01	0.01	0.01	0.01						
Jan 2025	12.62	2.92	1.73	1.31	1.54	1.36	0.66	0.46	0.41	0.16	0.34	0.54	0.27	0.21	0.19	0.12	0.13	0.08		0.04	0.01	0.01	0.01	0.01						
Feb 2025	12.47	2.74	1.70	1.25	1.43	1.45	0.66	0.46	0.36	0.16	0.33	0.48	0.28	0.22	0.18	0.14	0.12	0.08		0.01	0.01	0.01	0.01	0.01						
Mar 2025	12.18	2.87	1.51	1.28	1.18	1.25	0.67	0.47	0.33	0.25	0.33	0.36	0.27	0.21	0.18	0.14	0.13	0.07	0.04	0.01	0.01	0.01	0.01	0.01						
Apr 2025	12.35	2.97	1.64	1.53	1.28	1.26	0.68	0.48	0.44	0.41	0.34	0.33	0.30	0.23	0.19	0.13	0.12	0.08	0.03	0.02	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} are the clear top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podsights	Podscribe	Blubrry	Podcorn	Podroll	Spotify	Audiotakes	OP3	Podder	Swap.fm	Claritas	ArtsAI	Feedpress	Gumshoe	Veritonic	RSS Insight	Médiamétrie	CoHost Prefix	United Podcasters	Podkite	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
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
Sep 2022	2.26	1.74	0.02	1.49	2.45							0.01	0.09	0.21				0.52			0.01				0.02	0.02		
Oct 2022	2.35	1.81	0.07	1.61	2.51				0.03			0.02	0.10	0.18				0.50			0.01	0.01			0.02	0.04		
Nov 2022	2.37	2.03	0.15	1.62	2.43				0.04	0.01		0.03	0.10	0.18				0.50			0.01	0.01			0.02	0.05		
Dec 2022	2.32	1.81	0.03	1.61	2.05				0.05	0.04		0.02	0.05	0.18				0.49			0.01	0.01		0.01	0.02	0.05		
Jan 2023	2.35	1.88	0.20	1.61	2.15				0.07	0.11		0.06	0.10	0.18				0.54			0.01	0.01		0.01	0.02	0.06		
Feb 2023	2.29	1.92	0.21	1.62	2.30				0.07	0.11		0.07	0.10	0.19				0.49			0.01	0.01		0.01	0.02	0.06	0.03	
Mar 2023	2.25	2.03	0.21	1.53	2.22	0.04			0.08	0.11		0.07	0.11	0.18		0.04		0.45			0.01	0.01		0.01	0.02	0.06		
Apr 2023	2.26	2.00	0.21	1.67	2.20	0.06			0.09	0.15		0.07	0.11	0.17	0.08	0.05		0.45			0.01	0.01		0.01	0.01			
May 2023	2.27	2.04	0.24	1.67	2.28	0.09			0.09	0.15		0.08	0.11	0.19	0.07	0.05		0.45			0.01	0.01	0.01	0.01	0.01			
Jun 2023	2.39	2.23	0.26	1.64	1.86	0.10			0.09	0.15		0.07	0.12	0.19	0.08	0.05		0.51			0.01	0.01	0.01	0.01	0.01			
Jul 2023	2.38	2.52	0.27	1.53	1.17	0.14	0.01		0.08	0.14		0.07	0.11	0.18	0.06	0.06		0.55			0.01	0.01	0.01	0.01	0.01			
Aug 2023	2.72	2.76	0.36	1.58	1.23	0.16	0.03	0.04	0.11	0.15		0.08	0.12	0.17	0.07	0.07		0.53			0.01	0.01	0.02	0.01				
Sep 2023	2.49	2.47	0.37	1.39	1.10	0.13	0.05	0.05	0.10	0.15		0.10	0.12	0.16	0.07	0.06		0.58			0.01	0.01	0.02	0.01				
Oct 2023	2.29	2.28	0.39	1.37	1.11	0.12	0.08	0.05	0.10	0.16		0.10	0.12	0.16	0.08	0.06		0.50			0.01	0.02	0.03	0.01				
Nov 2023	2.25	2.33	0.47	1.45	1.14	0.12	0.11	0.06	0.13	0.16		0.11	0.12	0.17	0.10	0.06		0.33			0.01	0.01	0.03					
Dec 2023	2.20	2.19	0.54	1.53	1.12	0.12	0.12	0.06	0.11	0.16		0.11	0.12	0.16	0.09	0.06		0.33			0.01	0.01	0.03					
Jan 2024	2.37	2.21	0.65	1.55	1.17	0.11	0.15	0.08	0.13	0.16		0.12	0.14	0.17	0.10	0.06		0.25		0.01	0.01	0.01	0.01					
Feb 2024	2.38	2.22	0.69	1.52	1.21	0.12	0.22	0.09	0.16	0.17		0.13	0.13	0.17	0.11	0.06		0.22		0.01	0.01	0.01						
Mar 2024	2.53	2.19	0.69	1.54	1.14	0.12	0.25	0.09	0.14	0.16		0.14	0.12	0.16	0.10	0.06		0.22		0.01	0.01	0.01						
Apr 2024	2.53	2.16	0.73	1.51	1.24	0.34	0.27	0.07	0.18	0.17		0.15	0.13	0.15	0.11	0.07		0.19	0.01	0.01	0.01	0.01						
May 2024	2.75	2.24	0.83	1.50	1.20	0.36	0.30	0.06	0.18	0.16		0.15	0.14	0.15	0.11	0.07		0.09	0.01	0.01	0.01	0.01						
Jun 2024	2.88	2.34	0.91	1.52	0.71	0.37	0.32	0.07	0.20	0.15	0.03	0.16	0.16	0.15	0.11	0.07		0.10	0.01	0.01	0.01	0.01						
Jul 2024	2.83	2.45	1.01	1.65	0.71	0.43	0.34	0.09	0.20	0.15	0.06	0.18	0.17	0.15	0.12	0.07		0.09	0.01	0.01	0.01	0.01						
Aug 2024	2.96	2.48	1.11	1.70	0.81	0.45	0.35	0.11	0.19	0.35	0.12	0.18	0.18	0.14	0.12	0.08		0.08	0.01	0.01	0.01	0.01						
Sep 2024	3.13	2.26	1.18	1.44	0.72	0.44	0.35	0.13	0.24	0.42	0.12	0.18	0.18	0.15	0.13	0.08		0.07	0.01	0.01	0.01	0.01						
Oct 2024	3.23	2.35	1.23	1.53	0.66	0.43	0.40	0.14	0.27	0.39	0.17	0.19	0.18	0.14	0.12	0.09		0.09	0.01	0.01	0.01	0.01						
Nov 2024	3.21	2.31	1.27	1.52	0.63	0.43	0.44	0.14	0.29	0.41	0.19	0.21	0.17	0.11	0.12	0.08		0.10	0.01	0.01	0.01	0.01						
Dec 2024	3.06	2.13	1.29	1.40	0.62	0.43	0.45	0.15	0.29	0.54	0.24	0.21	0.18	0.09	0.12	0.08		0.09	0.01	0.01	0.01	0.01						
Jan 2025	2.92	1.73	1.31	1.36	0.66	0.46	0.41	0.16	0.34	0.54	0.27	0.21	0.19	0.12	0.13	0.08		0.04	0.01	0.01	0.01	0.01						
Feb 2025	2.74	1.70	1.25	1.45	0.66	0.46	0.36	0.16	0.33	0.48	0.28	0.22	0.18	0.14	0.12	0.08		0.01	0.01	0.01	0.01	0.01						
Mar 2025	2.87	1.51	1.28	1.25	0.67	0.47	0.33	0.25	0.33	0.36	0.27	0.21	0.18	0.14	0.13	0.07	0.04	0.01	0.01	0.01	0.01	0.01						
Apr 2025	2.97	1.64	1.53	1.26	0.68	0.48	0.44	0.41	0.34	0.33	0.30	0.23	0.19	0.13	0.12	0.08	0.03	0.02	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

### Overall

At least one tracker was found on 18.08% of new episodes in April, growing 2.71% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "43.91%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "11.54%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.31%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.92%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.31%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.27%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.13%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.45%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.40%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.15%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of April 2025.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 12.35% of new episodes in April, growing 1.46% from last month.

Of these, 10.31% had one other tracker, 7.86% had 2 other trackers, 1.35% had 3 other trackers, 1.28% had 4 other trackers, 1.08% had 5 other trackers, 0.32% had 6 other trackers, 0.22% had 7 other trackers, and 0.01% had 8 other trackers.

8.60% also included Podsights, 6.30% also included Adswizz, 5.58% also included Podscribe, 5.31% also included Chartable, 3.31% also included Podroll, 2.20% also included Spotify, 2.18% also included Magellan AI, 1.51% also included Swap.fm, 1.39% also included Podder, 1.35% also included Podcorn, 1.22% also included Claritas, 1.19% also included OP3, 1.05% also included Blubrry, 0.95% also included ArtsAI, 0.69% also included Audiotakes, 0.58% also included Gumshoe, 0.52% also included Veritonic, 0.08% also included CoHost Prefix, 0.04% also included United Podcasters, 0.04% also included Feedpress, 0.02% also included Podkite, 0.01% also included Médiamétrie, 0.01% also included AdBarker, and <0.01% also included Zencastr.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "64.10%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "8.58%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.77%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.30%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.09%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.18%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.70%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.01%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.66%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.64%" >}}
---

### 2. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.97% of new episodes in April, growing 3.39% from last month.

Of these, 16.03% had 2 other trackers, 12.70% had one other tracker, 8.70% had 3 other trackers, 2.18% had 4 other trackers, 1.48% had 5 other trackers, 0.37% had 6 other trackers, and 0.37% had 7 other trackers.

26.19% also included Podtrac, 15.03% also included Podscribe, 12.78% also included Magellan AI, 12.49% also included Podroll, 9.40% also included Audiotakes, 3.10% also included Podsights, 2.46% also included Swap.fm, 2.42% also included Spotify, 2.23% also included Claritas, 1.28% also included ArtsAI, 1.23% also included Blubrry, 0.81% also included Chartable, 0.76% also included Podder, 0.64% also included OP3, 0.61% also included Veritonic, 0.29% also included Podcorn, 0.07% also included Gumshoe, and 0.04% also included United Podcasters.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "66.62%" >}}
2. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "5.59%" >}}
3. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "5.08%" >}}
4. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "4.43%" >}}
5. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "4.39%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.63%" >}}
7. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "2.51%" >}}
8. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "2.06%" >}}
9. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.40%" >}}
10. {{< a "https://www.ilsole24ore.com/" "Il Sole 24 Ore" >}} {{< span "weak" "0.78%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 2.49% of new episodes in April, growing 10.38% from last month.

Of these, 56.79% also included Podtrac, 29.35% also included Podscribe, 14.34% also included Magellan AI, 8.09% also included Claritas, 7.33% also included Adswizz, 7.02% also included Swap.fm, 6.21% also included ArtsAI, 4.70% also included Audiotakes, 3.52% also included Podcorn, 3.42% also included Gumshoe, 3.00% also included OP3, 2.96% also included Veritonic, 2.76% also included Podroll, 2.17% also included Podder, 0.35% also included Blubrry, 0.34% also included United Podcasters, 0.28% also included CoHost Prefix, 0.06% also included Feedpress, 0.03% also included Podkite, 0.03% also included Firstory, 0.01% also included Zencastr, and 0.01% also included AdBarker.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "57.55%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "15.99%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.27%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.18%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.69%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.94%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.68%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.43%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.19%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.99%" >}}
---

### 3. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.64% of new episodes in April, growing 8.50% from last month.

Of these, 33.69% had one other tracker, 23.61% had 2 other trackers, 10.48% had 4 other trackers, 10.26% had 3 other trackers, 7.30% had 5 other trackers, 2.60% had 6 other trackers, 1.32% had 7 other trackers, and 0.05% had 8 other trackers.

64.69% also included Podtrac, 41.70% also included Chartable, 31.51% also included Podscribe, 16.10% also included Magellan AI, 8.97% also included Swap.fm, 6.72% also included Claritas, 6.11% also included ArtsAI, 5.61% also included Adswizz, 5.36% also included Audiotakes, 4.67% also included Podcorn, 4.48% also included Spotify, 4.20% also included Gumshoe, 4.13% also included OP3, 3.69% also included Veritonic, 3.33% also included Podroll, 2.74% also included Podder, 0.41% also included CoHost Prefix, 0.40% also included Blubrry, 0.36% also included United Podcasters, 0.09% also included Feedpress, and 0.04% also included Podkite.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "62.11%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.94%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.02%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.87%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.24%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.65%" >}}
7. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.50%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.25%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.96%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.59%" >}}
---

### 4. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 1.53% of new episodes in April, growing 19.95% from last month.

Of these, 25.75% had 3 other trackers, 16.49% had one other tracker, 16.19% had 4 other trackers, 13.39% had 2 other trackers, 10.79% had 5 other trackers, 3.15% had 6 other trackers, 1.77% had 7 other trackers, and 0.05% had 8 other trackers.

44.97% also included Podtrac, 44.13% also included Magellan AI, 33.73% also included Podsights, 29.12% also included Adswizz, 26.42% also included Audiotakes, 16.30% also included Chartable, 15.68% also included Spotify, 14.61% also included Claritas, 11.67% also included ArtsAI, 7.19% also included Swap.fm, 5.23% also included Podcorn, 4.60% also included Gumshoe, 4.25% also included Podder, 4.03% also included OP3, 4.00% also included Podroll, 3.86% also included Veritonic, 0.44% also included United Podcasters, 0.39% also included CoHost Prefix, 0.22% also included Blubrry, and 0.02% also included Podkite.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "36.07%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "27.74%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.77%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.08%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.57%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.86%" >}}
7. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "3.64%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.36%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.37%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.20%" >}}
---

### 5. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 1.28% of new episodes in April, growing 8.66% from last month.

Of these, 35.20% had 2 other trackers, 21.68% had one other tracker, 7.76% had 3 other trackers, 6.75% had 4 other trackers, 3.03% had 5 other trackers, 2.13% had 6 other trackers, 0.26% had 7 other trackers, and 0.02% had 8 other trackers.

53.42% also included Podsights, 51.22% also included Podtrac, 19.51% also included Podscribe, 10.50% also included Spotify, 9.79% also included Swap.fm, 9.44% also included Magellan AI, 3.92% also included Claritas, 2.70% also included Podroll, 2.18% also included Veritonic, 1.89% also included Adswizz, 1.62% also included Podder, 1.11% also included Gumshoe, 1.10% also included ArtsAI, 1.00% also included Podcorn, 0.85% also included Audiotakes, 0.76% also included OP3, 0.46% also included CoHost Prefix, 0.37% also included United Podcasters, 0.13% also included Blubrry, 0.12% also included Feedpress, 0.05% also included Firstory, 0.02% also included Zencastr, 0.02% also included AdBarker, and 0.01% also included Podkite.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "85.04%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.15%" >}}
3. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.27%" >}}
4. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.56%" >}}
5. {{< a "https://cloud.google.com/" "Google Cloud" >}} {{< span "weak" "0.46%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.38%" >}}
7. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.34%" >}}
8. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.28%" >}}
9. {{< a "https://www.wideorbit.com/" "WideOrbit" >}} {{< span "weak" "0.28%" >}}
10. {{< a "https://podetize.com/" "Podetize" >}} {{< span "weak" "0.22%" >}}
---

### 6. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.26% of new episodes in April, growing 0.50% from last month.

Of these, 14.52% had one other tracker, 0.66% had 2 other trackers, 0.21% had 3 other trackers, 0.13% had 4 other trackers, 0.03% had 6 other trackers, and 0.03% had 5 other trackers.

10.33% also included Podtrac, 2.90% also included Adswizz, 1.58% also included Feedpress, 0.52% also included Podsights, 0.46% also included OP3, 0.31% also included Podcorn, 0.29% also included Swap.fm, 0.27% also included Podscribe, 0.26% also included Podder, 0.13% also included Chartable, 0.12% also included Magellan AI, 0.09% also included Spotify, 0.04% also included Podkite, 0.03% also included ArtsAI, 0.01% also included Audiotakes, and 0.01% also included Veritonic.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "47.41%" >}}
2. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "4.64%" >}}
3. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.64%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.98%" >}}
5. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "1.98%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.96%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.21%" >}}
8. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.17%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.88%" >}}
10. {{< a "https://joy.org.au/" "JOY Media" >}} {{< span "weak" "0.75%" >}}
---

### 7. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.90% of new episodes in April, growing 39.53% from last month.

Of these, 33.58% had 3 other trackers, 17.47% had 4 other trackers, 11.10% had 5 other trackers, 8.53% had 2 other trackers, 4.91% had 6 other trackers, 4.48% had one other tracker, and 2.80% had 7 other trackers.

75.19% also included Podscribe, 42.19% also included Adswizz, 36.91% also included Audiotakes, 29.91% also included Podtrac, 29.37% also included Podsights, 19.71% also included Claritas, 14.66% also included Spotify, 13.44% also included Chartable, 12.06% also included ArtsAI, 7.94% also included Swap.fm, 5.88% also included Veritonic, 3.55% also included Podroll, 2.87% also included Podder, 1.40% also included Gumshoe, 0.93% also included OP3, 0.34% also included United Podcasters, 0.17% also included Blubrry, 0.15% also included Podcorn, and 0.09% also included CoHost Prefix.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "39.77%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.50%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.28%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.37%" >}}
5. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "7.23%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.41%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.81%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "2.22%" >}}
9. {{< a "https://www.americanpublicmedia.org/" "American Public Media" >}} {{< span "weak" "1.57%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.34%" >}}
---

### 8. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.68% of new episodes in April, growing 1.50% from last month.

Of these, 12.29% had one other tracker, 6.60% had 5 other trackers, 5.67% had 2 other trackers, 2.66% had 4 other trackers, 1.81% had 3 other trackers, 0.25% had 6 other trackers, 0.11% had 8 other trackers, and 0.06% had 7 other trackers.

24.52% also included Podtrac, 11.75% also included Podscribe, 11.24% also included Podsights, 10.87% also included OP3, 7.90% also included Gumshoe, 2.43% also included Podroll, 1.88% also included Chartable, 1.25% also included Adswizz, 1.17% also included Podder, 0.82% also included Spotify, 0.58% also included Blubrry, 0.22% also included Swap.fm, 0.19% also included Magellan AI, 0.18% also included Feedpress, 0.14% also included United Podcasters, 0.08% also included Podkite, 0.08% also included CoHost Prefix, 0.06% also included Audiotakes, 0.06% also included Claritas, and 0.03% also included Zencastr.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "23.77%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "11.84%" >}}
3. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "11.49%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "11.24%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "7.82%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.81%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "6.68%" >}}
8. {{< a "https://www.wideorbit.com/" "WideOrbit" >}} {{< span "weak" "3.58%" >}}
9. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.06%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.25%" >}}
---

### 9. [Podroll](https://podroll.fm/)

Podroll was found on 0.48% of new episodes in April, growing 2.12% from last month.

Of these, 74.44% had 2 other trackers, 8.39% had one other tracker, 6.52% had 4 other trackers, 4.81% had 3 other trackers, 1.91% had 5 other trackers, 1.45% had 6 other trackers, 0.43% had 7 other trackers, and 0.16% had 8 other trackers.

84.78% also included Podtrac, 77.03% also included Adswizz, 12.74% also included Podscribe, 11.34% also included Podsights, 7.17% also included Chartable, 6.63% also included Magellan AI, 5.54% also included Swap.fm, 4.48% also included Audiotakes, 3.44% also included Podcorn, 1.63% also included Claritas, 1.08% also included OP3, 1.02% also included Spotify, 0.97% also included ArtsAI, 0.89% also included Gumshoe, 0.51% also included United Podcasters, 0.38% also included Podder, 0.34% also included CoHost Prefix, and 0.33% also included Veritonic.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "77.17%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.11%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.16%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.16%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "1.65%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.03%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.82%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.50%" >}}
9. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "0.21%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.13%" >}}
---

### 10. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.44% of new episodes in April, growing 31.60% from last month.

Of these, 32.82% had 2 other trackers, 15.43% had 4 other trackers, 12.01% had 5 other trackers, 9.02% had one other tracker, 6.94% had 3 other trackers, 5.35% had 6 other trackers, 5.00% had 7 other trackers, and 0.06% had 8 other trackers.

62.40% also included Podtrac, 55.23% also included Podscribe, 30.89% also included Chartable, 30.30% also included Magellan AI, 27.50% also included Claritas, 18.65% also included ArtsAI, 16.87% also included Podsights, 16.51% also included Adswizz, 9.40% also included Audiotakes, 5.90% also included Veritonic, 2.95% also included Gumshoe, 2.04% also included Podder, 1.72% also included Swap.fm, 1.47% also included OP3, 1.29% also included Podcorn, 1.13% also included Podroll, 0.30% also included United Podcasters, and 0.27% also included Blubrry.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "40.71%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "16.16%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "15.89%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "12.72%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.76%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.64%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.78%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.23%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.14%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.46%" >}}
---

### 11. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.41% of new episodes in April, growing 65.97% from last month.

Of these, 64.65% had 3 other trackers, 19.47% had 4 other trackers, 7.98% had 5 other trackers, 5.18% had 2 other trackers, 1.51% had 6 other trackers, 0.51% had one other tracker, and 0.14% had 7 other trackers.

99.11% also included Podscribe, 81.27% also included Magellan AI, 68.28% also included Adswizz, 21.53% also included Podsights, 20.93% also included Podtrac, 12.48% also included ArtsAI, 10.01% also included Spotify, 5.28% also included Podroll, 4.87% also included Podder, 2.66% also included Chartable, 1.96% also included Swap.fm, 1.93% also included Veritonic, 1.09% also included Gumshoe, 0.46% also included OP3, 0.45% also included United Podcasters, 0.17% also included Claritas, 0.09% also included Podcorn, and 0.03% also included Blubrry.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "68.78%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.65%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.26%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.39%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.22%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.86%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.79%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.42%" >}}
9. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.40%" >}}
10. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.18%" >}}
---

### 12. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.34% of new episodes in April, growing 1.52% from last month.

Of these, 22.56% had one other tracker, 13.52% had 5 other trackers, 9.10% had 2 other trackers, 4.02% had 4 other trackers, 2.98% had 3 other trackers, 1.06% had 6 other trackers, 0.20% had 7 other trackers, and 0.15% had 8 other trackers.

43.16% also included Podtrac, 21.82% also included Podcorn, 19.97% also included Podsights, 18.19% also included Podscribe, 16.69% also included Gumshoe, 5.61% also included Adswizz, 2.87% also included Chartable, 2.46% also included Magellan AI, 1.89% also included Spotify, 1.70% also included Blubrry, 1.57% also included Swap.fm, 1.54% also included Podroll, 1.46% also included Podder, 0.87% also included Claritas, 0.72% also included ArtsAI, 0.56% also included Audiotakes, 0.48% also included CoHost Prefix, 0.41% also included Podkite, 0.17% also included United Podcasters, 0.13% also included Feedpress, and 0.06% also included Zencastr.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "28.01%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "8.17%" >}}
3. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "7.67%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.78%" >}}
5. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "4.21%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.17%" >}}
7. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "3.93%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.89%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.37%" >}}
10. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.95%" >}}
---

### 13. [Podder](https://www.podderapp.com/)

Podder was found on 0.33% of new episodes in April, shrinking 10.47% from last month.

Of these, 36.24% had one other tracker, 10.99% had 2 other trackers, 7.37% had 4 other trackers, 5.26% had 3 other trackers, 3.77% had 5 other trackers, 0.64% had 6 other trackers, and 0.15% had 8 other trackers.

52.85% also included Podtrac, 20.02% also included Podscribe, 13.83% also included Podsights, 7.93% also included Magellan AI, 6.95% also included Adswizz, 6.36% also included Chartable, 6.11% also included Audiotakes, 2.73% also included Spotify, 2.46% also included Podcorn, 2.19% also included ArtsAI, 1.53% also included OP3, 1.14% also included Claritas, 1.03% also included Blubrry, 0.91% also included Gumshoe, 0.56% also included Podroll, 0.23% also included Swap.fm, 0.19% also included Veritonic, 0.15% also included CoHost Prefix, 0.14% also included United Podcasters, and 0.10% also included Podkite.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "32.25%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "31.51%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.43%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.58%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.80%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.42%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.26%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.24%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.01%" >}}
10. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.64%" >}}
---

### 14. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.30% of new episodes in April, growing 9.06% from last month.

Of these, 28.56% had 2 other trackers, 17.15% had 4 other trackers, 16.98% had 3 other trackers, 16.31% had one other tracker, 11.41% had 5 other trackers, 2.14% had 6 other trackers, 1.63% had 7 other trackers, and 0.08% had 8 other trackers.

62.68% also included Podtrac, 49.58% also included Podsights, 42.24% also included Chartable, 37.13% also included Podscribe, 24.62% also included Adswizz, 24.07% also included Magellan AI, 8.99% also included Podroll, 7.65% also included ArtsAI, 5.68% also included Claritas, 2.69% also included Audiotakes, 2.52% also included Spotify, 1.80% also included OP3, 1.23% also included Blubrry, 1.21% also included United Podcasters, 1.19% also included Gumshoe, 0.78% also included Veritonic, 0.51% also included Podcorn, 0.25% also included Podder, and 0.17% also included CoHost Prefix.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "54.71%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "24.60%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.54%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.88%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "4.43%" >}}
6. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.34%" >}}
7. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.21%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.19%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.11%" >}}
---

### 15. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.23% of new episodes in April, growing 9.97% from last month.

Of these, 32.72% had 4 other trackers, 26.78% had 5 other trackers, 15.87% had 6 other trackers, 9.05% had 7 other trackers, 6.74% had 3 other trackers, 5.61% had 2 other trackers, and 1.99% had one other tracker.

95.57% also included Podscribe, 75.69% also included Magellan AI, 64.36% also included Podtrac, 51.09% also included Spotify, 47.09% also included Podsights, 40.24% also included ArtsAI, 28.28% also included Adswizz, 21.41% also included Chartable, 17.67% also included Veritonic, 7.20% also included Swap.fm, 3.36% also included Podroll, 1.58% also included Podder, 1.26% also included OP3, 0.97% also included Gumshoe, 0.32% also included United Podcasters, 0.30% also included Audiotakes, 0.27% also included CoHost Prefix, and 0.16% also included Podcorn.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "35.48%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "27.93%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "22.43%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.12%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.67%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.51%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.27%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.24%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.16%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.05%" >}}
---

### 16. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.19% of new episodes in April, growing 10.25% from last month.

Of these, 34.12% had 4 other trackers, 24.37% had 5 other trackers, 12.87% had 7 other trackers, 8.90% had 6 other trackers, 7.62% had 3 other trackers, 7.14% had 2 other trackers, and 4.69% had one other tracker.

92.64% also included Podscribe, 61.03% also included Podtrac, 56.17% also included Magellan AI, 51.91% also included Podsights, 48.81% also included Claritas, 42.03% also included Spotify, 26.39% also included Audiotakes, 19.68% also included Adswizz, 17.53% also included Veritonic, 11.76% also included Swap.fm, 7.27% also included Chartable, 3.68% also included Podder, 2.41% also included Podroll, 1.27% also included OP3, 0.39% also included United Podcasters, 0.26% also included Gumshoe, 0.23% also included Blubrry, and 0.16% also included CoHost Prefix.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "28.64%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "27.99%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "19.16%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.44%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "9.55%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.25%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.33%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.20%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.16%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.16%" >}}
---

### 17. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.13% of new episodes in April, shrinking 6.85% from last month.

Of these, 20.26% had one other tracker, and 1.14% had 2 other trackers.

15.03% also included Blubrry, 3.99% also included Podtrac, 1.14% also included Podsights, 1.14% also included Chartable, 0.90% also included Podcorn, and 0.33% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "55.92%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "10.89%" >}}
3. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "6.23%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.71%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.66%" >}}
6. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "2.57%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.04%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.62%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.52%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.47%" >}}
---

### 18. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.12% of new episodes in April, shrinking 2.80% from last month.

Of these, 36.26% had 5 other trackers, 14.96% had one other tracker, 13.33% had 4 other trackers, 11.03% had 2 other trackers, 6.23% had 3 other trackers, 1.99% had 6 other trackers, 1.28% had 7 other trackers, and 0.41% had 8 other trackers.

58.17% also included Podtrac, 57.20% also included Podscribe, 55.98% also included Podsights, 46.02% also included OP3, 43.72% also included Podcorn, 11.54% also included Chartable, 10.42% also included Spotify, 10.21% also included Magellan AI, 3.63% also included Audiotakes, 3.47% also included Podroll, 2.86% also included Swap.fm, 2.55% also included CoHost Prefix, 2.40% also included Podder, 1.84% also included Claritas, 1.74% also included Adswizz, 1.48% also included Veritonic, 0.87% also included United Podcasters, and 0.41% also included ArtsAI.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "48.72%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "21.86%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "20.48%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.32%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.20%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.84%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.56%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.26%" >}}
9. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.20%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.20%" >}}
---

### 19. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.08% of new episodes in April, growing 4.50% from last month.

Of these, 30.51% had 7 other trackers, 22.78% had 6 other trackers, 17.41% had 5 other trackers, 16.76% had 3 other trackers, 6.27% had 2 other trackers, 3.74% had 4 other trackers, and 0.41% had one other tracker.

83.24% also included Podtrac, 78.36% also included Podsights, 76.48% also included Podscribe, 68.35% also included Magellan AI, 53.54% also included Claritas, 43.78% also included ArtsAI, 36.13% also included Chartable, 33.20% also included Spotify, 23.27% also included Adswizz, 10.17% also included Audiotakes, 3.01% also included Swap.fm, 2.36% also included Gumshoe, 2.03% also included Podroll, 0.81% also included Podder, 0.41% also included CoHost Prefix, 0.24% also included United Podcasters, and 0.16% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "67.62%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "22.95%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.52%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.44%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.44%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.65%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.41%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.33%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.16%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.16%" >}}
---

### 20. [Firstory](https://firstory.me/)

Firstory was found on 0.04% of new episodes in April, shrinking 0.74% from last month.

Of these, 1.52% had one other tracker.

1.52% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.24%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.76%" >}}
---

### 21. [RSS Insight](https://www.rssinsight.com/)

RSS Insight was found on 0.03% of new episodes in April, shrinking 18.84% from last month.

For episodes that used RSS Insight, here are the top underlying podcast hosts:

1. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "100.00%" >}}
---

### 22. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.02% of new episodes in April, growing 46.95% from last month.

Of these, 9.92% had one other tracker.

9.92% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "100.00%" >}}
---

### 23. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.01% of new episodes in April, growing 7.55% from last month.

Of these, 26.29% had one other tracker, 18.97% had 5 other trackers, 15.09% had 4 other trackers, 6.90% had 2 other trackers, 3.88% had 6 other trackers, 3.45% had 8 other trackers, 2.16% had 3 other trackers, and 2.16% had 7 other trackers.

70.26% also included Podtrac, 46.55% also included Podsights, 41.38% also included Podscribe, 40.52% also included Chartable, 21.55% also included Gumshoe, 11.21% also included Podroll, 11.21% also included OP3, 5.60% also included Magellan AI, 4.31% also included Claritas, 3.88% also included Podcorn, 3.45% also included Podder, 3.45% also included Swap.fm, 2.16% also included ArtsAI, and 2.16% also included Veritonic.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "46.98%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "13.79%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "12.93%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.76%" >}}
5. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "5.60%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "5.60%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.16%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.29%" >}}
9. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.29%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.86%" >}}
---

### 24. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in April, growing 40.52% from last month.

Of these, 19.82% had 4 other trackers, 19.38% had one other tracker, 18.50% had 3 other trackers, 10.13% had 6 other trackers, 8.37% had 5 other trackers, 7.93% had 2 other trackers, and 1.76% had 8 other trackers.

46.70% also included Podscribe, 41.41% also included Podsights, 37.89% also included Podtrac, 33.48% also included Chartable, 25.11% also included Swap.fm, 21.15% also included Magellan AI, 17.18% also included Podroll, 12.78% also included Audiotakes, 9.25% also included Spotify, 8.81% also included Adswizz, 7.49% also included Gumshoe, 6.61% also included Podcorn, 5.29% also included ArtsAI, 5.29% also included Claritas, 3.96% also included OP3, 3.08% also included Podder, and 1.32% also included Veritonic.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "48.90%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.57%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "9.69%" >}}
4. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "8.81%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.37%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "4.41%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.64%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.20%" >}}
9. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "2.20%" >}}
10. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "1.76%" >}}
---

### 25. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in April, growing 4.51% from last month.

Of these, 32.86% had one other tracker, 3.57% had 2 other trackers, 3.57% had 5 other trackers, and 2.86% had 4 other trackers.

25.00% also included Podtrac, 15.71% also included OP3, 7.14% also included Podsights, 6.43% also included Blubrry, 6.43% also included Podcorn, 3.57% also included Podder, 2.86% also included Podscribe, and 2.14% also included Chartable.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "23.57%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "19.29%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "12.86%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "12.86%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "9.29%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "6.43%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.71%" >}}
8. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "4.29%" >}}
9. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "4.29%" >}}
10. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "1.43%" >}}
---

### 26. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in April, shrinking 5.56% from last month.

Of these, 13.75% had one other tracker, and 3.75% had 2 other trackers.

7.50% also included Podtrac, 6.25% also included Chartable, 3.75% also included OP3, and 3.75% also included Podcorn.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "28.75%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "16.25%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "16.25%" >}}
4. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "11.25%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "11.25%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.50%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "5.00%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.75%" >}}
---

### 27. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in April, shrinking 9.09% from last month.

Of these, 26.67% had one other tracker.

20.00% also included Podtrac, and 6.67% also included Chartable.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "36.67%" >}}
2. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "21.67%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "13.33%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.67%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "6.67%" >}}
6. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "5.00%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.33%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
