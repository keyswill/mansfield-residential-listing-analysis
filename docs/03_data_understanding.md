# Phase 3: Data Understanding

**Status: Complete**

## Dataset Grain

> One row represents one archived residential listing in Mansfield, Texas.

The dataset contains 336 listings with no missing values or exact duplicate rows.

## Key Fields and Business Use

| Field group | Business use | Interpretation limit |
|---|---|---|
| Listing price | Price benchmarks and distributions | Asking price, not closed-sale price |
| Square footage | Size comparison and price relationship | Does not capture condition or lot size |
| Bedrooms and bathrooms | Configuration comparison | Luxury groups have small samples |
| Listing type | Realtor, By Owner, and Foreclosure comparison | Groups are highly unequal |
| Address/location | Map archived listings | Does not define or measure neighborhoods |
| Price per square foot | Standardized price comparison | Still affected by unobserved property quality |

## Validated Baseline

| Metric | Value |
|---|---:|
| Listings | 336 |
| Median listing price | $300,000 |
| Median price per square foot | $104.93 |
| Median property size | 2,800.5 sq ft |
| Missing values | 0 |
| Exact duplicates | 0 |

## Distribution and Sample Context

- Mean listing price is $399,140, materially above the $300,000 median.
- Mean price per square foot is $125.27, above the $104.93 median.
- The 6+ bedroom group has seven listings; the 5+ bathroom group has four.
- Listing types include 302 Realtor, 24 By Owner, and 10 Foreclosure records.

These patterns justify using medians and disclosing sample sizes.

## Connection to Business Questions

| Business question | Required fields | Measure | Interpretation limit |
|---|---|---|---|
| How does size relate to price? | Square footage, listing price | Scatterplot and correlations | Relationship is not causal |
| How do configurations differ? | Bedrooms, bathrooms, price | Group medians and counts | Luxury groups are small |
| How do listing types compare? | Listing type, price per square foot | Median and sample count | Condition and repair cost unavailable |
| Where are listings located? | Address/location | Map | No neighborhood-effect measure |

## Analytical Readiness

The data supports descriptive benchmarking, distribution analysis, property-characteristic comparisons, and mapping. It is not sufficient for appraisal, causal pricing models, neighborhood premiums, or investment-return estimates.

## Related Documentation

- [Data dictionary](../data/data-dictionary.md)
- [Validated analysis](validated-analysis.md)
- [Phase 2 Business Understanding](02_business_understanding.md)

