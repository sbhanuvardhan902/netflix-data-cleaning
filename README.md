# netflix-data-cleaning
Netflix Movies and Tv Shows Data Cleaning and Preprocessing


Objectives

- Identify and handle missing values
- Remove duplicates
- Standardize inconsistent text
- Convert dates to datetime format
- Rename columns for uniformity
- Fix and standardize data types

Summary of Changes

- Removed duplicate rows
- Filled missing values in `director`, `cast`, `country`, and `rating` columns
- Converted `date_added` to datetime format
- Standardized column names (e.g., lowercase, underscores)
- Cleaned and stripped whitespace from text columns
- Converted `release_year` to integer
- Created new features: `year_added`, `month_added`, `main_genre`
