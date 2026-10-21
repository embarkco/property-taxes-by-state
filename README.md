# Property taxes by U.S. state, 2026

Property taxes in all 50 states and the District of Columbia: median real estate taxes paid on owner-occupied homes and median home values (U.S. Census Bureau, American Community Survey 2024 1-year), the effective rate they give, that rate on a $400,000 home, and whether each state’s taxes are paid in arrears or in advance, which decides who credits whom at closing.

- **Web page, charts and methodology:** https://brokerandagent.com/research/property-taxes-by-state
- **Files:** [`data/property-taxes-by-state.csv`](data/property-taxes-by-state.csv) and [`data/property-taxes-by-state.json`](data/property-taxes-by-state.json) (the same rows, with full detail in the JSON)
- **Coverage:** all 50 states and the District of Columbia
- **Last updated:** 2026-10-01
- **Publisher:** [Broker & Agent Solutions](https://brokerandagent.com), a real estate software company in Sarasota, Florida

## Columns (CSV)

| Column | What it is |
|---|---|
| `state_code` | Two-letter postal code |
| `state` | State name (the District of Columbia included) |
| `median_taxes_paid` | Median real estate taxes paid a year on owner-occupied homes, Census ACS 2024 1-year (B25103), in dollars |
| `median_taxes_paid_moe` | The Census Bureau’s margin of error for that figure (90% confidence) |
| `median_home_value` | Median value of owner-occupied homes, Census ACS 2024 1-year (B25077) |
| `effective_rate_pct` | Median taxes paid as a percent of median home value |
| `tax_on_400k` | That rate applied to a $400,000 home, in dollars a year (an illustration: actual bills depend on local rates, assessments and exemptions) |
| `paid` | When taxes usually fall due: in arrears (after the period they cover) or in advance |
| `at_closing` | Who usually credits whom for the year’s taxes at closing |
| `last_checked` | When the state’s tax timing was last checked against its sources |

## Sources

- https://data.census.gov/table/ACSDT1Y2024.B25103
- https://data.census.gov/table/ACSDT1Y2024.B25077

## Limits

These are Census survey estimates with margins of error (included). The effective rate is a statewide median ratio, not any one home's bill: local rates, assessments, reassessment at sale and exemptions all change what a given owner pays.

## License

[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You can copy, share and adapt it, commercially too, as long as you credit Broker & Agent Solutions and link to the source page.

## How to cite

> Broker & Agent Solutions. "Property taxes by U.S. state, 2026." Updated 2026-10-01. https://brokerandagent.com/research/property-taxes-by-state. Licensed under CC BY 4.0.

More on crediting and versions: https://brokerandagent.com/research/use-our-data

## Updates and corrections

The data is reviewed at least every six months and whenever a law changes. Each update is a new release here, so earlier versions stay available. Spot something out of date? Email hello@brokerandagent.com or open an issue, with a source if you have one.

## Related datasets

- [Real estate transfer tax by U.S. state, 2026](https://brokerandagent.com/research/transfer-tax-by-state) · [GitHub](https://github.com/embarkco/transfer-tax-by-state)
- [Closing costs by U.S. state, 2026](https://brokerandagent.com/research/closing-costs-by-state) · [GitHub](https://github.com/embarkco/closing-costs-by-state)
