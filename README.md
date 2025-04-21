# Data-Cleaning-Internship_task_1-
Cleaning & Preprocessing Steps

Step	Description
 Missing Values	Checked using .isnull(), handled with dropna() or fillna()
 Duplicates	Removed using .drop_duplicates()
 Standardized Text	Fixed inconsistent casing and spacing in columns like Gender, Product, etc.
 Date Formatting	Converted Order Date to datetime format
 Column Renaming	Renamed all columns to lowercase with underscores (e.g., Order ID → order_id)
 Data Type Fixes	Converted price to float, quantity to int, order_date to datetime
 Exported Clean Dataset	Saved cleaned dataset as cleaned_sales_data.csv
 
How to Run

Open cleaning_script.ipynb in Jupyter or VS Code.
Make sure Mall_Customers.csv is in the same directory.
Run the notebook step-by-step.
The cleaned dataset will be saved in the same folder.
Tools Used

Python 3.x
Pandas
Jupyter Notebook / VS Code
