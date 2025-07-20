# 📊 Financial Analysis Dashboard – Power BI Project

## 🔎 Overview

This Power BI project is designed to provide a comprehensive **financial performance analysis** based on data sourced directly from a **SQL Server database**. The project demonstrates the integration of SQL Server with Power BI, utilizing Power BI's powerful data transformation and visualization capabilities to deliver actionable business insights.

---

## 🗂️ Project Structure

### 1. **Data Source**
- **Database:** SQL Server
- **Data Flow:** Created within Power BI Service (Power BI Dataflows) to import and preprocess data from SQL Server.
- **Tables Included:** 
  - Revenue
  - Expenses
  - Profit & Loss
  - Financial KPIs
  - Time Dimension Table (for temporal slicing)

### 2. **Data Transformation**
- Performed via Power Query in Power BI.
- Key steps:
  - Column renaming and datatype conversion.
  - Filtering for relevant fiscal periods.
  - Merging tables for consolidated financial views.
  - DAX measures created for dynamic calculations (e.g., YoY growth, Net Profit Margin).

### 3. **Visualizations**
- **Financial Summary Cards:**
  - Total Revenue, Total Expenses, Net Profit, Profit Margin.
- **Time Series Charts:**
  - Revenue and Expenses trend over months/quarters/years.
- **Category Breakdown:**
  - Pie/Donut Charts for Expense by Department or Revenue by Product.
- **Profit & Loss Statement:**
  - Matrix visual showing itemized P&L over selected periods.
- **KPIs:**
  - Conditional formatting used to show positive/negative trends.

---

## 🧠 Key Features

- 🔗 **Live Connection** to SQL Server through Power BI dataflow.
- 🧮 **Dynamic DAX Measures** for year-over-year comparisons, rolling averages, and ratios.
- 🗓️ **Custom Time Intelligence**: Calendar table and dynamic filters.
- 📉 **Business Impact Insight**: Clear indication of cost centers and high-revenue sources.
- 📊 **Responsive Dashboard**: Filters for date ranges, regions, departments, etc.

---

## 🚀 How to Use

### Requirements:
- Power BI Desktop (latest version)
- Access to the SQL Server database (if refreshing the data directly)
- Alternatively, refresh the dataflow in Power BI Service

### Steps:
1. Open the file: `Financial Analysis.pbix`
2. Use the filters on the left pane to explore data by:
   - Year
   - Department
   - Financial Metric
3. Hover over charts for tooltips.
4. Use slicers to drill into specific time periods or business units.

---

## 📈 Use Cases

- Monthly and Quarterly Financial Review
- Departmental Expense Monitoring
- Trend Analysis for Revenue and Profit
- Management-level Reporting and Forecasting

---

## ✅ Best Practices Followed

- **Normalization** of tables in SQL before dataflow ingestion.
- **Star schema** adopted in Power BI model for optimal performance.
- **Naming conventions** followed for tables, columns, and measures.
- **Performance optimization** using Power BI aggregations and data reduction techniques.

---

## 🛠️ Tools & Technologies

| Tool                  | Description                              |
|-----------------------|------------------------------------------|
| **SQL Server**        | Source system for financial data         |
| **Power BI Dataflows**| For centralized data transformation      |
| **Power BI Desktop**  | For visualization and modeling           |
| **DAX**               | For business logic and KPIs              |
| **Power Query**       | For data cleansing and shaping           |

---

## 📁 File Details

- **Filename:** `Financial Analysis.pbix`
- **Created by:** *Mahek Mehta*
- **Date Created:** *20-07-2025*

---

## 📬 Contact

For any queries, improvements, or contributions, feel free to reach out:

**Email:** mahekmehta1884@gmail.com  
**LinkedIn:** https://www.linkedin.com/in/mahek-mehta/ 
