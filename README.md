Car Insurance Claims Analysis for AlphaCare Insurance Solutions
Project Overview
This project involves an in-depth analysis of car insurance claims data provided by AlphaCare Insurance Solutions (ACIS). The primary objective is to uncover risk factors and predictive metrics related to insurance claims, using techniques like exploratory data analysis, hypothesis testing, and advanced statistical modeling. The analysis aims to guide product optimization, marketing strategies, and client acquisition efforts.

Table of Contents
Project Overview
Objective
Technologies Used
Data Preparation
Model Development
Model Evaluation
Conclusion
How to Use This Repository
Future Work
Objective
The goal of this project is to:

Identify patterns, correlations, and predictive factors associated with insurance claims.
Improve the understanding of risk levels across geographic locations.
Provide actionable insights to refine product offerings and marketing strategies.
Technologies Used
The following libraries and tools were used for this analysis:

Python: Programming language used for data manipulation and model building.
Pandas: For data cleaning, manipulation, and preparation.
NumPy: For numerical operations and calculations.
Matplotlib & Seaborn: For data visualization.
Scikit-learn: For machine learning model development.
XGBoost: For gradient boosting models.
Statsmodels: For hypothesis testing and statistical analysis.
Data Preparation
1. Handling Missing Data:
Missing numerical values were imputed using the median.
Missing categorical values were imputed using the mode.
2. Feature Engineering:
Retained relevant features like Citizenship, LegalType, Bank, Vehicle attributes.
Categorical variables were one-hot encoded for model compatibility.
3. Categorical Data Encoding:
One-hot encoding was applied to transform categorical variables into numerical formats.
After encoding, the dataset contained 682 features.
Model Development
The following models were implemented and trained using an 80-20 split for training and testing:

Linear Regression: Basic regression model to predict Total Premium.
Decision Tree Regressor: A tree-based model to capture non-linear patterns.
Random Forest Regressor: An ensemble model to handle more complex interactions.
XGBoost Regressor: A gradient boosting machine for enhanced performance.
Model Evaluation
Each model was evaluated using the following metrics:

Mean Absolute Error (MAE): The average magnitude of errors in predictions.
Mean Squared Error (MSE): The squared difference between predicted and actual values.
Root Mean Squared Error (RMSE): The square root of MSE for better interpretability.
R² Score: Indicates how well the model explains variance in the target variable.
Feature Importance Analysis:
Random Forest and XGBoost models were analyzed for feature importance to understand which variables contributed the most to the predictions.
Conclusion
Significant risk differences were found across provinces, helping AlphaCare to focus on regional strategies.
No significant differences were detected at the zip code level for risk and margin, meaning other factors may contribute more to risk differentiation.
Ensemble models (Random Forest and XGBoost) outperformed simpler models and provided the most accurate predictions for Total Premium.
