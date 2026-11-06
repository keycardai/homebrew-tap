# homebrew-tap

The Homebrew tap for the [Keycard CLI](https://keycard.ai).

## Install

```sh
brew install keycardai/tap/keycard
```

Or tap first, then install by name:

```sh
brew tap keycardai/tap
brew install keycard
```

`brew upgrade keycard` moves to the latest release.

## What is here

`Casks/keycard.rb` is the only cask. It installs the `keycard` binary and covers
macOS as a universal build and Linux on arm64 and x86_64.

GoReleaser writes that file during a CLI release and its header says so. Do not
edit it by hand — a version bump arrives here as a release commit, and a manual
change is overwritten by the next one. The CLI itself is developed elsewhere;
this repository only publishes it.

## License

Apache-2.0 — see [LICENSE](./LICENSE) and, for the copyright notice, [NOTICE](./NOTICE).
The Keycard name and logo are trademarks; [TRADEMARKS.md](./TRADEMARKS.md) states how
they may be used.
