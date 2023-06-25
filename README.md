# Data Science Job Salaries Prediction

This project focuses on predicting salaries for data science jobs based on various features such as work year, experience level, employment type, job title, remote work ratio, company location, and company size. It utilizes machine learning models for prediction.

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

## EDA on Data Science Salaries

This section explores the dataset through exploratory data analysis (EDA) techniques to gain insights and visualize different aspects of the dataset.

### About Dataset

The dataset used for this project is called "Data Science Job Salaries Dataset". It contains information about data science job salaries, including various features such as work year, experience level, employment type, job title, and more. The dataset was obtained from a reliable source, [Kaggle](https://www.kaggle.com/datasets/arnabchaki/data-science-salaries-2023).

### Importing Libraries

The following libraries and APIs were used for data analysis, visualization, and machine learning:

- `pandas`: A powerful data manipulation library used for handling and analyzing structured data.
- `numpy`: A library for mathematical operations and array manipulation.
- `country_converter`: An API used for converting country codes to country names.
- `matplotlib.pyplot`: A popular plotting library for creating visualizations.
- `seaborn`: A statistical data visualization library based on matplotlib.
- `plotly`: A library used for interactive and dynamic visualizations.
- `WordCloud`: A library used to generate word clouds for visualizing textual data.
- `nltk`: The Natural Language Toolkit library for text processing and analysis.
- `sklearn`: The Scikit-learn library for machine learning algorithms and evaluation metrics.

### Loading Dataset

The dataset is loaded into the project using the `pd.read_csv()` function from the `pandas` library. The dataset file is located at the specified path.

### Understanding the Data

This section involves analyzing the dataset to gain a deeper understanding of its structure, feature types, and basic statistics. Various operations, such as accessing specific columns, counting unique values, and listing column names, are performed to understand the dataset better.

### Visualization

Data visualization techniques are used to present meaningful insights and patterns from the dataset. This section includes several visualizations, such as word clouds, bar plots, histograms, and pie charts, to showcase different aspects of the dataset.

#### WordCloud of Job Designations

A word cloud is generated to visualize the frequency of different job designations in the dataset. The `WordCloud` library is used for this purpose.

#### Top 10 Highest Paying Jobs

A bar plot is created to display the top 10 highest paying jobs in the dataset. The `seaborn` library is used for this visualization.

#### Salary Distribution

A histogram plot is used to visualize the distribution of salaries in the dataset. The `seaborn` library is utilized for this visualization.

#### Work Year Distribution

A pie chart is created to showcase the distribution of work years in the dataset. The `matplotlib.pyplot` library is used to generate this visualization.
