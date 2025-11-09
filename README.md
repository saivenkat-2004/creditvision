# creditvision
CreditVision: Loan Default Prediction Using Machine Learning
# CreditVision: Loan Default Prediction Using Machine Learning

This project focuses on predicting whether a borrower will **default on a loan**, based on demographic, financial, and credit history information. By analyzing borrower patterns and training a classification model, we aim to support better **credit risk assessment** and lending decisions.

---

##  Problem Statement
Financial institutions face significant risk when approving loans due to borrowers who may default. Manual evaluation of loan applications is slow, inconsistent, and may overlook key risk patterns. This project builds a **machine learning model** to classify borrowers as *likely to default* or *likely to repay*, enabling faster and more accurate credit decisions.

---

##  Objectives
- Analyze borrower characteristics and detect patterns linked to default behavior.
- Clean, preprocess, and transform dataset features.
- Perform exploratory data analysis (EDA) to understand key insights.
- Train and evaluate machine learning models for prediction.
- Identify the most impactful financial and behavioral features.

---

##  Machine Learning Pipeline

| Step | Description |
|------|-------------|
| Data Cleaning | Handle missing values, detect outliers, correct data types |
| Feature Engineering | Scaling numeric features, One-Hot Encoding categorical features |
| Statistical Tests | Chi-Square & ANOVA to identify significant predictors |
| Model Training | Logistic Regression, KNN, Random Forest (or others used) |
| Model Evaluation | Accuracy, Precision, Recall, F1 Score, ROC-AUC |

---

##  Key Insights from EDA
- Loan purpose (Education/Medical/Venture) shows higher default tendencies.
- Higher **loan_percent_income** correlates strongly with default.
- Credit history length plays a critical role in repayment behavior.

---

##  Technologies & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn
- Scipy Stats

---

##  How to Run the Project
```bash
git clone https://github.com/saivenkat-2004/CreditVision.git
cd CreditVision-Loan-Default-Prediction
pip install -r requirements.txt
jupyter notebook CreditVisionProjectML.ipynb
