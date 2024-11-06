# CustomerChurnPrediction

Customer Churn Prediction
Overview
This project is a full-stack application designed to predict customer churn using advanced machine learning models. The core of the system leverages a dataset from Kaggle, which provides the foundation for understanding customer behavior and retention. Through meticulous feature engineering and data preprocessing, the model is trained to provide accurate predictions, ultimately enhancing customer relationship management strategies.

# Objectives
The primary goal of this project is to design robust machine learning models that can accurately predict whether a customer will churn. Key objectives include:

Data Preprocessing: Clean and prepare the dataset for effective model training.

Feature Engineering: Extract and construct features that enhance model performance.

Model Training: Utilize various machine learning algorithms to evaluate their predictive capabilities.

Model Evaluation: Achieve a high recall rate to ensure the model effectively identifies potential churners.

Front-end Development: Create an intuitive user interface to visualize predictions and insights.
Dataset

The dataset utilized for this project is sourced from Kaggle. It contains information on customer behavior, including demographic details, account information, and previous interactions, which are essential for predicting churn.

Machine Learning Models

Multiple models were explored to determine the best performance for predicting churn. Here are some:

Random Forest Classifier (RFC): An ensemble method that operates by constructing multiple decision trees and outputting the mode of their predictions.

XGBoost: A powerful gradient boosting framework that is highly effective for structured data.

Support Vector Classifier (SVC): A classification method that finds the optimal hyperplane to separate different classes in the feature space.

Model Performance

After training and validating the models, the highest recall achieved was 55%. This indicates the model's effectiveness in correctly identifying customers who are likely to churn, which is critical for implementing retention strategies.

Ensembling Techniques

To improve predictive performance, ensembling methods were applied, merging the outputs of multiple models. This approach enhances the robustness of predictions by leveraging the strengths of each individual model.

Front-End Development

The user interface for this project is built using Streamlit, an open-source framework that enables rapid development of web applications in Python. The front-end features include:

Gauge Chart: Visual representation of key metrics related to customer churn.

Linear Bar Chart: Displays the distribution of predictions across different customer segments.

These visual tools provide intuitive insights into the data and model predictions, facilitating easier decision-making.

LLM Integration
To enhance customer interactions, the application integrates with a Large Language Model (LLM) API. This functionality allows for:

Custom Email Generation: Automatically generate personalized emails based on churn predictions.
Explanatory Insights: Provide users with clear explanations regarding the likelihood of customer churn.
