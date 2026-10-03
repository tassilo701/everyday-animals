# Everyday Animals — REPORT

v0.90.0 separates eight more continent-page marker pairs that were still under 11px at the settled 300px / FOV 42° / z=2.65 view. Open-water nudges only, each still nearer its own country than any other. Pins already over 11px, including the v0.87, v0.88, and v0.89 pins, stay where they are. The readable country list remains the fallback.

Iberia—Portugal 6.72→11.30; Estonia—Latvia 6.88→12.85; Honduras—Nicaragua 6.88→12.40; Armenia—Azerbaijan 7.04→11.19; Niue—Tonga 7.30→11.10; Latvia—Lithuania 7.52→11.07; Guatemala—El Salvador 7.77→11.16; Dominican Republic—Haiti 7.84→11.14 px.

Saint Lucia—Saint Vincent stays at 2.27px, Saint Lucia—Dominica at 3.78px, Trinidad—Grenada at 3.97px, Grenada—Saint Vincent at 4.19px, and Qatar—Bahrain at 3.59px. At camera z=4.2 those five are 1.27, 2.29, 2.43, 2.34, and 1.94px, so the farther camera does not clear them. Dominica—Saint Kitts stays at 4.61px and Lebanon—Syria at 4.67px: no open-water cell that is still their own reaches 11px. Saint Kitts—U.S. Virgin Islands stays at 5.30px: own-water cells that reach 11px drop another settled pair that was already over 11px. Alpine-Central—Liechtenstein and Hungary—Slovakia have no open water inside their own waters. Barbados, Martinique, Guadeloupe, Antigua, Aruba, and Puerto Rico were not moved.

`npm run typecheck`, `npm run check:reliability`, and `npm run export:web` are green. `.nojekyll`, `404.html`, and `TEST.md` are preserved.
