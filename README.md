Audiobook Customer Retention Prediction
📘 Project Overview

This project aims to predict returning customers for a fictitious audiobook company using machine learning. The dataset contains customer interaction and feedback data collected over a 2-year period, with the target variable based on customer behavior six months after the initial dataset.

The goal is to identify key factors that influence whether a customer is likely to return, helping the company improve retention strategies and personalize marketing efforts.

🧠 Objectives

Build a predictive model to classify returning vs. non-returning customers.

Analyze customer feedback and engagement patterns over time.

Generate insights that can support data-driven retention strategies.

📂 Dataset

Source: Fictitious Audiobook Company

Timeframe: 2 years of historical data + 6-month target window

Features: Customer demographics, purchase history, feedback ratings, and engagement metrics.

Target: Binary indicator (1 = Returned, 0 = Did not return).

⚙️ Methodology

Data Preprocessing

Handled missing values and outliers

Normalized numerical features

Encoded categorical variables

Extracted behavior-based metrics (e.g., listening frequency, feedback sentiment)

Created temporal features to capture customer lifecycle trends

Model Building

Split dataset into training, validation, and test sets

Used tensorflow and keras to build a model

Evaluated model performance with accuracy

Model Evaluation

Identified the best-performing model for predicting returning customers


🧾 Results

Achieved strong predictive performance in identifying returning customers. Model achieved an accuracy of 85% on test data.

Found that customer feedback scores, engagement duration, and purchase frequency were strong indicators of retention.

💡 Insights

Positive feedback and consistent engagement are major predictors of return likelihood.

First 3 months of customer interaction play a critical role in retention.

Personalized follow-ups for customers with moderate satisfaction ratings can improve long-term return rates.

🧰 Tools & Technologies

Language: Python

Libraries: NumPy TensorFlow/Keras

Environment: Jupyter Notebook

Include text sentiment analysis from open-ended customer feedback.

Experiment with more advanced deep learning architectures (e.g., LSTM for time-based behavior).

Deploy the model as an API or dashboard for real-time retention monitoring.

🧑‍💻 Author

Chukwuma Samuel
Data Analyst | Machine Learning Enthusiast
