# California Housing Price Prediction

This project predicts the **median house value** in California districts using the California Housing dataset.

**Dataset** — 20,640 rows, 10 columns (income, rooms, population, age, location, etc.).
Target column: `median_house_value`.

**Pipeline (Overview)**

1. Load dataset using pandas
2. Basic EDA + histograms
3. Handle missing values
4. Encode `ocean_proximity`
5. Train models — Linear Regression & Random Forest
6. Evaluate using MSE, MAE, R²

**Results (current run)**
MSE ≈ 5.77e9 | MAE ≈ 55.8k | R² ≈ 0.57

**Notes** — Model works but can be improved using
feature engineering, scaling, cross-validation, and tuning.

Run using Jupyter / Colab or Python scripts from repo.
