# titanic-passenger-survival-analysis-yuvaintern-task1
Titanic Passenger Survival Analysis using Python, Pandas, NumPy and EDA.
# Titanic Passenger Survival Analysis Using Python

## Data Science Fundamentals Assessment – Task 1

### Project Overview
This project focuses on exploring and analyzing the Titanic passenger dataset using Python and fundamental data science techniques.

The project covers dataset understanding, Python programming fundamentals, data cleaning, statistical analysis, and Exploratory Data Analysis (EDA).

### Dataset Information
- **Dataset Name:** Titanic Passenger Dataset
- **File Name:** tested.csv
- **Total Records:** 418
- **Total Columns:** 12
- **Data Source:** Supplied Titanic dataset

### Technologies and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

### Project Objectives

1. Understand the dataset structure, columns, and data types.
2. Apply Python fundamentals, including lists, tuples, dictionaries, sets, loops, conditions, and functions.
3. Perform data cleaning and handle missing values.
4. Calculate statistical measures such as mean, median, mode, standard deviation, variance, and correlation.
5. Perform Exploratory Data Analysis using tables and visualizations.
6. Prepare a detailed data analysis report.

### Data Cleaning
The following data cleaning techniques were applied:

- Missing Age values were replaced using the median.
- Missing Fare values were replaced using the median.
- Missing Cabin values were replaced with "Unknown".
- Duplicate records were checked.
- Text inconsistencies were standardized.
- Data types were verified.

### Statistical Analysis
The following statistical concepts were applied:

- Mean
- Median
- Mode
- Standard Deviation
- Variance
- Correlation Analysis

### Exploratory Data Analysis
The following visualizations were created:

- Passenger Survival Distribution
- Age Distribution
- Survival Rate by Gender
- Survival Rate by Passenger Class
- Correlation Heatmap
- Age and Fare Outlier Detection

### Key Findings
- The dataset contains 418 passenger records.
- The provided survival label indicates 36.36% labelled survivors.
- The average passenger age is approximately 29.60 years.
- The average ticket fare is approximately 35.58.
- The analysis identified 36 potential Age outliers and 55 potential Fare outliers using the IQR method.
- Passenger class and fare show a negative correlation.

### Dataset Limitation
The supplied dataset shows that all female records have Survived = 1 and all male records have Survived = 0. This unusual pattern may indicate that the survival labels are predictions rather than independently verified historical outcomes. Therefore, the findings are interpreted only within the supplied dataset.

### Project Files
- `tested.csv` – Dataset used for analysis.
- `Titanic_Passenger_Survival_Analysis.ipynb` – Google Colab notebook.
- `Titanic_Passenger_Survival_Analysis_Report.docx` – Detailed project report.
- `README.md` – Project documentation.

### Conclusion
This project demonstrates the practical application of Python programming, data cleaning, statistical analysis, and exploratory data analysis. It provides experience in understanding real-world datasets, identifying patterns, interpreting results, and documenting findings using data science techniques.

---

**Project:** Titanic Passenger Survival Analysis Using Python

**Internship:** YuvaIntern – Data Science Internship

**Task:** Data Science Fundamentals Assessment – Task 1
