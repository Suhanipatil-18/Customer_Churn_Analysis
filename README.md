# 📊 Customer Churn Analysis & Prediction Dashboard

## 🔹 Project Overview
An end-to-end **Customer Churn Analytics and Prediction** project that builds a complete data pipeline using **SQL Server, Power BI, and Machine Learning (Random Forest)** to analyze customer behavior, identify churn drivers, and predict future churners.

---

## 🔹 Business Problem
Customer churn negatively impacts revenue and long-term growth.  
Organizations often struggle to:
- Identify churn-prone customer segments
- Understand reasons behind churn
- Predict which customers are likely to churn in advance

This project addresses these challenges using data analytics and predictive modeling.

---

## 🔹 Project Objectives
- Analyze historical customer churn patterns  
- Segment customers by demographics, geography, services, and account details  
- Identify key churn drivers  
- Predict future churners using machine learning  
- Provide decision-ready dashboards for business users  

---

## 🔹 Tech Stack
🗄️ SQL Server & SSMS – Database creation, ETL pipeline, data cleaning, and views

📊 Power BI Desktop – Interactive dashboards and executive summaries

🔄 Power Query – Data transformation and feature engineering

🧠 DAX (Data Analysis Expressions) – KPIs, churn metrics, and dynamic calculations

🐍 Python (Jupyter Notebook) – Machine learning model development

🤖 Scikit-Learn (Random Forest) – Churn prediction model

📁 Excel / CSV – Intermediate data exchange

📦 File Formats – .pbix, .sql, .ipynb, .csv

---

## 🔹 Data Source
- Telecom Customer Churn Dataset (CSV)
- Customer demographics, account info, services, billing, and churn status

---

## 🔹 Project Architecture

CSV Data
↓
SQL Server (Staging → Production → Views)
↓
Power BI (Analysis & Dashboard)
↓
Python (ML Model – Random Forest)
↓
Predicted Churn Data
↓
Power BI (Prediction Dashboard)


---

## 🔹 ETL Process (SQL Server)
- Created database `db_Churn`
- Imported raw CSV into staging table
- Data profiling (distinct values, null checks)
- Cleaned and standardized data
- Loaded data into production table
- Created analytical views:
  - `vw_ChurnData` (Stayed & Churned)
  - `vw_JoinData` (New Joiners)

---

## 🔹 Power BI Data Transformation
- Created churn flag and charge buckets
- Built Age Group and Tenure Group mapping tables
- Unpivoted service columns for service-level analysis
- Established data model relationships

---

## 🔹 Key Metrics (DAX)
- **Total Customers**
- **New Joiners**
- **Total Churn**
- **Churn Rate (%)**
- **Predicted Churn Count**

---

## 🔹 Dashboard Pages & Insights

### 1️⃣ Executive Summary
- Total Customers  
- New Joiners  
- Total Churn  
- Churn Rate  

### 2️⃣ Demographic Analysis
- Gender vs Churn Rate  
- Age Group vs Customer Count & Churn Rate  

### 3️⃣ Account & Payment Analysis
- Payment Method vs Churn Rate  
- Contract Type vs Churn Rate  
- Tenure Group vs Customer & Churn Rate  

### 4️⃣ Geographic Analysis
- Top States by Churn Rate  

### 5️⃣ Churn Distribution
- Churn Category
- Tooltip: Churn Reasons  

### 6️⃣ Services Analysis
- Internet Type vs Churn Rate  
- Services Used vs Churn %

---

## 🔹 Machine Learning – Churn Prediction
- **Algorithm:** Random Forest Classifier
- **Goal:** Predict whether a customer will churn (Yes / No)

### ML Workflow
- Data imported from SQL views
- Categorical encoding
- Train-test split (80/20)
- Model training & evaluation
- Feature importance analysis
- Prediction on new joiners
- Export predicted churners

---

## 🔹 Prediction Dashboard (Power BI)
- List of predicted churners
- Demographic breakdown
- Account & payment insights
- Geographic churn distribution

---

## 🔹 Color Theme
- Primary: `#4A44F2`
- Secondary: `#9B9FF2`
- Background: `#F2F2F2`
- Accent: `#A0D1FF`

---

## 🔹 Target Audience
- Data Analysts & BI Professionals  
- Marketing & Retention Teams  
- Business Stakeholders  
- Subscription-based Businesses  

---

## 🔹 Project Outcome
- Delivered an industry-ready churn analytics solution  
- Integrated SQL, BI, and ML in one workflow  
- Enabled proactive churn prevention strategies  

---

## 🔹 Dashboard Preview

### 🔸 Summary Dashboard
![Summary Dashboard](https://github.com/Suhanipatil-18/Customer_Churn_Analysis/blob/main/Snapshot_of_Summary-Dashboard.png)

### 🔸 Churn Prediction Dashboard
![Churn Prediction Dashboard](https://github.com/Suhanipatil-18/Customer_Churn_Analysis/blob/main/Snapshot_customer_prediction-window.png)


---

## ⭐ If you like this project, feel free to star the repository!
