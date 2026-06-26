# 🛒 Superstore Sales Dashboard

An interactive Power BI dashboard built on the Superstore dataset, providing end-to-end visibility into sales performance, regional trends, and profitability across customer segments, product categories, and shipping modes.

---

## 📊 Dashboard Overview

The report is split into two pages:

### Page 1 — Sales & Profit Overview
- **KPI Cards**: Total Sales (1.10M), Total Revenue (942.67K), Total Profit (132.52K), Profit Margin (12.05%), Total Orders (5,009), Total Quantity (19K)
- **Sales by Customer Segment**: Donut chart breaking down Consumer (51%), Corporate (31%), and Home Office (18%) segments
- **Sales by Category**: Donut chart across Furniture (34%), Office Supplies (31%), and Technology (35%)
- **Sales by Ship Mode**: Bar chart comparing Standard Class, Second Class, First Class, and Same Day
- **Discount vs. Profit Scatter**: Visual correlation between discount rates and profit margins
- **Sales by Month and Year**: Area/line chart tracking seasonal trends
- **Sales by Quarter and Category**: Stacked bar chart highlighting Q4 as the peak quarter
- **Sales by State**: Filled US map showing geographic distribution

### Page 2 — Product & Regional Performance
- **Sales Trend Over Time**: Waterfall chart showing year-over-year growth from 2014 to 2017
- **Total Sales by Year and Category**: Small multiples line charts for Furniture, Office Supplies, and Technology
- **Sales by Sub-Category**: Horizontal bar chart — Chairs and Phones lead at ~167K and ~162K
- **Sales by Region**: Dot plot comparing Central, East, South, and West
- **Top 10 Cities by Sales**: Ranked table led by Wilmington
- **Top 10 Products by Sales**: Ranked product list
- **Month-over-Month Sales Growth**: Line chart across years
- **Sales by Region and Profit**: Map with regional profit segmentation

---

## 🔧 Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard development & visualizations |
| **DAX** | Calculated measures (Profit Margin %, MoM Growth, etc.) |
| **Power Query** | Data transformation & cleaning |
| **Superstore Dataset** | Source data (orders, returns, customers) |

---

## 🎛️ Filters & Slicers

- **Year Slicer**: 2014, 2015, 2016, 2017
- **Region Slicer**: Central, East, South, West
- **Segment Slicer**: Consumer, Corporate, Home Office
- **Category Slicer**: Furniture, Office Supplies, Technology

---

## 📁 Project Structure

```
superstore-sales-dashboard/
│
├── SuperstoreDashboard.pbix      # Power BI report file
├── data/
│   └── superstore.csv            # Source dataset
├── screenshots/
│   ├── page1_sales_profit.png
│   └── page2_product_regional.png
└── README.md
```

---

## 🚀 Getting Started

1. Clone this repository
2. Open `SuperstoreDashboard.pbix` in Power BI Desktop
3. If prompted, update the data source path to point to `data/superstore.csv`
4. Refresh the data and explore!

---

## 💡 Key Insights

- **Technology** drives the highest sales but discounting significantly erodes margins
- **Q4** is consistently the strongest quarter across all categories
- **Consumer segment** accounts for over half of all revenue
- **West and East** regions outperform Central and South in total sales
- Heavy discounting (>0.4) is strongly correlated with negative profit

---



**Product & Regional Performance**

![Product & Regional Performance](screenshots/page2_product_regional.png)
