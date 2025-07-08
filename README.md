# Sustainability-Score-Predictor

In this project,I developed and evaluated machine learning models to predict the sustainability score of products based on categorical attributes like material, usage, and product type. The objective was to enable automated scoring of eco-friendliness for products on a sustainable e-commerce platform.

I began by preprocessing the dataset, converting key string features (Material, Used In, and Type) into numerical form using label encoding. Exploratory data analysis (EDA) and visualizations were performed to understand feature distributions and correlations.

Two regression models were trained and compared:

Random Forest Regressor

XGBoost Regressor

The Random Forest model outperformed XGBoost in all evaluation metrics:

MAE: 6.30 (vs 6.90)

RMSE: 8.72 (vs 10.36)

R² Score: 0.89 (vs 0.85)

This suggests that Random Forest is more suitable for this small-to-medium dataset with categorical inputs.

Additionally, visual comparisons such as predicted vs actual scatter plots and 3D feature plots confirmed the accuracy and reliability of the Random Forest model. Feature importance analysis further highlighted which input factors (e.g., material type) contributed most to sustainability prediction.

✅ Final Outcome:
A trained Random Forest model ready for integration into the backend of the sustainable shopping platform — capable of auto-scoring products based on eco-relevant attributes.
