# Customer Churn Analysis Project
This repository provides an analysis of customer churn using a dataset from a telecommunications company. The project explores churn patterns, builds predictive models, and provides actionable insights to reduce customer attrition.

## Dataset Description
The dataset contains information about customers, their service usage patterns, and whether they churned (left the service). It includes the following key features:

* State: The state where the customer resides.
* Account Length: Duration of the customer's account in days.
* Area Code: Numeric representation of the area.
* International Plan: Whether the customer has an international calling plan (yes/no).
* Voice Mail Plan: Whether the customer has a voicemail plan (yes/no).
Service Usage:
* Total day, evening, and night minutes, calls, and charges.
* Total international minutes, calls, and charges.
* Customer Service Calls: Number of calls made to customer service.
* Churn (Target): Boolean flag indicating whether the customer churned.

## Objectives
* Understand churn drivers: Identify key factors contributing to customer churn.
* Predict churn probability: Build machine learning models to predict churn risk.
* Provide actionable insights: Suggest strategies to improve customer retention.


## Key Models and Techniques

### 1. Logistic Regression
A baseline model to understand feature importance and linear relationships with churn.
Provides probabilistic outputs for churn prediction.
Offers interpretable coefficients for actionable insights.

### 2. Decision Tree Classifier
Captures nonlinear patterns and feature interactions.
Visual representation helps in understanding decision paths.
Hyperparameter tuning improves model performance and generalization.
