# Mobile Sales Analytics Dashboard

An interactive **Power BI dashboard** for analyzing mobile sales performance, transactions, customer ratings, payment behavior, product performance, and historical sales trends.

## 📊 Project Overview

The **Mobile Sales Analytics Dashboard** transforms mobile sales data into an interactive 3-page reporting solution.

The project focuses on:

- Sales and transaction KPIs
- Brand and mobile model performance
- Monthly, quarterly, and yearly trends
- City-wise sales
- Payment method analysis
- Customer rating analysis
- Month-to-Date (MTD) analysis
- Same Period Last Year (SPLY) comparison

## 🎯 Objectives

- Track important business KPIs.
- Understand sales performance by brand and mobile model.
- Analyze customer payment behavior.
- Identify sales trends over time.
- Compare current sales with previous-year performance.
- Build an interactive reporting solution using Power BI.

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Custom Calendar / Date Table**
- **Power BI Visualizations**

## 📑 Dashboard Pages

### 1. Executive Overview

The first page provides a summary of overall mobile sales performance.

It includes:

- Total Sales
- Total Quantity
- Transactions
- Average Price
- Sales by City
- Quantity by Month
- Customer Ratings
- Transactions by Payment Method
- Sales by Mobile Model
- Sales by Day Name
- Brand-wise Sales and Transactions

### 2. MTD Report

The second page focuses on **Month-to-Date (MTD)** sales pacing.

It includes:

- Date-level sales details
- Continuous sales trend
- Year/date hierarchy filtering
- Mobile Model filter
- Payment Method filter
- Monthly navigation

### 3. SPLY Analysis

The third page compares **Total Sales** with **Same Period Last Year (SPLY)**.

It includes:

- Yearly comparison
- Quarterly comparison
- Monthly comparison
- Date-level sales table
- Total Sales vs SPLY visuals

## 📌 Key KPIs

| KPI | Value |
|---|---:|
| Total Sales | 769.20M approx. |
| Total Quantity | 19K |
| Transactions | 3,835 approx. |
| Average Price | 40.11K |

## 📈 Key Insights

- **Apple** recorded the highest total sales among the brands shown, at approximately **161.6M**.
- **iPhone SE** was the highest-grossing mobile model in the model-level analysis.
- Payment methods showed a relatively balanced transaction distribution across **UPI, Debit Card, Credit Card, and Cash**.
- Monthly sales and quantity show noticeable changes over time, making trend analysis useful for understanding sales patterns.
- The SPLY page provides a direct comparison of current performance with previous-year periods.

## 🧮 DAX & Time Intelligence

The dashboard uses DAX measures for dynamic calculations.

 Include:

- `SUMX` – row-level aggregation/calculation
- `TOTALMTD` – Month-to-Date analysis
- `SAMEPERIODLASTYEAR` – previous-year period comparison

A custom calendar table is used to support continuous date-based analysis and time intelligence.

## 📂 Folder Structure

```
Mobile-Sales-Analytics-Dashboard/
│
├── Mobile_Sales_dashboard.pbix
├── README.md
├── Project_Report.pdf
└── mobile_sales_data.xlsx
```

## 📌 Project Learning

This project provided practical experience with:

- Power BI dashboard development
- Data modeling
- Power Query transformations
- DAX measures
- Time intelligence
- KPI development
- Interactive filtering
- Business-focused data visualization
- Sales trend and performance analysis


## 👤 Author

**Prajwal Salunkhe**

Data Analytics | Power BI | SQL | Python | Data Science

