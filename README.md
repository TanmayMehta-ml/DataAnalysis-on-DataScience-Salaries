# Data Science Job Salaries Prediction

This project focuses on predicting salaries for data science jobs based on various features such as work year, experience level, employment type, job title, remote work ratio, company location, and company size. It utilizes a RandomForestRegressor model to make predictions.

## Dataset

The dataset used for this project is called "Data Science Job Salaries Dataset". It contains information about data science job salaries, including 11 columns:

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

## Model Training

The project involves the following steps for model training:

1. Preprocessing: The dataset is preprocessed by dropping duplicates, replacing values in certain columns, and dropping unnecessary columns.
2. Splitting Data: The dataset is split into predictor variables (X) and the target variable (y).
3. One-Hot Encoding: One-hot encoding is performed on the predictor variables (X) to convert categorical variables into numerical format.
4. Train-Test Split: The data is split into training and test sets using a test size of 0.2.
5. Model Selection: A RandomForestRegressor model is chosen for its ability to handle both categorical and numerical features.
6. Model Training: The RandomForestRegressor model is trained on the training data using the selected parameters.
7. Model Evaluation: The trained model is evaluated on the test data using mean squared error (MSE), mean absolute error (MAE), and R-squared (R^2) scores.

## Testing the Model

To test the trained model with new data, follow these steps:

1. Prepare the test data by creating a DataFrame with the required columns.
2. Preprocess the test data in the same way as the training data (e.g., replacing values, one-hot encoding).
3. Use the trained RandomForestRegressor model to make predictions on the preprocessed test data.
4. Obtain the predicted salary in USD from the model.

Example code for testing the model:

```python
# Replace with the actual name of your trained model
rf_best = RandomForestRegressor(max_depth=10, min_samples_split=10, n_estimators=50, random_state=0)

# Prepare and preprocess the test data
# ...

# Make predictions using the trained model
# ...

print("Predicted salary in USD:", predicted_salary)
