# 📊 Optimizing Financial Telemarketing through Predictive Modeling

> **Master's Thesis (TFM)** focused on applying data analysis and machine learning to optimize direct marketing campaigns within the Banking and Financial Services (Fintech) sector.

---

## 🛠️ Tech Stack & Libraries

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-v1.5-150458.svg?style=flat&logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-🚀-blue)

---

## 💼 Business Problem

The financial institution faces the challenge of maximizing fixed-term deposit conversions through telemarketing campaigns. The current approach suffers from three critical inefficiencies:

*   **Low operational efficiency:** Repeatedly contacting the same customer without a predictive guarantee of success.
*   **Seasonal volatility:** Inefficient concentration of outreach in specific months (e.g., over-contacting in May vs. inactivity in November).
*   **High operational costs:** Human and technical resources are not optimized based on the customer's actual propensity to buy.

**🎯 Project Objective:** To analyze historical campaign data to identify, weight (using techniques like SHAP values), and predict the key driving factors that lead a customer to subscribe to a fixed-term deposit.

---

## 📊 Dataset

*   **Source:** Private dataset provided by the Master's program (not publicly available due to confidentiality agreements).
*   **Content:** Raw and processed data integrating demographic features, customer relationship history, and macroeconomic variables.

---

## ⚙️ Methodology

The project follows a rigorous Data Science pipeline structured into the following phases:

1.  **Strategic Definition:** Establishing general business objectives, tactical approaches, and designing the KPI tree.
2.  **Environment Setup & Loading:** Preparing the Python production environment and orchestrating libraries (`Pandas`, `Seaborn`, `Plotly`, `FuzzyWuzzy`).
3.  **Exploratory Data Analysis (EDA):** Deep dive into demographic profiles, the impact of macroeconomic variables (Euribor, inflation), and operational campaign drivers.
4.  **Data Cleaning & Feature Engineering:** Automated handling of missing values, duplicate removal, outlier management, and categorical variable normalization/encoding.
5.  **Advanced KPI Analysis:**
    *   *Rate Penetration Context:* Impact of the Euribor on subscription propensity.
    *   *Conversion Elasticity:* Mathematical relationship between market fluctuations and final sales.
    *   *Recurrence Rate:* Analytical behavior of customers with a history of past successful conversions.

---

## 💡 Key Insights

*   **📈 Macro Opportunity Window:** A critical spike in conversion was detected during periods when the Euribor exceeded **4.8%**, making the product highly competitive.
*   **👤 High-Conversion Profile:** Administrative profiles with a university education show financial stability that correlates positively with long-term deposit subscriptions.
*   **🛑 Customer Fatigue (Over-contacting):** The contact frequency analysis identified the optimal threshold for calls per campaign. Beyond this limit, the probability of success drops drastically, unnecessarily driving up operational costs.

---

## 📦 Repository Deliverables

*   📁 `notebooks/` - Jupyter Notebook containing the structured code for EDA, cleaning, and modeling.
*   📁 `docs/` - Detailed technical documentation detailing the methodology and statistical justification.
*   📄 `executive_presentation.pdf` - Final presentation tailored for the Fintech's Executive Board.

---

## 🚀 How to Run

1. Clone this repository to your local machine:
```bash
   git clone [https://github.com/your-username/your-repo.git](https://github.com/your-username/your-repo.git)
