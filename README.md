# Highland property site kit releases

This repository holds released versions of `@highland/property-site-kit` under `woods-crossing-code-kit/`.

- Tags never change. A released tag is never moved, overwritten or deleted.
- Each tagged `woods-crossing-code-kit/` directory is byte-identical to its released tree. Details for every tag
  are in `PROVENANCE.md`.
- Projects pin an exact tag and verify it with the kit's release validation (`pnpm validate:release` inside
  `woods-crossing-code-kit/`), which recomputes the implementation digest recorded in `release.json`.
- Upgrades are explicit and never automatic.
