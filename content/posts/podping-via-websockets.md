---
title: "Podping via Websockets"
description: "Listen to Podping updates via standard Websockets"
slug: "podping-via-websockets"
date: 2021-05-26T17:05:00-05:00
updated: 2022-01-18T12:30:00-06:00
draft: false
---

Following on the heels of our free [Podping syndication service over WebSub](/podping-via-websub), we are also making Podpings available to client-side developers for free over standard Websockets.

Simply point your client code to `wss://api.livewire.io/ws/podping`, it's as simple as that - no need for callback servers.

---

Live view of the latest Podpings:

{{< iframe "https://api.livewire.io/ws/podping.html" >}}

---

Example browser-side script:
```javascript
    const ws = new WebSocket("wss://api.livewire.io/ws/podping");
    ws.addEventListener("message", event => {
        const msg = JSON.parse(event.data);
        // see message format below
        if (msg.t === "podping") {
            console.log("podping message", msg);
            for (const op of msg.p) {
                if (op.i === "podping") {
                    // version 0.x payload
                    for (const url of op.p.urls) {
                        // process feed url
                    }
                } else {
                    // version 1.0 payload
                    for (const iri of op.p.iris) {
                        // process iri
                    }
                }
            }
        }
    });
    ws.addEventListener("close", event => {
        // handle close event
    });
    ws.addEventListener("error", event => {
        // handle error event
    });
```

---

Message format:
```typescript
interface PodpingMessage {
     /** Type. */ 
    readonly t: 'podping';

    /** Websocket payload version. */ 
    readonly v: 2;

    /** Hive api server polled by the backend to provide the data. */ 
    readonly a: string;

    /** Hive block number. */ 
    readonly n: number;

    /** Hive operation count.
     * 
     * Total number of operations in the block, not just Podpings. */ 
    readonly o: number;

    /** Podping operations. */
    readonly p: Operation[];
}

interface Operation {
    /** Auth used to write the transaction. */ 
    readonly a: string;
    
    /** ISO 8601 timestamp. */
    readonly t: string;

    /** Hive event id like 'podping' (v0.x) or 'pp_podcast_update' (v1.0) */
    readonly i: string;

    /** Podping. */
    readonly p: Podping;
}

// Raw Podping payload json format
// i.e. "json" from https://github.com/Podcastindex-org/podping.cloud#what-it-does
type Podping = PodpingV0 | PodpingV1;

interface PodpingV0 {
    readonly version: '0.2' | '0.3';
    readonly num_urls: number;
    readonly reason: 'feed_update';
    readonly urls: string[];
}

interface PodpingV1 {
    readonly version: '1.0';
    readonly medium: string; // e.g. podcast, music, video, etc
    readonly reason: string; // e.g. update or live
    readonly iris: string[]; // can contain IRIs that are not http(s) URLs
}

```

---
*Updated 2022-01-18, to support the new [Podping 1.0 payload format](https://write.agates.io/podcasting-2-0-evolution-of-podping#definition)*

---

*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/podping-via-websockets.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
