# 📊 Telecom Customer Churn Analysis Report

## 1. Introduction

This project analyzes **customer churn** for a telecom company using SQL Server, Power BI, and Excel. The dataset consists of **7,043 customers** with detailed demographic, service usage, billing, and churn information.

The primary objectives of this analysis are:

* To identify patterns that differentiate churned customers from retained customers.
* To understand the main drivers of churn.
* To recommend strategies that can help reduce churn and improve retention.
* To create an interactive dashboard for business stakeholders.

---

## 2. Dataset Information

The dataset was sourced from **Kaggle** and contains **7,043 rows and 23 attributes**.

### Key Features:

* **Demographics**: Gender, Senior Citizen, Partner, Dependents.
* **Services**: Phone Service, Internet Service, Online Security, Backup, Device Protection, Tech Support, Streaming.
* **Billing & Contracts**: Monthly Charges, Total Charges, Payment Method, Contract Type, Paperless Billing.
* **Support**: Number of Administrative and Technical Tickets.
* **Target Variable**: `Churn` (Yes/No).

---

## 3. Methodology

### 🔹 SQL Server

* Imported raw dataset into SQL Server.
* Created staging and cleaned tables.
* Converted problematic data types (e.g., BIT → VARCHAR).
* Handled missing/null values.
* Performed exploratory queries (distribution checks, churn segmentation, revenue analysis).

### 🔹 Power BI

* Imported cleaned SQL data into Power BI.
* Performed data transformations (binary replacements, grouping ranges, unpivoting service columns).
* Created measures such as churn rate, retention rate, and revenue metrics.
* Built **two dashboards**:

  * **Overall Customer Dashboard** (entire customer base).
  * **Churned Customer Dashboard** (focused on churned customers).

### 🔹 Excel

* Used for preliminary checks and dataset validation.

---

## 4. Key Calculations & KPIs

* **Total Customers**: 7,043
* **Churned Customers**: 1,868
* **Churn Rate**: 26.5%
* **Average Monthly Charges**: \$64.8
* **Total Revenue**: \$16.1 Million

---

## 5. Detailed Observations

1. Customers using **Fiber Optic Internet** and paying via **Electronic Check** show the highest churn rate.
2. **Gender** is not a significant factor — churn rates are similar for both male and female customers.
3. Customers less likely to churn include:

   * Those with **partners or dependents**.
   * Customers on **long-term contracts (1-year, 2-year)**.
   * Customers paying via **Credit Card Auto-pay**.
4. Among churned customers, usage of **Online Security, Online Backup, Device Protection, and Tech Support** is **very low**, suggesting poor adoption of retention-related services.

---

## 6. Recommendations

### Service Quality Improvements

* Address speed, downtime, and pricing issues in **Fiber Optic plans**.
* Offer **loyalty discounts** and **bundled add-ons** to retain fiber customers.

### Payment Method Optimization

* Encourage customers to switch from **Electronic Check** to **Auto-pay methods** (Bank Transfer, Credit Card).
* Provide incentives such as discounts, cashback, or reward points for auto-pay adoption.

### Retention & Contract Strategies

* Promote **long-term contracts** (1-year, 2-year) using discounts or bundled offers.
* Highlight **family-friendly benefits** like multi-device access for partners and dependents.

### Service Adoption Campaigns

* Run awareness campaigns highlighting the importance of Online Backup, Security, and Device Protection.
* Provide **free trial periods (1–3 months)** for these services.
* Bundle these services at **discounted rates** with internet/phone plans.

### Customer Support Enhancements

* Train support teams to **upsell retention-related services** during at-risk customer interactions.

---

## 7. Deliverables

The project includes the following files:

* 📑 **Report**: https://github.com/ANUPRIYAROYANU/TELCO-CHURN-ANALYSIS/blob/main/REPORT.docx – Formal written report.
* 🗂 **Raw Data**: https://github.com/ANUPRIYAROYANU/TELCO-CHURN-ANALYSIS/blob/main/RAW%20DATA.xlsx
* 📝 **SQL Queries**: Not all queries are uploaded.
* 📊 **Power BI Dashboard**: https://github.com/ANUPRIYAROYANU/TELCO-CHURN-ANALYSIS/blob/main/DASHBOARDS.pbix

 ## 🖼 Dashboard Previews  

### 1️⃣ Overall Customer Dashboard  
https://github.com/ANUPRIYAROYANU/TELCO-CHURN-ANALYSIS/blob/main/CUSTOMER%20DASHBOARD.png


### 2️⃣ Churned Customers Dashboard  
https://github.com/ANUPRIYAROYANU/TELCO-CHURN-ANALYSIS/blob/main/CHURNED%20CUSTOMER.png 

---

## 8. Conclusion

This project highlights that **26.5% of customers churn**, with churn concentrated among **Fiber Optic internet users** and **Electronic Check payers**.

Key strategies such as **improving service quality**, **incentivizing auto-pay methods**, **promoting long-term contracts**, and **increasing adoption of support-related services** can significantly reduce churn.

Implementing these recommendations will not only improve **customer retention** but also positively impact **revenue growth and long-term loyalty**.

---

