# Titanic Survival Prediction

This is a beginner-friendly data science project that aims to predict whether a passenger survived the Titanic disaster using machine learning. It walks through the full data science pipeline, from understanding the problem to modeling and evaluation.

---

## 📌 Problem Statement

The sinking of the Titanic is one of the most infamous shipwrecks in history. The goal of this project is to predict which passengers survived the tragedy using features such as:

- Passenger class
- Gender
- Age
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Embarked port

---

## 🛠️ Tools & Libraries

- **Python**
- **Pandas** – for data manipulation
- **NumPy** – for numerical operations
- **Seaborn & Matplotlib** – for data visualization
- **Scikit-learn** – for building and evaluating the model

---

## 📊 Dataset

The dataset used is the **Titanic dataset** from [Kaggle](https://www.kaggle.com/c/titanic/data) or [this raw link](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv).

It contains 891 records and the following columns:

- `Survived` (0 = No, 1 = Yes)
- `Pclass` (Passenger Class)
- `Name`
- `Sex`
- `Age`
- `SibSp` (Siblings/Spouses aboard)
- `Parch` (Parents/Children aboard)
- `Ticket`
- `Fare`
- `Cabin`
- `Embarked` (Port of Embarkation)

---

## 🔍 Steps Followed

1. **Understanding the problem** – Identified the goal and outcome.
2. **Loading the data** – Imported the Titanic dataset using Pandas.
3. **Exploratory Data Analysis (EDA)** – Investigated data patterns and class distributions using `.info()`, `.describe()`, and Seaborn visualizations.
4. **Data Cleaning** – Handled missing values, dropped irrelevant features.
5. **Feature Engineering** – Converted categorical data to numeric using `.map()` and `pd.get_dummies()`.
6. **Modeling** – Built a logistic regression model using Scikit-learn.
7. **Evaluation** – Measured model performance using accuracy, confusion matrix, and classification report.
8. **Reporting** – Summarized key insights and possible improvements.

---

## ✅ Results

- The logistic regression model achieved an accuracy of around **X%** (replace with your actual result).
- The most influential features were:
  - Gender (Females had higher survival rates)
  - Passenger Class (Higher class had better survival)
- Suggestions: Try using other models like Random Forests or improving with hyperparameter tuning.

---

## 🙋🏽‍♀️ Author

**Prudence Wambui**  
Aspiring Data Scientist | Content Creator  
Course: WorldQuant University – Applied Data Science Lab  
GitHub: [wambuuyy](https://github.com/Wambuuyy)

---

## 🧠 Lessons Learned

- How to apply the full data science process from scratch
- Importance of data cleaning and feature encoding
- How simple models like logistic regression can still be powerful
- I can do this on my own 💪🏽

---

## 🚀 Next Steps

- Try other classifiers (e.g., Random Forest, Decision Tree)
- Explore new datasets and apply the same process
- Upload the project to GitHub with clear documentation
