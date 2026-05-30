# SocifyMedia.in — Website (FLAT structure, GitHub-web-upload safe)

Static site, plain HTML. NO folders — every page is a flat .html file at the root.
This is intentional: GitHub's website uploader flattens folders, which caused
collisions before. Flat files upload cleanly via drag-and-drop and Cloudflare
serves them at clean URLs (e.g. digital-marketing-agency-mumbai.html → /digital-marketing-agency-mumbai).

## Upload (GitHub website)
1. Unzip this folder.
2. GitHub → your repo → Add file → Upload files.
3. Select ALL files inside (Ctrl+A) and drag them in. (No folders = nothing to flatten.)
4. Commit. Cloudflare auto-deploys.

## Cloudflare build settings
- Framework preset: None
- Build command: (empty)
- Output directory: /

Custom domain: add socifymedia.in under the project's Domains tab.
