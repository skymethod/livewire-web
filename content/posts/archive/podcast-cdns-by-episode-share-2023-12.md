---
title: "Top Podcast CDNs by Episode Share (December 2023)"
description: "Ranked list of podcast CDNs (content delivery networks), based on number of new episodes published"
slug: "archive/podcast-cdns-by-episode-share-december-2023"
images:
- cdns-2023-12.png
date: 2024-01-02T11:51:00-06:00
lastmod: 2024-01-02T11:51:00-06:00
draft: false
rssrevision: 2023-12
tags:
- archive
---
*This is an archived version, the current version is [here](/podcast-cdns-by-episode-share/).*

In our third and final installment observing the current state of the podcast world, as measured by number of new episodes produced in December 2023, 
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

We started with our universe of _every single new podcast episode published_ (about 1.7 million in December 2023), and mapped the
underlying host of the last entity in the request chain to a known CDN or network provider.  We were able to identify the underlying
network for 99.39% of the universe.

---

First, a quick chart of the top podcast CDNs over time, based on share of new episodes every month.

---

{{< graph cdnshares "Top Podcast CDNs by New Episode Share" "height:700px">}}
Month	Amazon Cloudfront	Cloudflare	Akamai	OVH	Hetzner	Hivelocity	Triton Digital	Fastly	Cogent	Hurricane Electric	Highwinds	CDN77
Sep 2021	43.66	12.97	3.65	3.81	2.04		2.61	1.72			8.99	2.93
Oct 2021	43.45	12.99	3.70	3.87	1.96		2.38	1.72			8.90	2.69
Nov 2021	42.95	13.32	3.55	3.87	1.95		2.26	1.63			9.29	2.70
Dec 2021	44.96	13.63	4.10	4.13	1.83	1.55	2.20	1.09			9.22	2.69
Jan 2022	44.71	13.59	3.56	4.05	1.86	1.58	1.85	1.72			9.07	2.51
Feb 2022	45.91	13.72	3.97	4.06	1.86	1.87	1.62				8.09	2.70
Mar 2022	51.18	13.48	3.45	4.09	1.87	1.87	1.70	1.68			4.09	2.75
Apr 2022	51.94	12.71	3.67	4.27	1.78	1.72	1.86	1.66			3.95	2.47
May 2022	50.53	12.69	3.87	4.47	1.80	1.85	1.88	1.72			4.09	2.61
Jun 2022	50.08	12.14	4.03	4.72	1.82	2.01	2.07	1.71			4.32	2.70
Jul 2022	50.57	12.68	3.63	4.61	1.81	1.96	2.08	1.69			4.40	2.68
Aug 2022	51.07	13.82	3.41	4.32	1.69	1.93	2.08	1.56			4.70	2.10
Sep 2022	50.25	13.98	2.78	4.61	1.79	1.91	2.06	1.66			4.75	2.67
Oct 2022	49.87	14.70	2.60	4.60	1.78	1.85	2.07	1.68			4.93	2.50
Nov 2022	49.41	14.87	2.58	4.53	1.91	1.90	1.98	1.70			5.24	2.45
Dec 2022	49.64	14.64	2.65	4.57	2.03	1.95	1.99	1.60			5.24	2.36
Jan 2023	49.04	15.76	2.51	4.53	1.88	1.93	2.06	1.64			5.37	2.38
Feb 2023	49.39	15.95	2.28	4.64	1.97	1.92	1.94	1.59			5.34	2.23
Mar 2023	51.08	15.62	2.63	4.47	1.91	2.10	1.80	0.95			5.63	1.39
Apr 2023	51.56	15.23	2.03	4.59	1.84	1.98	1.67	1.41			5.73	2.07
May 2023	51.00	15.89	2.53	4.40	1.86	1.96	1.67	0.84			5.93	2.12
Jun 2023	48.84	15.47	2.37	4.75	1.94	2.30	2.02	1.69			6.18	2.03
Jul 2023	48.49	15.36	2.65	4.72	2.03	2.63	2.29	1.71		0.89	6.36	
Aug 2023	48.84	15.23	2.54	4.70	2.11	2.66	2.32	1.53	1.09		6.93	
Sep 2023	52.41	14.04	2.31	4.35	1.94	2.54	2.16	1.62	1.02		6.27	
Oct 2023	54.38	14.07	2.12	3.99	1.86	2.35	1.85	1.60	0.97		5.83	
Nov 2023	54.68	14.35	7.04	4.33	1.94	2.15	1.64	1.73	0.83	0.84		
Dec 2023	54.85	14.18	7.84	4.39	2.08	1.95	1.71	1.70	0.84	0.70		
{{< /graph >}}

---

And finally, the top 50 podcast content delivery networks ordered by share percentage of new episodes published during 
the month of December 2023.

If significant, we also list the top podcast hosting companies using each CDN, and the percentage of their own episodes allocated to the network.

---

### 1. [Amazon Cloudfront · 54.85%](https://aws.amazon.com/cloudfront/)

Amazon CloudFront is a content delivery network (CDN) operated by Amazon Web Services with over 275 edge locations on six continents.

For episodes that used Amazon Cloudfront, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "100%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "100%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "100%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "100%" >}}
5. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "99%" >}}
6. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "100%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "100%" >}}
8. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "57%" >}}
9. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "100%" >}}
10. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "100%" >}}
---

### 2. [Cloudflare · 14.18%](https://www.cloudflare.com/cdn/)

Cloudflare is an American web infrastructure and website security company that provides content delivery network (in over 250 cites in over 100 countries) and DDoS mitigation services. Cloudflare's services sit between a website's visitor and the customer's hosting provider, acting as a reverse proxy for websites.

For episodes that used Cloudflare, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "100%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "100%" >}}
3. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "90%" >}}
4. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "100%" >}}
5. {{< a "https://www.sermonaudio.com/" "SermonAudio" >}} {{< span "weak" "100%" >}}
6. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "96%" >}}
7. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "100%" >}}
8. {{< a "https://stand.fm/" "stand.fm" >}} {{< span "weak" "100%" >}}
9. {{< a "https://kajabi.com/" "Kajabi" >}} {{< span "weak" "100%" >}}
10. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "100%" >}}
---

### 3. [Akamai · 7.84%](https://www.akamai.com/)

Akamai is a global content delivery network (CDN), cybersecurity, and cloud service company, providing web and Internet security services. Akamai's Intelligent Edge Platform is one of the world's largest distributed computing platforms.

For episodes that used Akamai, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "100%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "99%" >}}
3. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "100%" >}}
4. {{< a "https://www.deutschlandradio.de/" "Deutschlandradio" >}} {{< span "weak" "100%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "100%" >}}
6. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "100%" >}}
7. {{< a "https://www.rferl.org/" "Radio Free Europe and Radio Liberty" >}} {{< span "weak" "100%" >}}
8. {{< a "https://www.dr.dk/" "DR" >}} {{< span "weak" "100%" >}}
9. {{< a "https://www.br.de/index.html" "Bayerischer Rundfunk" >}} {{< span "weak" "100%" >}}
10. {{< a "https://www3.nhk.or.jp/news/" "NHK" >}} {{< span "weak" "100%" >}}
---

### 4. [OVH · 4.39%](https://www.ovh.com/world/)

OVH is a French cloud computing company which offers VPS, dedicated servers and other web services. As of 2016 OVH owned the world's largest data center in surface area.

For episodes that used OVH, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "92%" >}}
2. {{< a "https://enacast.com/" "Enacast" >}} {{< span "weak" "100%" >}}
3. {{< a "https://www.sharp-stream.com/" "Sharpstream" >}} {{< span "weak" "98%" >}}
4. {{< a "https://octopus.saooti.com/" "Octopus" >}} {{< span "weak" "100%" >}}
---

### 5. [Hetzner · 2.08%](https://www.hetzner.com/)

Hetzner Online GmbH is an Internet hosting company and data center operator based in Gunzenhausen, Germany.

For episodes that used Hetzner, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "100%" >}}
2. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "100%" >}}
3. {{< a "https://iono.fm/" "iono.fm" >}} {{< span "weak" "100%" >}}
4. {{< a "https://kabbalahmedia.info/" "Kabbalah Media" >}} {{< span "weak" "100%" >}}
5. {{< a "https://letscast.fm/" "LetsCast.fm" >}} {{< span "weak" "100%" >}}
6. {{< a "https://hearthis.at/" "hearthis.at" >}} {{< span "weak" "100%" >}}
7. {{< a "https://kostenlos-hosten.de/" "Podcastbude" >}} {{< span "weak" "58%" >}}
8. {{< a "https://kerkdienstgemist.nl/" "Kerkdienst Gemist" >}} {{< span "weak" "100%" >}}
9. {{< a "https://www.freie-radios.net/" "Bundesverband Freier Radios" >}} {{< span "weak" "100%" >}}
10. {{< a "https://www.stationista.com/" "stationista" >}} {{< span "weak" "100%" >}}
---

### 6. [Hivelocity · 1.95%](https://www.hivelocity.net/)

Hivelocity provides Dedicated Servers, Colocation and Cloud Hosting services to customers from over 130 countries since 2002. Hivelocity operates 31 data centers on 4 continents.

For episodes that used Hivelocity, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "31%" >}}
2. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "36%" >}}
3. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "11%" >}}
4. {{< a "https://www.securenetsystems.net/" "Securenet Systems" >}} {{< span "weak" "30%" >}}
---

### 7. [Triton Digital · 1.71%](https://www.tritondigital.com/)

Triton Digital, formerly Triton Media Group, is a digital audio technology and advertising company based in Los Angeles.

---

### 8. [Fastly · 1.70%](https://www.fastly.com/products/cdn)

Fastly's CDN service follows the reverse proxy model, routing all website traffic through their own servers instead of providing a 'cdn.mydomain.com' address to store site-specific files. It then fetches content from the point of presence nearest to the location of the requesting user, out of nearly 60 worldwide.

For episodes that used Fastly, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "100%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "100%" >}}
3. {{< a "http://www.rtve.es/" "RTVE" >}} {{< span "weak" "100%" >}}
4. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "100%" >}}
5. {{< a "https://www.ondacero.es/" "Onda Cero" >}} {{< span "weak" "100%" >}}
6. {{< a "https://pod.space/" "Podspace" >}} {{< span "weak" "100%" >}}
7. {{< a "https://www.rtp.pt/" "RTP" >}} {{< span "weak" "100%" >}}
8. {{< a "https://www.cope.es/" "COPE" >}} {{< span "weak" "100%" >}}
9. {{< a "https://www.ccma.cat/catradio/podcast/" "CCMA" >}} {{< span "weak" "100%" >}}
10. {{< a "https://sermons.faithlife.com/" "Faithlife Sermons" >}} {{< span "weak" "100%" >}}
---

### 9. [Cogent · 0.84%](https://www.cogentco.com/en/)

Cogent Communications is a multinational internet service provider based in the United States. Cogent's primary services consist of Internet access and data transport, offered on a fiber optic, IP data-only network, along with colocation in data centers.

For episodes that used Cogent, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.ximalaya.com/" "Ximalaya" >}} {{< span "weak" "100%" >}}
2. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "8%" >}}
3. {{< a "https://wavpub.com/" "WavPub" >}} {{< span "weak" "42%" >}}
---

### 10. [Hurricane Electric · 0.70%](https://he.net/)

Hurricane Electric is considered the largest IPv6 backbone in the world as measured by number of networks connected. Within its global network, Hurricane Electric is connected to over 250 major exchange points and exchanges traffic directly with more than 9,200 different networks.

For episodes that used Hurricane Electric, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "23%" >}}
2. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "16%" >}}
---

### 11-50.

11. {{< a "https://aws.amazon.com/s3/" "Amazon S3 · 0.69%" >}}
12. {{< a "https://soundstack.com/" "SoundStack · 0.60%" >}}
13. {{< a "https://cloud.google.com/" "Google Cloud · 0.38%" >}}
14. {{< a "https://cloud.mts.ru/en/" "MTS Cloud · 0.37%" >}}
15. {{< a "https://www.tatacommunications.com/" "Tata Communications · 0.35%" >}}
16. {{< a "https://www.edgecast.com/" "Edgecast · 0.30%" >}}
17. {{< a "https://www.gtt.net/us-en" "GTT Communications · 0.26%" >}}
18. {{< a "https://www.deft.com/" "Deft · 0.26%" >}}
19. {{< a "https://intergrid.com.au/" "Intergrid · 0.25%" >}}
20. {{< a "https://aws.amazon.com/ec2/" "Amazon EC2 · 0.23%" >}}

<br>

21. {{< a "https://en.wikipedia.org/wiki/Endurance_International_Group" "Unified Layer · 0.22%" >}}
22. {{< a "https://www.cdn77.com/" "CDN77 · 0.21%" >}}
23. {{< a "https://1gservers.com/" "1G Servers · 0.19%" >}}
24. {{< a "https://archive.org/" "Internet Archive · 0.17%" >}}
25. {{< a "https://www.spie-ics.com/nos-solutions/cloud/" "SPIE ICS · 0.16%" >}}
26. {{< a "https://www.constant.com/" "Constant · 0.16%" >}}
27. {{< a "https://www.cachefly.com/" "CacheFly · 0.16%" >}}
28. {{< a "https://www.2connect.cz/" "2 connect · 0.15%" >}}
29. {{< a "https://cloud.ionos.com/" "IONOS Cloud · 0.15%" >}}
30. {{< a "https://www.dreamhost.com/" "DreamHost · 0.14%" >}}

<br>

31. {{< a "https://edgeuno.com/" "Edgeuno · 0.13%" >}}
32. {{< a "https://www.serverroom.net/" "Server Room · 0.12%" >}}
33. {{< a "https://wasabi.com/" "Wasabi · 0.11%" >}}
34. {{< a "https://www.scaleway.com/en/" "Scaleway · 0.11%" >}}
35. {{< a "https://www.godaddy.com/" "GoDaddy · 0.11%" >}}
36. {{< a "https://automattic.com/" "Automattic · 0.11%" >}}
37. {{< a "https://www.swan.sk/" "SWAN · 0.10%" >}}
38. {{< a "http://www.uplus.co.kr/home/Index.hpi" "LG DACOM · 0.10%" >}}
39. {{< a "https://www.digitalocean.com/" "DigitalOcean · 0.09%" >}}
40. {{< a "https://microsoft.com/" "Microsoft · 0.08%" >}}

<br>

41. {{< a "https://www.leaseweb.com/" "Leaseweb · 0.07%" >}}
42. {{< a "https://www.hosteurope.de/en/" "Host Europe · 0.07%" >}}
43. {{< a "https://www.gsneotek.co.kr/en/" "GS Neotek · 0.07%" >}}
44. {{< a "https://www.quantil.com/" "QUANTIL · 0.07%" >}}
45. {{< a "https://www.liquidweb.com/" "Liquid Web · 0.07%" >}}
46. {{< a "https://www.aruba.it/" "Aruba.it · 0.06%" >}}
47. {{< a "https://www.err.ee/" "Eesti Rahvusringhääling · 0.06%" >}}
48. {{< a "https://www.equinix.com/" "Equinix · 0.05%" >}}
49. {{< a "https://apa.at/about/apa-tech/" "APA Tech · 0.05%" >}}
50. {{< a "https://www.networksolutions.com/" "Network Solutions · 0.05%" >}}

---
Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) and other sources, for giving us signals of when 
to check for new episodes in public podcasts.

Also thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

And thanks to folks working at various networks to help us identify each one as accurately as possible.

---
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-cdns-by-episode-share-2023-12.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
