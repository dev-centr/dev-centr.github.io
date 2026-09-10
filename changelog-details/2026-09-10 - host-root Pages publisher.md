# 2026-09-10 — Host-root Pages publisher

Established `dev-centr/dev-centr.github.io` as the host-root GitHub Pages publisher so crawlers can discover project sitemaps under `dev-centr.github.io` via a single organization `robots.txt`.

Published files:

* `index.html` — brief pointer to [devcentr.org](https://devcentr.org/) and [docs.devcentr.org](https://docs.devcentr.org/)
* `robots.txt` — `Allow: /` plus `Sitemap:` lines for CentrMark, PackageHub, Stack Advisor, Equivalence Engine docs, and Code Lens (site is live; sitemap may appear later)
* `sitemap.xml` — sitemap index listing those same project sitemap URLs
