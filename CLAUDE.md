# SlickyAds Portfolio

Performance marketing portfolio site — single-file HTML slide deck (`index.html` + `assets/*.webp`).

## Project context

- User: paid-media / PPC expert running SlickyAds (Google & Meta ads)
- Goal: replace sending `Scaling Business.pdf` with a shareable website link
- Deck: 7 slides exported from Canva, navigation via bottom bar (arrows + dots + counter), keyboard + touch support
- Theme: light/dark aware, responsive down to ~400px

## Key files

- `index.html` — the full slide deck (HTML/CSS/JS inline, no build step)
- `assets/` — slide images `1.webp` through `7.webp`
- `.gitignore` — excludes `.DS_Store`, `Scaling Business.pdf`, `upwork/`

## Notes for future work

- To deploy: GitHub Pages from `main` branch root folder → `https://slickyads.github.io/portfolio/`
- To add slides: add `assets/N.webp` and add a `<section class="slide">` block in `index.html`, then update the `total` count logic if needed (currently hardcoded to 7 in HTML but the JS reads `slides.length`)
- Do not commit the PDF or upwork screenshots
