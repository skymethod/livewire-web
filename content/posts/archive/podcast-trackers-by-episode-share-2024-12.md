---
title: "Top Podcast Tracking Services by Episode Share (December 2024)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-december-2024"
images:
- trackers-2024-12.png
date: 2025-01-02T11:11:00-05:00
lastmod: 2025-01-02T11:11:00-05:00
draft: false
rssrevision: 2024-12
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.7 million in December 2024), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in December, how many
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
Month	Podtrac	Adswizz	Chartable	Podsights	Blubrry	Podscribe	Podcorn	Podder	Spotify	Podroll	OP3	Swap.fm	Claritas	ArtsAI	Audiotakes	Gumshoe	Feedpress	Médiamétrie	Veritonic	CoHost Prefix	United Podcasters	Zencastr	Podkite	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	1.00	4.06	1.16	2.07		2.09										0.32	0.42											1.61
Oct 2021	4.05	1.01	4.09	1.20	2.11		2.13										0.34	0.54											1.61
Nov 2021	4.07	1.02	4.30	1.25	2.01		2.14										0.32	0.57											0.59
Dec 2021	4.06	1.24	4.42	1.19	1.57		2.27										0.19	0.59											
Jan 2022	4.11	1.41	4.45	1.21	1.56		2.31										0.16	0.63											
Feb 2022	4.15	1.44	4.48	1.25	1.53		2.38										0.17	0.58											
Mar 2022	4.37	1.51	4.72	1.34	1.56		2.40										0.17	0.53											
Apr 2022	4.44	1.49	4.71	1.33	1.55		2.33										0.16	0.51											
May 2022	4.49	1.58	4.87	1.41	1.48		2.26										0.17	0.56											
Jun 2022	4.75	1.77	5.10	1.54	1.50		2.06										0.21	0.62								0.02			
Jul 2022	4.70	1.89	5.10	1.50	1.50		2.16										0.25	0.54								0.02			
Aug 2022	4.83	2.08	5.26	1.73	1.51		2.45							0.10			0.20	0.41								0.01			
Sep 2022	7.53	2.26	5.40	1.74	1.49	0.02	2.45						0.01	0.09			0.21	0.52					0.01			0.02	0.02		
Oct 2022	8.24	2.35	5.48	1.81	1.61	0.07	2.51				0.03		0.02	0.10			0.18	0.50				0.01	0.01			0.02	0.04		
Nov 2022	8.11	2.37	5.62	2.03	1.62	0.15	2.43	0.01			0.04		0.03	0.10			0.18	0.50				0.01	0.01			0.02	0.05		
Dec 2022	8.01	2.32	5.54	1.81	1.61	0.03	2.05	0.04			0.05		0.02	0.05			0.18	0.49				0.01	0.01		0.01	0.02	0.05		
Jan 2023	7.85	2.35	5.56	1.88	1.61	0.20	2.15	0.11			0.07		0.06	0.10			0.18	0.54				0.01	0.01		0.01	0.02	0.06		
Feb 2023	7.58	2.29	5.51	1.92	1.62	0.21	2.30	0.11			0.07		0.07	0.10			0.19	0.49				0.01	0.01		0.01	0.02	0.06	0.03	
Mar 2023	7.79	2.25	5.53	2.03	1.53	0.21	2.22	0.11		0.04	0.08		0.07	0.11			0.18	0.45	0.04			0.01	0.01		0.01	0.02	0.06		
Apr 2023	7.66	2.26	5.43	2.00	1.67	0.21	2.20	0.15		0.06	0.09		0.07	0.11		0.08	0.17	0.45	0.05			0.01	0.01		0.01	0.01			
May 2023	7.58	2.27	5.59	2.04	1.67	0.24	2.28	0.15		0.09	0.09		0.08	0.11		0.07	0.19	0.45	0.05			0.01	0.01	0.01	0.01	0.01			
Jun 2023	8.22	2.39	5.83	2.23	1.64	0.26	1.86	0.15		0.10	0.09		0.07	0.12		0.08	0.19	0.51	0.05			0.01	0.01	0.01	0.01	0.01			
Jul 2023	8.60	2.38	5.95	2.52	1.53	0.27	1.17	0.14	0.01	0.14	0.08		0.07	0.11		0.06	0.18	0.55	0.06			0.01	0.01	0.01	0.01	0.01			
Aug 2023	9.19	2.72	6.43	2.76	1.58	0.36	1.23	0.15	0.03	0.16	0.11		0.08	0.12	0.04	0.07	0.17	0.53	0.07			0.01	0.01	0.02	0.01				
Sep 2023	8.46	2.49	5.77	2.47	1.39	0.37	1.10	0.15	0.05	0.13	0.10		0.10	0.12	0.05	0.07	0.16	0.58	0.06			0.01	0.01	0.02	0.01				
Oct 2023	7.90	2.29	5.54	2.28	1.37	0.39	1.11	0.16	0.08	0.12	0.10		0.10	0.12	0.05	0.08	0.16	0.50	0.06			0.02	0.01	0.03	0.01				
Nov 2023	7.65	2.25	5.59	2.33	1.45	0.47	1.14	0.16	0.11	0.12	0.13		0.11	0.12	0.06	0.10	0.17	0.33	0.06			0.01	0.01	0.03					
Dec 2023	7.48	2.20	5.60	2.19	1.53	0.54	1.12	0.16	0.12	0.12	0.11		0.11	0.12	0.06	0.09	0.16	0.33	0.06			0.01	0.01	0.03					
Jan 2024	7.64	2.37	5.61	2.21	1.55	0.65	1.17	0.16	0.15	0.11	0.13		0.12	0.14	0.08	0.10	0.17	0.25	0.06		0.01	0.01	0.01	0.01					
Feb 2024	7.69	2.38	5.58	2.22	1.52	0.69	1.21	0.17	0.22	0.12	0.16		0.13	0.13	0.09	0.11	0.17	0.22	0.06		0.01	0.01	0.01						
Mar 2024	9.01	2.53	5.46	2.19	1.54	0.69	1.14	0.16	0.25	0.12	0.14		0.14	0.12	0.09	0.10	0.16	0.22	0.06		0.01	0.01	0.01						
Apr 2024	10.78	2.53	5.47	2.16	1.51	0.73	1.24	0.17	0.27	0.34	0.18		0.15	0.13	0.07	0.11	0.15	0.19	0.07	0.01	0.01	0.01	0.01						
May 2024	11.59	2.75	5.63	2.24	1.50	0.83	1.20	0.16	0.30	0.36	0.18		0.15	0.14	0.06	0.11	0.15	0.09	0.07	0.01	0.01	0.01	0.01						
Jun 2024	11.54	2.88	6.06	2.34	1.52	0.91	0.71	0.15	0.32	0.37	0.20	0.03	0.16	0.16	0.07	0.11	0.15	0.10	0.07	0.01	0.01	0.01	0.01						
Jul 2024	12.34	2.83	6.80	2.45	1.65	1.01	0.71	0.15	0.34	0.43	0.20	0.06	0.18	0.17	0.09	0.12	0.15	0.09	0.07	0.01	0.01	0.01	0.01						
Aug 2024	14.22	2.96	6.72	2.48	1.70	1.11	0.81	0.35	0.35	0.45	0.19	0.12	0.18	0.18	0.11	0.12	0.14	0.08	0.08	0.01	0.01	0.01	0.01						
Sep 2024	12.95	3.13	5.99	2.26	1.44	1.18	0.72	0.42	0.35	0.44	0.24	0.12	0.18	0.18	0.13	0.13	0.15	0.07	0.08	0.01	0.01	0.01	0.01						
Oct 2024	12.24	3.23	5.49	2.35	1.53	1.23	0.66	0.39	0.40	0.43	0.27	0.17	0.19	0.18	0.14	0.12	0.14	0.09	0.09	0.01	0.01	0.01	0.01						
Nov 2024	11.86	3.21	4.66	2.31	1.52	1.27	0.63	0.41	0.44	0.43	0.29	0.19	0.21	0.17	0.14	0.12	0.11	0.10	0.08	0.01	0.01	0.01	0.01						
Dec 2024	12.56	3.06	2.29	2.13	1.40	1.29	0.62	0.54	0.45	0.43	0.29	0.24	0.21	0.18	0.15	0.12	0.09	0.09	0.08	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} are the clear top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podsights	Blubrry	Podscribe	Podcorn	Podder	Spotify	Podroll	OP3	Swap.fm	Claritas	ArtsAI	Audiotakes	Gumshoe	Feedpress	Médiamétrie	Veritonic	CoHost Prefix	United Podcasters	Zencastr	Podkite	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	1.00	1.16	2.07		2.09										0.32	0.42											1.61
Oct 2021	1.01	1.20	2.11		2.13										0.34	0.54											1.61
Nov 2021	1.02	1.25	2.01		2.14										0.32	0.57											0.59
Dec 2021	1.24	1.19	1.57		2.27										0.19	0.59											
Jan 2022	1.41	1.21	1.56		2.31										0.16	0.63											
Feb 2022	1.44	1.25	1.53		2.38										0.17	0.58											
Mar 2022	1.51	1.34	1.56		2.40										0.17	0.53											
Apr 2022	1.49	1.33	1.55		2.33										0.16	0.51											
May 2022	1.58	1.41	1.48		2.26										0.17	0.56											
Jun 2022	1.77	1.54	1.50		2.06										0.21	0.62								0.02			
Jul 2022	1.89	1.50	1.50		2.16										0.25	0.54								0.02			
Aug 2022	2.08	1.73	1.51		2.45							0.10			0.20	0.41								0.01			
Sep 2022	2.26	1.74	1.49	0.02	2.45						0.01	0.09			0.21	0.52					0.01			0.02	0.02		
Oct 2022	2.35	1.81	1.61	0.07	2.51				0.03		0.02	0.10			0.18	0.50				0.01	0.01			0.02	0.04		
Nov 2022	2.37	2.03	1.62	0.15	2.43	0.01			0.04		0.03	0.10			0.18	0.50				0.01	0.01			0.02	0.05		
Dec 2022	2.32	1.81	1.61	0.03	2.05	0.04			0.05		0.02	0.05			0.18	0.49				0.01	0.01		0.01	0.02	0.05		
Jan 2023	2.35	1.88	1.61	0.20	2.15	0.11			0.07		0.06	0.10			0.18	0.54				0.01	0.01		0.01	0.02	0.06		
Feb 2023	2.29	1.92	1.62	0.21	2.30	0.11			0.07		0.07	0.10			0.19	0.49				0.01	0.01		0.01	0.02	0.06	0.03	
Mar 2023	2.25	2.03	1.53	0.21	2.22	0.11		0.04	0.08		0.07	0.11			0.18	0.45	0.04			0.01	0.01		0.01	0.02	0.06		
Apr 2023	2.26	2.00	1.67	0.21	2.20	0.15		0.06	0.09		0.07	0.11		0.08	0.17	0.45	0.05			0.01	0.01		0.01	0.01			
May 2023	2.27	2.04	1.67	0.24	2.28	0.15		0.09	0.09		0.08	0.11		0.07	0.19	0.45	0.05			0.01	0.01	0.01	0.01	0.01			
Jun 2023	2.39	2.23	1.64	0.26	1.86	0.15		0.10	0.09		0.07	0.12		0.08	0.19	0.51	0.05			0.01	0.01	0.01	0.01	0.01			
Jul 2023	2.38	2.52	1.53	0.27	1.17	0.14	0.01	0.14	0.08		0.07	0.11		0.06	0.18	0.55	0.06			0.01	0.01	0.01	0.01	0.01			
Aug 2023	2.72	2.76	1.58	0.36	1.23	0.15	0.03	0.16	0.11		0.08	0.12	0.04	0.07	0.17	0.53	0.07			0.01	0.01	0.02	0.01				
Sep 2023	2.49	2.47	1.39	0.37	1.10	0.15	0.05	0.13	0.10		0.10	0.12	0.05	0.07	0.16	0.58	0.06			0.01	0.01	0.02	0.01				
Oct 2023	2.29	2.28	1.37	0.39	1.11	0.16	0.08	0.12	0.10		0.10	0.12	0.05	0.08	0.16	0.50	0.06			0.02	0.01	0.03	0.01				
Nov 2023	2.25	2.33	1.45	0.47	1.14	0.16	0.11	0.12	0.13		0.11	0.12	0.06	0.10	0.17	0.33	0.06			0.01	0.01	0.03					
Dec 2023	2.20	2.19	1.53	0.54	1.12	0.16	0.12	0.12	0.11		0.11	0.12	0.06	0.09	0.16	0.33	0.06			0.01	0.01	0.03					
Jan 2024	2.37	2.21	1.55	0.65	1.17	0.16	0.15	0.11	0.13		0.12	0.14	0.08	0.10	0.17	0.25	0.06		0.01	0.01	0.01	0.01					
Feb 2024	2.38	2.22	1.52	0.69	1.21	0.17	0.22	0.12	0.16		0.13	0.13	0.09	0.11	0.17	0.22	0.06		0.01	0.01	0.01						
Mar 2024	2.53	2.19	1.54	0.69	1.14	0.16	0.25	0.12	0.14		0.14	0.12	0.09	0.10	0.16	0.22	0.06		0.01	0.01	0.01						
Apr 2024	2.53	2.16	1.51	0.73	1.24	0.17	0.27	0.34	0.18		0.15	0.13	0.07	0.11	0.15	0.19	0.07	0.01	0.01	0.01	0.01						
May 2024	2.75	2.24	1.50	0.83	1.20	0.16	0.30	0.36	0.18		0.15	0.14	0.06	0.11	0.15	0.09	0.07	0.01	0.01	0.01	0.01						
Jun 2024	2.88	2.34	1.52	0.91	0.71	0.15	0.32	0.37	0.20	0.03	0.16	0.16	0.07	0.11	0.15	0.10	0.07	0.01	0.01	0.01	0.01						
Jul 2024	2.83	2.45	1.65	1.01	0.71	0.15	0.34	0.43	0.20	0.06	0.18	0.17	0.09	0.12	0.15	0.09	0.07	0.01	0.01	0.01	0.01						
Aug 2024	2.96	2.48	1.70	1.11	0.81	0.35	0.35	0.45	0.19	0.12	0.18	0.18	0.11	0.12	0.14	0.08	0.08	0.01	0.01	0.01	0.01						
Sep 2024	3.13	2.26	1.44	1.18	0.72	0.42	0.35	0.44	0.24	0.12	0.18	0.18	0.13	0.13	0.15	0.07	0.08	0.01	0.01	0.01	0.01						
Oct 2024	3.23	2.35	1.53	1.23	0.66	0.39	0.40	0.43	0.27	0.17	0.19	0.18	0.14	0.12	0.14	0.09	0.09	0.01	0.01	0.01	0.01						
Nov 2024	3.21	2.31	1.52	1.27	0.63	0.41	0.44	0.43	0.29	0.19	0.21	0.17	0.14	0.12	0.11	0.10	0.08	0.01	0.01	0.01	0.01						
Dec 2024	3.06	2.13	1.40	1.29	0.62	0.54	0.45	0.43	0.29	0.24	0.21	0.18	0.15	0.12	0.09	0.09	0.08	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

### Overall

At least one tracker was found on 19.00% of new episodes in December, shrinking 1.56% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "39.82%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.63%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.90%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.22%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.80%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.27%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.00%" >}}
8. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.29%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.22%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.20%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of December 2024.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 12.56% of new episodes in December, growing 5.80% from last month.

Of these, 13.36% had one other tracker, 8.23% had 2 other trackers, 1.61% had 3 other trackers, 1.27% had 5 other trackers, 1.22% had 4 other trackers, 0.44% had 6 other trackers, 0.12% had 8 other trackers, 0.08% had 7 other trackers, and <0.01% had 9 other trackers.

10.84% also included Podsights, 8.94% also included Chartable, 6.33% also included Adswizz, 6.08% also included Podscribe, 2.86% also included Podroll, 2.80% also included Podder, 2.19% also included Magellan AI, 2.02% also included Spotify, 1.29% also included Podcorn, 1.25% also included Swap.fm, 1.09% also included Claritas, 1.06% also included OP3, 0.92% also included ArtsAI, 0.70% also included Audiotakes, 0.62% also included Gumshoe, 0.55% also included Veritonic, 0.29% also included Blubrry, 0.09% also included CoHost Prefix, 0.03% also included Feedpress, 0.02% also included United Podcasters, 0.01% also included Médiamétrie, 0.01% also included Zencastr, 0.01% also included Podkite, and 0.01% also included AdBarker.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "60.12%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.12%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.33%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.58%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.92%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.21%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.33%" >}}
8. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.06%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.05%" >}}
10. {{< a "https://portal.rozhlas.cz/" "Cesky rozhlas" >}} {{< span "weak" "0.81%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 3.68% of new episodes in December, shrinking 33.11% from last month.

Of these, 52.61% also included Podtrac, 19.70% also included Podscribe, 10.03% also included Magellan AI, 7.92% also included Adswizz, 4.97% also included Claritas, 4.54% also included Swap.fm, 4.28% also included Podder, 3.99% also included ArtsAI, 3.27% also included Audiotakes, 2.65% also included Podcorn, 2.52% also included Gumshoe, 2.16% also included Podroll, 2.15% also included OP3, 2.12% also included Veritonic, 0.60% also included Firstory, 0.31% also included Blubrry, 0.24% also included CoHost Prefix, 0.18% also included United Podcasters, 0.04% also included Feedpress, 0.04% also included Podkite, 0.03% also included Zencastr, and 0.01% also included AdBarker.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "49.61%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.02%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.26%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.62%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.31%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.08%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.06%" >}}
8. {{< a "https://www.rti.org.tw/" "Radio Taiwan International" >}} {{< span "weak" "2.05%" >}}
9. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.75%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "1.66%" >}}
---

### 2. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 3.06% of new episodes in December, shrinking 5.24% from last month.

Of these, 14.52% had 2 other trackers, 14.42% had one other tracker, 1.54% had 5 other trackers, 1.47% had 3 other trackers, 1.32% had 4 other trackers, 0.38% had 6 other trackers, 0.29% had 7 other trackers, and 0.05% had 8 other trackers.

26.02% also included Podtrac, 10.33% also included Podroll, 5.56% also included Podscribe, 4.79% also included Podsights, 3.93% also included Chartable, 3.14% also included Magellan AI, 2.42% also included Claritas, 2.10% also included Spotify, 1.74% also included Swap.fm, 1.29% also included ArtsAI, 1.14% also included Blubrry, 0.92% also included Audiotakes, 0.90% also included Podder, 0.69% also included Veritonic, 0.32% also included OP3, 0.22% also included Podcorn, 0.02% also included Gumshoe, and 0.02% also included United Podcasters.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "52.15%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "8.01%" >}}
3. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "6.86%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "6.80%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "6.51%" >}}
6. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "5.05%" >}}
7. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.32%" >}}
8. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "2.04%" >}}
9. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "1.58%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.22%" >}}
---

### 3. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 2.29% of new episodes in December, shrinking 50.11% from last month.

Of these, 27.03% had 2 other trackers, 27.01% had one other tracker, 6.99% had 3 other trackers, 4.96% had 4 other trackers, 2.63% had 5 other trackers, 1.94% had 6 other trackers, 0.63% had 8 other trackers, 0.22% had 7 other trackers, and 0.01% had 9 other trackers.

48.96% also included Podtrac, 42.85% also included Podsights, 14.40% also included Podscribe, 8.06% also included Magellan AI, 7.69% also included Spotify, 6.14% also included Swap.fm, 5.24% also included Adswizz, 4.18% also included Podder, 3.29% also included Claritas, 2.17% also included Podroll, 2.10% also included Veritonic, 2.08% also included ArtsAI, 1.38% also included Podcorn, 1.21% also included Audiotakes, 0.97% also included Firstory, 0.96% also included OP3, 0.75% also included Gumshoe, 0.26% also included CoHost Prefix, 0.25% also included Blubrry, 0.16% also included United Podcasters, 0.06% also included Feedpress, 0.04% also included Podkite, 0.04% also included Zencastr, and 0.02% also included AdBarker.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "64.15%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.60%" >}}
3. {{< a "https://www.rti.org.tw/" "Radio Taiwan International" >}} {{< span "weak" "3.29%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.98%" >}}
5. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.66%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.04%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.94%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.64%" >}}
9. {{< a "https://portal.rozhlas.cz/" "Cesky rozhlas" >}} {{< span "weak" "1.62%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.41%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.13% of new episodes in December, shrinking 6.40% from last month.

Of these, 36.62% had one other tracker, 22.38% had 2 other trackers, 10.12% had 3 other trackers, 8.66% had 4 other trackers, 6.50% had 5 other trackers, 2.87% had 6 other trackers, 0.70% had 8 other trackers, 0.31% had 7 other trackers, and 0.01% had 9 other trackers.

63.80% also included Podtrac, 46.06% also included Chartable, 25.20% also included Podscribe, 13.24% also included Magellan AI, 6.87% also included Adswizz, 6.19% also included Swap.fm, 5.99% also included Podder, 5.97% also included Claritas, 5.69% also included ArtsAI, 4.08% also included Audiotakes, 3.71% also included Spotify, 3.53% also included Gumshoe, 3.42% also included Podcorn, 3.11% also included Podroll, 3.10% also included OP3, 3.00% also included Veritonic, 0.37% also included CoHost Prefix, 0.25% also included Blubrry, 0.23% also included United Podcasters, 0.06% also included Feedpress, 0.04% also included Zencastr, and 0.02% also included Podkite.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "59.52%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "23.72%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.00%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.98%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.55%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.78%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.30%" >}}
8. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.27%" >}}
9. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.00%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.78%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.40% of new episodes in December, growing 1.07% from last month.

Of these, 5.67% had one other tracker, 0.41% had 2 other trackers, 0.20% had 3 other trackers, 0.06% had 4 other trackers, 0.03% had 5 other trackers, and 0.03% had 6 other trackers.

2.59% also included Podtrac, 2.49% also included Adswizz, 0.55% also included Feedpress, 0.40% also included Chartable, 0.38% also included Podsights, 0.34% also included OP3, 0.23% also included Podscribe, 0.17% also included Podder, 0.16% also included Swap.fm, 0.13% also included Podcorn, 0.08% also included Magellan AI, 0.07% also included Spotify, 0.01% also included Podroll, 0.01% also included Audiotakes, and 0.01% also included Veritonic.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "38.12%" >}}
2. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "10.24%" >}}
3. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "7.20%" >}}
4. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "4.04%" >}}
5. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "2.81%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.30%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.85%" >}}
8. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "0.96%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.91%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.66%" >}}
---

### 6. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 1.29% of new episodes in December, growing 4.18% from last month.

Of these, 24.80% had one other tracker, 14.92% had 2 other trackers, 14.74% had 4 other trackers, 13.62% had 5 other trackers, 10.96% had 3 other trackers, 4.91% had 6 other trackers, 1.16% had 8 other trackers, 0.88% had 7 other trackers, and 0.01% had 9 other trackers.

59.08% also included Podtrac, 41.62% also included Podsights, 26.19% also included Magellan AI, 25.56% also included Chartable, 15.97% also included Spotify, 15.28% also included Claritas, 13.15% also included Adswizz, 12.17% also included ArtsAI, 11.20% also included Audiotakes, 9.78% also included Podder, 5.92% also included Podcorn, 5.43% also included Gumshoe, 5.16% also included Swap.fm, 4.63% also included Veritonic, 4.25% also included OP3, 3.00% also included Podroll, 0.54% also included CoHost Prefix, 0.32% also included United Podcasters, 0.24% also included Blubrry, 0.05% also included Zencastr, 0.02% also included Podkite, and 0.02% also included AdBarker.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "50.80%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "11.78%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "11.39%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.39%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.28%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "4.08%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.65%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.47%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.15%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.40%" >}}
---

### 7. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.62% of new episodes in December, shrinking 1.56% from last month.

Of these, 14.31% had one other tracker, 6.63% had 5 other trackers, 5.19% had 2 other trackers, 2.88% had 4 other trackers, 2.32% had 3 other trackers, 0.60% had 6 other trackers, 0.10% had 7 other trackers, 0.10% had 8 other trackers, and 0.02% had 9 other trackers.

26.14% also included Podtrac, 12.30% also included Podscribe, 11.73% also included Podsights, 9.88% also included OP3, 8.56% also included Gumshoe, 5.10% also included Chartable, 2.54% also included Podroll, 1.86% also included Podder, 1.06% also included Adswizz, 0.56% also included Spotify, 0.45% also included Magellan AI, 0.33% also included Swap.fm, 0.30% also included Blubrry, 0.20% also included Zencastr, 0.17% also included Feedpress, 0.10% also included CoHost Prefix, 0.09% also included Podkite, 0.09% also included United Podcasters, 0.06% also included Audiotakes, and 0.05% also included AdBarker.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "18.75%" >}}
2. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "16.80%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "12.92%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "11.20%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "8.84%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "8.53%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.69%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.47%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.17%" >}}
10. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "1.86%" >}}
---

### 8. [Podder](https://www.podderapp.com/)

Podder was found on 0.54% of new episodes in December, growing 33.83% from last month.

Of these, 42.55% had one other tracker, 9.02% had 4 other trackers, 8.71% had 2 other trackers, 7.84% had 5 other trackers, 5.44% had 3 other trackers, 2.31% had 6 other trackers, 0.20% had 7 other trackers, 0.09% had 8 other trackers, and 0.02% had 9 other trackers.

64.73% also included Podtrac, 23.48% also included Podsights, 23.20% also included Podscribe, 17.59% also included Chartable, 10.73% also included Magellan AI, 8.02% also included Audiotakes, 5.06% also included Adswizz, 3.38% also included ArtsAI, 2.94% also included Spotify, 2.12% also included Podcorn, 1.80% also included Claritas, 1.04% also included OP3, 0.98% also included Podroll, 0.97% also included Gumshoe, 0.43% also included Blubrry, 0.40% also included Veritonic, 0.32% also included Swap.fm, 0.22% also included CoHost Prefix, 0.14% also included United Podcasters, and 0.09% also included Podkite.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "41.45%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.56%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "22.53%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.18%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.76%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.02%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.02%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.97%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.96%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.37%" >}}
---

### 9. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.51% of new episodes in December, growing 28.44% from last month.

Of these, 22.42% had 4 other trackers, 20.51% had 5 other trackers, 14.29% had 3 other trackers, 9.79% had 6 other trackers, 8.14% had 2 other trackers, 6.23% had one other tracker, 2.83% had 8 other trackers, and 1.98% had 7 other trackers.

66.52% also included Podscribe, 55.55% also included Podsights, 54.11% also included Podtrac, 36.34% also included Chartable, 31.92% also included Claritas, 22.54% also included Spotify, 18.89% also included Adswizz, 18.29% also included ArtsAI, 14.21% also included Audiotakes, 11.49% also included Podder, 9.59% also included Veritonic, 6.67% also included Swap.fm, 2.77% also included Podroll, 1.88% also included Gumshoe, 0.96% also included OP3, 0.55% also included Podcorn, 0.29% also included United Podcasters, 0.21% also included Blubrry, and 0.05% also included CoHost Prefix.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "43.41%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "14.97%" >}}
3. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "11.85%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.56%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.53%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.42%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.33%" >}}
8. {{< a "https://www.americanpublicmedia.org/" "American Public Media" >}} {{< span "weak" "3.59%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "2.74%" >}}
10. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.40%" >}}
---

### 10. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.45% of new episodes in December, growing 2.23% from last month.

Of these, 35.75% had 2 other trackers, 12.02% had 5 other trackers, 7.54% had one other tracker, 7.11% had 4 other trackers, 6.50% had 3 other trackers, 4.68% had 6 other trackers, 3.18% had 8 other trackers, and 1.58% had 7 other trackers.

56.43% also included Podtrac, 45.82% also included Podscribe, 39.16% also included Chartable, 25.45% also included Magellan AI, 18.48% also included Claritas, 17.55% also included Podsights, 14.25% also included Adswizz, 11.72% also included ArtsAI, 8.74% also included Audiotakes, 4.83% also included Veritonic, 3.55% also included Podder, 2.73% also included Gumshoe, 0.90% also included OP3, 0.78% also included Podcorn, 0.55% also included Podroll, 0.42% also included Swap.fm, 0.21% also included Blubrry, and 0.09% also included United Podcasters.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "42.48%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "25.78%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "13.22%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.04%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.01%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.77%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.63%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.36%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.95%" >}}
10. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "0.55%" >}}
---

### 11. [Podroll](https://podroll.fm/)

Podroll was found on 0.43% of new episodes in December, growing 0.16% from last month.

Of these, 75.98% had 2 other trackers, 9.16% had one other tracker, 4.65% had 4 other trackers, 3.90% had 3 other trackers, 1.85% had 5 other trackers, 1.73% had 6 other trackers, 0.42% had 7 other trackers, 0.18% had 8 other trackers, and 0.03% had 9 other trackers.

84.15% also included Podtrac, 73.89% also included Adswizz, 15.54% also included Podsights, 11.63% also included Chartable, 9.07% also included Podscribe, 4.43% also included Swap.fm, 3.70% also included Podcorn, 3.30% also included Magellan AI, 2.18% also included Claritas, 1.36% also included ArtsAI, 1.25% also included Podder, 1.11% also included Gumshoe, 1.10% also included OP3, 0.89% also included Audiotakes, 0.71% also included CoHost Prefix, 0.58% also included Spotify, 0.36% also included Veritonic, 0.31% also included United Podcasters, and 0.04% also included Blubrry.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "73.36%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "15.53%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.40%" >}}
4. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "2.21%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.07%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.10%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.85%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.39%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.36%" >}}
10. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "0.24%" >}}
---

### 12. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.29% of new episodes in December, growing 1.57% from last month.

Of these, 23.05% had one other tracker, 15.25% had 5 other trackers, 7.25% had 2 other trackers, 4.18% had 3 other trackers, 3.67% had 4 other trackers, 1.14% had 6 other trackers, 0.18% had 7 other trackers, 0.16% had 8 other trackers, and 0.04% had 9 other trackers.

45.66% also included Podtrac, 22.66% also included Podsights, 21.09% also included Podcorn, 19.96% also included Gumshoe, 18.86% also included Podscribe, 7.57% also included Chartable, 3.37% also included Adswizz, 1.94% also included Podder, 1.67% also included Magellan AI, 1.65% also included Blubrry, 1.61% also included Podroll, 1.39% also included Spotify, 0.84% also included ArtsAI, 0.80% also included Swap.fm, 0.59% also included Claritas, 0.37% also included Podkite, 0.35% also included Audiotakes, 0.20% also included CoHost Prefix, 0.18% also included United Podcasters, and 0.08% also included Feedpress.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "29.35%" >}}
2. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "10.70%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.53%" >}}
4. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "5.39%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.61%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.27%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.06%" >}}
8. {{< a "https://radiolaser.fr/" "Radio Laser" >}} {{< span "weak" "2.51%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.27%" >}}
10. {{< a "https://podcastai.com/" "PodcastAI" >}} {{< span "weak" "2.20%" >}}
---

### 13. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.24% of new episodes in December, growing 33.16% from last month.

Of these, 27.58% had 2 other trackers, 25.69% had 3 other trackers, 19.75% had one other tracker, 16.07% had 4 other trackers, 5.25% had 5 other trackers, 2.65% had 6 other trackers, 0.42% had 7 other trackers, and 0.07% had 8 other trackers.

64.97% also included Podtrac, 58.10% also included Chartable, 54.49% also included Podsights, 27.48% also included Podscribe, 21.96% also included Adswizz, 13.98% also included Magellan AI, 7.80% also included Podroll, 2.72% also included ArtsAI, 2.36% also included Claritas, 1.32% also included Gumshoe, 1.01% also included Veritonic, 0.96% also included OP3, 0.93% also included Blubrry, 0.83% also included Podcorn, 0.79% also included Spotify, 0.71% also included Podder, 0.64% also included Audiotakes, 0.49% also included United Podcasters, 0.25% also included Zencastr, and 0.12% also included CoHost Prefix.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "65.31%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "21.52%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.75%" >}}
4. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "3.07%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.15%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.47%" >}}
7. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.44%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.29%" >}}
---

### 14. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.21% of new episodes in December, growing 2.40% from last month.

Of these, 29.11% had 5 other trackers, 23.44% had 4 other trackers, 20.40% had 6 other trackers, 8.28% had 2 other trackers, 6.20% had 8 other trackers, 5.49% had 3 other trackers, 3.47% had 7 other trackers, and 3.21% had one other tracker.

93.49% also included Podscribe, 76.89% also included Magellan AI, 64.89% also included Podtrac, 60.36% also included Podsights, 39.42% also included Spotify, 35.73% also included Chartable, 35.00% also included Adswizz, 32.09% also included ArtsAI, 20.01% also included Veritonic, 4.65% also included Podder, 4.42% also included Podroll, 2.70% also included Swap.fm, 0.82% also included OP3, 0.82% also included Gumshoe, 0.31% also included Audiotakes, and 0.23% also included CoHost Prefix.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "41.96%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "28.71%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.19%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.10%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "6.09%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.00%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.25%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.17%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.14%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.14%" >}}
---

### 15. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.18% of new episodes in December, growing 3.24% from last month.

Of these, 24.67% had 5 other trackers, 24.41% had 4 other trackers, 13.41% had 6 other trackers, 11.87% had 2 other trackers, 8.09% had 8 other trackers, 7.09% had 3 other trackers, 5.82% had 7 other trackers, and 4.48% had one other tracker.

88.33% also included Podscribe, 68.27% also included Podsights, 64.93% also included Podtrac, 52.29% also included Magellan AI, 38.08% also included Claritas, 29.66% also included Spotify, 26.85% also included Chartable, 26.68% also included Audiotakes, 22.13% also included Adswizz, 20.39% also included Veritonic, 10.33% also included Podder, 3.71% also included Swap.fm, 3.28% also included Podroll, 1.37% also included OP3, and 0.07% also included Gumshoe.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.20%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.52%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "14.51%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "11.80%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "11.67%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "7.12%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.24%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.47%" >}}
9. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.30%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.17%" >}}
---

### 16. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.15% of new episodes in December, growing 10.60% from last month.

Of these, 36.98% had 4 other trackers, 20.63% had 3 other trackers, 20.47% had 5 other trackers, 8.99% had 2 other trackers, 8.64% had 6 other trackers, 1.13% had one other tracker, and 1.05% had 7 other trackers.

94.71% also included Podscribe, 57.14% also included Podtrac, 56.95% also included Podsights, 47.29% also included Magellan AI, 31.06% also included ArtsAI, 28.57% also included Podder, 25.77% also included Spotify, 18.33% also included Adswizz, 18.14% also included Chartable, 4.55% also included Veritonic, 2.49% also included Podroll, 2.14% also included Gumshoe, 1.01% also included Swap.fm, 0.90% also included United Podcasters, 0.66% also included OP3, 0.43% also included Claritas, 0.23% also included Podcorn, and 0.12% also included Blubrry.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.10%" >}}
2. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "24.83%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "17.21%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "9.73%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.45%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.75%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.56%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.36%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.78%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.16%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.12% of new episodes in December, growing 2.35% from last month.

Of these, 35.87% had 5 other trackers, 16.05% had one other tracker, 13.98% had 4 other trackers, 10.35% had 3 other trackers, 10.21% had 2 other trackers, 3.68% had 6 other trackers, 0.39% had 8 other trackers, 0.10% had 7 other trackers, and 0.10% had 9 other trackers.

64.28% also included Podtrac, 62.07% also included Podsights, 57.90% also included Podscribe, 47.99% also included OP3, 43.92% also included Podcorn, 14.28% also included Chartable, 10.16% also included Spotify, 7.90% also included Magellan AI, 4.37% also included Podder, 3.93% also included Podroll, 3.04% also included CoHost Prefix, 2.70% also included Audiotakes, 2.65% also included Swap.fm, 1.47% also included Veritonic, 1.42% also included Claritas, 0.83% also included United Podcasters, 0.59% also included Adswizz, and 0.10% also included ArtsAI.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "48.68%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.70%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "19.19%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.17%" >}}
5. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "2.40%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.98%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.25%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.25%" >}}
9. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.25%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.10%" >}}
---

### 18. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.09% of new episodes in December, shrinking 12.28% from last month.

Of these, 12.99% had one other tracker, and 1.32% had 2 other trackers.

8.09% also included Blubrry, 3.39% also included Podtrac, 1.44% also included Chartable, 1.32% also included Podsights, 1.13% also included Podcorn, and 0.25% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "75.22%" >}}
2. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "6.90%" >}}
3. {{< a "https://podcasters.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "3.45%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.51%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.13%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.76%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.25%" >}}
8. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.13%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.13%" >}}
10. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "0.94%" >}}
---

### 19. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.09% of new episodes in December, shrinking 6.14% from last month.

Of these, 1.97% had one other tracker.

1.97% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "41.44%" >}}
2. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "33.74%" >}}
3. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "21.07%" >}}
---

### 20. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.08% of new episodes in December, shrinking 1.31% from last month.

Of these, 26.15% had 6 other trackers, 17.76% had 8 other trackers, 16.94% had 5 other trackers, 11.37% had 3 other trackers, 9.14% had 2 other trackers, 9.14% had 7 other trackers, and 8.10% had 4 other trackers.

86.11% also included Podtrac, 79.87% also included Podsights, 74.67% also included Podscribe, 60.92% also included Magellan AI, 60.18% also included Chartable, 52.75% also included Claritas, 45.32% also included ArtsAI, 27.19% also included Spotify, 26.52% also included Adswizz, 8.69% also included Audiotakes, 3.05% also included Swap.fm, 2.75% also included Podder, 2.23% also included Gumshoe, 1.93% also included Podroll, and 0.22% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "64.71%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "21.32%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "4.53%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.64%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.75%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.41%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.82%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.37%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.22%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.22%" >}}
---

### 21. [Firstory](https://firstory.me/)

Firstory was found on 0.06% of new episodes in December, growing 1.22% from last month.

Of these, 36.72% had one other tracker.

36.72% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.70%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.30%" >}}
---

### 22. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.01% of new episodes in December, growing 4.66% from last month.

Of these, 21.49% had 4 other trackers, 18.86% had 2 other trackers, 16.67% had 3 other trackers, 14.91% had one other tracker, 13.16% had 5 other trackers, 3.51% had 6 other trackers, 3.51% had 8 other trackers, and 0.88% had 9 other trackers.

83.33% also included Podtrac, 57.89% also included Podsights, 51.32% also included Podscribe, 44.30% also included Chartable, 27.19% also included Gumshoe, 22.37% also included Podroll, 8.77% also included Podder, 4.39% also included OP3, 4.39% also included Podcorn, 3.51% also included Claritas, 2.19% also included Swap.fm, and 1.75% also included Magellan AI.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "57.02%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "15.35%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "7.02%" >}}
4. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "6.14%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.82%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.19%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.75%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.88%" >}}
---

### 23. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in December, shrinking 9.15% from last month.

Of these, 20.27% had one other tracker, 20.27% had 4 other trackers, 18.92% had 2 other trackers, 16.22% had 3 other trackers, 7.43% had 5 other trackers, 4.05% had 6 other trackers, 2.70% had 7 other trackers, and 1.35% had 8 other trackers.

55.41% also included Podsights, 47.30% also included Podscribe, 41.22% also included Chartable, 28.38% also included Podtrac, 16.89% also included Magellan AI, 15.54% also included Audiotakes, 14.86% also included Podroll, 13.51% also included Swap.fm, 11.49% also included Gumshoe, 8.78% also included Podder, 6.08% also included Podcorn, 6.08% also included OP3, 5.41% also included Adswizz, 4.73% also included Spotify, and 3.38% also included Zencastr.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "48.65%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "15.54%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.81%" >}}
4. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "8.11%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.41%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.73%" >}}
7. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "3.38%" >}}
8. {{< a "https://podcasters.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "2.70%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.68%" >}}
---

### 24. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in December, growing 13.58% from last month.

Of these, 19.38% had one other tracker, 3.88% had 6 other trackers, 3.10% had 7 other trackers, 2.33% had 2 other trackers, and 0.78% had 5 other trackers.

16.28% also included Podcorn, 15.50% also included Podtrac, 11.63% also included Chartable, 10.08% also included Podsights, 7.75% also included Podscribe, 7.75% also included Swap.fm, and 3.88% also included United Podcasters.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "28.68%" >}}
2. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "26.36%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "10.85%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "10.08%" >}}
5. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "6.98%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.98%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.43%" >}}
8. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "2.33%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.33%" >}}
---

### 25. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in December, shrinking 13.47% from last month.

Of these, 19.83% had one other tracker, 6.90% had 2 other trackers, 3.45% had 5 other trackers, 2.59% had 4 other trackers, and 1.72% had 6 other trackers.

16.38% also included Podtrac, 15.52% also included OP3, 13.79% also included Chartable, 7.76% also included Podcorn, 6.90% also included Podsights, 6.90% also included Podder, and 4.31% also included Podscribe.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "22.41%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "19.83%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "18.97%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "14.66%" >}}
5. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "7.76%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.90%" >}}
7. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "3.45%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.45%" >}}
9. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "0.86%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.86%" >}}
---

### 26. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in December, growing 0.71% from last month.

Of these, 20.00% had one other tracker, 6.67% had 3 other trackers, and 5.00% had 2 other trackers.

21.67% also included Podtrac, 13.33% also included Chartable, 8.33% also included Podcorn, and 6.67% also included Podscribe.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "46.67%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "18.33%" >}}
3. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "15.00%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "10.00%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.00%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.33%" >}}
7. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "1.67%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2024-12.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
