<p align="center">
  <a href="https://atlas.freedomcore.io/"><img src="https://raw.githubusercontent.com/freedomcoreai-lang/freedomcoreai-lang/main/assets/atlas-banner.png" alt="FreedomCore Atlas — 6,735 exchange-qualified listings across 59 stock exchanges in 53 countries, 1,500 crypto assets, and 20 benchmarks" width="100%"></a>
</p>

# FreedomCore Atlas

**[atlas.freedomcore.io](https://atlas.freedomcore.io/)** is a global stock and crypto research engine covering **6,735 exchange-qualified listings**: **5,215 equities across 59 exchanges in 53 countries**, **1,500 crypto assets**, and **20 global benchmarks** (9 indices, 8 commodities, 3 FX) across **69 unique venues** (59 equity exchanges + 10 crypto and benchmark namespaces). Every price, profile, filing link and research note is checked against its source and dated; anything that fails a check is held rather than guessed.

[![Site](https://img.shields.io/badge/Site-atlas.freedomcore.io-0284c7)](https://atlas.freedomcore.io/)
[![Open data](https://img.shields.io/badge/Open_data-CC_BY_4.0-d97706)](https://atlas.freedomcore.io/datasets/)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-freedomcoreai-ffcc4d)](https://huggingface.co/freedomcoreai)
[![Kaggle](https://img.shields.io/badge/Kaggle-atlasfreedomcoreio-20beff)](https://www.kaggle.com/atlasfreedomcoreio)

---

## Live Atlas surfaces

| Surface | What it does |
| :-- | :-- |
| [Symbol directory](https://atlas.freedomcore.io/stocks/) | 6,715 company and crypto listings across 53 countries, for example [Toyota (TSE:7203)](https://atlas.freedomcore.io/stocks/7203/), [Apple (NASDAQ:AAPL)](https://atlas.freedomcore.io/stocks/AAPL/) or [Bitcoin (CRYPTO:BTC)](https://atlas.freedomcore.io/stocks/BTC/). Each page carries a dated price, verified company profile, chart, printable PDF dossier and source-cited research. |
| [Side-by-side comparisons](https://atlas.freedomcore.io/research/compare/) | Peer comparison tables built from verified fundamentals and price histories. |
| [Atlas Quakes](https://atlas.freedomcore.io/quakes/) | Source-dated company and protocol developments with daily archive editions at `/quakes/YYYY-MM-DD/`. |
| [Economic calendar](https://atlas.freedomcore.io/economic-calendar/) | Upcoming central bank decisions, CPI, GDP and labour releases from official statistical agencies. |
| [Earnings season](https://atlas.freedomcore.io/earnings-season/) | Upcoming confirmed issuer earnings dates linked directly to company realms. |
| [Daily Notes](https://atlas.freedomcore.io/notes/daily/) | Receipt-bound daily research editions tied to source links. |
| [Atlas Studio](https://atlas.freedomcore.io/studio/) | Audio and video market briefings. |
| [Research workstation](https://atlas.freedomcore.io/workstation/) | Interactive research desk with source citations. |
| [Open datasets](https://atlas.freedomcore.io/datasets/) | Full listing register, ticker collision table and security posture index as free CC BY 4.0 CSV/JSON. |
| [Methodology](https://atlas.freedomcore.io/methodology/) · [Security](https://atlas.freedomcore.io/security/) | Source admission rules, clock separation, non-fabrication boundary and reproducible controls. |

## How Atlas keeps its data accurate

- **Exact exchange listings, never bare tickers.** Every listing is keyed `EXCHANGE:TICKER`, `CRYPTO:SYMBOL`, or `COINGECKO:ID`. In the current 6,735-listing universe, **353 bare tickers collide across 776 distinct equity and crypto listings** (355 groups / 781 listings including benchmarks) — for example `SOL` maps to Solana plus four separate listed companies on ASX, BME, JSE and MIL.
- **Session-aware pricing.** Each exchange uses its own published trading hours, holidays and currency subunit scale (such as `GBp` pence and `KWF` fils). A price counts as *live* only when current for that exchange's session and verified against identity and currency rules.
- **Held, never guessed.** If a source check fails, Atlas holds the quote rather than fabricating a number. Unknown never means delisted.
- **Everything is dated and hash-verifiable.** Prices, profiles and dataset snapshots carry observation timestamps and SHA-256 digests verifiable against [`atlas-authority-manifest.json`](https://atlas.freedomcore.io/datasets/atlas-authority-manifest.json).
- **Independent peer review.** Built by Rob Sharples with an AI engineering team (Codex, Gemini and Claude) on FreedomCore infrastructure, with independent cross-family review before changes go live.

## Open data (CC BY 4.0)

- **Symbol Coverage (`6,735` listings, daily):** [Hugging Face](https://huggingface.co/datasets/freedomcoreai/atlas-symbol-coverage) · [Kaggle](https://www.kaggle.com/datasets/atlasfreedomcoreio/atlas-symbol-coverage) · [GitHub](https://github.com/freedomcoreai-lang/freedomcore-datasets) · [Interactive Explorer](https://huggingface.co/spaces/freedomcoreai/atlas-symbol-explorer)
- **Global Ticker Collisions (`355` groups / `781` listings):** [Hugging Face](https://huggingface.co/datasets/freedomcoreai/atlas-global-ticker-collisions) · [Kaggle](https://www.kaggle.com/datasets/atlasfreedomcoreio/atlas-global-ticker-collisions) · [GitHub](https://github.com/freedomcoreai-lang/freedomcore-datasets/tree/main/atlas-global-ticker-collisions)
- **Atlas Quakes Editions:** [Hugging Face](https://huggingface.co/datasets/freedomcoreai/atlas-quakes-archive) · [Live editions](https://atlas.freedomcore.io/quakes/)
- **Security Posture Index (`v3.3`):** [Hugging Face](https://huggingface.co/datasets/freedomcoreai/atlas-security-posture) · [Kaggle](https://www.kaggle.com/datasets/atlasfreedomcoreio/atlas-security-posture)
- **Kaggle analysis notebooks:** [Market data freshness audit](https://www.kaggle.com/code/atlasfreedomcoreio/market-data-freshness-audit-6-394-listings) · [Collision-free security master in Python](https://www.kaggle.com/code/atlasfreedomcoreio/collision-free-security-master-in-python) · [Global equity coverage across 59 exchanges](https://www.kaggle.com/code/atlasfreedomcoreio/global-equity-coverage-59-exchanges-53-countries)
- **Zenodo (citable archive):** [10.5281/zenodo.20717847](https://doi.org/10.5281/zenodo.20717847)
- **Provenance note:** [docs/atlas-public-data-authority.md](docs/atlas-public-data-authority.md)

## Contact

For licensing, partnerships or questions about the data: [support@freedomcore.io](mailto:support@freedomcore.io)

Atlas is research. Nothing here is financial advice, and Atlas does not execute trades.

<sub>This repository previously held the earlier FreedomCore site and token materials. Those files remain in `/site`, `/contract` and `/docs` as an archive; they are not part of Atlas.</sub>
