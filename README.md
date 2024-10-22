# inventory-management-sql-project
inventory-management-sql-project
Inventory-Control-Management-SQL/
├── data/           # Store datasets here (e.g., Walmart dataset)
├── queries/        # Store SQL scripts and queries here
├── analysis/       # Store SQL analysis and results here
├── README.md       # Project description and details (will update this later)
# Inventory Control Management Database Project

This project aims to build an SQL-based inventory management system for Walmart sales data (2009-2014). The project analyzes various factors like weather, holidays, and macroeconomic parameters to understand their impact on sales.

## Dataset
The dataset used is the [Walmart Dataset](https://www.kaggle.com/datasets) from Kaggle, which includes:
- Sales Data (Year, Month, Product Category, Sales)
- Macroeconomic Parameters (GDP, CPI, Cotton Production, Unemployment Rate)
- Weather Data
- Holiday Data

## Project Questions
We aim to answer the following key questions:
1. Which year had the highest sales?
2. How was the weather during the year of highest sales?
3. Does weather have an essential impact on sales?
4. Do sales rise near the holiday season for all years?
5. Analyze the relationship between sales and macroeconomic variables.

## SQL Queries
- [Year with Highest Sales](queries/year-highest-sales.sql)
- [Weather Impact on Sales](queries/weather-impact.sql)
- [Holiday Season Sales](queries/holiday-season-sales.sql)
- [Macroeconomic Analysis](queries/macroeconomic-analysis.sql)

## Step-by-Step Analysis
1. **Year with Highest Sales**: Use SQL `GROUP BY` and `ORDER BY` to find the year with the highest sales.
2. **Weather Impact**: Join sales data with weather data to check correlations.
3. **Holiday Sales**: Analyze sales patterns near holidays.
4. **Macroeconomic Variables**: Use SQL to analyze the correlation between sales and variables like GDP and unemployment.

## Conclusion
Based on the analysis, we can infer if factors like weather, holidays, and macroeconomic parameters significantly impact sales.

git add .
git commit -m "Added SQL queries and project description"
git push origin main



