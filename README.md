# SocifyMedia.in — Website (Cloudflare-ready)

Static site. Plain HTML/CSS, no build step.

## What's inside
- `index.html` — homepage (original, unchanged)
- `404.html` — custom error page (original, unchanged)
- 13 location landing pages (folder/index.html for clean URLs)
- `about/`, `blog/`, `blog/digital-marketing-agency-checklist-2026/`, `privacy-policy/`
- `_redirects` — Cloudflare-valid (relative URLs, codes 301; no `!`, no 404 line)
- `_headers` — security + caching headers
- `sitemap.xml`, `robots.txt`, `manifest.webmanifest`, `humans.txt`
- all icons/logos
- `.gitignore` — keeps `.git`/build temp out of the published assets

## Deploy on Cloudflare (Pages → Connect to Git)
- Framework preset: **None**
- Build command: **(leave empty)**
- Build output directory: **/**

That's it. Custom domain: add `socifymedia.in` under the project's Domains tab.
