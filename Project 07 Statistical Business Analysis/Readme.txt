# 📊 Statistical Business Analysis using Python

A complete statistical analysis project using Python to analyze sales and customer churn datasets.
This project demonstrates descriptive statistics, hypothesis testing, correlation analysis, confidence intervals, regression analysis, and business insights generation.

---

# 🚀 Project Overview

This project focuses on applying statistical techniques to real business datasets in order to:

* Analyze sales performance
* Understand customer behavior
* Discover relationships between variables
* Perform statistical hypothesis testing
* Build predictive regression models
* Generate actionable business insights

The project uses:

* `sales_data.csv`
* `customer_churn.csv`

---

# 🎯 Project Objectives

✔ Calculate descriptive statistics
✔ Analyze data distributions
✔ Perform correlation analysis
✔ Conduct hypothesis testing
✔ Calculate confidence intervals
✔ Perform regression analysis
✔ Generate business insights and recommendations

---

# 🛠 Technologies Used

| Technology                 | Purpose                   |
| -------------------------- | ------------------------- |
| Python                     | Programming Language      |
| Pandas                     | Data Manipulation         |
| NumPy                      | Numerical Calculations    |
| Matplotlib                 | Data Visualization        |
| Seaborn                    | Statistical Visualization |
| SciPy                      | Statistical Testing       |
| Scikit-learn               | Regression Analysis       |
| Jupyter Notebook / VS Code | Development Environment   |

---

# 📂 Project Structure

```text
Project 07: Statistical_Business_Analysis/
│
├── CSV Files
|	├── Sales_Data.csv
|	└── customer_churn.csv
├── Main Code/
│     ├── Project_07_Statistical_Business_Analysis.py
│     └── Project_07_Statistical_Business_Analysis.ipynb
├── Statistical_Business_Analysis_Report.pdf
├── requirements.txt
├── hypothesis_tests_results.txt
├── README.md
└── screenshots/
      ├── Code
      ├── Output
      └── Visualization

```

---

# ⚙️ Setup and Installation Guide

## Step 1: Install Python

Download Python from the official website:

[https://www.python.org/downloads/](https://www.python.org/downloads/)

### Important:

During installation, check:

```text
✔ Add Python to PATH
```

Then click:

```text
Install Now
```

---

## Step 2: Install Git

Download Git from:

[https://git-scm.com/downloads](https://git-scm.com/downloads)

Install using default settings.

---

## Step 3: Clone the Repository

Open Command Prompt / PowerShell / VS Code Terminal:

```bash
git clone https://github.com/your-username/Statistical_Business_Analysis.git
```

Move into the project folder:

```bash
cd Project 07: Statistical_Business_Analysis
```

---

## Step 4: Create Virtual Environment

### Windows

```bash
python -m venv venv
```

Activate virtual environment:

```bash
venv\Scripts\activate
```

### Mac/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## Step 5: Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## Step 6: Run the Project

```bash
Project 07: Statistical_Business_Analysis.py
Project 07: Statistical_Business_Analysis.ipynb
```

---

# 📦 Requirements

Create a `requirements.txt` file with:

```text
pandas
numpy
matplotlib
seaborn
scipy
scikit-learn
python-docx
```

---

# 📊 Features Implemented

## 1. Descriptive Statistics

Calculated:

* Mean
* Median
* Mode
* Standard Deviation
* Minimum & Maximum values

---

## 2. Data Distribution Analysis

Performed:

* Histogram visualization
* Shapiro-Wilk normality test

---

## 3. Correlation Analysis

Implemented:

* Pearson correlation coefficient
* Correlation matrix
* Heatmap visualization

---

## 4. Hypothesis Testing

Performed 3 statistical tests:

### ✔ Independent T-Test

Compared sales between East and West regions.

### ✔ One Sample T-Test

Compared monthly charges with a reference value.

### ✔ ANOVA Test

Compared product sales performance.

---

## 5. Confidence Interval Calculation

Calculated:

* 95% Confidence Interval
* Margin of Error

---

## 6. Regression Analysis

Implemented:

* Linear Regression
* Prediction model
* R-squared calculation

---

# 📈 Sample Output

```text
STATISTICAL ANALYSIS REPORT
-----------------------------------
Average Sales: 145230.45
95% Confidence Interval: (132400.11, 158060.79)
Correlation (Quantity vs Total Sales): 0.81
Marketing affects sales: p = 0.0012 ✓ SIGNIFICANT
Regression R-squared: 0.66
```

---

# 📷 Screenshots

## At Screenshots folder

# 🧪 Testing Evidence

## Test Case 1: Dataset Loading Validation

✔ Passed

```python
print(sales_df.shape)
print(churn_df.shape)
```

---

## Test Case 2: Correlation Analysis Validation

✔ Passed

```python
sales_df.corr()
```

---

## Test Case 3: Hypothesis Testing Validation

✔ Passed

```python
ttest_ind(east_sales, west_sales)
```

---

## Test Case 4: Regression Analysis Validation

✔ Passed

```python
model.fit(X, y)
```

---

# 🧠 Key Insights

* Quantity sold strongly impacts total sales
* Product categories significantly affect sales
* Regional sales patterns exist
* Regression analysis effectively predicts sales trends

---

# 💡 Business Recommendations

### ✔ Focus on High-Performing Products

Allocate more marketing budget to products generating higher sales.

### ✔ Create Region-Specific Strategies

Different regions show varying sales behavior.

### ✔ Improve Inventory Planning

Use predictive analysis for stock forecasting.

### ✔ Monitor Customer Pricing

Optimize pricing strategies to reduce customer churn.

---

# 🔍 Technical Details

## Algorithms Used

| Algorithm              | Purpose               |
| ---------------------- | --------------------- |
| Descriptive Statistics | Data Summary          |
| Pearson Correlation    | Relationship Analysis |
| T-Test                 | Mean Comparison       |
| ANOVA                  | Group Comparison      |
| Confidence Interval    | Population Estimation |
| Linear Regression      | Predictive Modeling   |

---

# 🏗 Architecture Flow

```text
CSV Files
   ↓
Data Loading
   ↓
Data Cleaning & Preparation
   ↓
Statistical Analysis
   ↓
Visualization
   ↓
Hypothesis Testing
   ↓
Regression Analysis
   ↓
Business Insights
   ↓
Final Report Generation
```

---

# 🚧 Challenges Faced

* Understanding statistical assumptions
* Selecting appropriate hypothesis tests
* Interpreting p-values
* Visualizing correlations effectively
* Understanding regression metrics

---

# 🔮 Future Improvements

Possible future enhancements:

* Power BI Dashboard Integration
* Advanced Machine Learning Models
* Time Series Forecasting
* Customer Segmentation Analysis
* Interactive Dashboards

---

# ✅ Conclusion

This project demonstrates a complete statistical business analysis workflow using Python.

The project successfully covers:

✔ Statistical Analysis
✔ Data Visualization
✔ Hypothesis Testing
✔ Confidence Interval Calculation
✔ Regression Analysis
✔ Business Insights Generation
---

# 👨‍💻 Author

MD AFROZ ANSARI

AI-Enabled Data Analyst | Python | SQL | Power BI | Statistics | Gen AI

GitHub: [https://github.com/Afroz13](https://github.com/Afroz13)

LinkedIn: [https://www.linkedin.com/in/md-afroz-ansari380400195/](https://www.linkedin.com/in/md-afroz-ansari380400195/)
