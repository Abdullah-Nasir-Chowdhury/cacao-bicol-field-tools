# Cacao Bicol Field Tools

Field tools built from interviews with cacao farmers and processors in Bicol, Philippines (Muravah Foundation / Mayon Gold, the farmer Tatay, and a local processing facility). Water pressure — not water scarcity — came up as the concrete, solvable engineering problem, so these tools focus there.

Each file is a single self-contained HTML page — no build step, no dependencies. Download and double-click to open in any browser, or view them live via the links below.

## Tools

### [`index.html`](./index.html)
Landing page linking to all the tools below.

### [`drip-pressure-planner.html`](./drip-pressure-planner.html)
Turns a farm's size and water source into a straight answer: how many trees you can irrigate at once, whether you need a booster pump, how many irrigation zones you need, and how big a dry-season buffer tank to keep on hand. Defaults reflect Tatay's actual farm (2.5 ha, no sprinklers, unmeasured source).

### [`drip-system-schematic.html`](./drip-system-schematic.html)
A P&ID-style diagram (the notation water engineers use for pipe, valve, and instrument drawings) of the same drip system — source, check valve, filter, pressure regulator, zoning, and trees, with a rainwater buffer tank as backup. Toggle between a gravity-fed source and a source below the field to see the one component that changes.

### [`schematic-editor.html`](./schematic-editor.html)
A drag-and-drop canvas for editing either diagram above — reposition nodes, wire new connections, and add components from a palette. Each diagram autosaves separately in the browser; Export/Import moves a layout between browsers.

### [`presentation.html`](./presentation.html)
The full pitch deck as a click-through, phone-friendly website — on-screen Prev/Next buttons (also arrow keys or a swipe on mobile), auto light/dark theme, and the same interactive charts as the dashboard below, embedded live in the relevant slides. Deploys straight to Netlify alongside everything else in this repo (see `netlify.toml`). Drop your own photos into [`images/`](./images/) using the filenames listed in [`images/README.md`](./images/README.md) — each slide picks them up automatically, no code changes needed. `SPEAKER-NOTES.md` has the study material for whoever presents each section.

## Pitch materials

- [`Bicol-Cacao-Pitch.pptx`](./Bicol-Cacao-Pitch.pptx) — the same pitch as a PowerPoint file, for anywhere a live website isn't an option.
- [`SPEAKER-NOTES.md`](./SPEAKER-NOTES.md) — who presents which section, with the facts and figures behind each slide (also embedded directly in the .pptx's Notes field).
- [`scripts/`](./scripts/) — the same speaker notes, split into one printable PDF per presenter (`Nancy.pdf`, `Ria.pdf`, `Masa.pdf`, `Keisuke.pdf`, `Ash.pdf`, `Chow.pdf`; Masa's and Keisuke's include Japanese translations) — study material, not a verbatim script.
- [`FIELD-NOTES.md`](./FIELD-NOTES.md) — the running research log this whole project is built from.

## Slide-ready graphics

The two `.html` tools are interactive pages — a slide deck can't run them directly, so use these static SVGs instead. Any recent PowerPoint, Keynote, or Google Slides can insert an SVG directly (Insert → Picture / Image) and keep it as sharp vector art; if your version can't, open the file in a browser and screenshot it, or ask for a PNG export.

- [`drip-system-schematic-gravity.svg`](./drip-system-schematic-gravity.svg) — the schematic, gravity-fed configuration
- [`drip-system-schematic-pump.svg`](./drip-system-schematic-pump.svg) — the schematic, pump-assisted configuration (Tatay's case)
- [`drip-pressure-planner-summary.svg`](./drip-pressure-planner-summary.svg) — a static results card for Tatay's farm (trees, demand, required pressure, buffer tank), for when you want the numbers on a slide instead of the live calculator

For an actual live demo during the pitch, open the interactive links above in a browser tab rather than trying to embed them in the deck.

## Background

Notes are from field interviews conducted in Bicol (Albay, near Mayon) in August 2026, covering cacao farming challenges: typhoons, pests and disease, water access, aging farmer populations, and post-harvest losses. Water pressure was identified as a controllable, well-defined engineering problem — unlike typhoons (unpredictable) or pest/disease pressure (a biological problem outside this scope).
