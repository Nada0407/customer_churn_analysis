# Customer Churn Analysis (EDA & Business Insights)

## 📌 Project Overview
This project analyzes customer churn behavior using the IBM Telco Customer Churn dataset.  
The goal is to identify key factors associated with customer churn and translate insights into actionable business recommendations.

Customer churn represents a major business risk, as acquiring new customers is significantly more expensive than retaining existing ones.

---

## 🎯 Objective
- Understand the distribution of churn
- Identify customer characteristics linked to higher churn
- Provide data-driven recommendations to reduce churn

---

## 📊 Dataset
- **Source:** IBM Telco Customer Churn dataset  
- **Rows:** ~7,000 customers  
- **Target variable:** `Churn` (Yes / No)  
- Each row represents one customer with demographic, service, contract, and payment information

---

## 🛠 Tools & Libraries
- Python
- pandas, numpy
- seaborn, matplotlib
- Jupyter Notebook

---

## 🔍 Key Analysis Steps
1. **Data Loading & Inspection**
   - Checked dataset structure, data types, and missing values

2. **Data Cleaning**
   - Converted `TotalCharges` from object to numeric
   - Removed rows with missing `TotalCharges`

3. **Exploratory Data Analysis (EDA)**
   - Churn distribution
   - Churn by gender, senior citizen status
   - Contract type vs churn
   - Monthly charges vs churn
   - Internet service and payment method impact
   - Tenure distribution by churn

4. **Insight Generation**
   - Identified churn drivers
   - Translated findings into business recommendations

---

## 📈 Key Insights
- Approximately **27% of customers churn**, indicating a significant retention problem
- **Gender has no impact** on churn
- **Senior citizens churn more** than younger customers
- **Month-to-month contracts show the highest churn**
- Higher **monthly charges** are associated with higher churn
- **Electronic check users** churn at the highest rate
- Customers with **tenure under 12 months** are most likely to churn

---

## 💡 Business Recommendations
- Incentivize customers to move from month-to-month to long-term contracts
- Introduce early-stage retention and onboarding programs
- Encourage automatic payment methods through discounts or rewards
- Monitor high-charge customers more closely

---

## 🚀 Next Steps
- Feature encoding and preprocessing
- Train churn prediction models (Logistic Regression, Random Forest)
- Evaluate recall-focused performance
- Deploy insights using Streamlit

---

## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook
