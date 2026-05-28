# homebrew-paneflow

Homebrew tap for [Paneflow](https://github.com/ArthurDEV44/paneflow) — a cross-platform terminal multiplexer built in pure Rust with Zed's GPUI framework.

## Install

```sh
brew install --cask arthurdev44/paneflow/paneflow
```

Or tap first, then install by short name:

```sh
brew tap arthurdev44/paneflow
brew install --cask paneflow
```

> macOS Apple Silicon only. The `.dmg` is code-signed and Apple-notarized, so it installs without Gatekeeper prompts. Intel Macs are not currently supported.

## Upgrade

```sh
brew update && brew upgrade --cask paneflow
```

Paneflow also updates itself in-app.

## Maintenance

`Casks/paneflow.rb` is **auto-generated** by the release pipeline in [ArthurDEV44/paneflow](https://github.com/ArthurDEV44/paneflow) (`.github/workflows/update_cask.yml`, rendered from `packaging/homebrew/paneflow.rb`). Do not hand-edit it here — changes are overwritten on the next release.
