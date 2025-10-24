# 📊 Loan Application Analysis (Excel Project)
##![Image](https://github.com/user-attachments/assets/a4e71d53-b0ad-4faf-a6c3-a7dbc31960f0)
## 🗂️ About the Dataset
This dataset simulates loan applications and approval outcomes for **2,000 individuals**.  
It contains demographic, financial, and employment-related attributes that can be used to explore loan approval patterns and credit risk factors.

### **Dataset Columns**
| Column Name | Description |
|--------------|--------------|
| `name` | Applicant’s name |
| `city` | City of residence |
| `income` | Applicant’s monthly income (₦) |
| `credit_score` | Creditworthiness score of the applicant |
| `loan_amount` | Amount of loan requested (₦) |
| `years_employed` | Number of years the applicant has been employed |
| `points` | Additional scoring points assigned by the bank |
| `loan_approved` | Loan approval status (Approved / Rejected) |

---

## 🎯 Project Objective
To analyze the loan dataset and uncover key insights related to:
- Loan approval trends  
- Impact of income, employment, and credit score on approvals  
- Identification of risk thresholds and applicant characteristics  
- Development of an **interactive Excel dashboard** for business reporting

---

## 📈 Tools Used
- **Microsoft Excel**
  - Pivot Tables
  - Pivot Charts
  - Conditional Formatting
  - Slicers
  - Grouping
  - Scatter Plots
  - Column, Bar, and Pie Charts

---

## 🧮 Business Questions Explored

### 1️⃣ What percentage of loan applications were approved vs rejected?
**Excel Steps:**
- Create a Pivot Table  
  - Rows: `loan_approved`  
  - Values: `loan_approved` (count)  
- Right-click → *Show Values As → % of Grand Total*  
- Visualize using a **Pie Chart**

---

### 2 What is the average income and credit score of approved vs rejected applicants?
**Steps:**
- Rows: `loan_approved`  
- Values: `income` → *Average*  
- Values: `credit_score` → *Average*  
- Visualize with a **Clustered Column Chart**

---

### 3 What is the average loan amount requested across different income levels?
**Steps:**
- Rows: `income` → Group into ranges (e.g., 0–50k, 51–100k, etc.)  
- Values: `loan_amount` → *Average*  
- Visualize using a **Column Chart**

---

### 4 Is there a minimum credit score threshold where approvals increase significantly?
**Steps:**
- Rows: `credit_score` → Group (by 50 or 25)  
- Columns: `loan_approved`  
- Values: `loan_approved` (count)  
- Show Values As → *% of Row Total*  
- Add **Column Chart**  
- Highlight threshold using **Data Labels** and **Conditional Formatting**

---

### 5 What is the approval rate by income group?
**Steps:**
- Rows: `income` → Group into ranges  
- Columns: `loan_approved`  
- Values: `loan_approved` (count)  
- Show Values As → *% of Row Total*  
- Visualize with a **Bar Chart**

---

## 🧠 Key Insights
- Loan approvals increase significantly for applicants with **credit scores above 650**.  
- **Higher-income** and **longer-employed** applicants have greater approval chances.  
- **Credit Score** strongly influences approval outcomes.  
- Most rejected applicants fall in the **low income (< ₦50,000)** and **low credit score (< 600)** segments.

---

## 🖼️ Dashboard Overview
The final Excel dashboard includes:
| Section | Visualization |
|----------|----------------|
| Loan Approval Distribution | Pie Chart |
| Approval by Income Group | Bar Chart |
| Credit Score Thresholds | Column + Conditional Formatting |
| Average Income & Credit Score by Approval | Clustered Column Chart |
| Filters | Slicers for City, Employment Years, Loan Status |

---

## 🔄 How to Refresh the Dashboard
When new data is added:
1. Click any Pivot Table.  
2. Go to **PivotTable Analyze → Refresh All.**  
3. All Pivot Charts and Slicers update automatically.

---

## 📘 Conclusion
This Excel project demonstrates how business intelligence techniques can be applied using **Microsoft Excel** to:
- Derive data-driven insights  
- Identify loan approval patterns  
- Improve decision-making in financial analysis  

The project focuses entirely on **Excel-based analysis**, without using Python, SQL, or any external libraries.

---

**Author:** Adewole Temitayo Ezekiel  
**Tool:** Microsoft Excel  
**Institution:** University of Ilorin  
**Focus:** Business Intelligence & Data Analytics  
