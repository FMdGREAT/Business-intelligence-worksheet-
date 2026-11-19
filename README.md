# IFEXA Business Intelligence Dashboard

A 4-page Power BI dashboard for IFEXA, a Nigerian electronics and IT retailer, built from an Excel dataset covering 2024 to 2026.

## Problem
IFEXA keeps its sales, customer, product, expense, inventory and target data in separate Excel sheets, so management can't easily see how the business is performing. This project combines everything into one Power BI model and answers:
- How much are we selling, and to how many customers?
- Which regions, categories and products perform best?
- How do sales change month to month?
- How profitable is the business after expenses?

## Dashboard Preview

### 1. Sales Analysis (Executive View)
![Sales Analysis](Screenshot_2026-11-19_085655.png)

### 2. Sales Dashboard
![Sales Dashboard](Screenshot_2026-11-19_085716.png)

### 3. Customer Dashboard
![Customer Dashboard](Screenshot_2026-11-19_085726.png)

### 4. Profitability Dashboard
![Profitability Dashboard](Screenshot_2026-11-19_085740.png)

## Key numbers
- Total Sales: 191.64bn across 30K orders and 224K units
- Average Order Value: 6.44M
- Top category: Computers (49bn); top brand: Samsung (25bn)
- Sales are evenly spread across 2024, 2025 and 2026 (about 63 to 65bn each)

## What's inside
- **Data:** 8 tables (sales, customers, products, employees, expenses, inventory, targets, dates)
- **Model:** star schema with fact and dimension tables linked by ID columns
- **Cleaning:** Power Query (data types, trimming, text formatting)
- **Measures (DAX):** Total Sales, Total Orders, Total Quantity, Average Order Value, Gross Profit Margin, Sales per Customer, Approved Expenses and more
- **Pages:** Sales Analysis, Sales, Customer and Profitability

## Data quality checks
- 250 duplicate rows found in the sales table
- Cancelled and returned orders were being counted as sales
- Sales target was hardcoded instead of coming from the targets table
- Sales table wasn't linked to the date table

## Next steps
- Fix the issues above and re-check the totals
- Correct the margin measures and sort months January to December
- Standardise text casing (e.g. Online / online)
- Add a Target vs Actual page

## Tools
Power BI · Power Query · DAX · Excel

## Files
- `github file.pbix`: the Power BI report (open with Power BI Desktop)
- `Power BI/`: dataset and project notes

**Author:** Egunlusi Oluwafemi
