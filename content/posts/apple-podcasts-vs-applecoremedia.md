---
title: "Apple Podcasts vs AppleCoreMedia downloads, before and after iOS 16.4"
description: "Apple made a change under the hood, did it make a difference?"
slug: "apple-podcasts-vs-applecoremedia"
images:
- apple-podcasts-vs-applecoremedia.png
date: 2023-06-18T15:57:00-05:00
lastmod: 2023-06-18T15:57:00-05:00
draft: false
---

Apple made a change under the hood, did it make a difference?

{{% subscribe %}}

---

[As of iOS 16.4](https://podcasters.apple.com/4844-ios-164-whats-new-for-apple-podcasts), released on March 27th, 2023, the Apple Podcasts app now sends a User-Agent that looks like:
```
Podcasts/4022.610.1 CFNetwork/1408.0.4 Darwin/22.5.0
```
...when streaming a podcast episode, instead of a more generic one that looked like:
```
AppleCoreMedia/1.0.0.20D67 (iPhone; U; CPU OS 16_3_1 like Mac OS X; en_us)
```

Since [Apple Podcasts is responsible for the most podcast episode downloads](https://livewire.io/buzzsprout-stats-visualized/), and downloads are still used across the industry to measure listenership for ad campaign purposes: any time Apple changes something, it's worth measuring the impact.

We'd expect to see a rise in Apple Podcast download share, now that these requests can be properly attributed, in whatever portion of downloads are streamed in Apple Podcasts (i.e. the listener hit play without the file already being downloaded, typically a fraction of overall downloads).

---

Since we are midway through June, I used [data from OP3](https://op3.dev/api/docs#tag/redirect-logs/operation/queryRedirectLogs) for the first 15 days in June, and compared it to the first 15 days in each of May, April, and March (before 16.4 was publicly available).

[OP3](https://op3.dev) is a free podcast download measurement service, measuring a wide variety of shows - some of which have a high proportion of Apple Podcasts listeners, some that don't.  For the first 15 days of March, OP3 measured 2.3 million [IAB-style downloads](https://op3.dev/download-calculation), increasing to 2.9 million downloads for the first 15 days of June.

_One tweak I made to the Download calculation for this analysis was to include Apple Watch speculative downloads (the `atc/` user-agent) as a separate item - so we can see if those changed over this period as well.  Normally these are excluded from podcasting stats reporting like OP3, but they'll be useful to see here for this custom analysis in relation to the others. Broken out below as ‘Apple Podcasts (Watch)’_

---

{{< graph downloads "OP3 download share, first 15 days of each month" "limit:12,height:600px">}}
Date	Apple Podcasts	Spotify	CastBox	AppleCoreMedia	Overcast	Chrome	Apple Podcasts (Watch)	Podcast Addict	Pocket Casts	Podverse	Google Podcasts	Fountain	Podcast Republic	Safari	iTunes	Stitcher	AntennaPod	Podbean	Firefox	Dalvik	Amazon Music	Downcast
March 2023	26.318581209502295	21.373481131292298	8.903880351813905	11.869655832324758	4.1576259115396885	3.634230636472074	2.616714218926819	2.531032765182133	2.6082378282962893	2.0372611645861642	2.092008161802937	0.887617915769145	0.9229653385531589	0.917503746652044	0.38034525999362084	0.9586623032188438	0.6989526851370422	0.5919928693456139	0.5661704628371441	0.49910211429145673	0.40214793486287037	0.25595204285383466
April 2023	27.505907951143843	17.809609455851295	8.547002603106082	11.569326552247064	4.3157490743087035	3.8742337701399525	2.8733266600397354	2.8059997053087455	3.170147688999019	2.3773499780285503	2.2483030260619206	1.174679327669292	0.8909411995324927	0.9991685186287904	0.44060254364625223	1.0147723770848427	0.7957967812586795	0.6156352400321118	0.7311211785216148	0.7390752345033909	0.3862715601641752	0.31464159154140475
May 2023	30.020833408209008	21.77204968869689	7.36576987569839	7.310421775683655	4.1187612088887615	3.59079783926768	2.362597143702596	2.6999969251055544	2.971905448193819	2.434278124601911	2.1990287326922378	1.2399412016288156	0.8665212281527751	1.055527402301219	0.4393505024257722	0.9699494958570788	0.7496752392327779	0.5628254845654276	0.7804241836854088	0.7648899766827161	0.3368806433797323	0.3674299193618915
June 2023	30.34499160517316	24.4497041501936	6.918187685305821	5.340195302008087	4.142484944793255	3.9789785377964244	2.8220929304046907	2.598749400678154	2.5782160379390175	2.066506663145345	1.9748324577847545	1.2365647338457917	0.9936211760500793	0.979171772641057	0.8173591952304524	0.8151122784323988	0.7361936468946054	0.6446231453862329	0.6049045699867915	0.6002378966369878	0.4571957164778162	0.3865042572159733
{{< /graph >}}

This shows the apps with the highest share of OP3 downloads (those above one percent share) for the first 15 days each of March, April, May, and June 2023.

AppleCoreMedia is broken out as a separate item, as it can be sent from any iOS app that uses [AVFoundation](https://developer.apple.com/av-foundation/) for audio streaming (which is most of them except Spotify).

You can see the share for AppleCoreMedia start to fall in the May and June periods, after 16.4 was released - from 11.87% of all downloads in the first 15 days of March down to 5.34% of all downloads in the first 15 days of June.

Similarly, Apple Podcasts’ share rose from 26.32% in March to 30.34% in June.

_Note: Apple Watch speculative downloads remained relatively constant, which is good news: this means Apple is not mixing these these up with the main app and should continue to be excluded from any podcast download reporting stats. Any user-initiated download or play on the Apple Watch is tagged with the normal Apple Podcasts agent and included in that number._

---
Let's keep going!

One of the cool things about OP3 is that it can track these streaming downloads vs normal downloads on Apple platforms, so we can limit our focus to streaming requests and see if we find a similar migration from AppleCoreMedia to Apple Podcasts.

{{< graph streaming-downloads "OP3 iOS streaming download share, first 15 days of each month" "limit:10,height:600px">}}
Date	Apple Podcasts	AppleCoreMedia	Podverse	Safari	Pocket Casts	Fountain	Overcast	Stitcher	iHeartRadio	Audible	Chrome	CastBox	Downcast	TuneIn	Amazon Music	Facebook	Google Podcasts	Snipd	Podimo	Firefox
March 2023	0.46943152784166803	75.273927429322	7.6414252539752034	5.401787941096597	3.4461927274138033	1.368944361002267	1.515537795611619	1.0089729591921566	0.7132920617853916	0.5248543764652416	0.3718873142641786	0.45252755901147806	0.13800289307269814	0.17513620165049243	0.8116676180922346	0.17679888710919964	0.10170092722425747	0.081748701719771	0.030759680986083324	0.06678453259140613
April 2023	9.586697086697086	64.87583362583362	8.182451932451933	5.144348894348894	3.8003100503100504	2.138908388908389	1.5753578253578253	0.936000936000936	0.6383818883818884	0.3917066417066417	0.3943878943878944	0.6308256308256308	0.15624390624390624	0.13235638235638236	0.780975780975781	0.17452517452517452	0.10359385359385359	0.09603759603759604	0.015356265356265357	0.057768807768807766
May 2023	32.93384543562148	41.28204492096319	8.568090735023151	5.633501052095056	3.464583977032077	2.4765392951301415	1.5852467630880398	1.0036062164947757	0.5814150171064115	0.41339554940110645	0.41001260709831505	0.46188438907444956	0.17952147153479583	0.12313909982160619	0.1432112241515017	0.21786148429976476	0.10870521266302963	0.08322038064866791	0.009697767934668618	0.07194390630602998
June 2023	43.11334917919707	32.922878480163845	7.430898580065391	5.478995688302037	3.2810761519750735	2.026220419808611	1.5660069918272075	0.928541988335565	0.6925624811803673	0.535171624371878	0.4563694179100971	0.44227471431530707	0.1488486122055862	0.13987925537253795	0.12493032731745757	0.11916431221049797	0.11638808271455449	0.10549672084585306	0.07709375754120032	0.055097477688724875
{{< /graph >}}

The switchover is more dramatic here, and exactly what we'd expect to see.  Bear in mind these iOS streaming requests are a small fraction of overall downloads across all devices and platforms, about 16% in this OP3 data.

> Although AppleCoreMedia is down to 32.92% of these downloads, and 5.34% of overall downloads, there are still a handful of popular apps that haven't bothered to change it, [I'm keeping track of those apps here](https://docs.google.com/spreadsheets/d/1YKQgt7xwLSdHmgtZew1TVD_RqzuA9W0ec0ab9BF9E0c/edit?usp=sharing), the required change looks [something like this](https://github.com/Automattic/pocket-casts-ios/pull/473/files).

---

It's remarkable how quickly a change to Apple Podcasts can have an effect on the overall podcasting ecosystem.  Thankfully the change landed in the 16.x line, this means it will remain available to older Apple devices that cannot upgrade to the upcoming [iOS 17](https://www.apple.com/ios/ios-17-preview/) later this year.

Let's quantify how quickly podcast listeners update their iOS by looking at the same OP3 data, but this time focusing exclusively on downloads from Apple Podcasts and which OS version they used.

{{< graph ap-distribution "OP3 Apple Podcasts iOS distribution share, first 15 days of each month" "limit:100,height:600px,type:stacked-bar">}}
Date	17.0 (beta)	16.6 (beta)	16.5 (2023-05-18)	16.4 (2023-03-27)	16.3 (2023-01-23)	16.2 (2022-12-13)	16.1 (2022-10-24)	16.0 (2022-09-12)	15	14, 13, 10
March 2023	0.007470962857693099	0	0	1.4272859486130571	44.042820238672356	14.426429278205374	17.111493329260274	4.418659476833374	14.460131621763413	4.105709143794452
April 2023	0.0172253854772617	0	1.180808076019261	19.36970892259165	43.15512170762042	8.05847781322941	11.497075635245352	3.112895808542211	10.602145745724867	3.006540905549576
May 2023	0.014500330580931135	0.0011972750020952311	1.4201011830407326	56.43302510153557	16.385772648119545	4.426724774413435	7.671073968979936	2.280276756768262	8.48309248151208	2.884235480047411
June 2023	0.831405197820438	1.1556281620567994	57.136151999735695	12.713732539978196	8.613667718169815	2.8473748306829303	5.8271274141566725	1.3289040329645667	7.47603928497786	2.069968819457023
{{< /graph >}}

The cumulative share of Apple Podcasts users on iOS 16.4 (the bold red bar) or higher quickly grows from 1.43% percent in March (beta testers) to *71.84%* only a few short months after release.

Any change Apple makes is quickly metabolized.

---
Data collected and visualized by [John Spurlock](https://twitter.com/johnspurlock)

{{% funding %}}

---
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/apple-podcasts-vs-applecoremedia.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*