---
title: "Top Podcast Tracking Services by Episode Share (January 2025)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2025-01.png
date: 2025-02-03T11:56:00-05:00
lastmod: 2025-02-03T11:56:00-05:00
draft: false
rssrevision: 2025-01
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.5 million in January 2025), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in January, how many
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
Month	Podtrac	Adswizz	Podsights	Chartable	Blubrry	Podscribe	Podcorn	Podder	Podroll	Spotify	OP3	Swap.fm	Claritas	ArtsAI	Audiotakes	Gumshoe	Feedpress	Veritonic	Médiamétrie	CoHost Prefix	United Podcasters	Podkite	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	1.00	1.16	4.06	2.07		2.09										0.32		0.42										1.61
Oct 2021	4.05	1.01	1.20	4.09	2.11		2.13										0.34		0.54										1.61
Nov 2021	4.07	1.02	1.25	4.30	2.01		2.14										0.32		0.57										0.59
Dec 2021	4.06	1.24	1.19	4.42	1.57		2.27										0.19		0.59										
Jan 2022	4.11	1.41	1.21	4.45	1.56		2.31										0.16		0.63										
Feb 2022	4.15	1.44	1.25	4.48	1.53		2.38										0.17		0.58										
Mar 2022	4.37	1.51	1.34	4.72	1.56		2.40										0.17		0.53										
Apr 2022	4.44	1.49	1.33	4.71	1.55		2.33										0.16		0.51										
May 2022	4.49	1.58	1.41	4.87	1.48		2.26										0.17		0.56										
Jun 2022	4.75	1.77	1.54	5.10	1.50		2.06										0.21		0.62							0.02			
Jul 2022	4.70	1.89	1.50	5.10	1.50		2.16										0.25		0.54							0.02			
Aug 2022	4.83	2.08	1.73	5.26	1.51		2.45							0.10			0.20		0.41							0.01			
Sep 2022	7.53	2.26	1.74	5.40	1.49	0.02	2.45						0.01	0.09			0.21		0.52			0.01				0.02	0.02		
Oct 2022	8.24	2.35	1.81	5.48	1.61	0.07	2.51				0.03		0.02	0.10			0.18		0.50			0.01	0.01			0.02	0.04		
Nov 2022	8.11	2.37	2.03	5.62	1.62	0.15	2.43	0.01			0.04		0.03	0.10			0.18		0.50			0.01	0.01			0.02	0.05		
Dec 2022	8.01	2.32	1.81	5.54	1.61	0.03	2.05	0.04			0.05		0.02	0.05			0.18		0.49			0.01	0.01		0.01	0.02	0.05		
Jan 2023	7.85	2.35	1.88	5.56	1.61	0.20	2.15	0.11			0.07		0.06	0.10			0.18		0.54			0.01	0.01		0.01	0.02	0.06		
Feb 2023	7.58	2.29	1.92	5.51	1.62	0.21	2.30	0.11			0.07		0.07	0.10			0.19		0.49			0.01	0.01		0.01	0.02	0.06	0.03	
Mar 2023	7.79	2.25	2.03	5.53	1.53	0.21	2.22	0.11	0.04		0.08		0.07	0.11			0.18	0.04	0.45			0.01	0.01		0.01	0.02	0.06		
Apr 2023	7.66	2.26	2.00	5.43	1.67	0.21	2.20	0.15	0.06		0.09		0.07	0.11		0.08	0.17	0.05	0.45			0.01	0.01		0.01	0.01			
May 2023	7.58	2.27	2.04	5.59	1.67	0.24	2.28	0.15	0.09		0.09		0.08	0.11		0.07	0.19	0.05	0.45			0.01	0.01	0.01	0.01	0.01			
Jun 2023	8.22	2.39	2.23	5.83	1.64	0.26	1.86	0.15	0.10		0.09		0.07	0.12		0.08	0.19	0.05	0.51			0.01	0.01	0.01	0.01	0.01			
Jul 2023	8.60	2.38	2.52	5.95	1.53	0.27	1.17	0.14	0.14	0.01	0.08		0.07	0.11		0.06	0.18	0.06	0.55			0.01	0.01	0.01	0.01	0.01			
Aug 2023	9.19	2.72	2.76	6.43	1.58	0.36	1.23	0.15	0.16	0.03	0.11		0.08	0.12	0.04	0.07	0.17	0.07	0.53			0.01	0.01	0.02	0.01				
Sep 2023	8.46	2.49	2.47	5.77	1.39	0.37	1.10	0.15	0.13	0.05	0.10		0.10	0.12	0.05	0.07	0.16	0.06	0.58			0.01	0.01	0.02	0.01				
Oct 2023	7.90	2.29	2.28	5.54	1.37	0.39	1.11	0.16	0.12	0.08	0.10		0.10	0.12	0.05	0.08	0.16	0.06	0.50			0.01	0.02	0.03	0.01				
Nov 2023	7.65	2.25	2.33	5.59	1.45	0.47	1.14	0.16	0.12	0.11	0.13		0.11	0.12	0.06	0.10	0.17	0.06	0.33			0.01	0.01	0.03					
Dec 2023	7.48	2.20	2.19	5.60	1.53	0.54	1.12	0.16	0.12	0.12	0.11		0.11	0.12	0.06	0.09	0.16	0.06	0.33			0.01	0.01	0.03					
Jan 2024	7.64	2.37	2.21	5.61	1.55	0.65	1.17	0.16	0.11	0.15	0.13		0.12	0.14	0.08	0.10	0.17	0.06	0.25		0.01	0.01	0.01	0.01					
Feb 2024	7.69	2.38	2.22	5.58	1.52	0.69	1.21	0.17	0.12	0.22	0.16		0.13	0.13	0.09	0.11	0.17	0.06	0.22		0.01	0.01	0.01						
Mar 2024	9.01	2.53	2.19	5.46	1.54	0.69	1.14	0.16	0.12	0.25	0.14		0.14	0.12	0.09	0.10	0.16	0.06	0.22		0.01	0.01	0.01						
Apr 2024	10.78	2.53	2.16	5.47	1.51	0.73	1.24	0.17	0.34	0.27	0.18		0.15	0.13	0.07	0.11	0.15	0.07	0.19	0.01	0.01	0.01	0.01						
May 2024	11.59	2.75	2.24	5.63	1.50	0.83	1.20	0.16	0.36	0.30	0.18		0.15	0.14	0.06	0.11	0.15	0.07	0.09	0.01	0.01	0.01	0.01						
Jun 2024	11.54	2.88	2.34	6.06	1.52	0.91	0.71	0.15	0.37	0.32	0.20	0.03	0.16	0.16	0.07	0.11	0.15	0.07	0.10	0.01	0.01	0.01	0.01						
Jul 2024	12.34	2.83	2.45	6.80	1.65	1.01	0.71	0.15	0.43	0.34	0.20	0.06	0.18	0.17	0.09	0.12	0.15	0.07	0.09	0.01	0.01	0.01	0.01						
Aug 2024	14.22	2.96	2.48	6.72	1.70	1.11	0.81	0.35	0.45	0.35	0.19	0.12	0.18	0.18	0.11	0.12	0.14	0.08	0.08	0.01	0.01	0.01	0.01						
Sep 2024	12.95	3.13	2.26	5.99	1.44	1.18	0.72	0.42	0.44	0.35	0.24	0.12	0.18	0.18	0.13	0.13	0.15	0.08	0.07	0.01	0.01	0.01	0.01						
Oct 2024	12.24	3.23	2.35	5.49	1.53	1.23	0.66	0.39	0.43	0.40	0.27	0.17	0.19	0.18	0.14	0.12	0.14	0.09	0.09	0.01	0.01	0.01	0.01						
Nov 2024	11.86	3.21	2.31	4.66	1.52	1.27	0.63	0.41	0.43	0.44	0.29	0.19	0.21	0.17	0.14	0.12	0.11	0.08	0.10	0.01	0.01	0.01	0.01						
Dec 2024	12.56	3.06	2.13	2.29	1.40	1.29	0.62	0.54	0.43	0.45	0.29	0.24	0.21	0.18	0.15	0.12	0.09	0.08	0.09	0.01	0.01	0.01	0.01						
Jan 2025	12.62	2.92	1.73	1.54	1.36	1.31	0.66	0.54	0.46	0.41	0.34	0.27	0.21	0.19	0.16	0.13	0.12	0.08	0.04	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} are the clear top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podsights	Blubrry	Podscribe	Podcorn	Podder	Podroll	Spotify	OP3	Swap.fm	Claritas	ArtsAI	Audiotakes	Gumshoe	Feedpress	Veritonic	Médiamétrie	CoHost Prefix	United Podcasters	Podkite	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	1.00	1.16	2.07		2.09										0.32		0.42										1.61
Oct 2021	1.01	1.20	2.11		2.13										0.34		0.54										1.61
Nov 2021	1.02	1.25	2.01		2.14										0.32		0.57										0.59
Dec 2021	1.24	1.19	1.57		2.27										0.19		0.59										
Jan 2022	1.41	1.21	1.56		2.31										0.16		0.63										
Feb 2022	1.44	1.25	1.53		2.38										0.17		0.58										
Mar 2022	1.51	1.34	1.56		2.40										0.17		0.53										
Apr 2022	1.49	1.33	1.55		2.33										0.16		0.51										
May 2022	1.58	1.41	1.48		2.26										0.17		0.56										
Jun 2022	1.77	1.54	1.50		2.06										0.21		0.62							0.02			
Jul 2022	1.89	1.50	1.50		2.16										0.25		0.54							0.02			
Aug 2022	2.08	1.73	1.51		2.45							0.10			0.20		0.41							0.01			
Sep 2022	2.26	1.74	1.49	0.02	2.45						0.01	0.09			0.21		0.52			0.01				0.02	0.02		
Oct 2022	2.35	1.81	1.61	0.07	2.51				0.03		0.02	0.10			0.18		0.50			0.01	0.01			0.02	0.04		
Nov 2022	2.37	2.03	1.62	0.15	2.43	0.01			0.04		0.03	0.10			0.18		0.50			0.01	0.01			0.02	0.05		
Dec 2022	2.32	1.81	1.61	0.03	2.05	0.04			0.05		0.02	0.05			0.18		0.49			0.01	0.01		0.01	0.02	0.05		
Jan 2023	2.35	1.88	1.61	0.20	2.15	0.11			0.07		0.06	0.10			0.18		0.54			0.01	0.01		0.01	0.02	0.06		
Feb 2023	2.29	1.92	1.62	0.21	2.30	0.11			0.07		0.07	0.10			0.19		0.49			0.01	0.01		0.01	0.02	0.06	0.03	
Mar 2023	2.25	2.03	1.53	0.21	2.22	0.11	0.04		0.08		0.07	0.11			0.18	0.04	0.45			0.01	0.01		0.01	0.02	0.06		
Apr 2023	2.26	2.00	1.67	0.21	2.20	0.15	0.06		0.09		0.07	0.11		0.08	0.17	0.05	0.45			0.01	0.01		0.01	0.01			
May 2023	2.27	2.04	1.67	0.24	2.28	0.15	0.09		0.09		0.08	0.11		0.07	0.19	0.05	0.45			0.01	0.01	0.01	0.01	0.01			
Jun 2023	2.39	2.23	1.64	0.26	1.86	0.15	0.10		0.09		0.07	0.12		0.08	0.19	0.05	0.51			0.01	0.01	0.01	0.01	0.01			
Jul 2023	2.38	2.52	1.53	0.27	1.17	0.14	0.14	0.01	0.08		0.07	0.11		0.06	0.18	0.06	0.55			0.01	0.01	0.01	0.01	0.01			
Aug 2023	2.72	2.76	1.58	0.36	1.23	0.15	0.16	0.03	0.11		0.08	0.12	0.04	0.07	0.17	0.07	0.53			0.01	0.01	0.02	0.01				
Sep 2023	2.49	2.47	1.39	0.37	1.10	0.15	0.13	0.05	0.10		0.10	0.12	0.05	0.07	0.16	0.06	0.58			0.01	0.01	0.02	0.01				
Oct 2023	2.29	2.28	1.37	0.39	1.11	0.16	0.12	0.08	0.10		0.10	0.12	0.05	0.08	0.16	0.06	0.50			0.01	0.02	0.03	0.01				
Nov 2023	2.25	2.33	1.45	0.47	1.14	0.16	0.12	0.11	0.13		0.11	0.12	0.06	0.10	0.17	0.06	0.33			0.01	0.01	0.03					
Dec 2023	2.20	2.19	1.53	0.54	1.12	0.16	0.12	0.12	0.11		0.11	0.12	0.06	0.09	0.16	0.06	0.33			0.01	0.01	0.03					
Jan 2024	2.37	2.21	1.55	0.65	1.17	0.16	0.11	0.15	0.13		0.12	0.14	0.08	0.10	0.17	0.06	0.25		0.01	0.01	0.01	0.01					
Feb 2024	2.38	2.22	1.52	0.69	1.21	0.17	0.12	0.22	0.16		0.13	0.13	0.09	0.11	0.17	0.06	0.22		0.01	0.01	0.01						
Mar 2024	2.53	2.19	1.54	0.69	1.14	0.16	0.12	0.25	0.14		0.14	0.12	0.09	0.10	0.16	0.06	0.22		0.01	0.01	0.01						
Apr 2024	2.53	2.16	1.51	0.73	1.24	0.17	0.34	0.27	0.18		0.15	0.13	0.07	0.11	0.15	0.07	0.19	0.01	0.01	0.01	0.01						
May 2024	2.75	2.24	1.50	0.83	1.20	0.16	0.36	0.30	0.18		0.15	0.14	0.06	0.11	0.15	0.07	0.09	0.01	0.01	0.01	0.01						
Jun 2024	2.88	2.34	1.52	0.91	0.71	0.15	0.37	0.32	0.20	0.03	0.16	0.16	0.07	0.11	0.15	0.07	0.10	0.01	0.01	0.01	0.01						
Jul 2024	2.83	2.45	1.65	1.01	0.71	0.15	0.43	0.34	0.20	0.06	0.18	0.17	0.09	0.12	0.15	0.07	0.09	0.01	0.01	0.01	0.01						
Aug 2024	2.96	2.48	1.70	1.11	0.81	0.35	0.45	0.35	0.19	0.12	0.18	0.18	0.11	0.12	0.14	0.08	0.08	0.01	0.01	0.01	0.01						
Sep 2024	3.13	2.26	1.44	1.18	0.72	0.42	0.44	0.35	0.24	0.12	0.18	0.18	0.13	0.13	0.15	0.08	0.07	0.01	0.01	0.01	0.01						
Oct 2024	3.23	2.35	1.53	1.23	0.66	0.39	0.43	0.40	0.27	0.17	0.19	0.18	0.14	0.12	0.14	0.09	0.09	0.01	0.01	0.01	0.01						
Nov 2024	3.21	2.31	1.52	1.27	0.63	0.41	0.43	0.44	0.29	0.19	0.21	0.17	0.14	0.12	0.11	0.08	0.10	0.01	0.01	0.01	0.01						
Dec 2024	3.06	2.13	1.40	1.29	0.62	0.54	0.43	0.45	0.29	0.24	0.21	0.18	0.15	0.12	0.09	0.08	0.09	0.01	0.01	0.01	0.01						
Jan 2025	2.92	1.73	1.36	1.31	0.66	0.54	0.46	0.41	0.34	0.27	0.21	0.19	0.16	0.13	0.12	0.08	0.04	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

### Overall

At least one tracker was found on 18.33% of new episodes in January, shrinking 2.32% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "43.96%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.43%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.93%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.18%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.26%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.21%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.18%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.32%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.27%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.03%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of January 2025.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 12.62% of new episodes in January, growing 1.93% from last month.

Of these, 11.56% had one other tracker, 8.08% had 2 other trackers, 1.43% had 3 other trackers, 1.37% had 5 other trackers, 1.18% had 4 other trackers, 0.43% had 6 other trackers, 0.11% had 8 other trackers, and 0.10% had 7 other trackers.

9.08% also included Podsights, 6.78% also included Chartable, 6.59% also included Adswizz, 6.03% also included Podscribe, 3.17% also included Podroll, 2.87% also included Podder, 2.33% also included Magellan AI, 2.03% also included Spotify, 1.50% also included Swap.fm, 1.30% also included Podcorn, 1.17% also included OP3, 1.10% also included Claritas, 0.94% also included ArtsAI, 0.75% also included Audiotakes, 0.68% also included Gumshoe, 0.65% also included Blubrry, 0.56% also included Veritonic, 0.07% also included CoHost Prefix, 0.04% also included Feedpress, 0.02% also included United Podcasters, 0.01% also included Médiamétrie, 0.01% also included Podkite, 0.01% also included AdBarker, and 0.01% also included Zencastr.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "63.74%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "9.76%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.47%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.30%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.18%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.09%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.49%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.91%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.60%" >}}
10. {{< a "https://portal.rozhlas.cz/" "Cesky rozhlas" >}} {{< span "weak" "0.55%" >}}
---

### 2. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.92% of new episodes in January, shrinking 2.99% from last month.

Of these, 17.22% had 2 other trackers, 12.18% had one other tracker, 1.78% had 5 other trackers, 1.61% had 3 other trackers, 1.23% had 4 other trackers, 0.51% had 6 other trackers, and 0.33% had 7 other trackers.

28.47% also included Podtrac, 12.45% also included Podroll, 6.56% also included Podscribe, 4.07% also included Podsights, 4.01% also included Magellan AI, 2.70% also included Swap.fm, 2.64% also included Claritas, 2.44% also included Spotify, 1.58% also included ArtsAI, 1.21% also included Blubrry, 1.11% also included Podder, 1.09% also included Audiotakes, 0.82% also included Veritonic, 0.66% also included Chartable, 0.54% also included OP3, 0.23% also included Podcorn, 0.03% also included Gumshoe, and 0.02% also included United Podcasters.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "64.72%" >}}
2. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "5.90%" >}}
3. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "5.27%" >}}
4. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "4.84%" >}}
5. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "4.11%" >}}
6. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "2.82%" >}}
7. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "2.00%" >}}
8. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.98%" >}}
9. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.62%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.36%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 2.70% of new episodes in January, shrinking 25.87% from last month.

Of these, 58.39% also included Podtrac, 27.14% also included Podscribe, 14.06% also included Magellan AI, 7.47% also included Adswizz, 6.94% also included Claritas, 6.14% also included Swap.fm, 5.66% also included ArtsAI, 5.44% also included Podder, 4.61% also included Audiotakes, 3.56% also included Gumshoe, 3.51% also included Podcorn, 3.13% also included OP3, 2.97% also included Veritonic, 2.43% also included Podroll, 0.38% also included Blubrry, 0.27% also included CoHost Prefix, 0.26% also included United Podcasters, 0.06% also included Feedpress, 0.04% also included Zencastr, 0.04% also included Firstory, 0.03% also included Podkite, and 0.01% also included AdBarker.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "58.24%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "13.08%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.94%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.84%" >}}
5. {{< a "https://www.rti.org.tw/" "Radio Taiwan International" >}} {{< span "weak" "2.43%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.00%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.83%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.48%" >}}
9. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.28%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.16%" >}}
---

### 3. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 1.73% of new episodes in January, shrinking 17.68% from last month.

Of these, 30.31% had one other tracker, 24.68% had 2 other trackers, 11.25% had 3 other trackers, 10.50% had 4 other trackers, 8.81% had 5 other trackers, 3.46% had 6 other trackers, 0.79% had 8 other trackers, and 0.39% had 7 other trackers.

66.24% also included Podtrac, 45.75% also included Chartable, 32.14% also included Podscribe, 17.09% also included Magellan AI, 8.03% also included Swap.fm, 7.39% also included ArtsAI, 7.29% also included Claritas, 6.88% also included Adswizz, 6.88% also included Podder, 5.40% also included Audiotakes, 4.86% also included Podcorn, 4.74% also included Gumshoe, 4.51% also included OP3, 3.90% also included Spotify, 3.80% also included Veritonic, 3.19% also included Podroll, 0.38% also included CoHost Prefix, 0.34% also included Blubrry, 0.32% also included United Podcasters, 0.09% also included Feedpress, 0.05% also included Zencastr, and 0.04% also included Podkite.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "63.12%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "16.16%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.43%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.13%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.35%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.76%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.65%" >}}
8. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.63%" >}}
9. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.25%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.95%" >}}
---

### 4. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 1.54% of new episodes in January, shrinking 32.08% from last month.

Of these, 31.90% had 2 other trackers, 24.94% had one other tracker, 7.66% had 3 other trackers, 6.58% had 4 other trackers, 3.38% had 5 other trackers, 2.41% had 6 other trackers, 0.85% had 8 other trackers, and 0.20% had 7 other trackers.

55.40% also included Podtrac, 51.25% also included Podsights, 18.58% also included Podscribe, 10.61% also included Magellan AI, 10.51% also included Spotify, 8.39% also included Swap.fm, 5.29% also included Podder, 4.34% also included Claritas, 2.62% also included Veritonic, 2.44% also included Podroll, 2.26% also included ArtsAI, 1.24% also included Adswizz, 1.23% also included Audiotakes, 0.86% also included Podcorn, 0.75% also included Gumshoe, 0.70% also included OP3, 0.43% also included CoHost Prefix, 0.24% also included Blubrry, 0.21% also included United Podcasters, 0.11% also included Feedpress, 0.07% also included Firstory, 0.06% also included Zencastr, 0.02% also included AdBarker, and 0.01% also included Podkite.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "81.86%" >}}
2. {{< a "https://www.rti.org.tw/" "Radio Taiwan International" >}} {{< span "weak" "4.26%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.51%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.58%" >}}
5. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.49%" >}}
6. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "0.35%" >}}
7. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.31%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.29%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "0.26%" >}}
10. {{< a "https://podcastai.com/" "PodcastAI" >}} {{< span "weak" "0.26%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.36% of new episodes in January, shrinking 1.17% from last month.

Of these, 9.95% had one other tracker, 0.44% had 2 other trackers, 0.29% had 3 other trackers, 0.07% had 4 other trackers, 0.04% had 5 other trackers, and 0.03% had 6 other trackers.

6.03% also included Podtrac, 2.60% also included Adswizz, 1.13% also included Feedpress, 0.78% also included OP3, 0.43% also included Podsights, 0.28% also included Podscribe, 0.28% also included Swap.fm, 0.27% also included Chartable, 0.25% also included Podder, 0.15% also included Podcorn, 0.10% also included Magellan AI, 0.08% also included Spotify, 0.01% also included Audiotakes, 0.01% also included ArtsAI, 0.01% also included Veritonic, <0.01% also included Podroll, and <0.01% also included Claritas.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "43.98%" >}}
2. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "5.10%" >}}
3. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "5.07%" >}}
4. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.23%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.66%" >}}
6. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "2.31%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.85%" >}}
8. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.34%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.01%" >}}
10. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.80%" >}}
---

### 6. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 1.31% of new episodes in January, growing 2.81% from last month.

Of these, 24.13% had one other tracker, 15.11% had 4 other trackers, 14.95% had 2 other trackers, 14.71% had 5 other trackers, 10.58% had 3 other trackers, 4.77% had 6 other trackers, 1.04% had 8 other trackers, and 0.97% had 7 other trackers.

58.13% also included Podtrac, 42.46% also included Podsights, 28.74% also included Magellan AI, 21.91% also included Chartable, 15.41% also included Claritas, 15.28% also included Spotify, 14.64% also included Adswizz, 12.61% also included ArtsAI, 11.66% also included Audiotakes, 10.05% also included Podder, 6.57% also included Podcorn, 6.13% also included Swap.fm, 6.10% also included Gumshoe, 5.16% also included OP3, 4.87% also included Veritonic, 2.54% also included Podroll, 0.49% also included CoHost Prefix, 0.38% also included United Podcasters, 0.29% also included Blubrry, 0.05% also included AdBarker, 0.05% also included Zencastr, and 0.02% also included Podkite.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "48.85%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.82%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "10.72%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.70%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "4.51%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.51%" >}}
7. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "4.43%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.69%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.46%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.50%" >}}
---

### 7. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.66% of new episodes in January, growing 4.22% from last month.

Of these, 11.69% had one other tracker, 7.90% had 5 other trackers, 4.74% had 2 other trackers, 2.66% had 4 other trackers, 2.10% had 3 other trackers, 0.26% had 6 other trackers, 0.12% had 8 other trackers, and 0.11% had 7 other trackers.

24.68% also included Podtrac, 12.96% also included Podscribe, 12.67% also included Podsights, 11.17% also included OP3, 9.80% also included Gumshoe, 2.22% also included Podroll, 2.00% also included Chartable, 1.79% also included Podder, 1.03% also included Adswizz, 0.67% also included Spotify, 0.34% also included Swap.fm, 0.33% also included Magellan AI, 0.33% also included Zencastr, 0.31% also included Blubrry, 0.20% also included Feedpress, 0.13% also included United Podcasters, 0.10% also included AdBarker, 0.08% also included CoHost Prefix, 0.07% also included Podkite, and 0.03% also included Audiotakes.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "24.68%" >}}
2. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "12.63%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "12.42%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "11.89%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "7.64%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.28%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "6.98%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.91%" >}}
9. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "2.17%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.11%" >}}
---

### 8. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.58% of new episodes in January, growing 15.79% from last month.

Of these, 20.74% had 4 other trackers, 18.75% had 5 other trackers, 14.79% had 3 other trackers, 8.80% had 6 other trackers, 8.08% had one other tracker, 7.46% had 2 other trackers, 2.21% had 8 other trackers, and 1.97% had 7 other trackers.

64.87% also included Podscribe, 50.97% also included Podsights, 50.60% also included Podtrac, 29.17% also included Claritas, 28.25% also included Chartable, 20.63% also included Spotify, 20.16% also included Adswizz, 16.95% also included ArtsAI, 13.60% also included Audiotakes, 9.21% also included Podder, 9.03% also included Swap.fm, 8.94% also included Veritonic, 2.30% also included Podroll, 1.72% also included Gumshoe, 0.92% also included OP3, 0.37% also included Podcorn, 0.31% also included United Podcasters, 0.23% also included Blubrry, and 0.14% also included CoHost Prefix.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "39.58%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "15.68%" >}}
3. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "11.84%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.68%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.82%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.73%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.94%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "3.61%" >}}
9. {{< a "https://www.americanpublicmedia.org/" "American Public Media" >}} {{< span "weak" "2.44%" >}}
10. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.48%" >}}
---

### 9. [Podder](https://www.podderapp.com/)

Podder was found on 0.54% of new episodes in January, growing 0.15% from last month.

Of these, 45.48% had one other tracker, 10.66% had 2 other trackers, 9.22% had 4 other trackers, 7.02% had 5 other trackers, 4.71% had 3 other trackers, 2.56% had 6 other trackers, 0.13% had 7 other trackers, and 0.10% had 8 other trackers.

67.35% also included Podtrac, 24.44% also included Podscribe, 22.10% also included Podsights, 15.19% also included Chartable, 9.93% also included Magellan AI, 8.80% also included Audiotakes, 6.02% also included Adswizz, 4.14% also included ArtsAI, 3.10% also included Spotify, 2.21% also included Podcorn, 1.86% also included Claritas, 1.09% also included Gumshoe, 1.07% also included OP3, 0.84% also included Podroll, 0.63% also included Blubrry, 0.42% also included Swap.fm, 0.39% also included Veritonic, 0.26% also included CoHost Prefix, 0.10% also included United Podcasters, and 0.09% also included Podkite.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "44.70%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "22.82%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "18.00%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.26%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.82%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.32%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.31%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "1.27%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.95%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.37%" >}}
---

### 10. [Podroll](https://podroll.fm/)

Podroll was found on 0.46% of new episodes in January, growing 9.42% from last month.

Of these, 79.13% had 2 other trackers, 7.94% had one other tracker, 3.87% had 3 other trackers, 2.60% had 4 other trackers, 2.11% had 6 other trackers, 1.55% had 5 other trackers, 0.21% had 7 other trackers, and 0.17% had 8 other trackers.

86.82% also included Podtrac, 78.92% also included Adswizz, 11.98% also included Podsights, 8.19% also included Chartable, 7.22% also included Podscribe, 4.11% also included Swap.fm, 3.19% also included Podcorn, 2.90% also included Magellan AI, 1.95% also included Claritas, 1.38% also included ArtsAI, 0.98% also included Podder, 0.98% also included OP3, 0.91% also included Gumshoe, 0.46% also included Spotify, 0.44% also included Audiotakes, 0.41% also included Veritonic, 0.37% also included CoHost Prefix, 0.26% also included United Podcasters, and 0.01% also included Blubrry.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "78.52%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.18%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.37%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.84%" >}}
5. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "1.64%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.03%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.81%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.53%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.39%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.29%" >}}
---

### 11. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.41% of new episodes in January, shrinking 7.36% from last month.

Of these, 37.81% had 2 other trackers, 13.65% had 5 other trackers, 9.50% had one other tracker, 7.47% had 4 other trackers, 6.85% had 3 other trackers, 4.28% had 6 other trackers, 3.18% had 8 other trackers, and 2.43% had 7 other trackers.

62.06% also included Podtrac, 48.60% also included Podscribe, 39.43% also included Chartable, 29.07% also included Magellan AI, 20.81% also included Claritas, 17.32% also included Adswizz, 16.38% also included Podsights, 12.11% also included ArtsAI, 8.86% also included Audiotakes, 6.19% also included Veritonic, 4.05% also included Podder, 3.03% also included Gumshoe, 1.18% also included OP3, 1.09% also included Podcorn, 0.75% also included Swap.fm, 0.51% also included Podroll, 0.27% also included Blubrry, and 0.13% also included United Podcasters.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "44.72%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.81%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "16.38%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "5.70%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.88%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "3.50%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.29%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.32%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.32%" >}}
10. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "0.75%" >}}
---

### 12. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.34% of new episodes in January, growing 17.08% from last month.

Of these, 23.90% had one other tracker, 16.26% had 5 other trackers, 6.74% had 2 other trackers, 3.99% had 4 other trackers, 3.28% had 3 other trackers, 0.41% had 6 other trackers, 0.21% had 7 other trackers, and 0.16% had 8 other trackers.

43.55% also included Podtrac, 22.98% also included Podsights, 21.86% also included Podcorn, 20.58% also included Gumshoe, 19.94% also included Podscribe, 4.63% also included Adswizz, 3.18% also included Chartable, 3.12% also included Blubrry, 1.71% also included Podder, 1.57% also included Magellan AI, 1.43% also included Spotify, 1.34% also included Podroll, 1.16% also included Swap.fm, 0.72% also included ArtsAI, 0.54% also included Audiotakes, 0.48% also included Podkite, 0.41% also included Claritas, 0.17% also included United Podcasters, 0.16% also included CoHost Prefix, and 0.12% also included Feedpress.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "29.32%" >}}
2. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "9.73%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "6.18%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.52%" >}}
5. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "4.75%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.93%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.84%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.79%" >}}
9. {{< a "https://radiolaser.fr/" "Radio Laser" >}} {{< span "weak" "2.19%" >}}
10. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "1.61%" >}}
---

### 13. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.27% of new episodes in January, growing 14.88% from last month.

Of these, 31.43% had 2 other trackers, 19.98% had 3 other trackers, 17.75% had one other tracker, 16.91% had 4 other trackers, 7.14% had 5 other trackers, 3.35% had 6 other trackers, 0.62% had 7 other trackers, and 0.10% had 8 other trackers.

69.09% also included Podtrac, 50.62% also included Podsights, 47.22% also included Chartable, 29.28% also included Podscribe, 28.77% also included Adswizz, 19.09% also included Magellan AI, 6.90% also included Podroll, 4.38% also included ArtsAI, 4.05% also included Claritas, 1.44% also included OP3, 1.39% also included Blubrry, 1.37% also included Gumshoe, 1.13% also included Spotify, 1.13% also included Veritonic, 0.81% also included Podcorn, 0.81% also included Podder, 0.67% also included Audiotakes, 0.48% also included United Podcasters, 0.29% also included CoHost Prefix, and 0.24% also included Zencastr.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "55.22%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "28.58%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.86%" >}}
4. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "4.22%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.76%" >}}
6. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.53%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.43%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.22%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.12%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.07%" >}}
---

### 14. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.21% of new episodes in January, growing 2.83% from last month.

Of these, 33.74% had 5 other trackers, 21.70% had 4 other trackers, 19.61% had 6 other trackers, 6.67% had 2 other trackers, 6.24% had 3 other trackers, 5.99% had 8 other trackers, 2.98% had 7 other trackers, and 2.30% had one other tracker.

94.38% also included Podscribe, 79.13% also included Magellan AI, 65.12% also included Podtrac, 59.00% also included Podsights, 40.07% also included Spotify, 36.08% also included Adswizz, 33.62% also included ArtsAI, 31.38% also included Chartable, 20.96% also included Veritonic, 5.19% also included Swap.fm, 4.67% also included Podder, 4.21% also included Podroll, 1.14% also included Gumshoe, 0.65% also included OP3, 0.46% also included CoHost Prefix, 0.22% also included Audiotakes, and 0.03% also included Blubrry.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "40.14%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "29.75%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.83%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.85%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.15%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "6.08%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.28%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.22%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.18%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.18%" >}}
---

### 15. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.19% of new episodes in January, growing 6.25% from last month.

Of these, 27.24% had 5 other trackers, 22.27% had 4 other trackers, 14.18% had 2 other trackers, 12.88% had 6 other trackers, 7.34% had 3 other trackers, 6.88% had 8 other trackers, 6.07% had 7 other trackers, and 3.00% had one other tracker.

88.67% also included Podscribe, 68.63% also included Podsights, 63.76% also included Podtrac, 52.79% also included Magellan AI, 38.60% also included Claritas, 26.78% also included Spotify, 26.29% also included Audiotakes, 24.81% also included Adswizz, 21.07% also included Veritonic, 18.77% also included Chartable, 11.96% also included Podder, 6.46% also included Swap.fm, 3.42% also included Podroll, 1.31% also included OP3, 0.07% also included Blubrry, and 0.07% also included Gumshoe.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "32.96%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "16.37%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "15.38%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "12.35%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "11.82%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "7.94%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.47%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.32%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.18%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.14%" >}}
---

### 16. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.16% of new episodes in January, growing 6.41% from last month.

Of these, 39.35% had 4 other trackers, 20.11% had 3 other trackers, 19.49% had 5 other trackers, 9.52% had 2 other trackers, 7.88% had 6 other trackers, 0.94% had one other tracker, and 0.90% had 7 other trackers.

95.36% also included Podscribe, 58.97% also included Podtrac, 58.31% also included Podsights, 49.28% also included Magellan AI, 30.57% also included ArtsAI, 29.59% also included Podder, 22.77% also included Spotify, 19.90% also included Adswizz, 11.90% also included Chartable, 4.92% also included Veritonic, 2.09% also included Gumshoe, 1.27% also included Podroll, 1.15% also included Swap.fm, 1.15% also included OP3, 1.03% also included United Podcasters, 0.29% also included Claritas, 0.12% also included Podcorn, and 0.08% also included Blubrry.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "32.13%" >}}
2. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "27.70%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "18.71%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "9.77%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.16%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.09%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.56%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.40%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.16%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.16%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.13% of new episodes in January, growing 10.64% from last month.

Of these, 41.39% had 5 other trackers, 13.93% had one other tracker, 13.78% had 4 other trackers, 9.25% had 2 other trackers, 7.46% had 3 other trackers, 2.24% had 6 other trackers, 0.45% had 7 other trackers, and 0.40% had 8 other trackers.

65.42% also included Podtrac, 62.04% also included Podsights, 60.45% also included Podscribe, 52.84% also included OP3, 49.25% also included Podcorn, 9.45% also included Spotify, 8.81% also included Chartable, 7.56% also included Magellan AI, 4.43% also included Podder, 3.18% also included Podroll, 2.94% also included CoHost Prefix, 2.84% also included Swap.fm, 2.54% also included Audiotakes, 1.84% also included Claritas, 1.64% also included Veritonic, 0.75% also included Adswizz, 0.60% also included United Podcasters, and 0.10% also included ArtsAI.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "53.68%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "20.15%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "17.86%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.23%" >}}
5. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.79%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.04%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.30%" >}}
8. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.30%" >}}
9. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.20%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.20%" >}}
---

### 18. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.12% of new episodes in January, growing 30.48% from last month.

Of these, 17.85% had one other tracker, and 1.35% had 2 other trackers.

12.57% also included Blubrry, 3.88% also included Podtrac, 1.35% also included Podsights, 1.35% also included Chartable, 1.08% also included Podcorn, and 0.32% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "60.84%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.66%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.72%" >}}
4. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "4.91%" >}}
5. {{< a "https://podcasters.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "2.91%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.43%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.89%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.83%" >}}
9. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.62%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.19%" >}}
---

### 19. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.08% of new episodes in January, growing 4.09% from last month.

Of these, 29.22% had 6 other trackers, 15.61% had 8 other trackers, 15.21% had 5 other trackers, 14.73% had 3 other trackers, 12.89% had 7 other trackers, 7.93% had 2 other trackers, and 3.52% had 4 other trackers.

86.79% also included Podtrac, 79.98% also included Podsights, 77.66% also included Podscribe, 63.17% also included Magellan AI, 54.60% also included Claritas, 49.32% also included Chartable, 47.80% also included ArtsAI, 31.06% also included Spotify, 29.22% also included Adswizz, 9.61% also included Audiotakes, 3.76% also included Swap.fm, 2.64% also included Gumshoe, 2.56% also included Podder, 2.32% also included Podroll, and 0.16% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "61.49%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "23.78%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "4.80%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.52%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.24%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.24%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.12%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.32%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.32%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.16%" >}}
---

### 20. [Firstory](https://firstory.me/)

Firstory was found on 0.05% of new episodes in January, shrinking 21.49% from last month.

Of these, 2.26% had one other tracker.

2.26% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.58%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.42%" >}}
---

### 21. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.04% of new episodes in January, shrinking 51.73% from last month.

Of these, 3.55% had one other tracker.

3.55% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "43.34%" >}}
2. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "36.83%" >}}
3. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "17.16%" >}}
---

### 22. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.01% of new episodes in January, shrinking 4.89% from last month.

Of these, 26.15% had one other tracker, 24.10% had 5 other trackers, 19.49% had 4 other trackers, 6.15% had 6 other trackers, 5.64% had 2 other trackers, 4.10% had 8 other trackers, and 1.03% had 3 other trackers.

73.33% also included Podtrac, 51.79% also included Chartable, 51.28% also included Podsights, 49.74% also included Podscribe, 30.26% also included Gumshoe, 13.33% also included Podroll, 10.77% also included Podder, 7.69% also included Claritas, 6.15% also included Swap.fm, 6.15% also included Magellan AI, 4.10% also included OP3, and 4.10% also included Podcorn.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "53.85%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "13.33%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "7.69%" >}}
4. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "7.18%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "6.15%" >}}
6. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.56%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "2.05%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.05%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.54%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "0.51%" >}}
---

### 23. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in January, growing 12.94% from last month.

Of these, 21.48% had one other tracker, 21.48% had 2 other trackers, 20.13% had 4 other trackers, 14.09% had 3 other trackers, 4.03% had 6 other trackers, 3.36% had 5 other trackers, 3.36% had 7 other trackers, and 2.68% had 8 other trackers.

57.05% also included Podsights, 50.34% also included Podscribe, 32.89% also included Chartable, 30.87% also included Podtrac, 18.12% also included Magellan AI, 16.78% also included Audiotakes, 13.42% also included Swap.fm, 12.08% also included Podroll, 8.72% also included Podcorn, 8.05% also included Gumshoe, 6.04% also included OP3, 5.37% also included Spotify, 5.37% also included Podder, 4.70% also included Adswizz, and 3.36% also included Zencastr.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "46.31%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "16.78%" >}}
3. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "11.41%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.72%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.37%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.70%" >}}
7. {{< a "https://podcasters.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "3.36%" >}}
8. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "2.68%" >}}
9. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "0.67%" >}}
---

### 24. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in January, growing 16.81% from last month.

Of these, 26.19% had one other tracker, 5.56% had 2 other trackers, 3.17% had 4 other trackers, and 2.38% had 5 other trackers.

19.84% also included OP3, 17.46% also included Podtrac, 7.94% also included Podsights, 5.56% also included Podcorn, 5.56% also included Podder, 3.17% also included Podscribe, and 2.38% also included Chartable.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "29.37%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "19.84%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "15.87%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "13.49%" >}}
5. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.56%" >}}
6. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "4.76%" >}}
7. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "3.97%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.97%" >}}
9. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "1.59%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.79%" >}}
---

### 25. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in January, growing 1.98% from last month.

Of these, 27.50% had one other tracker, 4.17% had 6 other trackers, 4.17% had 7 other trackers, and 2.50% had 2 other trackers.

27.50% also included Podcorn, 15.83% also included Podtrac, 11.67% also included Chartable, 10.83% also included Podsights, 8.33% also included Podscribe, 8.33% also included Swap.fm, and 4.17% also included United Podcasters.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "31.67%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "21.67%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "13.33%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "12.50%" >}}
5. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "7.50%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.50%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.00%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.83%" >}}
---

### 26. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in January, growing 40.22% from last month.

Of these, 21.33% had one other tracker, and 13.33% had 3 other trackers.

29.33% also included Podtrac, 13.33% also included Podscribe, 13.33% also included Podcorn, and 5.33% also included Chartable.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "48.00%" >}}
2. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "14.67%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "12.00%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "10.67%" >}}
5. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "6.67%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.33%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.67%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
