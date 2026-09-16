# 🚢 Titanic Survival Prediction

A machine learning project that predicts whether a passenger survived the Titanic disaster using passenger and travel-related features.

The project focuses on **Exploratory Data Analysis (EDA), Feature Engineering, and a Scikit-learn Machine Learning Pipeline**.

---

## 📌 Project Overview

The Titanic dataset contains information about passengers such as age, gender, passenger class, fare, and family size.

The goal of this project is to build a machine learning model that can predict **passenger survival** based on these features.

---

## 🔍 Exploratory Data Analysis (EDA)

The dataset was analyzed to understand the relationship between passenger characteristics and survival.

### Key Insights

- 👩 **Female passengers had higher survival rates** compared to male passengers.
- 👨‍👩‍👧‍👦 **Family size influenced survival**, with survival patterns varying across different family sizes.
- 📊 Passenger class and other passenger-related features provided useful information for prediction.
- 🧹 Missing values were identified and handled carefully during preprocessing.

---

## ⚙️ Feature Engineering

Feature engineering was performed to improve the quality of the data and make it suitable for machine learning.

Key steps included:

- Handling missing values
- Encoding categorical features
- Creating useful features from existing columns
- Preparing numerical features for modeling
- Removing unnecessary information

---

## 🤖 Machine Learning Pipeline

The project uses a **Scikit-learn Pipeline** to combine preprocessing and machine learning steps into a single workflow.

### Pipeline Workflow

```text
Raw Data
   ↓
Data Cleaning
   ↓
Missing Value Handling
   ↓
Feature Engineering
   ↓
Categorical Encoding
   ↓
Feature Scaling
   ↓
Machine Learning Model
   ↓
Survival Prediction
