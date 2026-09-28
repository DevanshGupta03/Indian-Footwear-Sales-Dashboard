# 🇮🇳 Indian Sports Footwear E-Commerce Sales Dashboard

### Interactive Excel Dashboard | Data Analytics Portfolio Project

![Dashboard Preview](DashBoard_Screenshot.png)

---

## 📊 Project Overview

This project is an improved and refined version of an India-focused sports footwear e-commerce sales analysis created using Microsoft Excel.

The project evolved from an earlier dashboard implementation. The initial version established the core dataset, KPI structure, PivotTable analysis and dashboard framework.

Based on further analysis, testing and refinement, the current version focuses on improving:

- Data readability
- KPI presentation
- Dashboard interactivity
- Order Status analysis
- Chart readability
- Number formatting
- Visual consistency
- Dashboard presentation

The final output is an interactive Excel dashboard designed to provide a quick overview of sales performance, customer behavior, product performance, brand performance, geographic performance and order status.

---

## 🔄 Project Evolution

This repository represents the **improved and refined version** of an earlier project iteration.

### Version 1

The earlier version was created to establish the initial:

- Sales dataset structure
- KPI framework
- PivotTable analysis
- PivotChart visualizations
- Dashboard layout
- Interactive slicers

### Version 2 — Current Project

The current version builds on the earlier implementation with improved analysis, readability, interactivity and presentation.

### Key Improvements

- Refined India-focused sales dataset
- Improved analytical structure
- Improved KPI calculations and presentation
- Added **Net Units Sold** KPI
- Added **Order Status** analysis
- Improved handling of Order Status values
- Added dynamic Order Status references for the dashboard
- Replaced missing Order Status results with `0` instead of `#REF!`
- Improved revenue number formatting
- Converted large revenue values into readable formats such as `₹1.73 Cr`
- Converted AOV into a compact format such as `₹5.46K`
- Improved chart axis readability
- Improved chart data-label readability
- Simplified the Revenue Trend combo chart
- Added meaningful color differentiation where required
- Added KPI and Order Status icons
- Added a Key Insights section to the dashboard
- Performed slicer-based testing and validation
- Refined the overall dashboard presentation

### Earlier Version

The earlier version is maintained separately as part of the project's development history.

👉 **View the Earlier Version:**  
https://github.com/DevanshGupta03/Indian-Footwear-Sales-Analysis

The two repositories are intentionally kept separate:

- **Version 1:** Initial dashboard implementation
- **Version 2:** Improved and refined dashboard

---

## 🎯 Business Objectives

The dashboard was designed to answer key business questions such as:

- How is revenue performing from 2018 to 2025?
- Which products generate the highest revenue?
- Which brands perform the best?
- Which Indian states contribute the most revenue?
- What is the contribution of different customer types?
- How does sales performance change across different sales channels?
- What are the overall sales and customer performance indicators?
- How do KPIs and visualizations change when different filters are applied?
- What is the distribution of order statuses?
- Which areas of the business are performing strongly?

---

## 📌 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Revenue | ₹1.73 Cr |
| Total Orders | 3,163 |
| Net Units Sold | 3,135 |
| Average Order Value | ₹5.46K |
| Average Customer Rating | 4.1 / 5 |

> KPI values update dynamically based on dashboard slicer selections.

---

## 📈 Dashboard Features

The interactive dashboard includes:

- Revenue Trend from 2018–2025
- Top 5 Products by Revenue
- Top 5 Indian States by Revenue
- Revenue by Brand
- Revenue by Customer Type
- Order Status summary
- Dynamic KPI cards
- Interactive Year slicer
- Brand slicer
- Category slicer
- Sales Channel slicer
- PivotTables
- PivotCharts
- Custom number formatting
- Dashboard-level data visualization
- Key Insights section
- Interactive dashboard filtering

---

## 📊 Dashboard Structure

The dashboard contains six major analytical sections:

### 1. Revenue Trend | 2018–2025

A combination chart showing yearly revenue performance along with Net Units Sold.

The combo chart allows two different business metrics to be viewed together while using separate scales for better interpretation.

### 2. Top 5 Products by Revenue

A horizontal bar chart highlighting the five highest-revenue products.

The horizontal format makes longer product names easier to read.

### 3. Revenue by Customer Type

A doughnut chart showing revenue contribution from:

- Loyal Customers
- New Customers
- Repeat Customers

This provides a quick view of customer-segment contribution.

### 4. Top 5 States by Revenue

A horizontal bar chart showing the top five Indian states by revenue.

This provides a geographic perspective of sales performance.

### 5. Revenue by Brand

A column chart comparing revenue generated by the major footwear brands included in the dataset.

### 6. Order Status

The Order Status section provides an operational view of:

- Delivered
- Cancelled
- Returned

The dashboard uses separate visual indicators for each status to improve readability.

---

## 🎛️ Interactive Filters

The dashboard includes four interactive slicers:

- **Year**
- **Brand**
- **Category**
- **Sales Channel**

These slicers allow users to filter the dashboard and dynamically analyze different business segments.

The connected KPI cards, PivotCharts and Order Status information update according to the selected filters.

The dashboard was tested using different slicer combinations to validate the interactive behavior.

---

## 🔍 Key Insights

### Overall Revenue

Total revenue across the analyzed period is approximately **₹1.73 Cr**.

The Revenue Trend provides an overview of yearly sales performance from 2018 to 2025.

### Brand Performance

**Adidas** is the highest-revenue brand in the overall dashboard view, generating approximately **₹32.09L**.

### State Performance

**West Bengal** is the leading state among the top five states shown, generating approximately **₹8.08L**.

### Product Performance

**New Balance Minimus TR** is the highest-revenue product among the products shown in the Top 5 Products analysis, generating approximately **₹6.61L**.

### Customer Contribution

**Repeat Customers** represent the largest customer segment by revenue contribution at approximately **43%** in the overall dashboard view.

### Order Status

The dashboard provides a clear view of delivered, cancelled and returned orders, adding an operational perspective to the sales analysis.

---

## 🎨 Dashboard Design & Readability

The dashboard was designed with a focus on **clarity, consistency and quick interpretation**.

Key design decisions included:

- Blue-based primary visual theme
- Teal accent for secondary trend information
- Green for Delivered orders
- Red for Cancelled orders
- Yellow/amber for Returned orders
- White KPI cards for visual separation
- Compact revenue formatting such as `₹1.73 Cr`
- Compact AOV formatting such as `₹5.46K`
- Simplified chart labels
- Improved chart axis readability
- Consistent chart titles
- Visual icons for KPIs and Order Status
- Key Insights section at the bottom of the dashboard

The objective was to make the dashboard easy to understand without overcrowding it with unnecessary visual elements.

---

## 🧹 Data Preparation

The dataset was cleaned, reviewed and transformed before building the dashboard.

Major preparation steps included:

- Reviewing and cleaning the source data
- Adapting the dataset to an India-focused business scenario
- Structuring sales and customer information
- Organizing product, brand and category information
- Adding Indian states and geographic dimensions
- Preparing customer-related fields
- Structuring order-status information
- Preparing the data for PivotTable analysis
- Creating dashboard-ready analytical fields
- Creating revenue and sales-related measures
- Reviewing KPI calculations
- Testing Order Status calculations
- Testing dashboard behavior using different slicer selections

The final dataset contains **3,163 records and 27 columns** covering the period from **2018 to 2025**.

---

## 🛠️ Tools & Techniques

### Tools

- Microsoft Excel
- Git
- GitHub

### Excel Techniques

- Data Cleaning
- Data Transformation
- PivotTables
- PivotCharts
- Slicers
- KPI Cards
- Excel Formulas
- Custom Number Formatting
- Dashboard Design
- Data Visualization
- Business Analysis
- Interactive Reporting
- Dashboard Testing & Validation

---

## 📚 Data Source

The project started with a publicly available sports footwear sales dataset.

The source dataset was subsequently cleaned, transformed and adapted into an India-focused analytical dataset for this project.

The current version further refines the dataset and dashboard implementation based on learnings and testing from the earlier version.

> This project is intended for educational, portfolio and data analytics practice purposes. The India-focused dataset represents an adapted analytical scenario and should not be treated as official Indian footwear market data.

---

## 💡 What This Project Demonstrates

This project demonstrates practical skills in:

- Excel-based data analysis
- Business-oriented data visualization
- Interactive dashboard development
- KPI design
- PivotTable and PivotChart analysis
- Slicer-based interactive reporting
- Data cleaning and transformation
- Sales performance analysis
- Product and brand analysis
- Customer segment analysis
- Geographic sales analysis
- Order-status analysis
- Custom number formatting
- Dashboard readability improvement
- Dashboard testing and validation
- Presenting analytical results in a professional format

---

## 🚀 Future Improvements

Possible future improvements include:

- Adding profit and margin analysis
- Adding monthly and quarterly sales analysis
- Adding customer retention analysis
- Adding advanced Excel formulas and measures
- Rebuilding the dashboard in Power BI
- Adding SQL-based analysis
- Creating automated reporting

---

## 📂 Project Files

| File | Description |
|---|---|
| `Indian_Footwear_Sales_Dashboard.xlsx` | Final Excel workbook containing the interactive dashboard |
| `Indian_Footwear_Sales_Data.csv` | Dashboard-ready sales dataset |
| `Dashboard_Screenshot.png` | Preview image of the final dashboard |

---

## 👤 Author

**Devansh Gupta**

Data Analytics Project

---

⭐ If you find this project useful, feel free to explore the dashboard and dataset.
