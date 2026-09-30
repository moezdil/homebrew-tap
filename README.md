# homebrew-tap

Homebrew formulae for [siltide](https://github.com/moezdil/siltide), the terminal monitor for GPUs, NPUs, and other AI accelerators.

```sh
brew install moezdil/tap/siltide
```

`Formula/siltide.rb` is rendered by `scripts/update.sh` from the newest siltide release and refreshed by a workflow on every siltide release, with a run every 6 hours as a fallback. It points at a stable release when one exists and at the newest `main` pre-release until then.
