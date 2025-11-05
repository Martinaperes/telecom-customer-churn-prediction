#  Customer Churn Prediction for a Telecom Company
## 📘 Project Overview
This project focuses on predicting **customer churn** in a telecom company using **machine learning** techniques.  
Customer churn refers to when customers stop using a company’s services. By predicting churn early, telecom companies can implement retention strategies to minimize customer loss and improve long-term profitability.

This project was developed as a **capstone project** using data from Kaggle:  
👉 [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
[View my Kaggle notebook here](https://www.kaggle.com/code/perismartina/customer-churn-prediction-for-a-telecom-company)
---

## 🎯 Objectives
- Analyze telecom customer data to understand churn patterns.
- Identify **key factors** influencing customer churn.
- Build and evaluate multiple **machine learning models** to predict churn.
- Recommend actionable **business strategies** for churn reduction.

---

##  Tools and Libraries Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Scikit-learn** (Logistic Regression, SVM, Decision Tree, Random Forest)
- **Kaggle Notebook**
- **Plotly / Seaborn** for visualization

---

##  Steps Followed

### 1. Data Preparation & EDA
- Loaded and explored the Telco Customer Churn dataset.
- Handled missing and inconsistent values (e.g., `TotalCharges` column).
- Performed **Exploratory Data Analysis (EDA)** to identify patterns and correlations.
- Visualized churn distribution and relationships between features (e.g., tenure, contract type, payment method).

### 2. Feature Engineering
- Encoded categorical variables using `get_dummies()`.
- Scaled numerical features.
- Split the dataset into training and testing sets using `train_test_split()`.

### 3. Model Training
Trained four classification models:
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Decision Tree Classifier**
- **Random Forest Classifier**

### 4. Model Evaluation
Evaluated models using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **Confusion Matrix**

| Model | Accuracy | Precision | Recall | F1-Score |
|--------|-----------|------------|---------|----------|
| Logistic Regression | 0.80 | 0.66 | 0.55 | 0.60 |
| SVM | 0.79 | 0.64 | 0.52 | 0.57 |
| Decision Tree | 0.74 | 0.50 | 0.47 | 0.49 |
| Random Forest | 0.79 | 0.65 | 0.49 | 0.55 |

✅ **Best Model:** Logistic Regression (most balanced and interpretable)

---

## 🔍 Key Insights
- Short-term (month-to-month) contracts and high monthly charges strongly influence churn.
- Customers paying via **electronic check** are more likely to churn.
- New customers (low tenure) are more likely to leave than long-term customers.

---

## 💡 Recommendations
- Offer **loyalty rewards** for customers on month-to-month contracts.
- Introduce **discounts or flexible plans** for high-bill customers.
- Encourage **auto-pay options** to reduce churn from payment inconvenience.
- Focus on **early customer engagement** and service quality improvements.

---

## 📈 Results
- The final Logistic Regression model achieved **80% accuracy**.
- It effectively balances precision and recall for churn prediction.
- The model provides a foundation for proactive customer retention strategies.

---

## 🚀 How to Run This Project Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Martinaperes/telecom-churn-prediction.git
