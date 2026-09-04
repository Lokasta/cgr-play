# Dirt2 technical UV derivative

`colt_python_dirt2.glb` is a deterministic technical derivative of the
CC-BY-4.0 model documented in `LICENSE.txt`.

- Source: `colt_python.glb`
- Source SHA-256: `1cc6810fedfadceb0d6b1a3cea2f6410b8bcddc0ec0792eb1416b1bf4fc75ff0`
- Derived SHA-256: `28b03107757c996bd9da8c4b8c9748d5abddab608a7601911caa3ed3755a704c`
- Generator: `tools/bake-dirt2-storage-uv.mjs`
- Geometry, indices, materials, textures, `TEXCOORD_0`, and `TEXCOORD_1` are
  preserved. The generator only appends one 8,031-item VEC2/FLOAT
  `TEXCOORD_2` attribute (64,248 bytes) and provenance metadata.
- The attribute stores registered UVs for ordinary UV islands and exact
  negative integer rescue codes for the 215 sub-pixel islands listed by the
  active Dirt2 recipe.

Re-running the generator must reproduce the derived digest above. The original
artist, source URL, and license remain embedded in the glTF asset metadata and
are reproduced in `LICENSE.txt`.
