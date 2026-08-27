# Cacao Bicol Field Tools

Field tools built from interviews with cacao farmers and processors in Bicol, Philippines (Muravah Foundation / Mayon Gold, the farmer Tatae, and a local processing facility). Water pressure — not water scarcity — came up as the concrete, solvable engineering problem, so these tools focus there.

Each file is a single self-contained HTML page — no build step, no dependencies. Download and double-click to open in any browser, or view them live via the links below.

## Tools

### [`drip-pressure-planner.html`](./drip-pressure-planner.html)
Turns a farm's size and water source into a straight answer: how many trees you can irrigate at once, whether you need a booster pump, how many irrigation zones you need, and how big a dry-season buffer tank to keep on hand. Defaults reflect Tatae's actual farm (2.5 ha, no sprinklers, unmeasured source).

Live: https://preview.ai/code/artifact/128c106e-1640-463a-a5af-393ee2f1cb26

### [`drip-system-schematic.html`](./drip-system-schematic.html)
A P&ID-style diagram (the notation water engineers use for pipe, valve, and instrument drawings) of the same drip system — source, check valve, filter, pressure regulator, zoning, and trees, with a rainwater buffer tank as backup. Toggle between a gravity-fed source and a source below the field to see the one component that changes.

Live: https://preview.ai/code/artifact/7bd1cd7d-457e-4d6b-b387-94e27b1b116b

## Slide-ready graphics

The two `.html` tools are interactive pages — a slide deck can't run them directly, so use these static SVGs instead. Any recent PowerPoint, Keynote, or Google Slides can insert an SVG directly (Insert → Picture / Image) and keep it as sharp vector art; if your version can't, open the file in a browser and screenshot it, or ask for a PNG export.

- [`drip-system-schematic-gravity.svg`](./drip-system-schematic-gravity.svg) — the schematic, gravity-fed configuration
- [`drip-system-schematic-pump.svg`](./drip-system-schematic-pump.svg) — the schematic, pump-assisted configuration (Tatae's case)
- [`drip-pressure-planner-summary.svg`](./drip-pressure-planner-summary.svg) — a static results card for Tatae's farm (trees, demand, required pressure, buffer tank), for when you want the numbers on a slide instead of the live calculator

For an actual live demo during the pitch, open the interactive links above in a browser tab rather than trying to embed them in the deck.

## Background

Notes are from field interviews conducted in Bicol (Albay, near Mayon) in August 2026, covering cacao farming challenges: typhoons, pests and disease, water access, aging farmer populations, and post-harvest losses. Water pressure was identified as a controllable, well-defined engineering problem — unlike typhoons (unpredictable) or pest/disease pressure (a biological problem outside this scope).
