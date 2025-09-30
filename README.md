# Sales Trend Analysis (Task 6)

## Objective
Analyze monthly revenue and monthly order volume from the `online_sales` table.

## Tools used
- Google Colab (Python, pandas, sqlite3)
- SQLite (online_sales.db)
- Output file: sales_trend.csv

## How to run
1. Open `Task6_Sales_Analysis.ipynb` in Google Colab.
2. Run cells from top to bottom (Shift+Enter).
3. Outputs will be in `sales_trend.csv`. The DB file `online_sales.db` contains the source table.

## SQL queries used
- `SUM(amount)` for monthly revenue
- `COUNT(DISTINCT order_id)` for order volume
- `strftime('%Y-%m', order_date)` to group by year-month (SQLite)
