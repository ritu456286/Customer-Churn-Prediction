# Customer Churn Prediction

## Project Overview

This project is focused on predicting customer churn using machine learning techniques. Customer churn is when a customer stops doing business with a company, and predicting it can help businesses retain customers by identifying patterns that lead to churn.

We have applied three different machine learning algorithms for this task:
- Logistic Regression
- Random Forest Classifier
- Artificial Neural Network (ANN)

Each model was evaluated based on accuracy, and the results are provided below.

## Dataset

The dataset used for this project contains customer information and various attributes that could influence customer churn, such as:
- Demographics (e.g., gender, age)
- Service usage (e.g., tenure, monthly charges, total charges)
- Contract information (e.g., contract type, payment method)
- Features related to churn (target variable)

## Models Used

### 1. Logistic Regression
Logistic Regression is a linear model for binary classification. It is simple yet effective for predicting churn based on the probability of a customer churning (0 or 1).

- **Accuracy**: 0.8796

### 2. Random Forest Classifier
Random Forest is an ensemble learning method that builds multiple decision trees and merges them together to get a more accurate and stable prediction.

- **Accuracy**: 0.8688

### 3. Artificial Neural Network (ANN)
The Artificial Neural Network (ANN) is a deep learning model inspired by the human brain. It consists of multiple layers of neurons that help the model learn complex patterns in the data.

- **Accuracy**: 0.8512

## Installation and Setup

To run the code for this project, you need to have Python and the required libraries installed. You can follow the steps below to set up the project environment:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-churn-prediction.git
   cd customer-churn-prediction
