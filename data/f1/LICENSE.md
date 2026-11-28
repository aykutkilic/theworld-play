# Formula 1 data

- `f1.json` is an extract of the Jolpica-F1 API (https://github.com/jolpica/jolpica-f1, the successor of Ergast),
  licensed **CC BY-NC-SA 4.0** (https://creativecommons.org/licenses/by-nc-sa/4.0/). This extract is shared under the
  same licence, for non-commercial use, with attribution to Jolpica-F1. Built by `tools/build-f1.ts`.
- `layouts.json` holds circuit outlines from bacinger/f1-circuits (https://github.com/bacinger/f1-circuits, MIT),
  re-ordered from the start line in the racing direction, with transforms fitted to OpenF1 car positions
  (https://openf1.org). No OpenF1 position data is stored here; the app fetches it live when a race is watched.

This project is not affiliated with Formula 1, the FIA or Formula One Licensing B.V.; "Formula 1" and "F1" are their
trademarks, used here only to name the championship.

- `historic.json` holds historic Grand Prix courses (old Spa, the Nordschleife, Monza with the banking, Reims-Gueux,
  Pescara) routed over OpenStreetMap data — © OpenStreetMap contributors, available under the Open Database License
  (ODbL 1.0, https://opendatacommons.org/licenses/odbl/). Built by `tools/build-historic-circuits.ts`.
- `highlights.json` lists only YouTube video ids of Formula 1's own channel; the app links to them on YouTube.
