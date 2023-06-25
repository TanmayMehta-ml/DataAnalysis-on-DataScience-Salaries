# Data Science Job Salaries Prediction

This project focuses on predicting salaries for data science jobs based on various features such as work year, experience level, employment type, job title, remote work ratio, company location, and company size. It utilizes a RandomForestRegressor model to make predictions.

## Table of Contents

1. [EDA on Data Science Salaries](#eda-on-data-science-salaries)
2. [About Dataset](#about-dataset)
3. [Importing Libraries](#importing-libraries)
4. [Loading Dataset](#loading-dataset)
5. [Understanding the Data](#understanding-the-data)
6. [Visualization](#visualization)
   - WordCloud of Job Designations
   - Top 10 Highest Paying Jobs
   - Salary Distribution
   - Work Year Distribution
   - Salary Based on Employment Type
   - Company Size and Average Salaries
   - Experience Level and Salary
7. [Predictive Analysis](#predictive-analysis)
   - Handling Categorical Variables
   - Splitting Training and Testing Data
   - Choosing the Right ML Model
   - Tuning the Hyperparameters of Random Forest

## EDA on Data Science Salaries

This section explores the data through exploratory data analysis (EDA) techniques to gain insights and visualize different aspects of the dataset.

### About Dataset

The dataset used for this project is called "Data Science Job Salaries Dataset". It is sourced from Kaggle and can be accessed [here](https://www.kaggle.com/datasets/arnabchaki/data-science-salaries-2023). The dataset contains information about data science job salaries, including 11 columns:

- `work_year`: The year the salary was paid.
- `experience_level`: The experience level in the job during the year.
- `employment_type`: The type of employment for the role.
- `job_title`: The role worked in during the year.
- `salary`: The total gross salary amount paid.
- `salary_currency`: The currency of the salary paid as an ISO 4217 currency code.
- `salary_in_usd`: The salary in USD (target variable).
- `employee_residence`: Employee's primary country of residence during the work year as an ISO 3166 country code.
- `remote_ratio`: The overall amount of work done remotely.
- `company_location`: The country of the employer's main office or contracting branch.
- `company_size`: The median number of people that worked for the company during the year.

### Importing Libraries

The required libraries for data analysis and visualization are imported in this step.

### Loading Dataset

The dataset is loaded into the project using a suitable method or library.

### Understanding the Data

This section involves analyzing the dataset to gain a deeper understanding of its structure, feature types, and basic statistics.

### Visualization

Data visualization techniques are used to present meaningful insights and patterns from the dataset. This includes various visualizations such as bar plots, histograms, scatter plots, etc.
