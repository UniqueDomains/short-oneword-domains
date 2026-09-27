# Short One-Word Domains, 6 Characters or Fewer (3,191,143)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-3%2C191%2C143%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

This selection covers short, one-word domain names of six characters or fewer across 506 TLDs. It includes 1,759,539 domains with a median ask of $420. Updated daily, most entries fall under $500, with a smaller premium tier priced above $2,000.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **3,191,143 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 3,191,143 domains · **Median ask:** $269.21 · **High-demand under $2,500:** 6,697

**Last updated:** 2026-09-27
**Canonical page:** `https://unique.domains/domains/short`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/short?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./short.csv">CSV</a> / <a href="./short.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this exact search](https://unique.domains/domains/short?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this exact search](https://unique.domains/domains/short?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for the exact Unique Domains search represented by `https://unique.domains/domains/short`.

### Files

- `short.csv`, public CSV extract (1,000 rows)
- `short.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/short-oneword-domains/main/short.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| aba.bargains    | available | $21.99    | $43.99        | high           | low    | 3      | name.com          |
| remote.autos    | resell    | $684.64   | —             | high           | medium | 6      | NameCheap, Inc.   |
| boy.singles     | premium   | $41.99    | —             | high           | low    | 3      | name.com          |
| aec.vc          | available | $32.98    | $41.98        | high           | low    | 3      | namecheap         |
| bet.news        | resell    | —         | —             | high           | medium | 3      | Name.com, Inc.    |
| bug.study       | premium   | $625      | —             | high           | low    | 3      | name.com          |
| afl.forsale     | available | $13.98    | $47.48        | high           | low    | 3      | namecheap         |
| dna.tours       | resell    | —         | —             | high           | medium | 3      | Dynadot Inc       |
| cad.mobile      | premium   | $390      | $390          | high           | low    | 3      | namecheap         |
| aid.enterprises | available | $5.99     | —             | high           | low    | 3      | name.com          |
| ely.us          | resell    | —         | —             | high           | low    | 3      | GoDaddy.com, LLC  |
| cat.motorcycles | premium   | $2,500    | —             | high           | high   | 3      | name.com          |
| ala.delivery    | available | $8.99     | —             | high           | low    | 3      | name.com          |
| emu.us          | resell    | —         | —             | high           | high   | 3      | GoDaddy.com, LLC  |
| ccc.download    | premium   | $625      | $81.25        | high           | medium | 3      | name.com          |
| ala.markets     | available | $9.99     | —             | high           | low    | 3      | name.com          |
| fan.app         | resell    | —         | —             | high           | medium | 3      | united-domains AG |
| cva.press       | premium   | $162.50   | $325          | medium         | low    | 3      | namecheap         |
| avo.clothing    | available | $32.99    | $32.99        | high           | low    | 3      | namesilo          |
| fop.co          | resell    | —         | —             | high           | low    | 3      | GoDaddy.com, LLC  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 3,191,143 live domains                     |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 6,697 high-demand names under $2,500       |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/short?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/short?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=related_pricing)

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
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This is a broad pool of short, one-word domain names limited to six characters or fewer, spread across 506 different TLD extensions rather than one narrow category. Pricing skews affordable — the bulk of listings sit under $500, with a thinner tier of premium names priced above $2,000 and a small handful above $10,000. Availability status is mixed, so checking each domain's status and renewal cost before shortlisting is worthwhile.

- 1,759,539 domains, six characters or fewer, across 506 TLDs
- Median ask $420; most list under $500, some premium above $10k
- 76% status Available, with Premium and Resell tiers mixed in
- Only ~2% score in the Top 15% demand tier — scarcity matters

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Short One-Word Domains, 6 Characters or Fewer*. Version 2026-09-27. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live search](https://unique.domains/domains/short?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
