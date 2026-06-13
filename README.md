# Swiss Interior — Event Launch 2026 Forms

Self-contained, single-file HTML sign-up forms used at the 2026 launch event.
Each form runs entirely in the browser (no backend), captures a signed selection,
and lets the designer download a branded PDF copy.

## Contents

| File | Purpose |
|------|---------|
| `index.html` | Landing page linking to both packages |
| `essential-carpentry.html` | Essential Carpentry Package — per-foot-run selection with live pricing |
| `bto-standard.html` | BTO Standard Essential Renovation Package — fixed package for 3 / 4 / 5-Room flats |

## Editing prices

- **BTO packages & combo gift:** edit the clearly-marked `PACKAGES` / `COMBO` block
  at the top of the `<script>` in `bto-standard.html`.
- **Carpentry rates:** edit the `CATALOGUE` object in `essential-carpentry.html`.

## Hosting

These are static files — host anywhere (GitHub Pages, Netlify, tiiny.host, or the
company web server). For GitHub Pages, the root URL serves `index.html` as the menu.

External dependencies loaded from CDN (require internet when the page opens):
Google Fonts and the jsPDF library (for the Download PDF feature).
