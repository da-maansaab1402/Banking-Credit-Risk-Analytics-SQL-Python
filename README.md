# Banking Credit Risk & Loan Default Analysis (SQL | Python | Power BI)

## 📌 Business Problem
Financial institutions face capital erosion from Non-Performing Assets (NPAs). This project analyzes 32,500+ retail loan applications to identify key behavioral and financial drivers of borrower default, helping Credit Risk teams tighten underwriting policies without sacrificing healthy loan disbursement volume.

## 🛠️ Tech Stack
* **SQL (MySQL):** CTEs, Window Functions, Risk Bucket Segmentation
* **Python:** Pandas, NumPy, Seaborn, Scikit-Learn (Logistic Regression & Random Forest)
* **BI Tool:** Power BI (Portfolio Risk & Delinquency Dashboard)

## 📊 Key Analytical Findings
1. **Debt-to-Income (DTI) Threshold:** Borrowers with a Loan-to-Income ratio above **35%** exhibited a **3.4x higher default rate** compared to borrowers below 20%.
2. **Renters vs. Homeowners:** Applicants living in rented accommodations with `< 2 years` of employment tenure accounted for **48% of early defaults**.
3. **High-Risk Loan Grades:** Sub-prime grades (D, E, F) carried high interest rates (14%–18%) but suffered default rates exceeding **55%**, eroding net interest margins.

## 💡 Business Recommendations for Credit Risk Policy
* **Automated Policy Rule:** Cap unsecured personal loans at **30% Loan-to-Income ratio** for borrowers with prior bureau defaults.
* **Risk-Based Pricing:** Introduce mandatory co-applicant or collateral checks for Grade D/E loans above ₹5 Lakhs.
