# 🧠 Stroke Prediction – Don’t Be Fooled by Big Numbers

## 📌 Description
This project explores the prediction of stroke risk using the [Kaggle Stroke Prediction dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset).  
The main goal is to highlight the challenges of **imbalanced datasets** and to show why metrics like **accuracy can be misleading** in a medical context.

## 📊 Dataset
- **Source**: Kaggle – Stroke Prediction Dataset  
- **Target variable**: `stroke` (binary classification)  
- **Class imbalance**:  
  - Non-stroke: ~95%  
  - Stroke: ~5%  

⚠️ This imbalance makes prediction difficult and explains why high accuracy is not always meaningful.

## ⚙️ Methods
- **Exploratory Data Analysis (EDA)**  
- **Decision Tree Classifier** → first model with very high accuracy but poor recall  
- **Handling imbalance**: stratified split, class weighting  
- **Hyperparameter tuning**  
- **Evaluation metrics**: Accuracy, Recall, F1-score, ROC-AUC, Confusion Matrix  

## 🧾 Key Takeaways
- A model can achieve **95% accuracy** simply by predicting "non-stroke" for everyone.  
- **Recall and ROC-AUC** are more appropriate metrics for evaluating medical prediction models.  
- Feature importance analysis highlights age, hypertension, and heart disease as strong predictors.  
- Proper handling of imbalance (e.g., class weights) significantly improves the model’s usefulness.

## 📂 Repository Structure
Stroke-Prediction/

├── notebooks/

│ └── stroke-prediction.ipynb

├── figures/ # (plots and visualizations - to be added later)

└── README.md


## 🚀 Next Steps
- Add SHAP analysis for interpretability  
- Try oversampling/undersampling techniques (SMOTE, random under/oversampling)  
- Compare with more models (e.g., Logistic Regression, Random Forest, XGBoost)  

---

✍️ Author: Nicolas (9Nicox)  
📅 Initial work: 2023 – Updated 2025  
