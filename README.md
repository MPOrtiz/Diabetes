## 🩺 Diabetes Classification - Machine Learning Project

📊 Project Overview
This project focuses on predicting diabetes status (Non-Diabetic, Prediabetic, Diabetic) using clinical and biochemical features from patients. The goal is to evaluate multiple machine learning models and determine the most accurate and reliable for medical decision support.

🔍 Objectives
- Clean and preprocess the dataset (handling outliers, encoding categorical features).
- Perform exploratory data analysis (EDA) with boxplots, distribution plots, and statistical tests.
- Apply multiple classification models using:
- One-Hot Encoding (OHE)
- Ordinal Encoding

Evaluate models using:
- Accuracy
- F1-score (macro)
- AUC-ROC (macro)
- Log Loss

📈 Key Insights
- CatBoost delivered the best results across all metrics on both validation and test sets.
- HBA1C and creatinine were strong predictors based on statistical analysis and model feature importance.

🧪 Dataset & Features
Note: The dataset used is anonymized and includes fields such as:


🧠 Tools & Libraries
Python 3.x
Pandas, NumPy, Seaborn, Matplotlib
Scikit-learn
LightGBM, CatBoost
Jupyter Notebook

Mabe by MP Ortiz
