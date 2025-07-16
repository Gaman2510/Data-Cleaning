##🛍️ Online Retail Sales Data Cleaning, Preprocessing & EDA

This project involves cleaning, transforming, and performing Exploratory Data Analysis (EDA) on an Online Retail Sales dataset using Python and pandas. The workflow covers all essential steps to prepare the dataset for future analytics or machine learning applications.


-----
##📁 Project Structure

project 2.ipynb: The main Jupyter Notebook for data loading, cleaning, and EDA.

online_retail_sales.csv: Raw dataset (assumed to be present).

Data online.xlsx: Final cleaned and transformed data exported to Excel.



-----
##🎯 Project Objectives

Load and inspect the dataset.

Handle missing and inconsistent values.

Standardize formats and correct data types.

Detect and classify patterns in invoice numbers.

Perform exploratory data analysis to understand trends and outliers.



-----
##🧽Data Cleaning & Transformation

Handled null values, especially in CustomerID.

Converted InvoiceDate to consistent datetime format.

Removed duplicates and invalid date records.

Standardized InvoiceNo by detecting formats:

All Digits

Letters + Digits

Digits + Letters

Mixed or Irregular Patterns


Added prefix "C" to numeric invoice numbers for uniformity.


-----
##📊 Exploratory Data Analysis (EDA)

The project includes basic EDA using pandas to derive insights such as:

📅 Date-wise sales activity using the cleaned InvoiceDate field.

📦 Frequent products and descriptions based on quantity ordered.

🌍 Country-wise sales analysis.

👤 Customer behavior patterns using CustomerID.

🧾 Invoice pattern type distributions to understand structural anomalies.


These insights help identify business patterns, high-performing SKUs, and potential data quality issues.



-----
##📦 Technologies Used

Python 3

Jupyter Notebook

Pandas

NumPy

Regular Expressions

Excel I/O (via to_excel)


------
##🚀 How to Run

1. Clone this repository.


2. Place the dataset online_retail_sales.csv in the working directory.


3. Install required libraries:

pip install pandas numpy openpyxl


4. Launch Jupyter Notebook:

jupyter notebook "project 2.ipynb"




-----
##📌 Output Summary

Cleaned and standardized dataset saved as Excel.

Pattern type classification for invoices.

Nulls handled and data types corrected.

EDA plots and value counts included for analysis.
