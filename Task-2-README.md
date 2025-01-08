# Exploring-Machine-Learning - House Price Prediction - Regression Model
Dummy Regressor, Random Forest Regressor

## Task: Predicting House Prices
This project aims to predict house prices using a regression model. The task involves preprocessing the dataset, visualizing important features, and training a regression model to predict the sale price of houses. The model is evaluated using the Root Mean Squared Logarithmic Error (RMSLE) metric.

## Workflow Overview
### Data Preparation:
Data Loading: Load the house prices training and testing datasets.

### Data Preprocessing:
1. Convert categorical columns into numeric format using one-hot encoding.
2. Handle missing values by replacing them with column means.
3. Feature Selection: Identify key features for prediction, such as overall quality, square footage, garage cars, and year built.
4. Data Splitting: Split the dataset into training and testing sets (80/20 split).

### Model Training and Evaluation:
1. Dummy Regressor (Baseline): Use a simple dummy regressor to set a baseline for performance.
2. Random Forest Regressor: Train a Random Forest Regressor model on the training data.
3. Evaluation: Evaluate both the dummy regressor and the Random Forest model using the RMSLE score.

### Performance Metrics
Evaluate models using the RMSLE score to assess prediction accuracy, especially for data with wide value distributions.

### Dependencies:
Python (>=3.7)
pandas
numpy
scikit-learn
seaborn
matplotlib

### How to Run:
1. Load the Data: Load the training and testing datasets from CSV files.
2. Preprocess the Data: Handle missing values and encode categorical features.
3. Train the Models: Train both the Dummy Regressor and Random Forest Regressor models.
4. Evaluate the Models: Compare the RMSLE score of the models.

### File Structure:
HousePricePrediction/
    |-- train.csv               # Training dataset
    |-- test.csv                # Test dataset
    |-- house_price_prediction.py # Python script with code for training and evaluation
    |-- README.md               # Documentation for the project
    |-- requirements.txt        # List of dependencies

### Results:
1. Dummy Regressor (Baseline):
RMSLE Score: 0.446
2. Random Forest Regressor:
RMSLE Score: 0.187

### License:
This project is licensed under the MIT License. See the LICENSE file for details.
