# sandeepbaynes/homebrew-tap

A [Homebrew](https://brew.sh) tap with formulae for tools by **Sandeep Baynes**.

## Install

```sh
# Install a tool directly — this auto-taps:
brew install sandeepbaynes/tap/byn

# …or tap once, then install by short name:
brew tap sandeepbaynes/tap
brew install byn
```

Upgrade and remove like any formula:

```sh
brew upgrade byn
brew uninstall byn
```

(Homebrew installs into a directory that's already on your `PATH`, so there's
nothing extra to configure.)

## Formulae

| Formula | Description | Source |
|---|---|---|
| `byn` | Local-first secure secrets vault & credential manager (CLI). | <https://github.com/sandeepbaynes/byn> |

*(More tools land here over time — this tap is shared across all of them.)*

## How this tap is maintained

The files in `Formula/` are **generated automatically** by
[GoReleaser](https://goreleaser.com) when a source project cuts a release —
**please don't hand-edit them**, as they're overwritten on the next release.
Each project publishes its own `Formula/<tool>.rb` here, so a single tap serves
every tool.

## Issues & contributing

Report bugs or request features **on the tool's own repository** (e.g.
[byn](https://github.com/sandeepbaynes/byn/issues)), not here — this repo only
holds install recipes.

## License

Each formula installs software under **that project's own license** (for
example, `byn` is PolyForm Noncommercial 1.0.0 — see its repository). The recipe
files in this tap are provided as-is.
