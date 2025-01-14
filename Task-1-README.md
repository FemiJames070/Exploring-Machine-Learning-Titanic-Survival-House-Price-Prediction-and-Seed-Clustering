# Exploring-Machine-Learning-Titanic-Survival-Classification.
Dummy Classifier, Decision Tree Classifier, Random Forest Classifier

## Task 1: Data Preprocessing, Visualization, and Classification Models
This task involves preprocessing the Titanic dataset, visualizing important features, and training classification models to predict survival. Models used include a Decision Tree Classifier, a Dummy Classifier, and an improved model with a Random Forest Classifier.

## Workflow Overview
### Data Preparation:
1. Convert categorical columns to numeric using one-hot encoding.
2. Handle missing values by replacing them with column means.
3. Split the dataset into training and test sets (80/20 split).

### Model Training and Evaluation
1. Train and evaluate a Decision Tree Classifier.
2. Compare with a Dummy Classifier baseline.
3. Train and evaluate an Improved Model using the Random Forest Classifier.

### Performance Metrics
Evaluate models using Accuracy and F1 Score on both training and test sets.

### Requirements
To run this task, you need the following:
Python (>=3.7)
pandas
scikit-learn
numpy

### How to Run
1. Load and Preprocess the Data
2. Convert categorical variables (e.g., Sex) into numeric form using one-hot encoding.
3. Handle missing values by filling with column means.

### Train the Models
1. Train a Decision Tree Classifier on Pclass, Age, and Sex features.
2. Use a Dummy Classifier as a baseline.
3. Train an Improved Model using a Random Forest Classifier with additional features.

### Evaluate the Models
Use Accuracy and F1 Score for evaluation.

### Results
1. Dummy Classifier (Baseline)
F1 Score: 0.000, Accuracy: 0.587
2. Decision Tree Classifier:
F1 Score: 0.745, Accuracy: 0.793
3. Improved Random Forest Model
F1 Score: 0.755, Accuracy: 0.804

### File Structure
Titanic-Data-Classification/
task1_preprocessing_and_models.ipynb  # Notebook for Task 1
README.md                             # Documentation for Task 1
requirements.txt                      # List of dependencies

### Acknowledgements
The dataset and lab activity are for educational purposes and demonstrate classification techniques on real-world data.
