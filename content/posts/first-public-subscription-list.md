---
title: "First public WebSub Subscription List is now available"
description: "Here is the first known publicly-available working example of a WebSub static Subscription List, it contains a handful of podcast feeds that are known to update frequently."
slug: "first-public-subscription-list"
date: 2021-04-06T17:56:00-05:00
draft: false
---

---

Here is the first known publicly-available working example of a WebSub static [Subscription List](https://livewire.io/aggregator-hubs/#subscription-list), it contains a handful of podcast feeds that are known to update frequently:

* https://livewire.io/lists/often.json

---

As described in the [spec](https://livewire.io/aggregator-hubs), any working WebSub subscriber can subscribe to this resource (using the hub specified in the resource itself), and not only receive updates of when it changes, but also when any of the underlying feeds change! 

Feel free to use this as a test, there is no http authentication required for this list to keep things simple.

---

*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/first-public-subscription-list.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
