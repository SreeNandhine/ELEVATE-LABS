Data Cleaning and Preprocessing – Task 1

📌 Objective
The goal of this task was to clean and preprocess a raw dataset containing missing values, duplicates, inconsistent formats, and mixed data types. This step is essential before performing any data analysis or visualization.

🛠 Steps Performed
1. Removed Duplicates
        Duplicate rows were dropped to avoid data redundancy.
2. Handled Missing Values
        Age → Missing values filled with the median.
        Name & Country → Missing values replaced with "Unknown".
        PurchaseAmount → Missing values replaced with 0.
        JoinDate → Missing values replaced with default "1900-01-01".
3. Standardized Text Values
       Gender → Converted variations (M, F, male, female, etc.) into standardized male and female.
       Country → Converted to lowercase and standardized (us → usa, uk → united kingdom).
4. Fixed Inconsistent Formats
       Dates → Converted to datetime format (YYYY-MM-DD).
5. Renamed Columns
      Converted all column headers to lowercase with underscores (e.g., CustomerID → customerid).
6. Corrected Data Types
      CustomerID → Converted to integer (Int64).
      Age → Converted to integer.
      PurchaseAmount → Converted to float.

✅ Deliverables
                Raw dataset → raw_dataset_with_issues.csv
                Cleaned dataset → cleaned_dataset.csv
                Python script → data_cleaning.py (contains the code used for cleaning)
                README.md → This file explaining the process

🎯 Outcome
               Created a structured, consistent, and analysis-ready dataset.
               Gained practical experience in handling missing values, duplicates, inconsistent formats, and data type corrections.
