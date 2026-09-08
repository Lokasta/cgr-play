# part — recorded takes

Slices in this directory were cut by `tools/build-sfx-assets.mjs` from masters that
live OUTSIDE the repository (the cut-list's `mastersDir`, never committed). Each slice
is a take of the manifest cue in its name (`<cue>-<n>.wav`); the synth descriptor of
that cue keeps sounding when the take is missing. Rebuild a pack with:

    node tools/build-sfx-assets.mjs tools/sfx-cutlists/gdc2020-systematic-cloth.json
    node tools/build-sfx-assets.mjs tools/sfx-cutlists/gdc2020-wavjunction-tools.json

## gdc2020-systematic-cloth

- source: Sonniss #GameAudioGDC Bundle 2020 (Part 6) — "Systematic Sound – Sound Themes – Modern Cloth Foley 01" pack sample (the bundle ships 3–4 files per supplier). Downloaded 2026-09-08 from Mirror #1 named on https://sonniss.com/gameaudiogdc/: https://ftpmirror.your.org/pub/misc/sonniss2020/individual/Systematic-Sound%20-%20Sound%20Themes%20-%20Modern%20Cloth%20Foley%2001/ · bundle license PDF + Filelist.xlsx kept beside the masters.
- license: see LICENSE.txt (https://sonniss.com/gdc-bundle-license/)
- masters: `gdc2020-systematic-cloth/` (outside the repo)
- cut-list: `tools/sfx-cutlists/gdc2020-systematic-cloth.json`
- built: 2026-09-08

| cue | file | master | start (ms) | dur (ms) | trim (dB) | tag | note |
|---|---|---|---|---|---|---|---|
| part.grab | part.grab-1.wav | SFX CLOTH Foley Jacket Leather Rough Movement Slow Rustle.wav | 4580 | 130 | 0 | — | leather accent (−24…−25 dB RMS cell) — skin-and-leather 'thup' of a part picked off the mat |
| part.grab | part.grab-2.wav | SFX CLOTH Foley Jacket Leather Rough Movement Slow Rustle.wav | 8280 | 130 | 0 | — | leather accent (−24…−25 dB RMS cell) — skin-and-leather 'thup' of a part picked off the mat |
| part.grab | part.grab-3.wav | SFX CLOTH Foley Jacket Leather Rough Movement Slow Rustle.wav | 10780 | 130 | 0 | — | leather accent (−24…−25 dB RMS cell) — skin-and-leather 'thup' of a part picked off the mat |
| part.grab | part.grab-4.wav | SFX CLOTH Foley Jacket Leather Rough Movement Slow Rustle.wav | 18880 | 130 | 0 | — | leather accent (−24…−25 dB RMS cell) — skin-and-leather 'thup' of a part picked off the mat |
| part.grab | part.grab-5.wav | SFX CLOTH Foley Jacket Leather Rough Movement Slow Rustle.wav | 14680 | 130 | 0 | — | leather accent (−24…−25 dB RMS cell) — skin-and-leather 'thup' of a part picked off the mat |

## gdc2020-wavjunction-tools

- source: Sonniss #GameAudioGDC Bundle 2020 (Part 6) — "Wav Junction Sound Effects – Tools" pack sample (the bundle ships 3–4 files per supplier). Downloaded 2026-09-08 from Mirror #1 named on https://sonniss.com/gameaudiogdc/: https://ftpmirror.your.org/pub/misc/sonniss2020/individual/Wav%20Junction%20Sound%20Effects%20-%20Tools/ · bundle license PDF + Filelist.xlsx kept beside the masters.
- license: see LICENSE.txt (https://sonniss.com/gdc-bundle-license/)
- masters: `gdc2020-wavjunction-tools/` (outside the repo)
- cut-list: `tools/sfx-cutlists/gdc2020-wavjunction-tools.json`
- built: 2026-09-08

| cue | file | master | start (ms) | dur (ms) | trim (dB) | tag | note |
|---|---|---|---|---|---|---|---|
| part.land.desk | part.land.desk-1.wav | 0005_Hammer_on_Wood.wav | 588 | 110 | 0 | — | the same steel-on-wood tap with 110 ms of tail — a steel part meeting bare desk; heavier than a small part, level left to the cue |
| part.land.desk | part.land.desk-2.wav | 0005_Hammer_on_Wood.wav | 1048 | 110 | 0 | — | the same steel-on-wood tap with 110 ms of tail — a steel part meeting bare desk; heavier than a small part, level left to the cue |
| part.land.desk | part.land.desk-3.wav | 0005_Hammer_on_Wood.wav | 1558 | 110 | 0 | — | the same steel-on-wood tap with 110 ms of tail — a steel part meeting bare desk; heavier than a small part, level left to the cue |
| part.land.desk | part.land.desk-4.wav | 0005_Hammer_on_Wood.wav | 2018 | 110 | 0 | — | the same steel-on-wood tap with 110 ms of tail — a steel part meeting bare desk; heavier than a small part, level left to the cue |
| part.land.desk | part.land.desk-5.wav | 0005_Hammer_on_Wood.wav | 2518 | 110 | 0 | — | the same steel-on-wood tap with 110 ms of tail — a steel part meeting bare desk; heavier than a small part, level left to the cue |
