# Predicting medal counts for countries using historical Olympic data with machine learning.

📌 Overview
This project develops a predictive model to estimate the number of medals a country will win in the Olympics based on:
- Number of athletes
- Previous medal performance
- Temporal trends (data split by year)

# Technical Approach
python

# Key steps implemented:
1. Data preprocessing (log-transform for skewed targets, handling zeros)
2. Time-based train/test split (pre-2012 / post-2012)
3. Linear Regression + SHAP explainability
4. Post-processing (non-negative constraints & integer rounding)
## Key Insights
Strongest predictor: Historical medals (medalhas_anteriores) showed 2.1× higher impact than athlete count (SHAP analysis)

Model performance: MAE of 3.3 medals after log-transform (38% improvement vs baseline)

Data skewness: 50% of countries won zero medals (requiring specialized handling)

## Technical Stack
Python (pandas, scikit-learn)

SHAP for interpretability

Seaborn/Matplotlib for visualization

📂 Files
olympics_model.ipynb: Full analysis notebook

times.csv: Raw dataset
