# Week 1 - Titanic Data Analysis

## Project Overview

This project is part of my Week 1 Data Science internship task, focused on Data Acquisition, Data Cleaning, Preprocessing, and Exploratory Data Analysis (EDA) using Python.

The Titanic dataset was used as a publicly available dataset to practice real-world data preparation and analysis techniques.

## Objectives

- Acquire and understand a public dataset
- Identify and handle missing values
- Check for duplicate records
- Perform data cleaning and preprocessing
- Conduct exploratory data analysis
- Create meaningful visualizations
- Identify important patterns and insights from the data

## Dataset

The Titanic dataset contains information about passengers, including:

- Passenger class
- Gender
- Age
- Number of siblings/spouses
- Number of parents/children
- Ticket information
- Fare
- Port of embarkation
- Survival status

The original dataset contains 891 rows and 12 columns.

## Data Cleaning

The following preprocessing steps were performed:

- Checked the dataset structure and data types
- Identified missing values
- Filled missing `Age` values using the median
- Filled missing `Embarked` values using the mode
- Removed the `Cabin` column because it contained a large proportion of missing values
- Checked for duplicate records
- Verified the cleaned dataset

## Exploratory Data Analysis

The analysis includes:

- Missing value analysis
- Survival distribution
- Age distribution
- Survival by gender
- Survival by passenger class
- Correlation analysis

## Key Insights

- The overall survival rate was approximately 38.38%.
- Female passengers had a considerably higher survival rate than male passengers.
- First-class passengers had a higher survival rate compared with second- and third-class passengers.
- Age and passenger class showed useful patterns for understanding survival.
- Passenger class had a negative correlation with survival, while Fare had a positive correlation with survival.

Correlation shows association between variables and does not by itself establish causation.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Data Analysis and Visualization

## Project Files

- `Untitled56.ipynb` - Python/Jupyter Notebook containing the analysis
- `titanic.csv` - Dataset used for the analysis
- `Week_1_Titanic_Data_Analysis_Report.docx` - Detailed project report
- `README.md` - Project documentation

## Conclusion

This project provided practical experience in acquiring, cleaning, preprocessing, and exploring a real-world dataset using Python. The analysis helped identify patterns related to passenger survival and demonstrated the importance of data quality and exploratory analysis before further data science or machine learning tasks.
