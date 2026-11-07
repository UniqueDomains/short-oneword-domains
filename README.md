# Short One-Word Domains (~6,910,000)

~6,910,000 names in this list today, refreshed every night.

Live page: [unique.domains/domains/short](https://unique.domains/domains/short?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=top_page)

<img alt="updated: daily" src="https://img.shields.io/badge/updated-daily-0969da"> <img alt="extract: 1,000 rows" src="https://img.shields.io/badge/extract-1%2C000%20rows-8250df"> <img alt="formats: CSV | JSON" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b"> <img alt="licence: CC BY 4.0" src="https://img.shields.io/badge/licence-CC%20BY%204.0-2ea44f">

## Download

- [short.csv](https://github.com/UniqueDomains/short-oneword-domains/raw/main/short.csv), 1,000 rows
- [short.json](https://github.com/UniqueDomains/short-oneword-domains/raw/main/short.json), 1,000 rows

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/short-oneword-domains/main/short.csv")
print(df.head())
```

## Sample rows

The first 20 rows of the file, in the file's order.

| domain           | status    | purchase_price | renewal_price | attractiveness | demand | length |
| ---------------- | --------- | -------------- | ------------- | -------------- | ------ | ------ |
| azur.watch       | available | $5.99          | $44.49        | medium         | low    | 4      |
| mazama.equipment | available | $22.97         | $22.97        | medium         | low    | 6      |
| ripen.click      | premium   | $72.65         | $103.70       | high           | low    | 5      |
| mhc.fyi          | premium   | $15.73         | $15.73        | high           | low    | 3      |
| pueblo.sale      | available | $7             | —             | medium         | low    | 6      |
| csm.salon        | available | $45.74         | $45.74        | high           | low    | 3      |
| befit.win        | premium   | $448           | $53.92        | high           | low    | 5      |
| shari.hospital   | available | $44.20         | $44.20        | medium         | low    | 5      |
| khel.im          | available | $4.18          | $6.73         | medium         | low    | 4      |
| tind.coach       | available | $10.55         | $62.30        | high           | low    | 4      |
| lar.rest         | available | $2.19          | $28.99        | medium         | low    | 3      |
| carers.hamburg   | available | $69.98         | $73.98        | medium         | low    | 6      |
| cta.photography  | available | $14.49         | $36.49        | high           | low    | 3      |
| surrey.pink      | available | $21.62         | $21.62        | high           | low    | 6      |
| shifts.boston    | available | $23.49         | $23.49        | medium         | low    | 6      |
| zed.mom          | available | $1.24          | $26           | high           | low    | 3      |
| ters.poker       | available | $10.99         | $67.99        | low            | low    | 4      |
| lodger.cheap     | available | $5.57          | $30.18        | medium         | low    | 6      |
| isf.codes        | available | $55.20         | $55.20        | medium         | low    | 3      |
| huck.ooo         | premium   | $58.99         | $23.59        | high           | low    | 4      |

## What is in the data

- `domain`: Fully qualified domain name.
- `status`: Current acquisition state for the domain in the public extract.
- `purchase_price`: Visible purchase price when available.
- `renewal_price`: Visible renewal price when available.
- `attractiveness`: Public composite naming band used as a decision-support signal.
- `demand`: Public buyer-pressure band when available.
- `length`: Character count without the TLD.
- `registrar`: Registrar name when known.
- `created_at`: Creation timestamp when known.
- `expires_at`: Expiry timestamp when known.

Types and formats: [DATA_DICTIONARY.md](./DATA_DICTIONARY.md).

## Methodology

- The files hold 1,000 rows of the ~6,910,000 names in the live list today.
- Every row is a one-word domain name.
- Status and prices are the last ones Unique Domains stored for each name, not a reading taken on the day of the rebuild.
- The live count marked with a tilde is estimated from a 2 percent page sample of the catalog and rounded to three significant digits; it moves between nights. The rows in the files are real rows.

More in [METHODOLOGY.md](./METHODOLOGY.md).

## Update policy

- The files are rebuilt every night from the same export.
- The snapshot is the day of the rebuild; each row's status is the last one stored, not a reading of that day.
- The files hold the public extract, not the whole live list.

## How to cite

> Unique Domains, Short One-Word Domains, https://unique.domains/domains/short, CC BY 4.0

Citation metadata: [CITATION.cff](./CITATION.cff). A DOI follows once Zenodo mints one.

## Related datasets

- [Every one-word domain](https://github.com/UniqueDomains/oneword-domains) (the hub)

One-word domains by ending:

- [.com](https://github.com/UniqueDomains/com-oneword-domains), [page](https://unique.domains/tld/com?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=related_tld_page)
- [.ai](https://github.com/UniqueDomains/ai-oneword-domains), [page](https://unique.domains/tld/ai?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=related_tld_page)
- [.io](https://github.com/UniqueDomains/io-oneword-domains), [page](https://unique.domains/tld/io?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=related_tld_page)
- [.app](https://github.com/UniqueDomains/app-oneword-domains), [page](https://unique.domains/tld/app?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=related_tld_page)
- [.co](https://github.com/UniqueDomains/co-oneword-domains), [page](https://unique.domains/tld/co?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=related_tld_page)
- [.xyz](https://github.com/UniqueDomains/xyz-oneword-domains), [page](https://unique.domains/tld/xyz?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=related_tld_page)

Lists:

- [Expired](https://github.com/UniqueDomains/expired-oneword-domains)
- [Expiring](https://github.com/UniqueDomains/expiring-oneword-domains)
- [Brandable](https://github.com/UniqueDomains/brandable-oneword-domains)

Every ending Unique Domains tracks: [unique.domains/tld](https://unique.domains/tld?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=related_hub).

## About Unique Domains

[Unique Domains](https://unique.domains/?utm_source=github&utm_medium=referral&utm_campaign=repo_short_oneword_domains&utm_content=about) tracks one-word domain names across the endings people build on: which are free to register, what they cost to hold and what names of each ending sell for. The datasets in this organization are its public extracts, refreshed every night.

Questions and corrections: `kai@unique.domains`
