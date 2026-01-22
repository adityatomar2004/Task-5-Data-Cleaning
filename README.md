# Task 5: Python Basics - Reading Data + Simple Cleaning (Pandas)

## Overview
This repository contains my submission for **Task 5** of the Data Analyst Internship. The goal of this task was to perform data cleaning and basic feature engineering on the **Titanic Dataset** using Python and the Pandas library.

## Files Included
* `Task5_Cleaning.ipynb`: The Google Colab notebook containing all python code, analysis, and markdown notes.
* `cleaned_titanic_data.csv`: The final processed dataset after cleaning and transformation.
* `README.md`: Project documentation.

## Tools Used
* **Language:** Python
* **Environment:** Google Colab
* **Libraries:** `pandas`, `numpy`

## Cleaning Process
As outlined in the task requirements, I performed the following steps:

1.  **Data Loading:** Loaded the raw Titanic dataset using `pd.read_csv()`.
2.  **Missing Value Handling:**
    * **Age:** Filled missing values with the **median** age to maintain data distribution.
    * **Embarked:** Filled missing values with the **mode** (most frequent port).
    * **Cabin:** Dropped the column entirely as it had excessive missing data.
3.  **Duplicate Removal:** Checked for and removed duplicate rows to ensure data integrity.
4.  **Data Type Conversion:** Converted the `Age` column from float to integer format.
5.  **Feature Engineering:** Created a new column `FamilySize` by combining `SibSp` (Siblings/Spouse) and `Parch` (Parents/Children).
6.  **Export:** Saved the cleaned dataframe to a new CSV file.

## How to Run
1.  Open the `Task5_Cleaning.ipynb` file.
2.  Click the "Open in Colab" button (if viewing on GitHub) or download the file to run in Jupyter Notebook.
3.  Run the cells sequentially to reproduce the cleaning process.

---
*Submitted by: [Your Name]*
