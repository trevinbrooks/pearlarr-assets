# Pearlarr README media

Binary assets the [Pearlarr](https://github.com/trevinbrooks/pearlarr) README
hot-links via `raw.githubusercontent.com`. They live in their own repository so
cloning Pearlarr never downloads a media byte; GitHub's release-asset CDN is
not an option because it forces `application/octet-stream`, which PyPI's image
proxy refuses to render.

Pushed by Pearlarr's Release workflow on every release - do not edit by hand.
`main` always holds the newest release's media, and the GitHub README points
here; the immutable `vX.Y.Z` tag pins that release's copy, and the version's
PyPI page points there forever. Rulesets block force pushes, tag rewrites, and
deletions, so published URLs never break.
