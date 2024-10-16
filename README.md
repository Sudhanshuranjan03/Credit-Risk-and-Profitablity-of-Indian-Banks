# Credit Risk and Profitability Analysis of Indian Banks (2017-2019): A Panel Data study


**Overview**

This project explores the relationship between credit risk and profitability in Indian public and private sector banks, focusing on the period from 2017 to 2019. Using panel data analysis, it examines how credit risk measures such as the Non-Performing Assets to Loans Ratio (NPALR) and the Capital Adequacy Ratio (CAR) impact the Return on Assets (ROA), which is used as a proxy for bank profitability.

**Objective**

The primary objective of this study is to investigate how credit risk influences the profitability of banks in India. The project aims to:

Analyze the impact of NPALR and CAR on ROA.
Identify the most suitable econometric model to explain the relationship between credit risk and profitability.
Provide insights into credit risk management's role in maintaining financial stability for banks.

**Data**

Data Source: The data is sourced from the annual accounts of scheduled commercial banks, compiled from the Reserve Bank of India's Database on Indian Economy (DBIE).
Sample Size: 33 banks (12 public sector banks and 21 private sector banks).
Time Period: 3 years (2017, 2018, and 2019).

**Methodology**

This project employs panel data analysis to capture both cross-sectional and time-series variations. The following models were used:

Pooled Ordinary Least Squares (OLS): Assumes homogeneity across banks without accounting for individual differences.
Fixed Effects (FE) Model: Controls for bank-specific effects by considering variations within banks over time.
Random Effects (RE) Model: Considers variations across banks while assuming bank-specific effects are random.

**Statistical Tests**

Hausman Test: Determines whether FE or RE is more appropriate.
Breusch-Pagan LM Test: Tests for the suitability of Pooled OLS vs. RE.
F-Test: Evaluates the significance of time dummies.
Results
Best-Fit Model: The Random Effects (RE) model was selected as the best-fitting model, based on statistical test results.

**Key Findings:**

An increase in NPALR negatively impacts ROA, indicating that higher non-performing assets reduce bank profitability.
A higher CAR has a positive influence on ROA, suggesting that maintaining adequate capital buffers enhances profitability.

**Conclusion**

The study highlights the importance of effective credit risk management in maintaining the financial health of banks. It provides valuable insights for policymakers and bank managers on optimizing credit risk to improve profitability.

**Repository Structure**

data/: Contains the dataset used for the analysis.

notebooks/: Jupyter notebooks with the model codes and model outputs.

results/: Summary statistics, model comparisons, and reporting.

README.md: Overview and detailed information about the project.
