# 📞 Telco Customer Churn Analysis & Prediction (MBA-Style)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-orange.svg)
![PowerBI](https://img.shields.io/badge/PowerBI-Latest-yellow.svg)

This project was developed as the **Capstone Project** for the **Advanced AI-Driven Data Analytics (MBA-Style)** program at **Orange Digital Center Egypt**, in collaboration with **Global Knowledge Egypt**.

🎓 **Final Grade:** **99%**

---

# 🎯 Business Problem

Customer churn is one of the biggest challenges in the telecommunications industry. Acquiring new customers is significantly more expensive than retaining existing ones.

The objective of this project is to analyze customer behavior, identify the key factors that drive churn, build predictive Machine Learning models, and recommend a profitable data-driven retention strategy.

---

# 📊 Dataset

- **Dataset:** Telco Customer Churn
- **Source:** Kaggle
- **Records:** 7,043 Customers
- **Target Variable:** Churn

🔗 https://www.kaggle.com/datasets/blastchar/telco-customer-churn

---

# 🔍 Project Workflow

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Modeling
- Model Evaluation
- Business Insights
- Financial Impact Simulation
- Retention Strategy

---

# 📈 Key Business Insights

The Exploratory Data Analysis revealed several important churn drivers:

- 📌 Customers with **Month-to-Month Contracts** have the highest churn rate.
- 📌 Customers with **low Tenure** are much more likely to leave.
- 📌 Higher **Monthly Charges** increase churn probability.
- 📌 Customers without **Online Security** or **Tech Support** have significantly higher churn rates.
- 📌 **Fiber Optic** customers are more likely to churn compared to DSL customers.

---

# 🤖 Machine Learning Models

Two classification models were developed and compared:

- Logistic Regression
- Random Forest

### ✅ Best Performing Model

**Logistic Regression**

| Metric | Score |
|---------|-------|
| Accuracy | **80%** |
| AUC Score | **0.84** |
| Recall | **57%** |

> **Business Decision:**  
> Recall was prioritized over Accuracy because failing to identify a customer who is likely to churn is more costly than incorrectly flagging a loyal customer.

---

# 💰 Financial Impact

The project also evaluated the business value of implementing a retention campaign.

| Metric | Value |
|---------|---------:|
| Annual Revenue at Risk | **$290,814.36** |
| Potential Savings | **$87,088.79** |
| Campaign Cost | **$7,480.00** |
| Expected Net Profit | **$79,608.79** |

✅ The campaign reaches the **break-even point by retaining only 10 customers**, demonstrating a strong business case for proactive retention strategies.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Power BI
- Jupyter Notebook

---

# 📁 Repository Structure

```text
Customer-Churn/
│
├── Data/                 # Dataset
├── Notebooks/            # Data Cleaning, EDA & Machine Learning
├── Presentation/         # PowerPoint Presentation
├── Images/               # Charts & Screenshots
└── README.md
```

---

# 🎥 Project Presentation

📺 **Presentation Video**

https://drive.google.com/file/d/1M42nu7PUivwY5ZIQItsb1BVKIMoi9ogI/view?usp=sharing

---

# 🚀 Future Improvements

- Hyperparameter Tuning
- XGBoost & LightGBM Models
- Deployment with Streamlit
- Real-time Churn Prediction API
- Explainable AI using SHAP

---

# 👩‍💻 Author

**Mennatullah Mahmoud Saleh**

If you found this project useful, feel free to ⭐ the repository.

---
⭐ Developed with 🤍 as part of the Advanced AI-Driven Data Analytics (MBA-Style) Program at Orange Digital Center Egypt.
