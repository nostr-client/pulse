# pulse

The live heartbeat of the nostr network — events per second, kinds, hashtags,
relay health — with **no backend, no API keys**: just the shared
[pool](https://github.com/nostr-client/pool)'s websockets running in your tab.

**Live:** https://nostr-client.github.io/pulse/

One buildless HTML file: a firehose subscription over a dozen kinds, a
per-second ring buffer drawn to a canvas sparkline, and top-N bars for kinds
and hashtags. A nice stress test for the pool — and a nice screensaver.

Part of [nostr-client](https://github.com/nostr-client). AGPL-3.0-or-later.
