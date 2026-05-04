🚢 Titanic Survival Analysis & Prediction

 Project Overview

This project analyzes the famous Titanic dataset to understand *factors affecting passenger survival* and builds machine learning models to predict survival.

The project is divided into two main parts:

1. 📊 Exploratory Data Analysis (EDA)
2. 🤖 Machine Learning Models Comparison

---

 Project Structure

```
📁 Titanic-Project
│
├── titanic_survival_updated.ipynb        # Graphs & survival analysis
├── titanic_classification_uodated.ipynb	# ML models (SVM, RF, Logistic Regression)
├── train.csv
├── test.csv
└── README.md
```

---

## 📊 Exploratory Data Analysis (EDA)

In this part, we analyze survival trends using **clear visualizations**.

### ✔ Features Analyzed

* Gender (Sex)
* Passenger Class (Pclass)
* Age Groups
* Fare Groups
* Port of Embarkation (Embarked)
* Family Size (Alone vs With Family)

### ✔ Visualization Style

All graphs are designed for **easy understanding**:

* Show **Survived / Total**
* Include **Percentage (%)**
* Clean and simple bar charts

### 📈 Example Insight

* Females had a much higher survival rate than males
* 1st class passengers had higher survival compared to 3rd class
* Higher fare → higher survival probability

---

## 🤖 Machine Learning Models

We implemented and compared 3 models:

* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest

### ⚙️ Steps Performed

* Data cleaning (handling missing values)
* Feature encoding
* Feature selection
* Model training & evaluation

### 📊 Model Comparison

Each model is evaluated based on:

* Accuracy
* Performance comparison

---

## 🧠 Key Insights

* Gender is one of the strongest predictors of survival
* Passenger class significantly affects survival chances
* Fare and class are correlated with survival
* People traveling with family had different survival patterns

---

## Technologies Used

* Python 
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🎯 Conclusion

This project demonstrates:

* How to perform **clean and understandable EDA**
* How to build and compare **machine learning models**
* How to present results using **both count and percentage (professional standard)**

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Feature engineering
* Deploy model using a web app

---
