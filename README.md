# homebrew-quintile

Homebrew tap for [Quintile](https://github.com/stefanopineda/quintile) — keyboard-only N×M grid window tiling for macOS.

## Install

```sh
brew install --cask stefanopineda/quintile/quintile
```

Then grant Accessibility permission when prompted:
**System Settings → Privacy & Security → Accessibility → enable Quintile**.

> **Note:** the cask installs a Developer ID-signed, notarized `Quintile.app`
> from the main repo's GitHub Releases. Until the first tagged release is
> published there, `brew install` will not find an artifact — build from
> source in the meantime (`git clone` + `make run`).
