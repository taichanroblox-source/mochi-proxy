# 🍡 mochi-proxy

Mochi-themed browser interface with Ultraviolet v3 library assets.

## Current status
- Browser tabs, address bar, DuckDuckGo search URL generation, and local bookmarks: implemented.
- Ultraviolet static assets and a Service Worker scaffold: added.
- **External website proxying: not yet enabled.** No unrestricted Wisp/Bare relay is running.
- Browser-exit cookie deletion and full website compatibility: not implemented.

## Run
```sh
npm install
npm start
```

Health check: `/health`. Render configuration: `render.yaml`.

The UV upstream is no longer maintained: https://github.com/titaniumnetwork-dev/Ultraviolet
