# Available .LIMO One-Word Domains (16,987)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-16%2C987%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .limo one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **16,987 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 16,987 domains · **Median ask:** $21.74 · **High-demand under $2,500:** 0

**Last updated:** 2026-08-18
**Canonical page:** `https://unique.domains/domains/tld/limo`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/limo?utm_source=github&utm_medium=referral&utm_campaign=repo_limo_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./limo.csv">CSV</a> / <a href="./limo.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_limo_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_limo_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .LIMO search](https://unique.domains/domains/tld/limo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_limo_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .LIMO search](https://unique.domains/domains/tld/limo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_limo_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_limo_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LIMO one-word domain catalog.

### Files

- `limo.csv`, public CSV extract (1,000 rows)
- `limo.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/limo-oneword-domains/main/limo.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                          |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------------------------------ |
| act.limo      | available | $19.99    | —             | high           | low    | 3      | name.com                                                           |
| cloud.limo    | resell    | —         | —             | high           | medium | 5      | Domain Science Kutatási Szolgáltató Korlátolt Felelősségű Társaság |
| all.limo      | premium   | $123.75   | $123.75       | high           | medium | 3      | name.com                                                           |
| ain.limo      | available | $19.99    | $71.99        | low            | low    | 3      | name.com                                                           |
| motor.limo    | resell    | —         | —             | high           | low    | 5      | Sav.com, LLC - 37                                                  |
| car.limo      | premium   | $78.54    | $78.54        | high           | medium | 3      | namesilo                                                           |
| ash.limo      | available | $19.99    | —             | medium         | low    | 3      | name.com                                                           |
| flying.limo   | resell    | —         | —             | high           | low    | 6      | GoDaddy.com, LLC                                                   |
| ego.limo      | premium   | $118.80   | $118.80       | medium         | low    | 3      | namesilo                                                           |
| bad.limo      | available | $19.99    | —             | high           | medium | 3      | name.com                                                           |
| stallion.limo | resell    | —         | —             | high           | low    | 8      | Mesh Digital Limited                                               |
| ice.limo      | premium   | $242      | $242          | medium         | medium | 3      | namesilo                                                           |
| bra.limo      | available | $19.99    | —             | medium         | low    | 3      | name.com                                                           |
| asia.limo     | premium   | $500      | —             | high           | low    | 4      | name.com                                                           |
| bug.limo      | available | $19.99    | —             | high           | low    | 3      | name.com                                                           |
| golf.limo     | premium   | $250      | —             | high           | medium | 4      | name.com                                                           |
| cow.limo      | available | $19.99    | —             | high           | low    | 3      | name.com                                                           |
| post.limo     | premium   | $500      | —             | high           | medium | 4      | name.com                                                           |
| eat.limo      | available | $19.99    | —             | high           | low    | 3      | name.com                                                           |
| sexy.limo     | premium   | $250      | —             | high           | low    | 4      | name.com                                                           |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 16,987 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/limo?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_limo_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/limo?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_limo_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_limo_oneword_domains&utm_content=related_pricing)

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

This selection includes 12,682 one-word .limo domain names, spanning everyday nouns, compound words, and industry-adjacent terms such as finals.limo, bedframe.limo, and pictures.limo. The median asking price sits near $22.68, making single-word .limo names accessible for both quick investment plays and founder-led brand launches. Because .limo is a niche, non-mainstream TLD, evaluating trademark risk, memorability, and long-term renewal cost is especially important before committing to any name in this set.

- 12,682 one-word .limo domain names in this set
- Median asking price near $22.68 per domain
- Includes everyday, compound, and thematic one-word names
- Niche TLD: weigh renewal cost and brand recognition before buying

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LIMO One-Word Domains*. Version 2026-08-18. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LIMO page](https://unique.domains/domains/tld/limo?utm_source=github&utm_medium=referral&utm_campaign=repo_limo_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_limo_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_limo_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_limo_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
