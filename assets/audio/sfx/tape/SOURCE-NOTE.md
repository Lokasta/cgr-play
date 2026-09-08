# tape — recorded takes

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
| tape.rip | tape.rip-1.wav | Duct Tape_mono_short rip 1.wav | 175 | 140 | 0 | — | the sample's one clean short duct-tape rip: 100 ms to −30 dB, peak −0.7 dBFS, centroid 11.5 kHz |
| tape.rip | tape.rip-2.wav | Duct Tape_stereo_pulling 5.wav | 0 | 190 | 0 | — | file opens on a pull-rip already sounding (−15 dB RMS for 200 ms, then silence) — abrupt start is the rip |
| tape.rip | tape.rip-3.wav | Duct Tape_stereo_pulling 5.wav | 405 | 200 | 0 | — | duct tape pulled off the roll, 200 ms to −30 dB, centroid 6.6 kHz |
| tape.rip | tape.rip-4.wav | Duct Tape_stereo_pulling 5.wav | 1015 | 260 | 0 | — | longer pull (340 ms event) cut at 260 ms, darker (centroid 5.1 kHz) |
| tape.rip | tape.rip-5.wav | Shipping Tape_stereo_pulling 2.wav | 2040 | 200 | 0 | — | stick-slip accent inside the continuous shipping-tape pull (starts mid-sound); hissier, centroid 9 kHz |
| tape.rip | tape.rip-6.wav | Shipping Tape_stereo_pulling 2.wav | 2370 | 200 | 0 | — | second stick-slip accent of the shipping-tape pull, 210 ms to −30 dB |
| tape.crackle | tape.crackle-1.wav | Masking Tape_stereo_crumbling 1.wav | 808 | 40 | 0 | — | single masking-tape crackle (onset ≥ 12 dB over the preceding 100 ms, 10–60 ms to −30 dB, centroid 5–8 kHz); 40 ms ≈ the 45 ms synth grain |
| tape.crackle | tape.crackle-2.wav | Masking Tape_stereo_crumbling 1.wav | 1138 | 40 | 0 | — | single masking-tape crackle (onset ≥ 12 dB over the preceding 100 ms, 10–60 ms to −30 dB, centroid 5–8 kHz); 40 ms ≈ the 45 ms synth grain |
| tape.crackle | tape.crackle-3.wav | Masking Tape_stereo_crumbling 1.wav | 1838 | 40 | 0 | — | single masking-tape crackle (onset ≥ 12 dB over the preceding 100 ms, 10–60 ms to −30 dB, centroid 5–8 kHz); 40 ms ≈ the 45 ms synth grain |
| tape.crackle | tape.crackle-4.wav | Masking Tape_stereo_crumbling 1.wav | 2048 | 40 | 0 | — | single masking-tape crackle (onset ≥ 12 dB over the preceding 100 ms, 10–60 ms to −30 dB, centroid 5–8 kHz); 40 ms ≈ the 45 ms synth grain |
| tape.crackle | tape.crackle-5.wav | Masking Tape_stereo_crumbling 1.wav | 3068 | 40 | 0 | — | single masking-tape crackle (onset ≥ 12 dB over the preceding 100 ms, 10–60 ms to −30 dB, centroid 5–8 kHz); 40 ms ≈ the 45 ms synth grain |
| tape.crackle | tape.crackle-6.wav | Masking Tape_stereo_crumbling 1.wav | 3228 | 40 | 0 | — | single masking-tape crackle (onset ≥ 12 dB over the preceding 100 ms, 10–60 ms to −30 dB, centroid 5–8 kHz); 40 ms ≈ the 45 ms synth grain |
| tape.crackle | tape.crackle-7.wav | Masking Tape_stereo_crumbling 1.wav | 4508 | 40 | 0 | — | single masking-tape crackle (onset ≥ 12 dB over the preceding 100 ms, 10–60 ms to −30 dB, centroid 5–8 kHz); 40 ms ≈ the 45 ms synth grain |
| tape.crackle | tape.crackle-8.wav | Masking Tape_stereo_crumbling 1.wav | 4668 | 40 | 0 | — | single masking-tape crackle (onset ≥ 12 dB over the preceding 100 ms, 10–60 ms to −30 dB, centroid 5–8 kHz); 40 ms ≈ the 45 ms synth grain |
| tape.strain | tape.strain-1.wav | Shipping Tape_stereo_pulling 2.wav | 500 | 2400 | 0 | — | continuous shipping-tape pull, −17…−26 dB RMS from 0.5 to 2.9 s — the only ≥ 2 s steady stretch in the sample. NOTE: SampleBank at 00f46f0 skips takes of loop cues; this take is inert until loop takes are decoded |
