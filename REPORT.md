# Everyday Animals — REPORT

v0.93.0 separates three more continent-page marker pairs that were still under 11px at the settled 300px / FOV 42° / z=2.65 view. Open-water nudges only, each still nearer its own country than any other. Pins already over 11px, including the v0.87–v0.92 pins, stay where they are. The readable country list remains the fallback.

Italy–Slovenia 10.68→11.49; Moldova–Romania 10.69→11.73; Alpine-Central–Germany 10.70→27.08 px.

Only three pairs still under 11px had a legal own-water cell. Luxembourg–Netherlands (10.38), Kosovo–Montenegro (10.48), North Macedonia–Serbia (10.48), and Andorra–San Marino (10.60) have no open-water cell that reaches 11px and stays nearer their own country than a neighbor. British Virgin Islands–Saint Kitts is frozen at both ends. Every tighter pair is on the stuck or already-illegal list, including Saint Lucia–Saint Vincent, Qatar–Bahrain, the other Caribbean overlaps, Lebanon–Syria, Alpine-Central–Liechtenstein, Hungary–Slovakia, Switzerland–Liechtenstein, and Austria–Czechia. This open-water nudge tactic is exhausted. 36 pairs remain under 11px, and none of them has a legal own-water cell.

`npm run typecheck`, `npm run check:reliability`, and `npm run export:web` are green. `.nojekyll`, `404.html`, and `TEST.md` are preserved.
