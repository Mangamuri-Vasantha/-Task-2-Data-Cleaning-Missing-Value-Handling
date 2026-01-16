
# Task 2: Data Cleaning & Missing Value Handling

## 📌 Project Overview
This project focuses on performing data cleaning and handling missing values using Python. The objective is to prepare raw datasets for further analysis or machine learning by improving data quality, consistency, and completeness.

Two real-world datasets were used:
- **House Prices Dataset**
- **Medical Appointment No Shows Dataset**

---

## 🛠️ Tools & Technologies
- Python 3
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📂 Datasets Used
1. **kc_house_data.csv**  
   - Contains housing-related features such as price, bedrooms, bathrooms, and location details.

2. **KaggleV2-May-2016.csv**  
   - Contains medical appointment records and whether patients showed up or not.

---

## 🔍 Data Cleaning Steps
The following steps were applied to both datasets:

1. Loaded datasets using Pandas
2. Identified missing values using `isnull().sum()`
3. Visualized missing data patterns using bar charts
4. Applied **median imputation** for numerical columns
5. Applied **mode imputation** for categorical columns
6. Removed columns with extremely high missing values
7. Validated datasets after cleaning
8. Compared dataset size before and after cleaning
9. Saved cleaned datasets as CSV files

---

## 📊 Results
- All missing values were successfully handled
- Data quality improved significantly
- Datasets are now ready for analysis or machine learning
- Cleaned datasets were saved for future use

---


