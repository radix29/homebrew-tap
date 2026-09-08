# radix29 Homebrew tap

Homebrew formulae for [radix29](https://github.com/radix29)'s tools.

```sh
brew install radix29/tap/gossms
```

Or, to keep the tap around for future formulae:

```sh
brew tap radix29/tap
brew install gossms
```

## gossms

[goSSMS](https://github.com/radix29/gossms) — a portable, cross-platform
terminal reimplementation of SQL Server Management Studio. macOS (Apple
silicon and Intel) and Linux (amd64 and arm64).

`Formula/gossms.rb` is **generated**, not written by hand: the release
workflow in `radix29/gossms` renders it from the published release archives
and their checksums on every tag, and pushes it here. Edits made directly to
that file are overwritten by the next release. Change the template in
`.github/workflows/release.yml` in the gossms repo instead.
