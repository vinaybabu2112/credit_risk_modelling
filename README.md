
# Credit Risk Modelling with Machine Learning 💳

**Objective:** Build a model to predict borrower default risk (binary classification: default vs non-default) based on demographics, loan history, and financial indicators.

## 📁 Repository Structure



credit\_risk\_modelling/
├── data/
├── notebooks/
├── src/
│   └── main.py
├── requirements.txt
└── LICENSE


## 🚀 How to Run

```bash
git clone …
cd credit_risk_modelling
pip install -r requirements.txt
jupyter notebook  # to explore analysis
````

```bash
python src/main.py --input new_application.csv
```

## 🧠 Modeling Approach

* EDA & preprocessing
* Handling class imbalance (SMOTE / undersampling)
* Feature selection & engineering
* Trained models: Logistic Regression, Random Forest, XGBoost
* Hyperparameter tuning via GridSearchCV
* Interpretation with SHAP/LIME

## 📊 Evaluation Metrics

* Accuracy: 0.XX
* AUC‑ROC: 0.XX
* Precision / Recall / F1-score
* KS-statistic or Gini Coefficient

## 🚩 Key Insights

* Top drivers: credit history, loan amount, income-to-debt ratio
* X model outperformed others after hyperparameter tuning
* Feature interactions improved discriminatory power

## 🧾 License

Licensed under MIT (or whatever you choose)

## 🙏 Acknowledgments

* Inspired by Codebasics credit risk ML course
* Special Thanks to Dhaval patel
* Data source: Kaggle Lending Club dataset, etc.

