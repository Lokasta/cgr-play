# gun — recorded takes

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
| gun.land.sigh | gun.land.sigh-1.wav | SFX CLOTH Foley Jacket Leather Rough Movement Slow Rustle.wav | 15000 | 200 | -2 | — | even leather rustle (−29…−33 dB, no accent) — the mat exhaling under the gun; brighter (centroid ≈ 4 kHz) than the LPF-600 synth, hence −2 dB |
| gun.land.sigh | gun.land.sigh-2.wav | SFX CLOTH Foley Jacket Leather Rough Movement Slow Rustle.wav | 19300 | 200 | -2 | — | even leather rustle (−29…−33 dB, no accent) — the mat exhaling under the gun; brighter (centroid ≈ 4 kHz) than the LPF-600 synth, hence −2 dB |
| gun.land.sigh | gun.land.sigh-3.wav | SFX CLOTH Foley Jacket Leather Rough Movement Slow Rustle.wav | 3300 | 200 | -2 | — | even leather rustle (−29…−33 dB, no accent) — the mat exhaling under the gun; brighter (centroid ≈ 4 kHz) than the LPF-600 synth, hence −2 dB |
