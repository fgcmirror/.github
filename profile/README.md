# fgcmirror

> Preserving historic websites from the fighting-game community before they disappear.

Many of the sites that documented fighting games — character pages, move lists, official sites, fan portals — are dead or one server migration away from being lost. **fgcmirror** archives them as static, fully self-contained mirrors served from this organization.

🌐 **Browse & search all mirrors:** <https://fgcmirror.com>

## Mirrors (3)

| Title | Repository | Original |
| --- | --- | --- |
| [Buriki One](https://buriki-one.fgcmirror.com) | [source](https://github.com/fgcmirror/buriki-one) | [original](http://www.neogeo.co.jp/buriki-one/buriki-one_index.htm) |
| [Fatal Fury: Wild Ambition (Garou Densetsu Wild Ambition)](https://fatal-fury-wild-ambition.fgcmirror.com) | [source](https://github.com/fgcmirror/fatal-fury-wild-ambition) | [original](http://www.neogeo.co.jp/garou/wild_ambition/wild-ambition-index.htm) |
| [NeoGeo Battle Coliseum](https://neogeo-battle-coliseum.fgcmirror.com) | [source](https://github.com/fgcmirror/neogeo-battle-coliseum) | [original](https://game.snk-corp.co.jp/official/nbc/) |

## How to help

### Request a site to be preserved
[Open an issue in `fgcmirror/.github`](https://github.com/fgcmirror/.github/issues/new) with the site's URL (and a Wayback link if the site is dead). We'll capture and publish it.

### Improve an existing mirror
Each repository above has a `README.md` listing assets that couldn't be recovered. If you can find better snapshots or supply missing files, open a PR on that repo.

## How it works

Each site is captured (live or via the Wayback Machine), gaps are backfilled from neighbouring snapshots, every URL is rewritten to be local, and the result is published as its own public repo with GitHub Pages on a custom subdomain.
