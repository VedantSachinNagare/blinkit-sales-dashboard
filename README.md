# Blinkit Sales Analytics Dashboard

Interactive Power BI dashboard analyzing sales performance, inventory mix and outlet performance for a grocery delivery business.

**Stack:** Power BI, DAX, Power Query, Excel





## Dataset

8,523 records | 1,559 unique products | 16 item categories | 10 outlets (`BlinkIT_Grocery_Data.xlsx`)

## Dashboard contents

- KPI cards: Total Sales, Average Sales, Number of Items, Average Rating (DAX measures)
- Sales by fat content, item type, outlet size, outlet location and outlet establishment year
- Fat content by outlet location, and an all-metrics table by outlet type
- Slicers for outlet location type, outlet size and item type

## Data preparation (Power Query)

- Standardized inconsistent `Item Fat Content` labels (`LF`, `low fat`, `reg`) into `Low Fat` and `Regular`, fixing 545 records (6.4% of data)
- Set column data types

## Key insights

- Total sales of 1.20M; Supermarket Type 1 outlets generate 65.5% of them
- Tier 3 outlets generate 472.1K vs 336.4K for Tier 1 (40% higher)
- Low Fat items contribute 64.6% of sales
- Medium-size outlets contribute 42.3% of sales
- The top 5 of 16 categories (Fruits and Vegetables, Snack Foods, Household, Frozen Foods, Dairy) account for 59% of sales
- The 2018 peak on the establishment chart reflects two outlets opened that year, not a sales surge

## Files

- `blinkit_dashboard.pbix` - the Power BI report
- `BlinkIT_Grocery_Data.xlsx` - source data
- `screenshots/` - dashboard images

## Acknowledgement

Project brief and chart requirements adapted from a public Data Tutorials walkthrough. KPI figures were validated against the raw data.
