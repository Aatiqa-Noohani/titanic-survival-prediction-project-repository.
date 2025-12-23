# titanic-survival-prediction-project-repository.
# Titanic Survival Prediction Project

 Aatiqa Attaullah

## 📌 Project Overview

This project aims to predict the survival of passengers on the Titanic using machine learning techniques. The dataset includes demographic and personal information of passengers, such as age, sex, class, and port of embarkation.

The project demonstrates a complete ML workflow including **data collection, preprocessing, exploratory data analysis (EDA), feature encoding, model training, and evaluation**.

---

## 📂 Dataset

* **Source:** Kaggle Titanic Dataset (`train.csv`)
* **Features Used:**

  * Pclass (Passenger Class)
  * Sex
  * Age
  * SibSp (Siblings/Spouses aboard)
  * Parch (Parents/Children aboard)
  * Fare
  * Embarked (Port of Embarkation)
* **Target Variable:** Survived (0 = No, 1 = Yes)

---

## 🧹 Data Preprocessing

* Dropped the `Cabin` column due to excessive missing values
* Filled missing `Age` values with the mean
* Filled missing `Embarked` values with the mode
* Converted categorical columns (`Sex`, `Embarked`) to numeric values

---

## 🔎 Exploratory Data Analysis (EDA)

* Countplots for `Survived`, `Sex`, and `Pclass`
* Visualized survival rates by gender and class
* Statistical summary using `describe()`

---

## 🛠️ Feature Selection

* Dropped irrelevant columns: `PassengerId`, `Name`, `Ticket`
* Defined features `X` and target `y`

---

## 📊 Model Training

* Split dataset into training and testing sets (80% train, 20% test)
* Trained **Logistic Regression** classifier

---

## 📈 Model Evaluation

* **Training Accuracy:** Evaluated using `accuracy_score`
* **Testing Accuracy:** Evaluated using `accuracy_score`
* Predictions made on both training and testing sets

---

## 🔮 Results

* The Logistic Regression model provides a baseline for survival prediction
* Accuracy scores indicate the model’s effectiveness on train and test sets

---

---

## 📌 Tools & Technologies

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## 📂 Repository Structure

* `train.csv` : Titanic training dataset
* `titanic_prediction.ipynb` : Jupyter Notebook with full code and analysis

---

 Aatiqa Attaullah
