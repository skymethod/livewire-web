---
title: "Podcast Tracker Rankings by Episode Share (September 2021)"
description: "Ranked list of podcast trackers (third-party analytics services), based on number of new episodes published"
slug: "archive/podcast-trackers-by-episode-share-september-2021"
images:
- trackers-2021-09.png
date: 2021-10-13T17:28:00-05:00
lastmod: 2021-10-21T18:35:00-05:00
draft: false
tags:
- archive
---
*This is an archived version, the current version is [here](/podcast-trackers-by-episode-share/).*

Now that we have a good idea of [which podcast hosts are producing new podcast episodes](/podcast-hosts-by-episode-share),
let's turn our attention to third-party podcast analytics services.

These services are typically provided by a company that is not the podcast host, but can provide tracking and analytics 
by being specified as the underlying media file url, which then redirects back to the host.  Sometimes, these services
are implemented as custom prefixes (taking the original media url and adding a prefix to it), but not always.

By intercepting every episode media file request, these analytics services can provide a view that is potentially larger than
what the underlying podcast host analytics can provide.

Podtrac, one of the most popular services, recently released some 
[interesting data about their US download figures for September](https://podnews.net/article/podtrac-us-downloads-and-users-sep21).

But how representative of the entire podcast world is this data?  How many podcasters use the service?

---

We already did the work of analyzing _every single new podcast episode published_ (about 1.9 million in September 2021), 
[identifying which podcast hosting company it belongs to](/podcast-hosts-by-episode-share).

We used the actual media file url (past any tracking redirects) to identify the host
instead of the feed url domain, which can often undercount hosts that offer custom domains.

Let's now take a look at the tracking services themselves.  Of those episodes that were published in September, how many
of them included one or more of these tracking services?  Some episodes had as many as five of these redirecting trackers!

*Note we can only observe "client-side" trackers. There are other podcast analytics services 
such as {{< a "https://www.tritondigital.com/solutions/audience-measurement" "Triton Digital" >}} that receive private request logs 
directly from partner hosts. Like first-party podcast host analytics, the reach of these services is not measurable in a public
way, and thus not included in this analysis.*

Below is the ranking of podcast analytics services ordered by new episodes published during 
the month of September 2021.

---

### 1. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 4.16% of new episodes in September.

Of these, 25.91% had one other tracker, 16.47% had 2 other trackers, 3.03% had 3 other trackers, 0.22% had 4 other trackers, and 0.02% had 5 other trackers.

33.62% also included Chartable, 19.30% also included Podsights, 9.96% also included Adswizz, 2.77% also included FeedBurner, 1.74% also included Blubrry, 1.37% also included Podcorn, 0.12% also included Feedpress, 0.01% also included Médiamétrie, and <0.01% also included Magellan AI.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "19.92%" >}}
2. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "16.04%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "14.30%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "7.77%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "4.02%" >}}
6. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "3.63%" >}}
7. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "3.40%" >}}
8. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "3.09%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.25%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "1.68%" >}}
---

### 2. [Chartable](https://chartable.com/)

Chartable was found on 4.06% of new episodes in September.

Of these, 28.06% had one other tracker, 16.96% had 2 other trackers, 3.09% had 3 other trackers, 0.22% had 4 other trackers, and 0.02% had 5 other trackers.

34.43% also included Podtrac, 23.19% also included Podsights, 5.60% also included Podcorn, 5.35% also included Adswizz, 1.43% also included Firstory, 1.31% also included FeedBurner, 0.70% also included Blubrry, 0.22% also included Magellan AI, and 0.01% also included Feedpress.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "22.67%" >}}
2. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "14.56%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "8.56%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.70%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.28%" >}}
6. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "4.34%" >}}
7. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.24%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "3.91%" >}}
9. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.71%" >}}
10. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "3.48%" >}}
---

### 3. [Podcorn](https://podcorn.com/)

Podcorn was found on 2.09% of new episodes in September.

Of these, 10.31% had one other tracker, 1.88% had 2 other trackers, 0.51% had 3 other trackers, and 0.01% had 4 other trackers.

10.91% also included Chartable, 2.74% also included Podtrac, 1.31% also included Podsights, 0.38% also included Blubrry, 0.23% also included FeedBurner, 0.07% also included Adswizz, and 0.01% also included Magellan AI.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "59.56%" >}}
2. {{< a "https://rss.com/" "RSS Podcasting" >}} {{< span "weak" "10.14%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "6.89%" >}}
4. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "5.26%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "4.20%" >}}
6. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "2.87%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.76%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.00%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.11%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.09%" >}}
---

### 4. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 2.07% of new episodes in September.

Of these, 8.00% had one other tracker, 1.07% had 2 other trackers, 0.15% had 4 other trackers, 0.14% had 3 other trackers, and 0.04% had 5 other trackers.

4.79% also included FeedBurner, 3.49% also included Podtrac, 1.36% also included Chartable, 0.76% also included Feedpress, 0.42% also included Podsights, 0.38% also included Podcorn, and 0.18% also included Adswizz.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "77.62%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "5.21%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "2.42%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.98%" >}}
5. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.65%" >}}
6. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.36%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.35%" >}}
8. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "1.23%" >}}
9. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "0.86%" >}}
10. {{< a "https://analytics.podtrac.com/" "Podtrac" >}} {{< span "weak" "0.71%" >}}
---

### 5. [FeedBurner](https://feedburner.google.com/fb/a/myfeeds)

FeedBurner was found on 1.61% of new episodes in September.

Of these, 11.98% had one other tracker, 2.24% had 2 other trackers, 0.46% had 4 other trackers, 0.22% had 3 other trackers, and 0.05% had 5 other trackers.

7.17% also included Podtrac, 6.17% also included Blubrry, 3.31% also included Chartable, 0.96% also included Adswizz, 0.80% also included Podsights, 0.50% also included Feedpress, and 0.30% also included Podcorn.

For episodes that used FeedBurner, here are the top underlying podcast hosts:

1. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "6.32%" >}}
2. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "5.52%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "4.89%" >}}
4. {{< a "https://awr.org/" "Adventist World Radio" >}} {{< span "weak" "4.52%" >}}
5. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "3.72%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "3.15%" >}}
7. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.02%" >}}
8. {{< a "https://kabbalahmedia.info/" "Kabbalah Media" >}} {{< span "weak" "2.86%" >}}
9. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "2.51%" >}}
10. {{< a "https://analytics.podtrac.com/" "Podtrac" >}} {{< span "weak" "2.31%" >}}
---

### 6. [Podsights](https://podsights.com/)

Podsights was found on 1.16% of new episodes in September.

Of these, 58.16% had 2 other trackers, 19.86% had one other tracker, 10.87% had 3 other trackers, 0.77% had 4 other trackers, and 0.07% had 5 other trackers.

81.34% also included Chartable, 69.30% also included Podtrac, 16.88% also included Adswizz, 2.36% also included Podcorn, 1.11% also included FeedBurner, 0.75% also included Blubrry, and 0.48% also included Magellan AI.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "33.83%" >}}
2. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "28.14%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "15.78%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "6.21%" >}}
5. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "3.43%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "3.38%" >}}
7. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.86%" >}}
8. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.32%" >}}
9. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "1.17%" >}}
10. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "0.88%" >}}
---

### 7. [Adswizz](https://www.adswizz.com/audiomax/)

Adswizz was found on 1.00% of new episodes in September.

Of these, 40.06% had one other tracker, 10.97% had 3 other trackers, 9.52% had 2 other trackers, 0.72% had 4 other trackers, and 0.08% had 5 other trackers.

41.46% also included Podtrac, 21.76% also included Chartable, 19.57% also included Podsights, 10.45% also included Médiamétrie, 1.54% also included FeedBurner, 0.37% also included Blubrry, and 0.15% also included Podcorn.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "27.67%" >}}
2. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "21.43%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "16.17%" >}}
4. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "10.45%" >}}
5. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "6.63%" >}}
6. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "5.83%" >}}
7. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "4.13%" >}}
8. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "3.10%" >}}
9. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.92%" >}}
10. {{< a "https://analytics.podtrac.com/" "Podtrac" >}} {{< span "weak" "1.06%" >}}
---

### 8. [Médiamétrie](https://www.mediametrie.fr/)

Médiamétrie was found on 0.42% of new episodes in September.

Of these, 24.91% had one other tracker.

24.84% also included Adswizz, and 0.06% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.streamakaci.com/" "Streamakaci" >}} {{< span "weak" "28.28%" >}}
2. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "26.08%" >}}
3. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "24.84%" >}}
4. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "12.67%" >}}
5. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "7.72%" >}}
---

### 9. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.32% of new episodes in September.

Of these, 7.80% had one other tracker, and 0.62% had 2 other trackers.

4.88% also included Blubrry, 2.51% also included FeedBurner, 1.60% also included Podtrac, and 0.06% also included Chartable.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "79.73%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.50%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "2.59%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.38%" >}}
5. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "2.25%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "1.95%" >}}
7. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.65%" >}}
8. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "0.90%" >}}
9. {{< a "https://analytics.podtrac.com/" "Podtrac" >}} {{< span "weak" "0.61%" >}}
10. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.56%" >}}
---

### 10. [Firstory](https://firstory.me/)

Firstory was found on 0.08% of new episodes in September.

Of these, 73.83% had one other tracker.

73.83% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "98.30%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.44%" >}}
3. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "0.26%" >}}
---

### 11. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.02% of new episodes in September.

Of these, 36.10% had 2 other trackers, and 21.41% had one other tracker.

56.23% also included Chartable, 34.82% also included Podsights, 1.28% also included Podcorn, and 1.28% also included Podtrac.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "53.35%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "32.27%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "8.63%" >}}
4. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "3.19%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.28%" >}}
6. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.28%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---

*Updated 2021-10-21: Added Adswizz and tweaked the host identification to choose the last known host in the redirect chain instead of the first, in an attempt to better capture customer-driven host migrations.*

*Updated 2021-10-14: Added a section about how direct server-to-server analytics integrations are not publically visible, and thus out of scope.*

*Updated 2021-10-13: Removed Podtrac as a host under itself, even when it is the last media file url in the redirect chain.*

---
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-trackers-by-episode-share-2021-09.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
