---
title: "Transistor Statistics, visualized"
description: "Visualizing the podcast data provided monthly by Transistor, the podcast hosting company"
summary: "Transistor, the podcast hosting company, provides detailed data every month about the most common apps it sees when serving podcasts for its customers. We thought it might be fun to graph this data in order to visualize trends over time."
slug: "transistor-stats-visualized"
images:
- transistor-stats-visualized-2025-04.png
date: 2025-05-01T19:32:00-04:00
lastmod: 2025-05-01T19:32:00-04:00
draft: false
rssrevision: 2025-04
---

[Transistor](https://transistor.fm/), the podcast hosting company, just started publishing [detailed data every month](https://transistor.fm/global-stats/) about the most common apps it sees when serving podcasts for its customers.

We thought it might be fun to graph this data in order to visualize trends over time.  Only two months of data so far!

{{% subscribe %}}
---

{{< graph apps "Podcast Apps (top 25)" "limit:25,legendPosition:right,height:700px">}}
Month	Apple Podcasts	Spotify	Ex Apple/Spotify²	Embed Player	Desktop Browser	Mobile Browser	CastBox	Overcast	Pocket Casts	Storybutton	PodcastAddict	Amazon Music	Other	Alexa	iTunes	Podbean	AntennaPod	YouTube Music	NPR One	Audible	Transistor Site	Player FM	iVoox	iHeartRadio	Chromecast	Private Web Player	PodcastRepublic	FMRadio	Samsung	Downcast	Podcast Guru	Snipd	Pandora	JioSaavn	Podimo	Radio thmanyah	Google Podcasts	Deezer	audiobookshelf	The Podcast App	SiriusXM	Global Player	Facebook	TuneIn	Anghami	Castro	gPodder	Fountain	iCatcher	myTuner	BeyondPod	RSSRadio	Windows Media Player	VictorReader	Sonos	DoggCatcher	VLC	Earmark	radio.de	Roya Waves	MusicBee	Xiaoyuzhou	Rhythmbox	PodCruncher	PodMe	Apple iMessage	Garmin Watch	Roku	Castamatic	MediaMonkey	Podverse	Zune	Podplay	Mimir	Neuecast	Twitter	FocusPodcast	CloudPlayer	NetCast	NRC Audio	Queue	Bose	RadioPlayer	Metacast	Podurama	Squeezebox	Podeo	KKBOX	Podcini	Luminary	Procast	Cooler	PeaCast	BashPodder	Anytime Podcast Player	Reeder	Gaana	Winamp	Outcast	Podkicker	Sony Bravia	TikTok	Himalaya	Podcast Player	Clementine	Outlook	Amazon Fire TV	MoonFM	ServeStream	'sodes	Stitcher	Playapod	Instacast	RadioPublic	Samsung Free	Podbbang	Nvidia Shield	Kodi	WynkMusic	Goodpods	AllYouCanBooks	Hubhopper	Xbox	Repod	Playstation 5
Mar 2025	41.809	33.811	24.380000000000003	1.853	2.966	2.464	2.431	1.989	1.734	1.513	1.235	0.841	0.729	0.534	0.652	0.503	0.497	0.445	0.074	0.374	0.303	0.262	0.224	0.242	0.229	0.246	0.203	0.144	0.144	0.123	0.11	0.108	0.116	0.042	0.113	0.124	0.069	0.074	0.04	0.058	0.057	0.048	0.058	0.047	0.029	0.036	0.029	0.024	0.023	0.02	0.018	0.018	0.015	0.011	0.012	0.009	0.012	0.008	0.007	0.002	0.007	0.004	0.007	0.007	0.007	0.004	0.004	0.004	0.003	0.005	0.002	0.001	0.003	0.001	0.003	0.001	0.001	0.002	0.001	0.002	0.001	0.001	0.001	0.001	0.001	0	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0	0	0.001	0	0	0	0	0	0	0	0	0.001	0	0	0	0	0	0	0.001	0	0	0		0	0				0	0	0	0
Apr 2025	41.599	34.576	23.825000000000003	2.566	2.457	2.443	2.351	1.85	1.56	1.352	1.155	0.735	0.718	0.641	0.532	0.47	0.467	0.441	0.366	0.342	0.277	0.269	0.24	0.228	0.213	0.208	0.192	0.153	0.137	0.12	0.103	0.097	0.09	0.083	0.078	0.076	0.072	0.069	0.066	0.057	0.056	0.049	0.047	0.043	0.035	0.034	0.028	0.022	0.02	0.019	0.018	0.015	0.015	0.012	0.01	0.01	0.008	0.008	0.008	0.008	0.008	0.007	0.005	0.005	0.005	0.004	0.004	0.004	0.003	0.003	0.003	0.003	0.003	0.002	0.002	0.002	0.002	0.002	0.002	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0			
{{< /graph >}}

*² Ex Apple/Spotify: all apps excluding Apple Podcasts and Spotify*

---

Apple and Spotify are the top two apps by quite a bit.  Let's filter them out to see the others more clearly:

{{< graph apps2 "Podcast Apps (excluding top 2)" "limit:100,legendPosition:bottom,height:900px">}}
Month	Embed Player	Desktop Browser	Ex Apple/Spotify²	Mobile Browser	CastBox	Overcast	Pocket Casts	Storybutton	PodcastAddict	Amazon Music	Other	Alexa	iTunes	Podbean	AntennaPod	YouTube Music	NPR One	Audible	Transistor Site	Player FM	iVoox	iHeartRadio	Chromecast	Private Web Player	PodcastRepublic	FMRadio	Samsung	Downcast	Podcast Guru	Snipd	Pandora	JioSaavn	Podimo	Radio thmanyah	Google Podcasts	Deezer	audiobookshelf	The Podcast App	SiriusXM	Global Player	Facebook	TuneIn	Anghami	Castro	gPodder	Fountain	iCatcher	myTuner	BeyondPod	RSSRadio	Windows Media Player	VictorReader	Sonos	DoggCatcher	VLC	Earmark	radio.de	Roya Waves	MusicBee	Xiaoyuzhou	Rhythmbox	PodCruncher	PodMe	Apple iMessage	Garmin Watch	Roku	Castamatic	MediaMonkey	Podverse	Zune	Podplay	Mimir	Neuecast	Twitter	FocusPodcast	CloudPlayer	NetCast	NRC Audio	Queue	Bose	RadioPlayer	Metacast	Podurama	Squeezebox	Podeo	KKBOX	Podcini	Luminary	Procast	Cooler	PeaCast	BashPodder	Anytime Podcast Player	Reeder	Gaana	Winamp	Outcast	Podkicker	Sony Bravia	TikTok	Himalaya	Podcast Player	Clementine	Outlook	Amazon Fire TV	MoonFM	ServeStream	'sodes	Stitcher	Playapod	Instacast	RadioPublic	Samsung Free	Podbbang	Nvidia Shield	Kodi	WynkMusic	Goodpods	AllYouCanBooks	Hubhopper	Xbox	Repod	Playstation 5
Mar 2025	1.853	2.966		2.464	2.431	1.989	1.734	1.513	1.235	0.841	0.729	0.534	0.652	0.503	0.497	0.445	0.074	0.374	0.303	0.262	0.224	0.242	0.229	0.246	0.203	0.144	0.144	0.123	0.11	0.108	0.116	0.042	0.113	0.124	0.069	0.074	0.04	0.058	0.057	0.048	0.058	0.047	0.029	0.036	0.029	0.024	0.023	0.02	0.018	0.018	0.015	0.011	0.012	0.009	0.012	0.008	0.007	0.002	0.007	0.004	0.007	0.007	0.007	0.004	0.004	0.004	0.003	0.005	0.002	0.001	0.003	0.001	0.003	0.001	0.001	0.002	0.001	0.002	0.001	0.001	0.001	0.001	0.001	0	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0	0	0.001	0	0	0	0	0	0	0	0	0.001	0	0	0	0	0	0	0.001	0	0	0		0	0				0	0	0	0
Apr 2025	2.566	2.457		2.443	2.351	1.85	1.56	1.352	1.155	0.735	0.718	0.641	0.532	0.47	0.467	0.441	0.366	0.342	0.277	0.269	0.24	0.228	0.213	0.208	0.192	0.153	0.137	0.12	0.103	0.097	0.09	0.083	0.078	0.076	0.072	0.069	0.066	0.057	0.056	0.049	0.047	0.043	0.035	0.034	0.028	0.022	0.02	0.019	0.018	0.015	0.015	0.012	0.01	0.01	0.008	0.008	0.008	0.008	0.008	0.007	0.005	0.005	0.005	0.004	0.004	0.004	0.003	0.003	0.003	0.003	0.003	0.002	0.002	0.002	0.002	0.002	0.002	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0.001	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0			
{{< /graph >}}

---

Transistor currently only publishes monthly data about top apps.  We'd love to see more data in future, such as top countries, top devices and monthly downloads!

---

Data provided by [Transistor](https://transistor.fm/global-stats/), visualized by [John Spurlock](https://twitter.com/johnspurlock)

{{% funding %}}

---
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/transistor-stats-visualized.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*