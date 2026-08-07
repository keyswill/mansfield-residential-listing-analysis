# Phase 2: Business Understanding

**Status: Complete**

## Business Context

Home buyers and agents need practical price benchmarks, but listing-price distributions can be distorted by a small number of luxury properties. Property size, configuration, listing type, and location should be reviewed together with sample-size and source limitations.

## Main Business Question

> How can buyers and agents benchmark archived Mansfield listings by price, size, configuration, listing type, and location without overstating what the data proves?

## Business Problem

Simple averages and broad claims about neighborhoods or listing types can mislead users. The dashboard must use outlier-aware KPIs, expose small comparison groups, and distinguish listing prices from confirmed sale values.

## Stakeholders

| Stakeholder | Decision supported |
|---|---|
| Prospective buyer | Compare an archived listing with similar property characteristics |
| Real estate agent | Review price and price-per-square-foot benchmarks |
| Market analyst | Explore relationships and identify data needed for stronger valuation work |

## Business Objectives

1. Benchmark listing price and price per square foot using medians.
2. Compare price with square footage, bedrooms, and bathrooms.
3. Evaluate listing-type differences with sample-size context.
4. Display geographic patterns without claiming neighborhood effects.
5. Define the additional data required for valuation or investment analysis.

## Success Metrics

| Metric | Definition | Decision supported |
|---|---|---|
| Median listing price | Middle listing price | Outlier-resistant market benchmark |
| Median price per square foot | Middle price-per-square-foot value | Standardized property comparison |
| Median property size | Middle square footage | Typical size context |
| Correlation with listing price | Pearson and Spearman relationships | Compare visible property characteristics |
| Listing-type sample count | Records in each type | Judge comparison reliability |

## Assumptions and Limitations

- Records represent archived listings, not confirmed sales.
- The original Kaggle URL and collection date are unavailable.
- Listing-type groups are highly unequal.
- Property condition, repair cost, year built, lot size, neighborhood, and time on market are unavailable.
- Relationships are descriptive and do not establish causal price effects or investment returns.

## Main Limitation

> The dashboard supports descriptive listing benchmarks, not appraisal, valuation, or investment-return decisions.

## Related Documentation

- [Business requirements](business-requirements.md)
- [Validated analysis](validated-analysis.md)
- [Phase 3 Data Understanding](03_data_understanding.md)

