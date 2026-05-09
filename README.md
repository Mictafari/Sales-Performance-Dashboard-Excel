# Sales-Performance-Dashboard-Excel
This interactive Excel dashboard helps business owners and sales managers track key sales metrics, identify top‑performing products, and analyse regional performance over time. The dashboard updates automatically when new sales data is added.
## Problem Solved

Raw sales data in a table is hard to read. Decision makers need:
- A clear view of total sales, number of orders, and average sale value.
- The ability to filter by region and product without touching formulas.
- Visual trends (by month, product, region) that update instantly.

## Solution

A single Excel workbook containing:
- A structured **Excel Table** (`SalesData`) with 100+ rows of order information.
- **PivotTables** summarising sales by month, product, and region.
- **PivotCharts** (line, bar, column) placed on a dedicated Dashboard sheet.
- **Slicers** for Region and Product that control all charts simultaneously.
- **KPIs** (Total Sales, Total Orders, Average Sale, Top Product) using `SUM`, `COUNTA`, `AVERAGE`, and `INDEX/MATCH` directly on the table – they update instantly when data changes.

## Tools & Techniques

| Feature | How it's used |
|---------|----------------|
| Excel Table | Dynamic range: `=SUM(SalesData[Sales])` works across sheets |
| PivotTables | Summarise sales by month, product, region |
| PivotCharts | Line chart (monthly trend), bar chart (product sales), column chart (regional sales) |
| Slicers | Connected to all PivotTables – filter by Region and Product |
| Formulas | `SUM`, `COUNTA`, `AVERAGE`, `INDEX/MATCH` for KPIs |

## Files in this Repository

| File | Description |
|------|-------------|
| `Sales_Dashboard.xlsx` | The final Excel dashboard |
| `screenshot-dashboard.png` | Full dashboard view |
| `README.md` | This file |

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/9dee6186-798a-41aa-9c59-457f5e17d23b" />



## License

This project is for portfolio and educational purposes.
