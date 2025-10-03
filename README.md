# 📊 Bank Loan Report – Loan Data Analysis

![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-00758F?style=for-the-badge&logo=sql&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 📌 Table of Contents
1. [📝 Overview](#overview)
2. [💼 Business Problem](#business-problem)
3. [📂 Dataset](#dataset)
4. [🛠️ Tools & Technologies](#tools-technologies)
5. [🗂️ Project Structure](#project-structure)
6. [🧹 Data Cleaning & Preparation](#data-cleaning--preparation)
7. [📈 Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
8. [🔍 Research Questions & Key Findings](#research-questions--key-findings)
9. [📊 Dashboard](#dashboard)
10. [🚀 How to Run This Project](#how-to-run-this-project)
11. [✅ Final Recommendations](#final-recommendations)
12. [👤 Author & Contact](#author--contact)

---

## 📝Overview
This project analyses **bank loan data** to evaluate loan performance, identify credit risk, and provide insights into customer behaviour.  
The goal is to create an **interactive Power BI dashboard** for **data-driven loan approval and portfolio decisions**.  

---

## 💼Business Problem
The client, a lending institution, faces challenges:  

- ❌ Lack of centralized, real-time monitoring  
- ❌ No visibility into key metrics: Total Loan Applications, Funded Amount, Received Amount, Interest Rates, Debt-to-Income Ratios  
- ❌ Difficulty distinguishing **good vs. bad loans**  
- ❌ No Month-to-Date (MTD) / Month-over-Month (MoM) tracking  

**Solution:** A **three-tiered dashboard** (Summary, Overview, Details) for comprehensive **portfolio health analysis**.  

---

## 📂Dataset
Download the dataset here: [financial_loan.csv](https://drive.google.com/uc?export=download&id=17ECsTOxuBgUfIPZmvbTflub-CDorwagq)

---

## 🛠️Tools & Technologies
| Tool | Usage |
|------|-------|
| 🗄️ SQL | Data querying, comparisons, and transformations for Power BI analysis |
| 📊 Power BI | Data cleaning, preparation, and interactive dashboards |
| 🐱 GitHub | Version control, sharing, and collaboration |
| 📗 Excel | Data Exploration & Analysis |

---

## 🗂️Project Structure
```
loan-data-analysis/
│
├── README.md
├── .gitignore
├── requirements.txt
│
├── data/
│   └── loan_data.csv
│
├── notebooks/
│   ├── exploratory_data_analysis.xlsx
│   └── loan_risk_modeling.pbix
│
├── scripts/
│   ├── data_cleaning.sql
│   └── loan_summary.sql
│
├── dashboard/
│   └── bank_loan_dashboard.pbix

```

## 🧹Data Cleaning & Preparation
- 🧩 Handled missing values (**Loan Amount, DTI, Interest Rate**)  
- 🔤 Converted categorical variables (**Loan Status, Home Ownership, Loan Purpose**)  
- ⚙️ Derived features: **Good Loan vs. Bad Loan Classification**  
- 📊 Normalized Loan Amount vs. Funded vs. Received values  

---

## 📈Exploratory Data Analysis (EDA)
**Loan Status Distribution**  
- ✅ Fully Paid: 83%  
- ⚠️ Charged Off: 14%  
- ⏳ Current: 3%  

**Good vs. Bad Loans**  
- ✅ Good Loans: 86.2%  
- ❌ Bad Loans: 13.8%  

**Loan Performance Metrics**  
- 📄 Total Loan Applications: 38.6K  
- 💰 Total Funded Amount: $435.7M  
- 💵 Total Amount Received: $473.1M  
- 📈 Average Interest Rate: 12%  
- ⚖️ Average DTI: 13.3%  

---

## 🔍Research Questions & Key Findings
- **Which loans are risky?**  
  → High interest + high DTI loans default more.  

- **Approval trend?**  
  → Most loans are 36–60 months with stable growth across months.  

- **Employment length & state matter?**  
  → Employees with 10+ years experience & urban borrowers have higher approval & repayment rates.  

- **Which purposes dominate loan applications?**  
  → Debt consolidation and credit card loans dominate.  

---

## 📊Dashboard
The **Bank Loan Dashboard (Power BI)** provides:

**Summary View**  
- 📝 Total applications, funded vs. received  
- ✅ Good vs. Bad Loan performance  
- ⚠️ Loan status breakdown (Charged Off, Current, Fully Paid)  
- 📈 Average interest rate & DTI  

**Overview View**  
- 🌍 Applications by employee length, state, term, purpose, home ownership  
- 📆 Monthly loan trends  
- 🎛️ Interactive slicers for state, grade, loan purpose, loan type  

**Dashboard Preview**  

![Bank Loan Dashboard Page 1](https://raw.githubusercontent.com/soumikpaul8/Bank-Loan-Data-SQL-PowerBI/main/Images/Bank%20LoanData%20Page%201.png)


![Bank Loan Dashboard Page 2](https://raw.githubusercontent.com/soumikpaul8/Bank-Loan-Data-SQL-PowerBI/main/Images/Bank%20LoanData%20Page%202.png)


![Bank Loan Dashboard Page 3](https://raw.githubusercontent.com/soumikpaul8/Bank-Loan-Data-SQL-PowerBI/main/Images/Bank%20LoanData%20Page%203.png)



## 🚀How to Run This Project

1. Clone the repository:  
2. git clone https://github.com/soumikpaul8/loan-data-analysis.git
3. Open dataset in Power BI
4. Explore the interactive dashboard

## ✅Final Recommendations
⚡ Monitor high-interest + high-DTI loans

💳 Encourage debt consolidation loans

📅 Promote long-term loans (60 months)

🧾 Use employment length & credit history as strong approval predictors

## 👤Author & Contact
Soumik Paul
Aspiring Data Analyst | Former Software Test Engineer
📧 Email: SoumikPaul8@gmail.com




