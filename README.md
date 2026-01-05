**California Housing Price Prediction — Project Overview**

This project predicts the **median house value** for California districts using a clear and sequential machine learning workflow.

**1. Dataset Loading**
The dataset is taken from the Hands-On Machine Learning repository and loaded using pandas. It contains **20,640 rows and 10 features**. The target variable is **median_house_value**.

**2. Data Understanding and Exploratory Analysis**
The first few rows and summary statistics were inspected. **Histograms were plotted** to study distributions, identify skewness, and understand feature behavior.

**3. Data Cleaning**
Missing values were handled or removed. Only meaningful numeric and categorical features were retained to ensure a reliable learning pipeline.

**4. Feature Processing**
The categorical column **ocean_proximity** was encoded. The feature matrix (X) and target (y) were prepared and **split into training and testing sets**.

**5. Model Training**
Two models were developed and compared:

* **Linear Regression**
* **Random Forest Regressor**

Models were trained on the training split and predictions were generated on the test split.

**6. Evaluation Metrics**
Performance was measured using:

* **Mean Squared Error (MSE)**
* **Mean Absolute Error (MAE)**
* **R Squared (R²) and Adjusted R²**

The current R² value is **approximately 0.57**, indicating moderate predictive performance.

**7. Outcome and Scope for Improvement**
The project successfully demonstrates a **structured supervised learning pipeline**. Results can be improved through:

* feature engineering
* scaling and transformations
* cross-validation
* hyperparameter tuning
