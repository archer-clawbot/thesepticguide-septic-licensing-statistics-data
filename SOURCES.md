# Sources (retrieved Oct 21, 2026, America/Chicago)

Inputs are The Septic Guide's own published directory data, from GitHub repo archer-clawbot/thesepticguide.com at commit 4c04730089f6275413160582a77c3b1eefaccad5 (committed 2026-10-21 15:23 CDT).

- src/data/listings.json: provider directory (exported 2026-10-21). **Not redistributed here**: it holds row-level business records. Only aggregates are published. SHA-256: 8da43d7ef00b65b395ce3bcfb7550b464c880afd03560cf4e2c8d0578587b1c1
- src/data/licensing.json: state-by-state licensing rules (asOf 2026-10-20), copied unmodified to raw/licensing.json. SHA-256: ac28da59b6d57113acb8ca975fc52275dbe32325ffd6c8ad9340a111513a167f
- src/lib/states.ts: state code to name map. SHA-256: 664d8de58ada620470a5b8def064607669be7daf0d24c4f4960255a0c2aec80e
- Live page these figures match: https://thesepticguide.com/septic-data/

The underlying license lists come from the state agencies named in state-licensing-rules.csv (agency_url column). Each agency's roster was downloaded by The Septic Guide between 2026-10-16 and 2026-10-20.
