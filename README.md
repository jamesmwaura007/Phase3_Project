# Phase3_Project
Customer Churn Prediction
Customer Churn Prediction - SyriaTel

Project Overview

This project aims to predict customer churn for SyriaTel, a telecommunications company. Churn prediction helps businesses retain customers by identifying factors leading to customer attrition. By building a classification model, we can analyze customer behaviors and suggest strategies to reduce churn.

Dataset

The dataset used in this project contains various customer attributes, including:

Account length

Area code

Phone number

International and voice mail plans

Usage metrics (minutes, calls, and charges for different times of the day)

Customer service calls

Churn (Target variable)

Business Objective

Stakeholders: SyriaTel's management, marketing, and customer service teams.

Goal: Develop a machine learning model to predict whether a customer will churn.

Value: Helps in proactive customer retention strategies and business growth.

Data Preprocessing

Handling Missing Values: Checked and confirmed no missing values.

Encoding Categorical Variables: Converted categorical variables into numerical values using Label Encoding.

Splitting Data: Divided into training (80%) and testing (20%) sets.

Feature Scaling: Applied StandardScaler to normalize the dataset.

Models Used

Logistic Regression (Baseline Model)

Decision Tree Classifier

Random Forest Classifier

Evaluation Metrics

Accuracy

Precision

Recall

F1-score

Confusion Matrix

Results

Model

Accuracy

Precision (Churn)

Recall (Churn)

F1-score (Churn)

Logistic Regression

85%

57%

17%

26%

Decision Tree

94%

88%

67%

76%

Random Forest

94%

92%

69%

79%

Best Model: Random Forest Classifier with the highest precision and recall for churn prediction.

Visualizations

The following visualizations were generated:

Churn Distribution (Bar Chart)

Feature Correlation Heatmap

Tenure (Account Length) vs. Churn (Box Plot)

Monthly Charges Distribution by Churn (Histogram)

Feature Importance (Random Forest Model)

Confusion Matrices

ROC Curve for Model Comparison

Findings & Recommendations

Key Factors Influencing Churn:

High customer service call frequency correlates with higher churn rates.

International plan subscribers have a higher probability of churning.

Total call duration and charges impact churn probability.

Business Recommendations:

Improve customer support services to address frequent complaints.

Offer incentives or discounts to high-risk customers.

Target international plan users with better retention offers.

Implement proactive customer engagement strategies based on predicted churn risks.

Next Steps

Further hyperparameter tuning for improved model performance.

Additional feature engineering to enhance prediction accuracy.

Testing other advanced models such as XGBoost and Neural Networks.

Deploying the model into a real-time system for proactive customer retention.

Installation & Usage

Install dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn

Run the Jupyter Notebook to train and evaluate the models.

Explore visualizations to understand key customer behavior trends.

Author

James Kimani Mwaura
