# 📊 Swiggy Sales Analytics Dashboard – Excel

An interactive Swiggy Sales Analytics Dashboard built in Microsoft Excel to analyze sales performance, orders, customer ratings, food preferences and geographic performance.

## 📸 Dashboard Preview

![Swiggy Sales Dashboard](./Dashboard_Preview.png)


## 📥 Download the Interactive Excel Dashboard

[📊 Download Swiggy Sales Dashboard](./Swiggy_Sales_Dashboard.xlsx)

> Open the downloaded `.xlsx` file in Microsoft Excel to explore the interactive PivotTables, PivotCharts and Slicers.


## 📌 Project Overview

This project transforms raw Swiggy sales data into an interactive business dashboard using Excel data analysis and visualization techniques.

The dashboard provides a consolidated view of sales performance across different time periods, food types, states, cities and restaurants.

## 🛠️ Tools & Technologies

- Microsoft Excel
- PivotTables
- PivotCharts
- Slicers
- Excel Formulas
- Data Cleaning
- Data Analysis
- Data Visualization

## 📈 Dashboard Features

- Total Sales
- Total Orders
- Average Order Value
- Average Rating
- Rating Count
- Monthly Sales Trend
- Daily Sales Trend
- Daily Sales Trend by Day
- Sales by Food Type
- Sales by State
- Sales, Rating & Orders by Quarter
- Top 5 Cities by Sales
- Interactive Month, Category and Restaurant Name Slicers

## 🔍 Key Analysis

The dashboard helps analyze:

- Monthly sales performance
- Daily sales patterns
- Vegetarian vs Non-Vegetarian sales
- Quarterly sales and order performance
- State-wise sales distribution
- Top-performing cities
- Restaurant-level performance
- Customer rating patterns

## 🧮 Data Transformation

Additional analytical columns were created from the raw dataset, including:

- Food Type
- Day
- Quarter

These fields were used to support meaningful business analysis and dashboard visualizations.

## 📊 Key Metrics

| Metric | Value |
|---|---:|
| Total Sales | ₹53.01M |
| Total Orders | 197.43K |
| Average Order Value | ₹268.51 |
| Average Rating | 4.34 |
| Rating Count | 5.6M |

## 📁 Project Files

| File | Description |
|---|---|
| `Swiggy_Sales_Dashboard.xlsx` | Complete interactive Excel dashboard |
| `Dashboard_Preview.png` | Dashboard preview image |


## 🧩 Challenges Faced & Solutions

### 1. Raw Data Did Not Have Food Type
The dataset did not directly classify dishes as Veg or Non-Veg.

**Solution:** Created a `Food Type` column using Excel 'IF' and 'OR' logic to identify non-vegetarian keywords such as Chicken, Egg, Fish, Mutton, Prawns, Biryani and Kebab.

### 2. Creating Time-Based Analysis
The raw date field needed to be transformed into useful time dimensions for analysis.

**Solution:** Created additional fields for Month, Day and Quarter to analyze monthly, daily, weekly and quarterly sales trends.

### 3. Dashboard Layout & Visualization
Fitting multiple KPIs, charts, a map, and slicers into a single dashboard while keeping it readable was challenging.

**Solution:** Used a structured dashboard layout with KPI cards, consistent formatting, charts, slicers and a dedicated analysis sheet.

### 4. Slicer Formatting
Slicers created on the Analysis sheet appeared smaller when placed on the Dashboard, making the text difficult to read.

**Solution:** Adjusted slicer dimensions, button size, columns and formatting to improve readability and maintain consistency with the dashboard design.

### 5. Data Categorization & Aggregation
The raw dataset required transformation before meaningful business insights could be generated.

**Solution:** Used PivotTables and calculated fields to aggregate sales, orders, ratings, food types, states, cities and time periods.


## 🎯 Learning Outcomes

Through this project, I practiced:

- Excel-based data analysis
- Data cleaning and transformation
- PivotTable creation
- PivotChart development
- Interactive slicer implementation
- Dashboard design
- Business-oriented data visualization
- Deriving insights from sales data

## 👤 Author

**Amit Kumar Paswan**

Aspiring Data Analyst

[LinkedIn](https://www.linkedin.com/in/iamitkumarprofile)

[GitHub](https://github.com/iamitkumarprofile)
