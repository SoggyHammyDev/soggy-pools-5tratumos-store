# Soggy Pools AIO — 5tratumOS Store

Public app-store metadata for installing the 5tratumOS variant of Soggy Pools AIO.

Add this custom store URL in 5tratumOS:

`https://github.com/SoggyHammyDev/soggy-pools-5tratumos-store`

## Image

`ghcr.io/soggyhammydev/soggy-pools-5tratumos:5tratumos-dev`

This repository contains **only store metadata and a Docker Compose recipe**; it does not build the app or publish images. The 5tratumOS image is a separate GHCR package from the Umbrel image.

### Notes
- This is a testing build, not an official 5tratumOS core app.
- App ID: `soggy-pools-aio`. If an older Soggy Pools store is already registered, avoid installing both under the same ID.
- The image currently uses a moving development tag. Validate updates before upgrading a running mining node.
- The app's node databases persist under `${APP_DATA_DIR}/data`. Back up data before switching packages.
