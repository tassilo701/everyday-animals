# Everyday Animals — REPORT

v0.95.0 opens the static place files. Expo writes each card as a file such as animals/house-sparrow.html, continents/europe.html, regions/alpine_central.html, and bedtime/house-sparrow.html. Loading that file kept ".html" on the route id, so the page said the friend or place was resting. The id is now read without that suffix. Extensionless URLs are unchanged. Marker coordinates are unchanged. Zoom stays 1.55 / 2.65 / 4.2.

`npm run typecheck`, `npm run check:reliability`, and `npm run export:web` are green. `.nojekyll`, `404.html`, and `TEST.md` are preserved.
