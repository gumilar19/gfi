# GridFlow Inversion — Landing Page

Modular static landing page for the GridFlow Inversion web application.

## Structure

- `index.html` — page structure/content
- `css/style.css` — visual styling
- `js/script.js` — interactions and scroll effects
- `assets/images/features/` — dummy feature screenshots
- `assets/images/screenshots/` — dummy application screenshots
- `assets/icons/` — dummy feature icons

## Replacing dummy visuals

The page currently uses local SVG placeholders. Replace these files with your real PNG/WebP screenshots while keeping the same filenames, or update the `src` paths in `index.html`.

Suggested real assets:

- `assets/images/screenshots/app-overview.svg` → screenshot of the main GridFlow interface
- `assets/images/features/ves-inversion.svg` → VES processing/inversion result
- `assets/images/features/ert-inversion.svg` → 2D ERT inversion result
- `assets/images/features/resistivity-3d.svg` → 3D resistivity model

All main CTA buttons point to:
`https://gridflowinversion.streamlit.app/`
