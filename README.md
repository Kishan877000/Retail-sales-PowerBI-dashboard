<p align="center">
  <img src="dashboard_preview.png" alt="Retail Sales Dashboard by Kishan Shetty" width="800"/>
</p>

<h1 align="center">Retail Sales Dashboard (Power BI) - by Kishan Shetty</h1>




# Retail Sales Analytics Dashboard — Power BI
**Author:** Kishan Shetty

## Project Overview
An interactive Power BI dashboard analyzing retail sales (India, 2023–2024).  
This project demonstrates end-to-end analytics: data modeling (star schema), Power Query cleaning, DAX measures (sales, profit, margin), and interactive visuals (KPIs, trend analysis, category/product breakdown).

## Files
- `Retail_Sales_Analysis.pbix` — Power BI workbook (working file)  
- `data/` — CSV files: Sales_Fact.csv, Product_Dimension.csv, Customer_Dimension.csv, Date_Dimension.csv  
- `dashboard_preview.png` — static preview image  
- `README.md` — this document

## Key Features
- Star-schema data model (Sales fact + Product, Customer, Date dimension)  
- Core DAX measures: Total Sales, Total Profit, Profit Margin, Average Order Value  
- Interactive filters: Year, Region, Category  
- Visuals: KPI cards, sales trend, sales by category, top products, profit margin breakdown, discount vs profit analysis

## How to run
1. Download PBIX and CSV files.  
2. Open Power BI Desktop and load the .pbix file. If data paths are relative, use `Transform Data` → `Data source settings` to update data source locations to the `/data` CSV files.

## Key Insights (examples)
- Electronics is the largest category by revenue.  
- Profit margin varies by category (e.g., Electronics higher margin than Grocery).  
- Top products drive most revenue — Laptop & Smartphone top the list.

## Contact
**Kishan Shetty** — linkedin.com/in/kishan-shetty — github.com/YourGitHubUsername

