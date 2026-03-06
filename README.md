# **Content-Monetization-Modeler**

**Predicting YouTube Ad Revenue using Machine Learning and Streamlit**

**Overview :**

The Content Monetization Modeler is a machine learning project that predicts potential YouTube ad revenue using video performance metrics such as views, likes, comments, and engagement rate.

This project applies Exploratory Data Analysis (EDA), feature engineering, regression modeling, and data visualization to understand the factors that influence content profitability. The final model is integrated into a Streamlit web application for interactive revenue prediction.

**Problem Statement :**

Content creators and media companies rely heavily on video platforms such as YouTube for revenue generation. Predicting potential ad revenue based on video performance metrics can help creators optimize their content strategy and forecast future income.

The objective of this project is to develop a regression model that estimates YouTube ad revenue based on performance metrics and contextual features.

**Tech Used :**

Python ,
Pandas ,
NumPy ,
Scikit-learn ,
Matplotlib & Seaborn ,
Streamlit .

**Dataset Information :**

Dataset Name: YouTube Monetization Modeler

Format: CSV
Size: ~122,000 rows

**Target Variable:**

ad_revenue_usd

**Key Features:**

video_id – unique video identifier

date – upload/report date

views – total video views

likes – total likes

comments – total comments

watch_time_minutes – viewer watch time

video_length_minutes – duration of the video

subscribers – subscriber count of the channel

category – content category

device – viewing device

country – viewer location

**Project Workflow :**

**1. Data Exploration**

Loaded dataset using Pandas

Inspected data structure and statistics

Identified missing values and duplicate records

**2. Data Cleaning & Preprocessing**

Handled missing values (~5%)

Removed duplicate records (~2%)

Encoded categorical variables

Detected and treated outliers

**3. Feature Engineering**

Created new features such as:

Engagement Rate =
(likes + comments) / views

Additional transformations were applied to improve model performance.

**4. Model Development**

Multiple regression models were tested:

Linear Regression

Random Forest Regressor

Decision Tree Regressor

Gradient Boosting

Support Vector Regression

**5. Model Evaluation**

Models were evaluated using:

R² Score

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

The best-performing model was selected for prediction.

**6. Streamlit Application**

A Streamlit web app was developed to allow users to:

Enter video performance metrics

Predict estimated ad revenue

View interactive visualizations

**Repository Structure :**

**Content-Monetization-Modeler**

├── Content_Monetization_Modeler.ipynb
├── streamlit_app.py
└── README.md

**Project Outcomes :**

Built and evaluated multiple regression models for revenue prediction

Identified key factors influencing YouTube ad revenue

Developed an interactive Streamlit dashboard for predictions

Demonstrated a complete machine learning workflow from data preprocessing to deployment
