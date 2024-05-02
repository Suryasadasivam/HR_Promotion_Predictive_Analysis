# HR_Promotion_Predictive_Analysis

# Overview

Human resources (HR) analytics is revolutionizing the way HR departments operate, leading to higher efficiency and better results overall. Predictive analytics in HR allows organizations to identify potential promotees and prepare them in time for their new roles. This project focuses on predicting whether an employee is likely to be promoted based on various attributes related to their past and current performance, as well as demographics.

# Problem Statement

The client, a large multinational corporation (MNC), faces challenges in identifying the right candidates for promotion, particularly for manager positions and below. The current process involves selecting employees based on recommendations or past performance, followed by separate training and evaluation programs for each vertical. However, delays in announcing promotions after evaluation lead to inefficiencies in the promotion cycle. The client seeks to expedite this process by identifying eligible candidates at a particular checkpoint for potential promotion.

# Data Description

The dataset provided by the client includes the following attributes for each employee:

- employee_id: Unique ID for the employee
- department: Department of the employee
- region: Region of employment
- education: Education level
- gender: Gender of the employee
- recruitment_channel: Channel of recruitment for the employee
- no_of_trainings: Number of other trainings completed in the previous year
- age: Age of the employee
- previous_year_rating: Employee rating for the previous year
- length_of_service: Length of service in years
- KPIs_met >80%: Whether the employee met more than 80% of key performance indicators (KPIs)
- awards_won?: Whether the employee won any awards during the previous year
- avg_training_score: Average score in current training evaluations
- is_promoted: Target variable indicating whether the employee is recommended for promotion (1 if promoted, 0 if not)
  
# Approach

- Data Exploration: Explore the dataset to understand the distributions, relationships, and potential patterns in the data.
- Data Preprocessing: Handle missing values, encode categorical variables, and perform feature scaling if necessary.
- Model Selection: Experiment with different machine learning algorithms such as logistic regression, random forest, or gradient boosting to predict promotion likelihood.
- Model Evaluation: Evaluate the performance of the models using appropriate metrics such as accuracy, precision, recall, and F1-score.
- Model Deployment: Deploy the selected model to predict promotion likelihood for new data.

# Requirements
- Python
- Jupyter Notebook
- pandas
- scikit-learn
- matplotlib
- seaborn
