# Available .STORE One-Word Domains (68,360)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-68%2C360%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .store one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **68,360 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 68,360 domains · **Median ask:** $320.66 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
**Canonical page:** `https://unique.domains/domains/tld/store`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/store?utm_source=github&utm_medium=referral&utm_campaign=repo_store_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./store.csv">CSV</a> / <a href="./store.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_store_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_store_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .STORE search](https://unique.domains/domains/tld/store?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_store_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .STORE search](https://unique.domains/domains/tld/store?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_store_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_store_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .STORE one-word domain catalog.

### Files

- `store.csv`, public CSV extract (1,000 rows)
- `store.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/store-oneword-domains/main/store.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                          |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------------------------- |
| half.store       | premium   | $312.50   | $1,250        | high           | low    | 4      | name.com                           |
| getpast.store    | available | $2.99     | —             | high           | low    | 8      | name.com                           |
| weed.store       | resell    | —         | —             | medium         | low    | 4      | Namify Domains Inc                 |
| ala.store        | premium   | $781.25   | —             | high           | low    | 3      | name.com                           |
| howmany.store    | available | $2.99     | —             | medium         | low    | 8      | name.com                           |
| handy.store      | resell    | —         | —             | medium         | high   | 5      | Global Domains International, Inc. |
| ask.store        | premium   | $312.50   | —             | high           | medium | 3      | name.com                           |
| intight.store    | available | $2.99     | —             | medium         | low    | 8      | name.com                           |
| sahib.store      | resell    | —         | —             | medium         | high   | 5      | Namecheap                          |
| hat.store        | premium   | $312.50   | —             | high           | low    | 3      | name.com                           |
| turntup.store    | available | $2.99     | —             | high           | low    | 8      | name.com                           |
| thrive.store     | resell    | —         | —             | high           | high   | 6      | Namecheap                          |
| ivy.store        | premium   | $781.25   | —             | high           | low    | 3      | name.com                           |
| dishonour.store  | available | $2.99     | —             | high           | low    | 9      | name.com                           |
| fifteen.store    | resell    | —         | —             | high           | low    | 7      | GoDaddy.com, LLC                   |
| pot.store        | premium   | $3,125    | —             | high           | low    | 3      | name.com                           |
| keepback.store   | available | $2.99     | —             | medium         | low    | 9      | name.com                           |
| online.store     | resell    | —         | —             | high           | medium | 7      | Namify Domains Inc                 |
| buds.store       | premium   | $156.25   | —             | medium         | low    | 4      | name.com                           |
| adjectives.store | available | $2.99     | —             | medium         | low    | 10     | name.com                           |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 68,360 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/store?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_store_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/store?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_store_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_store_oneword_domains&utm_content=related_pricing)

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

This selection includes one-word .STORE domain names such as RomanEmpire.store, half.store, out.store, okay.store, and christmas.store — short, ecommerce-ready names built for retail and online store brands. With a median ask near $321 across 68,360 domains, pricing spans from budget-friendly to premium depending on word rarity and length. Renewal costs and rarity vary by registrar, so compare each name's ask price and renewal rate before deciding which one-word .STORE domain fits a launch or a portfolio.

- 68,360 one-word .STORE domain names, updated daily
- Median ask near $321 across this selection
- Short, brandable names built for ecommerce brands
- Compare ask price and renewal cost before you commit

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .STORE One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .STORE page](https://unique.domains/domains/tld/store?utm_source=github&utm_medium=referral&utm_campaign=repo_store_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_store_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_store_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_store_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
