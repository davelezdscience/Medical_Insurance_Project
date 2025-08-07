# Medical Insurance Project

🏥 Medical Insurance Project
This project analyzes a medical insurance dataset to explore the key factors influencing individual insurance charges and build predictive models.

📊 Objective
To develop a regression model that estimates individual medical charges based on features such as age, BMI, number of children, smoking status, and region.

📁 Notebook Overview
Data Loading

Reads the insurance.csv dataset

Displays basic information and structure

Exploratory Data Analysis (EDA)

Descriptive statistics

Visualization of numerical and categorical variables

Outlier detection and correlation analysis

Data Preprocessing

Encoding categorical variables (sex, smoker, region)

Scaling numerical features

Modeling

Train-test split

Model training with:

Linear Regression

Ridge and Lasso Regression

Random Forest Regressor

Evaluation using RMSE and R² metrics

Conclusion

Model performance comparison

Feature importance analysis

🧰 Technologies Used
Python

Pandas

NumPy

Seaborn & Matplotlib

Scikit-learn

📦 Installation
To install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
(You can generate the requirements.txt file by running pip freeze > requirements.txt.)

🧠 Summary
The analysis reveals that variables like age, smoking status, and BMI have a strong impact on insurance charges. Among the tested models, the Random Forest Regressor provided the most accurate predictions in this scenario.