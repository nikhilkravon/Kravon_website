# Kravon — kravon.in

Static marketing site. Single HTML file, no build tools, no dependencies.

## Structure
```
index.html          ← entire site (HTML + CSS + JS inline)
site.webmanifest    ← PWA metadata
robots.txt
sitemap.xml
assets/img/         ← favicons + OG image (replace placeholders with final brand assets)
```

## Before going live
1. Replace placeholder images in `assets/img/` with final brand assets
2. Uncomment and configure GTM block in `index.html` (search: `GTM-XXXXXXX`)
3. Uncomment and configure Meta Pixel block in `index.html` (search: `PIXEL_ID`)
4. Update `<lastmod>` in `sitemap.xml`

## Deploy
Connected to Vercel via this repo. Push to `main` → auto-deploys.
