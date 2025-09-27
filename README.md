# H1_B_Visa Prediction
This project aims to predict the case status of H1B visa applications using a dataset from Kaggle. The project involves data cleaning, feature engineering, handling class imbalance using SMOTE, and training a machine learning model (XGBoost) to classify applications as 'CERTIFIED' or 'DENIED'.

## Dataset
The dataset used in this project is the "H-1B Visa Application" dataset from Kaggle. It contains information about H1B visa petitions, including case status, employer details, job title, prevailing wage, worksite location, full time position and so on.

## Project Steps
1)Data Loading and Exploration: Load the dataset and perform initial exploration to understand its structure and content.

2)Data Cleaning and Preprocessing: Handle missing values, convert categorical variables, and address inconsistencies in the data.

3)Feature Engineering: Create new features from existing ones to improve the model's performance.

4)Handling Class Imbalance: Use techniques like SMOTE to address the imbalance in the target variable ('CERTIFIED' vs. 'DENIED').

5)Model Training: Train an XGBoost classifier on the preprocessed data.

6)Model Evaluation: Evaluate the model's performance using metrics such as confusion matrix, classification report, and ROC AUC score.

7)Model Saving and Loading: Save the trained model for future use and demonstrate how to load it to make predictions on new data.


## Technologies Used
Python

Pandas

NumPy

Scikit-learn

Imbalanced-learn

XGBoost

Matplotlib

Pickle


## How to Use
Clone the repository.
Install the required libraries
Run the Jupyter Notebook (H1_B_ML.ipynb) to see the data processing, model training, and evaluation steps.
Use the provided code snippet in the notebook to make predictions on new data by providing the required input features.


## Results
The trained XGBoost model achieved an accuracy of 93% and an ROC AUC score of 93.27% on the test set. The confusion matrix and classification report provide further details on the model's performance.

