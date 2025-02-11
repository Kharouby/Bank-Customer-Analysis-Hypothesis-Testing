# Bank-Customer-Analysis-Hypothesis-Testing
This project analyzes bank customer data to identify significant differences in account balances across demographics using ANOVA and t-tests. Key insights help in customer segmentation. The analysis is done in Python using pandas, numpy, matplotlib, and scipy.stats.

# Bank Customer Analysis: Hypothesis Testing

## Overview
This project focuses on hypothesis testing to determine whether significant differences exist between different customer cohorts based on their bank balance. The dataset comes from a bank marketing campaign, and the analysis is conducted using statistical techniques.

## Dataset: `bank-full.csv`
- **Rows:** 45,211
- **Columns:** 17
- **Features:**
  - `age`, `job`, `marital`, `education`, `default`, `balance`, `housing`, `loan`, `contact`, `day`, `month`, `duration`, `campaign`, `pdays`, `previous`, `poutcome`, `y`
- **Target Variable:** `y` (whether the customer subscribed to a term deposit)
- **Missing Values:** None

## Objectives
- Understand whether different customer segments have significantly different account balances.
- Use **hypothesis testing** to validate statistical significance.
- Identify actionable insights from the results.

## Methods Used
### 1. Data Exploration
- Load and preview the dataset.
- Check for missing values and summary statistics.

### 2. Hypothesis Testing
- **One-way ANOVA**: Compare the mean balance across different customer segments.
- **Pairwise t-tests**: Further analyze which groups differ significantly.

### 3. Visualization
- Histograms and boxplots for balance distributions.
- Scatter plots to detect patterns.

## Libraries Used
- `pandas`, `numpy` for data handling
- `matplotlib`, `seaborn` for visualization
- `statsmodels`, `scipy.stats`, `pingouin` for hypothesis testing

## Results & Insights
- Significant differences in balance exist between customer cohorts.
- Certain job categories have distinctly higher/lower balances.
- The hypothesis tests confirm that the differences are statistically significant.
