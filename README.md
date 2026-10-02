# Fintech-_Transaction_Analysis-and-Monotoring-_risk_-profiles
End-to-end data analysis of financial transactions and risks for a Bank. Evaluates transaction success rates, fraud metrics, and revenue flow, complete with a dynamic Power BI visualization.

# Fintech Transaction Analysis & Risk Monitoring 🏦

## 📌 Project Overview
This project delivers an end-to-end data analysis of personal and retail financial transactions. The primary objective is to track spending habits, identify transaction friction, and monitor risk profiles for fraudulent activity. By extracting Key Performance Indicators (KPIs) from over 50,000 transaction records, this analysis provides a 360-degree view of financial health and operational performance.

The insights derived from this dataset are visualized in a dynamic, interactive dashboard to allow for intuitive exploration of revenue streams, expense distributions, and potential anomalies.

📊 **[View the Interactive Power BI Dashboard Here](https://app.powerbi.com/links/vnjGbGex1H?ctid=e4a7982a-3152-4bba-836d-4eaf3cb89f2d&pbi_source=linkShare)**

---

## 📂 Dataset Summary
The analysis is driven by the `finance_transactions.csv` dataset, encompassing **50,069 records** across 15 attributes, including transaction dates, amounts, channels, merchant categories, and risk scores.

### Key Descriptive Statistics:
*   **Total Amount Processed:** ₹456,141,514.47
*   **Mean Transaction Value:** ₹9,110.26
*   **Median Transaction Value:** ₹5,002.79
*   **Transaction Range:** -₹21,449.31 to ₹312,586.25 *(Note: Negative values indicate refunds, chargebacks, or account reversals)*

---

## 📈 Key Performance Indicators (KPIs)
*   **Total Transaction Volume:** 50,069 transactions processed.
*   **Success Rate:** **85.74%** (42,930 successful vs. 5,103 failed and 2,036 pending).
*   **Fraud Rate:** **1.26%** of all transactions (632 cases) were flagged as fraudulent.
*   **Revenue from Fees & Taxes:** ₹858,046.47 collected in total (Fees: ₹727,094.06 | Taxes: ₹130,952.41).

---

## 💡 Key Insights & Recommendations

1.  **Reduce Transaction Friction:** With over 5,100 failed transactions (~10.1%), there is a significant opportunity to investigate the primary technical or user-driven causes of failure—especially across high-volume channels like UPI, POS, and Auto Debit—to improve the end-user experience.
2.  **Fraud & Outlier Monitoring:** While the overall fraud rate is low (1.26%), the maximum transaction value exceeds ₹312,000 against a median of roughly ₹5,000. Dynamic security thresholds should be implemented to flag exceptionally high-value transactions or large negative values for manual review and risk scoring.
3.  **Data Quality Remediation:** The dataset contains typographical inconsistencies in the transaction channel column (e.g., "M@bile App" and trailing spaces). Stricter data validation or standardized dropdown menus at the point of data entry are recommended to ensure clean categorical reporting in future pipelines.
4.  **Targeted Merchant Campaigns:** The most heavily utilized merchant categories include Rent, Salary, Groceries, and Insurance. These segments can be leveraged to tailor customized loyalty programs, cashback offers, or targeted marketing campaigns.

---

## 🛠️ Tech Stack
*   **Data Analysis & Cleaning:** Python (Pandas) / SQL
*   **Data Visualization:** Power BI
*   **Domain:** Fintech, Risk Management, Data Analytics

---
**Author:** [Sanjay2422](https://github.com/Sanjay2422)
