# Kojima — Micro-graphic Generator

A standalone, dependency-free HTML tool that generates precise, grid-locked
micro-graphics — registration marks, dials, starbursts, barcodes, monospace
labels, one accent colour, everything locked to a grid.

Open [`index.html`](index.html) in any browser, or visit the live version at
[kojima-san.vercel.app](https://kojima-san.vercel.app). No build step, no
dependencies, works offline.

## The name

A double homage. The visual style is a tribute to the micro-graphic work of
**Kyle Anthony Miller** (the `AFTER K.A.M.` mark in the header). The results
also channel the diegetic, instrument-panel interface language of **Hideo
Kojima's** games — the codec screens, soliton radar, and tactical HUDs of Metal
Gear Solid, and the technical UI craft of Death Stranding — hence the name.

## Features

- **12 instruments** — target, burst, dial, orbit, arc-grid, eclipse, waveform,
  contour, bars, globe, radar, and field.
- **4 layout archetypes** — centered hero, split panel, offset asymmetric, and
  duo. Composition uses an exclusive slot system, so elements never overlap.
- **Lockable traits** — pin the palette, layout, instrument, or name, then hit
  lucky to reroll only what's unlocked. Click any trait value to cycle it, or hit
  its ⟳ button to reroll just that trait.
- **Complexity dial** — one calm↔dense slider scales tick density, decoration,
  and detail across the whole piece.
- **Palette editor** — define your own bg/ink/accent triple and save named
  palettes to your browser; shareable links carry a custom palette with them.
- **Wordmark type** — switch the title font between mono, condensed, and
  grotesk while the micro-labels stay mono for contrast.
- **Riso finish** — an optional print treatment adding subtle ink grain and a
  slightly misregistered accent plate; applies to the preview and all exports.
- **Japanese text** — an optional toggle adds bilingual plate labels (型録,
  検査済) to the generated graphic itself, echoing the footer's own
  すべての版は唯一無二.
- **Custom wordmark** — type your own text into the title block.
- **Deterministic seeds** — every graphic is reproducible from its seed; paste a
  seed to regenerate it exactly.
- **History** — a 10-deep strip restores seed, locks, and wordmark together.
- **Canvas formats** — export as square (1:1), poster (2:3), wide banner (2:1),
  or a tight avatar crop of the instrument. The format applies to the live
  preview and all exports.
- **Batch mode** — roll 6, 12, or 24 at once (respecting locks), download the
  whole set as a `.zip` of SVGs, or render them into a single contact-sheet
  poster PNG.
- **Export** — SVG or PNG (1×/2×/4×), plus a copy-SVG-to-clipboard button.
- **Shareable links** — every piece encodes its seed, locks, and wordmark into
  the URL; **Copy shareable link** gives you a URL that reopens the exact graphic.
- **Collection with editioning** — **Mint** a piece to save it to your browser
  with a permanent, monotonic edition number. The collection persists locally and
  each tile reloads its full state.
- **Rarity** — uncommon and rare trait combinations (the orange field palette, or
  a name aligned to its matching instrument) surface a badge with approximate
  odds. Roughly 16% of rolls are uncommon and ~1% are rare.

## Usage

- **Feeling lucky** (or press `L`) — roll a new random graphic.
- **Traits** — click a value to cycle it; click **Lock** to pin it across rolls.
- **Wordmark / seed** — set a custom title, or paste a seed and hit **Apply**.
- **Mint** (or press `M`) — save the current piece to your local collection with
  an edition number.
- **Copy shareable link** — copy a URL that reopens the exact piece.
- **Export** — download the current graphic as SVG or PNG.
- **Batch** — roll a set, click any tile to load it, or grab the ZIP.

## License

See [`LICENSE`](LICENSE).
