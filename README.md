# entities-images

Recipes that build the double-precision engine fork, from its branch tip, into binaries and container images for downstream projects.

## What it is for

The recipes cross-compile the engine from Linux to each supported platform, or build natively where that is simpler, and build the editor and runtime images the zone baker and zone server start from. `docs/DEVELOPMENT.md` covers the per-platform recipes and the engine branch.

## Build

```sh
just
just --list
```

The default recipe fetches the tip of the engine branch and builds both images; `just --list` names every other recipe.

## Licence

MIT; see `LICENSE`.
