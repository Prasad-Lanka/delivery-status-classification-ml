# delivery-status-classification-ml
Beginner machine learning project for classifying food delivery status using KNN, Naive Bayes, and Decision Tree models.
# Delivery Status Classification using Machine Learning

This is a beginner-level machine learning project focused on classifying food delivery status using different classification algorithms. The project uses a food delivery dataset and applies preprocessing, feature engineering, model training, and performance evaluation.

## Project Overview

The main objective of this project is to predict whether a food delivery order is delayed or not based on delivery-related features such as distance, customer ratings, restaurant ratings, delivery person experience, and other order details.

This project was created as part of my machine learning practice and assignment work.

## Dataset

The dataset used in this project is:

`Food_Delivery_Time_Prediction.csv`

The dataset contains information related to food delivery orders, including:

- Delivery person experience
- Restaurant rating
- Customer rating
- Delivery distance
- Order cost
- Tip amount
- Delivery time
- Other delivery-related features

## Machine Learning Models Used

The following classification algorithms were applied:

1. K-Nearest Neighbors (KNN)
2. Naive Bayes
3. Decision Tree Classifier

These models were trained and evaluated to compare their performance in classifying delivery status.

## Workflow

The project follows these major steps:

1. Importing required Python libraries
2. Loading the dataset
3. Exploring and understanding the data
4. Handling missing values
5. Feature engineering
6. Encoding categorical variables
7. Scaling numerical features
8. Splitting the data into training and testing sets
9. Training machine learning models
10. Evaluating model performance
11. Comparing model results
12. Preparing final conclusions and recommendations

## Model Evaluation

The models were evaluated using classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

These metrics help understand how well each model performs in predicting the delivery status.

## Key Insights

- Delivery distance and delivery-related cost features can influence delivery status.
- Classification models can be used to understand delivery delay patterns.
- Decision Tree models are easy to interpret and useful for understanding feature-based decisions.
- KNN and Naive Bayes provide useful baseline results for classification tasks.

## Important Note

This project is a beginner-level machine learning assignment. Some engineered features may be derived from delivery-time-related information, so the results are mainly for learning model implementation, preprocessing, and evaluation.

## Files in this Repository

```text
delivery-status-classification-ml/
│
├── assign_3.ipynb
├── Food_Delivery_Time_Prediction.csv
├── ass_3_report.pdf
└── README.md
