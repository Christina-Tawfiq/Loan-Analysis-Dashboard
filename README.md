# Loan Analysis Dashboard

## 👤 Candidate Summary

**Data Analytics candidate with an engineering background, developing practical skills in Excel, Power Query, Power Pivot, DAX, data analysis, and business-focused dashboard development.**

## 📂 Project Files

- [📁 Raw Data](./Raw-Data)
- [📊 Dashboard](./Dashboard)
- [📊 View / Download the Excel Dashboard](https://docs.google.com/spreadsheets/d/1sHLKO-_CaS0pPYRgTyCWQnsXxlv3LhtO/edit?usp=sharing&ouid=104296379546654231541&rtpof=true&sd=true)
  
## 📌 Project Overview

This project analyzes loan application data to understand loan activity, approval patterns, loan amounts, branch and product performance, officer efficiency, and processing time.

The project was built using **Microsoft Excel, Power Query, Power Pivot, and DAX**, with a focus on transforming raw data into clear, business-focused insights through an interactive dashboard.

---

## 🛠️ Tools & Techniques

* Microsoft Excel
* Power Query
* Power Pivot
* DAX
* Data Cleaning & Transformation
* Data Analysis
* Pivot Tables
* Dashboard Design
* Business Insights

---

## 🎯 Business Questions & Insights

### 1. From Request to Disbursement

**Business Question:**
How much of the requested loan amount is actually disbursed?

**Key Metrics:**

| Metric                       |   Value |
| ---------------------------- | ------: |
| Total Requested Loan Amount  | 345.13M |
| Total Loan Amount            |  38.51M |
| Disbursement Amount Rate     |  11.16% |
| Total Applications           |     999 |
| Approved Applications        |     545 |
| Not Approved Applications    |     454 |
| Approval Rate                |  54.55% |
| Requested vs Loan Amount Gap | 306.63M |

**Insight:**
54.55% of applications were approved, while the total Loan Amount represented 11.16% of the total requested amount.

---

### 2. Growth Over Time

**Business Question:**
How does loan activity change between 2023 and 2024?

| Metric                      |    2023 |    2024 |
| --------------------------- | ------: | ------: |
| Applications                |     492 |     507 |
| Total Requested Loan Amount | 169.66M | 175.47M |
| Total Loan Amount           |  19.29M |  19.22M |

**Insights:**

* Application volume increased from **492 to 507 (+3.0%)**.
* Total requested loan amount increased from **169.66M to 175.47M (+3.4%)**.
* Total Loan Amount was almost unchanged, moving from **19.29M to 19.22M (-0.4%)**.

---

### 3. Officer Performance

**Business Question:**
Are high-volume officers also efficient?

| Officer | Loan Amount | Work Efficiency |
| ------- | ----------: | --------------: |
| EMP15   |       2.27M |             0.7 |
| EMP5    |       2.17M |             0.7 |
| EMP9    |       2.00M |             0.9 |
| EMP2    |       1.80M |             0.6 |
| EMP14   |       1.75M |             0.4 |

**Insight:**
Among the top 5 officers by Loan Amount, Work Efficiency varied from **0.4 to 0.9**, indicating differences in processing efficiency across high-volume officers.

---

### 4. Processing Efficiency

**Business Question:**
Are approved loans processed within SLA?

**Key Metrics:**

| Metric       |     Value |
| ------------ | --------: |
| Average SLA  |    5 days |
| Average TAT  | 5.07 days |
| TAT Variance |     1.36% |

**Insight:**
Approved loans had an average TAT of **5.07 days** compared with an average SLA of **5 days**, indicating that processing time was slightly above the target on average.

---

### 5. Branch, Product & Monthly Activity

#### Branch Performance

**Business Question:**
Which branches have the highest loan activity?

Among the top 10 branches:

* Highest: **Hernandezhaven — 4.36M**
* Lowest: **East Carrie — 3.38M**

**Insight:**
Loan activity varied across branches, with Hernandezhaven recording the highest Loan Amount at **4.36M**, while East Carrie recorded the lowest among the top 10 branches at **3.38M**.

#### Product Analysis

**Business Question:**
How is loan activity distributed across products?

| Product        | Loan Amount |
| -------------- | ----------: |
| Personal Loan  |       8.24M |
| Auto Loan      |       8.19M |
| Business Loan  |       8.13M |
| Education Loan |       7.27M |
| Home Loan      |       6.68M |

**Insight:**
Personal Loan had the highest Loan Amount at **8.24M**, while Home Loan had the lowest at **6.68M**.

#### Monthly Loan Activity

**Business Question:**
How does loan activity vary by month?

**Insight:**
Monthly activity ranged from **70 to 94 cases**, with the highest volume in **March and December** and the lowest in **April**.

---

## 📊 Dashboard

The interactive dashboard includes:

### KPI Cards

* **Total Requested Loan Amount**
* **Total Loan Amount**
* **Total Applications**
* **Approved Applications**
* **Not Approved Applications**
* **Approval Rate**
* **Disbursement Amount Rate**

### Visualizations

* Top 5 Officers by Loan Amount vs Work Efficiency
* Loan Amount by Branch
* Loan Amount by Product
* Cases per Month
* Requested vs Loan Amount
* Approval Status Analysis
* SLA vs TAT

### Interactive Filters

* Timeline by Application Date
* Interactive slicers for exploring loan activity

---

## 🔄 Methodology

### 1. Data Preparation — Power Query

The raw dataset was prepared using Power Query.

Key steps included:

* Data type conversion
* Text, date, and number formatting
* Renaming **Tenure (Months)** to **Tenor (Months)**
* Selecting relevant columns
* Removing blank rows
* Removing duplicates based on Transaction ID
* Preparing the Approval Status field

### 2. Data Modeling — Power Pivot & Pivot Tables

The cleaned data was loaded into the Excel Data Model and analyzed using Power Pivot and Pivot Tables.

The analysis included:

* Loan Amount by Officer
* Loan Amount by Branch
* Loan Amount by Product
* Monthly application activity
* Requested vs Loan Amount
* Approval Status
* SLA and TAT analysis
* Work Efficiency

### 3. DAX Analysis

DAX measures were created to calculate key business metrics such as:

* Total Requested Loan Amount
* Total Loan Amount
* Total Applications
* Approved Applications
* Not Approved Applications
* Approval Rate
* Disbursement Amount Rate
* Requested vs Loan Amount Gap
* Average SLA
* Average TAT

### 4. Dashboard Design

The final dashboard combines KPIs, charts, timelines, and interactive filters to provide a clear view of loan operations and business performance.

---

## 💡 Business Value

The dashboard provides a consolidated view of loan operations and helps analyze:

* Loan application and approval activity
* Requested vs actual Loan Amount
* Branch performance
* Product-level loan activity
* Officer performance and efficiency
* Monthly application trends
* Processing time against SLA

The analysis transforms raw loan data into clear business insights that can support operational monitoring and performance analysis.

---

## 👩‍💻 About the Project

This project is part of my transition into **Data Analytics**, where I am developing practical skills in data cleaning, data modeling, DAX, visualization, and business analysis.

The project demonstrates how Excel can be used beyond basic spreadsheet analysis to build an interactive, data-driven business dashboard.
