# 🧹 Data Preprocessing for Customer Data

## 📌 Overview
In this assignment, we will perform data preprocessing on the customer data by removing any errors in the data, removing duplicates from the dataset, handling categorical values, and applying feature scaling.

---

## 📂 Data
Data consists of following columns:

- `customer_id` → ID column (duplicates present)
- `age` → Has missing values
- `city` → Is categorical (missing values present)
- `gender` → Is categorical
- `annual_income` → Numerical

---

## ⚙️ Task Performed

### ✅ Task 1 – Data Cleaning
- Handling missing values in `age` column → Replaced by median
- Handling missing values in `city` column → Replaced by mode
- Duplicate Rows → Removed

---

### 🔤 Task 2 – Encoding
- `City` → One Hot encoding
- `Gender` → Label Encoding

---

### 📏 Task 3 – Feature Scaling

#### 1. Min-Max Scaling
- Scale data between **0 and 1**
- Best use cases for:
  - Neural networks
  - Distance-based algorithms like KNN & K-Means

#### 2. Standardization
- Transform data such that:
  - Mean is 0
  - Standard Deviation is 1
- Best use cases for:
  - Logistic regression
  - SVM 
  - PCA

---

## 🛠️ Technologies Used
- Python
- Pandas
- Numpy
- Scikit-learn

---

## ▶️ How to run

```bash
pip install pandas numpy scikit-learn
python your_script.py
