# Everyday Animals — REPORT

v0.97.0 recovers from an invalid bedtime route. Opening `/bedtime/` with a missing id used to turn bedtime mode on and show only "That friend is resting tonight" with no ParentBack and no escape tap — unlike animals, regions, and continents after v0.79. Bedtime mode now arms only for a real animal, and the missing screen offers Back to globe plus Try Europe tonight. Marker coordinates are unchanged. Zoom stays 1.55 / 2.65 / 4.2. Continent globe start, `.html` route ids, and bedtime story scroll are unchanged.

`npm run typecheck`, `npm run check:reliability`, and `npm run export:web` are green. `.nojekyll`, `404.html`, and `TEST.md` are preserved.
