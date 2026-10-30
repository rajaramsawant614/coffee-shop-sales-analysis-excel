# Coffee Shop Sales Analysis | Excel

## About the project

I used Excel to explore six months of coffee shop transaction data, from January to June 2023. I wanted to understand when sales are strongest, which products and categories bring in the most revenue, and how the three store locations compare.

The analysis is built with Excel tables, PivotTables, PivotCharts, KPI calculations and slicers. The workbook includes the dashboard and supporting analysis.

## Business questions

- How did revenue change from month to month?
- Which store locations generated the most revenue?
- Which product categories and products contributed most to revenue?
- What were the busiest hours and strongest days?
- What could the business review to improve its sales operations?

## Files in this repository

| Folder / file | Description |
|---|---|
| `Dataset/Coffee_Shop_Sales.csv` | Original transaction data |
| `Excel_Project/Coffee_Shop_Sales_Analysis.xlsx` | Excel analysis and dashboard |
| `Business_Insights.md` | Findings and suggested actions |
| `README.md` | Project notes and methodology |

## Dataset

The dataset contains **149,116 transaction records** and 11 fields. It covers **1 January to 30 June 2023**.

Some of the main fields are:

- `transaction_id` — transaction identifier
- `transaction_date` and `transaction_time` — date and time of sale
- `transaction_qty` — number of units in the transaction
- `store_location` — store name
- `product_category`, `product_type` and `product_detail` — product information
- `unit_price` — selling price per unit

## What I did in Excel

1. Imported the CSV and formatted the data for analysis.
2. Checked for blank cells, duplicate rows and duplicate transaction IDs.
3. Created a revenue calculation using quantity multiplied by unit price.
4. Summarized sales by month, store, product category, product and time.
5. Built PivotTables and PivotCharts to compare the results.
6. Added KPI summaries and slicers to make the dashboard easier to explore.

## Key figures

| Measure | Result |
|---|---:|
| Revenue | **$698,812.33** |
| Units sold | **214,470** |
| Transactions | **149,116** |
| Average revenue per transaction | **$4.69** |
| Average units per transaction | **1.44** |

Revenue is calculated as `transaction_qty × unit_price`. Average revenue per transaction is total revenue divided by the number of unique transaction IDs.

## A few findings

- June had the highest revenue of the six months, at **$166,485.88**.
- Coffee was the largest category by revenue, followed by tea.
- Hell's Kitchen had the highest store revenue, although the three stores were fairly close.
- 10 AM was the highest-revenue hour.
- Monday had the highest revenue by day of week, while Friday had the most transactions.

More detail and the business implications are in [`Business_Insights.md`](Business_Insights.md).

## How to view the workbook

1. Open `Excel_Project/Coffee_Shop_Sales_Analysis.xlsx` in Microsoft Excel.
2. Select the `Dashboard` sheet.
3. Use the Month Name and Day Name slicers to explore the report.
4. Review the supporting PivotTables when you want to see how the summaries were produced.

If you edit or replace the source data, refresh the PivotTables before reviewing the dashboard.

## Limitations

The dataset includes selling prices and quantities, but it does not include product costs or operating expenses. For that reason, this project measures **revenue, not profit**. It also does not include customer IDs, discounts, refunds or inventory levels, so customer retention, promotion impact and stock-out analysis are outside the scope of this dataset.

The findings describe the six months provided. They should not be treated as proof of why sales changed or as a forecast.

## Tools used

- Microsoft Excel
- Excel Tables
- PivotTables and PivotCharts
- Excel formulas
- Slicers

