# Data Science Using Python – Internship Tasks

This repository contains a collection of internship tasks completed as part of the **Data Science Using Python** program.
Each task represents a key stage in the data science workflow — from cleaning raw datasets to exploring patterns and forecasting future trends.

---

# Project Structure

```
📁 Data Science Using Python Internship/
│
├── Task 1 - Data Cleaning & Preprocessing
│   ├── data_cleaning.py
│   ├── dataset.csv
│   └── cleaned_dataset.csv

---

Task 1 – Data Cleaning and Preprocessing

The first step in any data science project is ensuring that the data is accurate, consistent, and ready for analysis. In this task, the goal was to transform raw, messy datasets into clean, structured, and analysis-ready formats using Python. Real-world data often contains missing values, duplicate entries, inconsistent text formats, and incorrect data types that can lead to unreliable results. Therefore, this task focused on identifying such issues, diagnosing their causes, and applying systematic cleaning techniques to improve data quality.

The process began with **data ingestion**, where datasets were imported from various sources such as CSV or Excel files using the `pandas` library. Initial checks were performed to understand the dataset’s structure, including the number of rows and columns, data types, and missing value counts. Next, **duplicate records** were identified and removed using functions like `df.duplicated()` and `df.drop_duplicates()` to ensure data uniqueness. Irrelevant or redundant columns were dropped, while others were renamed and reordered for better clarity and consistency.

Handling **missing values** was a major part of preprocessing. Depending on the nature of the data, missing values were either deleted or filled (imputed) using the mean, median, or mode for numerical and categorical columns. Time-based data, if present, was treated using interpolation techniques. The **data type correction** step ensured that all columns had appropriate types — numerical data stored as text was converted into numbers using `pd.to_numeric()`, and date columns were standardized using `pd.to_datetime()`.

Further, **format standardization** was performed to maintain uniformity across text and categorical data. All text entries were converted to lowercase, leading and trailing spaces were removed, and inconsistent category labels such as `'M'`, `'F'`, and `'male'` were standardized to `'Male'` and `'Female'`. Finally, the cleaned data was validated to confirm that there were no remaining missing or duplicate values. The refined dataset was then saved as a new CSV file for further analysis.

Through this task, key skills such as data profiling, cleaning, and preprocessing using `pandas` and `numpy` were developed. It provided a clear understanding of how to prepare real-world data for analysis, emphasizing accuracy, consistency, and structure. The outcome of this task was a high-quality, analysis-ready dataset that could be confidently used for Exploratory Data Analysis (EDA) and predictive modeling in subsequent stages of the internship.

---

# Key Skills Demonstrated

* Data Cleaning and Preprocessing
* Libraries Used: `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `sklearn`

---

#Outcome

By completing these tasks, a complete end-to-end understanding of the **data science process** was gained — from raw data handling to statistical exploration and predictive modeling.
This internship strengthened both technical and analytical skills essen
