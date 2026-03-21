# Global Superstore Sales Analysis

## Project Objective

Analyze sales data to identify top performing regions, profitable product categories, and sales trends.

---

## Tools Used

Excel
SQL
Power BI

---

## Data Cleaning (Excel)

Steps performed:

• Removed duplicate rows
• Checked for missing values
• Standardized date format
• Created calculated columns for analysis

---

## SQL Analysis

Example Query:

SELECT region, SUM(sales) AS total_sales
FROM superstore_sales
GROUP BY region
ORDER BY total_sales DESC;

---

## Power BI Dashboard

Dashboard includes:

• Total Sales KPI
• Total Profit KPI
• Sales by Region
• Monthly Sales Trend
• Top 10 Products

---

## Key Insights

• West region generated highest revenue
• Technology category produced highest profit
• Sales increased during the holiday season
