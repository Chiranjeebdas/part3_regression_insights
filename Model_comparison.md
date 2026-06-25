# Model Comparison

## Objective

The objective of this analysis is to compare the performance of the Simple Linear Regression model and the Multiple Linear Regression model for predicting monthly sales.

---

# Models Evaluated

## Model 1: Simple Linear Regression

**Dependent Variable**

* monthly_sales

**Independent Variable**

* marketing_spend

This model evaluates the impact of marketing spend alone on monthly sales.

---

## Model 2: Multiple Linear Regression

**Dependent Variable**

* monthly_sales

**Independent Variables**

* marketing_spend
* footfall
* avg_discount_pct
* staff_count
* inventory_availability_pct
* competitor_distance_km
* holiday_flag
* customer_rating
* region (dummy variables)
* store_type (dummy variables)

This model evaluates the combined impact of multiple business factors on monthly sales.

---

# Comparison Table

| Metric                   | Simple Regression | Multiple Regression |
| ------------------------ | ----------------- | ------------------- |
| Number of Predictors     | 1                 | Multiple            |
| Model Complexity         | Low               | High                |
| Prediction Accuracy      | Moderate          | High                |
| Business Insights        | Limited           | Comprehensive       |
| Ability to Explain Sales | Low               | High                |

---

# Interpretation

The Simple Linear Regression model explains the relationship between monthly sales and marketing spend only. Although it is easy to understand, it ignores several important business factors.

The Multiple Linear Regression model considers additional operational and customer-related variables. As a result, it provides a more comprehensive explanation of monthly sales and produces more reliable predictions.

---

# Advantages of Simple Regression

* Easy to interpret
* Fast to build
* Useful for understanding one predictor

---

# Advantages of Multiple Regression

* Higher predictive capability
* Considers multiple business drivers
* Better decision support
* More accurate forecasting

---

# Limitations

### Simple Regression

* Ignores other influencing variables.
* Lower explanatory power.
* May underfit complex business problems.

### Multiple Regression

* More computationally intensive.
* Requires careful handling of multicollinearity.
* Slightly more difficult to interpret.

---

# Final Conclusion

The Multiple Linear Regression model is recommended for business decision-making because it captures the combined influence of multiple business factors and provides better predictive performance than the Simple Linear Regression model.
