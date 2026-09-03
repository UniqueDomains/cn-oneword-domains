# Available .CN One-Word Domains (899)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-899%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-899%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .cn one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 899 rows · **Live catalog:** 899 domains · **Median ask:** $0 · **High-demand under $2,500:** 0

**Last updated:** 2026-09-03
**Canonical page:** `https://unique.domains/domains/tld/cn`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/cn?utm_source=github&utm_medium=referral&utm_campaign=repo_cn_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./cn.csv">CSV</a> / <a href="./cn.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cn_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cn_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CN search](https://unique.domains/domains/tld/cn?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cn_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CN search](https://unique.domains/domains/tld/cn?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cn_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cn_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CN one-word domain catalog.

### Files

- `cn.csv`, public CSV extract (899 rows)
- `cn.json`, public JSON extract (899 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cn-oneword-domains/main/cn.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                           |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------------------------- |
| tender.cn     | resell    | —         | —             | high           | low    | 6      | Dynadot Inc                         |
| above.cn      | resell    | —         | —             | high           | low    | 5      | 阿里云计算有限公司（万网）                       |
| negative.cn   | resell    | —         | —             | high           | low    | 8      | 广西北部湾在线投资控股有限公司                     |
| cream.cn      | resell    | —         | —             | high           | —      | 5      | 阿里云计算有限公司（万网）                       |
| easter.cn     | resell    | —         | —             | high           | low    | 6      | Dynadot Inc                         |
| academic.cn   | resell    | —         | —             | high           | low    | 8      | 阿里云计算有限公司（万网）                       |
| ethical.cn    | resell    | —         | —             | high           | —      | 7      | 阿里云计算有限公司（万网）                       |
| midOctober.cn | available | —         | —             | high           | low    | 11     | —                                   |
| concise.cn    | resell    | —         | —             | high           | low    | 7      | 阿里云计算有限公司（万网）                       |
| lunch.cn      | resell    | —         | —             | high           | low    | 5      | Dynadot Inc                         |
| organic.cn    | resell    | —         | —             | high           | low    | 7      | Dynadot Inc                         |
| nutrient.cn   | resell    | —         | —             | high           | low    | 8      | Dynadot Inc                         |
| dirty.cn      | resell    | —         | —             | high           | low    | 5      | 阿里云计算有限公司（万网）                       |
| individual.cn | resell    | —         | —             | high           | low    | 10     | Dynadot Inc                         |
| elite.cn      | resell    | —         | —             | high           | medium | 5      | Web Commerce Communications Limited |
| efficient.cn  | resell    | —         | —             | high           | low    | 9      | 阿里云计算有限公司（万网）                       |
| familiar.cn   | resell    | —         | —             | high           | —      | 8      | 阿里云计算有限公司（万网）                       |
| half.cn       | resell    | —         | —             | high           | low    | 4      | 厦门易名科技股份有限公司                        |
| driving.cn    | resell    | —         | —             | high           | low    | 7      | Dynadot Inc                         |
| christian.cn  | resell    | —         | —             | high           | medium | 9      | Dynadot Inc                         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract        | Unique Domains                             |
| --------------------- | ------------------------------------------ |
| 899-row public sample | 899 live domains                           |
| Static CSV / JSON     | live search and daily refresh              |
| Basic exported fields | 0 high-demand names under $2,500           |
| No persistence        | Radar, saved search, and alerts            |
| No founder workflow   | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/cn?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cn_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/cn?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cn_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cn_oneword_domains&utm_content=related_pricing)

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

This set of one-word .CN domain names covers a wide range of naming styles, from everyday dictionary words like messages.cn and tips.cn to distinctive names built around pop culture, technology, and history. Several entries closely resemble existing brands or products, such as MacBook.cn and myspace.cn, which makes trademark screening an important step before acquiring any name in this list. Others, like based.cn and JollyRoger.cn, offer short, brandable options with fewer obvious conflicts. Because renewal costs and demand vary by name, each domain should be reviewed individually rather than assessed as a single category.

- 750 one-word .CN domains spanning dictionary and brand-like terms
- Mix of short common words and recognizable name-based domains
- Some names resemble existing brands—check trademark risk first
- Updated daily to reflect the current .CN one-word inventory

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CN One-Word Domains*. Version 2026-09-03. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CN page](https://unique.domains/domains/tld/cn?utm_source=github&utm_medium=referral&utm_campaign=repo_cn_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cn_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cn_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cn_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
