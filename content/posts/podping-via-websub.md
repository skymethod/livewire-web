---
title: "Podping via WebSub"
description: "We've created a publicly-available subscribable list, which makes Podping notifications available for free via standard WebSub."
slug: "podping-via-websub"
date: 2021-05-21T11:08:57-05:00
draft: false
---

---

The [Podcast Index project](https://podcastindex.org/) has recently created its own internal system for sending and receiving podcast feed notification updates, called [Podping](https://podping.cloud/).

Anyone can listen to these pings by [polling the Hive blockchain](https://github.com/Podcastindex-org/podping.cloud#simple-watcher-simple-watcherpy) on their own server.

This sounded like a great use case for a [subscribable dynamic subscription list](/aggregator-hubs#podcast-host-scenario) to represent the logical list of feeds participating in the Podping system.

So we've created a publicly-available subscribable list, which makes these pings available for free via standard [WebSub](https://www.w3.org/TR/websub) for anyone who wants to receive these updates via http webhook-style callbacks.

The subscribable list url is:
* https://livewire.io/lists/podping.json

You can preview the event stream by creating a temporary short-lived WebSub listener using our WebSub testing tool:
* {{< button listen-using-test-livewire-io "Start listening using test.livewire.io" >}}

You can also preview the event stream by creating a WebSub listener using the excellent [webhook.site](https://webhook.site/) service:
* {{< button listen-using-webhook-site "Start listening using webhook.site" >}}

{{< podping-via-websub-script >}}

Hope that helps!

---

*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/podping-via-websub.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
