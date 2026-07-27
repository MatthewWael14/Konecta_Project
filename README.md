# Enterprise ERP Analytics Dashboards (Power BI)

A suite of interactive Power BI dashboards built to deliver real-time data visualization, operational tracking, and executive insights across Human Resources and Finance domains.

---

##  Project Overview

This project focuses on transforming raw enterprise data into actionable business intelligence using Microsoft Power BI. The solution consists of two primary dashboards tailored for executive decision-making and performance monitoring:

1. **HR Analytics Dashboard** (`ERP System HR Dashboard.pbix`)
2. **Finance Analytics Dashboard** (`ERP System Finance Dashboard.pbix`)

---

##  Dashboards & Key Features

###  1. HR Analytics Dashboard
* **Developed by:** Matthew Wael/Mohamed Wael
* **Data Source:** `HR-Employee-Attrition.csv` (1,470 records)
* **Pages:**
  * **Executive Summary:** Overview of total headcount, employee demographics, department distribution, and compensation breakdowns.
  * **Attrition & Training:** Analysis of employee attrition rates, job role turnover, monthly income distribution, and workforce retention metrics.
* **Key Metrics Tracked:** Headcount, Attrition Rate, Departmental Headcount, Job Role Distribution, and Compensation Analysis.

---

###  2. Finance Analytics Dashboard
* **Developed by:** Ahmed Wael
* **Data Source:** `Financial Sample.xlsx`
* **Focus Areas:**
  * Global sales and profit performance categorized by product lines, market segments, and geographical regions.
  * High-level KPI tracking, gross vs. net sales calculations, and discount band impact analysis.
* **Key Metrics Tracked:** Total Sales, Gross Sales, Units Sold, Profitability by Product/Country, and Discount Impact.

---

##  Tools & Technologies

* **Business Intelligence:** Microsoft Power BI Desktop (`.pbix`)
* **Data Transformation:** Power Query (ETL, Data Cleaning, Data Type Formatting)
* **Modeling & Analytics:** DAX (Data Analysis Expressions) for custom measures and KPI calculations
* **Data Sources:** CSV & Excel (`.xlsx`)

---

##  Repository Structure

```text
├── ERP System HR Dashboard.pbix             # Power BI HR Dashboard
├── ERP System Finance Dashboard.pbix        # Power BI Finance Dashboard
├── HR-Employee-Attrition.csv    # Source Data for HR Dashboard
├── Financial Sample.xlsx                    # Source Data for Finance Dashboard
└── README.md                                # Project Documentation
