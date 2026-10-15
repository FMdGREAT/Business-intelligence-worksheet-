### BUSINESS INTELLIGENCE WORKSHEET 

##### POWER OVERVIEW 


My first Power BI project. It's a sales dashboard for a Nigerian electronics and IT retail business, built from an Excel dataset.

## What's in it
- **Data:** 8 tables (sales, customers, products, employees, expenses, inventory, targets, dates) covering 2024 to 2026
- **Model:** star schema with fact and dimension tables linked by ID columns
- **Cleaning:** done in Power Query (data types, trimming, text formatting)
- **Measures (DAX):** Total Customers, Total Orders, Total Quantity, Total Net Sales, Sales Variance, Sales Achievement
- **Report:** KPI cards, sales by region, orders by product, monthly net sales trend, city slicer

## What I found when I checked my work
- Sales table has 250 duplicate rows
- Cancelled and returned orders were counted as sales
- Sales target was hardcoded instead of coming from the targets table
- Sales table wasn't linked to the date table, so the monthly chart was wrong

## Next steps
- Fix the issues above
- Add Target vs Actual, Expenses and Inventory pages
- Add Year and Region slicers

## Tools
- Power BI,
- Power Query, 
- DAX, 
- Excel

## Problem Statement
IFEXA, a Nigerian electronics and IT retailer, keeps its sales, customer, product, expense, inventory and target data in separate Excel sheets. This makes it hard for management to see how the business is performing.

This project combines the data into one Power BI model and dashboard to answer:
- How much are we selling, and to how many customers?
- Which regions and products perform best?
- How do sales change month to month?
- Are we meeting our sales target?

 ## DATASETS
  Dataset includes the following :

- Sales 
- State
- country 
- customer
- Net Sales 
- category
- Cost 

### for practical class/ session 
**Author:** Egunlusi Oluwafemi 
