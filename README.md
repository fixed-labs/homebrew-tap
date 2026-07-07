# fixed-labs Homebrew tap

Homebrew formulae for [Fixed Point Labs](https://fixedlabs.dev) command-line tools.

## Install

```sh
brew install fixed-labs/tap/rift
```

Or tap first, then install with a bare name:

```sh
brew tap fixed-labs/tap
brew install rift
```

(`fixed-labs/tap` resolves to this repo — Homebrew strips the `homebrew-` prefix.)

## Upgrade

```sh
brew upgrade rift
```

## Formulae

| Formula | Description |
|---|---|
| `rift` | The `rift` CLI — spawn a remote devbox and open a shell inside it. |

Formulae here are published automatically by the GoReleaser release pipeline in
[`fixed-labs/oss`](https://github.com/fixed-labs/oss). **Do not edit them by hand** —
changes are overwritten on the next release.
