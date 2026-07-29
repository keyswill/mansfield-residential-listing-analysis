# Validated Analysis

This document reconciles the project claims to `Real Estate Listings.xlsx`.

## Dataset Profile

| Metric | Value |
| --- | ---: |
| Rows | 336 |
| Missing values | 0 |
| Exact duplicate rows | 0 |
| Realtor listings | 302 |
| By Owner listings | 24 |
| Foreclosure listings | 10 |

## Headline Metrics

| Metric | Mean | Median |
| --- | ---: | ---: |
| Listing price | $399,140.38 | $300,000.00 |
| Price per square foot | $125.27 | $104.93 |
| Property size | 2,979.24 sq ft | 2,800.50 sq ft |

## Relationships With Listing Price

| Characteristic | Pearson Correlation | Spearman Correlation |
| --- | ---: | ---: |
| Size (Sq Ft) | 0.656 | 0.802 |
| Beds | 0.500 | 0.523 |
| Baths | 0.438 | 0.665 |

Square footage has the strongest linear and rank-order relationship with listing
price among these three available characteristics. This does not establish a
causal price effect.

## Listing Type

| Type | Listings | Median Price | Median Price per Sq Ft |
| --- | ---: | ---: | ---: |
| By Owner | 24 | $403,988 | $177.96 |
| Realtor | 302 | $299,900 | $104.05 |
| Foreclosure | 10 | $204,950 | $81.16 |

The foreclosure median price per square foot is approximately 22% below the
Realtor median. This is a descriptive sample comparison, not an investment
return estimate.

## Small-Group Context

| Group | Listings |
| --- | ---: |
| 6+ bedrooms | 7 |
| 5+ bathrooms | 4 |

The luxury groups contain too few listings to support broad market
generalization.

## Claim Corrections

| Previous Framing | Defensible Revision |
| --- | --- |
| Property size is the primary driver of price | Square footage has the strongest observed relationship with listing price among the available characteristics |
| Foreclosures are the strongest value opportunity | Foreclosures have a lower median price per square foot in this small sample; condition and repair costs are unavailable |
| The dashboard analyzes sale prices | The dashboard analyzes archived listing prices |
| The map identifies premium neighborhoods | The map displays listing locations and geographic variation without measuring neighborhood effects |
| Foreclosures provide 34% more square footage per dollar | Foreclosure median price per square foot is approximately 22% below the Realtor median |
