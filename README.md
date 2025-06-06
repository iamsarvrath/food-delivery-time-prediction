# Food Delivery Time Prediction

## Objective
Predict or classify food delivery times based on key factors like distance, traffic, and weather using machine learning models. The project now includes an extended version with alternative classification models for deeper experimentation.

## Features
- Data Preprocessing and Cleaning
- Feature Engineering (e.g., Haversine Distance)
- Exploratory Data Analysis (EDA)
- Model Training and Evaluation:
  - Linear Regression (for time prediction)
  - Logistic Regression (for binary classification)
  - NEW: Naive Bayes, K-Nearest Neighbors (KNN), Decision Tree (v2 extension)
- Model Evaluation Metrics:
  - Regression: MAE, MSE, R²
  - Classification: Accuracy, Precision, Recall, F1-score
- Hyperparameter Tuning (GridSearchCV for KNN and Decision Tree)
- Visualizations: Distributions, Correlations, Confusion Matrices

## Structure
- `Food_Delivery_Time_Prediction.ipynb`: Original notebook for regression & logistic classification
- `Food_Delivery_Prediction_v2_Naive_Bayes_(KNN)_Decision_Tree.ipynb`: Separate v2 notebook with additional models
- `report_v2.txt`: Summary of v2 model results and recommendations

## Key Takeaways
- Linear and Logistic Regression provide a strong baseline for delivery prediction.
- Alternative models (KNN, Decision Tree) add flexibility for classification tasks.
- KNN yielded the best performance among v2 models, while Naive Bayes was limited by its assumptions.

## Recommendations
- Include time-based features (hour, day) and interaction terms
- Test ensemble methods (Random Forest, XGBoost) in future iterations
- Address class imbalance if it arises using SMOTE or reweighting

