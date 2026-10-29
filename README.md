# AI-Based Public Complaint Classification System

## Project Overview

This project uses Machine Learning to classify public complaints into their respective categories based on the complaint description entered by the user.

It focuses on civic and municipal issues such as garbage collection, drainage problems, road damage, and streetlight complaints. The model predicts the category of a complaint, helping organise complaints more efficiently.

## Problem Statement

Public complaints are received about various civic issues, and manually sorting them can take time. This project uses Machine Learning to identify the category of a complaint from its text and simplify the classification process.

## Objectives

- Classify public complaints based on their text.
- Predict the category of a new complaint entered by a user.
- Clean and prepare complaint data for model training.
- Evaluate the model using classification metrics.
- Save the trained model for future use.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Machine Learning Algorithm

**Logistic Regression**

CountVectorizer is used to convert complaint text into numerical features that the classification model can process.

## Project Workflow

1. Loaded and inspected the complaint dataset.
2. Handled missing values, empty complaints, and duplicate records.
3. Performed Exploratory Data Analysis (EDA) using visualisations.
4. Separated complaint descriptions and their corresponding categories.
5. Split the data into 80% training data and 20% testing data.
6. Converted complaint text into numerical features using CountVectorizer.
7. Trained the Logistic Regression model.
8. Evaluated the model using accuracy, precision, recall, F1-score, and a confusion matrix.
9. Saved the trained model for future predictions.
10. Added a user-input feature to predict the category of a new complaint.

## Key Features

- Automatic classification of public complaints.
- Prediction of categories for new user-entered complaints.
- Data cleaning and exploratory data analysis.
- Model evaluation using standard classification metrics.
- Saved model for reuse without retraining.

## Sample Input

**Complaint:**  
"The garbage has not been collected from our street for several days."

**Expected Output:**  
Predicted Category: Garbage Collection

*Note: This is an illustrative example. Actual predictions depend on the dataset categories and the trained model.*

## Model Evaluation

The model was evaluated on the test dataset using the following metrics:

| Evaluation Metric | Score |
|---|---:|
| Accuracy | 90% |
| Precision | 90% |
| Recall | 90% |
| F1-score | 89% |

The model achieved 90% accuracy on the test dataset. Precision, recall, and F1-score were also used to assess how well the model classified complaints.

## Dataset

The project uses the Civic and Municipality Complaint System dataset available on Kaggle.

Dataset link: https://www.kaggle.com/datasets/wajahattaj/civic-and-municipality-complaint-system-dataset

## How to Run the Project

1. Open the project notebook in Google Colab.
2. Upload the required CSV dataset.
3. Run the notebook cells in order.
4. Allow the model to complete training and evaluation.
5. Enter a complaint description to predict its category.

## Future Improvements

- Develop a web application for easier access.
- Support complaints in multiple languages.
- Extend the system to cover more civic complaint categories.
- Integrate the system with a municipal complaint management platform.

## Author

Machine Learning project developed using Python and Scikit-learn.
