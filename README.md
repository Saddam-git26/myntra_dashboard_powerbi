#  Myntra Sales Dashboard (Power BI)

An interactive Power BI dashboard that shows how Myntra products perform in terms of sales, revenue, discounts, brands and customer locations.

## Project Overview
This project helps to understand:
- How much sales and revenue the business is making
- Which brands and categories sell the most
- How discounts affect sales
- Which states and cities give the most orders

## Data Model
The data is arranged in a star schema with 5 tables:

| Table | What it contains |
|-------|------------------|
| fact_orders | Order details and sales amount |
| dim_products | Product name, brand, category, sub-category |
| dim_customers | Customer city and state |
| Date_table | Year, quarter, month, day of week |
| Measures_Table | All calculated measures (KPIs) |

## Key Measures (KPI Cards)
- Total Orders
- Total Sales Amount
- Average Sales Amount
- Total Revenue
- Average Discount
- Product Count

## Dashboard Pages
| Page | What it shows |
|------|---------------|
| Main | Complete dashboard with all KPIs, charts, map and slicers |
| Cards | KPI cards only |
| Charts | Sales by state, brand distribution, revenue by brand, product by category |
| Adv Charts | Sales vs discount (combo chart), year-wise category ribbon chart, sales by day of week (area chart) |
| Filters | Slicers for Brand, Category, Sub-Category and Year |
| Maps | City-wise orders on a map |
| Table Matrix | Brand-wise orders, discount and sales in a table |

##  Visuals Used
Cards, Column chart, Bar chart, Donut chart, Combo (line + column) chart, Ribbon chart, Area chart, Map, Table, Slicers

##  Tools Used
- Power BI Desktop
- DAX (for measures)
- Star schema data modelling

##  How to Open
1. Download the `.pbix` file from this repository.
2. Open it in **Power BI Desktop**.
3. Use the slicers to filter by Year, Brand, Category and Sub-Category.

##  Auther
|Saddam Pathan | pathansaddam651@gmail.com |Linked IN: 
