# tool — recorded takes

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
| tool.pick.cloth | tool.pick.cloth-1.wav | SFX CLOTH Foley Jacket Synthetic Soft Shell Whoosh Flutter.wav | 3688 | 120 | 0 | — | soft-shell flutter onset — fabric snatched up; centroid 3.3–5.9 kHz; cut near the 100 ms synth length |
| tool.pick.cloth | tool.pick.cloth-2.wav | SFX CLOTH Foley Jacket Synthetic Soft Shell Whoosh Flutter.wav | 5988 | 130 | 0 | — | soft-shell flutter onset — fabric snatched up; centroid 3.3–5.9 kHz; cut near the 100 ms synth length |
| tool.pick.cloth | tool.pick.cloth-3.wav | SFX CLOTH Foley Jacket Synthetic Soft Shell Whoosh Flutter.wav | 8158 | 130 | 0 | — | soft-shell flutter onset — fabric snatched up; centroid 3.3–5.9 kHz; cut near the 100 ms synth length |
| tool.pick.cloth | tool.pick.cloth-4.wav | SFX CLOTH Foley Jacket Synthetic Soft Shell Whoosh Flutter.wav | 8388 | 130 | 0 | — | soft-shell flutter onset — fabric snatched up; centroid 3.3–5.9 kHz; cut near the 100 ms synth length |
| tool.pick.cloth | tool.pick.cloth-5.wav | SFX CLOTH Foley Jacket Synthetic Soft Shell Whoosh Flutter.wav | 10588 | 130 | 0 | — | soft-shell flutter onset — fabric snatched up; centroid 3.3–5.9 kHz; cut near the 100 ms synth length |
| tool.pick.cloth | tool.pick.cloth-6.wav | SFX CLOTH Foley Jacket Synthetic Soft Shell Whoosh Flutter.wav | 12408 | 130 | 0 | — | soft-shell flutter onset — fabric snatched up; centroid 3.3–5.9 kHz; cut near the 100 ms synth length |
| tool.pick.cloth | tool.pick.cloth-7.wav | SFX CLOTH Foley Jacket Synthetic Soft Shell Whoosh Flutter.wav | 14668 | 110 | 0 | — | soft-shell flutter onset — fabric snatched up; centroid 3.3–5.9 kHz; cut near the 100 ms synth length |
| tool.put.cloth | tool.put.cloth-1.wav | SFX CLOTH Foley Jacket Synthetic Soft Shell Whoosh Flutter.wav | 6060 | 140 | 0 | — | decay half of a flutter (starts 60–70 ms into the gesture): fabric coming to rest |
| tool.put.cloth | tool.put.cloth-2.wav | SFX CLOTH Foley Jacket Synthetic Soft Shell Whoosh Flutter.wav | 8450 | 150 | 0 | — | decay half of a flutter (starts 60–70 ms into the gesture): fabric coming to rest |
| tool.put.cloth | tool.put.cloth-3.wav | SFX CLOTH Foley Jacket Synthetic Soft Shell Whoosh Flutter.wav | 12470 | 130 | 0 | — | decay half of a flutter (starts 60–70 ms into the gesture): fabric coming to rest |
| tool.put.cloth | tool.put.cloth-4.wav | SFX CLOTH Foley Jacket Synthetic Soft Shell Whoosh Flutter.wav | 10650 | 120 | 0 | — | decay half of a flutter (starts 60–70 ms into the gesture): fabric coming to rest |
| tool.put.cloth | tool.put.cloth-5.wav | SFX CLOTH Foley Jacket Synthetic Soft Shell Whoosh Flutter.wav | 8220 | 120 | 0 | — | decay half of a flutter (starts 60–70 ms into the gesture): fabric coming to rest |
| tool.put.cloth | tool.put.cloth-6.wav | SFX CLOTH Foley Jacket Synthetic Soft Shell Whoosh Flutter.wav | 12090 | 140 | 0 | — | soft approach rustle before a flutter (peak −25 dB): fabric settling gently |
| tool.put.cloth | tool.put.cloth-7.wav | SFX CLOTH Foley Jacket Synthetic Soft Shell Whoosh Flutter.wav | 9980 | 140 | 0 | — | soft approach rustle (peak −32 dB) — quiet master, ~31 dB of make-up gain; floor stays under −35 dBFS |

## gdc2020-wavjunction-tools

- source: Sonniss #GameAudioGDC Bundle 2020 (Part 6) — "Wav Junction Sound Effects – Tools" pack sample (the bundle ships 3–4 files per supplier). Downloaded 2026-09-08 from Mirror #1 named on https://sonniss.com/gameaudiogdc/: https://ftpmirror.your.org/pub/misc/sonniss2020/individual/Wav%20Junction%20Sound%20Effects%20-%20Tools/ · bundle license PDF + Filelist.xlsx kept beside the masters.
- license: see LICENSE.txt (https://sonniss.com/gdc-bundle-license/)
- masters: `gdc2020-wavjunction-tools/` (outside the repo)
- cut-list: `tools/sfx-cutlists/gdc2020-wavjunction-tools.json`
- built: 2026-09-08

| cue | file | master | start (ms) | dur (ms) | trim (dB) | tag | note |
|---|---|---|---|---|---|---|---|
| tool.put.brush | tool.put.brush-1.wav | 0005_Hammer_on_Wood.wav | 588 | 85 | 0 | — | hammer tap on wood (60–90 ms to −30 dB, centroid 2.4–3 kHz, tilt −3…−14 dB): a handle set down on the bench |
| tool.put.brush | tool.put.brush-2.wav | 0005_Hammer_on_Wood.wav | 1048 | 85 | 0 | — | hammer tap on wood (60–90 ms to −30 dB, centroid 2.4–3 kHz, tilt −3…−14 dB): a handle set down on the bench |
| tool.put.brush | tool.put.brush-3.wav | 0005_Hammer_on_Wood.wav | 1558 | 85 | 0 | — | hammer tap on wood (60–90 ms to −30 dB, centroid 2.4–3 kHz, tilt −3…−14 dB): a handle set down on the bench |
| tool.put.brush | tool.put.brush-4.wav | 0005_Hammer_on_Wood.wav | 2018 | 85 | 0 | — | hammer tap on wood (60–90 ms to −30 dB, centroid 2.4–3 kHz, tilt −3…−14 dB): a handle set down on the bench |
| tool.put.brush | tool.put.brush-5.wav | 0005_Hammer_on_Wood.wav | 2518 | 85 | 0 | — | hammer tap on wood (60–90 ms to −30 dB, centroid 2.4–3 kHz, tilt −3…−14 dB): a handle set down on the bench |
| tool.pick.rod | tool.pick.rod-1.wav | 0021_Tape_Measure_2.wav | 2040 | 80 | 0 | — | tape-measure blade slide (50–120 ms, centroid 7–9 kHz, tilt +13…+22 dB): bright metal sliding — the rod lifted off the tray |
| tool.pick.rod | tool.pick.rod-2.wav | 0021_Tape_Measure_2.wav | 2680 | 80 | 0 | — | tape-measure blade slide (50–120 ms, centroid 7–9 kHz, tilt +13…+22 dB): bright metal sliding — the rod lifted off the tray |
| tool.pick.rod | tool.pick.rod-3.wav | 0021_Tape_Measure_2.wav | 14330 | 80 | 0 | — | tape-measure blade slide (50–120 ms, centroid 7–9 kHz, tilt +13…+22 dB): bright metal sliding — the rod lifted off the tray |
| tool.pick.rod | tool.pick.rod-4.wav | 0021_Tape_Measure_2.wav | 25080 | 90 | 0 | — | tape-measure blade slide (50–120 ms, centroid 7–9 kHz, tilt +13…+22 dB): bright metal sliding — the rod lifted off the tray |
| tool.pick.rod | tool.pick.rod-5.wav | 0021_Tape_Measure_2.wav | 32000 | 90 | 0 | — | tape-measure blade slide (50–120 ms, centroid 7–9 kHz, tilt +13…+22 dB): bright metal sliding — the rod lifted off the tray |
| tool.pick.rod | tool.pick.rod-6.wav | 0021_Tape_Measure_2.wav | 36240 | 80 | 0 | — | tape-measure blade slide (50–120 ms, centroid 7–9 kHz, tilt +13…+22 dB): bright metal sliding — the rod lifted off the tray |
| tool.put.rod | tool.put.rod-1.wav | 0021_Tape_Measure_2.wav | 970 | 100 | 0 | — | tape-measure metal click (20–50 ms transient + 100 ms tail): metal set down — no wood body under it; the synth keeps the 2.4/3.9 kHz modes idea |
| tool.put.rod | tool.put.rod-2.wav | 0021_Tape_Measure_2.wav | 14410 | 100 | 0 | — | tape-measure metal click (20–50 ms transient + 100 ms tail): metal set down — no wood body under it; the synth keeps the 2.4/3.9 kHz modes idea |
| tool.put.rod | tool.put.rod-3.wav | 0021_Tape_Measure_2.wav | 27070 | 100 | 0 | — | tape-measure metal click (20–50 ms transient + 100 ms tail): metal set down — no wood body under it; the synth keeps the 2.4/3.9 kHz modes idea |
| tool.put.rod | tool.put.rod-4.wav | 0021_Tape_Measure_2.wav | 22190 | 100 | 0 | — | tape-measure metal click (20–50 ms transient + 100 ms tail): metal set down — no wood body under it; the synth keeps the 2.4/3.9 kHz modes idea |
| tool.put.rod | tool.put.rod-5.wav | 0021_Tape_Measure_2.wav | 43000 | 100 | 0 | — | tape-measure metal click (20–50 ms transient + 100 ms tail): metal set down — no wood body under it; the synth keeps the 2.4/3.9 kHz modes idea |
