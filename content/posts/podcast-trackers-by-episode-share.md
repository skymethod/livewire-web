---
title: "Podcast Tracker Rankings by Episode Share (December 2021)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "podcast-trackers-by-episode-share"
images:
- trackers-2021-12.png
date: 2022-01-07T13:05:00-06:00
lastmod: 2022-01-07T13:05:00-06:00
draft: false
---

Now that we have a good idea of [which podcast hosts are producing new podcast episodes](/podcast-hosts-by-episode-share),
let's turn our attention to third-party podcast analytics services.

These services are typically provided by a company that is not the podcast host, but can provide tracking and analytics 
by being specified as the underlying media file url, which then redirects back to the host.  Sometimes, these services
are implemented as custom prefixes (taking the original media url and adding a prefix to it), but not always.

By intercepting every episode media file request, these analytics services can provide a view that is potentially larger than
what the underlying podcast host analytics can provide.

Podtrac, one of the most popular services, released some 
[interesting data about their US download figures for September](https://podnews.net/article/podtrac-us-downloads-and-users-sep21).

But how representative of the entire podcast world is this data?  How many podcasters use services like these?

---

We already did the work of analyzing _every single new podcast episode published_ (about 1.5 million in December 2021), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of the new episodes that were published in November, how many
of them included one or more of these tracking services?  Some episodes had as many as *six* of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

Below is the ranking of podcast analytics services ordered by new episodes published during 
the month of November 2021.

---

### 1. [Chartable](https://chartable.com/)

Chartable was found on 4.42% of new episodes in December.

Of these, 29.47% had one other tracker, 17.11% had 2 other trackers, 2.20% had 3 other trackers, and 0.01% had 4 other trackers.

35.87% also included Podtrac, 22.11% also included Podsights, 5.17% also included Podcorn, 4.82% also included Adswizz, 1.57% also included Firstory, 0.37% also included Blubrry, 0.36% also included Magellan AI, 0.05% also included Backtracks, and <0.01% also included Feedpress.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "24.03%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.24%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "8.49%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.58%" >}}
5. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.58%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.90%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "4.02%" >}}
8. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "3.68%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.63%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.46%" >}}
---

### 2. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 4.06% of new episodes in December.

Of these, 28.88% had one other tracker, 18.13% had 2 other trackers, 2.39% had 3 other trackers, and 0.01% had 4 other trackers.

38.99% also included Chartable, 20.89% also included Podsights, 9.43% also included Adswizz, 1.52% also included Podcorn, 1.23% also included Blubrry, 0.17% also included Feedpress, 0.10% also included Backtracks, 0.02% also included Magellan AI, and 0.01% also included Médiamétrie.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.72%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "15.46%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "13.64%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "8.14%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.90%" >}}
6. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "3.61%" >}}
7. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "3.16%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.42%" >}}
9. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "2.17%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.98%" >}}
---

### 3. [Podcorn](https://podcorn.com/)

Podcorn was found on 2.26% of new episodes in December.

Of these, 9.31% had one other tracker, 2.03% had 2 other trackers, 0.40% had 3 other trackers, and 0.02% had 4 other trackers.

10.10% also included Chartable, 2.72% also included Podtrac, 1.21% also included Podsights, 0.31% also included Blubrry, 0.19% also included Magellan AI, 0.07% also included Adswizz, and 0.03% also included Backtracks.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "60.86%" >}}
2. {{< a "https://rss.com/" "RSS Podcasting" >}} {{< span "weak" "11.07%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "6.21%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "4.64%" >}}
5. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "4.44%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.54%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.37%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.85%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.23%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.22%" >}}
---

### 4. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.57% of new episodes in December.

Of these, 3.84% had one other tracker, 0.78% had 2 other trackers, 0.01% had 3 other trackers, and 0.01% had 4 other trackers.

3.19% also included Podtrac, 1.05% also included Chartable, 0.60% also included Feedpress, 0.44% also included Podcorn, 0.10% also included Adswizz, and 0.08% also included Podsights.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "78.02%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "4.98%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "3.02%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.07%" >}}
5. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.49%" >}}
6. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.45%" >}}
7. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.24%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.94%" >}}
9. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "0.83%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.75%" >}}
---

### 5. [Adswizz](https://www.adswizz.com/audiomax/)

Adswizz was found on 1.24% of new episodes in December.

Of these, 36.75% had one other tracker, 7.12% had 3 other trackers, and 6.29% had 2 other trackers.

30.94% also included Podtrac, 17.20% also included Chartable, 12.30% also included Podsights, 10.00% also included Médiamétrie, 0.13% also included Blubrry, and 0.12% also included Podcorn.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "27.64%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "21.43%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "14.68%" >}}
4. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "10.99%" >}}
5. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "10.00%" >}}
6. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "7.01%" >}}
7. {{< a "https://www.bbc.co.uk/" "BBC" >}} {{< span "weak" "3.70%" >}}
8. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.87%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.41%" >}}
10. {{< a "https://www.washingtonpost.com/" "The Washington Post" >}} {{< span "weak" "0.39%" >}}
---

### 6. [Podsights](https://podsights.com/)

Podsights was found on 1.20% of new episodes in December.

Of these, 61.91% had 2 other trackers, 19.68% had one other tracker, 8.12% had 3 other trackers, and 0.03% had 4 other trackers.

81.64% also included Chartable, 70.94% also included Podtrac, 12.73% also included Adswizz, 2.28% also included Podcorn, 0.31% also included Magellan AI, and 0.10% also included Blubrry.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.50%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "31.83%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "14.01%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.17%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.70%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.41%" >}}
7. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.72%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.36%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.30%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.74%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/)

Médiamétrie was found on 0.59% of new episodes in December.

Of these, 21.23% had one other tracker.

21.13% also included Adswizz, and 0.10% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "30.06%" >}}
2. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "23.85%" >}}
3. {{< a "https://www.streamakaci.com/" "Streamakaci" >}} {{< span "weak" "23.46%" >}}
4. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "21.13%" >}}
5. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "1.16%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.03%" >}}
---

### 8. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.20% of new episodes in December.

Of these, 8.42% had one other tracker.

4.84% also included Blubrry, 3.47% also included Podtrac, and 0.10% also included Chartable.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "68.89%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "10.96%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.05%" >}}
4. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "4.21%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.97%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "1.77%" >}}
7. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "1.34%" >}}
8. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.20%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.00%" >}}
10. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.84%" >}}
---

### 9. [Firstory](https://firstory.me/)

Firstory was found on 0.10% of new episodes in December.

Of these, 71.17% had one other tracker.

71.17% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.26%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.27%" >}}
---

### 10. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.03% of new episodes in December.

Of these, 32.67% had one other tracker, 28.43% had 2 other trackers, and 1.00% had 4 other trackers.

60.35% also included Chartable, 16.46% also included Podcorn, 14.21% also included Podsights, and 2.49% also included Podtrac.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "36.91%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "35.91%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "21.95%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "1.75%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.75%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.75%" >}}
---

### 11. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.01% of new episodes in December.

Of these, 45.66% had one other tracker, and 6.94% had 2 other trackers.

34.10% also included Podtrac, 20.23% also included Chartable, and 5.20% also included Podcorn.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "35.26%" >}}
2. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "31.21%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "6.36%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "5.78%" >}}
5. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "3.47%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.31%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.31%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "1.73%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.73%" >}}
10. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "0.58%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
*Updated 2022-01-07, with data for the month of December 2021.*

*Updated 2021-12-04, with data for the month of November 2021.*

*Updated 2021-11-18, added Backtracks.*

*Updated 2021-11-14, with data for the month of October 2021.*

*Updated 2021-10-21: Added Adswizz and tweaked the host identification to choose the last known host in the redirect chain instead of the first, in an attempt to better capture customer-driven host migrations.*

*Updated 2021-10-14: Added a section about how direct server-to-server analytics integrations are not publically visible, and thus out of scope.*

*Updated 2021-10-13: Removed Podtrac as a host under itself, even when it is the last media file url in the redirect chain.*

---
Previous versions:
 - [Podcast Tracker Rankings by Episode Share (November 2021)](/archive/podcast-trackers-by-episode-share-november-2021/)
 - [Podcast Tracker Rankings by Episode Share (October 2021)](/archive/podcast-trackers-by-episode-share-october-2021/)
 - [Podcast Tracker Rankings by Episode Share (September 2021)](/archive/podcast-trackers-by-episode-share-september-2021/)

---
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/podcast-trackers-by-episode-share.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
