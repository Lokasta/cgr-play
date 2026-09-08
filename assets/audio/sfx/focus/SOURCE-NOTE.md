# focus — recorded takes

Slices in this directory were cut by `tools/build-sfx-assets.mjs` from masters that
live OUTSIDE the repository (the cut-list's `mastersDir`, never committed). Each slice
is a take of the manifest cue in its name (`<cue>-<n>.wav`); the synth descriptor of
that cue keeps sounding when the take is missing. Rebuild a pack with:

    node tools/build-sfx-assets.mjs tools/sfx-cutlists/gdc2020-systematic-cloth.json

## gdc2020-systematic-cloth

- source: Sonniss #GameAudioGDC Bundle 2020 (Part 6) — "Systematic Sound – Sound Themes – Modern Cloth Foley 01" pack sample (the bundle ships 3–4 files per supplier). Downloaded 2026-09-08 from Mirror #1 named on https://sonniss.com/gameaudiogdc/: https://ftpmirror.your.org/pub/misc/sonniss2020/individual/Systematic-Sound%20-%20Sound%20Themes%20-%20Modern%20Cloth%20Foley%2001/ · bundle license PDF + Filelist.xlsx kept beside the masters.
- license: see LICENSE.txt (https://sonniss.com/gdc-bundle-license/)
- masters: `gdc2020-systematic-cloth/` (outside the repo)
- cut-list: `tools/sfx-cutlists/gdc2020-systematic-cloth.json`
- built: 2026-09-08

| cue | file | master | start (ms) | dur (ms) | trim (dB) | tag | note |
|---|---|---|---|---|---|---|---|
| focus.lift | focus.lift-1.wav | SFX CLOTH Foley Jacket Leather Rough Movement Slow Rustle.wav | 6980 | 150 | 0 | — | leather accent (−20…−23 dB RMS cell) in the slow rustle — the mat's leather decompressing as the piece lifts |
| focus.lift | focus.lift-2.wav | SFX CLOTH Foley Jacket Leather Rough Movement Slow Rustle.wav | 11080 | 150 | 0 | — | leather accent (−20…−23 dB RMS cell) in the slow rustle — the mat's leather decompressing as the piece lifts |
| focus.lift | focus.lift-3.wav | SFX CLOTH Foley Jacket Leather Rough Movement Slow Rustle.wav | 12380 | 150 | 0 | — | leather accent (−20…−23 dB RMS cell) in the slow rustle — the mat's leather decompressing as the piece lifts |
| focus.lift | focus.lift-4.wav | SFX CLOTH Foley Jacket Leather Rough Movement Slow Rustle.wav | 7980 | 150 | 0 | — | leather accent (−20…−23 dB RMS cell) in the slow rustle — the mat's leather decompressing as the piece lifts |
| focus.lift | focus.lift-5.wav | SFX CLOTH Foley Jacket Leather Rough Movement Slow Rustle.wav | 680 | 150 | 0 | — | leather accent (−20…−23 dB RMS cell) in the slow rustle — the mat's leather decompressing as the piece lifts |
| focus.lift | focus.lift-6.wav | SFX CLOTH Foley Jacket Leather Rough Movement Slow Rustle.wav | 10280 | 150 | 0 | — | leather accent (−20…−23 dB RMS cell) in the slow rustle — the mat's leather decompressing as the piece lifts |
