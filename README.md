# entities-images

Recipes that build the double-precision engine fork into binaries and container images, so downstream projects use a pinned build.

## What it is for

The recipes cross-compile the engine from Linux to each supported platform, or build natively where that is simpler, and build the editor and runtime images the zone baker and zone server start from. `docs/DEVELOPMENT.md` covers the per-platform recipes and the engine pin.

## Build

```sh
just
just --list
```

The default recipe fetches the engine at its pin and builds both images; `just --list` names every other recipe.

## Licence

MIT; see `LICENSE`.
