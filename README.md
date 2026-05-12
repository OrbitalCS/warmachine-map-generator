# Warmachine Battlefield Generator

A single-file battlefield map generator for **Warmachine Mk IV** tabletop games. Pick a scenario, pick two armies, hit deploy, and get a complete tactical brief: deployment zones, scenario elements at the correct distances, randomly placed terrain that respects Mk IV spacing rules, weather conditions, and a terrain legend listing the in-game effects of every piece on the table.

**Live site:** https://orbitalcs.github.io/warmachine-map-generator/

## Features

- **14 scenarios** from *Tales From The Frontlines* — 6 Casual Play missions and 8 Frontier Campaign missions, with deployment zones and scenario elements placed at the exact distances from the source diagrams.
- **All Mk IV armies** — every Prime army (Storm Legion, Winter Korps, Necrofactorium, Orgoth Sea Raiders, Dusk House Kallyss, Brineblood Marauders, The Old Faith, Khymaera) plus Legacy armies.
- **Battlefield conditions** — optional weather toggle rolls 2d6 on the Casual Play conditions table, including the "War Torn" double-roll case.
- **Smart terrain placement** — 8/10/12 pieces placed with minimum 3" spacing from each other, 3" from table edges, and clear of deployment zones and scenario elements.
- **Per-map terrain legend** — only shows the rules for terrain types actually placed on this map.
- **Re-roll buttons** — swap weather without re-rolling terrain, or vice versa.

## Usage

Open `index.html` in any modern browser. No build step, no install, no backend.

1. Pick a scenario (grouped by Casual Play / Frontier Campaign)
2. Pick army size (30 / 50 / 75 / 100 pts) and the two factions
3. Optionally enable Battlefield Conditions
4. Pick terrain density (8 / 10 / 12 pieces)
5. Hit **Deploy & Generate**

## Tech

Single self-contained HTML file. Vanilla JavaScript, inline SVG for the map, Google Fonts for typography. No frameworks, no dependencies, no tracking.

## Credits

Built as a tactical aid for Warmachine Mk IV. Game content, scenarios, and battlefield conditions are property of Steamforged Games / Privateer Press. This tool is a fan-made utility and is not affiliated with or endorsed by either company.

## License

MIT — do whatever you want with it, just don't blame me if your warjack rolls hot dice.
