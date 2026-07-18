# 📈 Bank Marketing Campaign Analysis

An end-to-end data analytics project that evaluates the effectiveness of a bank marketing campaign in promoting term deposit subscriptions. This project combines Exploratory Data Analysis (EDA), statistical hypothesis testing, and an interactive Power BI dashboard to uncover customer behavior and recommend marketing strategies that improve campaign performance.

---

## 📌 Project Overview

Banks invest significant resources in marketing campaigns to encourage customers to subscribe to term deposits. However, not every campaign successfully converts customers, resulting in unnecessary operational costs and inefficient resource allocation.

This project aims to analyze historical marketing campaign data to identify the factors influencing customer subscription decisions and provide actionable recommendations for improving future marketing campaigns.

---

## 🎯 Business Objectives

The objectives of this project are to:

- Evaluate the overall performance of the bank marketing campaign.
- Identify customer characteristics associated with higher subscription rates.
- Analyze the relationship between customers' financial conditions and deposit subscriptions.
- Recommend effective campaign strategies to improve conversion rates.

---

## ❓ Business Questions

This analysis seeks to answer the following questions:

1. How is the overall distribution of the bank's deposit marketing campaign?
2. What customer characteristics are associated with a higher likelihood of subscribing to a term deposit?
3. Is there a relationship between customers' financial conditions and their interest in subscribing to a term deposit?
4. What marketing campaign strategies are the most effective in improving deposit subscriptions?

---

## 📊 Dataset Information

- **Dataset:** Bank Marketing Dataset
- **Source:** UCI Machine Learning Repository
- **Records:** 11,162 Customers
- **Target Variable:** Deposit Subscription (`deposit`)

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook
- Power BI

---

## 🔄 Project Workflow

```
Business Understanding
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Statistical Analysis
        │
        ▼
Interactive Dashboard
        │
        ▼
Business Recommendation
```

---

## 📈 Exploratory Data Analysis

The exploratory analysis focuses on understanding both customer characteristics and marketing campaign performance.

The analysis includes:

- Customer demographic analysis
- Financial profile analysis
- Contact method performance
- Campaign frequency analysis
- Monthly subscription trend

---

## 📊 Statistical Analysis

To validate the findings obtained during the exploratory analysis, several statistical tests were performed.

| Statistical Test | Purpose |
|------------------|---------|
| Independent Sample t-Test | Compare numerical variables between subscribers and non-subscribers |
| Mann-Whitney U Test | Non-parametric comparison for numerical variables |
| One-Way ANOVA | Compare numerical variables across multiple customer groups |
| Chi-Square Test | Identify relationships between categorical variables and subscription outcomes |

---

# 📊 Dashboard

The Power BI dashboard provides an interactive overview of campaign performance through:

- KPI Summary
- Monthly Conversion Trend
- Deposit Subscription Distribution
- Contact Performance
- Campaign Frequency Analysis
- Financial Profile Analysis

> 📷 **Dashboard Preview**

<p align="center">
<img src="images/dashboard.png" width="900">
</p>

---

# 💡 Key Insights

- The highest conversion rate occurred during the **first customer contact**, reaching **53.4%**.
- Conversion rates gradually declined after the fourth contact, indicating diminishing returns from repeated follow-up attempts.
- Customers contacted through **cellular** achieved higher conversion rates than those contacted via telephone.
- Customers with higher account balances demonstrated stronger interest in subscribing to term deposits.
- Campaign performance varied across different months, suggesting that campaign timing also influences conversion success.

---

# 📌 Business Conclusion

The analysis indicates that both customer characteristics and campaign execution significantly influence deposit subscription outcomes.

Key conclusions include:

- Customer financial condition positively affects subscription likelihood.
- Communication channel selection influences campaign effectiveness.
- The first three customer contacts provide the highest conversion opportunity.
- Campaign timing contributes to variations in conversion performance.

---

# 🚀 Business Recommendations

Based on the findings, the following recommendations are proposed:

- Prioritize high-quality interactions during the first three customer contacts.
- Increase the use of **cellular communication**, which consistently demonstrates higher conversion rates.
- Focus marketing efforts on customers with stronger financial profiles.
- Optimize campaign scheduling based on historical monthly performance.
- Reduce excessive follow-up attempts for low-potential customers to improve marketing efficiency.

---

# 📂 Repository Structure

```
Bank-Marketing-Campaign-Analysis
│
├── data/
│   └── bank_marketing.csv
│
├── notebook/
│   └── bank_marketing_analysis.ipynb
│
├── dashboard/
│   └── Bank Marketing Dashboard.pbix
│
├── images/
│   └── dashboard.png
│
├── presentation/
│   └── Bank Marketing Campaign Analysis.pptx
│
└── README.md
```

---

# 📚 Skills Demonstrated

- Business Understanding
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Hypothesis Testing
- Data Visualization
- Dashboard Development
- Business Insight Generation
- Business Recommendation

---

## 👤 Author

**Chandra**

If you found this project useful, feel free to ⭐ this repository.
