# mhs-frontend-dist

Built, minified frontend assets for the Moroccan Heritage Studio Webflow site. Source lives in the private `MHS` repository; this repo only receives `dist/` per release tag and is served through jsDelivr.

- Stylesheet: `https://cdn.jsdelivr.net/gh/redabenryane/mhs-frontend-dist@<tag>/mhs.css`
- Script: `https://cdn.jsdelivr.net/gh/redabenryane/mhs-frontend-dist@<tag>/mhs.js`
- Channel alias (latest 0.1.x): `@0.1`
- Integrity hashes: `manifest.json`
- Fonts are **not** in this repo: `mhs.css` loads them from the site's own Webflow CDN.
- `staging/index.html`: staging build of the new homepage (noindex), served by GitHub Pages for review. It is not the production homepage.
