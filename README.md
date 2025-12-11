# Mobile-sales-dashboard
Interactive Power BI Mobile Sales Dashboard — Brand &amp; Model analysis, Monthly trends

## Features
- Total Sales, Total Orders, Average Selling Price (KPIs)
- Brand-wise and Model-wise sales comparison
- Monthly sales trend (MoM)
- Channel split: Online vs Offline
- City-wise sales map and top selling models
- Filters: Brand, City, Channel, Date range

## Files
- `Mobile_sales_dashboard.pbix` — Power BI report (open with Power BI Desktop)
- `dataset.xlsx` — Sample transactional dataset
- `screenshots/` — Dashboard images for README
- `docs/` — Additional notes and explanation (optional)

## How to run
1. Download `Mobile_sales_dashboard.pbix`.
2. Open with Power BI Desktop.
3. Use slicers on the right to explore brand, city and date filters.

## DAX (example measures)
```dax
Total Sales = SUM(Sales[Total])
Total Quantity = SUM(Sales[Qty])
Average Selling Price = DIVIDE([Total Sales], [Total Quantity])
Total Orders = DISTINCTCOUNT(Sales[Invoice No])



## Tools Used
    Power BI
    MS Excel
    DAX
    Data Modeling

## How to Use
    Download the .pbix file
    Open it in Power BI Desktop
    Explore interactive visuals and filters

## Author
    Priyanshu Kumar
