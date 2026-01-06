# -Insurance-Data-Analysis-Prediction-Project
This project analyzes an insurance dataset to identify key factors affecting medical charges. It includes data cleaning, EDA, feature engineering, and preparation of a model-ready dataset.



## **🔍 Project Overview**

This project focuses on exploratory data analysis (EDA), feature engineering, and data preprocessing on an Insurance dataset to understand the key factors affecting medical insurance charges.
The goal is to clean the data, analyze patterns, transform categorical variables, and prepare a model-ready dataset for further machine learning tasks.

## **Insurance Raw Dataset used :**
-<a href="https://github.com/laganmehra875/-Insurance-Data-Analysis-Prediction-Project/blob/main/insurance.csv"> Insurance.csv </a>

## Insurance Python Codes File :
-<a href="https://github.com/laganmehra875/-Insurance-Data-Analysis-Prediction-Project/blob/main/insurance.ipynb"> Isurance Python Codes file</a>

## **🎯 Problem Statement**

Insurance companies need to understand what factors influence medical insurance charges so they can:

1. Price policies accurately
2. Identify high-risk customers
4. Improve business decisions

This project analyzes variables like age, BMI, smoking habits, gender, region, and children to study their impact on insurance charges.



## **📁 Dataset Information**

***Dataset Name:*** Insurance Dataset

Source: Common public dataset (used for ML & analytics practice)

**Total Features:**

age

sex

bmi

children

smoker

region

charges (target variable)


## 🛠 Tools & Technologies Used

**Programming Language:** Python

**Libraries:**

NumPy

Pandas

Matplotlib

Seaborn

**Environment:** Jupyter Notebook

## 🔄 Project Workflow

### 1️⃣ Data Loading

Imported the dataset using Pandas

Checked dataset shape, columns, and data types


## 2️⃣ Exploratory Data Analysis (EDA)

***Distribution analysis using:***

Histograms

Boxplots

Countplots

***Identified:***

Outliers in BMI & charges

Imbalance in smoker vs non-smoker

Higher charges for smokers


## 3️⃣ Data Cleaning

Checked missing values (no null values found)

Converted categorical values into numerical form


## 4️⃣ Feature Engineering

***Converted:***

smoker → binary (0 = No, 1 = Yes)

sex → renamed as is_gender

***Created BMI categories***

Binned insurance charges using quantile binning

Applied One-Hot Encoding on region column

Converted all features to integer type for model compatibility


## 5️⃣ Feature Selection

***Final selected features:***

age

gender

bmi

children

smoker

region (encoded)

charges


# 📈 Key Insights

***Smokers have significantly higher insurance charges***

BMI and age strongly affect medical costs

Region has moderate impact

Non-smokers generally fall in lower charge brackets







