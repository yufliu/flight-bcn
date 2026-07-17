# Barcelona Flight Tracker ✈️

Cash-vs-points comparison for two parties flying one-way to **Barcelona (BCN)**, late Aug 2026.

- **Party A:** LAX → BCN, 2 travelers, flexible 8/26 / 8/27 / 8/28
- **Party B:** MCO → BCN, 2 travelers, target 8/27 — aim to land near Party A

## Use it
Open `index.html` in any browser (or the live Pages URL). Click any cell to edit.
The table computes **¢ per point** = `(cash − award taxes) ÷ miles × 100` and flags each
option 🟢 *book points* or 💵 *pay cash* against your threshold (default 1.8¢/pt).

Data **autosaves in your browser** (localStorage). Use **Export JSON** to back it up into
this repo or move it to your phone; **Import** to load it elsewhere.

## Files
| File | What |
|---|---|
| `index.html` | The tracker (self-contained, no dependencies) |
| `DESIGN.md` | Design/spec |
| `NOTES.md` | Optional API auto-feed upgrade path |
| `deploy.sh` | Publish to GitHub Pages |
| `bcn-flight-tracker.json` | (created when you Export) your saved fares |

## Deploy
```bash
bash deploy.sh          # pushes index.html to the public Pages repo
```
Starter rows are illustrative placeholders — replace with live numbers from Google Flights
/ airline sites. See `NOTES.md` for why award pricing stays manual.
