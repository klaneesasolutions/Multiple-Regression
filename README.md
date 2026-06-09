# Multiple-Regression
DHF Multiple Regression Analysis
# 📊 Multiple Linear Regression: Marketing Channel Effectiveness Analysis

## 🚀 Project Overview

This project applies Multiple Linear Regression to evaluate how different marketing channels influence sales performance.

The analysis focuses on four key marketing inputs:

* TV Advertising
* Radio Advertising
* Social Media Advertising
* Influencer Marketing

The objective is to quantify the impact of each channel and support data-driven marketing budget allocation decisions.

## 🎯 Business Problem

Organizations often invest across multiple marketing channels without clear visibility into which channels actually drive revenue.

This project answers a critical question:

> Which marketing channels significantly contribute to sales, and which ones do not?

## 📦 Dataset Description

The dataset contains marketing campaign data with the following variables:

| Variable     | Description                                    |
| ------------ | ---------------------------------------------- |
| TV           | TV advertising level (Low, Medium, High)       |
| Radio        | Radio advertising spend                        |
| Social Media | Social media advertising spend                 |
| Influencer   | Influencer category (Nano, Micro, Mega, etc.)  |
| Sales        | Target variable representing revenue generated |

## 🧰 Technologies Used

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Statsmodels (OLS Regression)
* SciPy

## 🔍 Workflow Summary

### 1. Data Cleaning

* Standardized column names
* Handled categorical variables
* Checked missing values and data types

### 2. Exploratory Data Analysis (EDA)

* Distribution analysis of Sales
* Correlation matrix to understand relationships between variables

### 3. Feature Engineering

* One-Hot Encoding for categorical variables (TV, Influencer)
* Prepared dataset for regression modeling

### 4. Multicollinearity Check

* Correlation matrix analysis
* Variance Inflation Factor (VIF) evaluation

### 5. Model Development

* Built Multiple Linear Regression model using Ordinary Least Squares (OLS)
* Evaluated statistical significance of predictors

### 6. Model Diagnostics

* Residual vs Fitted plot
* Q-Q plot for normality
* Residual distribution analysis

## 📊 Key Findings

* **Model Performance:** Strong explanatory power with high Adjusted R² (~0.90)
* **Strong Predictors:**

  * Radio advertising significantly impacts sales
  * TV advertising shows strong structural influence depending on spending level
* **Weak Predictors:**

  * Social Media shows no statistically significant effect
  * Influencer marketing does not contribute meaningfully to sales in this dataset

## 📉 Model Interpretation

* Increasing **Radio spend** leads to a consistent increase in sales.
* Higher **TV advertising tiers** significantly outperform lower tiers.
* **Social Media spend** does not show reliable predictive power.
* **Influencer categories** do not have statistically significant impact after controlling for other variables.

## 💡 Business Recommendations

### Increase Investment In:

* Radio advertising (high ROI channel)
* High-tier TV campaigns (strong performance driver)

### Reassess or Reduce:

* Social media spending strategy (low statistical impact)
* Influencer marketing strategy (inefficient ROI in current structure)

## 📌 Conclusion

The analysis shows that traditional media channels (TV and Radio) currently outperform digital and influencer channels in driving sales.

A reallocation of marketing budget toward high-performing channels is recommended to maximize return on investment.

## 🔮 Future Improvements

* Introduce interaction terms (e.g., TV × Radio)
* Apply log transformation for non-linear effects
* Perform feature selection using AIC/BIC
* Build predictive dashboard for real-time marketing optimization

## ⚙️ Installation

```bash
pip install pandas numpy matplotlib seaborn statsmodels scipy
```

## ▶️ How to Run

```bash
jupyter notebook
```

Open:

```
multiple_reg_analysis.ipynb
```

---

## 👤 Author

Kassim Busari
Chartered Accountant | Data Analyst | Financial Modelling Specialist
