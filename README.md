# Septic Contractor Licensing Statistics by State (U.S., 2026)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23550643.svg)](https://doi.org/10.5281/zenodo.23550643)

Published by **The Septic Guide** (https://thesepticguide.com/). This GitHub repository is a mirror; the canonical, versioned release is on Zenodo.

- **DOI:** [10.5281/zenodo.23550643](https://doi.org/10.5281/zenodo.23550643)
- **Zenodo record:** https://zenodo.org/records/23550643
- **Data page:** https://thesepticguide.com/septic-data/
- **License:** CC BY 4.0 (see LICENSE)

## How to cite
The Septic Guide. *Septic Contractor Licensing Statistics by State (U.S., 2026)*. Zenodo. https://doi.org/10.5281/zenodo.23550643

---

# Septic Contractor Licensing Statistics by State (U.S., 2026)

Compiled by **The Septic Guide** (https://thesepticguide.com/). License: CC BY 4.0.

Aggregate counts of septic service providers in The Septic Guide directory, how many are matched to an official state license or certification list, the agencies and license types behind those matches, and each state's licensing rules (state vs. local licensing, whether a public roster exists). **No row-level contractor records** (names, phones, addresses, websites, license numbers) are included.

| File | Rows | What |
|---|---|---|
| septic-providers-by-state.csv | 45 | Providers, license-matched, match rate, phone/website counts, services, licensing level |
| septic-providers-by-county.csv | 1,828 | Providers and license-matched by county/parish |
| license-types-by-issuer.csv | 421 | Providers holding each license type, by issuing agency |
| state-licensing-rules.csv | 51 | 50 states + DC: who licenses septic work, credentials, roster availability |
| summary.json | – | National totals |

Headline: 28,546 providers listed in 44 states + DC; 27,065 (94.8%) matched to license/certification lists from 26 state agencies. Snapshot as of Oct 21, 2026.

Rebuild: `python3 src/build.py /path/to/thesepticguide.com`. See METHODS.md, DATA-DICTIONARY.md, FINDINGS.md.
Suggested citation: The Septic Guide (2026). Septic Contractor Licensing Statistics by State. https://thesepticguide.com/septic-data/
