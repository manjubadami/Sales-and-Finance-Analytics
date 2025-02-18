# Atliq Sales Analysis and Reporting Project

This project uses PowerPivot and DAX to analyze Atliq's sales data, deliver insights, and answer key business questions. The interactive report, Sales_Report.xlsx, offers a comprehensive view of sales performance, trends, and product insights.

## Project Structure

*   **Data (Sales folder):**
    *   `dim_customer.csv`: Customer information (e.g., customer ID, demographics).
    *   `dim_market.csv`: Market or region details (e.g., market ID, region).
    *   `dim_product.csv`: Product details (e.g., product ID, category, subcategory).
    *   `fact_sales_monthly.csv`: Monthly sales data (e.g., product ID, customer ID, market ID, sales quantity, net sales).
    *   `fact_sales_monthly_with_cost.csv`: Monthly sales data including cost information (e.g., cost per unit).
    *   `ns_targets_2021.csv`: Net sales targets for 2021.

*   **Analysis and Reporting:**
    *   `Sales_Report.xlsx`: The PowerPivot-based Excel workbook containing the interactive report with visualizations and DAX measures.
    *   `tree.txt`: A text file displaying the project's directory structure.

## Key Insights and Reports

The `Sales_Report.xlsx` provides answers to these crucial business questions:

*   **Top 10 Products by Net Sales Growth (2020-2021):** Identify the products with the highest percentage increase in net sales.
*   **Division Report:** View net sales for each division in 2020 and 2021, along with growth percentages.
*   **Top 5 and Bottom 5 Products by Quantity Sold:** See the best and worst-performing products by quantity.
*   **New Products in 2021:** Discover products launched in 2021 (with 0% YoY growth).
*   **Top 5 Countries by Net Sales (2021):** Uncover the most significant markets by net sales.

## Getting Started

1.  **Prerequisites:**
    *   Microsoft Excel with PowerPivot enabled.
    *   Basic understanding of DAX.

2.  **Setup:**
    *   Clone this repository.
    *   Open `Sales_Report.xlsx` in Excel.
    *   Refresh the PowerPivot data connections to load the data from the CSV files in the `Sales` folder.

## Technical and Soft Skills

[x] ETL Proficiency: Demonstrated proficiency in ETL (Extract, Transform, Load) methodology
[x] Power Query Expertise: Utilized Power Query to generate dynamic data tables by connecting to various data sources
[x] Fiscal Date Handling: Skill in deriving fiscal months and quarters
[x] Power Pivot Data Modeling: Successfully defined and maintained relationships between tables within Power Pivot based on primary and foreign keys
[x] Data Model Expansion: Seamlessly integrated supplementary data from external sources into existing data models
[x] DAX Calculated Columns: Utilized DAX to create calculated columns


