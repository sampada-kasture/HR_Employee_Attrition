# HR Employee Attrition Analysis – Capstone Project



## Overview

This capstone project analyzes a fictional HR dataset to uncover patterns related to employee attrition and performance. The objective is to use both Python and SQL to extract actionable insights, identify high-risk employee groups, and build predictive models that can help organizations improve retention strategies.

---

##  Objectives

- Understand the **drivers behind employee attrition**
- Propose insights to **enhance performance ratings**
- Use SQL and Python for comprehensive exploratory and statistical analysis
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

- Languages: Python, SQL
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- Platform: Jupyter Notebook
- Database: SQLite

---

##  Workflow
## Part 1: Python-Based Analysis & Modeling

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

## Part 2: SQL-Based Analysis
### 1.Database Creation
- Converted the CSV into a SQLite3 database for structured querying
  
### 2.Attrition Summarization Using SQL
- Attrition by Gender, Department, Age Group, Job Level, Tenure
- Percentage-based breakdowns with subqueries

### 3.Root Cause Analysis
- Why people over 50 are more likely to leave
- Relationship between salary and attrition
- Exploring short tenure + overtime + job satisfaction as risk factors

---

## Key Insights

- Most attrition happens within the **first 2 years**
- **Sales Reps** and **employees working overtime** are more likely to leave
- High **salary hikes** and **job involvement** improve performance ratings
- Experience (years at company, years with manager) **negatively correlates** with attrition

---

## Repository Structure

📦 HR-Attrition-Capstone/
├── HR_Attrition_Capstone_Notebook.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── HR_Employee_Attrition_PartII.ipynb
├── README.md

