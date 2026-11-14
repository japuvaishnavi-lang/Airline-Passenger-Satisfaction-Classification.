# &#x20;Airline Passenger Satisfaction Classification

## &#x20;Project Overview

This project focuses on predicting airline passenger satisfaction using Machine Learning classification techniques.

The main objective is to analyze passenger information and service-related factors to classify whether a passenger is satisfied or dissatisfied with their airline experience.

The project includes data preprocessing, model building, hyperparameter tuning, ensemble learning, and prediction on separate test data.

## &#x20;Objectives

- Analyze airline passenger data.
- Identify important factors affecting passenger satisfaction.
- Perform data cleaning and preprocessing.
- Build and compare multiple Machine Learning classification models.
- Evaluate model performance on test data.
- Predict satisfaction for unseen passenger records.

## &#x20;Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## &#x20;Project Structure

```text
Airline-Passenger-Satisfaction-Classification/
│
├── project1_classfi.ipynb
├── train.csv
├── test.csv
├── test_predictions.csv
├── README.md
└── requirements.txt
```

## &#x20;Dataset Description

The dataset contains airline passenger information, including:

- Gender
- Customer Type
- Age
- Type of Travel
- Class
- Flight Distance
- In-flight Services
- Departure and Arrival Delays
- Passenger Satisfaction

**Target Variable:** `satisfaction`

- Satisfied
- Neutral or Dissatisfied

## &#x20;Project Workflow

### 1. Data Loading and Exploration

- Loaded the training dataset using Pandas.
- Checked dataset dimensions and information.
- Analyzed missing values.

### 2. Data Preprocessing

- Handled missing values using median imputation.
- Separated independent and dependent variables.
- Removed unnecessary columns such as ID columns.
- Applied encoding techniques for categorical variables.
- Used StandardScaler for numerical features.

### 3. Train-Test Splitting

- Divided the training data into training and validation sets.
- Used an 80:20 split.
- Applied stratified sampling to maintain class distribution.

### 4. Baseline Model

- Implemented Logistic Regression.
- Evaluated initial model performance.

### 5. Cross Validation

- Applied 5-Fold Cross Validation.
- Calculated mean accuracy and standard deviation.

### 6. Machine Learning Pipeline

- Used ColumnTransformer.
- Implemented SimpleImputer.
- Applied StandardScaler and OrdinalEncoder.
- Created Scikit-learn pipelines.

### 7. Hyperparameter Tuning

- Used GridSearchCV.
- Tuned Logistic Regression parameters.
- Identified the best model parameters.

### 8. Ensemble Learning Algorithms

Implemented and compared:

- Random Forest Classifier
- Hard Voting Classifier
- Soft Voting Classifier
- AdaBoost Classifier

### 9. Model Evaluation

Evaluated model performance using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

### 10. Prediction on Unseen Data

- Loaded separate test data.
- Applied the trained Soft Voting model.
- Generated predictions.
- Compared predicted values with actual values.
- Saved prediction results into a CSV file.

## &#x20;Expected Outcome

The project demonstrates how different Machine Learning classification algorithms can be applied to airline passenger data to predict customer satisfaction.

It also provides practical experience in preprocessing, model training, ensemble techniques, model comparison, and prediction on unseen data.

## &#x20;How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**Step 2:** Install the required libraries.

```bash
pip install -r requirements.txt
```

**Step 3:** Open Jupyter Notebook.

```bash
jupyter notebook
```

**Step 4:** Open `project1_classfi.ipynb`.

**Step 5:** Run the notebook cells in sequence.

## &#x20;Author

**Japu Vaishnavi**

B.Tech – Information Technology

Interested in Data Analytics, Python Programming, Data science and Machine Learning.

## &#x20;Acknowledgement

This project was developed as part of my practical learning in Python and Machine Learning.
