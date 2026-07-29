# Data Dictionary

| Field | Type | Definition |
| --- | --- | --- |
| ID | Integer | Unique listing identifier |
| Address | Text | Property street address |
| Type of Sale | Text | Realtor, By Owner, or Foreclosure listing category |
| Price | Integer | Archived listing price in U.S. dollars |
| Size (Sq Ft) | Integer | Property size in square feet |
| Baths | Decimal | Number of bathrooms |
| Beds | Integer | Number of bedrooms |
| Latitude | Decimal | Property latitude |
| Longitude | Decimal | Property longitude |

## Derived Tableau Fields

| Field | Definition |
| --- | --- |
| Price per Sq Ft | `Price / Size (Sq Ft)` |
| Bedroom Group | Bedroom counts 1–5 shown separately; 6 or more grouped as `6+` |
| Bathroom Group | Bathroom counts below 5 shown separately; 5 or more grouped as `5+` |

## Data Quality

- 336 rows and 9 source columns
- No missing values
- No exact duplicate rows
- 336 unique IDs and 336 unique addresses
- Listing-type distribution: 302 Realtor, 24 By Owner, and 10 Foreclosure

The original source URL, collection date, property condition, year built, lot
size, neighborhood label, and closed-sale price are unavailable.
