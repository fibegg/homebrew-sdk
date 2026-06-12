# fibegg/homebrew-sdk

Homebrew tap for the Fibe CLI.

## Install

```bash
brew install fibegg/sdk/fibe
```

Or:

```bash
brew tap fibegg/sdk
brew install fibe
```

## Maintenance

This repository does not store the actual binaries.

On each tagged release in `fibegg/sdk`, GoReleaser:

1. uploads the release archives to GitHub Releases in `fibegg/sdk`
2. commits `Formula/fibe.rb` into this tap repository

If this repository only contains the README, no tagged release has published the formula yet.
