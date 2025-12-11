# 📉 Customer Churn Analytics: End-to-End EDA

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Libraries](https://img.shields.io/badge/Library-Pandas%20%7C%20Seaborn%20%7C%20Matplotlib-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📖 Project Overview
Customer churn is a critical metric for businesses, especially in the telecommunications sector. This project performs an **End-to-End Exploratory Data Analysis (EDA)** on a Telco Customer Churn dataset to understand the demographic and service-related patterns of customers who leave the service.

The goal is to provide actionable insights that can help in retention strategies by visualizing correlations between customer attributes and churn rates.

## 1. Project Overview

Customer churn is one of the most important business problems across telecom, banking, SaaS, insurance, and e-commerce.
The goal of this project is to:

✔ Analyze customer behavior
✔ Identify churn drivers
✔ Build a predictive churn model (Logistic Regression, Random Forest, XGBoost, etc.)
✔ Deploy the model using cloud or big-data platforms
✔ Provide data-driven retention strategies

The workflow covers data ingestion → preprocessing → EDA → feature engineering → modeling → evaluation → deployment.

## 2. Technologies & Tools Used Python (Primary Language)

Libraries:

pandas, numpy (Data wrangling)

scikit-learn (ML algorithms → Logistic Regression, Random Forest)

XGBoost, CatBoost, LightGBM (Advanced boosting models)

TensorFlow / PyTorch (Deep Learning experiments)

Matplotlib, Seaborn, Plotly (Visualizations)

Imbalanced-learn (SMOTE) (Handling imbalanced data)

Big Data Tools (optional for huge datasets)

Apache Spark / PySpark for distributed ML pipelines

Databricks for scalable model development

Cloud Platforms

AWS SageMaker, Azure ML, GCP AI Platform for training & deployment

Visualization & BI Tools

Tableau / Power BI dashboards for churn monitoring and KPI reporting

## 3. Dataset Overview

Typical churn dataset includes:

Feature Type	Examples
Customer Info	Age, Gender, Tenure
Account Details	Contract type, Payment type
Usage Metrics	Data usage, calls, total charges
Service Features	Internet service, support calls
Target Variable	Churn = {Yes/No}
## 4. Data Preprocessing
4.1 Missing Value Handling

Numerical → mean/median imputation

Categorical → mode imputation

Optional: KNN imputation

4.2 Encoding Categorical Variables

One-hot encoding for nominal variables

Label encoding for ordinal variables

4.3 Outlier Treatment

IQR-based filtering

Winsorization

4.4 Handling Class Imbalance

SMOTE (oversampling)

Random undersampling

Hybrid methods

4.5 Feature Scaling

StandardScaler for Logistic Regression / Neural networks

Tree-based models (Random Forest, XGBoost) → scaling not necessary

## 5. Exploratory Data Analysis (EDA)
5.1 Univariate Analysis

Distribution of numerical variables

Churn rate (target imbalance check)

Missing values heatmap

5.2 Bivariate Analysis

Churn vs. Tenure (churn is high for low-tenure customers)

Churn vs. Contract type (month-to-month contracts churn more)

Churn vs. Support calls (high support calls → high churn)

5.3 Multivariate Analysis

Correlation matrix

Pairplots

Customer segmentation

RFM (Recency, Frequency, Monetary) analysis

5.4 Key Visualizations

Churn distribution

Customer demographics

Heatmap, boxplots, bar charts

Feature importance charts

## 6. Feature Engineering
6.1 Creating New Features

Tenure groups

Total usage (minutes + data + calls)

Average monthly charges

Customer engagement score

Number of complaints

RFM scores for SaaS/E-commerce datasets

6.2 Behavioral Time-Based Features

Last login days

Activity decline indicators

Usage trends (sliding windows)

6.3 Interaction Features

Contract type × tenure

Service features × satisfaction score

## 7. Model Building

The project uses several supervised ML algorithms:

7.1 Baseline Models

Logistic Regression

For interpretability

Coefficients used for churn driver analysis

Decision Tree Classifier

7.2 Advanced Models

Random Forest

Handles non-linearity

Robust feature importance

XGBoost, CatBoost, LightGBM

Best model accuracy

Handles missing values and categorical data efficiently


## 8. Model Validation
Metrics Used

Because churn datasets are imbalanced, accuracy is not reliable.

Use:

Precision

Recall (most important)

Confusion Matrix

Lift & Gain Charts

Kappa Statistic

Cross-validation

5-fold / 10-fold CV

Stratified sampling used to preserve class distribution

Hyperparameter Tuning

GridSearchCV

RandomizedSearch

Bayesian Optimization (Optuna, Hyperopt)

## 9. Model Deployment (Optional)

Real-Time Predictions

Incoming customer data from CRM (Salesforce, HubSpot)

Prediction triggers retention workflow

## 10. Business Insights from Models

✔ Customers with month-to-month contracts are most likely to churn
✔ Low tenure customers show highest churn probability
✔ High service issues (tickets/calls) strongly correlate with churn
✔ Paperless billing + monthly charges is a churn risk factor


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














