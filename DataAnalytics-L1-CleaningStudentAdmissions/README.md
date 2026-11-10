
# Data Cleaning: Student Admission Records

## Objective
Clean a deliberately messy student admissions dataset into an analysis-ready one, documenting every decision.

## Dataset
Student Admission Records (Kaggle, author: zeeshier), raw file: student_admission_record_dirty.csv

## Tools
Python, pandas, numpy, Jupyter/Colab

## Cleaning steps
1. Data quality report: nulls, duplicates, dtypes, value ranges
2. Duplicates: removed X rows
3. Missing values: median for numeric columns, mode for Gender and City, rows dropped where Admission Status was missing
4. Standardisation: consistent gender labels, capitalisation and trimmed spaces
5. Impossible values (e.g. percentages above 100) set to missing, then imputed
6. Outliers: detected with the IQR method and capped
7. Data types corrected

## Before vs. after
(paste screenshot of your comparison table)

## Files
- DataCleaning_StudentAdmissions.ipynb: full notebook
- student_admission_cleaned.csv: cleaned output
