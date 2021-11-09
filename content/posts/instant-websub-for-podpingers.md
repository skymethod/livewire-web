---
title: "Instant WebSub support for Podpingers"
description: "If your podcast already supports Podping, you can instantly support WebSub as well with only two tags"
slug: "instant-websub-for-podpingers"
images:
- podpingers.png
date: 2021-11-08T19:31:00-06:00
draft: false
---

---

Why isn't your new podcast episode showing up in Google Podcasts right away?  It's probably since your podcast's RSS feed doesn't support [WebSub](https://podnews.net/article/pubsubhubbub-for-podcasters), which is
a way to tell Google (and other apps) as soon as your episode becomes available.  It's not trivial to set up if your host doesn't already support it, you'll need to:
 1. add a few tags to your podcast feed
 2. find (or host) a hub, and 
 3. notify it whenever your feed changes.

The [Podcast Index project](https://podcastindex.org/) has introduced another mechanism for sending and receiving podcast feed notification updates called [Podping](https://podping.cloud/), and it's worked 
with a few existing podcast hosting companies to automatically support it for every podcast they host, with no changes required from the podcaster.

---

Ideally, your podcast _should support both WebSub and Podping_, ensuring large apps/aggregators that look at either mechanism receive your updates as soon as they're published.

Here at Livewire Labs, we want to make it as easy as possible for every podcaster to support both in their own feed.

So today, we're announcing a new free service using our existing WebSub hub.

---

Any podcast that is already Podping-enabled (but not WebSub-enabled) can now add two tags to their feed... _and become automatically WebSub enabled as well!_
```xml
<rss>
  <channel>
    ...
    <link rel="self" href="https://YOUR-FEED-URL"  xmlns="http://www.w3.org/2005/Atom" />
    <link rel="hub" href="https://hub.livewire.io/" xmlns="http://www.w3.org/2005/Atom" />
```

We'll listen for your podping under the hood, and publish out a WebSub ping to any WebSub subscribers for you.

That's it! No steps 2 or 3, and no additional server/subscriptions to manage.

Hope that helps!

 \- [John](https://twitter.com/johnspurlock)

---

*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/instant-websub-for-podpingers.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
