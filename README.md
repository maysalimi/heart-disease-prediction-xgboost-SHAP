# 🩺 Heart Disease Risk Prediction using XGBoost and SHAP

This project implements a machine learning pipeline to predict **10-year coronary heart disease (CHD) risk** using the **Framingham Heart Study dataset**.  
It demonstrates an end-to-end workflow: data preprocessing, model training and tuning, evaluation, and interpretation using **explainable AI (SHAP)**.

---

## 📊 Project Overview

- **Goal:** Predict the probability of developing CHD within 10 years.  
- **Dataset:** Framingham Heart Study ([Kaggle link](https://www.kaggle.com/datasets/amanajmera1/framingham-heart-study-dataset))  
- **Methods:**  
  - Data preprocessing (missing value imputation, feature scaling, encoding)  
  - XGBoost classifier  
  - Hyperparameter tuning via GridSearchCV  
  - Model evaluation (accuracy, precision, recall, F1-score, confusion matrix)  
  - SHAP feature importance for interpretability  

---

## 🧠 Key Findings

- Best XGBoost model achieved **~85% accuracy** on test data.  
- Top predictors included **age, blood pressure, cholesterol, and BMI**.  
- SHAP analysis visualized feature contributions to predictions.

---

## ⚙️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/EHR-Heart-Risk.git
   cd EHR-Heart-Risk

    Install dependencies

    pip install -r requirements.txt

    Download the dataset

        Save it as data/framingham.csv

    Open and run the notebook

        notebooks/project.ipynb in Jupyter or Colab

📈 Example Results

    Confusion matrix and classification report included in the notebook

    SHAP summary plot shows feature importance

Metric	Value
Accuracy	0.86
Precision (No CHD)	0.86
Recall (No CHD)	1.00
Precision (CHD)	0.67
Recall (CHD)	0.05
🔗 Open in Colab

🧰 Tools & Libraries

Python, pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, shap

🧑‍💻 Author

May Salimi
Quantitative Biologist | University of Milan
📧 mehranehsalimi@gmail.com
