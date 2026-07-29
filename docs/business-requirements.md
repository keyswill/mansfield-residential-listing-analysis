# Business Requirements

## Objective

Create a Tableau dashboard that helps users benchmark archived Mansfield
residential listings by price, size, property configuration, listing type, and
location.

## Intended Users

- Prospective buyers comparing listing characteristics
- Real estate agents reviewing price benchmarks
- Analysts exploring residential listing patterns

## User Stories

1. As a user, I want to compare listing price with property size so I can
   identify the strongest visible pricing relationship.
2. As a user, I want median prices by bedroom and bathroom group so luxury
   outliers do not dominate the comparison.
3. As a user, I want price-per-square-foot comparisons by listing type with
   visible sample context.
4. As a user, I want to filter by price, size, beds, baths, and listing type.
5. As a user, I want to view listing locations without treating visual clusters
   as measured neighborhood effects.

## Functional Requirements

- Display total listings, median listing price, median price per square foot,
  and median property size.
- Show one mark per listing in the size-price scatterplot and map.
- Group bedrooms at 6+ and bathrooms at 5+.
- Use medians for category comparisons.
- Apply dashboard filters across all worksheets using the same data source.
- Display an analytical limitation for listing-type comparisons.

## Acceptance Criteria

- Headline KPIs reconcile to 336 listings, $300,000 median price, $104.93 median
  price per square foot, and 2,801 median square feet.
- The scatterplot and map each represent all 336 listings when unfiltered.
- Listing-type counts reconcile to 302 Realtor, 24 By Owner, and 10 Foreclosure.
- Dashboard language consistently uses “listing price,” not “sale price.”
- The public documentation identifies the data as archived and discloses that
  the original source URL is unavailable.
