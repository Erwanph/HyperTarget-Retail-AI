# 🚀 HyperTarget Retail AI: Customer Conversion Engine

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Stacking%20Ensemble-CatBoost%20%7C%20XGBoost%20%7C%20LightGBM-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Achievement-FIND%20IT!%202024%20Finalist-success?style=for-the-badge)

> **Team Hustler** - FIND IT! 2024 Data Analytics Competition  
> *"Turning raw customer data into actionable revenue strategies through Stacking Ensemble Learning."*

---

## 🎯 At a Glance

**HyperTarget Retail AI** is an intelligent marketing engine designed to solve the "Hit-or-Miss" problem in retail promotions. By leveraging advanced **Ensemble Machine Learning** and **Behavioral Analytics**, this system predicts *exactly* which customers will respond to which campaign, maximizing conversion rates and minimizing marketing waste.

![Project Poster](./Poster_Hustler.jpg)

---

## 💼 Why This Matters? (The Business Value)

In a competitive retail landscape, generic marketing is dead. This project delivers:
1.  **Precision Targeting**: Stop spamming. Start targeting. We identify high-probability leads for specific campaigns.
2.  **Revenue Optimization**: By focusing on high-value segments (e.g., "Meat Lovers"), businesses can drive significantly higher ROI.
3.  **Data-Driven Decisions**: Transforming "gut feeling" marketing into mathematically backed strategies.

---

## 🛠️ The Technology Stack

We didn't just run a model; we engineered a solution.

*   **Core Engine**: Python (Pandas, NumPy, Scikit-Learn)
*   **The Brains (Algorithms)**:
    *   ⚡ **XGBoost & LightGBM**: For speed and efficiency.
    *   🐱 **CatBoost**: For handling categorical data like a pro.
    *   🏗️ **Stacking Classifier**: The secret sauce—combining all models to beat individual performance.
*   **Optimization**: **Optuna** (Hyperparameter Tuning) ensures the model runs at peak performance.
*   **Data Handling**: **Iterative Imputer** & **Robust Scaler** for industrial-grade data cleaning.

---

## 📊 Performance Highlights

Our Stacking Ensemble model outperforms traditional approaches, proving that *collaboration* (between algorithms) wins.

| Metric | Score | Impact |
| :--- | :--- | :--- |
| **Accuracy** | **79%** | Reliable predictions across diverse customer bases. |
| **F1-Macro** | **81%** | Balanced performance, even on rare/niche campaigns. |
| **Recall (High Value)** | **>90%** | We rarely miss the big spenders (Class 4 & 5). |

> *Key Insight: The model successfully identified that "Spending on Meat" is the strongest proxy for Wealth and Promo Acceptance.* 🥩💰

---

## 🔍 Deep Dive: Methodology

### 1. Advanced Feature Engineering
We engineered features that tell a story:
*   **`Income_Quantile`**: Segmenting users into economic classes dynamically.
*   **`Spending_Ratio`**: Understanding wallet share (e.g., "How much of their income goes to Fruit vs Meat?").
*   **Polynomial Interactions**: Capturing complex, non-linear relationships between Age and Spending Power.

### 2. Strategic Modeling
Instead of relying on one algorithm, we used a **Stacking Classifier**. Think of it as a "Committee of Experts"—where XGBoost, CatBoost, and Random Forest vote, and a Logistic Regression (Meta-Learner) makes the final, most accurate decision.

---

## 📂 Repository Structure

├── Hustler_Erwan-Poltak-Halomoan.ipynb # 🧠 The Code (Notebook)
├── Report_Hustler.pdf # 📄 Full Technical Report
├── Poster_Hustler.jpg # 🎨 Visual Summary
└── README.md # 📖 This file

---

## 👥 The Architects (Team Hustler)

Developed with precision by **Team Hustler** for the FIND IT! 2024 Competition.

*   **Erwan Poltak Halomoan**
*   **Mohamad Maulana Firdaus Ramadhan**
*   **Viktor Arsindiantoro Siringoringo**

*Institut Teknologi Bandung (ITB)*

---

*Ready to see the code? Dive into the [Jupyter Notebook](./Hustler_Erwan-Poltak-Halomoan.ipynb) or read the full [Case Study](./Report_Hustler.pdf).*
