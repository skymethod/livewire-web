---
title: "Top Podcast CDNs by Episode Share (March 2023)"
description: "Ranked list of podcast CDNs (content delivery networks), based on number of new episodes published"
slug: "archive/podcast-cdns-by-episode-share-march-2023"
images:
- cdns-2023-03.png
date: 2023-04-01T17:39:00-05:00
lastmod: 2023-04-01T17:39:00-05:00
draft: false
rssrevision: 2023-03
tags:
- archive
---
*This is an archived version, the current version is [here](/podcast-cdns-by-episode-share/).*

In our third and final installment observing the current state of the podcast world, as measured by number of new episodes produced in March 2023, 
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

We started with our universe of _every single new podcast episode published_ (about 1.9 million in March 2023), and mapped the
underlying host of the last entity in the request chain to a known CDN or network provider.  We were able to identify the underlying
network for 98.91% of the universe.

---

First, a quick chart of the top podcast CDNs over time, based on share of new episodes every month.

---

{{< graph cdnshares "Top Podcast CDNs by New Episode Share" "height:700px">}}
Month	Amazon Cloudfront	Cloudflare	Highwinds	OVH	Akamai	Hivelocity	Hetzner	Triton Digital	CDN77	Fastly
Sep 2021	43.66	12.97	8.99	3.81	3.65		2.04	2.61	2.93	1.72
Oct 2021	43.45	12.99	8.90	3.87	3.70		1.96	2.38	2.69	1.72
Nov 2021	42.95	13.32	9.29	3.87	3.55		1.95	2.26	2.70	1.63
Dec 2021	44.96	13.63	9.22	4.13	4.10	1.55	1.83	2.20	2.69	1.09
Jan 2022	44.71	13.59	9.07	4.05	3.56	1.58	1.86	1.85	2.51	1.72
Feb 2022	45.91	13.72	8.09	4.06	3.97	1.87	1.86	1.62	2.70	
Mar 2022	51.18	13.48	4.09	4.09	3.45	1.87	1.87	1.70	2.75	1.68
Apr 2022	51.94	12.71	3.95	4.27	3.67	1.72	1.78	1.86	2.47	1.66
May 2022	50.53	12.69	4.09	4.47	3.87	1.85	1.80	1.88	2.61	1.72
Jun 2022	50.08	12.14	4.32	4.72	4.03	2.01	1.82	2.07	2.70	1.71
Jul 2022	50.57	12.68	4.40	4.61	3.63	1.96	1.81	2.08	2.68	1.69
Aug 2022	51.07	13.82	4.70	4.32	3.41	1.93	1.69	2.08	2.10	1.56
Sep 2022	50.25	13.98	4.75	4.61	2.78	1.91	1.79	2.06	2.67	1.66
Oct 2022	49.87	14.70	4.93	4.60	2.60	1.85	1.78	2.07	2.50	1.68
Nov 2022	49.41	14.87	5.24	4.53	2.58	1.90	1.91	1.98	2.45	1.70
Dec 2022	49.64	14.64	5.24	4.57	2.65	1.95	2.03	1.99	2.36	1.60
Jan 2023	49.04	15.76	5.37	4.53	2.51	1.93	1.88	2.06	2.38	1.64
Feb 2023	49.39	15.95	5.34	4.64	2.28	1.92	1.97	1.94	2.23	1.59
Mar 2023	51.08	15.62	5.63	4.47	2.63	2.10	1.91	1.80	1.39	0.95
{{< /graph >}}

---

And finally, the top 50 podcast content delivery networks ordered by share percentage of new episodes published during 
the month of March 2023.

If significant, we also list the top podcast hosting companies using each CDN, and the percentage of their own episodes allocated to the network.

---

### 1. [Amazon Cloudfront · 51.08%](https://aws.amazon.com/cloudfront/)

Amazon CloudFront is a content delivery network (CDN) operated by Amazon Web Services with over 275 edge locations on six continents.

For episodes that used Amazon Cloudfront, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://podcasters.spotify.com/" "Spotify for Podcasters" >}} {{< span "weak" "100%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "100%" >}}
3. {{< a "https://libsyn.com/" "Libsyn" >}} {{< span "weak" "100%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "100%" >}}
5. {{< a "https://rss.com/" "RSS.com" >}} {{< span "weak" "100%" >}}
6. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "99%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "100%" >}}
8. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "100%" >}}
9. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "100%" >}}
10. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "100%" >}}
---

### 2. [Cloudflare · 15.62%](https://www.cloudflare.com/cdn/)

Cloudflare is an American web infrastructure and website security company that provides content delivery network (in over 250 cites in over 100 countries) and DDoS mitigation services. Cloudflare's services sit between a website's visitor and the customer's hosting provider, acting as a reverse proxy for websites.

For episodes that used Cloudflare, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "100%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "100%" >}}
3. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "98%" >}}
4. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "100%" >}}
5. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "100%" >}}
6. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "88%" >}}
7. {{< a "https://www.sermonaudio.com/" "SermonAudio" >}} {{< span "weak" "100%" >}}
8. {{< a "https://kajabi.com/" "Kajabi" >}} {{< span "weak" "100%" >}}
9. {{< a "https://stand.fm/" "stand.fm" >}} {{< span "weak" "100%" >}}
10. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "99%" >}}
---

### 3. [Highwinds · 5.63%](https://www.stackpath.com/highwinds)

Highwinds CDN was acquired by StackPath CDN, which is powered by over 45 edge locations around the world.

For episodes that used Highwinds, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "100%" >}}
2. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "99%" >}}
3. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "100%" >}}
4. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "100%" >}}
5. {{< a "https://www.elsitiocristiano.com/" "LightSource" >}} {{< span "weak" "100%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "22%" >}}
7. {{< a "https://www.lightsource.com/" "LightSource" >}} {{< span "weak" "100%" >}}
---

### 4. [OVH · 4.47%](https://www.ovh.com/world/)

OVH is a French cloud computing company which offers VPS, dedicated servers and other web services. As of 2016 OVH owned the world's largest data center in surface area.

For episodes that used OVH, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "90%" >}}
2. {{< a "https://enacast.com/" "Enacast" >}} {{< span "weak" "100%" >}}
3. {{< a "https://octopus.saooti.com/" "Octopus" >}} {{< span "weak" "100%" >}}
4. {{< a "https://www.chga.fm/" "CHGA" >}} {{< span "weak" "100%" >}}
5. {{< a "https://rctgn.cat/" "Ràdio Ciutat de Tarragona" >}} {{< span "weak" "100%" >}}
---

### 5. [Akamai · 2.63%](https://www.akamai.com/)

Akamai is a global content delivery network (CDN), cybersecurity, and cloud service company, providing web and Internet security services. Akamai's Intelligent Edge Platform is one of the world's largest distributed computing platforms.

For episodes that used Akamai, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "100%" >}}
2. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "100%" >}}
3. {{< a "https://www.deutschlandradio.de/" "Deutschlandradio" >}} {{< span "weak" "100%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "64%" >}}
5. {{< a "https://www.rferl.org/" "Radio Free Europe and Radio Liberty" >}} {{< span "weak" "100%" >}}
6. {{< a "https://www.rfi.fr/" "Radio France Internationale" >}} {{< span "weak" "100%" >}}
7. {{< a "https://www.wdr.de/" "Westdeutscher Rundfunk" >}} {{< span "weak" "100%" >}}
8. {{< a "https://www.br.de/index.html" "Bayerischer Rundfunk" >}} {{< span "weak" "100%" >}}
9. {{< a "https://www.bbc.co.uk/" "BBC" >}} {{< span "weak" "27%" >}}
10. {{< a "https://www.rfa.org/" "Radio Free Asia" >}} {{< span "weak" "100%" >}}
---

### 6. [Hivelocity · 2.10%](https://www.hivelocity.net/)

Hivelocity provides Dedicated Servers, Colocation and Cloud Hosting services to customers from over 130 countries since 2002. Hivelocity operates 31 data centers on 4 continents.

For episodes that used Hivelocity, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "34%" >}}
2. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "28%" >}}
---

### 7. [Hetzner · 1.91%](https://www.hetzner.com/)

Hetzner Online GmbH is an Internet hosting company and data center operator based in Gunzenhausen, Germany.

For episodes that used Hetzner, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "100%" >}}
2. {{< a "https://iono.fm/" "iono.fm" >}} {{< span "weak" "100%" >}}
3. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "100%" >}}
4. {{< a "https://hearthis.at/" "hearthis.at" >}} {{< span "weak" "100%" >}}
5. {{< a "https://kabbalahmedia.info/" "Kabbalah Media" >}} {{< span "weak" "100%" >}}
6. {{< a "https://letscast.fm/" "LetsCast.fm" >}} {{< span "weak" "100%" >}}
7. {{< a "https://kostenlos-hosten.de/" "Podcastbude" >}} {{< span "weak" "53%" >}}
8. {{< a "https://kerkdienstgemist.nl/" "Kerkdienst Gemist" >}} {{< span "weak" "100%" >}}
9. {{< a "https://www.freie-radios.net/" "Bundesverband Freier Radios" >}} {{< span "weak" "100%" >}}
10. {{< a "https://www.stationista.com/" "stationista" >}} {{< span "weak" "100%" >}}
---

### 8. [Triton Digital · 1.80%](https://www.tritondigital.com/)

Triton Digital, formerly Triton Media Group, is a digital audio technology and advertising company based in Los Angeles.

---

### 9. [CDN77 · 1.39%](https://www.cdn77.com/)

CDN77 provides a solid set of content delivery products and solutions all over the world, with 33 PoPs on 5 continents.

For episodes that used CDN77, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "56%" >}}
2. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "91%" >}}
3. {{< a "https://muslimcentral.com/" "Muslim Central" >}} {{< span "weak" "95%" >}}
4. {{< a "https://www.christianworldmedia.com/" "ChristianWorldMedia.com" >}} {{< span "weak" "100%" >}}
5. {{< a "https://podvine.com/" "Podvine" >}} {{< span "weak" "100%" >}}
6. {{< a "https://www.cohostpodcasting.com/" "CoHost" >}} {{< span "weak" "100%" >}}
7. {{< a "https://fans.fm/notes" "Fans.fm" >}} {{< span "weak" "100%" >}}
---

### 10. [Fastly · 0.95%](https://www.fastly.com/products/cdn)

Fastly's CDN service follows the reverse proxy model, routing all website traffic through their own servers instead of providing a 'cdn.mydomain.com' address to store site-specific files. It then fetches content from the point of presence nearest to the location of the requesting user, out of nearly 60 worldwide.

For episodes that used Fastly, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "100%" >}}
2. {{< a "https://www.atresmedia.com/" "Atresmedia" >}} {{< span "weak" "100%" >}}
3. {{< a "https://www.rtp.pt/" "RTP" >}} {{< span "weak" "100%" >}}
4. {{< a "https://www.cope.es/" "COPE" >}} {{< span "weak" "100%" >}}
5. {{< a "https://www.ccma.cat/catradio/podcast/" "CCMA" >}} {{< span "weak" "100%" >}}
6. {{< a "https://wradio.com.mx/" "W Radio (Mexico)" >}} {{< span "weak" "100%" >}}
7. {{< a "https://sermons.faithlife.com/" "Faithlife Sermons" >}} {{< span "weak" "100%" >}}
8. {{< a "https://www.barstoolsports.com/" "Barstool Sports" >}} {{< span "weak" "100%" >}}
9. {{< a "https://wistia.com/" "Wistia" >}} {{< span "weak" "77%" >}}
10. {{< a "https://www.jwplayer.com/" "JW Player" >}} {{< span "weak" "84%" >}}
---

### 11-50.

11. {{< a "https://aws.amazon.com/s3/" "Amazon S3 · 0.82%" >}}
12. {{< a "https://empirestreaming.com/" "EmpireStreaming · 0.73%" >}}
13. {{< a "https://he.net/" "Hurricane Electric · 0.65%" >}}
14. {{< a "https://cloud.google.com/" "Google Cloud · 0.49%" >}}
15. {{< a "https://www.zenlayer.com/" "Zenlayer · 0.46%" >}}
16. {{< a "https://aws.amazon.com/ec2/" "Amazon EC2 · 0.43%" >}}
17. {{< a "https://www.cogentco.com/en/" "Cogent · 0.41%" >}}
18. {{< a "https://www.lumen.com/" "Lumen · 0.38%" >}}
19. {{< a "https://www.gtt.net/us-en" "GTT Communications · 0.37%" >}}
20. {{< a "https://www.tatacommunications.com/" "Tata Communications · 0.31%" >}}

<br>

21. {{< a "https://www.edgecast.com/" "Edgecast · 0.31%" >}}
22. {{< a "https://cloud.mts.ru/en/" "MTS Cloud · 0.30%" >}}
23. {{< a "https://en.wikipedia.org/wiki/Endurance_International_Group" "Unified Layer · 0.26%" >}}
24. {{< a "https://intergrid.com.au/" "Intergrid · 0.24%" >}}
25. {{< a "https://www.deft.com/" "Deft · 0.21%" >}}
26. {{< a "https://archive.org/" "Internet Archive · 0.20%" >}}
27. {{< a "https://cloud.ionos.com/" "IONOS Cloud · 0.19%" >}}
28. {{< a "https://1gservers.com/" "1G Servers · 0.18%" >}}
29. {{< a "https://www.spie-ics.com/nos-solutions/cloud/" "SPIE ICS · 0.17%" >}}
30. {{< a "https://www.constant.com/" "Constant · 0.16%" >}}

<br>

31. {{< a "https://www.dreamhost.com/" "DreamHost · 0.16%" >}}
32. {{< a "https://www.2connect.cz/" "2 connect · 0.15%" >}}
33. {{< a "https://www.sharp-stream.com/" "Sharpstream · 0.14%" >}}
34. {{< a "https://www.scaleway.com/en/" "Scaleway · 0.14%" >}}
35. {{< a "https://www.axians.fr/en/" "AXIANS · 0.13%" >}}
36. {{< a "https://automattic.com/" "Automattic · 0.12%" >}}
37. {{< a "https://www.godaddy.com/" "GoDaddy · 0.11%" >}}
38. {{< a "https://wasabi.com/" "Wasabi · 0.11%" >}}
39. {{< a "https://www.digitalocean.com/" "DigitalOcean · 0.10%" >}}
40. {{< a "https://www.swan.sk/" "SWAN · 0.10%" >}}

<br>

41. {{< a "http://www.uplus.co.kr/home/Index.hpi" "LG DACOM · 0.09%" >}}
42. {{< a "https://microsoft.com/" "Microsoft · 0.09%" >}}
43. {{< a "https://www.serverroom.net/" "Server Room · 0.08%" >}}
44. {{< a "https://www.infomaniak.com/en" "Infomaniak · 0.08%" >}}
45. {{< a "https://www.err.ee/" "Eesti Rahvusringhääling · 0.07%" >}}
46. {{< a "https://www.networksolutions.com/" "Network Solutions · 0.07%" >}}
47. {{< a "https://www.leaseweb.com/" "Leaseweb · 0.07%" >}}
48. {{< a "https://www.liquidweb.com/" "Liquid Web · 0.07%" >}}
49. {{< a "https://www.aruba.it/" "Aruba.it · 0.06%" >}}
50. {{< a "https://www.quantil.com/" "QUANTIL · 0.06%" >}}

---
Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

Also thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

And thanks to folks working at various networks to help us identify each one as accurately as possible.

---
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
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-cdns-by-episode-share-2023-03.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
