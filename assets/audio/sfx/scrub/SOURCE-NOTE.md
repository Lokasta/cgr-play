# scrub — recorded takes

Slices in this directory were cut by `tools/build-sfx-assets.mjs` from masters that
live OUTSIDE the repository (the cut-list's `mastersDir`, never committed). Each slice
is a take of the manifest cue in its name (`<cue>-<n>.wav`); one-shots may use a synth fallback.
The cloth loop deliberately stays silent until its recording is available. Rebuild a pack with:

    node tools/build-sfx-assets.mjs tools/sfx-cutlists/cloth-foley-cc0.json

## cloth-foley-cc0

- source: Fabric petting - slow, conk0018, https://freesound.org/people/conk0018/sounds/713009/ ; public HQ preview https://cdn.freesound.org/previews/713/713009_41750-hq.mp3 (SHA-256 53c3e9e35d2fb47cbfb5e4d7cfc41392609234d274b00a34209a07a1fe28cdae). CC0 verified on source page 2026-09-24. Prepared with tools/prepare-cloth-foley.py: remove handling rumble, soften upper frequencies, overlap six contact excerpts with circular fades. Gently compressed and darkened for the user-selected slightly damp, muffled contact. No synthetic noise.
- license: see LICENSE.txt (https://creativecommons.org/publicdomain/zero/1.0/)
- masters: `cloth-foley-cc0/` (outside the repo)
- cut-list: `tools/sfx-cutlists/cloth-foley-cc0.json`
- built: 2026-09-24

| cue | file | master | start (ms) | dur (ms) | trim (dB) | tag | note |
|---|---|---|---|---|---|---|---|
| scrub.base | scrub.base-1.wav | cloth-contact-loop.wav | 0 | 2700 | 0 | — | Real fabric contact, gently rounded and darkened to suggest a slightly damp cloth. Continuous 2.7 s bed with soft movement envelope; no synthetic grains, hiss, squeaks or impacts. |
