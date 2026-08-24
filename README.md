# Spaceship_prediction_model .

In this repository i upload a kaggle compitition of spaceship titanic .


# 🚀 Spaceship Titanic - Machine Learning Project

-> In thid project i faced many problems but every problem taught me a new approach and new progress .

## 📌 Project Overview

This project is based on the **Spaceship Titanic** Kaggle dataset.

The goal of this project is to predict whether a passenger was **Transported to another dimension** based on different passenger details such as HomePlanet, CryoSleep, Age, spending information, VIP status, etc.

This was one of the most challenging Machine Learning projects I have worked on so far. I faced many problems during data preprocessing, handling missing values, encoding categorical data, model training, and prediction.

---

## 🎯 Objective

The main objective of this project is to:

- Understand and preprocess the Spaceship Titanic dataset
- Handle missing values
- Convert categorical data into numerical data
- Train a Machine Learning classification model
- Evaluate the model performance
- Make predictions on the test dataset
- Create a submission file for Kaggle

---

# Accuracy of model is 0.775689 (77%) 

## 🛠️ Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Logistic Regression

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Handling Missing Values
   ↓
Feature & Target Separation
   ↓
Categorical Encoding
   ↓
Train-Validation Split
   ↓
Logistic Regression
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Test Data Prediction
   ↓
Kaggle Submission



# 🚀 Spaceship Titanic - Machine Learning Project

## 📌 Project Overview

This project is based on the **Spaceship Titanic** Kaggle dataset.

The goal of this project is to predict whether a passenger was **Transported to another dimension** based on different passenger details such as HomePlanet, CryoSleep, Age, spending information, VIP status, etc.

This was one of the most challenging Machine Learning projects I have worked on so far. I faced many problems during data preprocessing, handling missing values, encoding categorical data, model training, and prediction.

---

## 🎯 Objective

The main objective of this project is to:

- Understand and preprocess the Spaceship Titanic dataset
- Handle missing values
- Convert categorical data into numerical data
- Train a Machine Learning classification model
- Evaluate the model performance
- Make predictions on the test dataset
- Create a submission file for Kaggle

---

## 🛠️ Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Logistic Regression

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Handling Missing Values
   ↓
Feature & Ta

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

### 1. Handling Missing Values

* Categorical columns → Mode
* Numerical columns → Median

### 2. Removing Unnecessary Features

`PassengerId` and `Name` were removed from the model features.

### 3. Categorical Encoding

Categorical features were converted into numerical features using:

```python
pd.get_dummies()
```

with:

```python
drop_first=True
```

### 4. Train-Validation Split

The dataset was divided into:

* 80% Training Data
* 20% Validation Data

---

## 🤖 Model Used

### Logistic Regression

Logistic Regression was used because this is a **binary classification problem**.

The target variable is:

```text
Transported
```

with two possible outcomes:

```text
True
False
```

---

## 📊 Model Performance

The model achieved approximately:

**77.57% validation accuracy**

I am also working on improving the model performance further.

---

## 💡 Challenges & Learning

This project was challenging for me because I faced several problems during the implementation.

Some of the major challenges were:

* Understanding the dataset
* Handling missing values correctly
* Encoding categorical features
* Making train and test features consistent
* Understanding model training and prediction
* Dealing with model convergence issues
* Creating the final Kaggle submission file

### What I Learned

This project taught me that Machine Learning is not only about training a model.

**Data preprocessing, feature handling, debugging, and understanding the data are equally important.**

Every error I faced helped me understand the Machine Learning workflow better.

---

## 📁 Project Structure

```text
Spaceship-Titanic/
│
├── train.csv
├── test.csv
├── spaceship.ipynb
├── submission.csv
└── README.md
```

---

## 🚀 Future Improvements

* Improve model accuracy
* Try other classification algorithms
* Perform feature engineering
* Apply feature scaling where required
* Perform hyperparameter tuning
* Compare different models

---



## ⭐ Conclusion

The Spaceship Titanic project was a great learning experience and helped me improve my understanding of the complete Machine Learning workflow — from **data preprocessing to model training and Kaggle submission**.

```
```
