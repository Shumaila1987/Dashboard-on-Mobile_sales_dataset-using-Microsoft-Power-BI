
# 📱 Mobile Sales Analysis Dashboard — Power BI

An interactive **Mobile Sales Analysis Dashboard** developed using **Microsoft Power BI** to analyze sales performance, product quantities, brands, customer locations, and regional trends.

The dashboard transforms raw mobile sales data into an interactive business intelligence report that helps users understand sales patterns and compare performance across different dimensions.

---

## 📊 Dashboard Preview

![Mobile Sales Dashboard](https://github.com/Shumaila1987/Dashboard-on-Mobile_sales_dataset-using-Microsoft-Power-BI/blob/main/Dashboard%20on%20mobile%20sales.png)
---

[![Watch the demo](https://github.com/Shumaila1987/Dashboard-on-Mobile_sales_dataset-using-Microsoft-Power-BI/blob/main/Power%20BI%20Dashboard.mp4)

## 🎯 Project Objective

The main objective of this project is to build an interactive Power BI dashboard that provides a clear overview of mobile and electronics sales performance.

The dashboard focuses on:

- Overall sales performance
- Quantity sold
- Average product price
- Brand-wise sales
- Region-wise sales distribution
- Customer locations
- Daily sales trends
- Product and brand comparisons
- Monthly filtering and analysis

---

## 📁 Dataset

The project uses a **Mobile Sales Dataset** containing **50,000 sales records** and **16 columns**.

### Dataset Fields

| Column | Description |
|---|---|
| Product | Product category |
| Brand | Product brand |
| Product Code | Unique product identifier |
| Product Specification | Product description |
| Price | Unit price of the product |
| Inward Date | Date the product entered inventory |
| Dispatch Date | Date the product was dispatched |
| Quantity Sold | Number of units sold |
| Customer Name | Customer name |
| Customer Location | Customer's location |
| Region | Sales region |
| Core Specification | Core product specification |
| Processor Specification | Processor information |
| RAM | RAM capacity |
| ROM | ROM/storage capacity |
| SSD | SSD capacity |

### Dataset Overview

- **Records:** 50,000
- **Columns:** 16
- **Products:** Mobile Phone, Laptop
- **Brands:** 20
- **Regions:** 5
- **Date Range:** March 2023 – March 2025
- **Unique Product Codes:** 50,000

---

## 📈 Dashboard Features

### 1. KPI Cards

The dashboard provides high-level KPIs for quickly understanding overall performance, including:

- **Total Sales**
- **Average Price**
- **Quantity Sold**
- **Total Units / Products**

These KPIs provide an immediate snapshot of business performance.

### 2. Daily Quantity Sold

A line chart displays **quantity sold by day**, making it easier to identify fluctuations and trends in daily sales volume.

### 3. Sales by Customer Location

A geographic map visualizes sales across different customer locations, providing a geographical perspective on the distribution of customers.

### 4. Regional Product Analysis

A regional comparison visual shows the distribution of products across:

- Central
- North
- West
- South
- East

This allows users to compare product activity across different regions.

### 5. Sales by Region

A pie chart provides a visual breakdown of **total sales by region**, helping identify the contribution of each geographical market.

### 6. Brand-wise Sales

The dashboard includes a brand-level sales comparison to identify differences in sales performance among brands.

### 7. Brand Performance Table

A detailed table provides brand-level metrics such as:

- Brand
- Total Price
- Total Sales

This allows users to compare individual brands in more detail.

### 8. Daily Sales Trend

A time-series chart shows **total sales by day**, helping identify sales peaks, drops, and overall patterns over time.

---

## 🎛️ Interactive Filters

The dashboard includes a **month-based slicer** that allows users to interactively filter the report by:

- January
- February
- March
- April
- May
- June
- July
- August
- September
- October
- November
- December

Selecting a month dynamically updates the dashboard visuals and KPIs.

The **Brand** field can also be used to analyze performance for individual brands.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Microsoft Bing Maps** / Map visual
- **CSV Dataset**

---

## 🔄 Data Analysis Workflow

The project follows a typical Business Intelligence workflow:

```text
Raw CSV Dataset
       ↓
Data Import into Power BI
       ↓
Data Cleaning & Transformation
       ↓
Data Modeling
       ↓
DAX Measures
       ↓
Interactive Visualizations
       ↓
Dashboard
       ↓
Business Insights
🧮 Key Calculations

Some of the important analytical measures used in the dashboard include calculations for:

Total Sales
Average Price
Total Quantity Sold
Product/Unit Counts
Brand-wise Sales
Region-wise Sales
Daily Sales
Daily Quantity Sold

Example DAX measures can be structured as:
Total Sales =
SUMX(
    Sales2_data,
    Sales2_data[Price] * Sales2_data[Quantity Sold]
)
Average Price =
AVERAGE(Sales2_data[Price])
Total Quantity Sold =
SUM(Sales2_data[Quantity Sold])
💡 Business Insights

The dashboard can be used to answer questions such as:

Which brands generate the highest sales?
Which regions contribute the most to overall revenue?
How does sales volume change over time?
Which customer locations have higher sales activity?
How does quantity sold vary by day?
How does brand performance change when different months are selected?
What are the differences between mobile phone and laptop sales?
📌 Key Takeaways

This project demonstrates how Power BI can be used to convert a large raw sales dataset into an interactive analytical dashboard.

The dashboard combines KPI cards, charts, tables, maps, slicers, and time-series analysis to provide both a high-level overview and detailed sales analysis.

🚀 Future Improvements

Potential improvements for future versions include:

Adding year and quarter slicers
Adding product-category analysis
Creating a dedicated product-performance page
Adding profit and margin analysis
Adding year-over-year sales comparison
Adding drill-through pages
Adding tooltip pages
Adding advanced customer segmentation
Adding forecasting for future sales
Improving mobile/responsive dashboard layout
👨‍💻 Project Type

Data Analytics | Business Intelligence | Power BI Dashboard

This project was created as a practical demonstration of data visualization, business intelligence, and interactive reporting using Microsoft Power BI.
⭐ If you found this project useful

Feel free to ⭐ the repository and explore the dashboard and dataset.
