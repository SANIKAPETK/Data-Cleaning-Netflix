# Data Cleaning and Preprocessing - Netflix Dataset

## Objective:
This project involves cleaning and preprocessing the raw Netflix dataset, which includes handling missing values, standardizing text data, dealing with duplicates, and extracting useful features.

## Steps Performed:
1. **Handle Missing Values**:
   - Filled missing values in columns like `director`, `cast`, `country`, `rating`, and `date_added`.

2. **Fix Duration Column**:
   - Extracted numeric and unit parts from the `duration` column and handled missing values.

3. **Standardize Text Data**:
   - Standardized country names such as 'USA' and 'UK' to 'United States' and 'United Kingdom'.

4. **Feature Extraction**:
   - Extracted `added_month` and `added_year` from `date_added`.
   - Created indicator columns for top genres like Documentaries, Comedies, Dramas, Action, and International.

5. **Remove Duplicates**:
   - Removed exact duplicates and near-duplicates based on title, type, and release year.

6. **Outlier Detection**:
   - Visualized distributions of `release_year` and `duration_int` using box plots to detect outliers.

## Tools Used:
- Python (Pandas, Numpy, Matplotlib, Seaborn)
- Google Colab

## Dataset:
- Netflix Movies and TV Shows dataset from Kaggle.

## How to Use:
You can download the cleaned dataset from [here](./cleaned_netflix_titles.csv).
