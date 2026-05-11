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

**Public extract:** 1,000 rows · **Live catalog:** 11,060 domains · **Median ask:** $54.58 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
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

- `fit.csv` — public CSV extract (1,000 rows)
- `fit.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/fit-oneword-domains/main/fit.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| finals.fit    | available | $2.99     | —             | 80             | 7      | 6      | name.com          |
| barup.fit     | available | $2.99     | —             | 82             | 2      | 6      | name.com          |
| toneup.fit    | available | $2.99     | —             | 80             | 5      | 7      | name.com          |
| Netflix.fit   | premium   | —         | —             | 92             | 58     | 7      | —                 |
| Snickers.fit  | available | $45.98    | —             | 80             | 10     | 8      | namecheap         |
| rumcake.fit   | available | $2.99     | —             | 81             | 3      | 8      | name.com          |
| beawake.fit   | available | $2.99     | —             | 84             | 3      | 8      | name.com          |
| chaitea.fit   | available | $2.99     | —             | 86             | 3      | 8      | name.com          |
| bedframe.fit  | available | $2.99     | —             | 80             | 3      | 9      | name.com          |
| flaxseed.fit  | available | $2.99     | —             | 80             | 4      | 9      | name.com          |
| makers.fit    | available | $2.99     | —             | 62             | 67     | 6      | name.com          |
| skills.fit    | resell    | —         | —             | 58             | 47     | 6      | GoDaddy.com, LLC  |
| Ryan.fit      | premium   | $280      | $35           | 60             | 44     | 4      | namecheap         |
| travelers.fit | available | $2.99     | —             | 58             | 61     | 9      | name.com          |
| matcha.fit    | resell    | —         | —             | 86             | 39     | 6      | Sav.com, LLC - 49 |
| Tools.fit     | premium   | $280      | $35           | 56             | 40     | 5      | namecheap         |
| RedSox.fit    | available | $45.98    | —             | 72             | 60     | 7      | namecheap         |
| lets.fit      | resell    | —         | —             | 77             | 39     | 4      | Spaceship, Inc.   |
| etc.fit       | premium   | $1,000    | —             | 58             | 34     | 3      | name.com          |
| payments.fit  | available | $2.99     | —             | 58             | 33     | 8      | name.com          |

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

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is entirely .fit, so the main decision is not extension quality but name quality inside the extension. For founders, the best candidates are clear, memorable, and easy to say once, such as toneup.fit or playon.fit. For investors, the focus is tighter: broad keyword relevance, clean spelling, and buy-in discipline against the median ask of 54.58. When comparing these domains, check whether the term feels naturally connected to fitness or performance, whether it reads cleanly in lowercase, and whether plural forms, city terms, or awkward phrasing reduce resale depth or brand confidence.

- All domains in this selection use the .fit extension
- Median ask across the set is 54.58
- Best fits often read naturally with fitness or wellness
- Watch spelling, plural forms, and trademark-heavy terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FIT One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FIT page](https://unique.domains/domains/tld/fit?utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_fit_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
