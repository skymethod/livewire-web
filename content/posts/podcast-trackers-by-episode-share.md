---
title: "Top Podcast Tracking Services by Episode Share (October 2024)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2024-10.png
date: 2024-11-06T12:56:00-06:00
lastmod: 2024-11-06T12:56:00-06:00
draft: false
rssrevision: 2024-10
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

We already did the work of analyzing _every single new podcast episode published_ (about 2.0 million in October 2024), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in October, how many
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
Month	Podtrac	Chartable	Adswizz	Podsights	Blubrry	Podscribe	Podcorn	Podroll	Spotify	Podder	OP3	Claritas	ArtsAI	Swap.fm	Audiotakes	Feedpress	Gumshoe	Médiamétrie	Veritonic	CoHost Prefix	United Podcasters	Podkite	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.00	1.16	2.07		2.09									0.32		0.42											1.61
Oct 2021	4.05	4.09	1.01	1.20	2.11		2.13									0.34		0.54											1.61
Nov 2021	4.07	4.30	1.02	1.25	2.01		2.14									0.32		0.57											0.59
Dec 2021	4.06	4.42	1.24	1.19	1.57		2.27									0.19		0.59											
Jan 2022	4.11	4.45	1.41	1.21	1.56		2.31									0.16		0.63											
Feb 2022	4.15	4.48	1.44	1.25	1.53		2.38									0.17		0.58											
Mar 2022	4.37	4.72	1.51	1.34	1.56		2.40									0.17		0.53											
Apr 2022	4.44	4.71	1.49	1.33	1.55		2.33									0.16		0.51											
May 2022	4.49	4.87	1.58	1.41	1.48		2.26									0.17		0.56											
Jun 2022	4.75	5.10	1.77	1.54	1.50		2.06									0.21		0.62								0.02			
Jul 2022	4.70	5.10	1.89	1.50	1.50		2.16									0.25		0.54								0.02			
Aug 2022	4.83	5.26	2.08	1.73	1.51		2.45						0.10			0.20		0.41								0.01			
Sep 2022	7.53	5.40	2.26	1.74	1.49	0.02	2.45					0.01	0.09			0.21		0.52				0.01				0.02	0.02		
Oct 2022	8.24	5.48	2.35	1.81	1.61	0.07	2.51				0.03	0.02	0.10			0.18		0.50				0.01	0.01			0.02	0.04		
Nov 2022	8.11	5.62	2.37	2.03	1.62	0.15	2.43			0.01	0.04	0.03	0.10			0.18		0.50				0.01	0.01			0.02	0.05		
Dec 2022	8.01	5.54	2.32	1.81	1.61	0.03	2.05			0.04	0.05	0.02	0.05			0.18		0.49				0.01	0.01		0.01	0.02	0.05		
Jan 2023	7.85	5.56	2.35	1.88	1.61	0.20	2.15			0.11	0.07	0.06	0.10			0.18		0.54				0.01	0.01		0.01	0.02	0.06		
Feb 2023	7.58	5.51	2.29	1.92	1.62	0.21	2.30			0.11	0.07	0.07	0.10			0.19		0.49				0.01	0.01		0.01	0.02	0.06	0.03	
Mar 2023	7.79	5.53	2.25	2.03	1.53	0.21	2.22	0.04		0.11	0.08	0.07	0.11			0.18		0.45	0.04			0.01	0.01		0.01	0.02	0.06		
Apr 2023	7.66	5.43	2.26	2.00	1.67	0.21	2.20	0.06		0.15	0.09	0.07	0.11			0.17	0.08	0.45	0.05			0.01	0.01		0.01	0.01			
May 2023	7.58	5.59	2.27	2.04	1.67	0.24	2.28	0.09		0.15	0.09	0.08	0.11			0.19	0.07	0.45	0.05			0.01	0.01	0.01	0.01	0.01			
Jun 2023	8.22	5.83	2.39	2.23	1.64	0.26	1.86	0.10		0.15	0.09	0.07	0.12			0.19	0.08	0.51	0.05			0.01	0.01	0.01	0.01	0.01			
Jul 2023	8.60	5.95	2.38	2.52	1.53	0.27	1.17	0.14	0.01	0.14	0.08	0.07	0.11			0.18	0.06	0.55	0.06			0.01	0.01	0.01	0.01	0.01			
Aug 2023	9.19	6.43	2.72	2.76	1.58	0.36	1.23	0.16	0.03	0.15	0.11	0.08	0.12		0.04	0.17	0.07	0.53	0.07			0.01	0.01	0.02	0.01				
Sep 2023	8.46	5.77	2.49	2.47	1.39	0.37	1.10	0.13	0.05	0.15	0.10	0.10	0.12		0.05	0.16	0.07	0.58	0.06			0.01	0.01	0.02	0.01				
Oct 2023	7.90	5.54	2.29	2.28	1.37	0.39	1.11	0.12	0.08	0.16	0.10	0.10	0.12		0.05	0.16	0.08	0.50	0.06			0.01	0.02	0.03	0.01				
Nov 2023	7.65	5.59	2.25	2.33	1.45	0.47	1.14	0.12	0.11	0.16	0.13	0.11	0.12		0.06	0.17	0.10	0.33	0.06			0.01	0.01	0.03					
Dec 2023	7.48	5.60	2.20	2.19	1.53	0.54	1.12	0.12	0.12	0.16	0.11	0.11	0.12		0.06	0.16	0.09	0.33	0.06			0.01	0.01	0.03					
Jan 2024	7.64	5.61	2.37	2.21	1.55	0.65	1.17	0.11	0.15	0.16	0.13	0.12	0.14		0.08	0.17	0.10	0.25	0.06		0.01	0.01	0.01	0.01					
Feb 2024	7.69	5.58	2.38	2.22	1.52	0.69	1.21	0.12	0.22	0.17	0.16	0.13	0.13		0.09	0.17	0.11	0.22	0.06		0.01	0.01	0.01						
Mar 2024	9.01	5.46	2.53	2.19	1.54	0.69	1.14	0.12	0.25	0.16	0.14	0.14	0.12		0.09	0.16	0.10	0.22	0.06		0.01	0.01	0.01						
Apr 2024	10.78	5.47	2.53	2.16	1.51	0.73	1.24	0.34	0.27	0.17	0.18	0.15	0.13		0.07	0.15	0.11	0.19	0.07	0.01	0.01	0.01	0.01						
May 2024	11.59	5.63	2.75	2.24	1.50	0.83	1.20	0.36	0.30	0.16	0.18	0.15	0.14		0.06	0.15	0.11	0.09	0.07	0.01	0.01	0.01	0.01						
Jun 2024	11.54	6.06	2.88	2.34	1.52	0.91	0.71	0.37	0.32	0.15	0.20	0.16	0.16	0.03	0.07	0.15	0.11	0.10	0.07	0.01	0.01	0.01	0.01						
Jul 2024	12.34	6.80	2.83	2.45	1.65	1.01	0.71	0.43	0.34	0.15	0.20	0.18	0.17	0.06	0.09	0.15	0.12	0.09	0.07	0.01	0.01	0.01	0.01						
Aug 2024	14.22	6.72	2.96	2.48	1.70	1.11	0.81	0.45	0.35	0.35	0.19	0.18	0.18	0.12	0.11	0.14	0.12	0.08	0.08	0.01	0.01	0.01	0.01						
Sep 2024	12.95	5.99	3.13	2.26	1.44	1.18	0.72	0.44	0.35	0.42	0.24	0.18	0.18	0.12	0.13	0.15	0.13	0.07	0.08	0.01	0.01	0.01	0.01						
Oct 2024	12.24	5.49	3.23	2.35	1.53	1.23	0.66	0.43	0.40	0.39	0.27	0.19	0.18	0.17	0.14	0.14	0.12	0.09	0.09	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} are the clear top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podsights	Blubrry	Podscribe	Podcorn	Podroll	Spotify	Podder	OP3	Claritas	ArtsAI	Swap.fm	Audiotakes	Feedpress	Gumshoe	Médiamétrie	Veritonic	CoHost Prefix	United Podcasters	Podkite	Zencastr	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	1.00	1.16	2.07		2.09									0.32		0.42											1.61
Oct 2021	1.01	1.20	2.11		2.13									0.34		0.54											1.61
Nov 2021	1.02	1.25	2.01		2.14									0.32		0.57											0.59
Dec 2021	1.24	1.19	1.57		2.27									0.19		0.59											
Jan 2022	1.41	1.21	1.56		2.31									0.16		0.63											
Feb 2022	1.44	1.25	1.53		2.38									0.17		0.58											
Mar 2022	1.51	1.34	1.56		2.40									0.17		0.53											
Apr 2022	1.49	1.33	1.55		2.33									0.16		0.51											
May 2022	1.58	1.41	1.48		2.26									0.17		0.56											
Jun 2022	1.77	1.54	1.50		2.06									0.21		0.62								0.02			
Jul 2022	1.89	1.50	1.50		2.16									0.25		0.54								0.02			
Aug 2022	2.08	1.73	1.51		2.45						0.10			0.20		0.41								0.01			
Sep 2022	2.26	1.74	1.49	0.02	2.45					0.01	0.09			0.21		0.52				0.01				0.02	0.02		
Oct 2022	2.35	1.81	1.61	0.07	2.51				0.03	0.02	0.10			0.18		0.50				0.01	0.01			0.02	0.04		
Nov 2022	2.37	2.03	1.62	0.15	2.43			0.01	0.04	0.03	0.10			0.18		0.50				0.01	0.01			0.02	0.05		
Dec 2022	2.32	1.81	1.61	0.03	2.05			0.04	0.05	0.02	0.05			0.18		0.49				0.01	0.01		0.01	0.02	0.05		
Jan 2023	2.35	1.88	1.61	0.20	2.15			0.11	0.07	0.06	0.10			0.18		0.54				0.01	0.01		0.01	0.02	0.06		
Feb 2023	2.29	1.92	1.62	0.21	2.30			0.11	0.07	0.07	0.10			0.19		0.49				0.01	0.01		0.01	0.02	0.06	0.03	
Mar 2023	2.25	2.03	1.53	0.21	2.22	0.04		0.11	0.08	0.07	0.11			0.18		0.45	0.04			0.01	0.01		0.01	0.02	0.06		
Apr 2023	2.26	2.00	1.67	0.21	2.20	0.06		0.15	0.09	0.07	0.11			0.17	0.08	0.45	0.05			0.01	0.01		0.01	0.01			
May 2023	2.27	2.04	1.67	0.24	2.28	0.09		0.15	0.09	0.08	0.11			0.19	0.07	0.45	0.05			0.01	0.01	0.01	0.01	0.01			
Jun 2023	2.39	2.23	1.64	0.26	1.86	0.10		0.15	0.09	0.07	0.12			0.19	0.08	0.51	0.05			0.01	0.01	0.01	0.01	0.01			
Jul 2023	2.38	2.52	1.53	0.27	1.17	0.14	0.01	0.14	0.08	0.07	0.11			0.18	0.06	0.55	0.06			0.01	0.01	0.01	0.01	0.01			
Aug 2023	2.72	2.76	1.58	0.36	1.23	0.16	0.03	0.15	0.11	0.08	0.12		0.04	0.17	0.07	0.53	0.07			0.01	0.01	0.02	0.01				
Sep 2023	2.49	2.47	1.39	0.37	1.10	0.13	0.05	0.15	0.10	0.10	0.12		0.05	0.16	0.07	0.58	0.06			0.01	0.01	0.02	0.01				
Oct 2023	2.29	2.28	1.37	0.39	1.11	0.12	0.08	0.16	0.10	0.10	0.12		0.05	0.16	0.08	0.50	0.06			0.01	0.02	0.03	0.01				
Nov 2023	2.25	2.33	1.45	0.47	1.14	0.12	0.11	0.16	0.13	0.11	0.12		0.06	0.17	0.10	0.33	0.06			0.01	0.01	0.03					
Dec 2023	2.20	2.19	1.53	0.54	1.12	0.12	0.12	0.16	0.11	0.11	0.12		0.06	0.16	0.09	0.33	0.06			0.01	0.01	0.03					
Jan 2024	2.37	2.21	1.55	0.65	1.17	0.11	0.15	0.16	0.13	0.12	0.14		0.08	0.17	0.10	0.25	0.06		0.01	0.01	0.01	0.01					
Feb 2024	2.38	2.22	1.52	0.69	1.21	0.12	0.22	0.17	0.16	0.13	0.13		0.09	0.17	0.11	0.22	0.06		0.01	0.01	0.01						
Mar 2024	2.53	2.19	1.54	0.69	1.14	0.12	0.25	0.16	0.14	0.14	0.12		0.09	0.16	0.10	0.22	0.06		0.01	0.01	0.01						
Apr 2024	2.53	2.16	1.51	0.73	1.24	0.34	0.27	0.17	0.18	0.15	0.13		0.07	0.15	0.11	0.19	0.07	0.01	0.01	0.01	0.01						
May 2024	2.75	2.24	1.50	0.83	1.20	0.36	0.30	0.16	0.18	0.15	0.14		0.06	0.15	0.11	0.09	0.07	0.01	0.01	0.01	0.01						
Jun 2024	2.88	2.34	1.52	0.91	0.71	0.37	0.32	0.15	0.20	0.16	0.16	0.03	0.07	0.15	0.11	0.10	0.07	0.01	0.01	0.01	0.01						
Jul 2024	2.83	2.45	1.65	1.01	0.71	0.43	0.34	0.15	0.20	0.18	0.17	0.06	0.09	0.15	0.12	0.09	0.07	0.01	0.01	0.01	0.01						
Aug 2024	2.96	2.48	1.70	1.11	0.81	0.45	0.35	0.35	0.19	0.18	0.18	0.12	0.11	0.14	0.12	0.08	0.08	0.01	0.01	0.01	0.01						
Sep 2024	3.13	2.26	1.44	1.18	0.72	0.44	0.35	0.42	0.24	0.18	0.18	0.12	0.13	0.15	0.13	0.07	0.08	0.01	0.01	0.01	0.01						
Oct 2024	3.23	2.35	1.53	1.23	0.66	0.43	0.40	0.39	0.27	0.19	0.18	0.17	0.14	0.14	0.12	0.09	0.09	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

### Overall

At least one tracker was found on 20.23% of new episodes in October, shrinking 4.10% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "35.56%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.44%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.60%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "8.37%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.95%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.88%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.04%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.85%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.61%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.36%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of October 2024.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 12.24% of new episodes in October, shrinking 5.47% from last month.

Of these, 15.34% had one other tracker, 11.28% had 2 other trackers, 2.34% had 3 other trackers, 1.29% had 5 other trackers, 1.18% had 4 other trackers, 0.48% had 6 other trackers, 0.27% had 7 other trackers, 0.03% had 8 other trackers, and <0.01% had 9 other trackers.

19.73% also included Chartable, 12.36% also included Podsights, 6.42% also included Adswizz, 5.99% also included Podscribe, 2.86% also included Podroll, 2.44% also included Podder, 1.92% also included Magellan AI, 1.91% also included Spotify, 1.45% also included Podcorn, 1.03% also included Claritas, 0.98% also included OP3, 0.94% also included ArtsAI, 0.67% also included Swap.fm, 0.66% also included Audiotakes, 0.63% also included Gumshoe, 0.62% also included Veritonic, 0.36% also included Blubrry, 0.07% also included CoHost Prefix, 0.04% also included Feedpress, 0.02% also included Médiamétrie, 0.02% also included United Podcasters, 0.01% also included Podkite, 0.01% also included Zencastr, and 0.01% also included AdBarker.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "58.48%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "11.53%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.41%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.08%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.87%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.22%" >}}
7. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.49%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.35%" >}}
9. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.18%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.09%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 6.28% of new episodes in October, shrinking 5.95% from last month.

Of these, 45.81% also included Podtrac, 12.80% also included Podscribe, 8.61% also included Adswizz, 5.38% also included Magellan AI, 2.85% also included Claritas, 2.82% also included Podder, 2.68% also included Podcorn, 2.64% also included ArtsAI, 2.60% also included Swap.fm, 2.00% also included Podroll, 1.88% also included Audiotakes, 1.74% also included Gumshoe, 1.59% also included OP3, 1.33% also included Veritonic, 0.76% also included Firstory, 0.39% also included Blubrry, 0.18% also included CoHost Prefix, 0.11% also included United Podcasters, 0.06% also included Podkite, 0.05% also included Feedpress, 0.03% also included Zencastr, 0.02% also included AdBarker, <0.01% also included Glystn, and <0.01% also included Voxalyze.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "31.69%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "23.59%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.26%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.52%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.00%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.51%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.71%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.62%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.28%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.13%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 5.49% of new episodes in October, shrinking 8.27% from last month.

Of these, 30.35% had one other tracker, 21.18% had 2 other trackers, 5.63% had 3 other trackers, 2.85% had 4 other trackers, 1.96% had 5 other trackers, 1.22% had 6 other trackers, 0.54% had 7 other trackers, 0.06% had 8 other trackers, and 0.01% had 9 other trackers.

43.96% also included Podtrac, 30.28% also included Podsights, 10.27% also included Podscribe, 7.74% also included Adswizz, 5.39% also included Spotify, 4.42% also included Magellan AI, 2.92% also included Swap.fm, 2.53% also included ArtsAI, 2.46% also included Podder, 2.25% also included Claritas, 2.10% also included Podroll, 1.93% also included Podcorn, 1.32% also included Veritonic, 1.32% also included Audiotakes, 1.01% also included Gumshoe, 0.86% also included Firstory, 0.83% also included OP3, 0.39% also included Blubrry, 0.20% also included CoHost Prefix, 0.11% also included United Podcasters, 0.06% also included Podkite, 0.05% also included Feedpress, 0.03% also included AdBarker, 0.02% also included Zencastr, <0.01% also included Glystn, and <0.01% also included Voxalyze.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "29.62%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "23.61%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "7.10%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.83%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.47%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.64%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.91%" >}}
8. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.61%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.38%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.17%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 3.23% of new episodes in October, growing 3.25% from last month.

Of these, 16.69% had one other tracker, 13.33% had 2 other trackers, 2.44% had 3 other trackers, 1.64% had 5 other trackers, 1.03% had 4 other trackers, 0.38% had 7 other trackers, 0.35% had 6 other trackers, and 0.09% had 8 other trackers.

24.32% also included Podtrac, 13.15% also included Chartable, 9.55% also included Podroll, 5.18% also included Podsights, 4.82% also included Podscribe, 2.25% also included Claritas, 2.24% also included Magellan AI, 2.06% also included Spotify, 1.29% also included ArtsAI, 0.93% also included Blubrry, 0.78% also included Audiotakes, 0.64% also included Veritonic, 0.62% also included Podder, 0.25% also included Podcorn, 0.23% also included Swap.fm, 0.09% also included OP3, 0.04% also included Gumshoe, 0.01% also included United Podcasters, and 0.01% also included CoHost Prefix.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "49.02%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "10.11%" >}}
3. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "7.49%" >}}
4. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "7.02%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "6.29%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "4.57%" >}}
7. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "4.48%" >}}
8. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.83%" >}}
9. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "1.73%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.13%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.35% of new episodes in October, growing 4.08% from last month.

Of these, 34.27% had 2 other trackers, 30.52% had one other tracker, 11.29% had 3 other trackers, 6.85% had 4 other trackers, 6.09% had 5 other trackers, 2.87% had 6 other trackers, 1.24% had 7 other trackers, 0.14% had 8 other trackers, and 0.02% had 9 other trackers.

70.77% also included Chartable, 64.33% also included Podtrac, 22.93% also included Podscribe, 10.34% also included Magellan AI, 7.12% also included Adswizz, 5.17% also included ArtsAI, 5.10% also included Podder, 5.01% also included Claritas, 4.51% also included Swap.fm, 3.32% also included Podcorn, 3.31% also included Gumshoe, 3.17% also included Audiotakes, 3.14% also included Spotify, 3.01% also included Podroll, 2.93% also included Veritonic, 2.89% also included OP3, 0.38% also included CoHost Prefix, 0.30% also included Blubrry, 0.22% also included United Podcasters, 0.05% also included Feedpress, 0.04% also included Zencastr, 0.03% also included Podkite, and <0.01% also included Voxalyze.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "57.51%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "25.03%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.61%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.86%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.83%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.59%" >}}
7. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.11%" >}}
8. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.06%" >}}
9. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.03%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.94%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.53% of new episodes in October, growing 6.88% from last month.

Of these, 5.88% had one other tracker, 1.07% had 2 other trackers, 0.11% had 3 other trackers, 0.06% had 4 other trackers, 0.03% had 6 other trackers, 0.02% had 7 other trackers, and 0.01% had 5 other trackers.

2.84% also included Podtrac, 1.97% also included Adswizz, 1.39% also included Chartable, 0.92% also included Feedpress, 0.46% also included Podsights, 0.38% also included Podscribe, 0.37% also included OP3, 0.26% also included Podcorn, 0.10% also included Podder, 0.08% also included Spotify, 0.06% also included Magellan AI, 0.04% also included Podroll, 0.01% also included Audiotakes, and 0.01% also included Veritonic.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "38.89%" >}}
2. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "9.33%" >}}
3. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "6.36%" >}}
4. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "3.46%" >}}
5. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.09%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.12%" >}}
7. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.74%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.72%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.95%" >}}
10. {{< a "https://podcast45minutos.com.br/" "KFKA" >}} {{< span "weak" "0.89%" >}}
---

### 6. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 1.23% of new episodes in October, growing 4.28% from last month.

Of these, 20.08% had one other tracker, 15.83% had 2 other trackers, 15.36% had 5 other trackers, 13.81% had 3 other trackers, 13.15% had 4 other trackers, 5.83% had 6 other trackers, 2.77% had 7 other trackers, 0.27% had 8 other trackers, and 0.04% had 9 other trackers.

59.57% also included Podtrac, 45.86% also included Chartable, 43.84% also included Podsights, 25.42% also included Magellan AI, 15.51% also included Spotify, 14.66% also included Claritas, 12.67% also included Adswizz, 12.59% also included ArtsAI, 9.77% also included Audiotakes, 9.03% also included Podder, 6.49% also included Podcorn, 5.59% also included Gumshoe, 5.22% also included Veritonic, 4.50% also included OP3, 4.36% also included Swap.fm, 3.13% also included Podroll, 0.49% also included CoHost Prefix, 0.48% also included Blubrry, 0.24% also included United Podcasters, 0.04% also included Feedpress, 0.04% also included Zencastr, 0.01% also included Podkite, and 0.01% also included AdBarker.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "50.01%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "12.57%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "10.73%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.07%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.36%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.89%" >}}
7. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "3.77%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.86%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.03%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.41%" >}}
---

### 7. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.66% of new episodes in October, shrinking 8.15% from last month.

Of these, 19.16% had one other tracker, 6.46% had 5 other trackers, 5.49% had 2 other trackers, 4.69% had 3 other trackers, 2.31% had 4 other trackers, 0.70% had 6 other trackers, 0.12% had 7 other trackers, 0.08% had 9 other trackers, and 0.07% had 8 other trackers.

26.97% also included Podtrac, 16.08% also included Chartable, 12.10% also included Podscribe, 11.84% also included Podsights, 9.74% also included OP3, 8.55% also included Gumshoe, 1.44% also included Podder, 1.29% also included Podroll, 1.24% also included Adswizz, 0.67% also included Spotify, 0.60% also included Blubrry, 0.40% also included Magellan AI, 0.39% also included Swap.fm, 0.34% also included Feedpress, 0.10% also included Podkite, 0.09% also included CoHost Prefix, 0.07% also included United Podcasters, 0.04% also included Audiotakes, 0.03% also included AdBarker, 0.02% also included Voxalyze, and 0.02% also included Claritas.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "20.80%" >}}
2. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "14.24%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "12.91%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "10.94%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "9.51%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "8.90%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.88%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.47%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.09%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.79%" >}}
---

### 8. [Podroll](https://podroll.fm/)

Podroll was found on 0.43% of new episodes in October, shrinking 1.52% from last month.

Of these, 73.47% had 2 other trackers, 8.45% had one other tracker, 7.40% had 3 other trackers, 5.84% had 4 other trackers, 1.59% had 6 other trackers, 1.29% had 5 other trackers, 0.46% had 7 other trackers, 0.12% had 9 other trackers, and 0.11% had 8 other trackers.

80.83% also included Podtrac, 71.24% also included Adswizz, 26.61% also included Chartable, 16.33% also included Podsights, 8.89% also included Podscribe, 5.39% also included Swap.fm, 1.96% also included Podcorn, 1.83% also included Magellan AI, 1.75% also included Claritas, 1.48% also included OP3, 1.20% also included ArtsAI, 1.12% also included Gumshoe, 1.08% also included Podder, 0.69% also included Audiotakes, 0.41% also included Spotify, 0.40% also included CoHost Prefix, 0.34% also included United Podcasters, 0.34% also included Veritonic, 0.13% also included Blubrry, and 0.01% also included Podkite.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "70.63%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "16.64%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.75%" >}}
4. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "3.02%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.84%" >}}
6. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.99%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.98%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.76%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.43%" >}}
10. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.39%" >}}
---

### 9. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.40% of new episodes in October, growing 15.55% from last month.

Of these, 31.53% had 2 other trackers, 24.28% had one other tracker, 12.34% had 5 other trackers, 10.33% had 3 other trackers, 7.81% had 4 other trackers, 5.84% had 6 other trackers, 5.79% had 7 other trackers, and 0.77% had 8 other trackers.

73.11% also included Chartable, 57.65% also included Podtrac, 47.11% also included Podscribe, 27.23% also included Magellan AI, 18.21% also included Podsights, 16.43% also included Adswizz, 15.70% also included Claritas, 13.40% also included ArtsAI, 8.36% also included Audiotakes, 6.21% also included Veritonic, 3.27% also included Podder, 3.01% also included Gumshoe, 1.09% also included Podcorn, 1.01% also included OP3, 0.44% also included Podroll, 0.31% also included Swap.fm, 0.30% also included Blubrry, and 0.09% also included United Podcasters.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "39.92%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "23.48%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "14.87%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "7.28%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.70%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.97%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.89%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.60%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.06%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.81%" >}}
---

### 10. [Podder](https://www.podderapp.com/)

Podder was found on 0.39% of new episodes in October, shrinking 6.63% from last month.

Of these, 49.81% had one other tracker, 11.15% had 2 other trackers, 11.04% had 4 other trackers, 9.90% had 5 other trackers, 8.06% had 3 other trackers, 3.22% had 6 other trackers, 0.70% had 7 other trackers, 0.13% had 9 other trackers, and 0.06% had 8 other trackers.

76.25% also included Podtrac, 34.50% also included Chartable, 30.57% also included Podsights, 28.34% also included Podscribe, 12.53% also included Magellan AI, 9.51% also included Audiotakes, 5.46% also included ArtsAI, 5.11% also included Adswizz, 3.38% also included Spotify, 2.42% also included Podcorn, 1.62% also included Gumshoe, 1.57% also included OP3, 1.44% also included Claritas, 1.20% also included Podroll, 0.55% also included Veritonic, 0.48% also included Swap.fm, 0.38% also included Blubrry, 0.26% also included United Podcasters, 0.22% also included CoHost Prefix, and 0.12% also included Podkite.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "49.79%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "32.89%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.11%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.74%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.57%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.29%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.13%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.12%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.91%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.43%" >}}
---

### 11. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.38% of new episodes in October, growing 8.31% from last month.

Of these, 31.36% had 5 other trackers, 20.81% had 4 other trackers, 14.40% had 3 other trackers, 12.68% had 6 other trackers, 7.35% had 7 other trackers, 5.52% had one other tracker, 5.01% had 2 other trackers, and 0.77% had 8 other trackers.

82.64% also included Podscribe, 64.25% also included Podsights, 64.15% also included Chartable, 62.09% also included Podtrac, 37.33% also included Claritas, 29.14% also included Spotify, 23.72% also included ArtsAI, 19.13% also included Adswizz, 15.35% also included Audiotakes, 13.22% also included Veritonic, 12.98% also included Podder, 2.18% also included Gumshoe, 2.10% also included Podroll, 1.80% also included Swap.fm, 1.08% also included OP3, 0.70% also included Podcorn, 0.36% also included United Podcasters, 0.24% also included Blubrry, and 0.01% also included CoHost Prefix.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "52.93%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "18.71%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.70%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "6.62%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.57%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.38%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.58%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.40%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.22%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.19%" >}}
---

### 12. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.27% of new episodes in October, growing 12.75% from last month.

Of these, 21.90% had one other tracker, 16.59% had 5 other trackers, 6.19% had 3 other trackers, 5.56% had 2 other trackers, 4.33% had 4 other trackers, 1.80% had 6 other trackers, 0.30% had 7 other trackers, 0.19% had 9 other trackers, and 0.09% had 8 other trackers.

44.87% also included Podtrac, 25.32% also included Podsights, 23.95% also included Podcorn, 21.86% also included Gumshoe, 20.63% also included Podscribe, 16.93% also included Chartable, 2.39% also included Podroll, 2.30% also included Podder, 2.14% also included Blubrry, 1.52% also included Spotify, 1.52% also included Magellan AI, 1.06% also included Adswizz, 0.84% also included ArtsAI, 0.63% also included Swap.fm, 0.61% also included Claritas, 0.28% also included Audiotakes, 0.21% also included Podkite, 0.17% also included CoHost Prefix, and 0.02% also included Feedpress.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "30.48%" >}}
2. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "8.90%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.56%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.47%" >}}
5. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "4.71%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.35%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.12%" >}}
8. {{< a "https://radiolaser.fr/" "Radio Laser" >}} {{< span "weak" "2.54%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.45%" >}}
10. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "1.97%" >}}
---

### 13. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.19% of new episodes in October, growing 5.99% from last month.

Of these, 39.23% had 5 other trackers, 23.30% had 6 other trackers, 15.64% had 4 other trackers, 7.39% had 2 other trackers, 7.21% had 7 other trackers, 4.40% had 3 other trackers, and 2.23% had one other tracker.

92.79% also included Podscribe, 72.67% also included Magellan AI, 64.57% also included Podtrac, 63.55% also included Chartable, 60.59% also included Podsights, 37.34% also included Adswizz, 32.70% also included Spotify, 28.64% also included ArtsAI, 15.67% also included Veritonic, 3.90% also included Podroll, 2.91% also included Podder, 2.23% also included Swap.fm, 0.84% also included OP3, 0.60% also included Gumshoe, 0.08% also included Podcorn, 0.05% also included Audiotakes, and 0.03% also included United Podcasters.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "39.26%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "30.53%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.51%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.10%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "5.92%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.01%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.86%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.21%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.18%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.13%" >}}
---

### 14. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.18% of new episodes in October, shrinking 0.21% from last month.

Of these, 26.08% had 5 other trackers, 18.63% had 6 other trackers, 18.40% had 7 other trackers, 14.93% had 4 other trackers, 11.55% had 3 other trackers, 7.88% had 2 other trackers, 1.62% had 8 other trackers, and 0.77% had one other tracker.

86.49% also included Podscribe, 77.67% also included Chartable, 67.86% also included Podsights, 64.48% also included Podtrac, 50.11% also included Magellan AI, 31.09% also included Claritas, 30.29% also included Spotify, 24.32% also included Audiotakes, 23.32% also included Adswizz, 20.99% also included Veritonic, 11.95% also included Podder, 2.90% also included Podroll, 1.96% also included Swap.fm, 1.25% also included OP3, 0.14% also included Gumshoe, and 0.03% also included United Podcasters.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "36.06%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "16.30%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "15.61%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "10.95%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.84%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "6.60%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.93%" >}}
8. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.94%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.63%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.14%" >}}
---

### 15. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.17% of new episodes in October, growing 35.66% from last month.

Of these, 34.86% had 3 other trackers, 26.41% had 2 other trackers, 16.40% had 4 other trackers, 14.74% had one other tracker, 2.86% had 6 other trackers, 2.83% had 5 other trackers, 1.01% had 7 other trackers, and 0.12% had 8 other trackers.

96.74% also included Chartable, 63.97% also included Podsights, 49.32% also included Podtrac, 32.37% also included Podscribe, 14.10% also included Podroll, 4.42% also included Adswizz, 4.12% also included Magellan AI, 2.61% also included Claritas, 2.12% also included ArtsAI, 1.54% also included Podcorn, 1.14% also included Podder, 1.01% also included OP3, 0.77% also included Spotify, 0.74% also included United Podcasters, 0.61% also included Audiotakes, 0.55% also included Gumshoe, 0.52% also included Veritonic, 0.28% also included Zencastr, and 0.15% also included CoHost Prefix.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "80.47%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "10.60%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.32%" >}}
4. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "2.52%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.35%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.77%" >}}
7. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.64%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "0.34%" >}}
---

### 16. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.14% of new episodes in October, growing 6.55% from last month.

Of these, 33.80% had 4 other trackers, 20.43% had 5 other trackers, 18.30% had 3 other trackers, 11.78% had 6 other trackers, 8.22% had 2 other trackers, 2.57% had one other tracker, and 2.25% had 7 other trackers.

85.47% also included Podscribe, 57.25% also included Podtrac, 53.01% also included Podsights, 51.52% also included Chartable, 41.30% also included Magellan AI, 30.98% also included ArtsAI, 26.52% also included Podder, 24.09% also included Spotify, 17.90% also included Adswizz, 2.93% also included Veritonic, 2.14% also included Podroll, 1.96% also included Gumshoe, 0.94% also included United Podcasters, 0.72% also included Swap.fm, 0.54% also included OP3, 0.18% also included Podcorn, 0.14% also included Blubrry, and 0.07% also included Claritas.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "32.14%" >}}
2. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "24.60%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "16.23%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "10.62%" >}}
5. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.57%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.03%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.96%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.67%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "1.05%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.07%" >}}
---

### 17. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.14% of new episodes in October, shrinking 6.60% from last month.

Of these, 15.77% had one other tracker, and 1.31% had 2 other trackers.

10.05% also included Blubrry, 3.39% also included Podtrac, 2.11% also included Chartable, 1.60% also included Podcorn, 0.84% also included Podsights, 0.36% also included Podscribe, and 0.04% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "57.32%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "7.87%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.88%" >}}
4. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.90%" >}}
5. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "2.59%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.37%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.86%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.82%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.35%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.31%" >}}
---

### 18. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.12% of new episodes in October, shrinking 2.30% from last month.

Of these, 36.88% had 5 other trackers, 14.52% had 4 other trackers, 12.73% had one other tracker, 12.73% had 3 other trackers, 10.77% had 2 other trackers, 4.98% had 6 other trackers, 0.41% had 9 other trackers, 0.20% had 8 other trackers, and 0.16% had 7 other trackers.

62.26% also included Podsights, 61.93% also included Podtrac, 55.08% also included Podscribe, 47.00% also included OP3, 45.17% also included Podcorn, 44.35% also included Chartable, 9.75% also included Spotify, 6.61% also included Magellan AI, 5.10% also included Podder, 3.88% also included Podroll, 2.69% also included CoHost Prefix, 2.20% also included Audiotakes, 1.39% also included Veritonic, 1.02% also included United Podcasters, 0.94% also included Adswizz, 0.94% also included Claritas, 0.73% also included Swap.fm, 0.20% also included ArtsAI, and 0.04% also included Podkite.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "47.41%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "26.76%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "17.46%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.16%" >}}
5. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.71%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.31%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.29%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.20%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.20%" >}}
10. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.20%" >}}
---

### 19. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.09% of new episodes in October, growing 25.96% from last month.

Of these, 2.37% had one other tracker.

2.37% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "41.59%" >}}
2. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "32.20%" >}}
3. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "21.57%" >}}
---

### 20. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.09% of new episodes in October, growing 5.34% from last month.

Of these, 30.71% had 7 other trackers, 23.73% had 6 other trackers, 14.01% had 4 other trackers, 11.27% had 5 other trackers, 8.59% had 2 other trackers, 6.44% had 3 other trackers, and 3.40% had 8 other trackers.

88.37% also included Podtrac, 84.97% also included Chartable, 80.62% also included Podsights, 75.13% also included Podscribe, 58.56% also included Magellan AI, 44.01% also included ArtsAI, 35.66% also included Claritas, 29.46% also included Spotify, 24.33% also included Adswizz, 4.83% also included Audiotakes, 2.50% also included Podder, 2.03% also included Gumshoe, 1.73% also included Podroll, 1.01% also included Swap.fm, and 0.24% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "66.61%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "20.16%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.58%" >}}
4. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.40%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.92%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.49%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.07%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.30%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.30%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.18%" >}}
---

### 21. [Firstory](https://firstory.me/)

Firstory was found on 0.06% of new episodes in October, shrinking 6.75% from last month.

Of these, 81.63% had one other tracker.

81.63% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.83%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.17%" >}}
---

### 22. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.01% of new episodes in October, growing 28.35% from last month.

Of these, 27.53% had 4 other trackers, 22.27% had 3 other trackers, 15.38% had 5 other trackers, 13.36% had one other tracker, 8.91% had 2 other trackers, 3.64% had 9 other trackers, and 2.83% had 6 other trackers.

89.47% also included Chartable, 70.45% also included Podsights, 66.40% also included Podtrac, 48.18% also included Podscribe, 26.72% also included Gumshoe, 13.77% also included Podroll, 6.88% also included Podder, 4.86% also included Podcorn, 3.64% also included OP3, 2.02% also included Swap.fm, 2.02% also included Adswizz, and 0.40% also included Magellan AI.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "69.23%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "8.10%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "6.88%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "5.26%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.45%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.24%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.02%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.81%" >}}
---

### 23. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in October, growing 6.21% from last month.

Of these, 23.44% had one other tracker, 18.23% had 3 other trackers, 14.06% had 5 other trackers, 10.94% had 4 other trackers, 8.33% had 2 other trackers, 5.21% had 6 other trackers, 2.08% had 8 other trackers, and 0.52% had 7 other trackers.

62.50% also included Chartable, 52.08% also included Podsights, 30.21% also included Podscribe, 22.92% also included Podtrac, 15.10% also included Podroll, 14.06% also included Magellan AI, 13.54% also included Audiotakes, 13.02% also included Gumshoe, 12.50% also included Swap.fm, 10.42% also included Podder, 4.69% also included Podcorn, 3.65% also included Spotify, 2.60% also included Adswizz, 2.08% also included Zencastr, 0.52% also included ArtsAI, and 0.52% also included Claritas.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "52.60%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "13.54%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.38%" >}}
4. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "8.85%" >}}
5. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "5.21%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.65%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.60%" >}}
8. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "2.08%" >}}
9. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.56%" >}}
10. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "0.52%" >}}
---

### 24. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in October, shrinking 7.58% from last month.

Of these, 29.44% had one other tracker, 11.11% had 2 other trackers, 4.44% had 5 other trackers, 0.56% had 3 other trackers, 0.56% had 6 other trackers, and 0.56% had 9 other trackers.

35.00% also included Chartable, 19.44% also included Podtrac, 8.89% also included Podsights, 7.22% also included Podcorn, 6.11% also included OP3, 5.00% also included Podder, 1.11% also included Podscribe, 0.56% also included Podroll, and 0.56% also included Gumshoe.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "35.00%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "18.33%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "14.44%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "10.56%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.67%" >}}
6. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "5.00%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "3.33%" >}}
8. {{< a "https://azure.microsoft.com/en-us/services/storage/blobs/" "Microsoft Azure Blob Storage" >}} {{< span "weak" "2.78%" >}}
9. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.78%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.11%" >}}
---

### 25. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in October, shrinking 7.75% from last month.

Of these, 10.90% had one other tracker, 9.62% had 2 other trackers, 3.21% had 5 other trackers, and 2.56% had 6 other trackers.

19.87% also included Podtrac, 16.03% also included Chartable, 11.54% also included Podsights, 5.77% also included Podscribe, 5.77% also included Swap.fm, and 2.56% also included United Podcasters.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.97%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "19.87%" >}}
3. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "14.74%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "10.90%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.77%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.77%" >}}
7. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "5.13%" >}}
8. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "1.92%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.92%" >}}
---

### 26. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in October, shrinking 27.98% from last month.

Of these, 23.81% had 2 other trackers, 20.63% had one other tracker, and 3.17% had 4 other trackers.

47.62% also included Chartable, 23.81% also included Podtrac, 6.35% also included Podcorn, and 3.17% also included Podscribe.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "38.10%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "19.05%" >}}
3. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "14.29%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.11%" >}}
5. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "6.35%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.35%" >}}
7. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "4.76%" >}}
---

### 27. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on <0.01% of new episodes in October, shrinking 44.88% from last month.

Of these, 55.56% had one other tracker, and 22.22% had 2 other trackers.

44.44% also included Chartable, 33.33% also included Podcorn, and 22.22% also included Podsights.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "55.56%" >}}
2. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "22.22%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "22.22%" >}}
---

### 28. [Glystn](https://glystn.com/)

Glystn was found on <0.01% of new episodes in October, growing 7.18% from last month.

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
