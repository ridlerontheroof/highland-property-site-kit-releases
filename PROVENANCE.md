# Provenance

Each tag in this repository publishes an already released kit tree without changing any byte. The values below
come from the Git objects of the source repository where each release was made.

## kit-v2.0.0-r1

| Item | Value |
|---|---|
| Source tag object | `c9c3a8ded77e93f01ce8c68aa747ea2b9c998bd2` |
| Source peeled commit | `7706c203a0e5365f0d85373e135e27119ced6730` |
| Source tag date | 2026-08-31T21:07:48Z |
| Kit tree hash (`woods-crossing-code-kit/`) | `8e4764d9d9b74a976de648e16e2b1591664198c3` |
| Implementation digest | `27624aee0b6a824b54650c49f0009c984f7e1631213a493eca50c4491e0ed458` (166 release files) |

The `woods-crossing-code-kit/` directory at this tag has the same Git tree hash as the source release, so every
file is byte-identical to it.

Wording in this release's metadata: `release.json` records `tag` `kit-v2.0.0` with publication status
`withdrawn`, and names `kit-v2.0.0-r1` as the replacement with status "pending". `kit-v2.0.0` was withdrawn and
`kit-v2.0.0-r1` is that replacement; the metadata was not edited after release. Its publication record names
the private repository the release was made from.

## kit-v2.0.1

| Item | Value |
|---|---|
| Source tag object | `4d8801ad5647a1ff80fb4ac68a08fc655a53cc64` |
| Source peeled commit | `51e37de78683793c1e8b15fd9c020d6b61252f20` |
| Source tag date | 2026-09-01T19:48:26Z |
| Kit tree hash (`woods-crossing-code-kit/`) | `6fc7db21cb2642b35027a84a3cac8cc57560b265` |
| Implementation digest | `92594acf9bdff4e1f73c4dabecd7ad425406ea9a29295640306e6a06cfedaecc` (168 release files) |

The `woods-crossing-code-kit/` directory at this tag has the same Git tree hash as the source release, so every
file is byte-identical to it.

Included standards file: `.agents/skills/property-site-onboarding/standards/changes/STD-2026-2.json` (blob
`7dcc7bfc3277c62c80b63686e98739c12fdce0fe`, identical to the source release's copy), at the same relative path
as in the source. It is included because this release's `release.json` points to it
(`standardsCompatibility.changeManifest`). No other file outside the kit directory is referenced.

Wording in this release's metadata: `release.json` still says `"released": null` and publication status
`candidate`, and the standards file says `"releaseDigest": "PENDING UNTIL RELEASE"`, although the release was
tagged on 2026-09-01. The files were not edited after release.

## Known content

The comments of one guard file (`woods-crossing-code-kit/guards/check-gtm-tracking.mjs`) name analytics
identifiers of the property the kit was first built for. No code reads them. They are kept because these trees
are published byte-identical, and a later release removes them.
