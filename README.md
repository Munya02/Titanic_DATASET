# Titanic Data Cleaning & Preprocessing

 Project Overview

This project focuses on cleaning and preparing the Titanic dataset for analysis.
Raw data often contains missing values, inconsistent formats, and unnecessary columns.
The goal is to transform the dataset into a clean and usable format.


 Objective

* Handle missing values
* Remove duplicate records
* Fix incorrect data types
* Rename columns for better readability

---

Dataset

* **Name:Titanic Dataset
* **Source: Public dataset
* **Format: CSV

---

Tools & Technologies

* Python
* pandas
* Jupyter Notebook (Google Colab)

---

 Data Cleaning Steps

Handling Missing Values

* Filled missing values in the **Age** column using the average (mean)
* Filled missing values in the **Embarked** column using the most frequent value (mode)
* Dropped the **Cabin** column due to too many missing values

---

 Removing Duplicates

* Checked for duplicate rows
* Removed duplicates to ensure data accuracy

---

 Fixing Data Types

* Converted the following columns to category type:

  * survived
  * pclass
  * sex
  * embarked

---

 Renaming Columns

* Converted column names to lowercase
* Replaced unclear names with more descriptive ones:

  * sibsp → siblings_spouses
  * parch → parents_children

---

#Final Output

* Clean dataset ready for analysis
* No missing values in key columns
* Consistent and readable column names
* Correct data types for efficient processing

---

 Key Learnings

* Importance of handling missing data
* How to clean and structure datasets
* Preparing data before analysis
* Writing clean and readable code

---

 How to Run the Project

1. Open the notebook in Google Colab
2. Run all cells step by step



* `task1_titanic_cleaning.ipynb` → Main notebook
* `titanic.csv` → Raw dataset
* `cleaned_titanic.csv` → Cleaned dataset (optional)

## Author

Mcdonald Mudavanhu
