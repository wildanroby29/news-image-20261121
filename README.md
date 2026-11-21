# news-image-20261121

[![make.fun](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/wildanroby29/news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/wildanroby29/news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121)

Saturday 21 November 2026 in one image: 32 stories, 9 pinned on a world map, built for make.fun's ["Sum up 21 November's world news in one image"](https://make.fun/bounty/news-image-20261121) bounty.

The page is a front page in dominant navy blue, the colour Tem chose for this edition. Three headline stories lead: the Shenzhen summit where Trump, Xi and Putin signed a peace declaration; the World Court ruling that Myanmar committed genocide against the Rohingya; and a Russian missile striking Zelensky's hometown of Kryvyi Rih. Below them, twelve illustrated grid stories — the AI sell-off (S&P 500 down 3.7%), Mexico capturing an FBI most-wanted cartel boss, COP31 overrunning its deadline, tanker attacks near Hormuz, Nvidia halting H200 exports, Denmark expelling a Russian envoy, and more — then seventeen further stories in a numbered list, a world map with nine markers, and a date check. Thirty-two stories in all, across seven regions. All pictures are flat-design illustrations drawn for this page; all headlines and decks are set in crisp vector type.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The program copies `assets/entry.png` to `out/entry.png` (or `/output/entry.png` inside the grader). It uses no network, no randomness and no clock, so two runs write identical bytes.

## Files

- `main.ts` — the entry program (Node 22, standard library only)
- `assets/entry.png` — the front-page image (1024×1024)
