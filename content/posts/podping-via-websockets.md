---
title: "Podping via Websockets"
description: "Listen to Podping updates via standard Websockets"
slug: "podping-via-websockets"
date: 2021-05-26T17:05:00-05:00
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
        console.log("message", msg);
        // handle message
    });
    ws.addEventListener("close", event => {
        // handle close event
    });
    ws.addEventListener("error", event => {
        // handle error event
    });
```

---

*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/podping-via-websockets.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
