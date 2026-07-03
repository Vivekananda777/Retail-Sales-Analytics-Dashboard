# 🛍️ Retail Sales Analytics Dashboard using Power BI

An interactive **Business Intelligence Dashboard** built using **Microsoft Power BI** to analyze retail sales performance, product profitability, promotional effectiveness, customer orders, and regional sales. The dashboard transforms raw sales data into meaningful business insights that support data-driven decision-making.

---

# 📌 Project Overview

Retail businesses generate thousands of transactions every day across products, customers, cities, and promotional campaigns. Analyzing this data manually is time-consuming and limits business visibility.

This project demonstrates the complete Power BI development lifecycle, including:

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Calculations
- Interactive Dashboard Design
- Business Intelligence Reporting

The dashboard enables users to monitor sales performance, compare business metrics across different periods, identify top and bottom-performing products, and analyze geographical sales trends.

---

# 🎯 Business Objectives

- Monitor overall sales performance
- Analyze product profitability
- Compare sales between different periods
- Identify top and bottom-performing products
- Evaluate promotional campaign effectiveness
- Track sales across different cities
- Enable interactive reporting and filtering
- Support business decision-making through visual analytics

---

# 📂 Dataset Information

The dataset contains retail sales transactions with information related to customers, products, promotions, and orders.

### Customer Details

- Customer ID
- Customer Name

### Product Details

- Product ID
- Product Name
- Category

### Sales Details

- Order ID
- Date
- Units Sold
- Price Per Unit
- Total Sales
- Net Sales
- Profit
- Discount
- Discount Percentage

### Promotion Details

- Promotion ID
- Promotion Name

### Location

- City

---

# 🧹 Data Preparation

Data preprocessing was performed using **Power Query**.

### Data Cleaning

- Removed duplicate records
- Handled missing values
- Corrected data types
- Standardized date formats
- Renamed columns
- Removed unnecessary fields
- Validated numeric values
- Improved overall data quality

### Data Transformation

- Created calculated columns
- Organized structured tables
- Optimized dataset for reporting
- Prepared the data model for analysis

---

# 🏗️ Data Modeling

Built an optimized Power BI data model by:

- Creating relationships between tables
- Implementing a Star Schema
- Optimizing report performance
- Developing reusable DAX measures

---

# 📊 Dashboard Features

## 📈 Executive Dashboard

Provides an overview of business performance using:

- Total Orders
- Profit vs Net Sales Scatter Plot
- Average Discount by Promotion Category
- Sales by City Map
- Sales Trend Analysis

---

## 📦 Product Performance Dashboard

Displays:

### Top 5 Products

- By Sales
- By Quantity Sold
- By Profit

### Bottom 5 Products

- By Sales
- By Quantity Sold
- By Profit

This helps identify high-performing and underperforming products.

---

## 📅 Sales Comparison Dashboard

Compare business performance between two user-selected periods.

Metrics compared:

- Total Sales
- Total Profit
- Quantity Sold

The comparison dashboard allows users to evaluate business growth and performance across different time periods.

---

## 📋 Detailed Sales Report

Interactive order-level report with filters for:

- Date
- Customer Name
- Product Name
- Promotion Name

Displays detailed transaction information including:

- Sales
- Profit
- Net Sales
- Discount
- Quantity Sold
- Price Per Unit

---

# 📊 Dashboard Visualizations

- KPI Cards
- Scatter Chart
- Line Chart
- Bar Chart
- Map Visualization
- Matrix/Table
- Slicers

---

# 💡 Key Business Insights

### Product Performance

- Apple iPhone 14 generated the highest sales and profit.
- Apple MacBook Air and Sony Bravia TV were among the top-performing products.
- Several low-performing products contributed minimal revenue and profit.

### Promotion Analysis

- Weekend Flash Sale offered the highest average discount.
- Seasonal promotions contributed differently to overall sales performance.

### Sales Trends

- Sales varied across different periods, indicating seasonal demand patterns.
- Trend analysis helps identify peak sales periods and supports forecasting.

### Profitability Analysis

- Strong positive relationship exists between Net Sales and Profit.
- Higher sales generally resulted in increased profitability.

### Regional Sales Analysis

- Metropolitan cities contributed significantly to total sales.
- Geographic analysis helps identify regional market opportunities.

---

# 🛠️ Power BI Features Used

## Power Query

- Data Cleaning
- Data Transformation
- Data Validation

## DAX

Created measures for:

- Total Sales
- Net Sales
- Total Profit
- Quantity Sold
- Average Discount
- Total Orders
- Product Rankings

## Interactive Features

- Slicers
- Cross Filtering
- Drill-down
- Interactive Maps
- Dynamic Tables

---

# 💻 Technologies Used

| Tool | Purpose |
|------|----------|
| Microsoft Power BI | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | KPI Calculations |
| Microsoft Excel | Data Source |
| Data Modeling | Relationship Management |

---

# 📚 Skills Demonstrated

### Technical Skills

- Power BI
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- Data Modeling
- Dashboard Development
- Data Visualization

### Business Skills

- Sales Analytics
- Product Performance Analysis
- Profitability Analysis
- Customer Analytics
- Geographic Analysis
- KPI Reporting
- Business Intelligence

---

# 📁 Repository Structure

```text
Retail-Sales-Analytics-Dashboard/
│
├── Dashboard/
│   └── Retail_Sales_Analytics_Dashboard.pbix
│
├── Dataset/
│   └── Store_Data.xlsx
│
├── Screenshots/
│   ├── Executive_Dashboard.png
│   ├── Product_Performance.png
│   ├── Sales_Comparison.png
│   ├── Order_Details.png
│   └── Dashboard_Overview.png
│
├── README.md
```

---

# 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Retail-Sales-Analytics-Dashboard.git
```

2. Open the `.pbix` file using **Microsoft Power BI Desktop**.

3. If prompted, reconnect the Excel dataset.

4. Refresh the data model.

5. Explore the dashboard using slicers and interactive visuals.

---

# 🔮 Future Enhancements

- SQL Server Integration
- Power BI Service Deployment
- Automatic Data Refresh
- Sales Forecasting
- Customer Segmentation
- Predictive Analytics
- Inventory Optimization
- Mobile Dashboard
- Row-Level Security (RLS)

---

# 👨‍💻 Author

**Vivekananda Survi**
