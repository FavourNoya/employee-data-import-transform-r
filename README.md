# employee-data-import-transform-r
Data import, cleaning, transformation, and compensation analysis using R.
____
**Overview**

This project focuses on importing, cleaning, transforming, and analyzing employee compensation data using R. The goal was to convert messy Excel data into a structured, analysis ready dataset while generating insights about tenure and compensation growth patterns.

**Tools and Technologies**

R
dplyr
tidyr
lubridate
readxl
ggplot2
scales
writexl

**Project Focus**

Data Import from Excel
Data Cleaning and Type Conversion
Feature Engineering
Compensation Analysis
Tenure Calculation
Regression Modeling
Data Export

**What I Did**

Imported raw Excel data and validated structure
Separated employee names into first and last name columns
Converted compensation fields from formatted strings to numeric values
Converted Excel serial date fields into standard R date format
Calculated employee tenure in years using system date
Created percent compensation increase metric
Formatted compensation fields into standardized US dollar format
Visualized relationship between tenure and compensation increase using regression models
Generated department level scatterplots with trend lines
Exported cleaned and transformed dataset back to Excel

**Key Insights**

Tenure and compensation increase vary across departments
Some departments show weak or near zero correlation between tenure and percent increase
Proper data type conversion significantly improves analytical reliability
Feature engineering enables more meaningful compensation comparisons

**Outcome**

This project demonstrates the ability to transform unstructured operational HR data into structured analytical datasets. It highlights technical strengths in data wrangling, feature engineering, regression visualization, and exporting reproducible outputs.

**What I Learned**

How to convert Excel serial dates into usable date formats
How to clean currency formatted variables for analysis
How to calculate tenure dynamically using system dates
How regression modeling helps evaluate compensation growth patterns
How structured transformation improves data integrity and interpretability
