# Titanic Survival Prediction - EDA Report

This repository contains the Exploratory Data Analysis (EDA) for the Titanic dataset, focused on identifying key patterns and relationships among features that influence passenger survival.

## Dataset Overview

The dataset contains information on Titanic passengers such as:
- Demographics (age, sex)
- Ticket fare and class
- Number of siblings/spouses and parents/children aboard
- Embarkation port
- Survival status (target variable)

---

## Objectives of EDA

- Understand the distribution and nature of each feature
- Detect missing values and outliers
- Analyze relationships between features and the survival label
- Identify the most influential features for prediction

---

## Key Visual Insights

### Age
- Distribution: Approximately normal (after standardization)
- Survivors tend to be slightly younger
- Outliers exist at both extremes
- Inference: Age has a moderate impact on survival

### Fare
- Distribution: Right-skewed, with high-value outliers
- Survivors often paid higher fares
- Inference: Fare is positively associated with survival and reflects passenger class

### Passenger Class
- 1st class passengers had the highest survival rate
- 3rd class had the lowest
- Inference: Pclass is a strong predictor of survival

### Gender
- Females had a much higher survival rate than males
- Inference: Gender is one of the strongest predictors

### Correlation Analysis
- Fare and Pclass: Strong negative correlation
- Survived correlates with Sex, Pclass, and Fare
- Inference: These three features are key drivers of survival

---

## Summary of Key Predictive Features

| Feature     | Importance | Notes |
|-------------|------------|-------|
| Sex         | High       | Females had significantly higher survival |
| Pclass      | High       | Higher class → better survival chance |
| Fare        | Medium     | Higher fare → higher likelihood of survival |
| Age         | Low-Medium | Younger age increased survival chances |

---

## Tools Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (for preprocessing)

---

## Author

This analysis was conducted as part of an internship task in AI/ML, focused on understanding feature behavior in survival prediction using EDA techniques.

