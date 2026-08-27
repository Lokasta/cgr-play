# Jazz radio source note

- Imported: 2026-08-27
- Source: 50 MP3 masters supplied locally by the project owner in
  `Downloads/MusicForGunCozyGame/`.
- Rights statement: the project owner states that licenses for these tracks
  were purchased before import.
- Runtime derivatives: 24 kHz mono MP3, 32 kbps, metadata stripped and built
  directly from the purchased masters with `tools/build-radio-assets.mjs`.
  This bandwidth is intentional: the diegetic radio output is low-passed at
  3.1 kHz, so higher runtime rates cost mobile transfer/decode without surviving
  the in-game mix. The purchased masters remain outside the repository and
  were not modified.
- Commercial-release gate: archive the purchase receipts/license documents in
  the project's private legal records and verify that the licensed product and
  distribution platforms include the public web build. This source note is
  provenance documentation, not a substitute for those licenses.

The numbered runtime filenames map to titles and artists in
`src/audio/radioPlaylist.ts`.
