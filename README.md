# repo-slots

An experiment in tokenizing the files of a repository. Parts of this repo are **slots** on a board
on a testnet (chain 46630, test money only). Whoever holds a slot writes it, and a service
commits what they wrote, here, on `main`. The board and every slot are listed in
[`slots.json`](slots.json).

## Featured

<!-- slot:readme.featured -->
_The owner wrote over this slot._
<!-- /slot -->

## Banner

<!-- slot:readme.banner -->
[![A holder's banner](slots/banner.png)](https://github.com/vibecodermaxi/websitekit)
<!-- /slot -->

## A note

<!-- slot:readme.note -->
> Math and a diagram, in one slot:
>
> $e^{i\pi} + 1 = 0$

```mermaid
flowchart LR
  buy[Buy on chain] --> edit[Edit the hash] --> commit[The writer commits]
```

<!-- /slot -->

## Whole files that are slots

- [`slots/banner.png`](slots/banner.png): the banner picture
- [`data/table.csv`](data/table.csv): a table
- [`docs/index.md`](docs/index.md): the home page of this repo's [site](https://vibecodermaxi.github.io/repo-slots/)

Built on [websitekit](https://github.com/vibecodermaxi/websitekit).
