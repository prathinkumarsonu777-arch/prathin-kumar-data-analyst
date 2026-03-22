# Coffee Shop Sales Analysis

## Project Objective

Analyze coffee shop sales data to identify best-selling products, peak sales hours, and store performance trends.

---

## Tools Used

Excel
SQL
Power BI

---

## Dataset

Coffee Shop Sales Dataset

---

## Data Cleaning (Excel)

Steps performed:

• Removed duplicate transactions
• Handled missing values
• Standardized date and time format
• Converted sales columns to numeric format
• Created new columns for hour-wise analysis

---

## SQL Analysis

Example Query:

SELECT hour, SUM(sales) AS total_sales
FROM coffee_sales
GROUP BY hour
ORDER BY total_sales DESC;

---

## Power BI Dashboard

Dashboard includes:

• Total Revenue KPI
• Total Orders KPI
• Hourly Sales Trend
• Top Selling Products
• Store Performance Comparison

---

## Key Insights

• Peak sales occur during morning hours
• Coffee beverages are the top-selling items
• Certain store locations outperform others significantly
