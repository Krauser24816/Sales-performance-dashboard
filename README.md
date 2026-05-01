# 📊 Superstore Sales Dashboard — Power BI Project

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Dashboard](https://img.shields.io/badge/Type-Sales%20Dashboard-blue?style=for-the-badge)

## 📌 Project Overview

This project is a beginner-friendly but insight-focused **Power BI sales dashboard** built using the Superstore dataset. The dashboard analyzes sales, profit, discount impact, customer behavior, product performance, geographic performance, shipping efficiency, order behavior, and business risk areas.

The goal of this project is to understand business performance using interactive visuals, filters, drill-downs, cards, treemaps, maps, scatter plots, bar charts, and line charts — without relying on advanced DAX or Power Query transformations.

---

## 🎯 Project Objectives

- Analyze total sales and profit performance.
- Identify the categories and sub-categories driving sales and profit.
- Understand the effect of discounts on profitability.
- Compare performance across markets, regions, states, and cities.
- Analyze customer segments and top customers by sales.
- Explore product-level and sub-category performance.
- Study sales and profit trends over time.
- Evaluate shipping mode usage and shipping cost behavior.
- Detect risk areas such as high discount with low profit and high sales with low profit.
- Create an interactive filtering page for region, segment, category, and year analysis.

---

## 🗂️ Folder Structure

```text
data/
├── raw/
│   └── superstore.csv
├── cleaned/
│   └── Cleaned data.pbix

powerbi/
└── Working_file.pbix

Screenshots/
├── Customer Insights.png
├── Discount Impact.png
├── Geographic Performance.png
├── Market-level Comparison.png
├── Order Behaviour.png
├── Product Performance.png
├── Risk and Problem Areas.png
├── Sales and Profit Performance.png
├── Sales Filtering.png
├── Shipping and Operational Efficiency.png
└── Time-based Trends.png

Project document.docx
README.md
```

---

## 📂 Dataset

The dataset contains Superstore order information, including:

- Sales and profit values
- Product categories and sub-categories
- Customer segments and customer names
- Market, region, state, and city information
- Discount and quantity values
- Shipping mode and shipping cost
- Order date, ship date, year, and order priority

---

## 🧹 Data Cleaning & Preparation

Basic dashboard-ready cleaning was performed before visualization:

- Removed an unclear column containing Chinese text.
- Removed unnecessary row identifier column.
- Converted `Order.Date` from Date/Time format to Date format.
- Converted `Ship.Date` from Date/Time format to Date format.
- Adjusted summarization behavior for columns such as `Discount` and `Year` where needed.
- Prepared a cleaned Power BI file for dashboard development.

---

## ❓ Business Questions Answered

### 1. Sales & Profit Performance
- What is the total sales vs total profit?
- Which categories and sub-categories drive the most sales?
- Which categories generate the highest vs lowest profit?

### 2. Discount Impact
- How does discount affect sales and profit?
- Which categories or sub-categories have high discounts but low profit?

### 3. Geographic Performance
- Which regions and markets generate the most sales?
- Which states/cities are top performers?
- Are there regions with high sales but low profit?

### 4. Customer Insights
- Which customer segments contribute the most sales?
- Who are the top customers by sales?
- Do certain segments prefer specific categories?

### 5. Product Performance
- Which products are top-selling?
- Which sub-categories have low profit despite high sales?
- What is the distribution of quantity sold across categories?

### 6. Time-Based Trends
- How do sales and profit change over time?
- Which months have peak sales?
- Is there a trend across years?

### 7. Shipping & Operational Efficiency
- Which shipping mode is most used?
- Which shipping mode has the highest cost?
- Does shipping cost vary by region or market?

### 8. Order Behaviour
- What is the average quantity per order?
- Which orders have high quantity but low profit?
- Does order priority affect sales or shipping mode?

### 9. Market-Level Comparison
- Which markets perform best in sales and profit?
- How do different markets compare across categories?

### 10. Risk & Problem Areas
- Which sub-categories or regions show consistent low profit?
- Are there cases of high discount with low profit?
- Are there cases of high sales with low profit?

### 11. Interactive Filtering
- What happens to sales when filtering by region?
- What happens to sales when filtering by segment?
- What happens to sales when filtering by category?
- What happens to sales when filtering by year?

---

## 📊 Dashboard Pages

### 1. Sales and Profit Performance

This dashboard page summarizes overall sales and profit performance. It includes KPI-style cards for total sales and total profit, a category-level sales comparison, and a profit treemap by category.

<img src="./screenshots/Sales%20and%20Profit%20Performance.png" width="900">

---

### 2. Discount Impact

This page analyzes how discounts affect sales and profitability. It compares profit and sales with and without discount and highlights sub-categories where discounting leads to reduced or negative profit.

<img src="./screenshots/Discount%20Impact.png" width="900">

---

### 3. Geographic Performance

This dashboard explores sales performance across markets, regions, states, and cities. It includes market-level sales, regional sales/profit comparison, and a map visualization for geographic distribution.

<img src="./screenshots/Geographic%20Performance.png" width="900">

---

### 4. Market-Level Comparison

This page compares sales and profit performance across different markets. It also breaks down profit by market and category to identify strong and weak market-category combinations.

<img src="./screenshots/Market-level%20Comparison.png" width="900">

---

### 5. Customer Insights

This dashboard focuses on customer behavior. It shows sales contribution by customer segment, top customers by sales, and category preference across segments.

<img src="./screenshots/Customer%20Insights.png" width="900">

---

### 6. Product Performance

This page identifies top-selling products, compares sales and profit by sub-category, and shows the distribution of quantity sold across main product categories.

<img src="./screenshots/Product%20Performance.png" width="900">

---

### 7. Time-Based Trends

This dashboard analyzes sales and profit trends over time using yearly and monthly views. It helps identify sales growth patterns and peak months.

<img src="./screenshots/Time-based%20Trends.png" width="900">

---

### 8. Shipping & Operational Efficiency

This page evaluates shipping mode usage and shipping cost distribution by ship mode, region, and market.

<img src="./screenshots/Shipping%20and%20Operational%20Efficiency.png" width="900">

---

### 9. Order Behaviour

This dashboard studies order patterns using average quantity, sales by order priority and shipping mode, and a scatter plot to identify orders with high quantity but low profit.

<img src="./screenshots/Order%20Behaviour.png" width="900">

---

### 10. Risk & Problem Areas

This page highlights low-profit sub-categories and problematic orders. It includes analysis of high discount with low profit and high sales with low profit.

<img src="./screenshots/Risk%20and%20Problem%20Areas.png" width="900">

---

### 11. Sales Filtering

This interactive page allows users to filter sales by region, category, segment, and year. The result card updates dynamically based on selected filters.

<img src="./screenshots/Sales%20Filtering.png" width="900">

---

## 🔍 Key Insights

- Total sales are much higher than total profit, showing the importance of analyzing profitability rather than revenue alone.
- Technology generated the highest profit among the main categories, while Furniture showed weaker profitability.
- Discounted orders produced a negative profit overall, showing that discounting can strongly reduce profitability.
- APAC was one of the strongest markets in sales and profit performance.
- Consumer customers contributed the highest sales among customer segments.
- Standard Class was the most frequently used shipping mode.
- Some orders showed high sales or high quantity but low profit, highlighting potential pricing or cost-efficiency issues.
- Interactive slicers make it easier to explore sales changes by region, category, segment, and year.

---

## 🛠️ Tools & Features Used

- **Power BI Desktop**
- Card visuals
- Bar and column charts
- Treemap visuals
- Map visualization
- Scatter plots
- Line charts
- Donut chart
- Matrix/table visuals
- Drill-down and drill-through interactions
- Slicers and interactive filtering
- Visual-level and page-level filtering
- Basic data type cleaning inside Power BI

---

## 🚀 How to Use This Project

1. Clone or download this repository.
2. Open `powerbi/Working_file.pbix` in Power BI Desktop.
3. Explore the dashboard pages.
4. Use slicers and filters to interact with the data.
5. Refer to `Project document.docx` for project questions and development progress.

---

## 📄 Project Documentation

The project document contains the full list of business questions and a day-by-day progress log from data understanding and cleaning to dashboard completion.

```text
Project document.docx
```

---

## ✅ Project Status

**Completed**

This project was completed as a basic introduction to Power BI dashboard development, focusing on clean visuals, business questions, and interactive analysis.

---

## ✨ Author

Created by **Himanshu Midha**

