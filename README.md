# session.farm — website

Static marketing site for Session Run, hosted on Cloudflare Pages at [session.farm](https://session.farm).

## Pages
- `index.html` — landing page
- `privacy.html` — privacy policy (linked from the Chrome Web Store and Edge Add-ons listings)

## Stack
Plain static HTML/CSS. No build step, no dependencies. Cloudflare Pages serves the files directly — `privacy.html` is available at both `/privacy.html` and the clean URL `/privacy`.

## Deploy
Pushing to `main` triggers an automatic Cloudflare Pages deployment.
