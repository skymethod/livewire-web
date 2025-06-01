---
title: "Top Podcast CDNs by Episode Share (April 2025)"
description: "Ranked list of podcast CDNs (content delivery networks), based on number of new episodes published"
slug: "archive/podcast-cdns-by-episode-share-april-2025"
images:
- cdns-2025-04.png
date: 2025-05-02T12:47:00-04:00
lastmod: 2025-05-02T12:47:00-04:00
draft: false
rssrevision: 2025-04
tags:
- archive
---
*This is an archived version, the current version is [here](/podcast-cdns-by-episode-share/).*

In our third and final installment observing the current state of the podcast world, as measured by number of new episodes produced in April 2025, 
we wanted to take a look at which underlying CDNs serve which episodes, and which podcast hosting companies use which network.

*See our earlier analyses of [podcast hosts by episode share](/podcast-hosts-by-episode-share) and [podcast trackers by episode share](/podcast-trackers-by-episode-share)*

In general, every podcast episode has a single url that tells the podcast client app what to play.  However, this episode-level
url might redirect several times in the course a single download request, through various first and third-party trackers, before
ultimately landing at the internet host responsible for serving the audio file byte payload.  

This last entity in the chain is what we are interested in for this analysis.  Bandwidth costs are still non-trivial for hosting
providers, hence most of them use a third-party content delivery network (CDN) to minimize this cost, and also to provide lower-latency
global distribution.

{{% subscribe %}}
---

We started with our universe of _every single new podcast episode published_ (about 1.6 million in April 2025), and mapped the
underlying host of the last entity in the request chain to a known CDN or network provider.  We were able to identify the underlying
network for 99.94% of the universe.

---

First, a quick chart of the top podcast CDNs over time, based on share of new episodes every month.

---

{{< graph cdnshares "Top Podcast CDNs by New Episode Share" "height:700px">}}
Month	Amazon Cloudfront	Cloudflare	Akamai	OVH	Hetzner	Fastly	Triton Digital	CDN77	Amazon S3	SoundStack	Hivelocity	Google Cloud	Zenlayer	Cogent	Hurricane Electric	Highwinds
Sep 2021	43.66	12.97	3.65	3.81	2.04	1.72	2.61	2.93								8.99
Oct 2021	43.45	12.99	3.70	3.87	1.96	1.72	2.38	2.69								8.90
Nov 2021	42.95	13.32	3.55	3.87	1.95	1.63	2.26	2.70								9.29
Dec 2021	44.96	13.63	4.10	4.13	1.83	1.09	2.20	2.69			1.55					9.22
Jan 2022	44.71	13.59	3.56	4.05	1.86	1.72	1.85	2.51			1.58					9.07
Feb 2022	45.91	13.72	3.97	4.06	1.86		1.62	2.70			1.87					8.09
Mar 2022	51.18	13.48	3.45	4.09	1.87	1.68	1.70	2.75			1.87					4.09
Apr 2022	51.94	12.71	3.67	4.27	1.78	1.66	1.86	2.47			1.72					3.95
May 2022	50.53	12.69	3.87	4.47	1.80	1.72	1.88	2.61			1.85					4.09
Jun 2022	50.08	12.14	4.03	4.72	1.82	1.71	2.07	2.70			2.01					4.32
Jul 2022	50.57	12.68	3.63	4.61	1.81	1.69	2.08	2.68			1.96					4.40
Aug 2022	51.07	13.82	3.41	4.32	1.69	1.56	2.08	2.10			1.93					4.70
Sep 2022	50.25	13.98	2.78	4.61	1.79	1.66	2.06	2.67			1.91					4.75
Oct 2022	49.87	14.70	2.60	4.60	1.78	1.68	2.07	2.50			1.85					4.93
Nov 2022	49.41	14.87	2.58	4.53	1.91	1.70	1.98	2.45			1.90					5.24
Dec 2022	49.64	14.64	2.65	4.57	2.03	1.60	1.99	2.36			1.95					5.24
Jan 2023	49.04	15.76	2.51	4.53	1.88	1.64	2.06	2.38			1.93					5.37
Feb 2023	49.39	15.95	2.28	4.64	1.97	1.59	1.94	2.23			1.92					5.34
Mar 2023	51.08	15.62	2.63	4.47	1.91	0.95	1.80	1.39			2.10					5.63
Apr 2023	51.56	15.23	2.03	4.59	1.84	1.41	1.67	2.07			1.98					5.73
May 2023	51.00	15.89	2.53	4.40	1.86	0.84	1.67	2.12			1.96					5.93
Jun 2023	48.84	15.47	2.37	4.75	1.94	1.69	2.02	2.03			2.30					6.18
Jul 2023	48.49	15.36	2.65	4.72	2.03	1.71	2.29				2.63				0.89	6.36
Aug 2023	48.84	15.23	2.54	4.70	2.11	1.53	2.32				2.66			1.09		6.93
Sep 2023	52.41	14.04	2.31	4.35	1.94	1.62	2.16				2.54			1.02		6.27
Oct 2023	54.38	14.07	2.12	3.99	1.86	1.60	1.85				2.35			0.97		5.83
Nov 2023	54.68	14.35	7.04	4.33	1.94	1.73	1.64				2.15			0.83	0.84	
Dec 2023	54.85	14.18	7.84	4.39	2.08	1.70	1.71				1.95			0.84	0.70	
Jan 2024	55.40	14.60	7.78	4.34	1.93	1.65	2.58			0.71	1.47			0.82		
Feb 2024	55.65	14.83	7.52	4.25	1.95	1.65	2.57			0.72	1.49			0.75		
Mar 2024	55.66	14.81	7.14	4.35	1.93	1.63	2.35			0.71	1.79			0.89		
Apr 2024	56.42	15.14	7.15	4.40	1.89	1.57	2.17		0.67		1.71			0.79		
May 2024	57.11	13.80	7.12	4.36	1.89	1.60	2.39			0.73	1.66			0.78		
Jun 2024	55.86	13.91	7.27	4.59	1.95	1.64	2.68			0.75	1.69			0.82		
Jul 2024	56.11	14.20	7.48	4.57	1.99	1.56	2.53		0.70	0.76	1.70					
Aug 2024	55.93	14.14	8.02	4.52	1.95	1.45	2.44		0.66	0.81	1.46					
Sep 2024	56.64	14.57	7.02	4.53	1.96	1.60	2.46		0.67	0.73	1.18					
Oct 2024	56.74	13.59	7.37	4.65	1.98	1.58	3.01		0.59	0.79	0.95					
Nov 2024	57.07	13.77	7.19	4.84	2.07	1.61	2.62			0.75	1.26		0.60			
Dec 2024	57.67	14.05	7.03	4.65	2.08	1.56	2.15			0.62	1.21		0.60			
Jan 2025	60.90	15.57	6.36	4.33	1.91	1.38	1.47		0.56		0.60	0.44				
Feb 2025	61.91	15.23	6.09	4.27	1.95	1.27	1.37		0.57		0.47	0.41				
Mar 2025	62.32	15.49	5.73	4.44	1.93	1.31	1.35		0.58		0.47	0.41				
Apr 2025	60.78	15.78	6.14	4.61	1.96	1.40	1.30	0.74	0.56	0.45						
{{< /graph >}}

---

{{< a "https://aws.amazon.com/cloudfront/" "Amazon Cloudfront" >}} and {{< a "https://www.cloudflare.com/cdn/" "Cloudflare" >}} are the clear top two CDNs of new podcast episodes.

Now let's graph the same data again, excluding them to see the others more clearly.

---

{{< graph trackershares2 "Top Podcast CDNs by New Episode Share (excluding top 2)" "height:500px,colorShift:2">}}
Month	Akamai	OVH	Hetzner	Fastly	Triton Digital	CDN77	Amazon S3	SoundStack	Hivelocity	Google Cloud	Zenlayer	Cogent	Hurricane Electric	Highwinds
Sep 2021	3.65	3.81	2.04	1.72	2.61	2.93								8.99
Oct 2021	3.70	3.87	1.96	1.72	2.38	2.69								8.90
Nov 2021	3.55	3.87	1.95	1.63	2.26	2.70								9.29
Dec 2021	4.10	4.13	1.83	1.09	2.20	2.69			1.55					9.22
Jan 2022	3.56	4.05	1.86	1.72	1.85	2.51			1.58					9.07
Feb 2022	3.97	4.06	1.86		1.62	2.70			1.87					8.09
Mar 2022	3.45	4.09	1.87	1.68	1.70	2.75			1.87					4.09
Apr 2022	3.67	4.27	1.78	1.66	1.86	2.47			1.72					3.95
May 2022	3.87	4.47	1.80	1.72	1.88	2.61			1.85					4.09
Jun 2022	4.03	4.72	1.82	1.71	2.07	2.70			2.01					4.32
Jul 2022	3.63	4.61	1.81	1.69	2.08	2.68			1.96					4.40
Aug 2022	3.41	4.32	1.69	1.56	2.08	2.10			1.93					4.70
Sep 2022	2.78	4.61	1.79	1.66	2.06	2.67			1.91					4.75
Oct 2022	2.60	4.60	1.78	1.68	2.07	2.50			1.85					4.93
Nov 2022	2.58	4.53	1.91	1.70	1.98	2.45			1.90					5.24
Dec 2022	2.65	4.57	2.03	1.60	1.99	2.36			1.95					5.24
Jan 2023	2.51	4.53	1.88	1.64	2.06	2.38			1.93					5.37
Feb 2023	2.28	4.64	1.97	1.59	1.94	2.23			1.92					5.34
Mar 2023	2.63	4.47	1.91	0.95	1.80	1.39			2.10					5.63
Apr 2023	2.03	4.59	1.84	1.41	1.67	2.07			1.98					5.73
May 2023	2.53	4.40	1.86	0.84	1.67	2.12			1.96					5.93
Jun 2023	2.37	4.75	1.94	1.69	2.02	2.03			2.30					6.18
Jul 2023	2.65	4.72	2.03	1.71	2.29				2.63				0.89	6.36
Aug 2023	2.54	4.70	2.11	1.53	2.32				2.66			1.09		6.93
Sep 2023	2.31	4.35	1.94	1.62	2.16				2.54			1.02		6.27
Oct 2023	2.12	3.99	1.86	1.60	1.85				2.35			0.97		5.83
Nov 2023	7.04	4.33	1.94	1.73	1.64				2.15			0.83	0.84	
Dec 2023	7.84	4.39	2.08	1.70	1.71				1.95			0.84	0.70	
Jan 2024	7.78	4.34	1.93	1.65	2.58			0.71	1.47			0.82		
Feb 2024	7.52	4.25	1.95	1.65	2.57			0.72	1.49			0.75		
Mar 2024	7.14	4.35	1.93	1.63	2.35			0.71	1.79			0.89		
Apr 2024	7.15	4.40	1.89	1.57	2.17		0.67		1.71			0.79		
May 2024	7.12	4.36	1.89	1.60	2.39			0.73	1.66			0.78		
Jun 2024	7.27	4.59	1.95	1.64	2.68			0.75	1.69			0.82		
Jul 2024	7.48	4.57	1.99	1.56	2.53		0.70	0.76	1.70					
Aug 2024	8.02	4.52	1.95	1.45	2.44		0.66	0.81	1.46					
Sep 2024	7.02	4.53	1.96	1.60	2.46		0.67	0.73	1.18					
Oct 2024	7.37	4.65	1.98	1.58	3.01		0.59	0.79	0.95					
Nov 2024	7.19	4.84	2.07	1.61	2.62			0.75	1.26		0.60			
Dec 2024	7.03	4.65	2.08	1.56	2.15			0.62	1.21		0.60			
Jan 2025	6.36	4.33	1.91	1.38	1.47		0.56		0.60	0.44				
Feb 2025	6.09	4.27	1.95	1.27	1.37		0.57		0.47	0.41				
Mar 2025	5.73	4.44	1.93	1.31	1.35		0.58		0.47	0.41				
Apr 2025	6.14	4.61	1.96	1.40	1.30	0.74	0.56	0.45						
{{< /graph >}}

---

And finally, the top 50 podcast content delivery networks ordered by share percentage of new episodes published during 
the month of April 2025.

If significant, we also list the top podcast hosting companies using each CDN, and the percentage of their own episodes allocated to the network.

---

### 1. [Amazon Cloudfront · 60.78%](https://aws.amazon.com/cloudfront/)

Amazon CloudFront is a content delivery network (CDN) operated by Amazon Web Services with over 275 edge locations on six continents.

For episodes that used Amazon Cloudfront, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://creators.spotify.com/" "Spotify for Creators" >}} {{< span "weak" "100%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "100%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "100%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "100%" >}}
5. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "100%" >}}
6. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "99%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "100%" >}}
8. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "100%" >}}
9. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "100%" >}}
10. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "100%" >}}
---

### 2. [Cloudflare · 15.78%](https://www.cloudflare.com/cdn/)

Cloudflare is an American web infrastructure and website security company that provides content delivery network (in over 250 cites in over 100 countries) and DDoS mitigation services. Cloudflare's services sit between a website's visitor and the customer's hosting provider, acting as a reverse proxy for websites.

For episodes that used Cloudflare, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "100%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "100%" >}}
3. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "99%" >}}
4. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "93%" >}}
5. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "88%" >}}
6. {{< a "https://www.sermonaudio.com/" "SermonAudio" >}} {{< span "weak" "98%" >}}
7. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "100%" >}}
8. {{< a "https://kajabi.com/" "Kajabi" >}} {{< span "weak" "100%" >}}
9. {{< a "https://stand.fm/" "stand.fm" >}} {{< span "weak" "100%" >}}
10. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "100%" >}}
---

### 3. [Akamai · 6.14%](https://www.akamai.com/)

Akamai is a global content delivery network (CDN), cybersecurity, and cloud service company, providing web and Internet security services. Akamai's Intelligent Edge Platform is one of the world's largest distributed computing platforms.

For episodes that used Akamai, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "100%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "99%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "100%" >}}
4. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "100%" >}}
5. {{< a "https://www.deutschlandradio.de/" "Deutschlandradio" >}} {{< span "weak" "100%" >}}
6. {{< a "https://sverigesradio.se/" "Sveriges Radio" >}} {{< span "weak" "100%" >}}
7. {{< a "https://www3.nhk.or.jp/news/" "NHK" >}} {{< span "weak" "100%" >}}
8. {{< a "https://www.wdr.de/" "Westdeutscher Rundfunk" >}} {{< span "weak" "100%" >}}
9. {{< a "https://www.br.de/index.html" "Bayerischer Rundfunk" >}} {{< span "weak" "100%" >}}
10. {{< a "https://www.srf.ch/" "SRF" >}} {{< span "weak" "100%" >}}
---

### 4. [OVH · 4.61%](https://www.ovh.com/world/)

OVH is a French cloud computing company which offers VPS, dedicated servers and other web services. As of 2016 OVH owned the world's largest data center in surface area.

For episodes that used OVH, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "100%" >}}
2. {{< a "https://www.sharp-stream.com/" "Sharpstream" >}} {{< span "weak" "96%" >}}
3. {{< a "https://octopus.saooti.com/" "Octopus" >}} {{< span "weak" "100%" >}}
4. {{< a "https://enacast.com/" "Enacast" >}} {{< span "weak" "100%" >}}
5. {{< a "https://www.chga.fm/" "CHGA" >}} {{< span "weak" "100%" >}}
6. {{< a "https://zenomedia.com/" "Zeno Media" >}} {{< span "weak" "100%" >}}
7. {{< a "https://djpod.com/" "Djpod" >}} {{< span "weak" "100%" >}}
8. {{< a "https://www.flumotion.com/" "Flumotion" >}} {{< span "weak" "100%" >}}
---

### 5. [Hetzner · 1.96%](https://www.hetzner.com/)

Hetzner Online GmbH is an Internet hosting company and data center operator based in Gunzenhausen, Germany.

For episodes that used Hetzner, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "100%" >}}
2. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "100%" >}}
3. {{< a "https://letscast.fm/" "LetsCast.fm" >}} {{< span "weak" "100%" >}}
4. {{< a "https://iono.fm/" "iono.fm" >}} {{< span "weak" "100%" >}}
5. {{< a "https://hearthis.at/" "hearthis.at" >}} {{< span "weak" "100%" >}}
6. {{< a "https://kabbalahmedia.info/" "Kabbalah Media" >}} {{< span "weak" "100%" >}}
7. {{< a "https://www.julephosting.de/" "Julep Hosting" >}} {{< span "weak" "50%" >}}
8. {{< a "https://kerkdienstgemist.nl/" "Kerkdienst Gemist" >}} {{< span "weak" "100%" >}}
9. {{< a "https://kostenlos-hosten.de/" "Podcastbude" >}} {{< span "weak" "47%" >}}
10. {{< a "https://www.freie-radios.net/" "Bundesverband Freier Radios" >}} {{< span "weak" "100%" >}}
---

### 6. [Fastly · 1.40%](https://www.fastly.com/products/cdn)

Fastly's CDN service follows the reverse proxy model, routing all website traffic through their own servers instead of providing a 'cdn.mydomain.com' address to store site-specific files. It then fetches content from the point of presence nearest to the location of the requesting user, out of nearly 60 worldwide.

For episodes that used Fastly, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "100%" >}}
2. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "100%" >}}
3. {{< a "https://pod.space/" "Podspace" >}} {{< span "weak" "100%" >}}
4. {{< a "http://www.rtve.es/" "RTVE" >}} {{< span "weak" "100%" >}}
5. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "100%" >}}
6. {{< a "https://www.rtp.pt/" "RTP" >}} {{< span "weak" "100%" >}}
7. {{< a "https://sermons.faithlife.com/" "Faithlife Sermons" >}} {{< span "weak" "100%" >}}
8. {{< a "https://www.audion.fm/" "Audion" >}} {{< span "weak" "97%" >}}
9. {{< a "https://www.ondacero.es/" "Onda Cero" >}} {{< span "weak" "71%" >}}
10. {{< a "https://www.lightcast.com/" "Lightcast" >}} {{< span "weak" "100%" >}}
---

### 7. [Triton Digital · 1.30%](https://www.tritondigital.com/)

Triton Digital, formerly Triton Media Group, is a digital audio technology and advertising company based in Los Angeles.

---

### 8. [CDN77 · 0.74%](https://www.cdn77.com/)

CDN77 provides a solid set of content delivery products and solutions all over the world, with 33 PoPs on 5 continents.

For episodes that used CDN77, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "44%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "8%" >}}
3. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "92%" >}}
4. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "100%" >}}
5. {{< a "https://www.christianworldmedia.com/" "ChristianWorldMedia.com" >}} {{< span "weak" "100%" >}}
6. {{< a "https://www.podtoo.com/" "PodToo" >}} {{< span "weak" "100%" >}}
7. {{< a "https://fans.fm/notes" "Fans.fm" >}} {{< span "weak" "100%" >}}
---

### 9. [Amazon S3 · 0.56%](https://aws.amazon.com/s3/)

Amazon Simple Storage Service (Amazon S3) is an object storage service offering industry-leading scalability, data availability, security, and performance.

For episodes that used Amazon S3, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "http://thecloudnetwork.com/" "the Cloud Network" >}} {{< span "weak" "95%" >}}
2. {{< a "https://www.planningcenter.com/" "Planning Center" >}} {{< span "weak" "100%" >}}
3. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "31%" >}}
4. {{< a "https://www.nucleus.church/" "Nucleus" >}} {{< span "weak" "100%" >}}
5. {{< a "https://www.voxnest.com/" "Voxnest" >}} {{< span "weak" "94%" >}}
---

### 10. [SoundStack · 0.45%](https://soundstack.com/)

SoundStack simplifies audio through the development of platform-agnostic technology for creators and advertisers.

For episodes that used SoundStack, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "98%" >}}
---

### 11-50.

11. {{< a "https://www.hivelocity.net/" "Hivelocity · 0.38%" >}}
12. {{< a "https://cloud.google.com/" "Google Cloud · 0.37%" >}}
13. {{< a "https://www.tencent.com/" "ACE CDN · 0.34%" >}}
14. {{< a "https://www.alibabacloud.com/product/networking" "Alibaba Cloud CDN · 0.24%" >}}
15. {{< a "https://www.deft.com/" "Deft · 0.21%" >}}
16. {{< a "https://www.tatacommunications.com/" "Tata Communications · 0.20%" >}}
17. {{< a "https://www.linode.com/" "Linode · 0.18%" >}}
18. {{< a "https://cloud.mts.ru/en/" "MTS Cloud · 0.18%" >}}
19. {{< a "https://en.wikipedia.org/wiki/Endurance_International_Group" "Unified Layer · 0.16%" >}}
20. {{< a "https://www.serverroom.net/" "Server Room · 0.15%" >}}

<br>

21. {{< a "https://cloud.ionos.com/" "IONOS Cloud · 0.13%" >}}
22. {{< a "https://1gservers.com/" "1G Servers · 0.13%" >}}
23. {{< a "https://aws.amazon.com/ec2/" "Amazon EC2 · 0.12%" >}}
24. {{< a "https://www.cachefly.com/" "CacheFly · 0.11%" >}}
25. {{< a "https://www.dreamhost.com/" "DreamHost · 0.11%" >}}
26. {{< a "https://intergrid.com.au/" "Intergrid · 0.11%" >}}
27. {{< a "https://archive.org/" "Internet Archive · 0.10%" >}}
28. {{< a "https://microsoft.com/" "Microsoft · 0.10%" >}}
29. {{< a "https://www.gtt.net/us-en" "GTT Communications · 0.09%" >}}
30. {{< a "https://edgeuno.com/" "Edgeuno · 0.09%" >}}

<br>

31. {{< a "https://automattic.com/" "Automattic · 0.08%" >}}
32. {{< a "https://www.digitalocean.com/" "DigitalOcean · 0.08%" >}}
33. {{< a "https://he.net/" "Hurricane Electric · 0.08%" >}}
34. {{< a "https://www.godaddy.com/" "GoDaddy · 0.08%" >}}
35. {{< a "https://www.spie-ics.com/nos-solutions/cloud/" "SPIE ICS · 0.07%" >}}
36. {{< a "https://www.2connect.cz/" "2 connect · 0.07%" >}}
37. {{< a "https://www.leaseweb.com/" "Leaseweb · 0.07%" >}}
38. {{< a "https://wasabi.com/" "Wasabi · 0.07%" >}}
39. {{< a "https://www.aruba.it/" "Aruba.it · 0.07%" >}}
40. {{< a "https://netrack.ru/" "NETRACK Russia · 0.06%" >}}

<br>

41. {{< a "https://www.swan.sk/" "SWAN · 0.06%" >}}
42. {{< a "https://www.hosteurope.de/en/" "Host Europe · 0.05%" >}}
43. {{< a "https://all-inkl.com/" "Neue Medien Münnich · 0.05%" >}}
44. {{< a "https://webhost1.ru/" "Webhost LLC · 0.05%" >}}
45. {{< a "https://www.gmo.jp/en/" "GMO Internet Group · 0.04%" >}}
46. {{< a "https://www.scaleway.com/en/" "Scaleway · 0.04%" >}}
47. {{< a "https://www.networksolutions.com/" "Network Solutions · 0.04%" >}}
48. {{< a "https://www.rtvslo.si/" "RTV Slovenija · 0.04%" >}}
49. {{< a "https://www.err.ee/" "Eesti Rahvusringhääling · 0.04%" >}}
50. {{< a "https://www.o2switch.fr/" "o2switch · 0.03%" >}}

---
Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

Also thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

And thanks to folks working at various networks to help us identify each one as accurately as possible.

---
*Updated 2025-05-02, with data for the month of April 2025.*

*Updated 2025-04-05, with data for the month of March 2025.*

*Updated 2025-03-01, with data for the month of February 2025.*

*Updated 2025-02-03, with data for the month of January 2025.*

*Updated 2025-01-02, with data for the month of December 2024.*

*Updated 2024-12-01, with data for the month of November 2024.*

*Updated 2024-11-06, with data for the month of October 2024.*

*Updated 2024-10-01, with data for the month of September 2024.*

*Updated 2024-09-01, with data for the month of August 2024.*

*Updated 2024-08-01, with data for the month of July 2024.*

*Updated 2024-07-02, with data for the month of June 2024.*

*Updated 2024-06-01, with data for the month of May 2024.*

*Updated 2024-05-01, with data for the month of April 2024.*

*Updated 2024-04-02, with data for the month of March 2024.*

*Updated 2024-03-02, with data for the month of February 2024.*

*Updated 2024-02-02, with data for the month of January 2024.*

*Updated 2024-01-02, with data for the month of December 2023.*

*Updated 2023-12-03, with data for the month of November 2023. [Highwinds/StackPath exited the CDN business, contracts moved to Akamai](https://www.datacenterdynamics.com/en/news/stackpath-quits-cdn-business-akamai-buys-enterprise-customer-contracts/).*

*Updated 2023-11-02, with data for the month of October 2023.*

*Updated 2023-10-01, with data for the month of September 2023.*

*Updated 2023-09-01, with data for the month of August 2023.*

*Updated 2023-08-02, with data for the month of July 2023.*

*Updated 2023-07-01, with data for the month of June 2023.*

*Updated 2023-06-01, with data for the month of May 2023.*

*Updated 2023-05-05, with data for the month of April 2023.*

*Updated 2023-04-01, with data for the month of March 2023.*

*Updated 2023-03-01, with data for the month of February 2023.*

*Updated 2023-02-01, with data for the month of January 2023.*

*Updated 2023-01-02, with data for the month of December 2022.*

*Updated 2022-12-01, with data for the month of November 2022.*

*Updated 2022-11-03, with data for the month of October 2022.*

*Updated 2022-10-03, with data for the month of September 2022.*

*Updated 2022-09-01, with data for the month of August 2022.*

*Updated 2022-08-01, with data for the month of July 2022.*

*Updated 2022-07-01, with data for the month of June 2022.*

*Updated 2022-06-01, with data for the month of May 2022.*

*Updated 2022-05-01, with data for the month of April 2022.*

*Updated 2022-04-05, RSS Podcasting is now known as RSS.com.*

*Updated 2022-04-04, with data for the month of March 2022 and a new graph.*

*Updated 2022-03-03, with data for the month of February 2022.*

*Updated 2022-02-10, with data for the month of January 2022.*

*Updated 2022-01-10, with data for the month of December 2021.*

*Updated 2021-11-15, with data for the month of November 2021.*

*Updated 2021-11-15, with data for the month of October 2021.*

*Updated 2021-10-21: Was showing the top 20, now showing the top 50, added thanks about feedback from networks.*

---
Previous versions:
 - [Podcast Host Rankings by Episode Share (March 2025)](/archive/podcast-cdns-by-episode-share-march-2025/)
 - [Podcast Host Rankings by Episode Share (February 2025)](/archive/podcast-cdns-by-episode-share-february-2025/)
 - [Podcast Host Rankings by Episode Share (January 2025)](/archive/podcast-cdns-by-episode-share-january-2025/)
 - [Podcast Host Rankings by Episode Share (December 2024)](/archive/podcast-cdns-by-episode-share-december-2024/)
 - [Podcast Host Rankings by Episode Share (November 2024)](/archive/podcast-cdns-by-episode-share-november-2024/)
 - [Podcast Host Rankings by Episode Share (October 2024)](/archive/podcast-cdns-by-episode-share-october-2024/)
 - [Podcast Host Rankings by Episode Share (September 2024)](/archive/podcast-cdns-by-episode-share-september-2024/)
 - [Podcast Host Rankings by Episode Share (August 2024)](/archive/podcast-cdns-by-episode-share-august-2024/)
 - [Podcast Host Rankings by Episode Share (July 2024)](/archive/podcast-cdns-by-episode-share-july-2024/)
 - [Podcast Host Rankings by Episode Share (June 2024)](/archive/podcast-cdns-by-episode-share-june-2024/)
 - [Podcast Host Rankings by Episode Share (May 2024)](/archive/podcast-cdns-by-episode-share-may-2024/)
 - [Podcast Host Rankings by Episode Share (April 2024)](/archive/podcast-cdns-by-episode-share-april-2024/)
 - [Podcast Host Rankings by Episode Share (March 2024)](/archive/podcast-cdns-by-episode-share-march-2024/)
 - [Podcast Host Rankings by Episode Share (February 2024)](/archive/podcast-cdns-by-episode-share-february-2024/)
 - [Podcast Host Rankings by Episode Share (January 2024)](/archive/podcast-cdns-by-episode-share-january-2024/)
 - [Podcast Host Rankings by Episode Share (December 2023)](/archive/podcast-cdns-by-episode-share-december-2023/)
 - [Podcast Host Rankings by Episode Share (November 2023)](/archive/podcast-cdns-by-episode-share-november-2023/)
 - [Podcast Host Rankings by Episode Share (October 2023)](/archive/podcast-cdns-by-episode-share-october-2023/)
 - [Podcast Host Rankings by Episode Share (September 2023)](/archive/podcast-cdns-by-episode-share-september-2023/)
 - [Podcast Host Rankings by Episode Share (August 2023)](/archive/podcast-cdns-by-episode-share-august-2023/)
 - [Podcast Host Rankings by Episode Share (July 2023)](/archive/podcast-cdns-by-episode-share-july-2023/)
 - [Podcast Host Rankings by Episode Share (June 2023)](/archive/podcast-cdns-by-episode-share-june-2023/)
 - [Podcast Host Rankings by Episode Share (May 2023)](/archive/podcast-cdns-by-episode-share-may-2023/)
 - [Podcast Host Rankings by Episode Share (April 2023)](/archive/podcast-cdns-by-episode-share-april-2023/)
 - [Podcast Host Rankings by Episode Share (March 2023)](/archive/podcast-cdns-by-episode-share-march-2023/)
 - [Podcast Host Rankings by Episode Share (February 2023)](/archive/podcast-cdns-by-episode-share-february-2023/)
 - [Podcast Host Rankings by Episode Share (January 2023)](/archive/podcast-cdns-by-episode-share-january-2023/)
 - [Podcast Host Rankings by Episode Share (December 2022)](/archive/podcast-cdns-by-episode-share-december-2022/)
 - [Podcast Host Rankings by Episode Share (November 2022)](/archive/podcast-cdns-by-episode-share-november-2022/)
 - [Podcast Host Rankings by Episode Share (October 2022)](/archive/podcast-cdns-by-episode-share-october-2022/)
 - [Podcast Host Rankings by Episode Share (September 2022)](/archive/podcast-cdns-by-episode-share-september-2022/)
 - [Podcast Host Rankings by Episode Share (August 2022)](/archive/podcast-cdns-by-episode-share-august-2022/)
 - [Podcast Host Rankings by Episode Share (July 2022)](/archive/podcast-cdns-by-episode-share-july-2022/)
 - [Podcast Host Rankings by Episode Share (June 2022)](/archive/podcast-cdns-by-episode-share-june-2022/)
 - [Podcast Host Rankings by Episode Share (May 2022)](/archive/podcast-cdns-by-episode-share-may-2022/)
 - [Podcast Host Rankings by Episode Share (April 2022)](/archive/podcast-cdns-by-episode-share-april-2022/)
 - [Podcast Host Rankings by Episode Share (March 2022)](/archive/podcast-cdns-by-episode-share-march-2022/)
 - [Podcast Host Rankings by Episode Share (February 2022)](/archive/podcast-cdns-by-episode-share-february-2022/)
 - [Podcast Host Rankings by Episode Share (January 2022)](/archive/podcast-cdns-by-episode-share-january-2022/)
 - [Podcast Host Rankings by Episode Share (December 2021)](/archive/podcast-cdns-by-episode-share-december-2021/)
 - [Podcast Host Rankings by Episode Share (November 2021)](/archive/podcast-cdns-by-episode-share-november-2021/)
 - [Podcast Host Rankings by Episode Share (October 2021)](/archive/podcast-cdns-by-episode-share-october-2021/)
 - [Podcast Host Rankings by Episode Share (September 2021)](/archive/podcast-cdns-by-episode-share-september-2021/)

{{% funding %}}

---
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-cdns-by-episode-share-2025-04.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
