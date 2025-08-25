# 📊 Credit Risk Prediction using Machine Learning

## 📌 Overview
This project predicts whether a loan applicant is likely to be approved or rejected (credit risk prediction) based on demographic, financial, and credit history attributes.

We perform data preprocessing, exploratory analysis, and build multiple machine learning models (Logistic Regression, Decision Tree, Random Forest) to classify loan applications. The models are evaluated using accuracy, confusion matrix, and ROC-AUC score.

The project concludes with feature importance analysis to understand which factors contribute most to loan approval decisions, providing business insights useful for financial institutions to minimize loan defaults and improve decision-making.

---

## 📂 Project Structure
```
credit-risk-prediction-ml/
│── Credit Risk Project.ipynb   # Main Jupyter Notebook
│── CreditRisk.csv              # Dataset (not uploaded if private)
│── README.md                   # Project documentation
│── requirements.txt             # Dependencies (optional)
```

---

## ⚙️ Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-risk-prediction-ml.git
   cd credit-risk-prediction-ml
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook "Credit Risk Project.ipynb"
   ```

---

## 📊 Results

- **Logistic Regression**: Accuracy ~ **88%**
- **Decision Tree**: Accuracy ~ **77%**
- **Random Forest**: Accuracy ~ **88%**

Random Forest provided the best balance of precision, recall, and F1-score.  
Feature importance analysis highlighted **Credit_History, ApplicantIncome, LoanAmount, and Education** as key predictors.

---

## 🚀 Future Work
- Implement advanced models (XGBoost, LightGBM).
- Perform hyperparameter tuning for better optimization.
- Explore cross-validation for more robust evaluation.
- Deploy model as a simple API or web app.

---

## 🏁 Conclusion
This project demonstrates how machine learning can be applied to credit risk analysis. By leveraging models like Random Forest and Logistic Regression, financial institutions can make faster, data-driven decisions to reduce loan default risk and improve customer targeting.
