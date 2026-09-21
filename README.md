Customer Churn Risk & Retention Analytics

AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026

Project Overview

This project analyzes customer churn using the IBM Telco Customer Churn dataset downloaded from Kaggle. It combines exploratory data analysis, business KPIs, Logistic Regression and customer risk segmentation.

The objective is to convert customer data into meaningful insights that can support retention analysis.

Problem Statement

Customer churn can affect recurring revenue and customer relationships. This project identifies churn patterns and estimates customer-level churn probability so that high-risk groups can be prioritized for further investigation.

Dataset

IBM Telco Customer Churn Dataset

Kaggle:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Technologies

Python

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Logistic Regression

Project Workflow

Raw Data
→ Data Cleaning
→ Exploratory Data Analysis
→ KPIs
→ Churn Driver Analysis
→ Logistic Regression
→ Model Evaluation
→ Risk Segmentation
→ Revenue-at-Risk Analysis
→ Business Insights
→ Retention Actions

Actual Dataset Results

KPI

Value

Total Customers

7,043

Churned Customers

1,869

Churn Rate

26.54%

Average Monthly Charges

64.76

Total Monthly Charges

456,116.60

Model

Algorithm: Logistic Regression

Actual evaluation results

Metric

Score

Accuracy

0.7381

Precision

0.5043

Recall

0.7834

F1 Score

0.6136

ROC-AUC

0.8413

Risk Segmentation

Risk Tier

Customers

Low

3,254

Medium

1,703

High

2,086

Risk thresholds used in this project:

Low: probability < 35%

Medium: 35%–65%

High: > 65%

These thresholds are project-defined for customer segmentation.

Revenue at Risk

The project classified 2,086 customers as High Risk.

Monthly charges associated with these high-risk customers:

164,795.80

Key Observed Insights

Overall observed churn rate: 26.54%

Month-to-month contract: 42.71% observed churn

Fiber optic internet service: 41.89% observed churn

Electronic check payment method: 45.29% observed churn

These are observed associations in the dataset and should not be interpreted as causal effects without further analysis.

Possible Business Actions

Prioritize high-risk customers for retention outreach.

Investigate customer experience among month-to-month contract customers.

Review service-related issues in high-churn service segments.

Investigate payment experience for electronic-check customers.

Measure churn after retention interventions.

How to Run

1. Install dependencies

pip install -r requirements.txt

2. Open the notebook

Open:

Niharika_Tiwari_Customer_Churn_Retention_Analytics.ipynb

3. Set the dataset path

In the dataset-loading cell, replace the example path with the path to your downloaded CSV:

DATASET_PATH = r"C:\Users\YourName\Downloads\Telco-Customer-Churn.csv"

4. Run cells sequentially

Run every cell from top to bottom.

The notebook includes a final verification cell.

Project Files

Niharika_Tiwari_Customer_Churn_Retention_Analytics.ipynb — complete executable project

requirements.txt — Python dependencies

Niharika_Tiwari_Customer_Churn_Retention_Analytics_ProjectReport.docx — project report

README.md — project overview and setup instructions