# Methods

1. **Directory.** The Septic Guide built its provider directory mostly from official state license/certification rosters (26,329 providers have services attributed via a state roster), plus provider websites (2,571) and the Pennsylvania Septage Management Association member directory (194). One record per business.
2. **License match.** A provider counts as license-matched when it holds at least one credential found on an official list that is issued by its own state, or is a certification (the same rule the live site uses, `isLicensed` in src/lib/directory.ts). Only active credentials held by in-state businesses were kept by the directory.
3. **Aggregation.** src/build.py counts providers by state, county, issuer and license label. Records with a state code outside the 50 states + DC are excluded (same as the site). Counties are as recorded; providers without a county are counted in state totals only.
4. **Licensing rules** are copied from licensing.json, researched 2026-10-16 to 2026-10-20 from official agency sites. level: state / local / partial. roster: list / lookup / none.

Nothing is estimated or imputed. Blank = not available.

## Caveats
- **Match rate is not a compliance rate.** Because most listings were sourced *from* license rosters, match rates near 100% mostly reflect sourcing, not the share of all septic businesses that are licensed. States with 0 matches are states where no roster was loaded (local licensing or no public list), not states with unlicensed contractors.
- Counts are directory counts, not official state totals; a state's own roster may be larger.
- Coverage: 44 states + DC (the site rounds this to "45 states"). No providers for AK, HI, ME, MT, VT, WY. 15 jurisdictions have providers but zero license matches: CO, DC, IN, IA, KS, KY, MA, MO, NV, NJ, NM, PA, UT, WA, WI.
- One business can hold several license types, so license-types rows don't sum to provider totals.
- Small county counts are still counts only; no business is identifiable from this dataset alone.
