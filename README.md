# Task1
**Sales Data Cleaning and Preprocessing**

This project focuses on cleaning and preparing a sales dataset for analysis. The tasks are performed using Python and pandas in a Jupyter Notebook.

## Contents
Task1.ipynb: Contains all the data cleaning and preprocessing steps.

Key Cleaning Steps
### 1. Handling Missing Values

1.1Dropped rows where ORDERLINENUMBER was missing.

1.2Filled missing values in numerical columns using the column mean.

1.3Filled missing values in categorical columns using the mode.

### 2. Standardizing Date Formats

2.1 Converted mixed-format date strings in the ORDERDATE column to a consistent dd-mm-yyyy format.

### 3. Renaming Columns

3.1 Converted all column names to lowercase.

3.2 Replaced spaces with underscores.

3.3 Removed special characters to maintain uniformity.

### 4. Standardizing Text Values

4.1 Applied consistent formatting to text columns such as COUNTRY, STATUS, TERRITORY, DEALSIZE, CUSTOMERNAME, and name fields.

4.2 Converted to proper casing (title/upper case) and removed leading/trailing spaces.

4.3 Replaced inconsistent values (e.g., “U.S.A.”, “Usa”, “United States” → “USA”).

### 5. Removing Duplicate Records

5.1 Identified and removed exact duplicate rows to ensure data quality.

### 6. Fixing Data Types

6.1 Converted ORDERDATE to datetime format.

6.2 Converted columns like QUANTITYORDERED and ORDERLINENUMBER to integers.

6.3 Ensured POSTALCODE is treated as a string to preserve leading zeros.

### Technologies Used:
Python 3.13

pandas

Google colab
