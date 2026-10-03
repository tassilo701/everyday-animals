# Everyday Animals — REPORT

v0.88.0 separates eight more continent-page marker pairs that were still under ~11px at the settled 300px / FOV 42° / z=2.65 view. Open-water nudges only. Pins already moved in v0.87 were left where they are. The readable country list remains the fallback.

Barbados—Saint Lucia 3.05→12.11; Martinique—Grenada 4.14→11.39; Lebanon—Palestine 4.54→11.49; Balkans—Serbia 5.08→26.04; Albania—North Macedonia 5.72→13.22; Belgium—Luxembourg 5.82→11.67; Benin—Togo 6.38→18.33; Guinea—Sierra Leone 7.20→17.60 px.

Qatar—Bahrain stays at 3.59px: no open-water cell clears 11px without landing on another pin. Benelux—Netherlands stays at 8.22px and Switzerland—Liechtenstein at 10.09px; the eight-move cap went to tighter pairs. South America still has no pair under 11px.

`npm run typecheck`, `npm run check:reliability`, and `npm run export:web` are green. `.nojekyll`, `404.html`, and `TEST.md` are preserved.
