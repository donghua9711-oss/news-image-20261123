# The World in One Day — Monday 23 November 2026

[![make.fun — news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123)
[![Rank](https://make.fun/badge/news-image-20261123/donghua9711-oss/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123)
[![Reward](https://make.fun/badge/news-image-20261123/donghua9711-oss/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Output](https://img.shields.io/badge/output-1024%C3%971024%20PNG%20%E2%89%A4%201%20MiB-blue)](entry.png)

One image that sums up the world news of **Monday 23 November 2026**: a one-page
newspaper. Thirty stories from seven regions — COP31's collapse in
Antalya, the Dymer apartment strike, tankers ablaze near Hormuz, the
Russian corvette sunk at Benghazi, Asia's AI rout, the Democrats'
largest House majority since 1992, the Banten factory fire and the
Shenzhen trilateral summit — drawn, mapped and footnoted on a single
page.

## The page

- Navy masthead with the day and a rainbow band of region
  counts, then a "day in UTC" timeline of five grounded
  moments.
- Three lead stories with artwork on top, then eight more
  illustrated cards — eleven drawn stories in all.
- A dot-matrix world map marking where it happened, and the
  remaining stories as one-line briefs.
- A date-check footer: everything printed happened, or was
  first reported, on Monday 23 November 2026. Developing stories are framed as
  reports and claims are attributed.

## Run it

```bash
node main.ts
```

Running the program writes `entry.png` (1024×1024 PNG, under
the 1 MiB cap) to the output directory — `MAKEFUN_OUTPUT_DIR`
or `/output` — and nowhere else, byte-identical on every run.
The page itself is composed by `compose.py` from the artwork
in `assets/`; per-story sourcing lives in [SOURCES.md](SOURCES.md).

## License

MIT — see [LICENSE](LICENSE).
