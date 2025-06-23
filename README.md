#  Task 1: Data Cleaning and Preprocessing — Netflix Titles Dataset

This project focuses on cleaning and preprocessing a real-world dataset from Netflix. The task was part of the Elevate Labs Internship program to help interns gain hands-on experience with raw data issues.

---

##  Dataset

- **Source**: [Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File used**: `netflix_titles.csv`

---

##  Cleaning Objectives

-  Identify and handle missing values
-  Remove duplicate records
-  Standardize column names
-  Fix inconsistent formats (e.g., dates, string spacing)
-  Convert data types where required
-  Prepare dataset for analysis or modeling

---

##  Tools Used

- **Language**: Python
- **Library**: Pandas
- **IDE**: Jupyter Notebook

---

##  Key Steps Performed

1. Renamed columns to lowercase and snake_case
2. Removed duplicate rows using `drop_duplicates()`
3. Filled missing values:
   - `director`, `cast`, `country`: `"Unknown"` / `"Not Available"`
   - `rating`, `duration`: Filled with mode
   - `date_added`: Converted to datetime, missing values filled with mode
4. Stripped white spaces from all string columns
5. Set DataFrame index to start from 1
6. Saved cleaned dataset as `netflix_titles_cleaned.csv`

---


##  Files in this Repository

| File | Description |
|------|-------------|
| `Task_01.ipynb` | Jupyter Notebook with all data cleaning code |
| `netflix_titles.csv` | Raw dataset from Kaggle |
| `netflix_titles_cleaned.csv` | Cleaned version of the dataset |
| `README.md` | Project overview and documentation |

---

##  Submission

This repository was created and submitted as part of Elevate Labs’ internship task on [DATE].  