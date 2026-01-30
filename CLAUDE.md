# CLAUDE.md

## Project
Personal portfolio site for Christopher Serrano — AI/ML Researcher.
Live at [TDerror.com](https://tderror.com) via GitHub Pages.

## Stack
Plain HTML + CSS + vanilla JS. No framework, no build step.

## File Structure
- `index.html` — Single-page site with all sections
- `css/style.css` — All styles, CSS variables for theming
- `js/main.js` — Sticky nav, smooth scroll, scroll reveal, mobile menu
- `assets/images/` — Press photos and publication figures
- `.nojekyll` — Disables Jekyll processing on GitHub Pages
- `Resume.md` — Source content reference (gitignored)

## Design
- Dark theme: `#0a0a14` background, `#3b82f6` electric blue accents
- Fonts: Inter (body) + JetBrains Mono (technical accents) via Google Fonts
- Cards use `#12121f` background with subtle border and blue glow on hover
- Publication images with dark backgrounds use `mix-blend-mode: lighten`

## Sections
Hero, Press Gallery, Video, Experience Timeline, Publications, Patents, Education, Footer

## Responsive Breakpoints
- Mobile: <640px (hamburger nav, single column)
- Tablet: 640-1024px (2-col press grid)
- Desktop: >1024px (3-col press grid, full nav)
