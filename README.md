<p align="center">
  <a href="https://atlas.freedomcore.io/"><img src="https://raw.githubusercontent.com/freedomcoreai-lang/freedomcoreai-lang/main/assets/atlas-banner.png" alt="FreedomCore Atlas" width="100%"></a>
</p>

# FreedomCore Atlas

**[atlas.freedomcore.io](https://atlas.freedomcore.io/)** is a global stock and crypto research engine. It covers 6,394 listings: 4,875 equities on 59 exchanges in 53 countries, 1,500 crypto assets, plus indices, commodities and FX. Every price, profile and research note is checked against its source and dated, and anything that fails a check is held rather than guessed.

[![Site](https://img.shields.io/badge/Site-atlas.freedomcore.io-0284c7)](https://atlas.freedomcore.io/)
[![Open data](https://img.shields.io/badge/Open_data-CC_BY_4.0-d97706)](https://atlas.freedomcore.io/datasets/)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-freedomcoreai-ffcc4d)](https://huggingface.co/freedomcoreai)
[![Kaggle](https://img.shields.io/badge/Kaggle-atlasfreedomcoreio-20beff)](https://www.kaggle.com/atlasfreedomcoreio)

---

## What you'll find on Atlas

| Surface | What it does |
| :-- | :-- |
| [Symbol pages](https://atlas.freedomcore.io/stocks/) | One page per listing, for example [Toyota (TSE:7203)](https://atlas.freedomcore.io/stocks/7203/) or [Bitcoin](https://atlas.freedomcore.io/stocks/BTC/). Each has its price with the time it was observed, a verified company profile, a chart and source-cited research. |
| [Atlas Quakes](https://atlas.freedomcore.io/quakes/) | Source-dated company and protocol developments as they happen. |
| [Daily Notes](https://atlas.freedomcore.io/notes/daily/) | Daily research editions, each tied to its sources. |
| [Atlas Studio](https://atlas.freedomcore.io/studio/) | Audio and video market briefings. |
| [Research workstation](https://atlas.freedomcore.io/workstation/) | Interactive research desk with source citations. |
| [Economic calendar](https://atlas.freedomcore.io/economic-calendar/) | Upcoming macro releases and events. |
| [Open datasets](https://atlas.freedomcore.io/datasets/) | The full listing register as free CSV/JSON. |
| [Methodology](https://atlas.freedomcore.io/methodology/) · [Security](https://atlas.freedomcore.io/security/) | How sources are admitted, and the public controls you can check yourself. |

## How Atlas keeps its data accurate

- **Exact listings, not bare tickers.** Every listing is keyed `EXCHANGE:TICKER`. "SOL" is Solana, but it's also four different listed companies, and Atlas keeps them apart (330 tickers in the register are shared by more than one instrument).
- **Prices are checked against the exchange's own calendar.** Each exchange is wired in one at a time, using trading hours and holidays taken from the exchange's published notices. A price only counts as *live* if it's current for that exchange's session and its currency, venue and company identity all match.
- **Held, never guessed.** If a check fails, the page says the price is held or stale instead of showing a number it can't stand behind. Unknown never means delisted.
- **Everything is dated.** Prices, profiles and research each carry the time they were observed, so you can always see how fresh a figure is.
- **Built and reviewed by an AI team.** Atlas is built by a small team of AI collaborators (Codex, Gemini and Claude) on FreedomCore's own servers. Each change is independently reviewed by another member before it goes live.

## Open data

The listing register is published daily under **CC BY 4.0**. It shows, for every listing, whether its price is live, and which profile, research and chart layers exist.

- **Hugging Face:** [freedomcoreai/atlas-symbol-coverage](https://huggingface.co/datasets/freedomcoreai/atlas-symbol-coverage) · search it in the [Atlas Symbol Explorer](https://huggingface.co/spaces/freedomcoreai/atlas-symbol-explorer)
- **Kaggle:** [atlasfreedomcoreio/atlas-symbol-coverage](https://www.kaggle.com/datasets/atlasfreedomcoreio/atlas-symbol-coverage) · analysis notebook: [Market data freshness audit](https://www.kaggle.com/code/atlasfreedomcoreio/market-data-freshness-audit-6-394-listings)
- **GitHub:** [freedomcore-datasets](https://github.com/freedomcoreai-lang/freedomcore-datasets)
- **Zenodo (citable archive):** [10.5281/zenodo.20717847](https://doi.org/10.5281/zenodo.20717847)
- **Provenance note:** [docs/atlas-public-data-authority.md](docs/atlas-public-data-authority.md)

## Contact

For partnerships, licensing or questions about the data: [freedomcoreai@gmail.com](mailto:freedomcoreai@gmail.com)

Atlas is research. Nothing here is financial advice, and Atlas doesn't execute trades.

<sub>This repository previously held the earlier FreedomCore site and token materials. Those files remain in `/site`, `/contract` and `/docs` as an archive; they are not part of Atlas.</sub>
