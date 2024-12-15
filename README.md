# Data Science Jobs Salary Analysis 📊

This project analyzes salary information for **Data Scientist**, **Data Analyst**, **Data Engineer** and **Data Relevant** roles across companies in the USA. The data is processed, explored, and analyzed to extract meaningful insights about salary trends, company ratings, and the impact of skills like Python, R, and Excel.

---

## **Project Overview**
This project involves:
1. **Data Preprocessing**:
   - Removing unnecessary columns.
   - Handling duplicate records.
   - Cleaning and standardizing data fields like `Location`, `Size`, and `Type of Ownership`.
2. **Exploratory Data Analysis (EDA)**:
   - Univariate and bivariate analysis to identify trends in salary distributions, top industries, and top states.
3. **Statistical Analysis**:
   - Hypothesis testing (t-tests) to understand the impact of specific skills on salaries.

---

## **Dataset**
- **Source**: Salary data for data-related roles (Data Scientist, Data Analyst, Data Engineer) across various companies in the USA.
- **Files Included**:
   - `Glassdoor_Salary.csv`: The raw dataset.
   - `Cleaned_Glassdoor_Salary.csv`: The cleaned version of the dataset.

---

## **Technologies Used**
- **Python Libraries**:
   - `Pandas` for data cleaning and manipulation.
   - `Matplotlib` and `Seaborn` for data visualization.
   - `Scipy` for statistical analysis.
- **Environment**: Google Colab

---

## **Project Structure**
This repository contains the following files:

1. **`Data_Preprocessing.ipynb`**  
   - Notebook for data preprocessing, including:
     - Removing unwanted columns.
     - Handling duplicate records.
     - Splitting `Location` into `City` and `State`.
     - Cleaning columns like `Size` and `Type of Ownership`.

2. **`Data_Analysis.ipynb`**  
   - Notebook for exploratory and statistical analysis, including:
     - Visualizing salary distributions, ratings, and company age.
     - Identifying top industries and states for job opportunities.
     - Performing t-tests to determine the impact of Python, R, and Excel skills on salaries.

3. **`Glassdoor_Salary.csv`**  
   - The raw dataset.

4. **`Cleaned_Glassdoor_Salary.csv`**  
   - The cleaned version of the dataset.

---

## **Key Findings**
1. **Salary Distributions**:
   - Most job salaries fall between **50K–150K**.
   - Higher salaries are skewed towards fewer positions.

2. **Top Industries and States**:
   - **Top Industries**: Biotech & Pharmaceuticals, IT Services, and Health Care.
   - **Top States**: California (CA), Massachusetts (MA), and New York (NY).

3. **Impact of Skills**:
   - **Python**: Significantly impacts average salary (p-value < 0.05).
   - **R and Excel**: No statistically significant impact on salaries.

---

### Contact
For questions or suggestions, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/manish-chamarajanagar-mahesh/).
