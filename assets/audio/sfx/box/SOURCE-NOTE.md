# box — recorded takes

Slices in this directory were cut by `tools/build-sfx-assets.mjs` from masters that
live OUTSIDE the repository (the cut-list's `mastersDir`, never committed). Each slice
is a take of the manifest cue in its name (`<cue>-<n>.wav`); the synth descriptor of
that cue keeps sounding when the take is missing. Rebuild a pack with:

    node tools/build-sfx-assets.mjs tools/sfx-cutlists/gdc2020-hearandnow-tape.json

## gdc2020-hearandnow-tape

- source: Sonniss #GameAudioGDC Bundle 2020 (Part 6) — "Hear and Now Sound – Tape Tape Tape!! The Essential Sound Library for Tape Sounds" pack sample (the bundle ships 3–4 files per supplier). Downloaded 2026-09-08 from Mirror #1 named on https://sonniss.com/gameaudiogdc/: https://ftpmirror.your.org/pub/misc/sonniss2020/individual/Hear%20and%20Now%20Sound%20-%20Tape%20Tape%20Tape%21%21%20The%20Essential%20Sound%20Library%20for%20Tape%20Sounds/ · bundle license PDF + Filelist.xlsx kept beside the masters.
- license: see LICENSE.txt (https://sonniss.com/gdc-bundle-license/)
- masters: `gdc2020-hearandnow-tape/` (outside the repo)
- cut-list: `tools/sfx-cutlists/gdc2020-hearandnow-tape.json`
- built: 2026-09-08

| cue | file | master | start (ms) | dur (ms) | trim (dB) | tag | note |
|---|---|---|---|---|---|---|---|
| box.open.paper | box.open.paper-1.wav | Masking Tape_stereo_crumbling 1.wav | 1500 | 40 | 0 | — | grain from a longer masking-tape crumble stretch (crepe-paper backing — the closest paper crinkle in the three packs); 40 ms vs the 30 ms synth grain |
| box.open.paper | box.open.paper-2.wav | Masking Tape_stereo_crumbling 1.wav | 1560 | 40 | 0 | — | grain from a longer masking-tape crumble stretch (crepe-paper backing — the closest paper crinkle in the three packs); 40 ms vs the 30 ms synth grain |
| box.open.paper | box.open.paper-3.wav | Masking Tape_stereo_crumbling 1.wav | 2500 | 40 | 0 | — | grain from a longer masking-tape crumble stretch (crepe-paper backing — the closest paper crinkle in the three packs); 40 ms vs the 30 ms synth grain |
| box.open.paper | box.open.paper-4.wav | Masking Tape_stereo_crumbling 1.wav | 2700 | 40 | 0 | — | grain from a longer masking-tape crumble stretch (crepe-paper backing — the closest paper crinkle in the three packs); 40 ms vs the 30 ms synth grain |
| box.open.paper | box.open.paper-5.wav | Masking Tape_stereo_crumbling 1.wav | 4050 | 40 | 0 | — | grain from a longer masking-tape crumble stretch (crepe-paper backing — the closest paper crinkle in the three packs); 40 ms vs the 30 ms synth grain |
| box.open.paper | box.open.paper-6.wav | Masking Tape_stereo_crumbling 1.wav | 4200 | 40 | 0 | — | grain from a longer masking-tape crumble stretch (crepe-paper backing — the closest paper crinkle in the three packs); 40 ms vs the 30 ms synth grain |
