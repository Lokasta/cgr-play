# Wife dialogue

Licensed/provided source masters live outside the repository in the creator's
`Downloads/audios pro cozy game` folder.

Runtime assets are rebuilt with:

```sh
node tools/build-wife-voice-assets.mjs "/absolute/path/to/audios pro cozy game"
```

The bake trims dead air, folds stereo to mono for positional HRTF playback,
applies gentle dialogue EQ/compression and normalizes the three performances to
one common loudness target. Creative room placement, early reflections and
mix ducking remain live in `src/audio/asmr.ts`.
