# Churn Prediction Notebook

This repository contains a churn prediction notebook where I analyze a dataset from Kaggle, perform exploratory data analysis (EDA), preprocess the data, train an Artificial Neural Network (ANN) and an XGBoost algorithm for churn prediction, and evaluate the results.

## Dataset

The dataset used for this churn prediction analysis is sourced from Kaggle [Link to dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). It contains information about various customers and their interactions with a product/service, including features that can potentially impact churn.

## Notebook Contents

1. Exploratory Data Analysis (EDA): In the notebook, I performed an in-depth EDA to understand the distribution of data, identify missing values, and visualize the relationships between different features and the target variable (churn).

2. Data Preprocessing: Before training the models, I treated the data by handling missing values, encoding categorical variables, and scaling numerical features to ensure optimal model performance.

3. Feature Selection: I employed Recursive Feature Elimination (RFE) to rank and select the most important features for predicting churn. This helped in reducing the dimensionality of the dataset and improving model efficiency.

4. Addressing Data Skewness: I used the Synthetic Minority Over-sampling Technique (SMOTE) to address the class imbalance problem and create a balanced dataset, which can lead to better model predictions for minority classes.

5. Model Training and Evaluation:
   - Artificial Neural Network (ANN): I built and trained an ANN using TensorFlow/Keras. The model architecture includes layers with specified activation functions and dropout layers to prevent overfitting.
   - XGBoost Algorithm: I also trained an XGBoost classifier, a powerful gradient boosting algorithm, to compare its performance against the ANN.
   - Evaluation Metrics: I used metrics such as accuracy, precision, recall, F1-score to assess the performance of both models. Confusion matrices were generated to visualize model predictions.

## Requirements

To run the notebook and reproduce the results, you will need to open the notebook in Colab and run through the code cells

## Usage

1. open the notebook in Colab:

2. Download the dataset from the provided Kaggle link and place it in the appropriate folder.

3.  Follow the step-by-step instructions in the notebook to execute each code cell.

## Results

The notebook provides insights into the data, feature importance, and the performance of two different models for churn prediction. The evaluation metrics and visualizations help in understanding the effectiveness of each model in identifying potential churn.






