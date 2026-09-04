# RoadSafe KH — Cambodia Road Signs

A clean, responsive bilingual (Khmer/English) reference guide to essential Cambodian road signs.

## Features

- 29 official Cambodian road-sign artworks across warning, prohibition, mandatory and information categories
- Khmer / English language toggle
- Search, category filters and grid/list views
- Light and dark themes
- Sign detail modal with meaning, correct action and fine guidance
- Vehicle-specific fine selector
- Fully responsive static site; no build step or backend required

## Run locally

For a single-file version, download and open `preview.html`. It includes the CSS and JavaScript inside the HTML file.

To regenerate it after editing the source files:

```bash
node build-preview.js
```

Alternatively, keep `index.html`, `styles.css` and `app.js` together, then open `index.html` directly or serve the folder:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Legal source

Fine guidance references Cambodian Sub-Decree No. 39 ANKr.BK dated 17 March 2020, amending Sub-Decree No. 44 on intervention penalties for road traffic law violations. This site is an educational guide, not legal advice. Always check current official sources for a specific case.

Road-sign artwork is sourced from the Wikimedia Commons Cambodia road-sign collection.

## GitHub Pages

In repository settings, open **Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
