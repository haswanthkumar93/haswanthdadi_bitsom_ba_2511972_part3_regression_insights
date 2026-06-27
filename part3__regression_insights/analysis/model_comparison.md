# Model Comparison

## Simple Regression 1

Model: monthly_sales ~ footfall

R² = 0.7363

### Interpretation

Footfall accounts for 73.63% of the variability in monthly sales. It is a strong predictor and very informative for assessing how customer traffic affects sales.

---

## Simple Regression 2

Model: monthly_sales ~ marketing_spend

R² = 0.1672

### Interpretation

Marketing spend explains 16.72% of the variability in monthly sales. It is statistically meaningful but substantially weaker than footfall.

---

## Multiple Regression

R² = 0.8229

Variables included:

* marketing_spend
* footfall
* inventory_availability_pct
* staff_count
* clean_customer_rating
* holiday_flag
* Region_North
* Region_South
* Region_West

### Interpretation

This model explains 82.29% of the variance in monthly sales and offers the strongest explanatory power.

---

## Comparison summary

| Model               | R²     | Strength    |
| ------------------- | ------ | ----------- |
| Simple Regression 1 | 0.7363 | Strong      |
| Simple Regression 2 | 0.1672 | Weak        |
| Multiple Regression | 0.8229 | Very Strong |

---

## Final model selection

The Multiple Regression model is chosen as the final model because it:

* Has the highest R²
* Provides coherent business interpretation
* Shows the best predictive performance
* Supports strategic decision-making
