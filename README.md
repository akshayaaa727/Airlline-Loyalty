# ✈️ Airline Loyalty Analysis & Customer Churn Prediction

An end-to-end data analytics and machine learning project that analyzes airline loyalty program data to identify customers at risk of churning, segment customers based on their behavior, and recommend personalized retention strategies. The project combines data preprocessing, exploratory data analysis, feature engineering, predictive modeling, customer segmentation, and interactive business dashboards.

---

## 📌 Problem Statement

Airline companies invest significantly in customer acquisition, making customer retention a critical business objective. This project aims to:

- Predict customers likely to churn.
- Identify different customer segments based on behavior and value.
- Generate actionable business insights for targeted marketing campaigns.
- Visualize key business metrics through an interactive Power BI dashboard.

---

## 📊 Dataset

The project uses an airline loyalty program dataset containing customer demographics, loyalty information, and flight activity.

### Data Includes

- Customer demographics
- Loyalty card information
- Customer Lifetime Value (CLV)
- Salary
- Flight activity
- Distance traveled
- Points earned and redeemed
- Enrollment and cancellation details

---

## 🚀 Project Pipeline

### 1. Data Cleaning

- Removed invalid salary values
- Imputed missing salaries using loyalty card-wise median
- Handled missing values
- Standardized categorical variables

---

### 2. Exploratory Data Analysis

Performed detailed EDA to understand:

- Customer demographics
- Flight frequency
- CLV distribution
- Loyalty card usage
- Missing data patterns
- Customer behavior trends

---

### 3. Feature Engineering

Created business-driven features including:

- Total Flights
- Total Distance
- Average Flights per Month
- Active Months
- Flight Trend
- Recency
- Redemption Ratio
- Season Concentration
- Customer Activity Score

---

### 4. Churn Prediction

Defined churn using both:

- **Hard Churn:** Official loyalty cancellation
- **Soft Churn:** No flight activity during the last six months

Models trained:

- Logistic Regression
- Random Forest
- XGBoost

Techniques used:

- Train-Test Split
- StandardScaler
- SMOTE
- Cross-validation
- ROC-AUC
- Precision
- Recall
- F1 Score

---

### 5. Customer Segmentation

Applied K-Means Clustering to group customers into distinct behavioral segments.

Identified customer groups such as:

- High Value Loyalists
- At-Risk Customers
- Declining Engagers
- Dormant Members
- Occasional Flyers

---

### 6. Business Recommendations

Designed targeted retention strategies for each customer segment, including:

- Personalized offers
- Loyalty rewards
- Reactivation campaigns
- Premium benefits
- Seasonal promotions

---

### 7. Power BI Dashboard

Built an interactive dashboard to visualize:

- Churn Overview
- Customer Segments
- Loyalty Card Distribution
- Revenue Insights
- Flight Activity Trends
- Geographic Analysis
- Customer Lifetime Value
- KPIs for business decision-making

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- imbalanced-learn (SMOTE)
- Power BI
- Jupyter Notebook

---

## 📈 Machine Learning Workflow

```
Raw Data
    │
    ▼
Data Cleaning
    │
    ▼
EDA
    │
    ▼
Feature Engineering
    │
    ▼
Train/Test Split
    │
    ▼
SMOTE
    │
    ▼
Model Training
    │
    ▼
Model Evaluation
    │
    ▼
Customer Segmentation
    │
    ▼
Business Recommendations
    │
    ▼
Power BI Dashboard
```

---

## 📊 Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Average Precision Score

---

## 📂 Repository Structure

```
├── Airline_Loyalty_Analysis.ipynb
├── Airline_Dashboard.pbix
├── dataset/
├── images/
├── README.md
```

---

## 💡 Key Business Insights

- Recency is one of the strongest indicators of customer churn.
- High Customer Lifetime Value does not always imply customer loyalty.
- Flight frequency and engagement trends significantly improve churn prediction.
- Behavioral segmentation enables more personalized marketing strategies than using CLV alone.

