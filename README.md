
# 💳 Credit Risk Modelling with Machine Learning

This project focuses on building a machine learning pipeline to predict whether a loan applicant is likely to default. It involves data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation. This type of model can be used by banks, NBFCs, and fintech platforms to automate and enhance the credit risk assessment process.



## 📌 Objective

To classify customers as **high-risk** or **low-risk** based on historical loan application data using machine learning techniques. The project helps financial institutions make informed decisions during the loan approval process.



## 🧾 Dataset Overview

- **Source**: Publicly available dataset (e.g. Kaggle, Lending Club – update if known)
- **Total Records**: ~10,000+
- **Target Variable**: `Loan_Status` or `Default`
- **Key Features**:
  - Applicant income
  - Employment status
  - Credit history
  - Loan amount
  - Marital status
  - Property area
  - Debt-to-income ratio
  - Number of dependents
  - Education level



## 📁 Project Structure



credit\_risk\_modelling/
├── data/                  # Raw and cleaned data files
├── notebooks/             # Jupyter notebooks for EDA and modeling
│   └── credit\_risk\_modeling.ipynb
├── models/                # Saved model objects (e.g., .pkl files)
├── src/                   # Source scripts for preprocessing, training, prediction
│   └── main.py            # Entry point for prediction
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
└── LICENSE





## 🔍 Exploratory Data Analysis (EDA)

The EDA notebook includes:

- Missing value analysis
- Correlation heatmap
- Target distribution
- Categorical variable encoding
- Outlier detection (box plots)
- Class imbalance visualization

---

## 🛠️ Modeling Techniques

- **Logistic Regression**
- **Random Forest Classifier**
- **XGBoost Classifier**
- **Hyperparameter Tuning** with GridSearchCV
- **Cross-validation** to avoid overfitting

---

## 🧠 Feature Engineering

- Label encoding and One-Hot Encoding
- Imputation of missing values
- Creation of debt-to-income ratio
- Binning of income and age
- Feature scaling using StandardScaler



## 📊 Evaluation Metrics

- Accuracy
- Precision / Recall
- F1-score
- ROC-AUC score
- Confusion Matrix
- Classification Report

> Best model achieved an **ROC-AUC score of 0.89** and **accuracy of 86%** on the test set.



## 🚀 How to Run the Project

1. **Clone the repository**

```bash
git clone https://github.com/vinaybabu2112/credit_risk_modelling.git
cd credit_risk_modelling
````

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the Jupyter Notebook**

```bash
jupyter notebook notebooks/credit_risk_modeling.ipynb
```

4. **Use the model to predict**

```bash
streamlit run main.py 
```




## 📦 Requirements

* Python 3.7+
* scikit-learn
* pandas
* numpy
* matplotlib
* seaborn
* xgboost
* streamlit


## 🧭 Future Improvements

* Integrate Streamlit or Flask app for user input
* Use SHAP/LIME for explainability
* Automate model retraining with new data
* Try ensemble models or neural networks



## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

## 🙌 Acknowledgments

* Inspired by [Codebasics ML Projects](https://github.com/codebasics/)
* Data sourced from Kaggle and public loan datasets
* Credit to Dhaval Patel & the Codebasics community for guidance

---

## 👤 Author

**Vinay Babu Muttireddy**
🔗 [GitHub](https://github.com/vinaybabu2112)

---

> ⭐ If you found this helpful, give it a star and share with fellow data scientists!

