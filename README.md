# Empire Fleet Planner

Static GitHub Pages planner for one Empire fleet.

## Files

- `index.html` — page structure
- `style.css` — medieval parchment styling
- `script.js` — planner logic
- `ports.json` — trade port rewards
- `options.json` — non-trade fleet option rewards

## New in this version

- Added a **Fleet Activity** dropdown.
- Choose **Trade voyage** to use the existing port picker.
- Choose another activity such as **Guarding**, **Questing**, **Raiding**, or **Scouting** to show the matching fleet options from `options.json`.
- The **Fleet Option** dropdown replaces the port dropdown when a non-trade activity is selected.
- Voyage production updates using the same Weirwood, Enchant Fleet, ritual, and debuff controls.
- Options can use ranks up to 20, while trade ports still use the port table maximum.

## Updated rituals

Rituals now load from `rituals.json`, generated from `Fleet rituals.xlsx`. The Enchant Fleet / Ritual dropdown is filtered by Fleet Activity: Trading shows Trading and All rituals; Raiding shows Raiding and All rituals; Guarding, Questing, and Scouting work the same way.

Upload `rituals.json` with the rest of the site files.
