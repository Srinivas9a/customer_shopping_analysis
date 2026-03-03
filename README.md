# 📊 Customer Shopping Behavior Analysis

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![SQL](https://img.shields.io/badge/SQL-PostgreSQL%20%7C%20MySQL%20%7C%20SQL%20Server-green?logo=postgresql)
![Power
BI](https://img.shields.io/badge/Visualization-Power%20BI-yellow?logo=powerbi)
![EDA](https://img.shields.io/badge/EDA-Exploratory%20Data%20Analysis-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

> 🚀 End-to-End Data Analytics Project \| Python + SQL + Power BI +
> Reporting

------------------------------------------------------------------------

## 📌 Project Overview

This project analyzes customer shopping behavior to extract meaningful
business insights using an end-to-end analytics workflow.

It demonstrates:

-   📥 Data Loading & Cleaning\
-   📊 Exploratory Data Analysis (EDA)\
-   🗄 SQL Business Queries (PostgreSQL / MySQL / SQL Server)\
-   📈 Interactive Power BI Dashboard\
-   📝 Analytical Report\
-   🎯 Professional Presentation (Gamma)

The goal is to transform raw transactional data into actionable insights
for decision-making.

------------------------------------------------------------------------

## 📂 Dataset Description

The dataset contains structured customer transaction data including:

-   Customer demographics\
-   Product categories\
-   Purchase history\
-   Sales amount\
-   Payment methods\
-   Transaction dates\
-   Region information

This dataset was analyzed using Python and imported into SQL databases
for advanced querying.

------------------------------------------------------------------------

## 🛠 Tech Stack

### 🔹 Programming & Analysis

-   Python\
-   Pandas\
-   NumPy\
-   Matplotlib\
-   Seaborn

### 🔹 Database & Querying

-   PostgreSQL\
-   MySQL\
-   SQL Server\
-   SQL (Joins, Aggregations, Subqueries, Window Functions)

### 🔹 Visualization & Reporting

-   Power BI\
-   Gamma (Presentation Design)

------------------------------------------------------------------------

## 🔄 Project Workflow

### 1️⃣ Data Loading

-   Imported dataset using Pandas
-   Connected Python to SQL database

### 2️⃣ Data Cleaning

-   Removed duplicates\
-   Handled missing values\
-   Converted data types\
-   Standardized categorical values\
-   Created derived columns (Age Groups, Total Spend)

### 3️⃣ Exploratory Data Analysis (EDA)

-   Sales distribution analysis\
-   Customer segmentation analysis\
-   Monthly sales trend visualization\
-   Category-wise revenue breakdown

### 4️⃣ SQL Business Analysis

Example Query:

``` sql
-- Top 5 revenue generating categories
SELECT category, SUM(sales) AS total_revenue
FROM customer_data
GROUP BY category
ORDER BY total_revenue DESC
LIMIT 5;
```

Key analyses performed: - Revenue by category\
- Monthly sales trends\
- Average order value\
- Top customers by spending\
- Region-wise performance

### 5️⃣ Power BI Dashboard

Developed an interactive dashboard including:

-   📌 Total Revenue KPI\
-   📌 Total Orders\
-   📌 Average Order Value\
-   📌 Monthly Sales Trend\
-   📌 Top Categories\
-   📌 Regional Performance\
-   📌 Customer Segmentation

------------------------------------------------------------------------

## 📊 Key Insights

-   Identified top-performing product categories\
-   Discovered peak sales months\
-   Detected high-value customer segments\
-   Highlighted underperforming regions\
-   Provided revenue growth recommendations

------------------------------------------------------------------------

## 📁 Project Structure

    Customer-Shopping-Analysis/
    │
    ├── data/
    │   └── dataset.csv
    │
    ├── notebooks/
    │   └── analysis.ipynb
    │
    ├── sql/
    │   └── queries.sql
    │
    ├── dashboard/
    │   └── powerbi_dashboard.pbix
    │
    ├── report/
    │   └── final_report.pdf
    │
    └── README.md

------------------------------------------------------------------------

## ▶️ How to Run

### 1️⃣ Clone the Repository

``` bash
git clone https://github.com/your-username/customer-shopping-analysis.git
cd customer-shopping-analysis
```

### 2️⃣ Install Dependencies

``` bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
```

### 3️⃣ Run the Notebook

``` bash
jupyter notebook
```

### 4️⃣ SQL Setup

-   Create database in PostgreSQL / MySQL / SQL Server\
-   Import dataset\
-   Execute provided SQL scripts

### 5️⃣ Power BI

-   Open `.pbix` file\
-   Refresh data connections

------------------------------------------------------------------------

## 🎯 Business Impact

This project showcases:

-   Strong data cleaning & transformation skills\
-   Practical SQL querying for business problems\
-   Dashboard design expertise\
-   Ability to convert data into strategic insights\
-   End-to-end data analytics workflow understanding

------------------------------------------------------------------------

## 👨‍💻 Author

**Srinivasu**\
Aspiring Data Analyst\
Python \| SQL \| Power BI

📫 Open to Data Analyst opportunities
