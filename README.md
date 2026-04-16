# 🧠 Customer Churn Prediction System

## 📌 Overview

This project is a Machine Learning-based system that predicts whether a customer will **churn (leave)** or **stay** with a company.
It not only provides predictions but also delivers **probability scores, risk levels, feature importance, and business recommendations**, making it useful for real-world decision-making.

---

## 🚀 Features

* 🔍 Predicts customer churn (Yes/No)
* 📊 Displays churn probability (%)
* 🎯 Classifies customers into:

  * High Risk 🔴
  * Medium Risk 🟡
  * Low Risk 🟢
* 💡 Provides actionable business recommendations
* 📈 Data visualization (Churn distribution, Age, Balance)
* 🧠 Feature importance analysis (Random Forest)
* 🤖 Uses best-performing ML model (Random Forest)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Joblib

---

## 📂 Project Structure

```
├── customer_churn_prediction.ipynb
├── Churn_Modelling.csv
├── rf_model.pkl
├── dt_model.pkl
├── knn_model.pkl
├── lr_model.pkl
├── svc_model.pkl
└── README.md
```

---

## ⚙️ How to Run

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction
```

### 2️⃣ Install dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib
```

### 3️⃣ Run the notebook or script

```bash
python your_script.py
```

OR open in Google Colab / Jupyter Notebook.

---

## 📊 Sample Input

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

## 📈 Output Example

```
Prediction: Customer Will Churn
Churn Probability: 82.45%
Risk Level: High Risk 🔴

Recommended Actions:
- Re-engage inactive customer
- Offer discounts or loyalty rewards
- Cross-sell products
```

---

## 🧠 Machine Learning Models Used

* Logistic Regression
* Decision Tree
* Random Forest (Best Model)
* K-Nearest Neighbors
* Support Vector Machine

---

## 💡 Business Insights

* Customers with **low activity** are more likely to churn
* Customers with **fewer products** show higher churn
* Customers with **low credit score** are high-risk
* Geography also influences churn behavior

---

## 🔥 Key Highlight

This project goes beyond prediction by providing:

* Probability-based risk analysis
* Actionable business strategies
* Model interpretability

---

## 🎯 Future Improvements

* Web-based UI using Streamlit
* Real-time prediction API
* SHAP-based explainability
* Model deployment on cloud

---

## 👨‍💻 Author

Soumya

---

## ⭐ Acknowledgment

Dataset inspired by real-world banking churn scenarios (Kaggle).

---

## 📢 Final Note

> This project demonstrates how machine learning can be applied not just for prediction, but also for **decision support in business environments**.
