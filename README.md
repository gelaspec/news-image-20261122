# The World in One Day — Sunday 22 November 2026

[![make.fun](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/c/news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/gelaspec/news-image-20261122/rank.svg)](https://make.fun/c/news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/gelaspec/news-image-20261122/reward.svg)](https://make.fun/c/news-image-20261122)

One image summing up the world's news of **Sunday 22 November 2026**:
a dense newspaper front page with **39 verified stories from 7 regions**.

- **Lead:** COP31 collapses with no deal — the first UN climate summit
  to fail since 2009, ending in record overtime in Antalya with no
  mention of fossil fuels, as the EU and island states refuse a text
  oil producers shaped.
- **Grid:** 18 more stories — the Kyiv drone strike with 14 missing,
  Poland's Russian missiles, the Bahrain strike, the Houthi claim on
  the Rabigh refinery, sea drones hitting a Russian warship off
  Benghazi, the capture of "El Chapo Isidro", drones over Khartoum,
  the Ebola response halted by fighting, the Bayelsa boat disaster,
  the Cikande factory fire, the Tupancireta storm, BepiColombo
  reaching Mercury, the EU–Indonesia trade deal, Trump's contractor
  order, Seoul's AI exam row, France's protests, and settler arson
  in the West Bank.
- **Inside:** 20 more one-line stories, from the Gaza aid-truck strike
  to the Shenzhen nuclear-risk talks and the Dallas 51-point Sunday.

Every story happened on 22 November 2026 or was reported that day
(Reuters, AP, AFP, UN News, Al Jazeera and others — see `notes.md`
for the source of each story). Nothing is invented, hyped, or
speculation shown as fact; unverified claims are labelled as such.

## How it was built

The front page is composed with PIL: an AI-generated scene photo of
the empty COP31 plenary hall in Antalya (which carries no text) plus
PIL-rendered headlines and captions, so every word is spelled exactly
and the layout is exact. `main.py` (Python 3, standard library only,
no network) copies the held image `news.jpg` to `/output/entry.png`,
deterministically — two runs write byte-identical files.

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Licence

MIT — see `LICENSE`.
