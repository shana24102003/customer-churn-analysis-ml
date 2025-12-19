# customer-churn-analysis-ml
Customer churn analysis using ML
# Customer Churn Analysis & Prediction using Machine Learning

## 📌 Project Overview
Customer churn is a critical business problem where companies lose customers to competitors.  
This project focuses on analyzing telecom customer data and building machine learning models to predict customer churn and identify key factors contributing to customer attrition.

The goal is to help businesses take proactive retention measures by identifying high-risk customers.

---

## 📊 Dataset Description
- Dataset: Telecom Customer Churn Dataset
- Format: Excel (.xlsx)
- Each row represents a customer
- Target Variable: `Churn_Label` (Yes / No)

---

## 🛠 Tools & Technologies Used
- Python
- Pandas & NumPy (Data Manipulation)
- Matplotlib & Seaborn (Data Visualization)
- Scikit-learn (Machine Learning)
- Google Colab / Jupyter Notebook

---

## 🔍 Project Workflow

### 1️⃣ Data Loading & Cleaning
- Loaded Excel dataset using Pandas
- Cleaned column names for consistency
- Converted `TotalCharges` to numeric
- Handled missing values
- Removed irrelevant columns like `customerID`

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Analyzed churn distribution
- Studied customer behavior patterns
- Identified trends related to contract type, tenure, and charges

---

### 3️⃣ Feature Engineering
- Encoded categorical variables using Label Encoding
- Prepared features and target variable
- Performed train-test split (80/20)

---

### 4️⃣ Model Building
Two machine learning models were implemented:

- **Logistic Regression**
  - Used as a baseline classification model
  - Achieved approximately **80% accuracy**

- **Random Forest Classifier**
  - Captured non-linear relationships
  - Improved prediction performance
  - Provided feature importance insights

---

### 5️⃣ Model Evaluation
- Accuracy Score
- Precision, Recall, and F1-score
- Confusion Matrix

Special focus was given to **Recall**, as identifying churn customers is more important from a business perspective.

---

## 📈 Key Insights
- Customers on **month-to-month contracts** are more likely to churn
- **Low tenure** customers have higher churn risk
- Higher **monthly charges** increase churn probability

---

## 💡 Business Recommendations
- Offer long-term contract incentives
- Design retention campaigns for low-tenure customers
- Provide personalized discounts to high-risk users

---

## 📌 Conclusion
This project demonstrates an end-to-end analytics and machine learning workflow — from data cleaning and EDA to model building and business insights.  
The results can help telecom companies reduce churn and improve customer retention strategies.

---

## 📎 Future Enhancements
- Hyperparameter tuning
- SQL-based analytics
- Power BI dashboard for visualization
- Deployment as a web app

---

## 👤 Author
**Your Name**  
Aspiring Data Analyst / Data Science Student
