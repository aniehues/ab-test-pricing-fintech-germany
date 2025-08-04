# A/B Testing – Discount Impact Analysis

This project simulates and analyzes an A/B test to evaluate whether offering a **15% discount** on financial products improves:

- ✅ Conversion Rate
- ✅ Average Revenue per User (ARPU)

## Objective

To help decision-makers assess whether discount-based strategies lead to statistically significant revenue uplift across markets.

## Experiment Design

| Element         | Value                       |
|----------------|-----------------------------|
| Sample Size     | 5,000 users (2,500 per group) |
| Test Duration   | Jan 1 to Mar 30, 2025       |
| Treatment       | 15% discount applied        |
| Countries       | Germany, Austria, Switzerland |
| Products        | Budget App, Financial Course |

## Key Results

- **Conversion** increased from **14.0% → 19.9%**
- **ARPU** increased from **€8.61 → €10.39**
- Both results were **statistically significant** (`p < 0.001`)

## Technologies & Tools

- Python
- pandas, numpy, scipy, statsmodels
- seaborn, matplotlib

## File Overview

| File | Description |
|------|-------------|
| `ab-test-pricing-fintech-germany.py` | Analysis script with hypothesis testing and visualization |
| `images/` | Contains saved plots for use |
| `requirements.txt` | Python dependencies |
| `README.md` | This file |
