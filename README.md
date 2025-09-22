# Data-Cleaning-and-Preprocessing-Demo

Dataset used: Netflix Movies and TV Shows

Tools used:
Python (Windows)
Kaggle (Dataset)
Pandas and Numpy for data manipulation operations

This repo contains a notebook to clean the Netflix dataset and the resulting cleaned CSV.

What was done
- Removed duplicates
- Dropped rows missing title or type
- Standardized text fields (strip, lowercase)
- Handling other missing values to numpy compatible format
- Formatting including datetime, year, category
- Converted date_added to dd-mm-yyyy consistent string type 
- Converted release_year to integer
- Converted rating to category
- Converted type to category
- Renamed headers to lowercase with underscores(removing spaces)
- Saved cleaned file: `netflix_titles_cleaned.csv`

How to regenerate
1. Create and activate a venv, then install requirements (PowerShell):
    python -m venv .netflix_env
    .\.netflix_env\Scripts\Activate.ps1

2. Open and run `data_cleaning_and_preprocessing.ipynb`. The notebook saves `netflix_titles_cleaned.csv`.

That's all.
