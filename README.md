# Customer Churn Analysis

Analyzed customer churn behavior using Excel with a focus on **contract length** and **usage frequency**.

---

##  Problem Statement

Businesses lose revenue when customers churn. This project explores:
- **Who is churning?**
- **What patterns exist?**
- **Which groups are most at risk and most valuable?**

---

##  Dataset Overview

Each row represents a customer with the following features:
- **Demographics**: Age, Gender
- **Usage**: Frequency, Support Calls
- **Service Details**: Subscription Type, Contract Length
- **Financials**: Total Spend, Payment Delays
- **Target**: Churn (1 = left, 0 = retained)

---

## 📊 Methodology

1. **Data Cleaning**
   - Already done before analysis (no missing or inconsistent values)

2. **Exploratory Analysis**
   - Grouped by `Contract Length` and `Usage Frequency`
   - Calculated average churn per group
   - Calculated average spend
   - Identified % of total customers in risky segments

3. **Filtered Segment:**
   - Focused on **Low Usage + Monthly Contract** group

---

## 🔍 Key Insights

| Metric                          | Value        |
|--------------------------------|--------------|
| Customers in Risk Segment      | 3,383        |
| % of Total Customers           | 5.26%        |
| Churn Rate (Risk Segment)      | 65.27%       |
| Churn Rate (All Customers)     | 47.37%       |
| Avg Spend (Risk Segment)       | 554.78       |
| Avg Spend (All Customers)      | 541.02       |

- Risk segment churns **more** and spends **more**
- Monthly contracts lead to **higher churn** than annual
- Low usage is a strong churn predictor

---

##  Possible Solutions

- Offer **loyalty incentives** for monthly users
- Create **usage-based nudges** to increase engagement
- Convert low-usage monthly customers to longer contracts
- Prioritize retention for **high-value churn risks**

---

##  Tools Used

- **Microsoft Excel** (pivot tables, filtering, formulas)
- **GitHub** for version control and documentation

---

##  Portfolio Note

This project demonstrates the ability to:
- Ask business-relevant questions
- Slice data into actionable segments
- Communicate results clearly and visually
