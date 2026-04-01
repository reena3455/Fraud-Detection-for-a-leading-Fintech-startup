# Fraud-Detection-for-a-leading-Fintech-startup(Anomaly Detection)


## Overview

This project detects **potential fraudulent bank transactions** using **unsupervised learning (K-Means clustering)**. It identifies anomalies based on how far transactions deviate from normal behavior.

---

##  Objectives

* Detect suspicious transactions without labeled data
* Perform exploratory data analysis (EDA)
* Identify anomalies using clustering
* Flag high-risk transactions

---

##  Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

##  Approach

###  Exploratory Data Analysis

* Analyzed transaction amount distribution
* Identified outliers and unusual patterns
* Examined relationships between features

###  Anomaly Detection

* Standardized numerical features
* One-hot encoded categorical features
* Applied **K-Means clustering**
* Used **distance to centroid** to detect anomalies

---

##  Key Technique

* Transactions in the **top 2% distance from cluster centroids** are flagged as potential fraud

---

##  Features Used

* Transaction Amount
* Account Balance
* Transaction Duration
* Login Attempts
* Customer Age
* Transaction Type, Channel, Location

---

##  Fraud Insights

* High-value transactions are rare and suspicious
* Multiple login attempts indicate possible account takeover
* Large debit transactions may signal unauthorized withdrawals
* Online transactions show higher fraud risk

---

## Output

* Clustered transactions
* Distance-based anomaly scores
* Flagged **potential fraud transactions**




