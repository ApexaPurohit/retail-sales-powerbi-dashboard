# Retail Sales Performance Dashboard (Power BI)

## 📊 Overview
An interactive 2-page Power BI dashboard analyzing retail order data — ₹4.66M in sales across 405 orders and 61 customers. Built to answer real business questions using KPI cards, trend analysis, category/region breakdowns, and a discount-efficiency check.

## 🎯 Business Questions
- Which categories and regions bring in the most revenue?
- Is demand steady through the year, or volatile?
- Which customers matter most to the business?
- Is discounting actually driving sales, or just eating margin?

## 🗂 Data Model
Single **Orders** table (connected to a **Customers** table on CustomerID) with fields:
OrderDate, Region, City, Category, Product Name, Customer Name, Quantity, Revenue, Discount

## 📈 Dashboard Pages
**Page 1 — Sales Overview:** KPI cards (Total Sales, Orders, Quantity, Customers), Sales Trend, Sales by Category, Top 10 Customers by Sales, Sales by Region

**Page 2 — Product Analysis:** Category Performance by Region, Sales by City (map), Product Performance table, Discount by Category

## 🔑 Key Insights
- Home & Kitchen and Electronics lead on revenue — but Home & Kitchen wins **without** heavy discounting
- Books gets the highest discount share (18.23%) yet ranks near the bottom in sales — a wasted-spend signal
- Orders (405) ≈ Quantity (404) → this is a single-item-per-order business
- Action Figure earns the most revenue (₹1,11,960) from just 26 units, while Board Game sells the most units (59) but earns the least — volume ≠ value
- Regional split is balanced (23.9%–26.5%) but city-level data shows real geographic concentration in North-West India

## 🛠 Tools Used
Power BI · DAX · Power Query · Data Modeling

## 📁 Files
- `Retail_Sales_Dashboard.pbix` — the Power BI file
- `screenshots/` — dashboard page images

## 🚀 How to Use
Download the `.pbix` file and open it in Power BI Desktop (free) to explore the dashboard interactively.
