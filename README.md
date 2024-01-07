# Price_Prediction_Uber_Lyft

Analyzed Kaggle data to observe Uber availability, car preferences, and price-weather correlation.
Applied binning to categorize surge multipliers into five buckets (0 to 4) for effective analysis.

Conducted RFE to identify attribute correlations with cab fare prices.
Insights gained into factors influencing cab fare prices for more accurate future predictions.

Model Conclusions:

1. Linear Regression Model:
Poor performance: MAE 4.79, MSE 38.26, RMAE 6.19
Overpredicting prices (26.02)

2. Decision Tree Model:
Excellent performance: Score 0.9644, low errors (MAE 1.02, RMAE 1.68)
Robust predictive accuracy

3. Gradient Boosting Regressor:
High performance: Score 0.9675, low errors (MAE 1.01, RMAE 1.61, MSE 2.58).
Accurate shared ride fare predictions, yet similar to Decision Tree.

Predicted prices closely align between Decision Tree and Gradient Boosting models, confirming accurate shared ride fares.

Key Performance Metrics:

Linear Regression:
MAE 4.79, MSE 38.26, RMAE 6.19.
Decision Tree:
MAE 1.02, MSE 2.83, RMAE 1.68.
Gradient Boosting:
MAE 1.01, MSE 2.58, RMAE 1.61.
Key Influencers:

Surge multiplier, product ID, cab name, and distance heavily impact ride prices.
