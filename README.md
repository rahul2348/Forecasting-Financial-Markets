# Forecasting-Financial-Markets
# 1-Year Return Prediction for Equity and Gold

The goal of this project is to **predict 1-year returns** of **equity (NIFTY 50)** and **gold** using historical return data over:

- 6 Months
- 1 Year
- 2 Years
- 3 Years
- 5 Years

---

## Repository Contents

This repository contains:

- `Equity.ipynb`  
  → Model to predict NIFTY 50 (equity) 1Y returns

- `Gold.ipynb`  
  → Model to predict gold 1Y returns

- `NIFTY_50_results/`  
  → Prediction outputs and evaluation results for equity

- `Gold_results/`  
  → Prediction outputs and evaluation results for gold

---

## Output Categories

Predicted returns are categorized into 5 buckets:

| Category | Return Range     |
|----------|------------------|
| 1        | Less than -15%   |
| 2        | -15% to -5%      |
| 3        | -5% to +5%       |
| 4        | +5% to +15%      |
| 5        | Greater than +15%|

---

## Future Improvements

- Include **debt instruments** in prediction for a more diversified portfolio.
- Customize investment decisions based on:
  - User's **risk appetite** (aggressive / balanced / conservative)
  - **Expected 1-year return goal**
- Using the predicted returns of gold, equity, and debt, suggest **optimal asset allocation** tailored to the user.

---

## Use Case

Given a user's financial profile and return
