# Customer Churn Analysis & Retention Strategy

## Project Overview

This project focuses on analyzing customer churn behavior using data analytics and machine learning techniques. The goal of the project is to identify the major factors influencing customer churn and provide actionable business recommendations to improve customer retention.

The project includes:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Predictive Modeling
- Business Recommendations
- Professional Visualizations

---

# Business Problem

Customer churn directly affects business revenue and long-term growth. The company wanted to understand:

- Why customers are leaving
- Which customers are most likely to churn
- How the business can improve customer retention

This project aims to solve these challenges using data-driven analysis.

---

# Dataset Information

The dataset contains customer-related information such as:

- CustomerID
- Tenure
- MonthlyCharges
- TotalCharges
- Contract
- PaymentMethod
- PaperlessBilling
- SeniorCitizen
- Churn

Dataset size:
- 500+ rows

---

# Project Structure

```bash
customer-churn-business-analysis/

│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   ├── 1_data_cleaning.ipynb
│   ├── 2_eda.ipynb
│   └── 3_analysis.ipynb
│
├── reports/
│   ├── executive_summary.pdf
│   └── technical_report.pdf
│
├── presentations/
│   └── business_presentation.pptx
│
├── dashboard/
│   └── churn_dashboard.pbix
│
├── portfolio/
│   └── portfolio_case_study.md
│
├── requirements.txt
│
└── README.md

# Technologies Used

1. Technology		Purpose
2. Python		Data Analysis
3. Pandas		Data Manipulation
4. NumPy		Numerical Operations
5. Matplotlib		Visualization
6. Seaborn		Statistical Visualization
7. cikit-learn		Machine Learning


# Data Cleaning Process

## The following preprocessing steps were performed:

Dataset loading
Data inspection
Missing value verification
Duplicate removal
Data type validation
Outlier analysis
Cleaned dataset generation
Exploratory Data Analysis (EDA)

## EDA was conducted to identify trends and patterns related to customer churn.

Key Visualizations
Customer churn distribution
Correlation heatmap
Tenure vs churn
Monthly charges vs churn
Contract type analysis
Payment method analysis
Feature importance visualization

# Key Insights

1. Customer Tenure Strongly Impacts Churn

Customers with shorter tenure are significantly more likely to churn.

2. Contract Type Influences Retention

Long-term contracts improve customer retention rates.

3. Higher Monthly Charges Increase Churn Risk

Customers with relatively higher monthly charges show increased churn probability.

4. Predictive Modeling Identified Important Churn Drivers

Logistic Regression successfully identified important customer risk factors.


# Machine Learning Model

## Model Used

-Logistic Regression

## Workflow
-Data preprocessing
-Feature encoding
-Train-test split
-Model training
-Prediction
-Model evaluation

## Evaluation Techniques

-Accuracy Score
-Classification Report
-Confusion Matrix


# Business Recommendations

- Introduce loyalty programs for new customers.
- Encourage long-term subscriptions through discounts.
- Improve onboarding experience for first-time users.
- Create retention campaigns for high-risk customers.
- Use predictive analytics for proactive churn prevention.

# Expected Business Impact

## The proposed strategies can help the business:

- Reduce customer churn
- Improve customer satisfaction
- Increase customer retention
- Improve revenue stability


# How to Run the Project
1. Clone Repository
git clone <your-github-repository-link>
2. Install Requirements
pip install -r requirements.txt
3. Run Jupyter Notebook
jupyter notebook


#Requirements

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter


# Future Improvements

Power BI Dashboard
Streamlit Web App
Advanced Machine Learning Models
Customer Segmentation
Real-time Churn Prediction System


# Author

- MD Afroz Ansari
  Data Analyst
  Python | SQL | Power BI | Machine Learning