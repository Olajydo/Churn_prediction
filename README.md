# 🧠 Customer Churn Prediction

## 📌 Project Summary  
This project predicts whether a telecom customer will churn (i.e., leave the service). By identifying at-risk customers, the business can take proactive steps to retain them and reduce revenue loss.

---

## 📊 Data Insights  
From the exploratory data analysis (EDA), key findings include:

- Customers on **month-to-month contracts** are more likely to churn.
- **Higher monthly charges** correlate with higher churn rates.
- **New customers** (tenure < 6 months) are at greater risk of leaving.
- Customers without **online security** or **tech support** churn more often.
- Those using **electronic checks** as payment method show the highest churn.
- **Senior citizens** exhibit slightly higher churn rates.
- Customers with **dependents** are less likely to churn.

---

## 🤖 Model Development

### Models Compared:
- Random Forest  
- XGBoost  
- **Stochastic Gradient Descent (SGDClassifier)** ✅

### Model Evaluation:
Cross-validation was used to assess the models. The **SGDClassifier** performed best with an initial accuracy of **0.7984**. After hyperparameter tuning, the model's accuracy improved slightly to **0.7991**.

---

## 🧩 Key Features Used
- `Contract`, `MonthlyCharges`, `tenure`, `InternetService`, `PaymentMethod`  
- `OnlineSecurity`, `TechSupport`, `SeniorCitizen`, `Dependents`

---

## 📈 Business Recommendations
- Promote **long-term contracts** to lower churn rates.
- Offer **early retention incentives** to new users within their first 6 months.
- Bundle **security and support services** to increase customer stickiness.
- Target **electronic check users** with engagement or retention campaigns.

---

