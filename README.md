# 🏦 HDFC Bank – Interactive Banking Analytics Dashboard
### Deposits vs Targets | Loan Portfolio | Branch Performance

**Microsoft Power BI | Power Query | DAX | Data Analytics | Business Intelligence**

---

## 📋 Table of Contents

- [📌 Project Overview](#-project-overview)
- [🎯 Problem Statement](#-problem-statement)
- [✨ Key Features](#-key-features)
- [🔄 Project Workflow](#-project-workflow)
- [🗂️ Data Model & Tables](#️-data-model--tables)
- [💰 Deposits vs Targets Analysis](#-deposits-vs-targets-analysis)
- [🏦 Loan Portfolio Analysis](#-loan-portfolio-analysis)
- [📊 Branch Performance Analysis](#-branch-performance-analysis)
- [🎥 Dashboard Walkthrough & Demonstration](#-dashboard-walkthrough--demonstration)
- [📈 Key Performance Indicators (KPIs)](#-key-performance-indicators-kpis)
- [🔍 Business Insights](#-business-insights)
- [🎛️ Interactive Dashboard Features](#️-interactive-dashboard-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [🏆 Advantages](#-advantages)
- [🙏 Acknowledgements](#-acknowledgements)
- [👤 Author](#-author)
  
---

## 📌 Project Overview

The HDFC Bank Interactive Banking Analytics Dashboard is a Business Intelligence project developed using Microsoft Power BI to analyze banking operations, deposit performance, loan portfolios, repayment activities, and branch performance.

This project consists of three interactive dashboards:

**1. Deposits vs Targets Dashboard:** Analyzes total deposits, deposit targets, achievement percentages, year-over-year growth, product-wise deposits, and geographical deposit distribution.

**2. Loan Portfolio Dashboard:** Provides insights into total loan books, active loans, EMI collections, repayment performance, outstanding loan amounts, and loan distribution by product.

**3. Branch Performance Dashboard:** Analyzes branch-level transactions, total branches, average transaction values, branch performance, and geographical distribution.

The main objective of this project is to convert banking data into meaningful visual insights that help understand financial performance, identify business trends, and support data-driven decision-making.

**Dashboard Reporting Date: 30-Apr-2025**

---

## 🎯 Problem Statement

Banking institutions manage large amounts of financial and operational data across deposits, loans, repayments, transactions, and branches.

Analyzing this data manually can make it difficult to identify performance trends, monitor financial targets, and compare branch-level operations.

**Objective:** To develop an interactive Power BI dashboard that provides a centralized view of banking performance and helps users analyze deposits, loan portfolios, repayments, and branch operations.

### Business Questions

- What are the total deposits and deposit targets?
- What percentage of deposit targets has been achieved?
- How much have deposits grown compared to the previous year?
- Which banking products contribute the most to deposits?
- What is the total loan book and number of active loans?
- How much EMI has been collected?
- Which loan product has the highest outstanding loan amount?
- Which geographical region has the highest loan exposure?
- How many branches and transactions are available?
- Which branches perform best based on transactions and deposits?

---

## ✨ Key Features

| Feature | Description |
|---|---|
| Banking KPI Cards | Displays important financial and operational metrics |
| Deposit Analysis | Compares total deposits against deposit targets |
| Loan Portfolio Analysis | Analyzes loan books and active loans |
| Repayment Analysis | Tracks EMI collections and repayment performance |
| Branch Performance | Compares branch-level transaction performance |
| Product Analysis | Analyzes deposits and loans by product type |
| Geographical Analysis | Displays city-wise and regional financial distribution |
| Year-over-Year Analysis | Compares current performance with previous-year values |
| Interactive Slicers | Filters data using financial year, quarter, month, region, zone, branch, and product |
| Drill-Down Analysis | Supports hierarchical analysis across geographical and branch dimensions |

---

## 🔄 Project Workflow

```text
           Banking Dataset
                  |
                  v
          Data Understanding
                  |
                  v
            Data Cleaning
                  |
                  v
         Data Transformation
                  |
                  v
             Data Modeling
                  |
                  v
          Table Relationships
                  |
                  v
           DAX Calculations
                  |
                  v
        Power BI Visualization
                  |
                  v
       Interactive Dashboards
                  |
                  v
           Business Insights
```

---

## 🗂️ Data Model & Tables

The project uses a structured banking data model consisting of seven tables.

| Table Name | Purpose |
|---|---|
| ProductCode | Stores banking product information |
| Date | Provides date, financial year, quarter, and month analysis |
| Branch | Contains branch name, city, zone, and region |
| Account | Stores account-related information |
| Transaction | Contains transaction details and transaction amounts |
| Loan Repayment | Stores EMI amounts and outstanding loan balances |
| Branch Deposit Target | Contains branch-wise deposit targets by year and month |

### Important Data Fields

**Branch Table**
- BranchID
- BranchName
- City
- Zone
- Region

**Transaction Table**
- TransactionID
- DateKey
- AccountID
- BranchID
- ProductCode
- Amount

**Loan Repayment Table**
- BranchID
- DateKey
- AccountID
- RepaymentID
- ProductCode
- EMIAmount
- OutstandingBalance

**Branch Deposit Target Table**
- BranchID
- Year
- Month
- TargetDeposit

The data model helps organize banking information and supports analysis across multiple dimensions.

---

## 💰 Deposits vs Targets Analysis

### 1. Overview

The Deposits vs Targets Dashboard analyzes the bank's deposit performance against predefined deposit targets.

It provides an overview of total deposits, target achievement, year-over-year growth, product-wise deposits, and geographical deposit distribution.

### 2. Dashboard Screenshot

![HDFC Bank Deposits vs Targets Dashboard](Asets/Dashboard%20Image/Page_1.png)

### 3. Key Performance Indicators

| KPI | Displayed Value |
|---|---:|
| Total Deposits | ₹12,509 Cr |
| Deposit Target | ₹49,321 Cr |
| Achievement % | 25.36% |
| YoY Deposit Growth | 49.9% |

### 4. Dashboard Components

| Visualization | Business Purpose |
|---|---|
| Actual vs Target Deposit | Compares actual deposits against monthly targets |
| Deposit Trend | Shows deposit trends across years, quarters, and months |
| Deposits by Product Type | Analyzes deposits across banking products |
| Geographical Deposit Distribution | Displays geographical deposit distribution |
| Branch Hierarchy Table | Compares deposit performance by region, zone, city, and branch |
| KPI Cards | Highlights important deposit metrics |

### 5. Key Insights

- Total deposits are ₹12,509 Cr.
- Deposit target is ₹49,321 Cr.
- Target achievement is 25.36%.
- Year-over-year deposit growth is 49.9%.
- The dashboard provides product-wise and geographical deposit comparisons.
- Branch-level analysis helps identify deposit performance across different locations.

---

## 🏦 Loan Portfolio Analysis

### 1. Overview

The Loan Portfolio Dashboard provides insights into the bank's lending activities, active loans, EMI collections, repayment performance, and outstanding loan amounts.

It helps understand the contribution of different loan products and geographical regions to the overall loan portfolio.

### 2. Dashboard Screenshot

![HDFC Bank Loan Portfolio Dashboard](Asets/Dashboard%20Image/Page_2.png)

### 3. Key Performance Indicators

| KPI | Displayed Value |
|---|---:|
| Total Loan Book | ₹37,567 Cr |
| Active Loan | 77,775 |
| EMI Collected | ₹38,267 Cr |
| Repayment | ₹1,50,000 |

### 4. Dashboard Components

| Visualization | Business Purpose |
|---|---|
| Loan Portfolio by Product | Compares the loan portfolio across different loan categories |
| Outstanding Loan Amount by Product | Displays outstanding loan amounts for each product |
| EMI Collected Trend | Analyzes EMI collection trends over time |
| Geographical Loan Amount by City | Displays city-wise loan distribution |
| Repayment by Product | Compares repayment distribution across loan products |
| Loan Portfolio Matrix | Provides hierarchical analysis by region, zone, and city |
| KPI Cards | Highlights loan and repayment performance |

### 5. Key Insights

- Total loan book is ₹37,567 Cr.
- The dashboard displays 77,775 active loans.
- EMI collected is ₹38,267 Cr.
- Repayment is displayed as ₹1,50,000.
- Business Loan shows the highest outstanding loan amount among the displayed products.
- West Region is highlighted for having the highest loan exposure.
- Repayment performance shows a 50.1% improvement compared with the previous year.

---

## 📊 Branch Performance Analysis

### 1. Overview

The Branch Performance Dashboard focuses on analyzing banking operations and transaction performance across different branches.

It helps compare transaction volumes, average transaction values, branch performance, and geographical distribution.

### 2. Dashboard Screenshot

![HDFC Bank Branch Performance Dashboard](Asets/Dashboard%20Image/Page_3.png)

### 3. Key Performance Indicators

| KPI | Displayed Value |
|---|---:|
| Total Branches | 500 |
| Total Transactions | 1M |
| Average Transaction Value | ₹2,50,174 |
| Best Performance Branch | HDFC Branch 5 |

### 4. Dashboard Components

| Visualization | Business Purpose |
|---|---|
| Branch Geographical Map | Displays geographical branch distribution |
| Branch by Transaction | Compares branches based on transaction volume |
| Transaction Trend | Analyzes transaction trends over time |
| Transaction Distribution | Displays transaction distribution by type |
| Branch Type by Performance | Compares deposits and loan books across branches |
| Branch Performance Table | Provides region-wise and branch-wise performance |
| KPI Cards | Highlights important branch metrics |

### 5. Key Insights

- The dashboard displays 500 total branches.
- Total transactions are approximately 1 million.
- Average transaction value is ₹2,50,174.
- HDFC Branch 5 is highlighted as the best-performing branch.
- The branch transaction chart identifies high-transaction branches.
- The geographical map helps analyze branch distribution across different cities.
- Branch performance can be compared using total transactions, total loan book, and total deposits.

---

## 🎥 Dashboard Walkthrough & Demonstration

Explore the HDFC Bank Analysis Dashboard through a comprehensive video walkthrough showcasing the data visualization, interactive reporting features, and key business insights developed using Microsoft Power BI.

[**View the Full Project Walkthrough**](https://drive.google.com/file/d/18kzfIBiyh-Ho2qJ3nDeMYSuQcSVQce03/view?usp=sharing)


---

## 📈 Key Performance Indicators (KPIs)

The following table summarizes the major KPIs displayed across all three dashboards.

| Dashboard | KPI | Displayed Value |
|---|---|---:|
| Deposits | Total Deposits | ₹12,509 Cr |
| Deposits | Deposit Target | ₹49,321 Cr |
| Deposits | Achievement | 25.36% |
| Deposits | YoY Growth | 49.9% |
| Loan Portfolio | Total Loan Book | ₹37,567 Cr |
| Loan Portfolio | Active Loans | 77,775 |
| Loan Portfolio | EMI Collected | ₹38,267 Cr |
| Loan Portfolio | Repayment | ₹1,50,000 |
| Branch Performance | Total Branches | 500 |
| Branch Performance | Total Transactions | 1M |
| Branch Performance | Average Transaction Value | ₹2,50,174 |
| Branch Performance | Best Branch | HDFC Branch 5 |

**Note:** These values are transcribed from the supplied dashboard screenshots. KPI values may change when filters are applied.

---

## 🔍 Business Insights

### 1. Deposit Performance

- Deposit growth is displayed at 49.9% compared with the previous year.
- Current deposits are ₹12,509 Cr against a target of ₹49,321 Cr.
- Target achievement is 25.36%.
- Product-wise and branch-wise analysis helps compare deposit contributions.

### 2. Loan Portfolio Performance

- Total loan book is ₹37,567 Cr.
- The dashboard highlights Business Loan as the leading product by outstanding loan amount.
- Geographical analysis identifies regional differences in loan exposure.
- Repayment performance shows positive year-over-year growth.

### 3. Branch Performance

- The dashboard covers 500 branches.
- Total transactions are approximately 1 million.
- HDFC Branch 5 is highlighted as the best-performing branch.
- Branch-level comparisons help identify differences in operational performance.

### 4. Overall Business Value

The three dashboards provide a consolidated view of banking performance by connecting deposit analysis, lending activities, repayment performance, and branch operations.

This makes it easier to identify trends, compare financial metrics, and understand business performance through interactive reporting.

---

## 🎛️ Interactive Dashboard Features

The dashboards provide multiple slicers to explore banking performance.

| Slicer | Purpose |
|---|---|
| Financial Year | Filters data by financial year |
| Quarter | Filters quarterly performance |
| Month | Filters monthly performance |
| Region | Filters regional performance |
| Zone | Filters zone-level performance |
| Branch | Filters individual branch performance |
| Product Type | Filters banking product information |
| City | Supports city-level analysis |

**Clear Filter:** Each dashboard provides a Clear Filter option to reset the selected filters.

---

## 🛠️ Tech Stack

| Tool / Technology | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development and visualization |
| Power Query | Data cleaning and transformation |
| DAX | Measures and KPI calculations |
| Data Modeling | Establishing relationships between banking tables |
| Microsoft Excel / Dataset | Data preparation and source data |
| Power BI Maps | Geographical analysis |

---

## 🏆 Advantages

| Advantage | Description |
|---|---|
| Centralized Reporting | Combines important banking metrics into interactive dashboards |
| Financial Monitoring | Helps monitor deposits, targets, loans, and repayments |
| Performance Analysis | Supports branch and regional comparisons |
| Interactive Filtering | Enables detailed analysis using slicers |
| Trend Analysis | Helps compare financial performance over time |
| Better Decision-Making | Converts banking data into meaningful business insights |
| Business Intelligence | Demonstrates practical applications of Power BI in banking analytics |

---

## 🙏 Acknowledgements

I would like to express my gratitude to everyone who supported me throughout the learning and development of this project.

- **Teachers and Mentors:** For their guidance, feedback, and support.
- **Microsoft Power BI:** For providing powerful business intelligence and visualization tools.
- **Microsoft Power Query:** For data cleaning and transformation capabilities.
- **Learning Resources:** For helping me improve my practical understanding of data analytics and business intelligence.

---

## 👤 Author

**Himanshi Sangani**

🎓 **Education:** Bachelor of Computer Applications (BCA) Graduate

📊 **Project Focus:** Data Analytics, Business Intelligence, and Dashboard Development

🛠️ **Skills:**
- Microsoft Power BI
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- Data Modeling
- Data Visualization
- KPI Analysis
- Business Intelligence

---

### ⭐ Thank You for Visiting!

**Learning • Analyzing • Visualizing • Growing**

If you find this project useful, feel free to explore and share your feedback.

