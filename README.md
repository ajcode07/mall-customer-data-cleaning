🧹 Data Cleaning – Mall Customer Segmentation Data
📌 Task Overview

This task is part of my Data Analyst Internship – Task 1.
The objective is to clean and preprocess a raw dataset to make it ready for analysis.

Dataset used: Mall Customer Segmentation Data (Kaggle)

🛠️ Steps Performed

Imported libraries: Pandas, NumPy

Loaded dataset: Mall_Customers.csv

Explored dataset:

Checked shape, datatypes, missing values, duplicates

Used .info(), .describe(), .isnull().sum(), .duplicated().sum()

Data Cleaning:

Removed duplicate rows

Handled missing values (none found in this dataset)

Standardized text values in gender column → converted to lowercase, unified categories

Renamed all columns to lowercase with underscores for consistency

Converted age → int, annual_income_(k$) → float

Exported cleaned dataset as mall_customers_cleaned.csv

📊 Deliverables

Notebook → Mall_Customers(Data Cleaning).ipynb

Raw dataset → Mall_Customers.csv

Cleaned dataset → mall_customers_cleaned.csv

✅ Summary of Cleaning

Removed duplicate rows

Standardized gender values (male, female)

Renamed columns to lowercase with underscores

Ensured correct datatypes for numerical fields

Exported a cleaned version of the dataset
