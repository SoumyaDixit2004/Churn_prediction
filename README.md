# 📊 Customer Churn Prediction

## 📌 Overview

This project focuses on predicting customer churn using machine learning techniques.
It analyzes customer attributes such as credit score, age, balance, and activity status to determine whether a customer will **churn** or **stay**.

Along with prediction, the system provides **probability scores, risk classification, feature importance, and business recommendations**.

---

## 🎯 Objectives

* Predict customer churn accurately
* Identify key factors influencing churn
* Provide actionable business insights
* Build a decision-support system

---

## 🚀 Features

* 🔍 Churn prediction (Churn / Stay)
* 📊 Churn probability estimation
* 🎯 Risk level classification:

  * 🔴 High Risk
  * 🟡 Medium Risk
  * 🟢 Low Risk
* 💡 Business recommendations
* 📈 Data visualization
* 🧠 Feature importance analysis

---

## 📂 Dataset

The project uses the **Churn Modelling dataset** with features:

* CreditScore
* Geography
* Gender
* Age
* Tenure
* Balance
* NumOfProducts
* HasCrCard
* IsActiveMember
* EstimatedSalary
* Exited (Target)

---

## 🤖 Machine Learning Models

* Logistic Regression
* Decision Tree
* Random Forest ⭐ (Best Model)
* K-Nearest Neighbors
* Support Vector Machine

---

## 🔄 Workflow

1. Data Loading & Exploration
2. Data Preprocessing & Encoding
3. Model Training (multiple algorithms)
4. Model Evaluation & Comparison
5. Best Model Selection
6. Prediction on new data
7. Probability & Risk Analysis
8. Recommendation Generation

---

## ⚙️ How to Run

1️⃣ Open in Google Colab or Jupyter Notebook

2️⃣ Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib
```

3️⃣ Upload required files:

* Churn_Modelling.csv
* Model files (.pkl)

4️⃣ Run all cells

---

## 📥 Sample Input

```
CreditScore: 350
Geography: 1
Gender: 0
Age: 65
Tenure: 0
Balance: 200000
NumOfProducts: 1
HasCrCard: 0
IsActiveMember: 0
EstimatedSalary: 20000
```

---

## 📤 Sample Output

```
Prediction: Customer Will Churn
Churn Probability: 82.45%
Risk Level: High Risk 🔴

Recommended Actions:
- Re-engage inactive customer
- Offer discounts or loyalty rewards
- Cross-sell additional products
```

---

## 💡 Business Insights

* Customers with low activity are more likely to churn
* Customers with fewer products have higher churn rates
* Low credit score indicates higher risk
* Geography influences churn patterns

---

## 🔮 Future Improvements

* 🌐 Build a Streamlit web app
* 📊 Add SHAP explainability
* ☁️ Deploy on cloud platforms
* ⚡ Optimize model performance

---

## 👨‍💻 Author

Soumya

---

## 📢 Conclusion

This project demonstrates how machine learning can be applied not only for prediction but also for **decision-making and customer retention strategies**.
