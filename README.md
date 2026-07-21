# Micrographic — Generator

A standalone, dependency-free HTML tool that generates precise, grid-locked
micro-graphics in the spirit of Kyle Anthony Miller's work — registration
marks, dials, starbursts, barcodes, monospace labels, one accent colour,
everything locked to a grid.

Open [`micrographic.html`](micrographic.html) in any browser. No build step, no
dependencies, works offline.

## Features

- **12 instruments** — target, burst, dial, orbit, arc-grid, eclipse, waveform,
  contour, bars, globe, radar, and field.
- **4 layout archetypes** — centered hero, split panel, offset asymmetric, and
  duo. Composition uses an exclusive slot system, so elements never overlap.
- **Lockable traits** — pin the palette, layout, instrument, or name, then hit
  lucky to reroll only what's unlocked. Click any trait value to cycle it.
- **Custom wordmark** — type your own text into the title block.
- **Deterministic seeds** — every graphic is reproducible from its seed; paste a
  seed to regenerate it exactly.
- **History** — a 10-deep strip restores seed, locks, and wordmark together.
- **Batch mode** — roll 6, 12, or 24 at once (respecting locks) and download the
  whole set as a `.zip` of SVGs.
- **Export** — SVG, or PNG at 560, 1120, or 2240px.

## Usage

- **Feeling lucky** (or press `L`) — roll a new random graphic.
- **Traits** — click a value to cycle it; click **Lock** to pin it across rolls.
- **Wordmark / seed** — set a custom title, or paste a seed and hit **Apply**.
- **Export** — download the current graphic as SVG or PNG.
- **Batch** — roll a set, click any tile to load it, or grab the ZIP.

## License

See [`LICENSE`](LICENSE).
