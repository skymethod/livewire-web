---
title: "Top Podcast Tracking Services by Episode Share (February 2025)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2025-02.png
date: 2025-03-01T09:39:00-05:00
lastmod: 2025-03-01T09:39:00-05:00
draft: false
rssrevision: 2025-02
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.5 million in February 2025), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in February, how many
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
Month	Podtrac	Adswizz	Podsights	Blubrry	Chartable	Podscribe	Podcorn	Podder	Podroll	Spotify	OP3	Swap.fm	Claritas	ArtsAI	Audiotakes	Feedpress	Gumshoe	Veritonic	CoHost Prefix	Médiamétrie	Podkite	United Podcasters	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	1.00	1.16	2.07	4.06		2.09									0.32				0.42									1.61
Oct 2021	4.05	1.01	1.20	2.11	4.09		2.13									0.34				0.54									1.61
Nov 2021	4.07	1.02	1.25	2.01	4.30		2.14									0.32				0.57									0.59
Dec 2021	4.06	1.24	1.19	1.57	4.42		2.27									0.19				0.59									
Jan 2022	4.11	1.41	1.21	1.56	4.45		2.31									0.16				0.63									
Feb 2022	4.15	1.44	1.25	1.53	4.48		2.38									0.17				0.58									
Mar 2022	4.37	1.51	1.34	1.56	4.72		2.40									0.17				0.53									
Apr 2022	4.44	1.49	1.33	1.55	4.71		2.33									0.16				0.51									
May 2022	4.49	1.58	1.41	1.48	4.87		2.26									0.17				0.56									
Jun 2022	4.75	1.77	1.54	1.50	5.10		2.06									0.21				0.62						0.02			
Jul 2022	4.70	1.89	1.50	1.50	5.10		2.16									0.25				0.54						0.02			
Aug 2022	4.83	2.08	1.73	1.51	5.26		2.45							0.10		0.20				0.41						0.01			
Sep 2022	7.53	2.26	1.74	1.49	5.40	0.02	2.45						0.01	0.09		0.21				0.52	0.01					0.02	0.02		
Oct 2022	8.24	2.35	1.81	1.61	5.48	0.07	2.51				0.03		0.02	0.10		0.18				0.50	0.01		0.01			0.02	0.04		
Nov 2022	8.11	2.37	2.03	1.62	5.62	0.15	2.43	0.01			0.04		0.03	0.10		0.18				0.50	0.01		0.01			0.02	0.05		
Dec 2022	8.01	2.32	1.81	1.61	5.54	0.03	2.05	0.04			0.05		0.02	0.05		0.18				0.49	0.01		0.01		0.01	0.02	0.05		
Jan 2023	7.85	2.35	1.88	1.61	5.56	0.20	2.15	0.11			0.07		0.06	0.10		0.18				0.54	0.01		0.01		0.01	0.02	0.06		
Feb 2023	7.58	2.29	1.92	1.62	5.51	0.21	2.30	0.11			0.07		0.07	0.10		0.19				0.49	0.01		0.01		0.01	0.02	0.06	0.03	
Mar 2023	7.79	2.25	2.03	1.53	5.53	0.21	2.22	0.11	0.04		0.08		0.07	0.11		0.18		0.04		0.45	0.01		0.01		0.01	0.02	0.06		
Apr 2023	7.66	2.26	2.00	1.67	5.43	0.21	2.20	0.15	0.06		0.09		0.07	0.11		0.17	0.08	0.05		0.45	0.01		0.01		0.01	0.01			
May 2023	7.58	2.27	2.04	1.67	5.59	0.24	2.28	0.15	0.09		0.09		0.08	0.11		0.19	0.07	0.05		0.45	0.01		0.01	0.01	0.01	0.01			
Jun 2023	8.22	2.39	2.23	1.64	5.83	0.26	1.86	0.15	0.10		0.09		0.07	0.12		0.19	0.08	0.05		0.51	0.01		0.01	0.01	0.01	0.01			
Jul 2023	8.60	2.38	2.52	1.53	5.95	0.27	1.17	0.14	0.14	0.01	0.08		0.07	0.11		0.18	0.06	0.06		0.55	0.01		0.01	0.01	0.01	0.01			
Aug 2023	9.19	2.72	2.76	1.58	6.43	0.36	1.23	0.15	0.16	0.03	0.11		0.08	0.12	0.04	0.17	0.07	0.07		0.53	0.01		0.01	0.02	0.01				
Sep 2023	8.46	2.49	2.47	1.39	5.77	0.37	1.10	0.15	0.13	0.05	0.10		0.10	0.12	0.05	0.16	0.07	0.06		0.58	0.01		0.01	0.02	0.01				
Oct 2023	7.90	2.29	2.28	1.37	5.54	0.39	1.11	0.16	0.12	0.08	0.10		0.10	0.12	0.05	0.16	0.08	0.06		0.50	0.01		0.02	0.03	0.01				
Nov 2023	7.65	2.25	2.33	1.45	5.59	0.47	1.14	0.16	0.12	0.11	0.13		0.11	0.12	0.06	0.17	0.10	0.06		0.33	0.01		0.01	0.03					
Dec 2023	7.48	2.20	2.19	1.53	5.60	0.54	1.12	0.16	0.12	0.12	0.11		0.11	0.12	0.06	0.16	0.09	0.06		0.33	0.01		0.01	0.03					
Jan 2024	7.64	2.37	2.21	1.55	5.61	0.65	1.17	0.16	0.11	0.15	0.13		0.12	0.14	0.08	0.17	0.10	0.06		0.25	0.01	0.01	0.01	0.01					
Feb 2024	7.69	2.38	2.22	1.52	5.58	0.69	1.21	0.17	0.12	0.22	0.16		0.13	0.13	0.09	0.17	0.11	0.06		0.22	0.01	0.01	0.01						
Mar 2024	9.01	2.53	2.19	1.54	5.46	0.69	1.14	0.16	0.12	0.25	0.14		0.14	0.12	0.09	0.16	0.10	0.06		0.22	0.01	0.01	0.01						
Apr 2024	10.78	2.53	2.16	1.51	5.47	0.73	1.24	0.17	0.34	0.27	0.18		0.15	0.13	0.07	0.15	0.11	0.07	0.01	0.19	0.01	0.01	0.01						
May 2024	11.59	2.75	2.24	1.50	5.63	0.83	1.20	0.16	0.36	0.30	0.18		0.15	0.14	0.06	0.15	0.11	0.07	0.01	0.09	0.01	0.01	0.01						
Jun 2024	11.54	2.88	2.34	1.52	6.06	0.91	0.71	0.15	0.37	0.32	0.20	0.03	0.16	0.16	0.07	0.15	0.11	0.07	0.01	0.10	0.01	0.01	0.01						
Jul 2024	12.34	2.83	2.45	1.65	6.80	1.01	0.71	0.15	0.43	0.34	0.20	0.06	0.18	0.17	0.09	0.15	0.12	0.07	0.01	0.09	0.01	0.01	0.01						
Aug 2024	14.22	2.96	2.48	1.70	6.72	1.11	0.81	0.35	0.45	0.35	0.19	0.12	0.18	0.18	0.11	0.14	0.12	0.08	0.01	0.08	0.01	0.01	0.01						
Sep 2024	12.95	3.13	2.26	1.44	5.99	1.18	0.72	0.42	0.44	0.35	0.24	0.12	0.18	0.18	0.13	0.15	0.13	0.08	0.01	0.07	0.01	0.01	0.01						
Oct 2024	12.24	3.23	2.35	1.53	5.49	1.23	0.66	0.39	0.43	0.40	0.27	0.17	0.19	0.18	0.14	0.14	0.12	0.09	0.01	0.09	0.01	0.01	0.01						
Nov 2024	11.86	3.21	2.31	1.52	4.66	1.27	0.63	0.41	0.43	0.44	0.29	0.19	0.21	0.17	0.14	0.11	0.12	0.08	0.01	0.10	0.01	0.01	0.01						
Dec 2024	12.56	3.06	2.13	1.40	2.29	1.29	0.62	0.54	0.43	0.45	0.29	0.24	0.21	0.18	0.15	0.09	0.12	0.08	0.01	0.09	0.01	0.01	0.01						
Jan 2025	12.62	2.92	1.73	1.36	1.54	1.31	0.66	0.54	0.46	0.41	0.34	0.27	0.21	0.19	0.16	0.12	0.13	0.08	0.01	0.04	0.01	0.01	0.01						
Feb 2025	12.47	2.74	1.70	1.45	1.43	1.25	0.66	0.48	0.46	0.36	0.33	0.28	0.22	0.18	0.16	0.14	0.12	0.08	0.01	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} are the clear top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podsights	Blubrry	Podscribe	Podcorn	Podder	Podroll	Spotify	OP3	Swap.fm	Claritas	ArtsAI	Audiotakes	Feedpress	Gumshoe	Veritonic	CoHost Prefix	Médiamétrie	Podkite	United Podcasters	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	1.00	1.16	2.07		2.09									0.32				0.42									1.61
Oct 2021	1.01	1.20	2.11		2.13									0.34				0.54									1.61
Nov 2021	1.02	1.25	2.01		2.14									0.32				0.57									0.59
Dec 2021	1.24	1.19	1.57		2.27									0.19				0.59									
Jan 2022	1.41	1.21	1.56		2.31									0.16				0.63									
Feb 2022	1.44	1.25	1.53		2.38									0.17				0.58									
Mar 2022	1.51	1.34	1.56		2.40									0.17				0.53									
Apr 2022	1.49	1.33	1.55		2.33									0.16				0.51									
May 2022	1.58	1.41	1.48		2.26									0.17				0.56									
Jun 2022	1.77	1.54	1.50		2.06									0.21				0.62						0.02			
Jul 2022	1.89	1.50	1.50		2.16									0.25				0.54						0.02			
Aug 2022	2.08	1.73	1.51		2.45							0.10		0.20				0.41						0.01			
Sep 2022	2.26	1.74	1.49	0.02	2.45						0.01	0.09		0.21				0.52	0.01					0.02	0.02		
Oct 2022	2.35	1.81	1.61	0.07	2.51				0.03		0.02	0.10		0.18				0.50	0.01		0.01			0.02	0.04		
Nov 2022	2.37	2.03	1.62	0.15	2.43	0.01			0.04		0.03	0.10		0.18				0.50	0.01		0.01			0.02	0.05		
Dec 2022	2.32	1.81	1.61	0.03	2.05	0.04			0.05		0.02	0.05		0.18				0.49	0.01		0.01		0.01	0.02	0.05		
Jan 2023	2.35	1.88	1.61	0.20	2.15	0.11			0.07		0.06	0.10		0.18				0.54	0.01		0.01		0.01	0.02	0.06		
Feb 2023	2.29	1.92	1.62	0.21	2.30	0.11			0.07		0.07	0.10		0.19				0.49	0.01		0.01		0.01	0.02	0.06	0.03	
Mar 2023	2.25	2.03	1.53	0.21	2.22	0.11	0.04		0.08		0.07	0.11		0.18		0.04		0.45	0.01		0.01		0.01	0.02	0.06		
Apr 2023	2.26	2.00	1.67	0.21	2.20	0.15	0.06		0.09		0.07	0.11		0.17	0.08	0.05		0.45	0.01		0.01		0.01	0.01			
May 2023	2.27	2.04	1.67	0.24	2.28	0.15	0.09		0.09		0.08	0.11		0.19	0.07	0.05		0.45	0.01		0.01	0.01	0.01	0.01			
Jun 2023	2.39	2.23	1.64	0.26	1.86	0.15	0.10		0.09		0.07	0.12		0.19	0.08	0.05		0.51	0.01		0.01	0.01	0.01	0.01			
Jul 2023	2.38	2.52	1.53	0.27	1.17	0.14	0.14	0.01	0.08		0.07	0.11		0.18	0.06	0.06		0.55	0.01		0.01	0.01	0.01	0.01			
Aug 2023	2.72	2.76	1.58	0.36	1.23	0.15	0.16	0.03	0.11		0.08	0.12	0.04	0.17	0.07	0.07		0.53	0.01		0.01	0.02	0.01				
Sep 2023	2.49	2.47	1.39	0.37	1.10	0.15	0.13	0.05	0.10		0.10	0.12	0.05	0.16	0.07	0.06		0.58	0.01		0.01	0.02	0.01				
Oct 2023	2.29	2.28	1.37	0.39	1.11	0.16	0.12	0.08	0.10		0.10	0.12	0.05	0.16	0.08	0.06		0.50	0.01		0.02	0.03	0.01				
Nov 2023	2.25	2.33	1.45	0.47	1.14	0.16	0.12	0.11	0.13		0.11	0.12	0.06	0.17	0.10	0.06		0.33	0.01		0.01	0.03					
Dec 2023	2.20	2.19	1.53	0.54	1.12	0.16	0.12	0.12	0.11		0.11	0.12	0.06	0.16	0.09	0.06		0.33	0.01		0.01	0.03					
Jan 2024	2.37	2.21	1.55	0.65	1.17	0.16	0.11	0.15	0.13		0.12	0.14	0.08	0.17	0.10	0.06		0.25	0.01	0.01	0.01	0.01					
Feb 2024	2.38	2.22	1.52	0.69	1.21	0.17	0.12	0.22	0.16		0.13	0.13	0.09	0.17	0.11	0.06		0.22	0.01	0.01	0.01						
Mar 2024	2.53	2.19	1.54	0.69	1.14	0.16	0.12	0.25	0.14		0.14	0.12	0.09	0.16	0.10	0.06		0.22	0.01	0.01	0.01						
Apr 2024	2.53	2.16	1.51	0.73	1.24	0.17	0.34	0.27	0.18		0.15	0.13	0.07	0.15	0.11	0.07	0.01	0.19	0.01	0.01	0.01						
May 2024	2.75	2.24	1.50	0.83	1.20	0.16	0.36	0.30	0.18		0.15	0.14	0.06	0.15	0.11	0.07	0.01	0.09	0.01	0.01	0.01						
Jun 2024	2.88	2.34	1.52	0.91	0.71	0.15	0.37	0.32	0.20	0.03	0.16	0.16	0.07	0.15	0.11	0.07	0.01	0.10	0.01	0.01	0.01						
Jul 2024	2.83	2.45	1.65	1.01	0.71	0.15	0.43	0.34	0.20	0.06	0.18	0.17	0.09	0.15	0.12	0.07	0.01	0.09	0.01	0.01	0.01						
Aug 2024	2.96	2.48	1.70	1.11	0.81	0.35	0.45	0.35	0.19	0.12	0.18	0.18	0.11	0.14	0.12	0.08	0.01	0.08	0.01	0.01	0.01						
Sep 2024	3.13	2.26	1.44	1.18	0.72	0.42	0.44	0.35	0.24	0.12	0.18	0.18	0.13	0.15	0.13	0.08	0.01	0.07	0.01	0.01	0.01						
Oct 2024	3.23	2.35	1.53	1.23	0.66	0.39	0.43	0.40	0.27	0.17	0.19	0.18	0.14	0.14	0.12	0.09	0.01	0.09	0.01	0.01	0.01						
Nov 2024	3.21	2.31	1.52	1.27	0.63	0.41	0.43	0.44	0.29	0.19	0.21	0.17	0.14	0.11	0.12	0.08	0.01	0.10	0.01	0.01	0.01						
Dec 2024	3.06	2.13	1.40	1.29	0.62	0.54	0.43	0.45	0.29	0.24	0.21	0.18	0.15	0.09	0.12	0.08	0.01	0.09	0.01	0.01	0.01						
Jan 2025	2.92	1.73	1.36	1.31	0.66	0.54	0.46	0.41	0.34	0.27	0.21	0.19	0.16	0.12	0.13	0.08	0.01	0.04	0.01	0.01	0.01						
Feb 2025	2.74	1.70	1.45	1.25	0.66	0.48	0.46	0.36	0.33	0.28	0.22	0.18	0.16	0.14	0.12	0.08	0.01	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

### Overall

At least one tracker was found on 18.09% of new episodes in February, shrinking 1.30% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "45.40%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.70%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "10.53%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.27%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.65%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.14%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.94%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.45%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.41%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.06%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of February 2025.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 12.47% of new episodes in February, shrinking 1.20% from last month.

Of these, 10.21% had one other tracker, 7.59% had 2 other trackers, 1.37% had 3 other trackers, 1.32% had 5 other trackers, 1.23% had 4 other trackers, 0.44% had 6 other trackers, 0.11% had 8 other trackers, and 0.10% had 7 other trackers.

9.04% also included Podsights, 6.40% also included Adswizz, 5.71% also included Chartable, 5.59% also included Podscribe, 3.15% also included Podroll, 2.40% also included Magellan AI, 2.40% also included Podder, 1.65% also included Spotify, 1.51% also included Swap.fm, 1.25% also included Podcorn, 1.10% also included Claritas, 1.04% also included OP3, 0.99% also included Blubrry, 0.88% also included ArtsAI, 0.76% also included Audiotakes, 0.64% also included Gumshoe, 0.56% also included Veritonic, 0.07% also included CoHost Prefix, 0.05% also included Feedpress, 0.02% also included United Podcasters, 0.01% also included Podkite, 0.01% also included Médiamétrie, 0.01% also included Zencastr, and 0.01% also included AdBarker.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "65.73%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "8.64%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.38%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.09%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.78%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.90%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.72%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.91%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.46%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.45%" >}}
---

### 2. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.74% of new episodes in February, shrinking 6.09% from last month.

Of these, 17.71% had 2 other trackers, 12.32% had one other tracker, 1.95% had 4 other trackers, 1.75% had 5 other trackers, 1.48% had 3 other trackers, 0.54% had 6 other trackers, and 0.32% had 7 other trackers.

29.11% also included Podtrac, 12.77% also included Podroll, 7.16% also included Podscribe, 4.93% also included Podsights, 4.52% also included Magellan AI, 2.72% also included Swap.fm, 2.62% also included Claritas, 2.48% also included Spotify, 1.70% also included ArtsAI, 1.35% also included Blubrry, 1.25% also included Audiotakes, 1.06% also included Podder, 0.80% also included Veritonic, 0.77% also included Chartable, 0.58% also included OP3, 0.29% also included Podcorn, 0.05% also included Gumshoe, and 0.02% also included United Podcasters.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "66.50%" >}}
2. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "6.28%" >}}
3. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "4.41%" >}}
4. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "3.70%" >}}
5. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "3.60%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.61%" >}}
7. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "2.27%" >}}
8. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "1.74%" >}}
9. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.41%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.35%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 2.60% of new episodes in February, shrinking 3.81% from last month.

Of these, 55.82% also included Podtrac, 28.94% also included Podscribe, 15.12% also included Magellan AI, 8.38% also included Adswizz, 7.23% also included Claritas, 6.41% also included Swap.fm, 5.59% also included ArtsAI, 5.30% also included Podder, 4.83% also included Audiotakes, 3.52% also included Gumshoe, 3.38% also included Podcorn, 3.06% also included Veritonic, 2.90% also included OP3, 2.58% also included Podroll, 0.51% also included Blubrry, 0.25% also included CoHost Prefix, 0.24% also included United Podcasters, 0.08% also included Feedpress, 0.04% also included Podkite, 0.02% also included Firstory, 0.02% also included Zencastr, and 0.01% also included AdBarker.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "56.10%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "13.70%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.36%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.66%" >}}
5. {{< a "https://azure.microsoft.com/en-us/services/storage/blobs/" "Microsoft Azure Blob Storage" >}} {{< span "weak" "2.55%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.99%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.83%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.66%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.27%" >}}
10. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.21%" >}}
---

### 3. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.70% of new episodes in February, shrinking 1.90% from last month.

Of these, 30.46% had one other tracker, 24.36% had 2 other trackers, 11.34% had 4 other trackers, 10.87% had 3 other trackers, 8.77% had 5 other trackers, 3.50% had 6 other trackers, 0.78% had 8 other trackers, and 0.43% had 7 other trackers.

66.42% also included Podtrac, 43.57% also included Chartable, 34.08% also included Podscribe, 18.44% also included Magellan AI, 8.25% also included Swap.fm, 7.97% also included Adswizz, 7.51% also included Claritas, 7.11% also included ArtsAI, 6.63% also included Podder, 5.58% also included Audiotakes, 4.54% also included Gumshoe, 4.53% also included Podcorn, 4.14% also included OP3, 4.11% also included Spotify, 3.86% also included Veritonic, 3.23% also included Podroll, 0.52% also included Blubrry, 0.35% also included CoHost Prefix, 0.28% also included United Podcasters, 0.13% also included Feedpress, 0.04% also included Podkite, and 0.02% also included Zencastr.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "61.85%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "16.91%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.58%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.07%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.27%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.69%" >}}
7. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.67%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.58%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.31%" >}}
10. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.16%" >}}
---

### 4. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.45% of new episodes in February, growing 6.45% from last month.

Of these, 12.45% had one other tracker, 0.61% had 2 other trackers, 0.32% had 3 other trackers, 0.07% had 5 other trackers, 0.06% had 4 other trackers, and 0.05% had 6 other trackers.

8.49% also included Podtrac, 2.56% also included Adswizz, 1.21% also included Feedpress, 0.95% also included OP3, 0.61% also included Podsights, 0.31% also included Swap.fm, 0.29% also included Podder, 0.28% also included Podcorn, 0.24% also included Podscribe, 0.22% also included Chartable, 0.15% also included Magellan AI, 0.12% also included Spotify, 0.06% also included ArtsAI, 0.01% also included Audiotakes, and 0.01% also included Veritonic.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "45.66%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.54%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.36%" >}}
4. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "3.29%" >}}
5. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "1.86%" >}}
6. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.73%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.73%" >}}
8. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "1.29%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.28%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.19%" >}}
---

### 5. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 1.43% of new episodes in February, shrinking 7.37% from last month.

Of these, 29.52% had 2 other trackers, 21.11% had one other tracker, 7.50% had 3 other trackers, 7.09% had 4 other trackers, 3.82% had 5 other trackers, 2.63% had 6 other trackers, 0.89% had 8 other trackers, and 0.28% had 7 other trackers.

51.69% also included Podsights, 49.74% also included Podtrac, 20.83% also included Podscribe, 11.66% also included Magellan AI, 9.07% also included Swap.fm, 7.57% also included Spotify, 5.09% also included Podder, 4.78% also included Claritas, 3.02% also included Veritonic, 2.74% also included Podroll, 2.26% also included ArtsAI, 1.48% also included Adswizz, 1.29% also included Audiotakes, 1.03% also included Gumshoe, 0.96% also included Podcorn, 0.59% also included OP3, 0.41% also included CoHost Prefix, 0.24% also included United Podcasters, 0.22% also included Blubrry, 0.15% also included Feedpress, 0.04% also included Firstory, 0.04% also included Zencastr, 0.02% also included Podkite, and 0.01% also included AdBarker.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "79.64%" >}}
2. {{< a "https://azure.microsoft.com/en-us/services/storage/blobs/" "Microsoft Azure Blob Storage" >}} {{< span "weak" "4.63%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.81%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.00%" >}}
5. {{< a "https://www.rti.org.tw/" "Radio Taiwan International" >}} {{< span "weak" "1.84%" >}}
6. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.49%" >}}
7. {{< a "https://cloud.google.com/" "Google Cloud" >}} {{< span "weak" "0.36%" >}}
8. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "0.32%" >}}
9. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.30%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.27%" >}}
---

### 6. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 1.25% of new episodes in February, shrinking 4.46% from last month.

Of these, 19.04% had one other tracker, 17.78% had 4 other trackers, 15.59% had 2 other trackers, 14.95% had 5 other trackers, 11.79% had 3 other trackers, 4.96% had 6 other trackers, 1.06% had 8 other trackers, and 1.02% had 7 other trackers.

55.69% also included Podtrac, 46.23% also included Podsights, 34.05% also included Magellan AI, 23.82% also included Chartable, 16.35% also included Claritas, 15.69% also included Spotify, 15.69% also included Adswizz, 12.87% also included ArtsAI, 12.62% also included Audiotakes, 10.55% also included Podder, 7.30% also included Swap.fm, 6.00% also included Podcorn, 5.95% also included Gumshoe, 5.17% also included Veritonic, 4.78% also included OP3, 2.83% also included Podroll, 0.49% also included CoHost Prefix, 0.39% also included United Podcasters, 0.28% also included Blubrry, 0.02% also included Podkite, 0.02% also included Zencastr, and 0.01% also included AdBarker.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "46.88%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.69%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "9.86%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.97%" >}}
5. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "4.81%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.80%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.16%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.92%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.83%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.56%" >}}
---

### 7. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.66% of new episodes in February, shrinking 0.63% from last month.

Of these, 12.30% had one other tracker, 7.28% had 5 other trackers, 4.52% had 2 other trackers, 2.35% had 4 other trackers, 1.96% had 3 other trackers, 0.25% had 6 other trackers, 0.12% had 8 other trackers, and 0.06% had 7 other trackers.

23.64% also included Podtrac, 11.66% also included Podsights, 11.39% also included Podscribe, 10.48% also included OP3, 8.96% also included Gumshoe, 2.32% also included Podroll, 2.07% also included Chartable, 1.75% also included Podder, 1.20% also included Adswizz, 0.75% also included Spotify, 0.62% also included Blubrry, 0.30% also included Swap.fm, 0.23% also included Zencastr, 0.16% also included Magellan AI, 0.09% also included Podkite, 0.09% also included United Podcasters, 0.09% also included Feedpress, 0.08% also included CoHost Prefix, 0.04% also included Audiotakes, and 0.02% also included AdBarker.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "25.15%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "11.62%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "11.28%" >}}
4. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "10.75%" >}}
5. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.81%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.69%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "7.38%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.93%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.57%" >}}
10. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "1.84%" >}}
---

### 8. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.60% of new episodes in February, growing 3.47% from last month.

Of these, 23.35% had 4 other trackers, 18.48% had 5 other trackers, 13.69% had 3 other trackers, 9.98% had 2 other trackers, 8.76% had 6 other trackers, 6.16% had one other tracker, 2.08% had 8 other trackers, and 1.79% had 7 other trackers.

70.97% also included Podscribe, 52.13% also included Podsights, 49.77% also included Podtrac, 28.93% also included Claritas, 27.78% also included Chartable, 20.67% also included Adswizz, 20.00% also included Spotify, 17.15% also included ArtsAI, 13.54% also included Audiotakes, 9.49% also included Podder, 9.29% also included Swap.fm, 9.00% also included Veritonic, 2.37% also included Podroll, 1.77% also included Gumshoe, 0.89% also included OP3, 0.36% also included Blubrry, 0.32% also included United Podcasters, 0.18% also included Podcorn, and 0.08% also included CoHost Prefix.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "40.64%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "15.65%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.54%" >}}
4. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "8.18%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.16%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.60%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.68%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "4.33%" >}}
9. {{< a "https://www.americanpublicmedia.org/" "American Public Media" >}} {{< span "weak" "2.09%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.45%" >}}
---

### 9. [Podder](https://www.podderapp.com/)

Podder was found on 0.48% of new episodes in February, shrinking 10.57% from last month.

Of these, 37.71% had one other tracker, 12.63% had 2 other trackers, 9.42% had 4 other trackers, 7.59% had 5 other trackers, 5.26% had 3 other trackers, 2.71% had 6 other trackers, 0.21% had 7 other trackers, and 0.11% had 8 other trackers.

62.04% also included Podtrac, 27.44% also included Podscribe, 23.37% also included Podsights, 15.12% also included Chartable, 11.83% also included Magellan AI, 9.83% also included Audiotakes, 6.01% also included Adswizz, 4.76% also included ArtsAI, 3.05% also included Spotify, 2.39% also included Podcorn, 1.68% also included Claritas, 1.46% also included OP3, 1.24% also included Gumshoe, 0.92% also included Podroll, 0.86% also included Blubrry, 0.33% also included Swap.fm, 0.33% also included Veritonic, 0.15% also included CoHost Prefix, 0.10% also included Podkite, and 0.08% also included United Podcasters.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "35.82%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.45%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "21.59%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.32%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.79%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.19%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "1.60%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.50%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.03%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.52%" >}}
---

### 10. [Podroll](https://podroll.fm/)

Podroll was found on 0.46% of new episodes in February, shrinking 1.18% from last month.

Of these, 77.21% had 2 other trackers, 8.99% had one other tracker, 4.83% had 3 other trackers, 2.43% had 4 other trackers, 1.97% had 6 other trackers, 1.50% had 5 other trackers, 0.41% had 7 other trackers, and 0.18% had 8 other trackers.

86.34% also included Podtrac, 76.88% also included Adswizz, 12.05% also included Podsights, 8.62% also included Chartable, 7.78% also included Podscribe, 4.72% also included Swap.fm, 3.35% also included Podcorn, 3.12% also included Magellan AI, 1.90% also included Claritas, 1.32% also included ArtsAI, 1.00% also included OP3, 0.97% also included Podder, 0.90% also included Gumshoe, 0.77% also included Spotify, 0.46% also included Audiotakes, 0.37% also included CoHost Prefix, 0.35% also included Veritonic, and 0.31% also included United Podcasters.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "76.72%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.98%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.27%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.90%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "1.81%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.09%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.81%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.57%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.34%" >}}
10. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "0.18%" >}}
---

### 11. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.36% of new episodes in February, shrinking 13.53% from last month.

Of these, 29.51% had 2 other trackers, 15.05% had 5 other trackers, 10.80% had one other tracker, 9.37% had 4 other trackers, 8.20% had 3 other trackers, 5.21% had 6 other trackers, 3.58% had 8 other trackers, and 2.52% had 7 other trackers.

57.62% also included Podtrac, 55.16% also included Podscribe, 33.72% also included Magellan AI, 30.41% also included Chartable, 24.01% also included Claritas, 19.57% also included Podsights, 19.10% also included Adswizz, 14.64% also included ArtsAI, 10.59% also included Audiotakes, 7.15% also included Veritonic, 4.12% also included Podder, 3.46% also included Gumshoe, 1.39% also included Podcorn, 1.24% also included OP3, 0.98% also included Podroll, 0.87% also included Swap.fm, 0.51% also included Blubrry, and 0.17% also included United Podcasters.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "38.13%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.23%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "18.22%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.83%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.61%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.86%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.69%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.60%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.30%" >}}
10. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "0.75%" >}}
---

### 12. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.33% of new episodes in February, shrinking 2.40% from last month.

Of these, 21.92% had one other tracker, 15.08% had 5 other trackers, 6.76% had 2 other trackers, 3.83% had 4 other trackers, 2.81% had 3 other trackers, 0.49% had 6 other trackers, 0.18% had 7 other trackers, and 0.16% had 8 other trackers.

39.23% also included Podtrac, 21.21% also included Podsights, 20.89% also included Podcorn, 18.52% also included Gumshoe, 18.08% also included Podscribe, 4.78% also included Adswizz, 4.15% also included Blubrry, 2.55% also included Chartable, 2.13% also included Podder, 1.62% also included Magellan AI, 1.38% also included Podroll, 1.34% also included Spotify, 1.19% also included Swap.fm, 0.81% also included ArtsAI, 0.59% also included Podkite, 0.57% also included Claritas, 0.49% also included Audiotakes, 0.20% also included CoHost Prefix, 0.16% also included Feedpress, 0.12% also included United Podcasters, and 0.08% also included Zencastr.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "27.83%" >}}
2. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "10.49%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.79%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "6.23%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.60%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.48%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.65%" >}}
8. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "2.41%" >}}
9. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "2.31%" >}}
10. {{< a "https://radiolaser.fr/" "Radio Laser" >}} {{< span "weak" "2.02%" >}}
---

### 13. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.28% of new episodes in February, growing 2.15% from last month.

Of these, 30.58% had 2 other trackers, 18.99% had 3 other trackers, 17.19% had one other tracker, 17.12% had 4 other trackers, 8.23% had 5 other trackers, 2.44% had 6 other trackers, 0.86% had 7 other trackers, and 0.10% had 8 other trackers.

67.10% also included Podtrac, 50.00% also included Podsights, 46.32% also included Chartable, 32.59% also included Podscribe, 26.64% also included Adswizz, 19.89% also included Magellan AI, 7.68% also included Podroll, 4.16% also included ArtsAI, 3.01% also included Claritas, 1.63% also included Blubrry, 1.41% also included OP3, 1.39% also included Gumshoe, 1.10% also included Spotify, 0.81% also included Veritonic, 0.72% also included Podcorn, 0.67% also included Audiotakes, 0.57% also included Podder, 0.41% also included United Podcasters, 0.17% also included CoHost Prefix, and 0.10% also included Zencastr.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "55.14%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "26.21%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.95%" >}}
4. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "4.78%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.46%" >}}
6. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.55%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.43%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.19%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.19%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.10%" >}}
---

### 14. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.22% of new episodes in February, growing 0.67% from last month.

Of these, 32.71% had 5 other trackers, 23.25% had 4 other trackers, 19.36% had 6 other trackers, 6.63% had 3 other trackers, 6.50% had 2 other trackers, 5.79% had 8 other trackers, 2.68% had 7 other trackers, and 1.99% had one other tracker.

95.05% also included Podscribe, 80.67% also included Magellan AI, 63.49% also included Podtrac, 59.20% also included Podsights, 39.71% also included Spotify, 33.43% also included Adswizz, 32.90% also included ArtsAI, 31.78% also included Chartable, 21.88% also included Veritonic, 4.01% also included Podroll, 3.92% also included Swap.fm, 3.77% also included Podder, 1.37% also included Gumshoe, 0.87% also included OP3, 0.34% also included CoHost Prefix, and 0.25% also included Audiotakes.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "42.30%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "27.54%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.21%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.75%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "5.88%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.66%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.50%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.28%" >}}
9. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.25%" >}}
10. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.22%" >}}
---

### 15. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.18% of new episodes in February, shrinking 3.09% from last month.

Of these, 27.77% had 5 other trackers, 23.46% had 4 other trackers, 13.99% had 2 other trackers, 13.55% had 6 other trackers, 6.90% had 8 other trackers, 6.24% had 3 other trackers, 5.86% had 7 other trackers, and 2.04% had one other tracker.

89.20% also included Podscribe, 66.82% also included Podsights, 60.47% also included Podtrac, 57.05% also included Magellan AI, 39.24% also included Claritas, 28.88% also included Spotify, 28.29% also included Audiotakes, 25.84% also included Adswizz, 20.68% also included Veritonic, 17.93% also included Chartable, 12.69% also included Podder, 6.46% also included Swap.fm, 3.34% also included Podroll, 1.48% also included OP3, 0.45% also included Blubrry, and 0.19% also included Gumshoe.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.30%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "18.11%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "14.18%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "12.88%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "11.02%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "7.50%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.12%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.45%" >}}
9. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.26%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.19%" >}}
---

### 16. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.16% of new episodes in February, growing 2.37% from last month.

Of these, 42.01% had 4 other trackers, 20.02% had 3 other trackers, 18.19% had 5 other trackers, 9.19% had 2 other trackers, 7.27% had 6 other trackers, 0.98% had 7 other trackers, and 0.69% had one other tracker.

96.28% also included Podscribe, 57.83% also included Podtrac, 57.74% also included Podsights, 49.57% also included Magellan AI, 31.14% also included ArtsAI, 28.85% also included Podder, 23.01% also included Spotify, 20.96% also included Adswizz, 11.24% also included Chartable, 4.86% also included Veritonic, 2.25% also included Gumshoe, 1.27% also included Podroll, 1.14% also included Swap.fm, 0.98% also included OP3, 0.94% also included United Podcasters, 0.33% also included Claritas, 0.16% also included Podcorn, and 0.08% also included Blubrry.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "31.88%" >}}
2. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "28.28%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "19.74%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "8.58%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.84%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.25%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.80%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.23%" >}}
9. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.20%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.16%" >}}
---

### 17. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.14% of new episodes in February, growing 17.24% from last month.

Of these, 17.12% had one other tracker, and 1.50% had 2 other trackers.

12.24% also included Blubrry, 4.08% also included Podtrac, 1.50% also included Podsights, 1.50% also included Chartable, 0.42% also included Podcorn, and 0.38% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "54.08%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "10.23%" >}}
3. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "5.30%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.25%" >}}
5. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "3.61%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.86%" >}}
7. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "2.86%" >}}
8. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.39%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.64%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.50%" >}}
---

### 18. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.12% of new episodes in February, shrinking 5.91% from last month.

Of these, 40.00% had 5 other trackers, 14.50% had one other tracker, 14.45% had 4 other trackers, 8.95% had 2 other trackers, 8.03% had 3 other trackers, 1.56% had 6 other trackers, 1.29% had 7 other trackers, and 0.43% had 8 other trackers.

63.77% also included Podtrac, 62.05% also included Podsights, 59.95% also included Podscribe, 49.33% also included OP3, 47.55% also included Podcorn, 11.86% also included Chartable, 9.92% also included Spotify, 8.57% also included Magellan AI, 4.80% also included Podder, 3.29% also included Podroll, 3.13% also included Swap.fm, 3.02% also included CoHost Prefix, 2.96% also included Audiotakes, 2.37% also included Claritas, 1.51% also included Veritonic, 1.02% also included Adswizz, 0.81% also included United Podcasters, and 0.27% also included ArtsAI.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "50.40%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.29%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "17.79%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.64%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.51%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "0.97%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.54%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.22%" >}}
9. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.22%" >}}
10. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.16%" >}}
---

### 19. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.08% of new episodes in February, shrinking 0.17% from last month.

Of these, 30.50% had 6 other trackers, 15.21% had 8 other trackers, 14.72% had 5 other trackers, 14.06% had 3 other trackers, 13.08% had 7 other trackers, 7.20% had 2 other trackers, 4.17% had 4 other trackers, and 0.08% had one other tracker.

85.85% also included Podtrac, 79.97% also included Podsights, 78.99% also included Podscribe, 65.90% also included Magellan AI, 57.48% also included Claritas, 52.74% also included Chartable, 45.54% also included ArtsAI, 31.07% also included Spotify, 26.74% also included Adswizz, 9.73% also included Audiotakes, 2.78% also included Swap.fm, 2.29% also included Gumshoe, 1.96% also included Podroll, 1.96% also included Podder, and 0.16% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "63.78%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "21.83%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "4.74%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.35%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.45%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.29%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.57%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.41%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.33%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.25%" >}}
---

### 20. [Firstory](https://firstory.me/)

Firstory was found on 0.04% of new episodes in February, shrinking 14.15% from last month.

Of these, 1.34% had one other tracker.

1.34% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.50%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.50%" >}}
---

### 21. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.01% of new episodes in February, growing 0.90% from last month.

Of these, 24.35% had one other tracker, 20.21% had 5 other trackers, 18.13% had 4 other trackers, 6.22% had 2 other trackers, 4.15% had 6 other trackers, 4.15% had 8 other trackers, and 2.59% had 3 other trackers.

67.88% also included Podtrac, 47.67% also included Podscribe, 45.60% also included Podsights, 45.08% also included Chartable, 29.02% also included Gumshoe, 12.95% also included Podroll, 5.70% also included Claritas, 5.70% also included Podder, 5.18% also included OP3, 4.15% also included Podcorn, 3.63% also included Swap.fm, and 3.63% also included Magellan AI.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "47.67%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.62%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "10.36%" >}}
4. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "6.22%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "6.22%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.11%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.07%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.07%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.07%" >}}
10. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.55%" >}}
---

### 22. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.01% of new episodes in February, shrinking 75.72% from last month.

Of these, 13.04% had one other tracker.

13.04% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "100.00%" >}}
---

### 23. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in February, growing 10.04% from last month.

Of these, 25.00% had one other tracker, 4.41% had 2 other trackers, 3.68% had 5 other trackers, and 2.94% had 4 other trackers.

21.32% also included OP3, 16.91% also included Podtrac, 8.09% also included Podsights, 6.62% also included Podcorn, 5.15% also included Podder, 2.94% also included Podscribe, and 2.94% also included Chartable.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "27.94%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "16.18%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "15.44%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.50%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "11.76%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.88%" >}}
7. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "4.41%" >}}
8. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "3.68%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.47%" >}}
10. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "0.74%" >}}
---

### 24. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in February, shrinking 6.94% from last month.

Of these, 25.74% had one other tracker, 24.26% had 4 other trackers, 16.18% had 3 other trackers, 13.24% had 2 other trackers, 4.41% had 5 other trackers, 3.68% had 6 other trackers, 2.94% had 8 other trackers, and 1.47% had 7 other trackers.

53.68% also included Podscribe, 52.21% also included Podsights, 38.24% also included Chartable, 25.00% also included Podtrac, 21.32% also included Magellan AI, 16.91% also included Audiotakes, 15.44% also included Podroll, 12.50% also included Swap.fm, 11.03% also included Gumshoe, 6.62% also included Podcorn, 6.62% also included Spotify, 5.88% also included Adswizz, 4.41% also included Podder, 4.41% also included OP3, and 1.47% also included Zencastr.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "50.74%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "14.71%" >}}
3. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "10.29%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "7.35%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.88%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.94%" >}}
7. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "2.94%" >}}
8. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "2.94%" >}}
9. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "2.21%" >}}
---

### 25. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in February, shrinking 6.55% from last month.

Of these, 24.55% had one other tracker, 3.64% had 2 other trackers, 1.82% had 6 other trackers, and 1.82% had 7 other trackers.

20.91% also included Podcorn, 10.91% also included Podtrac, 7.27% also included Chartable, 3.64% also included Podscribe, 3.64% also included Swap.fm, 3.64% also included OP3, 3.64% also included Podsights, and 1.82% also included United Podcasters.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "29.09%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "26.36%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "12.73%" >}}
4. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "7.27%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.27%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.27%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "6.36%" >}}
8. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "1.82%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.82%" >}}
---

### 26. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in February, shrinking 19.80% from last month.

Of these, 20.34% had one other tracker, and 3.39% had 3 other trackers.

18.64% also included Podtrac, 5.08% also included Chartable, 3.39% also included Podscribe, and 3.39% also included Podcorn.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "37.29%" >}}
2. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "20.34%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "13.56%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.86%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.78%" >}}
6. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "5.08%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.08%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
