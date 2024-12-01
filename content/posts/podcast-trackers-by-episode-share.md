---
title: "Top Podcast Tracking Services by Episode Share (November 2024)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2024-11.png
date: 2024-12-01T13:15:00-06:00
lastmod: 2024-12-01T13:15:00-06:00
draft: false
rssrevision: 2024-11
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.8 million in November 2024), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in November, how many
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

{{< details "_September 2023: Spotify for Podcasters data_" >}}
_Starting mid-September, we gained a better signal of when Spotify for Podcasters (formerly Anchor) podcasts release new episodes, so our crawlers are finding more.
Higher share of new episodes on S4P (which typically do not have prefixes) will have led to lower share overall._
{{< /details >}}

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Chartable	Adswizz	Podsights	Blubrry	Podscribe	Podcorn	Spotify	Podroll	Podder	OP3	Claritas	Swap.fm	ArtsAI	Audiotakes	Gumshoe	Feedpress	Médiamétrie	Veritonic	CoHost Prefix	United Podcasters	Podkite	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.00	1.16	2.07		2.09										0.32	0.42											1.61
Oct 2021	4.05	4.09	1.01	1.20	2.11		2.13										0.34	0.54											1.61
Nov 2021	4.07	4.30	1.02	1.25	2.01		2.14										0.32	0.57											0.59
Dec 2021	4.06	4.42	1.24	1.19	1.57		2.27										0.19	0.59											
Jan 2022	4.11	4.45	1.41	1.21	1.56		2.31										0.16	0.63											
Feb 2022	4.15	4.48	1.44	1.25	1.53		2.38										0.17	0.58											
Mar 2022	4.37	4.72	1.51	1.34	1.56		2.40										0.17	0.53											
Apr 2022	4.44	4.71	1.49	1.33	1.55		2.33										0.16	0.51											
May 2022	4.49	4.87	1.58	1.41	1.48		2.26										0.17	0.56											
Jun 2022	4.75	5.10	1.77	1.54	1.50		2.06										0.21	0.62								0.02			
Jul 2022	4.70	5.10	1.89	1.50	1.50		2.16										0.25	0.54								0.02			
Aug 2022	4.83	5.26	2.08	1.73	1.51		2.45							0.10			0.20	0.41								0.01			
Sep 2022	7.53	5.40	2.26	1.74	1.49	0.02	2.45					0.01		0.09			0.21	0.52				0.01				0.02	0.02		
Oct 2022	8.24	5.48	2.35	1.81	1.61	0.07	2.51				0.03	0.02		0.10			0.18	0.50				0.01	0.01			0.02	0.04		
Nov 2022	8.11	5.62	2.37	2.03	1.62	0.15	2.43			0.01	0.04	0.03		0.10			0.18	0.50				0.01	0.01			0.02	0.05		
Dec 2022	8.01	5.54	2.32	1.81	1.61	0.03	2.05			0.04	0.05	0.02		0.05			0.18	0.49				0.01	0.01		0.01	0.02	0.05		
Jan 2023	7.85	5.56	2.35	1.88	1.61	0.20	2.15			0.11	0.07	0.06		0.10			0.18	0.54				0.01	0.01		0.01	0.02	0.06		
Feb 2023	7.58	5.51	2.29	1.92	1.62	0.21	2.30			0.11	0.07	0.07		0.10			0.19	0.49				0.01	0.01		0.01	0.02	0.06	0.03	
Mar 2023	7.79	5.53	2.25	2.03	1.53	0.21	2.22		0.04	0.11	0.08	0.07		0.11			0.18	0.45	0.04			0.01	0.01		0.01	0.02	0.06		
Apr 2023	7.66	5.43	2.26	2.00	1.67	0.21	2.20		0.06	0.15	0.09	0.07		0.11		0.08	0.17	0.45	0.05			0.01	0.01		0.01	0.01			
May 2023	7.58	5.59	2.27	2.04	1.67	0.24	2.28		0.09	0.15	0.09	0.08		0.11		0.07	0.19	0.45	0.05			0.01	0.01	0.01	0.01	0.01			
Jun 2023	8.22	5.83	2.39	2.23	1.64	0.26	1.86		0.10	0.15	0.09	0.07		0.12		0.08	0.19	0.51	0.05			0.01	0.01	0.01	0.01	0.01			
Jul 2023	8.60	5.95	2.38	2.52	1.53	0.27	1.17	0.01	0.14	0.14	0.08	0.07		0.11		0.06	0.18	0.55	0.06			0.01	0.01	0.01	0.01	0.01			
Aug 2023	9.19	6.43	2.72	2.76	1.58	0.36	1.23	0.03	0.16	0.15	0.11	0.08		0.12	0.04	0.07	0.17	0.53	0.07			0.01	0.01	0.02	0.01				
Sep 2023	8.46	5.77	2.49	2.47	1.39	0.37	1.10	0.05	0.13	0.15	0.10	0.10		0.12	0.05	0.07	0.16	0.58	0.06			0.01	0.01	0.02	0.01				
Oct 2023	7.90	5.54	2.29	2.28	1.37	0.39	1.11	0.08	0.12	0.16	0.10	0.10		0.12	0.05	0.08	0.16	0.50	0.06			0.01	0.02	0.03	0.01				
Nov 2023	7.65	5.59	2.25	2.33	1.45	0.47	1.14	0.11	0.12	0.16	0.13	0.11		0.12	0.06	0.10	0.17	0.33	0.06			0.01	0.01	0.03					
Dec 2023	7.48	5.60	2.20	2.19	1.53	0.54	1.12	0.12	0.12	0.16	0.11	0.11		0.12	0.06	0.09	0.16	0.33	0.06			0.01	0.01	0.03					
Jan 2024	7.64	5.61	2.37	2.21	1.55	0.65	1.17	0.15	0.11	0.16	0.13	0.12		0.14	0.08	0.10	0.17	0.25	0.06		0.01	0.01	0.01	0.01					
Feb 2024	7.69	5.58	2.38	2.22	1.52	0.69	1.21	0.22	0.12	0.17	0.16	0.13		0.13	0.09	0.11	0.17	0.22	0.06		0.01	0.01	0.01						
Mar 2024	9.01	5.46	2.53	2.19	1.54	0.69	1.14	0.25	0.12	0.16	0.14	0.14		0.12	0.09	0.10	0.16	0.22	0.06		0.01	0.01	0.01						
Apr 2024	10.78	5.47	2.53	2.16	1.51	0.73	1.24	0.27	0.34	0.17	0.18	0.15		0.13	0.07	0.11	0.15	0.19	0.07	0.01	0.01	0.01	0.01						
May 2024	11.59	5.63	2.75	2.24	1.50	0.83	1.20	0.30	0.36	0.16	0.18	0.15		0.14	0.06	0.11	0.15	0.09	0.07	0.01	0.01	0.01	0.01						
Jun 2024	11.54	6.06	2.88	2.34	1.52	0.91	0.71	0.32	0.37	0.15	0.20	0.16	0.03	0.16	0.07	0.11	0.15	0.10	0.07	0.01	0.01	0.01	0.01						
Jul 2024	12.34	6.80	2.83	2.45	1.65	1.01	0.71	0.34	0.43	0.15	0.20	0.18	0.06	0.17	0.09	0.12	0.15	0.09	0.07	0.01	0.01	0.01	0.01						
Aug 2024	14.22	6.72	2.96	2.48	1.70	1.11	0.81	0.35	0.45	0.35	0.19	0.18	0.12	0.18	0.11	0.12	0.14	0.08	0.08	0.01	0.01	0.01	0.01						
Sep 2024	12.95	5.99	3.13	2.26	1.44	1.18	0.72	0.35	0.44	0.42	0.24	0.18	0.12	0.18	0.13	0.13	0.15	0.07	0.08	0.01	0.01	0.01	0.01						
Oct 2024	12.24	5.49	3.23	2.35	1.53	1.23	0.66	0.40	0.43	0.39	0.27	0.19	0.17	0.18	0.14	0.12	0.14	0.09	0.09	0.01	0.01	0.01	0.01						
Nov 2024	11.86	4.66	3.21	2.31	1.52	1.27	0.63	0.44	0.43	0.41	0.29	0.21	0.19	0.17	0.14	0.12	0.11	0.10	0.08	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} are the clear top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podsights	Blubrry	Podscribe	Podcorn	Spotify	Podroll	Podder	OP3	Claritas	Swap.fm	ArtsAI	Audiotakes	Gumshoe	Feedpress	Médiamétrie	Veritonic	CoHost Prefix	United Podcasters	Podkite	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
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
Sep 2022	2.26	1.74	1.49	0.02	2.45					0.01		0.09			0.21	0.52				0.01				0.02	0.02		
Oct 2022	2.35	1.81	1.61	0.07	2.51				0.03	0.02		0.10			0.18	0.50				0.01	0.01			0.02	0.04		
Nov 2022	2.37	2.03	1.62	0.15	2.43			0.01	0.04	0.03		0.10			0.18	0.50				0.01	0.01			0.02	0.05		
Dec 2022	2.32	1.81	1.61	0.03	2.05			0.04	0.05	0.02		0.05			0.18	0.49				0.01	0.01		0.01	0.02	0.05		
Jan 2023	2.35	1.88	1.61	0.20	2.15			0.11	0.07	0.06		0.10			0.18	0.54				0.01	0.01		0.01	0.02	0.06		
Feb 2023	2.29	1.92	1.62	0.21	2.30			0.11	0.07	0.07		0.10			0.19	0.49				0.01	0.01		0.01	0.02	0.06	0.03	
Mar 2023	2.25	2.03	1.53	0.21	2.22		0.04	0.11	0.08	0.07		0.11			0.18	0.45	0.04			0.01	0.01		0.01	0.02	0.06		
Apr 2023	2.26	2.00	1.67	0.21	2.20		0.06	0.15	0.09	0.07		0.11		0.08	0.17	0.45	0.05			0.01	0.01		0.01	0.01			
May 2023	2.27	2.04	1.67	0.24	2.28		0.09	0.15	0.09	0.08		0.11		0.07	0.19	0.45	0.05			0.01	0.01	0.01	0.01	0.01			
Jun 2023	2.39	2.23	1.64	0.26	1.86		0.10	0.15	0.09	0.07		0.12		0.08	0.19	0.51	0.05			0.01	0.01	0.01	0.01	0.01			
Jul 2023	2.38	2.52	1.53	0.27	1.17	0.01	0.14	0.14	0.08	0.07		0.11		0.06	0.18	0.55	0.06			0.01	0.01	0.01	0.01	0.01			
Aug 2023	2.72	2.76	1.58	0.36	1.23	0.03	0.16	0.15	0.11	0.08		0.12	0.04	0.07	0.17	0.53	0.07			0.01	0.01	0.02	0.01				
Sep 2023	2.49	2.47	1.39	0.37	1.10	0.05	0.13	0.15	0.10	0.10		0.12	0.05	0.07	0.16	0.58	0.06			0.01	0.01	0.02	0.01				
Oct 2023	2.29	2.28	1.37	0.39	1.11	0.08	0.12	0.16	0.10	0.10		0.12	0.05	0.08	0.16	0.50	0.06			0.01	0.02	0.03	0.01				
Nov 2023	2.25	2.33	1.45	0.47	1.14	0.11	0.12	0.16	0.13	0.11		0.12	0.06	0.10	0.17	0.33	0.06			0.01	0.01	0.03					
Dec 2023	2.20	2.19	1.53	0.54	1.12	0.12	0.12	0.16	0.11	0.11		0.12	0.06	0.09	0.16	0.33	0.06			0.01	0.01	0.03					
Jan 2024	2.37	2.21	1.55	0.65	1.17	0.15	0.11	0.16	0.13	0.12		0.14	0.08	0.10	0.17	0.25	0.06		0.01	0.01	0.01	0.01					
Feb 2024	2.38	2.22	1.52	0.69	1.21	0.22	0.12	0.17	0.16	0.13		0.13	0.09	0.11	0.17	0.22	0.06		0.01	0.01	0.01						
Mar 2024	2.53	2.19	1.54	0.69	1.14	0.25	0.12	0.16	0.14	0.14		0.12	0.09	0.10	0.16	0.22	0.06		0.01	0.01	0.01						
Apr 2024	2.53	2.16	1.51	0.73	1.24	0.27	0.34	0.17	0.18	0.15		0.13	0.07	0.11	0.15	0.19	0.07	0.01	0.01	0.01	0.01						
May 2024	2.75	2.24	1.50	0.83	1.20	0.30	0.36	0.16	0.18	0.15		0.14	0.06	0.11	0.15	0.09	0.07	0.01	0.01	0.01	0.01						
Jun 2024	2.88	2.34	1.52	0.91	0.71	0.32	0.37	0.15	0.20	0.16	0.03	0.16	0.07	0.11	0.15	0.10	0.07	0.01	0.01	0.01	0.01						
Jul 2024	2.83	2.45	1.65	1.01	0.71	0.34	0.43	0.15	0.20	0.18	0.06	0.17	0.09	0.12	0.15	0.09	0.07	0.01	0.01	0.01	0.01						
Aug 2024	2.96	2.48	1.70	1.11	0.81	0.35	0.45	0.35	0.19	0.18	0.12	0.18	0.11	0.12	0.14	0.08	0.08	0.01	0.01	0.01	0.01						
Sep 2024	3.13	2.26	1.44	1.18	0.72	0.35	0.44	0.42	0.24	0.18	0.12	0.18	0.13	0.13	0.15	0.07	0.08	0.01	0.01	0.01	0.01						
Oct 2024	3.23	2.35	1.53	1.23	0.66	0.40	0.43	0.39	0.27	0.19	0.17	0.18	0.14	0.12	0.14	0.09	0.09	0.01	0.01	0.01	0.01						
Nov 2024	3.21	2.31	1.52	1.27	0.63	0.44	0.43	0.41	0.29	0.21	0.19	0.17	0.14	0.12	0.11	0.10	0.08	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

### Overall

At least one tracker was found on 19.45% of new episodes in November, shrinking 3.89% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "35.35%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.92%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.56%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.88%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.02%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.89%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.90%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.79%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.49%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.36%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of November 2024.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 11.86% of new episodes in November, shrinking 3.08% from last month.

Of these, 14.73% had one other tracker, 11.22% had 2 other trackers, 2.27% had 3 other trackers, 1.35% had 5 other trackers, 1.24% had 4 other trackers, 0.50% had 6 other trackers, 0.16% had 7 other trackers, 0.13% had 8 other trackers, and 0.01% had 9 other trackers.

17.89% also included Chartable, 12.37% also included Podsights, 6.45% also included Adswizz, 6.31% also included Podscribe, 2.94% also included Podroll, 2.61% also included Podder, 2.16% also included Magellan AI, 2.10% also included Spotify, 1.46% also included Podcorn, 1.15% also included Claritas, 1.07% also included OP3, 0.96% also included ArtsAI, 0.89% also included Swap.fm, 0.70% also included Audiotakes, 0.63% also included Gumshoe, 0.61% also included Veritonic, 0.35% also included Blubrry, 0.08% also included CoHost Prefix, 0.03% also included Feedpress, 0.02% also included United Podcasters, 0.02% also included Médiamétrie, 0.01% also included Podkite, 0.01% also included Zencastr, and <0.01% also included AdBarker.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "57.61%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.04%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.38%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.26%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.92%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.37%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.34%" >}}
8. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.30%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.11%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.08%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 5.57% of new episodes in November, shrinking 11.20% from last month.

Of these, 47.18% also included Podtrac, 14.03% also included Podscribe, 9.37% also included Adswizz, 6.30% also included Magellan AI, 3.38% also included Claritas, 3.10% also included Swap.fm, 2.89% also included Podder, 2.73% also included ArtsAI, 2.63% also included Podcorn, 2.11% also included Audiotakes, 2.06% also included Podroll, 1.79% also included Gumshoe, 1.72% also included OP3, 1.46% also included Veritonic, 0.87% also included Firstory, 0.43% also included Blubrry, 0.21% also included CoHost Prefix, 0.12% also included United Podcasters, 0.05% also included Podkite, 0.03% also included Zencastr, 0.03% also included AdBarker, 0.02% also included Feedpress, and <0.01% also included Glystn.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.89%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "19.58%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.41%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.62%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.59%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.51%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.82%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.66%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.49%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.20%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 4.66% of new episodes in November, shrinking 15.23% from last month.

Of these, 29.66% had one other tracker, 23.16% had 2 other trackers, 6.11% had 3 other trackers, 3.25% had 4 other trackers, 1.94% had 5 other trackers, 1.37% had 6 other trackers, 0.35% had 7 other trackers, 0.32% had 8 other trackers, and 0.02% had 9 other trackers.

45.58% also included Podtrac, 33.03% also included Podsights, 10.80% also included Podscribe, 8.31% also included Adswizz, 5.95% also included Spotify, 5.04% also included Magellan AI, 3.56% also included Swap.fm, 2.57% also included Podder, 2.48% also included Claritas, 2.33% also included ArtsAI, 2.12% also included Podroll, 1.93% also included Podcorn, 1.44% also included Veritonic, 1.39% also included Audiotakes, 1.04% also included Firstory, 1.01% also included Gumshoe, 0.93% also included OP3, 0.38% also included Blubrry, 0.22% also included CoHost Prefix, 0.13% also included United Podcasters, 0.06% also included Podkite, 0.03% also included AdBarker, 0.03% also included Feedpress, 0.02% also included Zencastr, and <0.01% also included Glystn.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.88%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.29%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.31%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.14%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.18%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.61%" >}}
7. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.98%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.65%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.56%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.29%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 3.21% of new episodes in November, shrinking 0.73% from last month.

Of these, 15.37% had one other tracker, 13.93% had 2 other trackers, 2.19% had 3 other trackers, 1.48% had 5 other trackers, 1.17% had 4 other trackers, 0.47% had 7 other trackers, 0.29% had 6 other trackers, and 0.09% had 8 other trackers.

23.86% also included Podtrac, 12.05% also included Chartable, 9.50% also included Podroll, 5.56% also included Podsights, 4.93% also included Podscribe, 2.44% also included Magellan AI, 2.31% also included Claritas, 2.00% also included Spotify, 1.21% also included ArtsAI, 0.96% also included Blubrry, 0.76% also included Audiotakes, 0.71% also included Podder, 0.64% also included Veritonic, 0.33% also included Swap.fm, 0.22% also included OP3, 0.17% also included Podcorn, 0.03% also included Gumshoe, 0.01% also included United Podcasters, and <0.01% also included CoHost Prefix.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "48.79%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "9.03%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "7.39%" >}}
4. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "7.16%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "6.72%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.76%" >}}
7. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "4.72%" >}}
8. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.95%" >}}
9. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "1.82%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.17%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.31% of new episodes in November, shrinking 1.78% from last month.

Of these, 31.89% had one other tracker, 31.83% had 2 other trackers, 11.00% had 3 other trackers, 7.42% had 4 other trackers, 5.99% had 5 other trackers, 2.87% had 6 other trackers, 0.67% had 7 other trackers, 0.65% had 8 other trackers, and 0.03% had 9 other trackers.

66.61% also included Chartable, 63.56% also included Podtrac, 23.21% also included Podscribe, 10.85% also included Magellan AI, 7.73% also included Adswizz, 5.44% also included Claritas, 5.30% also included Swap.fm, 5.03% also included Podder, 5.02% also included ArtsAI, 3.36% also included Audiotakes, 3.32% also included Spotify, 3.20% also included Podroll, 3.18% also included Podcorn, 3.14% also included Gumshoe, 2.84% also included OP3, 2.82% also included Veritonic, 0.38% also included CoHost Prefix, 0.31% also included Blubrry, 0.21% also included United Podcasters, 0.04% also included Feedpress, 0.04% also included Zencastr, and 0.03% also included Podkite.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "57.56%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "25.47%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.59%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.73%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.65%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.52%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.18%" >}}
8. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.14%" >}}
9. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.98%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.90%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.52% of new episodes in November, shrinking 0.93% from last month.

Of these, 5.65% had one other tracker, 0.74% had 2 other trackers, 0.10% had 3 other trackers, 0.07% had 4 other trackers, 0.05% had 6 other trackers, and 0.04% had 5 other trackers.

2.75% also included Podtrac, 2.03% also included Adswizz, 1.15% also included Chartable, 0.50% also included Feedpress, 0.48% also included Podsights, 0.41% also included OP3, 0.31% also included Podscribe, 0.16% also included Podcorn, 0.13% also included Podder, 0.09% also included Spotify, 0.08% also included Magellan AI, 0.02% also included Audiotakes, 0.02% also included Podroll, 0.02% also included Veritonic, and <0.01% also included Claritas.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "38.57%" >}}
2. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "9.71%" >}}
3. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "6.43%" >}}
4. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "3.60%" >}}
5. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.25%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.27%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.79%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.03%" >}}
9. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "0.95%" >}}
10. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "0.83%" >}}
---

### 6. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 1.27% of new episodes in November, growing 3.21% from last month.

Of these, 22.83% had one other tracker, 15.26% had 2 other trackers, 14.03% had 5 other trackers, 13.07% had 4 other trackers, 12.84% had 3 other trackers, 5.52% had 6 other trackers, 1.71% had 7 other trackers, 1.17% had 8 other trackers, and 0.06% had 9 other trackers.

58.96% also included Podtrac, 42.22% also included Podsights, 39.63% also included Chartable, 24.43% also included Magellan AI, 15.43% also included Claritas, 15.26% also included Spotify, 12.47% also included Adswizz, 11.87% also included ArtsAI, 9.88% also included Audiotakes, 8.89% also included Podder, 5.96% also included Podcorn, 5.53% also included Gumshoe, 4.97% also included Swap.fm, 4.92% also included Veritonic, 4.10% also included OP3, 3.48% also included Podroll, 0.55% also included CoHost Prefix, 0.38% also included Blubrry, 0.28% also included United Podcasters, 0.03% also included Podkite, 0.03% also included Zencastr, 0.01% also included AdBarker, and 0.01% also included Feedpress.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "51.19%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "12.27%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.63%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.07%" >}}
5. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "4.35%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.13%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.56%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.43%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.10%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.43%" >}}
---

### 7. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.63% of new episodes in November, shrinking 3.87% from last month.

Of these, 17.53% had one other tracker, 6.40% had 5 other trackers, 5.86% had 2 other trackers, 4.02% had 3 other trackers, 2.52% had 4 other trackers, 0.72% had 6 other trackers, 0.12% had 9 other trackers, 0.08% had 7 other trackers, and 0.03% had 8 other trackers.

27.31% also included Podtrac, 14.16% also included Chartable, 11.92% also included Podscribe, 11.59% also included Podsights, 10.21% also included OP3, 8.03% also included Gumshoe, 1.96% also included Podroll, 1.48% also included Podder, 0.85% also included Adswizz, 0.48% also included Spotify, 0.39% also included Blubrry, 0.37% also included Magellan AI, 0.33% also included Swap.fm, 0.18% also included Feedpress, 0.10% also included Podkite, 0.09% also included CoHost Prefix, 0.09% also included United Podcasters, 0.04% also included AdBarker, and 0.03% also included Audiotakes.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "19.53%" >}}
2. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "16.03%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "12.32%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "11.14%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.45%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "9.45%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "6.19%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.59%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.95%" >}}
10. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "1.69%" >}}
---

### 8. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.44% of new episodes in November, growing 8.94% from last month.

Of these, 31.69% had 2 other trackers, 22.04% had one other tracker, 11.38% had 5 other trackers, 8.89% had 3 other trackers, 6.63% had 4 other trackers, 5.92% had 6 other trackers, 3.32% had 8 other trackers, and 2.17% had 7 other trackers.

62.84% also included Chartable, 56.37% also included Podtrac, 43.90% also included Podscribe, 24.97% also included Magellan AI, 18.55% also included Claritas, 17.39% also included Podsights, 14.54% also included Adswizz, 12.28% also included ArtsAI, 8.19% also included Audiotakes, 5.38% also included Veritonic, 3.07% also included Podder, 2.52% also included Gumshoe, 0.90% also included OP3, 0.69% also included Podcorn, 0.42% also included Podroll, 0.36% also included Swap.fm, 0.31% also included Blubrry, and 0.12% also included United Podcasters.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "39.57%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "26.99%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "13.28%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.65%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.51%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.65%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.53%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.32%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.90%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.57%" >}}
---

### 9. [Podroll](https://podroll.fm/)

Podroll was found on 0.43% of new episodes in November, shrinking 1.18% from last month.

Of these, 72.92% had 2 other trackers, 8.41% had one other tracker, 6.32% had 4 other trackers, 6.16% had 3 other trackers, 1.80% had 5 other trackers, 1.33% had 6 other trackers, 0.96% had 7 other trackers, 0.18% had 9 other trackers, and 0.11% had 8 other trackers.

81.53% also included Podtrac, 71.14% also included Adswizz, 23.06% also included Chartable, 17.24% also included Podsights, 10.31% also included Podscribe, 5.24% also included Swap.fm, 2.91% also included Podcorn, 2.54% also included Magellan AI, 2.17% also included Claritas, 1.76% also included OP3, 1.60% also included ArtsAI, 1.21% also included Podder, 1.08% also included Gumshoe, 0.76% also included Audiotakes, 0.56% also included CoHost Prefix, 0.43% also included Spotify, 0.34% also included Veritonic, 0.29% also included United Podcasters, 0.06% also included Blubrry, and 0.05% also included Podkite.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "70.57%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "17.22%" >}}
3. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "3.12%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.95%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.06%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.49%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.69%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.62%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.39%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.38%" >}}
---

### 10. [Podder](https://www.podderapp.com/)

Podder was found on 0.41% of new episodes in November, growing 4.15% from last month.

Of these, 48.62% had one other tracker, 11.55% had 2 other trackers, 9.79% had 4 other trackers, 9.59% had 5 other trackers, 6.88% had 3 other trackers, 3.54% had 6 other trackers, 0.49% had 7 other trackers, and 0.19% had 9 other trackers.

75.74% also included Podtrac, 29.29% also included Chartable, 28.46% also included Podsights, 27.63% also included Podscribe, 11.78% also included Magellan AI, 9.46% also included Audiotakes, 5.61% also included Adswizz, 4.69% also included ArtsAI, 3.32% also included Spotify, 2.31% also included Podcorn, 1.43% also included OP3, 1.40% also included Claritas, 1.32% also included Gumshoe, 1.27% also included Podroll, 0.52% also included Swap.fm, 0.49% also included Blubrry, 0.49% also included Veritonic, 0.29% also included CoHost Prefix, 0.24% also included United Podcasters, and 0.16% also included Podkite.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "50.59%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "30.86%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.72%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.06%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.29%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.33%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "1.23%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.09%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.08%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.44%" >}}
---

### 11. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.40% of new episodes in November, growing 6.92% from last month.

Of these, 27.04% had 5 other trackers, 22.32% had 4 other trackers, 13.51% had 3 other trackers, 12.14% had 6 other trackers, 8.35% had 2 other trackers, 6.44% had one other tracker, 3.91% had 7 other trackers, and 3.63% had 8 other trackers.

76.67% also included Podscribe, 63.45% also included Podtrac, 61.95% also included Podsights, 58.02% also included Chartable, 39.09% also included Claritas, 27.23% also included Spotify, 21.94% also included ArtsAI, 19.32% also included Adswizz, 14.51% also included Audiotakes, 12.22% also included Veritonic, 11.89% also included Podder, 3.94% also included Swap.fm, 2.69% also included Podroll, 2.19% also included Gumshoe, 0.94% also included OP3, 0.58% also included Podcorn, 0.47% also included United Podcasters, 0.31% also included Blubrry, and 0.04% also included CoHost Prefix.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "49.91%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "17.47%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.86%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.43%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.20%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.94%" >}}
7. {{< a "https://www.americanpublicmedia.org/" "American Public Media" >}} {{< span "weak" "4.33%" >}}
8. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.55%" >}}
9. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "0.43%" >}}
10. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.40%" >}}
---

### 12. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.29% of new episodes in November, growing 8.89% from last month.

Of these, 20.92% had one other tracker, 14.80% had 5 other trackers, 7.24% had 2 other trackers, 5.98% had 3 other trackers, 3.54% had 4 other trackers, 1.53% had 6 other trackers, 0.26% had 9 other trackers, and 0.15% had 7 other trackers.

43.54% also included Podtrac, 22.45% also included Podsights, 22.15% also included Podcorn, 18.67% also included Gumshoe, 17.80% also included Podscribe, 14.84% also included Chartable, 2.59% also included Podroll, 2.38% also included Adswizz, 2.12% also included Blubrry, 1.99% also included Podder, 1.36% also included Spotify, 1.30% also included Magellan AI, 0.65% also included ArtsAI, 0.60% also included Swap.fm, 0.58% also included Claritas, 0.52% also included Podkite, 0.22% also included Audiotakes, 0.19% also included CoHost Prefix, and 0.07% also included Feedpress.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "27.40%" >}}
2. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "11.36%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.68%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.06%" >}}
5. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "4.54%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.08%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.04%" >}}
8. {{< a "https://radiolaser.fr/" "Radio Laser" >}} {{< span "weak" "2.76%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.12%" >}}
10. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "1.81%" >}}
---

### 13. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.21% of new episodes in November, growing 7.58% from last month.

Of these, 32.08% had 5 other trackers, 21.07% had 6 other trackers, 18.18% had 4 other trackers, 8.43% had 2 other trackers, 7.65% had 7 other trackers, 5.72% had 8 other trackers, 3.72% had 3 other trackers, and 2.65% had one other tracker.

93.65% also included Podscribe, 75.62% also included Magellan AI, 65.37% also included Podtrac, 60.04% also included Podsights, 55.33% also included Chartable, 39.13% also included Spotify, 35.41% also included Adswizz, 32.70% also included ArtsAI, 20.84% also included Veritonic, 4.45% also included Podroll, 2.73% also included Podder, 2.60% also included Swap.fm, 0.81% also included OP3, 0.75% also included Gumshoe, 0.08% also included Audiotakes, and 0.03% also included Blubrry.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "42.40%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "29.03%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.79%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.89%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "5.98%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.46%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.57%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.21%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.18%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.16%" >}}
---

### 14. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.19% of new episodes in November, growing 15.03% from last month.

Of these, 33.36% had 3 other trackers, 20.30% had 2 other trackers, 19.16% had one other tracker, 17.22% had 4 other trackers, 4.90% had 5 other trackers, 3.11% had 6 other trackers, 0.68% had 7 other trackers, and 0.11% had 8 other trackers.

86.83% also included Chartable, 64.16% also included Podsights, 55.20% also included Podtrac, 33.05% also included Podscribe, 11.78% also included Podroll, 8.35% also included Magellan AI, 5.47% also included Adswizz, 2.85% also included Claritas, 2.65% also included ArtsAI, 1.11% also included Podder, 1.08% also included Podcorn, 0.91% also included OP3, 0.88% also included United Podcasters, 0.83% also included Spotify, 0.71% also included Veritonic, 0.68% also included Audiotakes, 0.66% also included Gumshoe, 0.23% also included Zencastr, and 0.17% also included CoHost Prefix.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "79.27%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.98%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.62%" >}}
4. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "2.31%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.48%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.57%" >}}
7. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.51%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.26%" >}}
---

### 15. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.17% of new episodes in November, shrinking 3.53% from last month.

Of these, 21.16% had 5 other trackers, 19.14% had 4 other trackers, 18.51% had 6 other trackers, 11.81% had 7 other trackers, 9.89% had 2 other trackers, 8.94% had 3 other trackers, 8.50% had 8 other trackers, and 1.92% had one other tracker.

87.25% also included Podscribe, 67.16% also included Podsights, 65.74% also included Podtrac, 62.94% also included Chartable, 51.39% also included Magellan AI, 39.58% also included Claritas, 31.36% also included Spotify, 24.53% also included Audiotakes, 22.48% also included Adswizz, 21.03% also included Veritonic, 11.08% also included Podder, 3.97% also included Podroll, 2.93% also included Swap.fm, 1.10% also included OP3, and 0.09% also included Gumshoe.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "35.48%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.07%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "14.77%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "11.15%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.80%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "7.05%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.83%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.94%" >}}
9. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.69%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.13%" >}}
---

### 16. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.14% of new episodes in November, growing 1.31% from last month.

Of these, 34.34% had 4 other trackers, 20.44% had 3 other trackers, 19.02% had 5 other trackers, 12.11% had 6 other trackers, 8.02% had 2 other trackers, 1.83% had 7 other trackers, and 1.68% had one other tracker.

88.04% also included Podscribe, 58.40% also included Podtrac, 54.51% also included Podsights, 45.30% also included Chartable, 41.21% also included Magellan AI, 29.76% also included ArtsAI, 27.12% also included Podder, 25.36% also included Spotify, 17.19% also included Adswizz, 2.98% also included Veritonic, 2.29% also included Podroll, 2.02% also included Gumshoe, 0.92% also included United Podcasters, 0.92% also included Swap.fm, 0.46% also included OP3, 0.23% also included Blubrry, 0.15% also included Podcorn, and 0.11% also included Claritas.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "31.70%" >}}
2. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "25.48%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "15.85%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "10.28%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.40%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.14%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.64%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.64%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "1.41%" >}}
10. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.27%" >}}
---

### 17. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.12% of new episodes in November, shrinking 3.66% from last month.

Of these, 35.50% had 5 other trackers, 14.79% had 4 other trackers, 14.25% had one other tracker, 12.17% had 3 other trackers, 11.13% had 2 other trackers, 4.34% had 6 other trackers, 0.63% had 9 other trackers, and 0.18% had 7 other trackers.

61.69% also included Podtrac, 60.20% also included Podsights, 58.34% also included Podscribe, 45.36% also included OP3, 42.33% also included Podcorn, 38.94% also included Chartable, 9.23% also included Spotify, 7.37% also included Magellan AI, 4.48% also included Podder, 3.84% also included Podroll, 2.94% also included CoHost Prefix, 2.40% also included Audiotakes, 1.40% also included Veritonic, 1.31% also included Claritas, 1.04% also included Swap.fm, 0.77% also included United Podcasters, 0.72% also included Adswizz, 0.18% also included Podkite, and 0.14% also included ArtsAI.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "46.18%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "25.15%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "17.91%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.39%" >}}
5. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "4.21%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.09%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.32%" >}}
8. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.27%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.18%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.14%" >}}
---

### 18. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.11% of new episodes in November, shrinking 21.36% from last month.

Of these, 11.72% had one other tracker, and 0.99% had 2 other trackers.

6.92% also included Blubrry, 3.41% also included Podtrac, 1.14% also included Chartable, 1.04% also included Podcorn, 0.89% also included Podsights, 0.20% also included OP3, and 0.10% also included Podscribe.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "71.27%" >}}
2. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "6.48%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.72%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.72%" >}}
5. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "2.67%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.83%" >}}
7. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.38%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.34%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.99%" >}}
10. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "0.99%" >}}
---

### 19. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.10% of new episodes in November, growing 4.04% from last month.

Of these, 2.44% had one other tracker.

2.44% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "40.42%" >}}
2. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "33.00%" >}}
3. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "22.54%" >}}
---

### 20. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.08% of new episodes in November, shrinking 2.82% from last month.

Of these, 22.48% had 6 other trackers, 17.37% had 8 other trackers, 16.58% had 7 other trackers, 13.37% had 4 other trackers, 12.45% had 5 other trackers, 9.17% had 2 other trackers, and 7.01% had 3 other trackers.

87.88% also included Podtrac, 80.93% also included Chartable, 78.37% also included Podsights, 75.16% also included Podscribe, 59.57% also included Magellan AI, 52.49% also included Claritas, 43.77% also included ArtsAI, 28.57% also included Spotify, 24.90% also included Adswizz, 5.11% also included Audiotakes, 2.42% also included Podder, 2.03% also included Gumshoe, 1.77% also included Podroll, 1.64% also included Swap.fm, and 0.33% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "66.12%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "20.45%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.93%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.67%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.15%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.18%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.72%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.26%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.26%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.26%" >}}
---

### 21. [Firstory](https://firstory.me/)

Firstory was found on 0.06% of new episodes in November, growing 2.88% from last month.

Of these, 80.93% had one other tracker.

80.93% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.73%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.27%" >}}
---

### 22. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.01% of new episodes in November, growing 5.94% from last month.

Of these, 29.39% had 3 other trackers, 22.86% had 4 other trackers, 12.65% had 2 other trackers, 11.43% had 5 other trackers, 8.98% had one other tracker, 4.08% had 6 other trackers, and 4.08% had 9 other trackers.

76.33% also included Chartable, 71.43% also included Podtrac, 65.71% also included Podsights, 52.24% also included Podscribe, 26.53% also included Gumshoe, 17.96% also included Podroll, 8.98% also included Podder, 4.49% also included Podcorn, 4.08% also included OP3, 2.45% also included Swap.fm, 1.22% also included Magellan AI, and 0.82% also included Adswizz.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "66.53%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "7.76%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "7.35%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "5.71%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.90%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "2.45%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.63%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.82%" >}}
9. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "0.82%" >}}
10. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "0.41%" >}}
---

### 23. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in November, shrinking 2.66% from last month.

Of these, 28.57% had one other tracker, 18.86% had 5 other trackers, 14.29% had 3 other trackers, 10.29% had 6 other trackers, 6.29% had 4 other trackers, 5.71% had 2 other trackers, and 2.29% had 8 other trackers.

64.57% also included Chartable, 51.43% also included Podsights, 37.71% also included Podscribe, 27.43% also included Podtrac, 20.00% also included Magellan AI, 17.71% also included Swap.fm, 13.71% also included Audiotakes, 13.14% also included Podroll, 10.29% also included Podder, 9.71% also included Gumshoe, 5.71% also included Podcorn, 5.71% also included Spotify, 2.86% also included Adswizz, and 2.29% also included Zencastr.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "52.57%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "13.71%" >}}
3. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "8.57%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.00%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.14%" >}}
6. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "4.57%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.86%" >}}
8. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "2.86%" >}}
9. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "1.14%" >}}
10. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "0.57%" >}}
---

### 24. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in November, shrinking 13.37% from last month.

Of these, 18.49% had one other tracker, 18.49% had 2 other trackers, 2.74% had 5 other trackers, 2.74% had 6 other trackers, and 2.74% had 9 other trackers.

34.93% also included Chartable, 19.86% also included Podtrac, 19.18% also included OP3, 8.90% also included Podsights, 8.22% also included Podcorn, 8.22% also included Podder, 5.48% also included Podscribe, 2.74% also included Podroll, and 2.74% also included Gumshoe.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "23.97%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "23.29%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "21.23%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "13.01%" >}}
5. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "6.16%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.16%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.42%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.05%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.68%" >}}
---

### 25. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in November, shrinking 9.63% from last month.

Of these, 11.36% had one other tracker, 9.85% had 2 other trackers, 3.03% had 5 other trackers, and 3.03% had 6 other trackers.

21.97% also included Podtrac, 15.15% also included Chartable, 12.12% also included Podsights, 6.06% also included Podscribe, 6.06% also included Swap.fm, and 3.03% also included United Podcasters.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "38.64%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "18.94%" >}}
3. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "12.12%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "9.85%" >}}
5. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "6.06%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "6.06%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.55%" >}}
8. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "2.27%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.52%" >}}
---

### 26. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in November, growing 8.50% from last month.

Of these, 21.88% had one other tracker, 14.06% had 2 other trackers, and 4.69% had 4 other trackers.

40.63% also included Chartable, 15.63% also included Podtrac, 7.81% also included Podcorn, and 4.69% also included Podscribe.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "35.94%" >}}
2. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "17.19%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "15.63%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "10.94%" >}}
5. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "7.81%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "6.25%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.25%" >}}
---

### 27. [Glystn](https://glystn.com/)

Glystn was found on <0.01% of new episodes in November, shrinking 78.64% from last month.

Of these, 100.00% had one other tracker.

100.00% also included Chartable.

For episodes that used Glystn, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "100.00%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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

*Updated 2023-11-02, with data for the month of October 2023. Improved accuracy in observing Spotify for Podcasters podcasts: more S4P new episodes leads to lower share of prefixed episodes overall.*

*Updated 2023-10-01, with data for the month of September 2023. Improved accuracy in observing Spotify for Podcasters podcasts: more S4P new episodes leads to lower share of prefixed episodes overall.*

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
