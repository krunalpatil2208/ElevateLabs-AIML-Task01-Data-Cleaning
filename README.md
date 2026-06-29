# Task 1 - Data Cleaning & Preprocessing

## Internship

AI & ML Internship - Elevate Labs

---

## Objective

The objective of this task is to clean and preprocess a raw dataset so that it is suitable for Machine Learning models.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Dataset

Titanic Dataset

The dataset contains passenger information including age, gender, fare, passenger class, survival status, etc.

---

## Steps Performed

### 1. Data Exploration

- Loaded the dataset
- Checked dataset shape
- Examined data types
- Generated statistical summary
- Identified missing values

---

### 2. Data Cleaning

- Filled missing values in Age using Median
- Filled missing values in Embarked using Mode
- Removed Cabin column due to excessive missing values
- Removed duplicate records

---

### 3. Encoding

Converted categorical variables into numerical values using Label Encoding.

Columns encoded:

- Sex
- Embarked

---

### 4. Feature Scaling

Applied StandardScaler to normalize numerical features.

Scaled columns:

- Age
- Fare

---

### 5. Outlier Detection

Visualized outliers using Boxplots.

Removed outliers using the IQR (Interquartile Range) method.

---

## Visualizations

- Boxplot
- Histogram
- Count Plot
- Correlation Heatmap

---

## Files Included

- Task1_DataCleaning.ipynb
- titanic.csv
- cleaned_titanic.csv

---

## Learning Outcomes

Through this task, I learned:

- Data Cleaning
- Missing Value Handling
- Encoding Techniques
- Feature Scaling
- Outlier Detection
- Data Visualization

---

## Author
KRUNAL PRAKASH PATIL
AI & ML Internship - Elevate Labs