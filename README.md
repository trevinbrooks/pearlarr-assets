# Pearlarr README media

Binary assets the [Pearlarr](https://github.com/trevinbrooks/pearlarr) README
hot-links via `raw.githubusercontent.com`. They live in their own repository so
cloning Pearlarr never downloads a media byte; GitHub's release-asset CDN is
not an option because it forces `application/octet-stream`, which PyPI's image
proxy refuses to render.

Pushed by Pearlarr's Release workflow on every release - do not edit by hand:

- `latest/` - the newest release's media; the GitHub README points here.
- `vX.Y.Z/` - that release's media, frozen; the version's PyPI page pins here.

History is append-only: released `vX.Y.Z/` paths are never modified or deleted
(published PyPI pages reference them forever), and a ruleset blocks force
pushes and branch deletion.
