# Notmyname's Frostpunk 2 Planner

An interactive, browser-based city planner for the **Crater** map in Frostpunk 2.
It's a single self-contained HTML file (`crater_planner.html`) with all tile data
and icons embedded — no server, no build step, nothing to install.

> **Unofficial fan project.** Not affiliated with, endorsed by, or associated with
> 11 bit studios. See the [Disclaimer](#disclaimer).

## Use it online

**[Open the planner →](https://notmyfname.github.io/notmyname-frostpunk2-planner/)**

(`index.html` redirects to the planner.)

## Use it locally

Open `crater_planner.html` in any modern browser.

## Features

- **Districts** — housing, food, extraction, industrial, logistics; 6- or 9-tile,
  contiguous placement, expand/delete, auto-drawn borders.
- **Hubs** — radius-2 influence preview with live stats (net influence, buildable
  tiles, how many 6/9-tile districts fit).
- **Faction hubs** — 3-tile triangle footprints with rotate (R). The Calculating
  Node (Technocrats) counts only city tiles, matching the game.
- **Heat** — optional layer showing each district's adjacency heat.
- **City tiles** — toggle possible-city tiles between locked City and buildable
  Normal (permanent city tiles stay fixed).
- **Save / Load** — export the plan as a PNG image or a `crater_plan.json`, and
  re-open a saved plan.
- **Right-click** the map to cancel the current tool / deselect.

## Disclaimer

Frostpunk 2 and all related names, marks, mechanics, and imagery are the property
of **11 bit studios**. This is a non-commercial, fan-made tool for players. It is
not affiliated with or endorsed by 11 bit studios. Game-derived content is
included only to make the tool usable and will be taken down on request of the
rights holder.
