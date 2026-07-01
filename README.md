# 📞 Telco Customer Churn Analysis & Prediction (MBA-Style)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-orange.svg)
![PowerBI](https://img.shields.io/badge/PowerBI-Latest-yellow.svg)

This project was developed as the Capstone Project for the **Advanced AI-Driven Data Analytics Program (MBA-Style)** at Orange Digital Center Egypt, in collaboration with Global Knowledge Egypt. 

**Final Grade Achieved:** **99%** 🌟

---

## 🎯 Business Problem & Objective
Customer churn is a major financial threat in the telecommunications industry. Acquiring new customers costs significantly more than retaining existing ones. 

**The Goal:** Analyze a dataset of **7,043 customers** to identify key churn drivers, build a predictive Machine Learning model to catch "at-risk" customers early, and simulate a profitable, data-driven retention strategy.

---

## 📊 Key Business Insights & Churn Drivers
From the Exploratory Data Analysis (EDA), the primary factors driving customer exit were:
1. **Contract Type:** Month-to-month contracts are the leading reason for churn, while long-term contracts create high stability.
2. **Tenure:** New customers (low tenure) are at the highest risk. Loyalty increases heavily over time.
3. **Financial Pressure:** Churned customers often have higher median monthly charges (price sensitivity).
4. **The "Safety" Factor:** Customers without **Online Security** or **Tech Support** are significantly more likely to leave. 

---

## 🤖 Machine Learning Modeling
We built and evaluated two predictive models: **Logistic Regression** and **Random Forest**.

*   **The Decision:** We prioritized **Recall** over overall accuracy because the business cost of missing a customer who will churn is much higher than wrongly flagging a loyal one.
*   **The Winner:** **Logistic Regression** performed consistently, achieving:
    *   **Accuracy:** 80%
    *   **AUC Score:** 0.84
    *   **Recall for Churn:** 57%

---

## 💰 Financial Impact & Retention Strategy
Instead of traditional reactive methods, a **Data-Driven Retention Simulation** was designed:
*   **Annual Revenue at Risk:** $290,814.36
*   **Potential Savings (Targeting 30% Churn Reduction):** $87,088.79
*   **Campaign Investment:** $7,480.00
*   **Net Profit from Strategy:** **$79,608.79** 📈
*   **Break-even Point:** The campaign fully pays for itself by saving **just 10 customers**!

---

## 🛠️ Tech Stack & Tools Used
*   **Language:** Python (Pandas, NumPy)
*   **Visualization:** Matplotlib, Seaborn, Power BI
*   **Machine Learning:** Scikit-Learn (Logistic Regression, Random Forest)
*   **AI Productivity:** Prompt Engineering & LLMs for workflow acceleration

---

## 📂 Repository Structure
```text
├── Data/                 # Dataset folder (Telco Customer Churn from Kaggle)
├── Notebooks/            # Jupyter Notebooks containing Data Cleaning, EDA, and Modeling
├── Presentation/         # Executive PowerPoint Presentation
└── README.md             # Project documentation
