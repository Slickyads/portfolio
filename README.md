# SlickyAds — Performance Marketing Portfolio

A shareable, link-based alternative to the "Scaling Business.pdf" deck. Built as a single HTML file so it can be hosted on GitHub Pages (or any static host) and viewed on any device.

## Structure

- `index.html` — self-contained slide deck (HTML, CSS, JS all in one file)
- `assets/` — 7 slide images exported from Canva (`1.webp` … `7.webp`)

## Navigation

- Left / Right arrows, `←` `→` keys, or swipe to move between slides
- Page dots at the bottom show current slide
- Counter shows `1 / 7`
- Works on desktop and mobile, with light/dark theme support

## Deploying

This is a static site — no build step required.

**GitHub Pages:**
1. Push `main` (done)
2. In GitHub: Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main`, Folder: `/(root)` → Save
3. Live at `https://adscampaign.slickyads.com/`

**Other hosts:** Drag the whole folder (`index.html` + `assets/`) onto Netlify Drop, Vercel, Surge, etc.

## Files intentionally excluded

- `Scaling Business.pdf` — the old PDF you're replacing with this site
- `upwork/` — local screenshots, not part of the public portfolio
