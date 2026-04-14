#  Customer Data Preprocessing

##  Project Overview

This project is done as part of my learning in data preprocessing.
In real-world datasets, data is usually not clean — it contains missing values, duplicates, and different formats.

In this project, I cleaned the dataset and prepared it properly so that it can be used for machine learning.

---

##  Dataset Details

The dataset contains the following columns:

* customer_id → Unique ID for each customer
* age → Age of the customer (some values are missing)
* city → Customer location
* gender → Male / Female
* annual_income → Income of the customer

---

##  Steps I Performed

###  1. Data Cleaning

* Filled missing values in:

  * age using **median**
  * city using **mode**
* Removed duplicate rows

---

###  2. Encoding

* Applied **One-Hot Encoding** for city
* Applied **Label Encoding** for gender

---

###  3. Feature Scaling

Scaled numerical columns:

* age
* annual_income

Used:

* Min-Max Scaling
* Standardization

---

##  What I Learned

* Missing values should be handled before encoding
* Order of preprocessing steps is very important
* Scaling helps in improving model performance
* Difference between Min-Max Scaling and Standardization

---

##  When to Use Scaling Methods

Min-Max Scaling is useful when we need values in a fixed range like 0 to 1, especially for algorithms like KNN.
Standardization is useful when data needs to be centered around mean 0 and works well with models like Logistic Regression and SVM.

---

##  Tools Used

* Python
* Pandas
* NumPy
* Scikit-learn

---


##  Files

* data_cleaning.ipynb → main notebook
* README.md → project explanation

---

##  Author

Rakesh Kommu

