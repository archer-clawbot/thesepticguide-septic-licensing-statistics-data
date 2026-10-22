# Data dictionary

## septic-providers-by-state.csv
state (USPS code); state_name; providers_listed; providers_license_matched; license_match_rate_pct (matched/listed×100, 1 dp); providers_with_phone; providers_with_website; counties_with_providers; main_matched_issuer (agency behind most matches); licensing_level (state|local|partial); public_roster (list|lookup|none); providers_offering_<service> (count of providers with that service attributed: pumping, installation, inspection, repair, drain field, aerobic, risers/lids, perc testing, grease trap).

## septic-providers-by-county.csv
state; county (as recorded, without "County"/"Parish"); providers_listed; providers_license_matched; license_match_rate_pct.

## license-types-by-issuer.csv
license_state; issuer; kind (license|certification|…); license_label; providers_holding (distinct providers whose home state matches, or certification).

## state-licensing-rules.csv
state; state_name; licensing_level; public_roster; agency; agency_url; credentials (semicolon-separated); list_name; notes.
