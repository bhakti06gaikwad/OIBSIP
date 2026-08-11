# Data Quality Report

## Dataset
Titanic Dataset

## Objective
The objective of this project is to assess and improve the quality
of the dataset through data cleaning and preprocessing.

## Data Quality Checks

### 1. Missing Values
Missing values were identified using pandas.
Age and Embarked were handled using appropriate imputation methods.
Cabin was removed because it contained a large number of missing values.

### 2. Duplicate Records
Duplicate records were identified and removed.

### 3. Data Standardization
Text values were standardized by removing unnecessary spaces
and applying consistent formatting.

### 4. Outlier Detection
Outliers were detected using the Interquartile Range (IQR) method.

### 5. Outlier Treatment
Outliers in selected numerical variables were treated using
the IQR method.

### 6. Numerical Standardization
Selected numerical features were standardized using StandardScaler.

## Before and After Comparison

The dataset was compared before and after cleaning based on:
- Number of rows
- Missing values
- Duplicate records
- Data types
- Outliers

## Output

The cleaned dataset was saved as:

Titanic_Cleaned.csv