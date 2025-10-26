# 🩺 Heart Disease Prediction using Machine Learning

This project uses multiple ML models (RandomForest, DecisionTree, XGBoost, Logistic Regression)  
to predict the presence of heart disease based on patient data.

## 📊 Models Used

- Random Forest
- Decision Tree
- XGBoost
- Logistic Regression

## 🧠 Accuracy Summary

| Model               | Accuracy |
| ------------------- | -------- |
| XGBoost             | 0.875    |
| Random Forest       | 0.869    |
| Logistic Regression | 0.799    |
| Decision Tree       | 0.777    |

## 🧩 Files Structure
```bash
heart-disease-ml/
│
├── data/
│ └── heart_disease_uci.csv
│
├── models/
│ ├── model_random_forest.pkl
│ ├── model_decision_tree.pkl
│ ├── model_xgboost.pkl
│ └── model_logistic_regression.pkl
│
├── heart_disease.ipynb
├── requirements.txt
└── README.md
```
## 🚀 How to Run

1. Clone the repo  
   `git clone https://github.com/USERNAME/heart-disease-ml.git`
2. Install requirements  
   `pip install -r requirements.txt`
3. Run the notebook  
   `jupyter notebook heart_disease.ipynb`
