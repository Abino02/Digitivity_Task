# Customer Churn Prediction using Machine Learning

## Project Overview

This project focuses on predicting customer churn in a banking dataset using machine learning techniques and rule-based logic. Customer churn refers to the situation where a customer leaves a company or stops using its services. Predicting churn is important for businesses as it helps in improving customer retention and decision-making strategies.

## Dataset Description

The dataset used in this project is "Churn_Modelling.csv", which contains information about 10,000 customers. The target variable is "Exited", where a value of 1 indicates that the customer has churned and 0 indicates that the customer has not churned. The dataset includes features such as credit score, geography, gender, age, tenure, balance, number of products, credit card status, activity status, and estimated salary. Columns such as RowNumber, CustomerId, and Surname were removed during preprocessing as they do not contribute to prediction.

## Data Preprocessing

The project begins with loading the dataset using Pandas and performing data preprocessing steps. Categorical variables such as Geography and Gender were converted into numerical format using encoding techniques. The dataset was then checked for missing values to ensure data quality. After preprocessing, the data was divided into input features and target variable for model training.

## Model Development

The dataset was split into training and testing sets in an 80:20 ratio. Two machine learning models were implemented for comparison. Logistic Regression was used as a baseline model due to its simplicity and effectiveness in binary classification problems. A Decision Tree Classifier was also implemented to capture more complex patterns in the data.

## Model Evaluation

Both models were trained on the training dataset and evaluated on the testing dataset using accuracy as the performance metric. The results showed that Logistic Regression provided stable and consistent predictions, while the Decision Tree model was able to capture more complex relationships in the data but may be prone to overfitting. The accuracy values obtained from both models were compared to determine the better performing model.

## Rule-Based Approach

In addition to machine learning models, a rule-based churn prediction system was implemented using simple conditions based on features such as age, balance, activity status, and credit score. This approach is easy to understand and interpret but is less flexible and less accurate compared to machine learning models.

## Data Visualization

A basic data visualization was included to show the distribution of churned and non-churned customers. This helps in understanding the dataset characteristics and class balance.

## Conclusion

This project demonstrates the application of data preprocessing, machine learning algorithms, and rule-based logic in solving a real-world problem. It highlights the importance of model selection, evaluation, and interpretability in building effective predictive systems.

## How to Run

To run this project, install the required Python libraries including pandas, numpy, scikit-learn, and matplotlib. Open the Jupyter Notebook file and execute all cells to reproduce the results. The project consists of the notebook file, the dataset, and this README file.

## Author

Abino F

## Acknowledgement

This project was developed as part of an internship assessment to demonstrate skills in data analysis, machine learning, and problem-solving.
