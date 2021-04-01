---
title: "Aggregator Hubs, using WebSub Subscription Lists"
slug: "aggregator-hubs"
date: 2021-03-30T16:01:41-05:00
draft: false
---
Reduce feed polling, improve feed change notification reliability.  Turn pollers into pushers!

---

*[Modify](https://github.com/johnspurlock-skymethod/livewire-web/blob/master/content/posts/aggregator-hubs.md) this proposal, [Discuss](https://github.com/johnspurlock-skymethod/livewire-web/discussions) this proposal*

---

### Current state {#current-state}
* Podcasters update their rss feed when new content is available, either directly, or via their podcast hosting provider.
* Aggregators (podcast apps, directories) periodically poll for changes to podcasts of interest, which may number in the [millions](https://podnews.net/update/2-million-podcasts).
* [WebSub](https://www.w3.org/TR/websub/) exists to let podcasters tell aggregators exactly when their feed changes, but suffers from problems in practice:
  * Not widely used by podcasters
  * Vast majority use [Google's hub](https://pubsubhubbub.appspot.com/) - free to use, and best-effort, but not always timely or reliable
  * Requires either the hosting CMS to send WebSub pings (not always available), or some other out-of-band process (not always reliable)

Aggregators, therefore, fallback to aggressive polling of every feed.  The more aggregators there are, the more each feed is hammered, wasting resources and $$$.

### Proposal {#proposal}
Perhaps the most important change to improve the current situation would be for **podcast hosting companies to provide timely and reliable WebSub hubs for the feeds they control**.

In the meantime, aggregators will be polling.  Since they are already polling, they also know when feed contents change, and can offer to host their own hubs - turning polling into pushes!  Federated apps & aggregators can delegate / rely on these intermediate hubs to lessen their own need to poll so aggressively, if only for a subset of feeds.

These new intermediate hubs, called **Aggregator Hubs**, should speak [WebSub](https://www.w3.org/TR/websub/) to each other instead of defining a new protocol - it is stable, well-documented, and already deals specifically with notification about web resource ("Topic URL") updates.

In order to facilitate bulk subscription and delegation, this proposal defines subscription list resources that represent multiple underlying feed subscriptions.  They are simple to implement (can be hosted static files), use WebSub and HTTPS for communication, and JSON for resource representation.

In general, Aggregator Hubs should follow the [WebSub spec](https://www.w3.org/TR/websub/), with the following additional constraints:
* Must use HTTPS
* Must provide secret in subscription requests (5.1) for content validation
* Must do Subscription Validation 5.2, and Verification of Intent 5.3

There is nothing in this proposal that modifies or extends WebSub in any way, it just defines two well-defined subscribable resource types to standarize [subscription list]({{< ref "#subscription-list" >}}) resources and their associated [requests]({{< ref "#subscription-list-request" >}}).

[JSON](https://www.json.org/json-en.html) is used to describe both resource types.  This allows either party to fetch the current state of the resource, in case WebSub pings are dropped.
* Large lists can include links to other lists to keep the top-level JSON file smaller, as shown in the examples below.
* Content-based ETags are used for conditional requests.
* Must use `utf-8` for encoding, and `application/json` for content type.

It is up to the hub whether or not they want to be subscribable by others, it is also up to the hub how they want to do authentication and authorization to limit subscribers.  e.g. they might use a [Bearer token](https://oauth.net/2/bearer-tokens/) or request signing.

It is up to the hub to define expected expiration dates for the WebSub subscriptions, or perhaps to disable expiration entirely for hub-to-hub communication.

---
### Subscription List resources {#subscription-list}

Subscription List resources are named lists of feeds and corresponding underlying feed subscription status.  These can either be created to correspond with a [Subscription List Request](({{< ref "#subscription-list-request" >}})) from another party, or standalone named lists of feeds that the hub is watching.

Subscription Lists can be either static or dynamic:
* Static Subscription Lists completely enumerate all underlying feeds
* Dynamic Subscription Lists are logical only, e.g. "All feeds managed by this host", or "All feeds I'm polling known to produce new content hourly".  In this case, the underlying feeds are not explicitly enumerated, but subscribers are still sent notifications for underlying feed changes.

Subscription List JSON objects have the following properties:
* `type: "static-subscription-list" | "dynamic-subscription-list` (required)
* `name: string` (required, human readable name describing the list)
* `modified: string` (required, date-time of last content change, must be ISO-8601 e.g. `1970-01-01T00:00:00Z`)
* `hubs: string[]` (array of one or more websub hub urls for [discovery](https://www.w3.org/TR/websub/#discovery), required if subscribable, not necessary for included sublists)
* `feeds` (static lists only, optional array of underlying feed objects)
  * `url: string` (required, the underlying feed url)
  * `status: positive integer` (required, the current subscription status, e.g. `202` if accepted, see https://www.w3.org/TR/websub/#subscription-response-details)
  * `level: positive integer` (required, how close is this hub to polling the underlying url: `1`=hub is polling directly, `2`=hub is subscribed to another agg hub with level=`1`, etc)
* `includes` (static lists only, optional array of reference objects to other static subscription lists)
  * `url: string` (required, the url to another Static Subscription List)
  * `etag: string` (required, strong etag value, without embedded surrounding double quotes, can be used for in-none-match conditionals)

#### Example 1: Static Subscription List, no inclusion

```
https://hub2.fm/subscription-lists/b7244c0f-e3e3-4886-8aa5-55ef1ba2c0cf.json
Content-Type: application/json; charset=UTF-8
ETag: "24c5f1231737"
{
  "type": "static-subscription-list",
  "name": "Feeds to watch for Hub1",
  "modified": "2021-03-27T12:54:47.725Z",
  "hubs": [
    "https://websub.hub2.fm"
  ],
  "feeds": [
    { "url": "https://example1.com/feed1.xml", "status": 202, "level": 1 },
    { "url": "https://example2.com/feed2.xml", "status": 202, "level": 1 },
  ]
}
```

#### Example 2: Dynamic Subscription List

```
https://hub2.fm/subscription-lists/b7244c0f-e3e3-4886-8aa5-55ef1ba2c0cf.json
Content-Type: application/json; charset=UTF-8
ETag: "24c5f1231737"
{
  "type": "dynamic-subscription-list",
  "name": "All feeds managed by hub2.fm",
  "modified": "2021-03-27T12:54:47.725Z",
  "hubs": [
    "https://websub.hub2.fm"
  ],
}
```

#### Example 3: Static Subscription List with inclusion

```
https://hub2.fm/subscription-lists/b7244c0f-e3e3-4886-8aa5-55ef1ba2c0cf.json
Content-Type: application/json; charset=UTF-8
ETag: "d50d8036590b"
{
  "type": "static-subscription-list",
  "name": "Feeds to watch for Hub1",
  "modified": "2021-03-27T12:54:47.725Z",
  "hubs": [
    "https://websub.hub2.fm"
  ],
  "includes": [
    { "url": "https://hub2.fm/subscription-lists/sublist-1.json", "etag": "24c5f1231737" },
  ]
}

https://hub2.fm/subscription-lists/sublist-1.json
Content-Type: application/json; charset=UTF-8
ETag: "24c5f1231737"
{
  "type": "static-subscription-list",
  "name": "Feeds to watch for Hub1 - Sublist 1",
  "modified": "2021-03-27T12:54:47.725Z",
  "feeds": [
    { "url": "https://example1.com/feed1.xml", "status": 202, "level": 1 },
    { "url": "https://example2.com/feed2.xml", "status": 202, "level": 1 },
  ]
}
```

---

### Subscription List Request resources {#subscription-list-request}

Subscription List Request resources are essentially named lists of feeds for another party to subscribe to.  The other party uses the request list to create a corresponding Static Subscription List on their side.

Subscription List Request JSON objects have the following properties:
* `type: "subscription-list-request"` (required)
* `name: string` (required, human readable name describing the list)
* `modified: string` (required, date-time of last content change, must be ISO-8601 e.g. `1970-01-01T00:00:00Z`)
* `hubs: string[]` (array of one or more websub hub urls for [discovery](https://www.w3.org/TR/websub/#discovery), required if subscribable, not necessary for included sublists)
* `feeds: string[]` (optional array of underlying feed urls)
* `includes:` (optional array of reference objects to other subscription list requests)
  * `url: string` (required, the url to another Subscription List Request)
  * `etag: string` (required, strong etag value, without embedded surrounding double quotes, can be used for in-none-match conditionals)

#### Example 1: Subscription List Request with inclusion
```
https://hub1.fm/subscription-list-requests/fab26f5a-6e21-4c8f-9651-0bc18b815817.json
Content-Type: application/json; charset=UTF-8
ETag: "b5d3971829c0"
{
  "type": "subscription-list-request",
  "name": "Delegated feeds for Hub2",
  "modified": "2021-03-26T22:54:47.725Z",
  "hubs": [
    "https://websub.hub1.fm"
  ],
  "feeds": [
    "https://example1.com/feed1.xml"
  ],
  "includes": [
    { "url": "https://hub1.fm/sublist-1.json", "etag": "b5d52dee01db" }
  ]
}

https://hub1.fm/sublist-1.json
Content-Type: application/json; charset=UTF-8
ETag: "b5d52dee01db"
{
  "type": "subscription-list-request",
  "name": "Delegated feeds for Hub2 - Sublist 1",
  "modified": "2021-03-26T12:54:47.725Z",
  "feeds": [
    "https://example2.com/feed2.xml"
  ],
}
```

---

### Delegation scenario {#delegation-scenario}
*Hub1 gives Hub2 a list of feeds to watch on its behalf*

![Alt Text](/hubs.png)

Agreement and setup, out of band (e.g. over email):
* Owner of Hub1 gives owner of Hub2 the Subscription List Request URL
* Owner of Hub2 gives owner of Hub1 the Subscription List URL

Subscription List Request URL and Subscription List URL should be [capability URLs](https://www.w3.org/TR/capability-urls/)

Typical flow:
* Hub1 creates the Subscription List Request (JSON resource with list of feeds to watch), makes it available via the agreed-upon Subscription List Request URL
* Hub1 fetches the agreed-upon Subscription List URL on Hub2, and subscribes using a hub discovered in the `hubs` property.

 
* Hub2 fetches the agreed-upon Subscription List Request Url on Hub1, and subscribes using a hub discovered in the `hubs` property.
* Hub2 fetches the Subscription List Request, creates associated Subscription List, makes it available via agreed-upon Subscription List URL

 
* Hub2 polls the feeds in the Subscription List, updating the Subscription List with status as necessary
* Hub2 sends a [CDR](https://www.w3.org/TR/websub/#x7-content-distribution) to Hub1 callback on Subscription List changes, OR if any of the underlying feeds change.
  * The topic in the Link header should reflect the url of the changed entity (the WebSub spec already allows this: "the topic URL in the content distribution request may be different from the topic URL that was originally subscribed to")

 
* Hub1 adds or removes feeds to the Subscription List Request if desired, sending a CDR to Hub2 on changes
* Hub1 can unsubscribe to the Subscription List, indicating that Hub1 is no longer relying on Hub2 for those feeds

 
* Hub2 can update the status of the Subscription List at any time, sending a CDR to Hub1 on changes
* Hub2 can unsubscribe to the Subscription List Request, indicating to Hub1 to stop relying on Hub2 for those feeds 

---

### Dynamic Subscription List scenario: Podcast Host {#podcast-host-scenario}
A podcast hosting company could host a publicly-subscribable Subscription List resource for internet clients to listen for ALL changes to feeds managed by the host.  In this case, no Subscription List Request is needed, and the Subscription List is logical only, would not need to enumerate all underlying feeds.

---

### Dynamic Subscription List scenario: Notifications for logical feed groups  {#feed-groups-scenario}
A smaller delegate Aggregator Hub could create a named Subscription List resource to notify a larger hub about feed changes it finds for the feeds it's polling, without enumerating them.  For example, it could notify the parent when it finds ANY change it knows the parent would care about, or a subset of feeds, say feeds that are known to produce new content hourly.

---

### References {#references}
* WebSub spec: https://www.w3.org/TR/websub/
* Capability URLs: https://www.w3.org/TR/capability-urls/
* WebSub CDR: [Content Distribution Request](https://www.w3.org/TR/websub/#x7-content-distribution) (the "ping")

---

*[Modify](https://github.com/johnspurlock-skymethod/livewire-web/blob/master/content/posts/aggregator-hubs.md) this proposal, [Discuss](https://github.com/johnspurlock-skymethod/livewire-web/discussions) this proposal*
