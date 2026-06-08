# FinSight Credit Risk Analysis & NPA Prediction

## Overview

This project focuses on performing large-scale Credit Risk Analytics and Non-Performing Asset (NPA) Prediction using banking loan data. The objective is to identify factors affecting loan defaults, engineer risk-related features, build regression models, and generate actionable business recommendations for reducing credit risk exposure.

---

## Project Objective

The primary objective of this project is to:

* Analyze credit risk patterns using large banking datasets
* Identify drivers influencing loan default and Loss Given Default (LGD)
* Engineer domain-specific risk features
* Build regression models for predictive analysis
* Generate business recommendations for improving lending strategies

---

## Dataset Description

The project uses **9 interconnected banking datasets** containing approximately **2 million loan records**.

### Datasets Used

* Loan Master Data
* Loan Performance Data
* Customer Bureau Data
* Credit Card Behavior Data
* Loan Enquiry Bureau Data
* Payment History Data
* Monthly EMI Tracking Data
* Collateral Information
* Regional & Economic Indicators

These datasets were merged using:

```text
loan_id
```

---

## Project Workflow

```text
Data Collection
        ↓
Data Integration
        ↓
Data Cleaning & Preprocessing
        ↓
Exploratory Data Analysis (EDA)
        ↓
Feature Engineering
        ↓
Regression Modeling
        ↓
Model Diagnostics
        ↓
Business Recommendations
```

---

## Data Cleaning & Preprocessing

The preprocessing pipeline included:

* Missing value handling
* Dirty data detection
* Outlier treatment
* Winsorization
* Data validation checks
* Feature transformation
* Dataset merging and integration

---

## Exploratory Data Analysis (EDA)

EDA was performed to understand:

* Loan default distribution
* Credit score behavior
* Correlation patterns
* Geographic risk distribution
* Loan grade performance
* Purpose-wise default behavior
* LGD distribution

### Major Visualizations

* Bar Charts
* Pie Charts
* Histograms
* KDE Plots
* Heatmaps
* Boxplots
* Scatterplots
* Time Series Analysis

---

## Feature Engineering

Several domain-specific features were created:

### Repayment Features

* EMI-to-Income Ratio
* Loan-to-Income Ratio
* Interest Rate Spread
* Real Interest Rate

### Behavioral Features

* Credit Utilization Composite
* Delinquency Severity Score
* Enquiry Velocity Score

### Risk Features

* Collateral Coverage Ratio
* Credit Depth Score
* Income Stability Ratio
* COVID Risk Indicator

---

## Regression Models Implemented

The project implements multiple regression approaches:

### OLS Regression

Used for baseline statistical modeling and interpretation.

### Ridge Regression

Used to reduce multicollinearity effects.

### Lasso Regression

Used for automatic feature selection.

### ElasticNet Regression

Used for combining L1 and L2 regularization.

---

## Model Diagnostics

Model validation included:

* Variance Inflation Factor (VIF)
* Residual Analysis
* QQ Plots
* Cook's Distance
* Scale-Location Analysis

---

## Key Findings

* Lower CIBIL scores are associated with higher default probability
* Higher EMI burden increases repayment risk
* Lower loan grades show increased default rates
* Certain loan purposes exhibit significantly higher risk
* Collateral coverage influences Loss Given Default

---

## Business Recommendations

The analysis proposes:

* Improved credit screening policies
* Risk-based pricing mechanisms
* Better collateral management
* EMI burden controls
* Portfolio optimization strategies

---

## Tech Stack

### Languages & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Statsmodels

### Tools Used

* Jupyter Notebook
* GitHub
* NotebookLM

---

## Future Scope

Potential improvements include:

* Advanced Machine Learning Models
* XGBoost Implementation
* Dashboard Development
* Real-Time Credit Scoring
* Model Deployment

---

## Author

**Soham Warke**

Computer Science | Credit Risk Analytics Project
