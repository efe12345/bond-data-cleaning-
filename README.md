## Overview
The raw dataset contained inconsistent formatting, missing values, and non-numeric entries across key financial fields such as credit ratings, issue price, and yield.

## Key Steps
- Standardized categorical variables (e.g., credit ratings)
- Converted non-numeric values such as "par" into numeric equivalents
- Handled missing values based on financial relevance:
  - Retained unrated bonds
  - Removed observations with missing YTM
- Converted numeric columns from object to float
- Removed empty and irrelevant columns

## Final Dataset
The cleaned dataset has:
- No missing values
- Correct data types for numerical and categorical fields
- Values within reasonable ranges for corporate bond data

## Files
- `bond_data_cleaning.ipynb` – full data cleaning workflow
- `bond_clean.csv` – cleaned dataset ready for analysis
