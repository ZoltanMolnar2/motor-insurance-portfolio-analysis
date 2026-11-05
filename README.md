# Where Is the Money Going?
### Motor Insurance Portfolio Analysis | Power BI

An interactive Power BI case study investigating financial deterioration in an anonymised motor insurance portfolio between 2022 and 2024.

The analysis examines why incurred claim costs increased faster than recorded premiums, which parts of the portfolio contributed most to the deterioration, and whether the pattern persists among policies observed in consecutive years.

## Key findings

- **Portfolio deterioration:** The claims-to-premium ratio increased from 65.62% in 2022 to 74.66% in 2024, a rise of 9.04 percentage points (pp).
- **Financial drivers:** A symmetric decomposition attributes +2.27 pp to the claim-cost-per-exposure component and +6.77 pp to the premium-per-exposure component.
- **Portfolio composition:** Changes within product types (+8.74 pp) dominated the product-mix effect (+0.30 pp).
- **Coverage contributions:** Property damage (+4.97 pp) and third-party liability (+4.36 pp) were the largest positive contributors.
- **Existing-book deterioration:** Among matched policies observed in both 2023 and 2024, the ratio increased by 13.80 pp, compared with 8.21 pp for the overall portfolio during the same period.

## Report features

The Power BI report includes:

1. **Executive diagnosis** — Portfolio-level premium, claim cost and ratio trends.
2. **Financial drivers** — Decomposition of the 9.04 pp deterioration into financial, product-type and coverage contributions.
3. **Existing-book dynamics** — Comparisons of matched policies and exposure-stable cohorts.
4. **Management priorities** — Evidence-based investigation priorities and an illustrative target-ratio scenario.
5. **Metric explorer** — Interactive metric selection and ratio comparisons.
6. **Coverage drillthrough** — Detailed examination of individual insurance coverages.
7. **About & Sources** — Methodological context, limitations, attribution and licensing.

## Download and open

**[Download the Power BI report (.pbix) from the latest GitHub Release](https://github.com/ZoltanMolnar2/motor-insurance-portfolio-analysis/releases/latest)**

Download `motor-insurance-portfolio-analysis.pbix` from the **Assets** section and open it in **Power BI Desktop**.

The saved Import-mode data model allows the report to be explored without separately downloading the original dataset. Refreshing the data may require reconnecting to the original source file.

## Scope and limitations

The analysis is descriptive. Its decompositions quantify how changes in the observed portfolio are distributed across components; they do not establish causality.

Matched-policy cohorts are selected subsets of the portfolio and should not be interpreted as representative of the entire book.

The target-ratio scenario is illustrative. It holds incurred claim costs constant and does not model customer responses, future claims development or expenses. It does not constitute a pricing recommendation.

## Data source and licensing

The report uses an adapted third-party dataset published on Mendeley Data:

Espinosa, Priscila; Lledó, Josep; Atance, David (2026). *A detailed dataset of motor insurance policies with coverage-specific financial information*. Mendeley Data, V1.

- **Dataset:** https://data.mendeley.com/datasets/sw4jmdb2sm/1
- **DOI:** https://doi.org/10.17632/sw4jmdb2sm.1
- **License:** Creative Commons Attribution 4.0 International (CC BY 4.0)
- **License terms:** https://creativecommons.org/licenses/by/4.0/

Premiums are reported in EUR in the source paper. Incurred claim costs are presented in EUR under the same-currency assumption.

## Copyright

Copyright © 2026 Zoltán Molnár. All rights reserved for the original analysis, dashboard design, visualizations and accompanying text.

The underlying third-party dataset remains subject to its original CC BY 4.0 license.
