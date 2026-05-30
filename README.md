# SocifyMedia.in — FINAL website (Cloudflare-ready, flat structure)

Static site, plain HTML. NO folders — every page is a flat .html at root,
so GitHub web upload (drag-and-drop) works without folder collisions.
Cloudflare serves clean URLs (mumbai.html -> /digital-marketing-agency-mumbai).

## Pages (37 total)
- Homepage, 404
- 13 India + global location pages
- 10 international tier-1 city pages (New York, LA, Chicago, Houston, London,
  Manchester, Birmingham, Sydney, Melbourne, Brisbane)
- 8 industry pages (real-estate, doctors, education, restaurants, ecommerce,
  lawyers, hotels-travel, startups)
- About, Blog, Blog post, Privacy Policy

## What's done
- All titles + meta descriptions keyword-first and within length limits
- Consistent footer on every page: all Locations (India + Global) + all Industries
- sitemap.xml covers all 36 indexable URLs
- Cloudflare-valid _redirects, security _headers, robots.txt, manifest
- Hero heading clipping fixed

## Upload (GitHub website)
1. Unzip, open the folder.
2. GitHub repo -> Add file -> Upload files.
3. Select ALL files (Ctrl+A) -> drag in -> Commit.
4. Cloudflare auto-deploys. Build: preset None, command empty, output "/".
Add socifymedia.in under the project's Domains tab.
