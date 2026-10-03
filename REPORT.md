# Everyday Animals — REPORT

v0.89.0 separates eight more continent-page marker pairs that were still under 11px at the settled 300px / FOV 42° / z=2.65 view. Open-water nudges only. Pins already over 11px, including the v0.87 and v0.88 pins, stay where they are. The readable country list remains the fallback.

Antigua—Saint Kitts 2.42→17.41; Antigua—Dominica 4.23→20.48; Antigua—U.S. Virgin Islands 7.72→20.55; Antigua—Saint Lucia 8.01→24.21; Antigua—Saint Vincent 10.07→26.38; Aruba—Curaçao 2.85→11.70; Puerto Rico—U.S. Virgin Islands 4.64→11.40; Puerto Rico—Saint Kitts 9.92→15.28 px.

Saint Lucia—Saint Vincent stays at 2.27px, Saint Lucia—Dominica at 3.78px, Trinidad—Grenada at 3.97px, and Grenada—Saint Vincent at 4.19px: moving them drops a pair that is already over 11px, and a small extra nudge of Barbados, Martinique, or Guadeloupe does not open a legal cell. Qatar—Bahrain stays at 3.59px: no open-water cell reaches 11px without a new under-11px pair or another country's coast. Dominica—Saint Kitts stays under 11px because separating it would push past the eight-pair cap.

`npm run typecheck`, `npm run check:reliability`, and `npm run export:web` are green. `.nojekyll`, `404.html`, and `TEST.md` are preserved.
