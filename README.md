# HR Employee Attrition Analysis – Capstone Project



## Overview

This project analyzes a fictional HR dataset to uncover patterns in employee attrition and performance. The goal is to identify key factors leading to employee departure, suggest improvements to reduce attrition, and build predictive models to flag at-risk employees.

---

##  Objectives

- Understand the **drivers behind employee attrition**
- Propose insights to **enhance performance ratings**
- Apply **EDA and machine learning** to build a predictive model
- Recommend actionable steps to **retain employees**

---

##  Dataset

- **Source**: Provided fictional HR dataset (`WA_Fn-UseC_-HR-Employee-Attrition.csv`)
- **Records**: 1,470 employees
- **Features**: 35 columns (age, gender, job role, satisfaction scores, income, etc.)
- **Target Variable**: `Attrition` (Yes/No)

---

##  Tools & Libraries

- Python (Pandas, NumPy)
- Matplotlib & Seaborn for visualization
- Scikit-learn for modeling
- Jupyter Notebook for analysis

---

##  Workflow

### 1. Data Loading & Cleaning
- Removed constant/irrelevant columns (`Over18`, `EmployeeCount`, etc.)
- Handled categorical data with **label encoding** and **one-hot encoding**

### 2.  Feature Engineering
- Created `TenureBucket` from `YearsAtCompany` for better segmentation

### 3.  Exploratory Data Analysis (EDA)
####  1D Analysis:
- Attrition distribution
- Age, gender, education, satisfaction level histograms

####  2D Analysis:
- Attrition vs Tenure Bucket
- Attrition vs Job Role
- Correlation heatmap with numeric features

---

##  Key Insights

- Most attrition happens within the **first 2 years**
- **Sales Reps** and **employees working overtime** are more likely to leave
- High **salary hikes** and **job involvement** improve performance ratings
- Experience (years at company, years with manager) **negatively correlates** with attrition

---

## 📂 Repository Structure

📦 HR-Attrition-Capstone/
├── HR_Attrition_Capstone_Notebook.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── README.md

