# Bike Sharing System Analysis

## Business Problem

The bike-sharing system managed by Capital Bikeshare needs to ensure an adequate number of bicycles are available in every condition and situation. Meeting demand is crucial to maintain customer trust, which directly impacts profit. Effective resource optimization is essential for user satisfaction and urban planning.

## Goals

Develop accurate predictive tools to forecast bike availability based on various factors, such as weather and seasonal data. This will help Capital Bikeshare maximize profit and minimize potential losses.

## Context

Bike sharing provides automated rentals, allowing easy access and returns at different locations. The system has a global presence with over 500 programs worldwide.

## Conclusion and Recommendations

The best model for predicting bike availability is the XGBoost Regressor, optimized with `n_estimators = 200`, `max_depth = 8`, and `learning_rate = 0.1`. This model achieved:

- **MAE:** 23.97
- **MAPE:** 0.24
- **R-Squared:** 0.9535

**Recommendations:**

1. **Implement the XGBoost model** for real-time predictions to optimize bike distribution.
2. **Focus on high-impact features** such as hour, year, and season for better decision-making.
3. **Monitor model performance** regularly to adapt to changing conditions and ensure accuracy.
