# Task 3 — Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a cleaned Retail Stores dataset. The goal is to understand patterns, relationships, distributions, and trends in retail transactions using statistical analysis and visualizations.

## 🎯 Objectives

- Explore and understand the dataset
- Analyze numerical and categorical variables
- Identify relationships and correlations
- Analyze transaction and spending trends over time
- Generate meaningful business insights

## 📊 Dataset

- **Rows:** 11,971
- **Columns:** 11
- **Time Period:** January 1, 2022 – January 18, 2025

### Main Features

`Transaction ID`, `Customer ID`, `Category`, `Item`, `Price Per Unit`, `Quantity`, `Total Spent`, `Payment Method`, `Location`, `Transaction Date`, `Discount Applied`

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## 🔍 EDA Performed

- Dataset inspection and statistical summary
- Category distribution analysis
- Payment method analysis
- Online vs. in-store transaction analysis
- Total spending distribution
- Price Per Unit vs. Total Spent analysis
- Quantity vs. Total Spent analysis
- Correlation analysis and heatmap
- Monthly transaction trend analysis
- Monthly spending trend analysis
- Discount status analysis

## 💡 Key Findings

- Transactions are fairly evenly distributed across product categories.
- Cash is the most commonly used payment method.
- Online and in-store transactions are relatively balanced.
- Most transactions have lower spending, with fewer high-value purchases.
- Quantity has the strongest correlation with Total Spent (**0.712**).
- Price Per Unit also has a positive correlation with Total Spent (**0.631**).
- Monthly transactions and spending remain relatively stable over time.
- Discount statuses are almost evenly distributed between True, False, and Unknown.
- January 2025 has lower values because the dataset ends on January 18, 2025.

## ▶️ How to Run

1. Open the EDA notebook in **Google Colab** or Jupyter Notebook.
2. Upload the cleaned Retail Stores dataset 
3. Run the notebook cells sequentially.
4. Review the generated visualizations and insights.

## 📁 Project Structure

```text
Task-3-EDA/
│
├── EDA_Retail_Stores.ipynb
├── cleaned_retail_stores.csv
└── README.md
```

## 📌 Conclusion

The EDA provides an overview of customer transactions, spending behavior, payment preferences, product categories, and time-based trends. The analysis demonstrates how statistical summaries and visualizations can be used to extract meaningful insights from retail data.
