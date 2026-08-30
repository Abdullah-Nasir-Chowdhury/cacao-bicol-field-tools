# Images for the presentation

Drop your photos into this folder using **exactly these filenames** — `presentation.html`
references them directly, so no code changes are needed once they're here. Until a file exists,
that slide shows a clearly-labeled placeholder box instead (nothing breaks).

Any reasonable size works (the page crops to fit with `object-fit: cover`); landscape photos
around 1200–1600px wide look best. JPG or PNG both work — just keep the filenames below exactly
(same extension, `.jpg`).

| Filename | Type | Slide | What it's for |
|---|---|---|---|
| `mayon-gold-1.jpg` | photo | We visited Mayon Gold / Muravah Foundation | Site visit photo 1 |
| `mayon-gold-2.jpg` | photo | We visited Mayon Gold / Muravah Foundation | Site visit photo 2 |
| `batbat-1.mp4` | **video** | August 26 — Tatay's Farm, Batbat | "Leaves dry" — leaves drying/rotting due to lack of water (the clip whose original filename ends in `105010.mp4`). Plays automatically, muted, on loop. |
| `batbat-2.mp4` | **video** | August 26 — Tatay's Farm, Batbat | "Cacao pod rotting". Plays automatically, muted, on loop. |
| `aug27-1.jpg` | photo | August 27 — Rice, Dairy, Bamboo & Honey Farms | Rice/dairy farm & farm school |
| `aug27-2.jpg` | photo | August 27 — Rice, Dairy, Bamboo & Honey Farms | Bamboo farm / honey producers |
| `aug28-1.jpg` | photo | August 28 — Solar, Wind & Agritourism | Zambales solar farm / agrivoltaics |
| `aug28-2.jpg` | photo | August 28 — Solar, Wind & Agritourism | Youth agritourism program |
| `vertical-panel.jpg` | photo | Vertical panels waste potential output | Vertical vs. tilted panel comparison (not in the field notes — this is the team's own photo) |
| `pest-infestation.jpg` | photo | What we found at Tatay's farm | Pest infestation ✅ already added |
| `dry-leaves.jpg` | photo | What we found at Tatay's farm | Dry, dying leaves |
| `diseased-pod.jpg` | photo | What we found at Tatay's farm | Diseased cacao pod |

That's 10 photos and 2 videos.

**How to add the videos** (chat only accepts images, so they go straight into the repo):
on github.com, open this `images/` folder → **Add file → Upload files** → drop in the two `.mp4`
files (renamed to `batbat-1.mp4` and `batbat-2.mp4`) → commit. If you deploy by dragging a folder
into Netlify instead, just make sure the files are in `images/` in that folder. Browsers require
autoplaying video to be muted — the page already sets that, so no sound plays.

The page also carries the two Google Drive share links as backup video sources — if the Drive
files are set to "anyone with the link can view," the videos may stream from Drive even before the
`.mp4` files land in this folder. Treat that as best-effort only: Drive throttles and blocks
direct playback unpredictably (especially for the larger clip), so uploading the files here is
still the reliable path.

If you use different filenames or extensions, either rename your files to match this table, or
open `presentation.html`, search for the old filename in each `<img src="...">` / `<source src="...">`
tag, and update it.
