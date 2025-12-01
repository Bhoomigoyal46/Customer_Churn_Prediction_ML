# Customer Churn Prediction ML

"Python ML project (Random Forest Classification) for customer churn prediction. Uses the advanced SMOTE technique to effectively handle data imbalance. Achieved **79.28% accuracy**. Identified TotalCharges, MonthlyCharges, and tenure as key drivers for attrition. Demonstrates end-to-end predictive modeling skills to deliver actionable insights."

---

## 🚀 Project Overview

This project focuses on predicting customer churn for a telecom company. The goal is to identify customers at high risk of leaving and determine the critical factors influencing their decision, enabling targeted retention efforts.

### 🛠️ Tools & Technologies

* **Language:** Python
* **Core Libraries:** Pandas, NumPy (Data Processing)
* **Modeling:** Scikit-learn (RandomForestClassifier)
* **Handling Imbalance:** Imbalanced-learn (SMOTE)
* **Visualization:** Matplotlib, Seaborn

### 📊 Methodology (Ask, Process, Analyze)

1.  **Data Cleaning & Preparation:** Handled missing values (e.g., in TotalCharges) and performed one-hot encoding for categorical features.
2.  **Imbalance Handling:** The dataset was highly imbalanced (Churn Rate ~16%). **SMOTE (Synthetic Minority Over-sampling Technique)** was applied to balance the classes, reducing model bias.
3.  **Model Training:** A **Random Forest Classifier** was trained and optimized, resulting in a **79.28% classification accuracy**.
4.  **Feature Importance:** Identified the top features driving the model's prediction.

---

## 💡 Key Findings & Actionable Recommendations

### Key Insights (Based on Analysis):

* **Financial Impact:** **Total Charges** and **Monthly Charges** are the strongest predictors of churn. High-value customers who pay more monthly are often the first to leave if satisfaction is low.
* **Tenure:** Customers with very **short tenure** (new customers) and those with very **long tenure** show different churn drivers, requiring segmented retention strategies.
* **Service Gaps:** Specific service offerings (e.g., Fiber Optic Internet) correlated significantly with higher churn rates.

### 📝 Action Plan (Act):

1.  **Targeted Outreach:** **Implement a predictive alerting system** to flag customers who have high Total Charges and low tenure, prioritizing them for personalized retention offers.
2.  **Service Quality:** Investigate service quality issues specifically related to **Fiber Optic Internet** to reduce dissatisfaction among the highest-risk group.
3.  **New Customer Focus:** Initiate a **proactive 30-day follow-up plan** for new customers to address early frustrations and increase early retention.

---

## 🖼️ Visualizations & Model Performance

The following visuals, created using Matplotlib and Seaborn, explain the model's performance and key insights.

* 
* 

[Image of Confusion Matrix]


**(Note: Please ensure you upload the corresponding image files into the Visualizations/ folder)**
