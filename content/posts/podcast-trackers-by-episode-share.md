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

Of these, 29.55% had one other tracker, 17.04% had 2 other trackers, 2.18% had 3 other trackers, and 0.01% had 4 other trackers.

35.85% also included Podtrac, 22.01% also included Podsights, 5.17% also included Podcorn, 4.80% also included Adswizz, 1.59% also included Firstory, 0.38% also included Blubrry, 0.36% also included Magellan AI, 0.05% also included Backtracks, and 0.01% also included Feedpress.

For episodes that used Chartable, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "24.14%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "17.12%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "8.52%" >}}
4. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "5.60%" >}}
5. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "5.54%" >}}
6. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "4.87%" >}}
7. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "3.99%" >}}
8. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "3.71%" >}}
9. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.61%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "3.48%" >}}
---

### 2. [Podtrac](https://analytics.podtrac.com/)

Podtrac was found on 4.06% of new episodes in December.

Of these, 28.97% had one other tracker, 18.10% had 2 other trackers, 2.37% had 3 other trackers, and 0.01% had 4 other trackers.

39.03% also included Chartable, 20.81% also included Podsights, 9.44% also included Adswizz, 1.53% also included Podcorn, 1.24% also included Blubrry, 0.17% also included Feedpress, 0.10% also included Backtracks, 0.02% also included Magellan AI, and 0.02% also included Médiamétrie.

For episodes that used Podtrac, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "23.79%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "15.33%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "13.55%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "8.13%" >}}
5. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "3.87%" >}}
6. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "3.58%" >}}
7. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "3.21%" >}}
8. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "2.43%" >}}
9. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "2.21%" >}}
10. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "2.00%" >}}
---

### 3. [Podcorn](https://podcorn.com/)

Podcorn was found on 2.27% of new episodes in December.

Of these, 9.29% had one other tracker, 2.05% had 2 other trackers, 0.40% had 3 other trackers, and 0.02% had 4 other trackers.

10.08% also included Chartable, 2.75% also included Podtrac, 1.23% also included Podsights, 0.31% also included Blubrry, 0.20% also included Magellan AI, 0.06% also included Adswizz, and 0.03% also included Backtracks.

For episodes that used Podcorn, here are the top underlying podcast hosts:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "60.67%" >}}
2. {{< a "https://rss.com/" "RSS Podcasting" >}} {{< span "weak" "11.12%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "6.22%" >}}
4. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "4.67%" >}}
5. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "4.49%" >}}
6. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "2.56%" >}}
7. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "2.36%" >}}
8. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "1.87%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.23%" >}}
10. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.22%" >}}
---

### 4. [Blubrry](https://create.blubrry.com/resources/podcast-media-download-statistics/)

Blubrry was found on 1.57% of new episodes in December.

Of these, 3.83% had one other tracker, 0.79% had 2 other trackers, 0.01% had 3 other trackers, and 0.01% had 4 other trackers.

3.20% also included Podtrac, 1.06% also included Chartable, 0.60% also included Feedpress, 0.45% also included Podcorn, 0.10% also included Adswizz, and 0.08% also included Podsights.

For episodes that used Blubrry, here are the top underlying podcast hosts:

1. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "78.00%" >}}
2. {{< a "https://aws.amazon.com/s3/" "Amazon S3" >}} {{< span "weak" "4.96%" >}}
3. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "3.02%" >}}
4. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "2.07%" >}}
5. {{< a "https://archive.org/" "Internet Archive" >}} {{< span "weak" "1.52%" >}}
6. {{< a "https://aws.amazon.com/cloudfront/" "Amazon CloudFront" >}} {{< span "weak" "1.43%" >}}
7. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "1.24%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "0.93%" >}}
9. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "0.83%" >}}
10. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "0.74%" >}}
---

### 5. [Adswizz](https://www.adswizz.com/audiomax/)

Adswizz was found on 1.24% of new episodes in December.

Of these, 36.84% had one other tracker, 7.07% had 3 other trackers, and 6.33% had 2 other trackers.

31.01% also included Podtrac, 17.16% also included Chartable, 12.26% also included Podsights, 10.01% also included Médiamétrie, 0.13% also included Blubrry, and 0.12% also included Podcorn.

For episodes that used Adswizz, here are the top underlying podcast hosts:

1. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "27.53%" >}}
2. {{< a "https://futurimedia.com/" "Futuri Media" >}} {{< span "weak" "21.26%" >}}
3. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "14.84%" >}}
4. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "10.94%" >}}
5. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "10.01%" >}}
6. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "7.14%" >}}
7. {{< a "https://www.bbc.co.uk/" "BBC" >}} {{< span "weak" "3.71%" >}}
8. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.87%" >}}
9. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.44%" >}}
10. {{< a "https://www.washingtonpost.com/" "The Washington Post" >}} {{< span "weak" "0.39%" >}}
---

### 6. [Podsights](https://podsights.com/)

Podsights was found on 1.19% of new episodes in December.

Of these, 61.93% had 2 other trackers, 19.73% had one other tracker, 8.08% had 3 other trackers, and 0.04% had 4 other trackers.

81.64% also included Chartable, 70.90% also included Podtrac, 12.71% also included Adswizz, 2.33% also included Podcorn, 0.31% also included Magellan AI, and 0.10% also included Blubrry.

For episodes that used Podsights, here are the top underlying podcast hosts:

1. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.74%" >}}
2. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "31.60%" >}}
3. {{< a "https://noxsolutions.com/podcasting" "Nox Solutions" >}} {{< span "weak" "13.94%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "5.12%" >}}
5. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "4.72%" >}}
6. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "2.41%" >}}
7. {{< a "https://www.wnyc.org/" "WNYC" >}} {{< span "weak" "1.76%" >}}
8. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "1.37%" >}}
9. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "1.32%" >}}
10. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "0.73%" >}}
---

### 7. [Médiamétrie](https://www.mediametrie.fr/)

Médiamétrie was found on 0.59% of new episodes in December.

Of these, 21.23% had one other tracker.

21.12% also included Adswizz, and 0.11% also included Podtrac.

For episodes that used Médiamétrie, here are the top underlying podcast hosts:

1. {{< a "https://www.akamai.com/" "Akamai CDN" >}} {{< span "weak" "30.36%" >}}
2. {{< a "https://www.audiomeans.fr/" "Audiomeans" >}} {{< span "weak" "23.73%" >}}
3. {{< a "https://www.streamakaci.com/" "Streamakaci" >}} {{< span "weak" "23.31%" >}}
4. {{< a "https://www.europe1.fr/" "Europe 1" >}} {{< span "weak" "21.12%" >}}
5. {{< a "https://www.ausha.co/" "Ausha" >}} {{< span "weak" "1.17%" >}}
6. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.03%" >}}
---

### 8. [Feedpress](https://feedpress.com/)

Feedpress was found on 0.19% of new episodes in December.

Of these, 8.46% had one other tracker.

4.87% also included Blubrry, 3.46% also included Podtrac, and 0.13% also included Chartable.

For episodes that used Feedpress, here are the top underlying podcast hosts:

1. {{< a "https://feedpress.com/" "Feedpress" >}} {{< span "weak" "68.76%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "10.98%" >}}
3. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "5.03%" >}}
4. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "4.35%" >}}
5. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.96%" >}}
6. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "1.73%" >}}
7. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "1.34%" >}}
8. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "1.21%" >}}
9. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "1.01%" >}}
10. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "0.85%" >}}
---

### 9. [Firstory](https://firstory.me/)

Firstory was found on 0.10% of new episodes in December.

Of these, 70.63% had one other tracker.

70.63% also included Chartable.

For episodes that used Firstory, here are the top underlying podcast hosts:

1. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "99.30%" >}}
2. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "0.26%" >}}
---

### 10. [Magellan AI](https://www.magellan.ai/pages/magellan-ai-verified-downloads)

Magellan AI was found on 0.03% of new episodes in December.

Of these, 33.25% had one other tracker, 28.47% had 2 other trackers, and 1.20% had 4 other trackers.

60.77% also included Chartable, 16.75% also included Podcorn, 14.11% also included Podsights, and 3.35% also included Podtrac.

For episodes that used Magellan AI, here are the top underlying podcast hosts:

1. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "38.04%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "34.93%" >}}
3. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "21.05%" >}}
4. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.15%" >}}
5. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.15%" >}}
6. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "1.67%" >}}
---

### 11. [Backtracks](https://backtracks.fm/publishers/switchboard/)

Backtracks was found on 0.01% of new episodes in December.

Of these, 46.41% had one other tracker, and 6.63% had 2 other trackers.

34.25% also included Podtrac, 19.89% also included Chartable, and 5.52% also included Podcorn.

For episodes that used Backtracks, here are the top underlying podcast hosts:

1. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "34.25%" >}}
2. {{< a "https://www.streamguys.com/" "StreamGuys" >}} {{< span "weak" "31.49%" >}}
3. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "7.18%" >}}
4. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "6.08%" >}}
5. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "3.31%" >}}
6. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "2.76%" >}}
7. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "2.21%" >}}
8. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "1.66%" >}}
9. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "1.66%" >}}
10. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "0.55%" >}}

---

Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

And thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

---
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
 - [Podcast Tracker Rankings by Episode Share (November 2021)](/archive/podcast-trackers-by-episode-share-november-2021/)
 - [Podcast Tracker Rankings by Episode Share (October 2021)](/archive/podcast-trackers-by-episode-share-october-2021/)
 - [Podcast Tracker Rankings by Episode Share (September 2021)](/archive/podcast-trackers-by-episode-share-september-2021/)

---
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/podcast-trackers-by-episode-share.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
