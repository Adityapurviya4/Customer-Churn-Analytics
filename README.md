# Customer-Churn-Analytics
End-to-End Customer Churn Analysis using Python. A comprehensive EDA project leveraging Pandas, Seaborn, and Matplotlib to identify key factors influencing customer attrition in the telecom industry.


Customer Churn Analytics (Python)

Conducted an end-to-end Exploratory Data Analysis (EDA) on a Telco dataset containing 7,000+ rows to identify churn drivers.

Performed data cleaning and feature engineering using Pandas, handling missing data in financial columns.

Visualized customer retention patterns using Seaborn and Matplotlib, revealing that customers on month-to-month contracts churn 3x more than those on yearly plans.

Analyzed numerical distributions and correlations (Heatmaps/Boxplots) to determine the impact of tenure and monthly charges on customer lifecycle.

# 📉 Customer Churn Analytics: End-to-End EDA

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Libraries](https://img.shields.io/badge/Library-Pandas%20%7C%20Seaborn%20%7C%20Matplotlib-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📖 Project Overview
Customer churn is a critical metric for businesses, especially in the telecommunications sector. This project performs an **End-to-End Exploratory Data Analysis (EDA)** on a Telco Customer Churn dataset to understand the demographic and service-related patterns of customers who leave the service.

The goal is to provide actionable insights that can help in retention strategies by visualizing correlations between customer attributes and churn rates.

## 📂 Dataset
The dataset includes customer information such as:
* **Demographics:** Gender, Senior Citizen status, Partner, Dependents.
* **Services:** Phone, Internet (DSL/Fiber), Online Security, Streaming, etc.
* **Account Info:** Tenure, Contract Type, Payment Method.
* **Financials:** Monthly Charges, Total Charges.

## 🛠️ Tech Stack & Libraries
* **Python**
* **Pandas** (Data Manipulation)
* **NumPy** (Numerical Operations)
* **Matplotlib & Seaborn** (Data Visualization)

## 🔍 Key Steps in Analysis
1.  **Data Preprocessing:**
    * Handling missing values (specifically in `TotalCharges`).
    * Data type conversion (Object to Numeric).
    * Categorical mapping (e.g., converting SeniorCitizen 0/1 to No/Yes).
2.  **Univariate Analysis:**
    * Distribution of target variable (`Churn`).
    * Histograms for numerical features (`Tenure`, `MonthlyCharges`).
3.  **Bivariate Analysis:**
    * Churn rate by Contract Type, Payment Method, and Internet Service.
    * Impact of gender and dependents on retention.
4.  **Correlation Analysis:**
    * Heatmap visualization to find relationships between numeric variables.
    * Boxplots to detect outliers in tenure and charges.

## 📊 Key Insights
* **Contract Type:** Customers with **Month-to-Month** contracts have a significantly higher churn rate compared to One or Two-year contracts.
* **Tenure:** Newer customers (lower tenure) are more likely to churn.
* **Payment Method:** Customers paying via **Electronic Check** show the highest attrition.
* **Services:** Customers without **Online Security** or **Tech Support** tend to churn more frequently.

## 🚀 How to Run
1.  Clone the repository:
    ```bash
    git clone [https://github.com/your-username/customer-churn-analytics.git](https://github.com/your-username/customer-churn-analytics.git)
    ```
2.  Install dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  Open the notebook:
    ```bash
    jupyter notebook "Churn Analysis.ipynb"
    ```

## 📬 Contact
Created by Aditya Purviya - Feel free to contact me!














