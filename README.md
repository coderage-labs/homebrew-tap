# homebrew-tap

Homebrew formulae for [coderage-labs](https://github.com/coderage-labs).

```sh
brew install coderage-labs/tap/spillway
```

`brew tap owner/name` resolves to `github.com/owner/homebrew-name`, which is
why this repository is named `homebrew-tap` and not `tap`.

## Formulae

| Formula | Description |
|---|---|
| `spillway` | Pool your own AI subscription accounts behind one local proxy |

## Maintenance

Nothing here is edited by hand. `Formula/spillway.rb` is generated and
committed by goreleaser from the [spillway](https://github.com/coderage-labs/spillway)
repository's release workflow, on every tagged release. A manual edit will be
overwritten by the next one.
