# Predictive Customer Churn Analysis in African Fintech

---

## Executive Summary

Customer retention is one of the most critical growth levers for African fintech companies operating in highly competitive and price-sensitive environments.

This project applies predictive analytics to identify high-risk churn customers and design data-driven retention strategies capable of increasing customer lifetime value and long-term profitability.

---

## 1. Business Context

African fintech markets are characterized by:

- Rapid customer acquisition
- Low switching costs
- High price sensitivity
- Strong competition

Reducing churn even marginally can generate significant revenue impact due to improved retention and engagement.

---

## 2. Business Problem

How can predictive analytics identify customers at high risk of churn and support targeted, cost-efficient retention strategies?

---

## 3. Data & Methodology

### 3.1 Data Preparation

- Data Cleaning & Transformation (R, tidyverse)
- Missing value handling
- Categorical encoding
- Feature scaling where required

### 3.2 Feature Engineering

Strategic variables created:

- Engagement Score (behavioral composite metric)
- Early Risk Flag
- Transaction Intensity
- Activity Recency

### 3.3 Modeling Approach

Two supervised learning models were applied:

- Logistic Regression (interpretability baseline)
- Random Forest (non-linear predictive performance)

### 3.4 Evaluation Metrics

- ROC Curve
- AUC Score
- Confusion Matrix
- Precision / Recall

---

## 4. Exploratory & Visual Insights

*(Visual dashboards will be integrated here)*

### 4.1 Churn Distribution

Insight: Churn is concentrated among early-stage customers, highlighting onboarding vulnerabilities.

### 4.2 Engagement Score vs Churn

Insight: Lower engagement levels significantly increase churn probability, validating behavioral segmentation strategies.

### 4.3 Payment Behavior Impact

Insight: Customers using automated payment methods demonstrate higher retention stability.

### 4.4 Model Performance Visualization

Insight: Random Forest shows superior discrimination power in separating churners from non-churners.

---

## 5. Key Findings

- Churn is strongly concentrated among low-tenure customers.
- Low engagement significantly increases churn probability.
- Automated payment adoption improves retention.
- Random Forest outperformed Logistic Regression.

---

## 6. Strategic Recommendations

1. Reinforce onboarding during first 90 days.
2. Deploy an engagement scoring system for proactive targeting.
3. Incentivize automated payment usage.
4. Develop long-term subscription & loyalty programs.

---

## 7. Model Performance

Random Forest achieved strong predictive performance (AUC > X), demonstrating reliable churn risk detection capability.

---

## 8. Business Impact Simulation

Reducing churn by 5% could:

- Increase Customer Lifetime Value
- Improve revenue stability
- Reduce acquisition dependency
- Strengthen competitive positioning

---

## 9. Tools & Technologies

- Python
- R
- R Markdown
- Tableau
- Random Forest
- Caret
- pROC

---

## 10. Project Status

✔ Data Preparation Completed  
✔ Feature Engineering Completed  
✔ Modeling Completed  
🔄 Visual Dashboard Integration in Progress  
🔄 Performance Optimization in Progress  

---

## Author

Franck Djandja  
Data Analyst | Predictive & Business Analytics  
Industry & Fintech Africa Focus
