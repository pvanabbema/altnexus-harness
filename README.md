# altnexus-harness

Static site for harness.altnexus.com, deployed via Cloudflare Pages from this repository's `main` branch. No build step: framework preset None, blank build command, output directory `/`.

| File | Purpose |
|---|---|
| `index.html` | Landing page: two-outcomes hero, analogy cards, three paths, CTA |
| `AIHARNESS-IMPROV-STAGE-DEMO_v1_20260816.html` | The Improv Stage, a JSON-driven interactive simulation of three failure scenes, harness off and on |
| `manifest.json` | PWA manifest. `start_url` is the simulation |
| `sw.js` | Service worker. Precaches only non-redirecting paths and always goes to the network for navigations |
| `icon-192.png`, `icon-512.png` | PWA icons |
| `og-image.png` | Social preview, 1200x630 |

All financial figures inside the simulation are modelled and labelled as such. The only external statistic in the funnel is a verified Gartner 2025 prediction, cited on the landing page's source article.

Copyright 2026 AltNexus Corp. All rights reserved.
