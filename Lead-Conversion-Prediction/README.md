# 📊 Lead Conversion Prediction using Machine Learning

A complete end-to-end Data Analytics and Machine Learning project that predicts whether a lead is likely to convert into a customer using historical sales and marketing data. The project also includes interactive dashboards built in **Power BI** and **Tableau** for business intelligence and decision-making.

---

## 📌 Project Overview

Companies receive thousands of leads from different marketing campaigns and channels such as websites, referrals, and social media. Identifying high-potential leads helps sales teams prioritize follow-ups, improve conversion rates, and optimize marketing efforts.

This project develops a machine learning classification model to predict lead conversion and provides interactive dashboards for analyzing lead and sales performance.

---

## 🎯 Objectives

- Clean and preprocess lead data
- Perform Exploratory Data Analysis (EDA)
- Build machine learning classification models
- Compare multiple algorithms
- Predict lead conversion probability
- Develop interactive dashboards using Power BI and Tableau
- Generate actionable business insights

---

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Power BI
- Tableau

---

## 📂 Repository Structure

```
Lead-Conversion-Prediction/
│
├── notebooks/
│   └── Lead_Conversion_Prediction.ipynb
│
├── powerbi/
│   └── Lead_Analytics_Dashboard.pbix
│
├── tableau/
│   └── Lead_Analytics_Dashboard.twbx
│
├── images/
│   ├── powerbi_dashboard.png
│   ├── tableau_dashboard.png
│   ├── roc_curve.png
│   ├── confusion_matrix.png
│   └── feature_importance.png
│
└── README.md
```

---

## 📊 Dataset

The dataset contains historical lead information, including:

- Lead Status
- Lead Tag
- Campaign Name
- Source Type
- Source Name
- Assigned Sales Executive
- First Call Attempt
- Last Call Date
- Sales
- Total Leads
- Conversion Rate (%)
- Total Cost

> **Note:** The original dataset is not included in this repository because it contains proprietary business data. Personal information was removed and the project is shared for educational and portfolio purposes.

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Removed personal information columns
- Handled missing values
- Created binary target variable (`Converted`)
- Encoded categorical variables using Label Encoding
- Removed data leakage by excluding the `lead_stage` feature
- Prepared data for machine learning models

---

## 📈 Exploratory Data Analysis

EDA was performed to understand conversion patterns and feature relationships.

Visualizations include:

- Lead Conversion Distribution
- Conversion by Source
- Conversion by Campaign
- Conversion by Lead Status
- Feature Importance Analysis

---

## 🤖 Machine Learning Models

The following classification algorithms were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest

---

## 📊 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|---------:|----------:|-------:|---------:|
| Logistic Regression | 99.65% | 88.46% | 85.19% | 86.79% |
| Decision Tree | 99.90% | 100.00% | 92.59% | 96.15% |
| Random Forest | **99.90%** | **100.00%** | **92.59%** | **96.15%** |

### ✅ Best Performing Model

**Random Forest** was selected as the final model due to its excellent performance across all evaluation metrics.

---

## 📌 Model Evaluation

Evaluation metrics used:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix
- Feature Importance

---

## 📊 Power BI Dashboard

The Power BI dashboard provides interactive insights into:

- Total Leads
- Total Sales
- Conversion Rate
- Campaign Performance
- Source Performance
- Executive Performance
- Lead Funnel Analysis
- Drillthrough and Tooltips

---

## 📈 Tableau Dashboard

The Tableau dashboard includes:

- KPI Cards
- Sales Trend
- Campaign Performance
- Source Analysis
- Executive Performance
- Lead Status Treemap
- Cost vs Sales Scatter Plot
- Interactive Filters and Dashboard Actions

---

## 💡 Business Insights

- Lead Status is the strongest predictor of conversion.
- Campaign performance varies significantly across marketing initiatives.
- Certain lead sources generate higher conversion rates than others.
- Random Forest provides highly accurate lead conversion predictions.
- Predictive models can help sales teams prioritize high-potential leads.

---

## 🚀 Future Improvements

- Hyperparameter tuning
- XGBoost implementation
- Streamlit web application
- Real-time lead prediction
- CRM integration
- Automated lead scoring

---

