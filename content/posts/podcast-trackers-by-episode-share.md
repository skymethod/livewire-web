---
title: "Top Podcast Tracking Services by Episode Share (July 2024)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2024-07.png
date: 2024-08-01T11:49:00-05:00
lastmod: 2024-08-01T11:49:00-05:00
draft: false
rssrevision: 2024-07
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

We already did the work of analyzing _every single new podcast episode published_ (about 1.8 million in July 2024), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in July, how many
of them included one or more of these tracking services?  Some episodes had as many as *nine* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

---

### A special note for March/April 2024 {#spreaker}
_We now have a better signal of when Spreaker releases new episodes, so our crawlers are finding more, starting early-March. This more accurate view seems to have helped Podtrac and Adswizz the most in this month's share rankings._

### A special note for September/October 2023 {#s4p}
_We now have a better signal of when Spotify for Podcasters (formerly Anchor) podcasts release new episodes, so our crawlers are finding more, starting mid-September._

_October was the first full month where this new signal was incorporated for the entire month, so should be a good baseline going forward.  It's likely that we were undercounting S4P prior to this,
in general our goal is to observe and validate every change to every podcast._

_Higher share of new episodes on S4P (which typically do not have prefixes) leads to lower share overall for all prefixes over these two months, but should be stable going forward now that we have a more accurate baseline._

---

First, a quick chart of the top podcast tracking services over time, based on share of new episodes every month.

---

{{< graph trackershares "Top Podcast Tracking Services by New Episode Share" "height:500px">}}
Month	Podtrac	Chartable	Adswizz	Podsights	Blubrry	Podscribe	Podcorn	Podroll	Spotify	OP3	Claritas	ArtsAI	Podder	Feedpress	Gumshoe	Médiamétrie	Audiotakes	Veritonic	Swap.fm	Zencastr	Podkite	United Podcasters	CoHost Prefix	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	4.16	4.06	1.00	1.16	2.07		2.09							0.32		0.42													1.61
Oct 2021	4.05	4.09	1.01	1.20	2.11		2.13							0.34		0.54													1.61
Nov 2021	4.07	4.30	1.02	1.25	2.01		2.14							0.32		0.57													0.59
Dec 2021	4.06	4.42	1.24	1.19	1.57		2.27							0.19		0.59													
Jan 2022	4.11	4.45	1.41	1.21	1.56		2.31							0.16		0.63													
Feb 2022	4.15	4.48	1.44	1.25	1.53		2.38							0.17		0.58													
Mar 2022	4.37	4.72	1.51	1.34	1.56		2.40							0.17		0.53													
Apr 2022	4.44	4.71	1.49	1.33	1.55		2.33							0.16		0.51													
May 2022	4.49	4.87	1.58	1.41	1.48		2.26							0.17		0.56													
Jun 2022	4.75	5.10	1.77	1.54	1.50		2.06							0.21		0.62										0.02			
Jul 2022	4.70	5.10	1.89	1.50	1.50		2.16							0.25		0.54										0.02			
Aug 2022	4.83	5.26	2.08	1.73	1.51		2.45					0.10		0.20		0.41										0.01			
Sep 2022	7.53	5.40	2.26	1.74	1.49	0.02	2.45				0.01	0.09		0.21		0.52					0.01					0.02	0.02		
Oct 2022	8.24	5.48	2.35	1.81	1.61	0.07	2.51			0.03	0.02	0.10		0.18		0.50				0.01	0.01					0.02	0.04		
Nov 2022	8.11	5.62	2.37	2.03	1.62	0.15	2.43			0.04	0.03	0.10	0.01	0.18		0.50				0.01	0.01					0.02	0.05		
Dec 2022	8.01	5.54	2.32	1.81	1.61	0.03	2.05			0.05	0.02	0.05	0.04	0.18		0.49				0.01	0.01				0.01	0.02	0.05		
Jan 2023	7.85	5.56	2.35	1.88	1.61	0.20	2.15			0.07	0.06	0.10	0.11	0.18		0.54				0.01	0.01				0.01	0.02	0.06		
Feb 2023	7.58	5.51	2.29	1.92	1.62	0.21	2.30			0.07	0.07	0.10	0.11	0.19		0.49				0.01	0.01				0.01	0.02	0.06	0.03	
Mar 2023	7.79	5.53	2.25	2.03	1.53	0.21	2.22	0.04		0.08	0.07	0.11	0.11	0.18		0.45		0.04		0.01	0.01				0.01	0.02	0.06		
Apr 2023	7.66	5.43	2.26	2.00	1.67	0.21	2.20	0.06		0.09	0.07	0.11	0.15	0.17	0.08	0.45		0.05		0.01	0.01				0.01	0.01			
May 2023	7.58	5.59	2.27	2.04	1.67	0.24	2.28	0.09		0.09	0.08	0.11	0.15	0.19	0.07	0.45		0.05		0.01	0.01			0.01	0.01	0.01			
Jun 2023	8.22	5.83	2.39	2.23	1.64	0.26	1.86	0.10		0.09	0.07	0.12	0.15	0.19	0.08	0.51		0.05		0.01	0.01			0.01	0.01	0.01			
Jul 2023	8.60	5.95	2.38	2.52	1.53	0.27	1.17	0.14	0.01	0.08	0.07	0.11	0.14	0.18	0.06	0.55		0.06		0.01	0.01			0.01	0.01	0.01			
Aug 2023	9.19	6.43	2.72	2.76	1.58	0.36	1.23	0.16	0.03	0.11	0.08	0.12	0.15	0.17	0.07	0.53	0.04	0.07		0.01	0.01			0.02	0.01				
Sep 2023	8.46	5.77	2.49	2.47	1.39	0.37	1.10	0.13	0.05	0.10	0.10	0.12	0.15	0.16	0.07	0.58	0.05	0.06		0.01	0.01			0.02	0.01				
Oct 2023	7.90	5.54	2.29	2.28	1.37	0.39	1.11	0.12	0.08	0.10	0.10	0.12	0.16	0.16	0.08	0.50	0.05	0.06		0.02	0.01			0.03	0.01				
Nov 2023	7.65	5.59	2.25	2.33	1.45	0.47	1.14	0.12	0.11	0.13	0.11	0.12	0.16	0.17	0.10	0.33	0.06	0.06		0.01	0.01			0.03					
Dec 2023	7.48	5.60	2.20	2.19	1.53	0.54	1.12	0.12	0.12	0.11	0.11	0.12	0.16	0.16	0.09	0.33	0.06	0.06		0.01	0.01			0.03					
Jan 2024	7.64	5.61	2.37	2.21	1.55	0.65	1.17	0.11	0.15	0.13	0.12	0.14	0.16	0.17	0.10	0.25	0.08	0.06		0.01	0.01	0.01		0.01					
Feb 2024	7.69	5.58	2.38	2.22	1.52	0.69	1.21	0.12	0.22	0.16	0.13	0.13	0.17	0.17	0.11	0.22	0.09	0.06		0.01	0.01	0.01							
Mar 2024	9.01	5.46	2.53	2.19	1.54	0.69	1.14	0.12	0.25	0.14	0.14	0.12	0.16	0.16	0.10	0.22	0.09	0.06		0.01	0.01	0.01							
Apr 2024	10.78	5.47	2.53	2.16	1.51	0.73	1.24	0.34	0.27	0.18	0.15	0.13	0.17	0.15	0.11	0.19	0.07	0.07		0.01	0.01	0.01	0.01						
May 2024	11.59	5.63	2.75	2.24	1.50	0.83	1.20	0.36	0.30	0.18	0.15	0.14	0.16	0.15	0.11	0.09	0.06	0.07		0.01	0.01	0.01	0.01						
Jun 2024	11.54	6.06	2.88	2.34	1.52	0.91	0.71	0.37	0.32	0.20	0.16	0.16	0.15	0.15	0.11	0.10	0.07	0.07	0.03	0.01	0.01	0.01	0.01						
Jul 2024	12.34	6.80	2.83	2.45	1.65	1.01	0.71	0.43	0.34	0.20	0.18	0.17	0.15	0.15	0.12	0.09	0.09	0.07	0.06	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

{{< a "https://analytics.podtrac.com/" "Podtrac" >}} and {{< a "https://chartable.com/" "Chartable" >}} are the clear top two trackers of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast Tracking Services by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Adswizz	Podsights	Blubrry	Podscribe	Podcorn	Podroll	Spotify	OP3	Claritas	ArtsAI	Podder	Feedpress	Gumshoe	Médiamétrie	Audiotakes	Veritonic	Swap.fm	Zencastr	Podkite	United Podcasters	CoHost Prefix	Voxalyze	Glystn	Zippycast	Gumball	Vpixl	FeedBurner
Sep 2021	1.00	1.16	2.07		2.09							0.32		0.42													1.61
Oct 2021	1.01	1.20	2.11		2.13							0.34		0.54													1.61
Nov 2021	1.02	1.25	2.01		2.14							0.32		0.57													0.59
Dec 2021	1.24	1.19	1.57		2.27							0.19		0.59													
Jan 2022	1.41	1.21	1.56		2.31							0.16		0.63													
Feb 2022	1.44	1.25	1.53		2.38							0.17		0.58													
Mar 2022	1.51	1.34	1.56		2.40							0.17		0.53													
Apr 2022	1.49	1.33	1.55		2.33							0.16		0.51													
May 2022	1.58	1.41	1.48		2.26							0.17		0.56													
Jun 2022	1.77	1.54	1.50		2.06							0.21		0.62										0.02			
Jul 2022	1.89	1.50	1.50		2.16							0.25		0.54										0.02			
Aug 2022	2.08	1.73	1.51		2.45					0.10		0.20		0.41										0.01			
Sep 2022	2.26	1.74	1.49	0.02	2.45				0.01	0.09		0.21		0.52					0.01					0.02	0.02		
Oct 2022	2.35	1.81	1.61	0.07	2.51			0.03	0.02	0.10		0.18		0.50				0.01	0.01					0.02	0.04		
Nov 2022	2.37	2.03	1.62	0.15	2.43			0.04	0.03	0.10	0.01	0.18		0.50				0.01	0.01					0.02	0.05		
Dec 2022	2.32	1.81	1.61	0.03	2.05			0.05	0.02	0.05	0.04	0.18		0.49				0.01	0.01				0.01	0.02	0.05		
Jan 2023	2.35	1.88	1.61	0.20	2.15			0.07	0.06	0.10	0.11	0.18		0.54				0.01	0.01				0.01	0.02	0.06		
Feb 2023	2.29	1.92	1.62	0.21	2.30			0.07	0.07	0.10	0.11	0.19		0.49				0.01	0.01				0.01	0.02	0.06	0.03	
Mar 2023	2.25	2.03	1.53	0.21	2.22	0.04		0.08	0.07	0.11	0.11	0.18		0.45		0.04		0.01	0.01				0.01	0.02	0.06		
Apr 2023	2.26	2.00	1.67	0.21	2.20	0.06		0.09	0.07	0.11	0.15	0.17	0.08	0.45		0.05		0.01	0.01				0.01	0.01			
May 2023	2.27	2.04	1.67	0.24	2.28	0.09		0.09	0.08	0.11	0.15	0.19	0.07	0.45		0.05		0.01	0.01			0.01	0.01	0.01			
Jun 2023	2.39	2.23	1.64	0.26	1.86	0.10		0.09	0.07	0.12	0.15	0.19	0.08	0.51		0.05		0.01	0.01			0.01	0.01	0.01			
Jul 2023	2.38	2.52	1.53	0.27	1.17	0.14	0.01	0.08	0.07	0.11	0.14	0.18	0.06	0.55		0.06		0.01	0.01			0.01	0.01	0.01			
Aug 2023	2.72	2.76	1.58	0.36	1.23	0.16	0.03	0.11	0.08	0.12	0.15	0.17	0.07	0.53	0.04	0.07		0.01	0.01			0.02	0.01				
Sep 2023	2.49	2.47	1.39	0.37	1.10	0.13	0.05	0.10	0.10	0.12	0.15	0.16	0.07	0.58	0.05	0.06		0.01	0.01			0.02	0.01				
Oct 2023	2.29	2.28	1.37	0.39	1.11	0.12	0.08	0.10	0.10	0.12	0.16	0.16	0.08	0.50	0.05	0.06		0.02	0.01			0.03	0.01				
Nov 2023	2.25	2.33	1.45	0.47	1.14	0.12	0.11	0.13	0.11	0.12	0.16	0.17	0.10	0.33	0.06	0.06		0.01	0.01			0.03					
Dec 2023	2.20	2.19	1.53	0.54	1.12	0.12	0.12	0.11	0.11	0.12	0.16	0.16	0.09	0.33	0.06	0.06		0.01	0.01			0.03					
Jan 2024	2.37	2.21	1.55	0.65	1.17	0.11	0.15	0.13	0.12	0.14	0.16	0.17	0.10	0.25	0.08	0.06		0.01	0.01	0.01		0.01					
Feb 2024	2.38	2.22	1.52	0.69	1.21	0.12	0.22	0.16	0.13	0.13	0.17	0.17	0.11	0.22	0.09	0.06		0.01	0.01	0.01							
Mar 2024	2.53	2.19	1.54	0.69	1.14	0.12	0.25	0.14	0.14	0.12	0.16	0.16	0.10	0.22	0.09	0.06		0.01	0.01	0.01							
Apr 2024	2.53	2.16	1.51	0.73	1.24	0.34	0.27	0.18	0.15	0.13	0.17	0.15	0.11	0.19	0.07	0.07		0.01	0.01	0.01	0.01						
May 2024	2.75	2.24	1.50	0.83	1.20	0.36	0.30	0.18	0.15	0.14	0.16	0.15	0.11	0.09	0.06	0.07		0.01	0.01	0.01	0.01						
Jun 2024	2.88	2.34	1.52	0.91	0.71	0.37	0.32	0.20	0.16	0.16	0.15	0.15	0.11	0.10	0.07	0.07	0.03	0.01	0.01	0.01	0.01						
Jul 2024	2.83	2.45	1.65	1.01	0.71	0.43	0.34	0.20	0.18	0.17	0.15	0.15	0.12	0.09	0.09	0.07	0.06	0.01	0.01	0.01	0.01						
{{< /graph >}}

---

### Overall

At least one tracker was found on 21.14% of new episodes in July, growing 6.98% from last month.

For episodes that used at least one tracker, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "34.78%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.03%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.90%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.53%" >}}
5. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "2.98%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.89%" >}}
7. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.12%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.80%" >}}
9. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.51%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.42%" >}}
---
### Individual Service Rankings

And now, the full list of individual podcast analytics services ordered by new episodes published during the month of July 2024.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 12.34% of new episodes in July, growing 6.92% from last month.

Of these, 14.93% had one other tracker, 11.51% had 2 other trackers, 2.34% had 3 other trackers, 1.03% had 4 other trackers, 0.98% had 5 other trackers, 0.39% had 6 other trackers, 0.26% had 7 other trackers, and 0.04% had 8 other trackers.

21.13% also included Chartable, 12.78% also included Podsights, 5.66% also included Podscribe, 5.15% also included Adswizz, 2.74% also included Podroll, 1.73% also included Magellan AI, 1.71% also included Podcorn, 1.65% also included Spotify, 0.92% also included Claritas, 0.92% also included ArtsAI, 0.87% also included OP3, 0.74% also included Podder, 0.56% also included Gumshoe, 0.52% also included Veritonic, 0.44% also included Audiotakes, 0.37% also included Blubrry, 0.29% also included Swap.fm, 0.04% also included Feedpress, 0.03% also included CoHost Prefix, 0.02% also included Podkite, 0.02% also included Médiamétrie, 0.02% also included United Podcasters, 0.01% also included Zencastr, and 0.01% also included AdBarker.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "59.29%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "12.07%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.08%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.27%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.78%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.08%" >}}
7. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "1.40%" >}}
8. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.34%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.34%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.00%" >}}
---

### Spotify ([Chartable, Podsights](https://newsroom.spotify.com/2022-02-16/spotify-acquires-podsights-and-chartable-to-advance-podcast-measurement-for-advertisers-and-insights-for-publishers/), and [Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/))

At least one Spotify tracker was found on 7.53% of new episodes in July, growing 11.63% from last month.

Of these, 40.05% also included Podtrac, 9.74% also included Podscribe, 6.39% also included Adswizz, 4.08% also included Magellan AI, 2.41% also included Podcorn, 2.15% also included Claritas, 2.09% also included ArtsAI, 2.08% also included Podroll, 1.53% also included Podder, 1.32% also included Gumshoe, 1.26% also included OP3, 1.12% also included Audiotakes, 0.96% also included Veritonic, 0.83% also included Swap.fm, 0.71% also included Firstory, 0.32% also included Blubrry, 0.09% also included United Podcasters, 0.07% also included CoHost Prefix, 0.06% also included Podkite, 0.03% also included Zencastr, 0.03% also included AdBarker, 0.03% also included Feedpress, <0.01% also included Voxalyze, and <0.01% also included Glystn.

For episodes that used at least one Spotify tracker, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "29.72%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "27.87%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.39%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.63%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.23%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.80%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.50%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.37%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.25%" >}}
10. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.10%" >}}
---

### 2. [Chartable by Spotify](https://chartable.com/)

Chartable was found on 6.80% of new episodes in July, growing 12.23% from last month.

Of these, 26.42% had one other tracker, 18.46% had 2 other trackers, 4.48% had 3 other trackers, 2.02% had 4 other trackers, 1.65% had 5 other trackers, 0.86% had 6 other trackers, 0.40% had 7 other trackers, and 0.07% had 8 other trackers.

38.35% also included Podtrac, 26.02% also included Podsights, 8.30% also included Podscribe, 5.81% also included Adswizz, 3.98% also included Spotify, 3.85% also included Magellan AI, 2.20% also included Podroll, 2.12% also included Claritas, 2.00% also included Podcorn, 2.00% also included ArtsAI, 1.46% also included Podder, 0.90% also included Swap.fm, 0.88% also included Veritonic, 0.84% also included Gumshoe, 0.82% also included OP3, 0.78% also included Firstory, 0.69% also included Audiotakes, 0.28% also included Blubrry, 0.10% also included United Podcasters, 0.08% also included CoHost Prefix, 0.07% also included Podkite, 0.03% also included AdBarker, 0.03% also included Feedpress, 0.02% also included Zencastr, <0.01% also included Voxalyze, and <0.01% also included Glystn.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "29.92%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "25.93%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.36%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.91%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "4.39%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "4.12%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.50%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.47%" >}}
9. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "2.33%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.17%" >}}
---

### 3. [Adswizz by Pandora](https://www.adswizz.com/audiomax/)

Adswizz was found on 2.83% of new episodes in July, shrinking 1.86% from last month.

Of these, 17.59% had one other tracker, 12.46% had 2 other trackers, 2.69% had 3 other trackers, 0.64% had 4 other trackers, 0.46% had 7 other trackers, 0.37% had 5 other trackers, 0.32% had 6 other trackers, and 0.13% had 8 other trackers.

22.49% also included Podtrac, 13.97% also included Chartable, 9.71% also included Podroll, 6.09% also included Podsights, 2.34% also included Podscribe, 1.22% also included ArtsAI, 1.14% also included Blubrry, 1.07% also included Claritas, 0.92% also included Spotify, 0.77% also included Magellan AI, 0.64% also included Veritonic, 0.29% also included Podcorn, 0.21% also included Audiotakes, 0.10% also included Podder, 0.05% also included Gumshoe, 0.04% also included Swap.fm, 0.02% also included OP3, and 0.02% also included United Podcasters.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "43.92%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "11.32%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "8.21%" >}}
4. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "7.93%" >}}
5. {{< a "https://www.nrjgroup.fr/" "NRJ-Group" >}} {{< span "weak" "6.87%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.18%" >}}
7. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "4.91%" >}}
8. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "1.97%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.32%" >}}
10. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.08%" >}}
---

### 4. [Podsights by Spotify](https://podsights.com/)

Podsights was found on 2.45% of new episodes in July, growing 4.51% from last month.

Of these, 36.30% had 2 other trackers, 30.64% had one other tracker, 10.87% had 3 other trackers, 5.77% had 4 other trackers, 5.71% had 5 other trackers, 2.48% had 6 other trackers, 1.14% had 7 other trackers, and 0.18% had 8 other trackers.

72.24% also included Chartable, 64.38% also included Podtrac, 21.66% also included Podscribe, 10.83% also included Magellan AI, 7.03% also included Adswizz, 5.83% also included Claritas, 4.99% also included ArtsAI, 3.48% also included Podder, 3.36% also included Spotify, 2.76% also included Gumshoe, 2.73% also included Podcorn, 2.69% also included Podroll, 2.64% also included Audiotakes, 2.44% also included Veritonic, 2.33% also included OP3, 1.63% also included Swap.fm, 0.30% also included Blubrry, 0.18% also included United Podcasters, 0.14% also included CoHost Prefix, 0.09% also included Podkite, 0.05% also included Feedpress, 0.04% also included Zencastr, and 0.01% also included Voxalyze.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "57.45%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "25.17%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.46%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.05%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "2.38%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.31%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.21%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.10%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.09%" >}}
10. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.99%" >}}
---

### 5. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.65% of new episodes in July, growing 8.90% from last month.

Of these, 5.93% had one other tracker, 0.79% had 2 other trackers, 0.11% had 3 other trackers, 0.08% had 4 other trackers, 0.03% had 6 other trackers, and 0.01% had 5 other trackers.

2.80% also included Podtrac, 1.96% also included Adswizz, 1.14% also included Chartable, 0.98% also included Feedpress, 0.45% also included Podsights, 0.33% also included OP3, 0.25% also included Podcorn, 0.23% also included Podscribe, 0.06% also included Spotify, 0.05% also included Magellan AI, 0.05% also included Podder, 0.03% also included Podroll, 0.01% also included Audiotakes, 0.01% also included Veritonic, and 0.01% also included ArtsAI.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "38.19%" >}}
2. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "10.82%" >}}
3. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "6.97%" >}}
4. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "3.28%" >}}
5. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.03%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.18%" >}}
7. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "1.75%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.61%" >}}
9. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.18%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.10%" >}}
---

### 6. [Podscribe](https://podscribe.com/blog/impression-verification-mb45x)

Podscribe was found on 1.01% of new episodes in July, growing 11.79% from last month.

Of these, 24.59% had one other tracker, 18.24% had 3 other trackers, 17.16% had 2 other trackers, 13.63% had 5 other trackers, 12.56% had 4 other trackers, 6.03% had 6 other trackers, 3.31% had 7 other trackers, and 0.38% had 8 other trackers.

68.91% also included Podtrac, 55.65% also included Chartable, 52.31% also included Podsights, 26.00% also included Magellan AI, 15.28% also included Claritas, 14.64% also included Spotify, 14.20% also included ArtsAI, 8.43% also included Audiotakes, 7.39% also included Podcorn, 6.52% also included Adswizz, 5.87% also included Veritonic, 5.47% also included Gumshoe, 3.93% also included Podder, 3.78% also included OP3, 3.39% also included Podroll, 1.86% also included Swap.fm, 0.37% also included Blubrry, 0.28% also included United Podcasters, 0.05% also included Feedpress, 0.04% also included Zencastr, 0.02% also included CoHost Prefix, and 0.01% also included AdBarker.

For episodes that used Podscribe, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "50.52%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "17.72%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.60%" >}}
4. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.53%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.48%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.50%" >}}
7. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "3.44%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.28%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.59%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.40%" >}}
---

### 7. [Podcorn by Audacy/Entercom](https://podcorn.com/)

Podcorn was found on 0.71% of new episodes in July, growing 0.05% from last month.

Of these, 23.53% had one other tracker, 7.08% had 2 other trackers, 5.17% had 3 other trackers, 4.55% had 5 other trackers, 1.55% had 4 other trackers, 0.76% had 6 other trackers, 0.13% had 8 other trackers, and 0.04% had 7 other trackers.

29.77% also included Podtrac, 19.14% also included Chartable, 10.55% also included Podscribe, 9.41% also included Podsights, 7.18% also included OP3, 6.99% also included Gumshoe, 1.16% also included Adswizz, 0.86% also included Podder, 0.80% also included Podroll, 0.57% also included Blubrry, 0.33% also included Spotify, 0.31% also included Magellan AI, 0.31% also included Swap.fm, 0.22% also included Feedpress, 0.13% also included CoHost Prefix, 0.06% also included AdBarker, 0.06% also included United Podcasters, 0.06% also included Audiotakes, 0.04% also included Podkite, and 0.03% also included Voxalyze.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "20.17%" >}}
2. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "14.86%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "13.66%" >}}
4. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "12.78%" >}}
5. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "9.22%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "9.14%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.78%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "2.88%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.22%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.21%" >}}
---

### 8. [Podroll](https://podroll.fm/)

Podroll was found on 0.43% of new episodes in July, growing 13.91% from last month.

Of these, 74.92% had 2 other trackers, 9.40% had 3 other trackers, 8.88% had one other tracker, 2.36% had 4 other trackers, 1.32% had 5 other trackers, 0.90% had 6 other trackers, 0.60% had 7 other trackers, and 0.21% had 8 other trackers.

79.54% also included Podtrac, 64.52% also included Adswizz, 35.19% also included Chartable, 15.48% also included Podsights, 8.09% also included Podscribe, 1.65% also included Magellan AI, 1.59% also included Claritas, 1.52% also included Podder, 1.34% also included Podcorn, 1.28% also included Gumshoe, 1.05% also included OP3, 0.82% also included Swap.fm, 0.67% also included ArtsAI, 0.65% also included Spotify, 0.29% also included United Podcasters, 0.26% also included CoHost Prefix, 0.16% also included Audiotakes, and 0.11% also included Blubrry.

For episodes that used Podroll, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "63.95%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "19.16%" >}}
3. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.14%" >}}
4. {{< a "https://www.prx.org/" "PRX" >}} {{< span "weak" "2.69%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.28%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.22%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "0.99%" >}}
8. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "0.45%" >}}
9. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.45%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.44%" >}}
---

### 9. [Spotify Ad Analytics](https://ads.spotify.com/en-US/news-and-insights/introducing-spotify-ad-analytics/)

Spotify was found on 0.34% of new episodes in July, growing 6.31% from last month.

Of these, 45.82% had 2 other trackers, 15.55% had one other tracker, 12.32% had 3 other trackers, 7.69% had 7 other trackers, 7.19% had 6 other trackers, 5.69% had 4 other trackers, 2.60% had 5 other trackers, and 1.14% had 8 other trackers.

80.71% also included Chartable, 60.88% also included Podtrac, 44.27% also included Podscribe, 24.55% also included Podsights, 19.85% also included Magellan AI, 16.32% also included ArtsAI, 8.18% also included Claritas, 7.77% also included Adswizz, 7.54% also included Veritonic, 7.49% also included Audiotakes, 3.98% also included Gumshoe, 1.38% also included Podder, 0.82% also included Podroll, 0.77% also included OP3, 0.71% also included Podcorn, 0.45% also included Swap.fm, 0.29% also included Blubrry, and 0.07% also included United Podcasters.

For episodes that used Spotify, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "51.19%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "13.67%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "8.29%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.33%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.17%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "3.49%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.39%" >}}
8. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.89%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.56%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.48%" >}}
---

### 10. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.33% of new episodes in July, growing 12.21% from last month.

Of these, 26.15% had 5 other trackers, 23.84% had 4 other trackers, 13.86% had 6 other trackers, 13.72% had 3 other trackers, 8.64% had 7 other trackers, 7.19% had 2 other trackers, 4.70% had one other tracker, and 1.10% had 8 other trackers.

80.81% also included Podsights, 80.31% also included Podscribe, 79.85% also included Chartable, 64.98% also included Podtrac, 38.14% also included Claritas, 24.18% also included ArtsAI, 20.27% also included Spotify, 14.08% also included Veritonic, 12.00% also included Podder, 10.68% also included Audiotakes, 6.65% also included Adswizz, 2.14% also included Podroll, 1.99% also included Gumshoe, 1.03% also included Swap.fm, 0.67% also included Podcorn, 0.57% also included United Podcasters, 0.26% also included Blubrry, and 0.15% also included OP3.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "64.62%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.36%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "7.01%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "6.76%" >}}
5. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "6.26%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.99%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "0.70%" >}}
8. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.27%" >}}
9. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "0.22%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.19%" >}}
---

### 11. [OP3 (the Open Podcast Prefix Project)](https://op3.dev/)

OP3 was found on 0.20% of new episodes in July, growing 3.73% from last month.

Of these, 24.11% had one other tracker, 15.64% had 5 other trackers, 9.85% had 2 other trackers, 8.29% had 3 other trackers, 5.24% had 4 other trackers, 2.75% had 6 other trackers, and 0.33% had 8 other trackers.

52.59% also included Podtrac, 28.10% also included Podsights, 27.32% also included Chartable, 25.13% also included Podcorn, 24.49% also included Gumshoe, 18.86% also included Podscribe, 2.77% also included Podder, 2.72% also included Blubrry, 2.19% also included Podroll, 1.28% also included Spotify, 0.31% also included CoHost Prefix, 0.28% also included Adswizz, 0.25% also included Magellan AI, 0.19% also included ArtsAI, 0.19% also included Swap.fm, 0.14% also included Feedpress, 0.11% also included Claritas, and 0.08% also included Audiotakes.

For episodes that used OP3, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "33.81%" >}}
2. {{< a "https://www.houstonpublicmedia.org/" "Houston Public Media" >}} {{< span "weak" "7.96%" >}}
3. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.38%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "4.52%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.19%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.77%" >}}
7. {{< a "https://podhome.fm/" "Podhome" >}} {{< span "weak" "2.88%" >}}
8. {{< a "https://radiolaser.fr/" "Radio Laser" >}} {{< span "weak" "2.52%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.36%" >}}
10. {{< a "https://vodio.fr/" "Vodio" >}} {{< span "weak" "2.16%" >}}
---

### 12. [Claritas](https://claritas.com/podcast-attribution-audience-identification/)

Claritas was found on 0.18% of new episodes in July, growing 9.38% from last month.

Of these, 33.30% had 5 other trackers, 21.84% had 6 other trackers, 18.33% had 4 other trackers, 9.47% had 7 other trackers, 5.76% had 2 other trackers, 5.41% had 3 other trackers, and 3.64% had one other tracker.

87.12% also included Podscribe, 81.01% also included Chartable, 80.31% also included Podsights, 70.40% also included Magellan AI, 63.98% also included Podtrac, 29.22% also included ArtsAI, 16.97% also included Adswizz, 15.70% also included Veritonic, 15.42% also included Spotify, 3.80% also included Podroll, 3.23% also included Podder, 1.11% also included Swap.fm, 0.16% also included Gumshoe, and 0.13% also included OP3.

For episodes that used Claritas, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "56.13%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.03%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "9.84%" >}}
4. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8.33%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "5.76%" >}}
6. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "5.41%" >}}
7. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.01%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.73%" >}}
9. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.32%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.16%" >}}
---

### 13. [ArtsAI](https://artsai.com/)

ArtsAI was found on 0.17% of new episodes in July, growing 5.62% from last month.

Of these, 23.33% had 5 other trackers, 19.04% had 7 other trackers, 17.62% had 6 other trackers, 15.18% had 3 other trackers, 12.82% had 4 other trackers, 8.39% had 2 other trackers, 2.16% had 8 other trackers, and 1.22% had one other tracker.

86.51% also included Podscribe, 81.60% also included Chartable, 73.45% also included Podsights, 67.97% also included Podtrac, 47.68% also included Magellan AI, 32.87% also included Spotify, 31.21% also included Claritas, 22.56% also included Veritonic, 20.76% also included Adswizz, 15.69% also included Audiotakes, 3.35% also included Podder, 1.93% also included Swap.fm, 1.72% also included Podroll, 0.24% also included OP3, 0.17% also included Gumshoe, and 0.07% also included Blubrry.

For episodes that used ArtsAI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "37.67%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "15.93%" >}}
3. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "12.72%" >}}
4. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.89%" >}}
5. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "9.94%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "7.34%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "1.62%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.39%" >}}
9. {{< a "https://soundstack.com/" "SoundStack" >}} {{< span "weak" "1.08%" >}}
10. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "0.98%" >}}
---

### 14. [Podder](https://www.podderapp.com/)

Podder was found on 0.15% of new episodes in July, growing 0.42% from last month.

Of these, 18.11% had one other tracker, 17.08% had 3 other trackers, 14.67% had 5 other trackers, 13.31% had 4 other trackers, 13.17% had 2 other trackers, 4.46% had 6 other trackers, 1.24% had 7 other trackers, and 0.44% had 8 other trackers.

64.52% also included Chartable, 59.29% also included Podtrac, 55.45% also included Podsights, 25.86% also included Podscribe, 25.60% also included Magellan AI, 4.21% also included Podroll, 3.95% also included Podcorn, 3.73% also included Claritas, 3.66% also included OP3, 3.62% also included ArtsAI, 3.00% also included Spotify, 2.63% also included Gumshoe, 1.83% also included Adswizz, 1.06% also included Podkite, 0.95% also included Audiotakes, 0.55% also included Blubrry, 0.55% also included United Podcasters, 0.40% also included CoHost Prefix, and 0.40% also included Veritonic.

For episodes that used Podder, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "62.22%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "9.62%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "7.43%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.23%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "3.26%" >}}
6. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.89%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.60%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.38%" >}}
9. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "1.39%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.99%" >}}
---

### 15. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.15% of new episodes in July, shrinking 2.26% from last month.

Of these, 15.18% had one other tracker, 1.09% had 2 other trackers, and 0.15% had 3 other trackers.

10.78% also included Blubrry, 3.34% also included Podtrac, 1.31% also included Chartable, 1.05% also included Podcorn, 0.79% also included Podsights, 0.34% also included Podscribe, and 0.19% also included OP3.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "56.72%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "9.54%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "4.81%" >}}
4. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.79%" >}}
5. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "2.55%" >}}
6. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.37%" >}}
7. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "1.99%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.65%" >}}
9. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.98%" >}}
10. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "0.83%" >}}
---

### 16. [Gumshoe](https://gumball.fm/help/podcasters/getting-started-with-gumball/360008116394#gumshoe-gumballs-campaign-tracking-solution)

Gumshoe was found on 0.12% of new episodes in July, growing 6.60% from last month.

Of these, 31.55% had 5 other trackers, 15.54% had 4 other trackers, 13.66% had 2 other trackers, 13.66% had 3 other trackers, 11.06% had one other tracker, 4.28% had 6 other trackers, and 0.58% had 8 other trackers.

59.45% also included Podtrac, 57.77% also included Podsights, 48.68% also included Chartable, 47.43% also included Podscribe, 42.47% also included OP3, 42.42% also included Podcorn, 11.40% also included Spotify, 5.58% also included Magellan AI, 4.67% also included Podroll, 3.46% also included Podder, 2.16% also included Audiotakes, 1.20% also included Adswizz, 1.06% also included United Podcasters, 0.58% also included Swap.fm, 0.53% also included CoHost Prefix, 0.24% also included ArtsAI, 0.24% also included Claritas, and 0.24% also included Veritonic.

For episodes that used Gumshoe, here are the top underlying podcast hosts:

1. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "42.71%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "28.19%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "18.57%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.96%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.44%" >}}
6. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "1.25%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.63%" >}}
8. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "0.34%" >}}
9. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.34%" >}}
10. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.24%" >}}
---

### 17. [Médiamétrie](https://www.mediametrie.fr/en/estat-podcast)

Médiamétrie was found on 0.09% of new episodes in July, shrinking 9.37% from last month.

Of these, 2.67% had one other tracker.

2.67% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "36.93%" >}}
2. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "34.51%" >}}
3. {{< a "https://www.mc-doualiya.com/" "Monte Carlo Doualiya" >}} {{< span "weak" "24.20%" >}}
---

### 18. [Audiotakes](https://audiotakes.net/)

Audiotakes was found on 0.09% of new episodes in July, growing 26.41% from last month.

Of these, 29.37% had 4 other trackers, 28.02% had 3 other trackers, 16.61% had 5 other trackers, 12.94% had 6 other trackers, 5.86% had 2 other trackers, 2.87% had one other tracker, and 1.10% had 7 other trackers.

92.67% also included Podscribe, 70.21% also included Podsights, 58.67% also included Podtrac, 50.61% also included Chartable, 38.03% also included Magellan AI, 28.33% also included ArtsAI, 27.23% also included Spotify, 6.35% also included Adswizz, 4.15% also included Veritonic, 2.75% also included Gumshoe, 1.65% also included United Podcasters, 1.59% also included Podder, 0.73% also included Podroll, 0.73% also included Swap.fm, 0.43% also included Podcorn, 0.18% also included Blubrry, and 0.18% also included OP3.

For episodes that used Audiotakes, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "36.69%" >}}
2. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "32.72%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "14.47%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.82%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "3.97%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "2.99%" >}}
7. {{< a "https://library.substack.com/p/how-to-use-substack-for-podcasts" "Substack" >}} {{< span "weak" "2.01%" >}}
8. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.47%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.79%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.06%" >}}
---

### 19. [Veritonic](https://www.veritonic.com/)

Veritonic was found on 0.07% of new episodes in July, growing 8.16% from last month.

Of these, 33.97% had 7 other trackers, 20.82% had 6 other trackers, 13.45% had 4 other trackers, 10.87% had 5 other trackers, 7.29% had 3 other trackers, 6.61% had 2 other trackers, and 4.86% had 8 other trackers.

86.17% also included Podtrac, 80.85% also included Chartable, 80.55% also included Podsights, 80.40% also included Podscribe, 62.39% also included Magellan AI, 50.68% also included ArtsAI, 37.69% also included Claritas, 34.12% also included Spotify, 24.39% also included Adswizz, 5.17% also included Audiotakes, 0.99% also included Swap.fm, 0.84% also included Podder, 0.38% also included Gumshoe, and 0.23% also included Blubrry.

For episodes that used Veritonic, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "63.07%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "20.44%" >}}
3. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "4.18%" >}}
4. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "4.10%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.50%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "2.74%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "0.91%" >}}
8. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "0.38%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.38%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.30%" >}}
---

### 20. [Firstory](https://firstory.me/)

Firstory was found on 0.07% of new episodes in July, growing 3.95% from last month.

Of these, 80.73% had one other tracker.

80.73% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "100.00%" >}}
---

### 21. [Swap.fm](https://swap.fm/)

Swap.fm was found on 0.06% of new episodes in July, growing 85.91% from last month.

Of these, 31.73% had 2 other trackers, 25.37% had 3 other trackers, 16.30% had one other tracker, 15.43% had 4 other trackers, 3.14% had 5 other trackers, 3.14% had 6 other trackers, 2.62% had 7 other trackers, and 0.35% had 8 other trackers.

94.68% also included Chartable, 61.81% also included Podsights, 56.32% also included Podtrac, 29.21% also included Podscribe, 5.41% also included Podroll, 5.23% also included Magellan AI, 4.97% also included ArtsAI, 3.40% also included Podcorn, 3.05% also included Claritas, 2.35% also included Spotify, 1.92% also included Adswizz, 1.13% also included Veritonic, 1.05% also included Audiotakes, 1.05% also included United Podcasters, 1.05% also included Gumshoe, and 0.61% also included OP3.

For episodes that used Swap.fm, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "83.17%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "11.42%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "3.05%" >}}
4. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "1.92%" >}}
5. {{< a "https://www.livewriters.com/" "LiveWriters" >}} {{< span "weak" "0.44%" >}}
---

### 22. [Zencastr](https://zencastr.com/)

Zencastr was found on 0.01% of new episodes in July, growing 6.76% from last month.

Of these, 11.83% had one other tracker, 8.88% had 2 other trackers, 2.37% had 4 other trackers, and 2.37% had 5 other trackers.

17.16% also included Chartable, 15.98% also included Podtrac, 10.65% also included Podsights, 4.73% also included Podscribe, and 2.37% also included United Podcasters.

For episodes that used Zencastr, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.32%" >}}
2. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "19.53%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "13.61%" >}}
4. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "11.24%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.33%" >}}
6. {{< a "https://www.blogtalkradio.com/" "Blog Talk Radio" >}} {{< span "weak" "4.73%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "4.73%" >}}
8. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "2.37%" >}}
9. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "2.37%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.78%" >}}
---

### 23. [Podkite](https://docs.podkite.com/download-analytics/setup/)

Podkite was found on 0.01% of new episodes in July, growing 8.92% from last month.

Of these, 29.76% had one other tracker, 14.29% had 4 other trackers, 6.55% had 2 other trackers, 2.98% had 5 other trackers, and 2.38% had 3 other trackers.

47.62% also included Chartable, 31.55% also included Podtrac, 22.62% also included Podsights, 17.26% also included Podder, and 2.98% also included Podcorn.

For episodes that used Podkite, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "33.33%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "26.19%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "11.31%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "8.93%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.95%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.36%" >}}
7. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "4.76%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.57%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "0.60%" >}}
---

### 24. [United Podcasters](https://up.audio/)

United Podcasters was found on 0.01% of new episodes in July, growing 8.40% from last month.

Of these, 27.88% had one other tracker, 26.06% had 3 other trackers, 21.21% had 5 other trackers, 9.70% had 2 other trackers, 2.42% had 6 other trackers, 2.42% had 8 other trackers, and 0.61% had 4 other trackers.

69.70% also included Chartable, 47.88% also included Podsights, 30.30% also included Podscribe, 25.45% also included Podtrac, 20.00% also included Magellan AI, 16.36% also included Audiotakes, 13.33% also included Podroll, 13.33% also included Gumshoe, 9.09% also included Podder, 7.27% also included Swap.fm, 5.45% also included Adswizz, 4.85% also included Podcorn, 2.42% also included Spotify, and 2.42% also included Zencastr.

For episodes that used United Podcasters, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "50.91%" >}}
2. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "16.36%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "10.30%" >}}
4. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "8.48%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.45%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.45%" >}}
7. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "2.42%" >}}
8. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "0.61%" >}}
---

### 25. [CoHost Prefix](https://www.cohostpodcasting.com/cohost-prefix)

CoHost Prefix was found on 0.01% of new episodes in July, growing 24.25% from last month.

Of these, 40.52% had 3 other trackers, 18.97% had one other tracker, 12.07% had 2 other trackers, 9.48% had 8 other trackers, and 1.72% had 4 other trackers.

80.17% also included Chartable, 53.45% also included Podtrac, 50.86% also included Podsights, 17.24% also included Podroll, 14.66% also included Podcorn, 9.48% also included OP3, 9.48% also included Podder, 9.48% also included Gumshoe, and 2.59% also included Podscribe.

For episodes that used CoHost Prefix, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "42.24%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "15.52%" >}}
3. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "15.52%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "11.21%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.17%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "5.17%" >}}
7. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "2.59%" >}}
8. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.59%" >}}
---

### 26. [AdBarker](https://adbarker.com/)

AdBarker was found on <0.01% of new episodes in July, shrinking 2.79% from last month.

Of these, 34.25% had 2 other trackers, 20.55% had one other tracker, and 1.37% had 4 other trackers.

52.05% also included Chartable, 30.14% also included Podtrac, 10.96% also included Podcorn, and 1.37% also included Podscribe.

For episodes that used AdBarker, here are the top underlying podcast hosts:

1. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "47.95%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "21.92%" >}}
3. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "8.22%" >}}
4. {{< a "https://adbarker.com/" "AdBarker" >}} {{< span "weak" "5.48%" >}}
5. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "5.48%" >}}
6. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.48%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.48%" >}}
---

### 27. [Voxalyze](https://voxalyze.com/)

Voxalyze was found on <0.01% of new episodes in July, growing 10.14% from last month.

Of these, 26.32% had one other tracker, and 26.32% had 2 other trackers.

31.58% also included Chartable, 26.32% also included Podsights, and 21.05% also included Podcorn.

For episodes that used Voxalyze, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "52.63%" >}}
2. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "21.05%" >}}
3. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "21.05%" >}}
4. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "5.26%" >}}
---

### 28. [Glystn](https://glystn.com/)

Glystn was found on <0.01% of new episodes in July, growing 23.18% from last month.

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
