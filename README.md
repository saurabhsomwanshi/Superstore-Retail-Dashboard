# Superstore-Retail-Dashboard
Superstore retail data analysis using Excel


# 📊 Excel Sales Dashboard & Business Analysis

## 📌 Project Overview

This project focuses on analyzing **online retail sales data using Microsoft Excel** and creating an interactive business dashboard.

The project demonstrates an end-to-end data analytics workflow, including **data cleaning, data modeling, DAX calculations, PivotTables, PivotCharts, and interactive dashboard development**.

The goal is to transform raw sales data into meaningful business insights that can support data-driven decision-making.

---

## 🎯 Project Objectives

* Clean and transform raw retail sales data using **Power Query**
* Build a structured data model using **Power Pivot**
* Create calculated measures using **DAX**
* Analyze sales, revenue, customers, products, and countries
* Build interactive reports using **PivotTables and PivotCharts**
* Add **Slicers and Filters** for dynamic analysis
* Identify important business trends and patterns
* Present insights through an easy-to-understand dashboard

---

## ❓ Business Questions

The dashboard was designed to answer questions such as:

* What is the total revenue generated?
* How many invoices/orders were recorded?
* Which countries generate the highest sales?
* Which products contribute the most to revenue?
* What are the monthly sales trends?
* Which months have the highest and lowest sales?
* What percentage of sales comes from domestic vs. international markets?
* What are the key sales trends and business opportunities?

---

## 🔄 Project Workflow

```text
Raw Data
   ↓
Data Cleaning & Transformation
   ↓
Power Query
   ↓
Data Model
   ↓
Power Pivot
   ↓
DAX Measures
   ↓
PivotTables & PivotCharts
   ↓
Slicers & Filters
   ↓
Interactive Dashboard
   ↓
Business Insights
```

---

## 🛠️ Tools & Technologies

| Tool                | Purpose                        |
| ------------------- | ------------------------------ |
| **Microsoft Excel** | Data analysis & dashboard      |
| **Power Query**     | Data cleaning & transformation |
| **Power Pivot**     | Data modeling                  |
| **DAX**             | Calculated measures & KPIs     |
| **PivotTables**     | Data aggregation               |
| **PivotCharts**     | Data visualization             |
| **Slicers**         | Interactive filtering          |
| **Filters**         | Dynamic data exploration       |

---

## 🧹 Data Preparation

Power Query was used to prepare the raw dataset for analysis.

### Key steps included:

* Removing invalid and unnecessary records
* Handling missing values
* Standardizing data formats
* Cleaning text and categorical fields
* Creating calculated columns
* Validating quantities and prices
* Identifying cancelled transactions
* Creating a structured sales dataset
* Preparing the data for Power Pivot

---

## 🧩 Data Model

The cleaned data was loaded into **Power Pivot** to create a structured analytical model.

The model allows different dimensions and measures to be analyzed efficiently through PivotTables and PivotCharts.

### Main analytical areas

* Sales
* Products
* Customers
* Countries
* Invoices
* Dates / Months
* Transaction status

---

## 📐 DAX Measures

DAX was used to create reusable business measures and KPIs.

Example measures include:

```DAX
Total Sales =
SUM('Sales'[Total Sales])
```

```DAX
Invoice Count =
DISTINCTCOUNT('Sales'[InvoiceNo])
```

```DAX
Average Invoice Value =
DIVIDE([Total Sales], [Invoice Count])
```

Additional measures were created to support the dashboard and business analysis.

---

## 📊 Dashboard Features

The interactive Excel dashboard includes:

* **Total Revenue KPI**
* **Invoice / Order Count**
* **Average Invoice Value**
* **Monthly Sales Trend**
* **Sales by Country**
* **Top Products**
* **Domestic vs. International Sales**
* **Interactive Slicers**
* **Filters**
* **PivotCharts**
* **Dynamic KPI analysis**

Users can interact with the dashboard by selecting different filters and slicers to explore the data from different perspectives.

---

## 📸 Dashboard Screenshots

### Main Dashboard

Add your dashboard screenshot here:

```markdown
![Excel Dashboard](images/dashboard.png)
```

### Data Model

```markdown
![Data Model](images/data-model.png)
```

### Power Query

```markdown
![Power Query](images/power-query.png)
```

> Replace the image paths with the actual screenshots uploaded to your GitHub repository.

---

## 🔍 Key Findings

The analysis identified several important business patterns:

* Total revenue was approximately **$10.6M**.
* The dataset contains sales across **38 countries**.
* The **UK** represents the largest share of sales.
* Domestic sales contribute approximately **90%** of total sales.
* International sales contribute approximately **10%**.
* Sales were strongest during the **September–November** period.
* **November** recorded the highest sales among the observed months.
* December showed a sharp decline, which may be influenced by the dataset ending partway through the month.
* A small group of top-selling products contributed a significant portion of total revenue.
* **DOTCOM POSTAGE, REGENCY CAKESTAND 3 TIER, PAPER CRAFT, and LITTLE BIRDIE** were among the major contributors to sales.

> Findings are based on the available dataset and should be interpreted within the dataset's time period and coverage.

---

## 📁 Repository Structure

```text
Excel-Sales-Dashboard/
│
├── README.md
│
├── Data/
│   └── raw_data.xlsx
│
├── Excel/
│   └── Sales_Dashboard.xlsx
│
├── Images/
│   ├── dashboard.png
│   ├── data-model.png
│   └── power-query.png
│
└── Documentation/
    └── Business_Insights.pdf
```

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open the Excel workbook.
3. Navigate to the **Dashboard** sheet.
4. Use the available **Slicers and Filters**.
5. Select different countries, products, months, or other dimensions.
6. Explore the updated KPIs and charts.
7. Review the business insights generated from the analysis.

---

## 💡 Skills Demonstrated

This project demonstrates practical skills in:

* Excel Data Analysis
* Data Cleaning
* Power Query
* Power Pivot
* Data Modeling
* DAX
* PivotTables
* PivotCharts
* Dashboard Development
* Data Visualization
* Business Intelligence
* Business Insights
* Interactive Reporting

---

## 📌 Project Highlights

**Data → Clean → Model → Calculate → Visualize → Analyze**

This project showcases how Excel can be used as a complete **business intelligence and data analytics tool**, from raw data preparation to interactive dashboard reporting.

---

## 👤 Author

**Saurabh Somwanshi**

Aspiring Data Analyst | Excel | SQL | Python | Data Visualization

---

## ⭐ If you find this project useful

Feel free to explore the repository and check out the Excel dashboard and analysis.
