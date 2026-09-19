# T1D Platform — Prototype

A static, self-contained prototype of the DiaTrapper / ASSET Type 1 Diabetes platform —
showcasing the three connected audiences (**researchers**, **labs & clinics**, and
**individuals & families**) on a shared, privacy-first foundation built around an
MTLR-based risk model trained on the TEDDY cohort.

## Live site

**https://s-b-iqbal.github.io/asset-t1d-platform/**

## About

The entire prototype lives in a single file, [`index.html`](index.html) — no build step
and no server required. It renders standalone in any modern browser and adapts to light
and dark color schemes.

The only external dependency is the Google Fonts stylesheet (IBM Plex Sans / Mono /
Arabic), loaded from CDN.

## Local preview

Open `index.html` directly in a browser, or serve the folder locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/
```

## Hosting

Published with **GitHub Pages** from the `main` branch, root (`/`) path.
