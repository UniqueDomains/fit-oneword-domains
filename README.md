# Available .FIT One-Word Domains (11,060)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C060%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .fit one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,060 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,060 domains · **Median ask:** $97.56 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
**Canonical page:** `https://unique.domains/domains/tld/fit`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/fit?utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./fit.csv">CSV</a> / <a href="./fit.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .FIT search](https://unique.domains/domains/tld/fit?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .FIT search](https://unique.domains/domains/tld/fit?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .FIT one-word domain catalog.

### Files

- `fit.csv`, public CSV extract (1,000 rows)
- `fit.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/fit-oneword-domains/main/fit.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain     | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                     |
| ---------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------------------- |
| beauty.fit | resell    | —         | —             | high           | low    | 6      | Spaceship, Inc.               |
| soft.fit   | premium   | $250      | $45.99        | high           | low    | 4      | name.com                      |
| lawn.fit   | available | $2.99     | —             | medium         | low    | 4      | name.com                      |
| menu.fit   | resell    | $52       | $31.20        | high           | low    | 4      | NameCheap, Inc.               |
| age.fit    | premium   | $2,500    | —             | high           | low    | 3      | name.com                      |
| pita.fit   | available | $2.99     | —             | high           | low    | 4      | name.com                      |
| her.fit    | resell    | —         | —             | medium         | low    | 3      | GoDaddy.com, LLC              |
| aid.fit    | premium   | $854      | $29.50        | medium         | low    | 3      | namesilo                      |
| pope.fit   | available | $2.99     | —             | high           | low    | 4      | name.com                      |
| cool.fit   | resell    | —         | —             | high           | low    | 4      | West263 International Limited |
| awe.fit    | premium   | $854      | $29.50        | high           | low    | 3      | namesilo                      |
| whiz.fit   | available | $42.99    | $45.99        | high           | low    | 4      | name.com                      |
| epic.fit   | resell    | —         | —             | high           | medium | 4      | GoDaddy.com, LLC              |
| beg.fit    | premium   | $854      | $29.50        | medium         | low    | 3      | namesilo                      |
| awful.fit  | available | $2.99     | $32.49        | high           | low    | 5      | namesilo                      |
| maze.fit   | resell    | —         | —             | medium         | low    | 4      | GoDaddy.com, LLC              |
| ben.fit    | premium   | $854      | $29.50        | high           | medium | 3      | namesilo                      |
| bacon.fit  | available | $2.99     | $32.49        | medium         | low    | 5      | namesilo                      |
| blank.fit  | resell    | —         | —             | medium         | low    | 5      | Spaceship, Inc.               |
| bye.fit    | premium   | $854      | $29.50        | high           | low    | 3      | namesilo                      |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,060 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/fit?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/fit?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection includes one-word .fit domains such as dogsit.fit, rolemodel.fit, and christmas.fit — short, memorable names built for fitness, wellness, and lifestyle brands. With a median asking price near $98, these domains offer a low-cost way to secure a clean, ownable name before it's taken. When comparing options within this list, prioritize dictionary words, short length, and clear pronunciation, since these traits translate directly into stronger brandability and steadier long-term renewal value.

- 11,060 one-word .fit domains in this selection
- Median asking price near $98
- Everyday words: half.fit, just.fit, feel.fit
- Ownable now — suited to fitness and wellness brands

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FIT One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FIT page](https://unique.domains/domains/tld/fit?utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
