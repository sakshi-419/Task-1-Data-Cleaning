# Task-1-Data-Cleaning

## Objective

The objective of this task was to clean and preprocess a raw dataset by handling missing values, standardizing categorical data, correcting column formats, and preparing the dataset for further analysis.

## Dataset Used

**Customer Personality Analysis** dataset from Kaggle.

## Tools Used

* Python
* Pandas
* Jupyter Notebook

## Data Cleaning Steps Performed

### 1. Loaded Dataset

* Imported the dataset using Pandas.
* Explored the structure using `head()`, `info()`, and `shape()`.

### 2. Missing Value Treatment

* Identified missing values using `isnull().sum()`.
* Found 24 missing values in the `Income` column.
* Replaced missing values with the median income value.

### 3. Duplicate Check

* Checked for duplicate records using `duplicated().sum()`.
* No duplicate records were found.

### 4. Standardized Categorical Values

#### Education

* `Graduation` → `Graduate`
* `2n Cycle` → `Secondary`
* `Basic` → `Basic Education`

#### Marital Status

* `Together` → `Partnered`
* `Alone` → `Single`
* `Absurd` → `Unknown`
* `YOLO` → `Unknown`

### 5. Renamed Column Headers

* Converted all column names to lowercase.
* Improved consistency and readability.

### 6. Data Type Verification

* Verified data types using `dtypes`.
* Confirmed numerical and categorical columns were correctly formatted.

## Summary of Changes

* Filled 24 missing income values.
* Standardized education categories.
* Standardized marital status categories.
* Renamed all columns to lowercase format.
* Verified dataset quality and consistency.
* Prepared the dataset for analysis and visualization.

## Repository Contents

```text
Task-1-Data-Cleaning/
│
├── data_cleaning.ipynb
├── marketing_campaign.csv
├── cleaned_dataset.csv
└── README.md
```

## Outcome

The dataset was successfully cleaned and transformed into a structured format suitable for exploratory data analysis, visualization, and machine learning applications.

