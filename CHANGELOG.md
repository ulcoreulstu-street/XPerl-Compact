# Changelog — XPerl Compact

## 1.0.0 — first standalone release

- Established XPerl Compact as a separate addon distribution based on the Sirus-adapted X-Perl UnitFrames codebase.
- Renamed addon folders and TOC manifests to the `XPerlCompact*` namespace to avoid addon-ID collisions with the original XPerl package.
- Updated module dependencies, addon-loader references and resource paths to the renamed folders.
- Set the compact edition maintainer to **Ulcore@** in addon metadata and the in-game description.
- Added per-module `X-Sirus-Update` metadata pointing to this GitHub repository.
- Removed obsolete CurseForge project metadata.
- Retained GNU GPL v3, original copyright notices and attribution to the upstream authors and Sirus adaptation lineage.
- Preserved existing saved-variable names and internal XPerl Lua APIs for continuity with prior settings.
