# Customer Churn Prediction for SyriaTel

## Overview

This project aims to develop a machine learning classifier to predict customer churn for SyriaTel, a telecommunications company. Churn prediction helps the company identify at-risk customers and implement strategies to improve customer retention. The project follows a full data science pipeline, from business understanding to modeling, evaluation, and recommendations.

## Business and Data Understanding

### Stakeholder Audience

The primary stakeholders are SyriaTel’s business executives, customer retention teams, and data analysts. Their main goal is to understand why customers leave and how to prevent churn through targeted interventions.

### Dataset Choice

The dataset consists of customer details, service usage, billing behavior, and churn labels (1 = churned, 0 = retained). Key features include:

- **Account length:** Duration of customer subscription
- **Customer service calls:** Number of calls to support
- **Total day charge:** Customer's total charge for daytime calls
- **International plan:** Whether the customer has an international plan
- **Voice mail plan:** Subscription to a voicemail plan

## Modeling

Two models were implemented:

1. **Baseline Model** – Logistic Regression, chosen for its interpretability.
2. **Improved Model** – Random Forest with hyperparameter tuning, selected for its ability to handle complex patterns and improve accuracy.

## Evaluation

The models were evaluated using classification metrics:

- **Accuracy:** Measures overall correctness.
- **Precision & Recall:** Precision prevents false positives, while recall prevents false negatives.
- **F1-Score:** Balances precision and recall, useful for imbalanced datasets.
- **ROC-AUC Score:** Assesses model’s ability to distinguish between churners and non-churners.

### Key Findings

- The **Random Forest model** outperformed Logistic Regression in predicting churn.
- **Feature Importance Analysis:**
  - High total day charges and frequent customer service calls are strong indicators of churn.
  - Customers with long account tenure tend to be more loyal.

## Conclusion

### Business Recommendations

1. **Proactive Retention Strategies** – Offer discounts or loyalty incentives for high-risk customers.
2. **Customer Service Improvement** – Reduce waiting times and improve issue resolution.
3. **Targeted Marketing Campaigns** – Focus on customers with high total day charges and frequent service complaints.

### Next Steps

- Further analysis using deep learning models.
- Incorporate time-series data for trend analysis.
- Explore additional customer behavior metrics.

This README serves as a bridge between the technical Jupyter Notebook and the non-technical presentation, summarizing methodology and business insights.
