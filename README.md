# 📊 Customer Data Management and Analysis

This project provides a comprehensive solution for managing and analyzing customer data using SQL databases, Python, Azure Machine Learning, and modern MLOps practices. The project was developed under the supervision of the **NTI – Data Engineering Professional Initiative (DEPI)**, part of the **Ministry of Communications and Information Technology – Egypt**.

---

## 🧠 Project Objectives

1. Build a robust infrastructure for customer data management using SQL Server.
2. Construct a data warehouse to aggregate and analyze customer data.
3. Apply Python and Azure Machine Learning for predictive modeling (e.g. churn prediction).
4. Deploy AI models using web frameworks and Azure services.
5. Integrate MLOps to track experiments and manage model lifecycles.

---

## 🧰 Tools & Technologies

- **SQL Server & Management Studio** – for database creation and queries  
- **SQL Data Warehouse** – for large-scale data aggregation  
- **Python** – for data analysis, modeling, and integration  
- **Pandas, Scikit-learn, Matplotlib** – for data manipulation and visualization  
- **Azure Machine Learning + Azure Data Studio** – for cloud-based modeling  
- **MLflow** – for MLOps and experiment tracking  
- **Flask / Streamlit** – for model deployment as web apps

---

## 🔍 Key Features

### 🗂️ Database & Warehouse Design
- Designed a normalized SQL schema with tables like:
  - `telco_customer_data`
  - `customer_trans`
  - `customer_inter`
- Created a dimensional model with fact and dimension tables for analytics

### 📊 Data Analysis & Insights
- Performed exploratory data analysis (EDA) using Python
- Key insights included churn behavior, transaction trends, and customer interaction patterns

### 🤖 Predictive Modeling
- Developed machine learning models to:
  - Predict customer churn probability
  - Suggest retention strategies
- Evaluated models using accuracy, classification reports, and real-world validation

### ☁️ Deployment & MLOps
- Used MLflow for tracking models and versions
- Deployed predictive models using Flask/Streamlit on Azure cloud services

---

## 📈 Key Insights

- SQL enabled powerful structured data control and transformation  
- Python provided flexibility for building and testing predictive models  
- Azure cloud streamlined data handling and model deployment  
- Churn prediction models significantly enhanced retention strategy planning  
- The integration of MLOps increased reproducibility and collaboration  

---

## 🎯 Project Benefits

- Better understanding of customer behavior
- Data-driven business decisions
- Improved retention and customer satisfaction
- Reduced manual processing with automation
- Scalable infrastructure for future customer analytics

---

## 🧪 Project Structure

```
├── database/
│   ├── schema_design.sql
│   ├── warehouse_model.sql
├── notebooks/
│   ├── eda.ipynb
│   ├── churn_modeling.ipynb
├── app/
│   ├── app.py (Flask/Streamlit)
├── README.md
└── requirements.txt
```

---

## 👩‍💻 Developed By

**Menna Sayed** – Faculty of Computers and Information 

Project Team: Basant Waleed, Nadine Ibrahim, Yazied Hassan, Ahmed Yousef  
Supervised by: **Ministry of Communications and Information Technology – NTI/DEPI Program**

---

## 📌 Future Work

- Integrate real-time dashboards with Power BI or Tableau  
- Expand customer segmentation models  
- Deploy models in CI/CD pipelines for real-world scalability  
