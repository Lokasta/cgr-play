# brush — recorded takes

Slices in this directory were cut by `tools/build-sfx-assets.mjs` from masters that
live OUTSIDE the repository (the cut-list's `mastersDir`, never committed). Each slice
is a take of the manifest cue in its name (`<cue>-<n>.wav`); one-shots retain a quiet synth fallback. The continuous brush beds stay silent
until their recordings decode; they never fall back to synthetic hiss. Rebuild a pack with:

    node tools/build-sfx-assets.mjs tools/sfx-cutlists/brush-foley-cc0.json

## brush-foley-cc0

- source: Toothbrush_Scrubbing_6_Circular_Motion by WavyWave00001, https://freesound.org/people/WavyWave00001/sounds/754335/ . CC0 verified 2026-09-25. Public HQ preview https://cdn.freesound.org/previews/754/754335_16303717-hq.mp3 ; SHA-256 c61534942efb96b1c8911b84aaed57063e3e9b715961c518f6886b129df4c423. Real bristles on a table. Prepared by tools/prepare-brush-foley.py: remove rumble, soften fibre peaks, circular overlap; no synthetic grains or ringing.
- license: see LICENSE.txt (https://creativecommons.org/publicdomain/zero/1.0/)
- masters: `brush-foley-cc0/` (outside the repo)
- cut-list: `tools/sfx-cutlists/brush-foley-cc0.json`
- built: 2026-09-25

| cue | file | master | start (ms) | dur (ms) | trim (dB) | tag | note |
|---|---|---|---|---|---|---|---|
| brush.base | brush.base-1.wav | brush-contact.wav | 0 | 2700 | 0 | — | Recorded continuous bristle friction; driver applies smooth movement and soil/powder response. |
| brush.powder | brush.powder-1.wav | brush-powder.wav | 0 | 2700 | 0 | — | Recorded continuous bristle friction; driver applies smooth movement and soil/powder response. |
| brush.cleaned | brush.cleaned-1.wav | brush-soft-stroke-1.wav | 0 | 220 | 0 | — | Rounded bristle stroke, no tonal click. |
| brush.cleaned | brush.cleaned-2.wav | brush-soft-stroke-2.wav | 0 | 220 | 0 | — | Rounded bristle stroke, no tonal click. |
| brush.cleaned | brush.cleaned-3.wav | brush-soft-stroke-3.wav | 0 | 220 | 0 | — | Rounded bristle stroke, no tonal click. |
| brush.saturated | brush.saturated-1.wav | brush-soft-stroke-1.wav | 0 | 220 | 0 | — | Rounded bristle stroke, no tonal click. |
| brush.saturated | brush.saturated-2.wav | brush-soft-stroke-2.wav | 0 | 220 | 0 | — | Rounded bristle stroke, no tonal click. |
| brush.saturated | brush.saturated-3.wav | brush-soft-stroke-3.wav | 0 | 220 | 0 | — | Rounded bristle stroke, no tonal click. |
