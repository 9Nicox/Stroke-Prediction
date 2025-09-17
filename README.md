# Stroke-Prediction
ML project aimed at find variables able to predict stroke risk

# Context : 
Stroke is a major cause of disability and mortality.
The objective of this project is to explore the use of machine learning to predict the probability of stroke based on simple clinical data (age, hypertension, BMI, lifestyle habits, etc.).
This work is not intended for direct medical use, but illustrates how data science approaches can be applied to clinical data to generate useful insights.


# Dataset :
Name: Stroke Prediction Dataset (Kaggle).
Size: ~5,000 patients, 10 clinical variables.
Link: [Kaggle Dataset](url)
Main variables: age, gender, hypertension, cardiac history, BMI, smoking.

# Methodology : 
  Exploratory data analysis (EDA)
Descriptive analysis of variables.
Visualizations: age distribution, BMI, correlations.

  Preprocessing & Feature Engineering
Cleaning missing values.
Creating derived variables (e.g., categorized age, binary obesity).

  Modeling
Logistic regression (baseline).
Random Forest / XGBoost.
Simple neural network (Keras).

  Evaluation
Accuracy, F1-score, AUC.
Confusion matrix.

  Explainability
SHAP values for XGBoost.
Identification of the most predictive clinical variables.

# Results (to be completed) : 
Logistic Regression: AUC = XX
XGBoost: AUC = XX
Neural Network: AUC = XX

  Top features (SHAP importance):
Age
Hypertension
BMI

# Clinical interpretation

To be completed
