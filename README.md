# AI-Powered Customer Churn & Retention Analytics

An end-to-end customer churn analytics project combining **Python, SQL, Machine Learning, and Power BI** to analyze customer behavior, identify high-risk customer segments, and predict customer churn.

## 📌 Project Overview

Customer churn is an important business problem because losing existing customers can directly affect revenue and long-term growth.

This project analyzes customer data to understand:

- Which customer segments have higher churn rates
- How tenure, usage, services, and subscription type relate to churn
- Which customers can be considered high-risk
- How machine learning can be used to predict customer churn
- How the analysis can be presented through an interactive Power BI dashboard

The project contains both **exploratory/business analysis** and a **machine learning churn prediction model**.

---

## 📊 Dataset

The dataset contains **5,000 customer records** and the following attributes:

- Customer ID
- Age
- Gender
- Location
- Tenure (Months)
- Subscription Type
- Monthly Charges
- Usage Hours
- Support Tickets
- Payment Method
- Number of Services
- Churn

### Churn Distribution

- Total Customers: **5,000**
- Non-Churned Customers: **4,791**
- Churned Customers: **209**
- Overall Churn Rate: **4.18%**

---

## 🔍 Data Analysis

The data was analyzed using Python and SQL to identify important churn patterns.

### Analysis Performed

- Data cleaning and validation
- Churn distribution analysis
- Customer segmentation
- Tenure group analysis
- Usage group analysis
- Subscription type analysis
- Location-wise churn analysis
- Support ticket analysis
- Monthly charge analysis
- Number of services analysis
- High-risk customer segmentation
- Multi-factor churn analysis

### High-Risk Segment

Customers were analyzed based on combinations of:

- Tenure
- Usage
- Number of services

This helped identify customer segments with comparatively higher churn rates.

---

## 🤖 Machine Learning

A **Logistic Regression** classification model was developed to predict customer churn.

### Machine Learning Workflow

1. Selected customer attributes as input features
2. Separated `Churn` as the target variable
3. Converted categorical variables using one-hot encoding
4. Split the dataset into training and testing data
5. Trained a Logistic Regression model
6. Used class balancing to address churn class imbalance
7. Generated churn predictions
8. Evaluated predictions using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix

### Model Result

The generated predictions on the complete dataset produced:

| Metric | Result |
|---|---:|
| Accuracy | 98.58% |
| Precision | 84.50% |
| Recall | 80.86% |
| F1-Score | 82.64% |

> **Note:** These metrics were calculated from predictions generated across the complete dataset after model training. They should not be interpreted as an independent held-out test-set performance.

---

## 📈 Power BI Dashboard

An interactive Power BI dashboard was created to provide a visual view of customer churn and retention patterns.

### Dashboard Includes

- Total Customers
- Churned Customers
- Overall Churn Rate
- High-Risk Customers
- High-Risk Churn Rate
- Churn Rate by Subscription Type
- Churn Rate by Location
- Churn Rate by Tenure Group
- Churn Rate by Usage Group
- Customer segmentation analysis
- High-risk vs overall churn comparison

The dashboard is designed to help users quickly identify customer segments that may require retention attention.

---

## 🛠️ Tools & Technologies

### Programming & Analysis
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Database / Querying
- SQL
- MySQL

### Machine Learning
- Scikit-learn
- Logistic Regression

### Visualization
- Microsoft Power BI

### Development
- Jupyter Notebook
- Git
- GitHub

---

## 📁 Project Structure

```text
AI-Powered-Customer-Churn-Retention-Analytics/
│
├── Customer_Churn_EDA.ipynb
├── Customer_Churn_ML.ipynb
├── Customer_Churn_Analytics.pbix
└── README.md
