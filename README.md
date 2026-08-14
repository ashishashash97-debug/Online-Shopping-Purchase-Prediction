# Online Shopping Customer Purchase Prediction

## Project Overview

This project predicts whether an online shopping visitor will make a purchase during a browsing session.

The project uses machine learning classification techniques to analyze online shopping session data and identify factors associated with purchase conversion.

## Problem Statement

An online retailer wants to predict whether a website visitor will make a purchase during a browsing session so that personalized offers can be displayed to potential buyers.

## Objectives

- Clean and preprocess web-session data
- Perform exploratory data analysis
- Analyze browsing behavior associated with purchases
- Build Decision Tree and SVM classification models
- Evaluate models using accuracy, precision, recall and F1-score
- Analyze confusion matrices
- Identify important factors influencing purchase prediction
- Provide recommendations for increasing online sales

## Dataset

Dataset: Online Shoppers Intention Dataset

The dataset contains information about:

- Administrative pages
- Informational pages
- Product-related pages
- Session duration
- Bounce rate
- Exit rate
- Page value
- Traffic type
- Visitor type
- Operating system
- Browser
- Region
- Weekend
- Revenue

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## Machine Learning Models

### 1. Decision Tree Classifier

Accuracy: 89.76%

Precision: 69.41%

Recall: 61.78%

F1-score: 65.37%

### 2. Support Vector Machine

Accuracy: 89.43%

Precision: 74.03%

Recall: 50.00%

F1-score: 59.69%

## Model Selection

The Decision Tree was selected as the preferred model because it achieved higher accuracy, recall and F1-score than the SVM in this experiment.

## Important Features

The major features identified by the Decision Tree include:

1. PageValues
2. BounceRates
3. Month_Nov
4. Total_Duration
5. ProductRelated_Duration
6. Administrative
7. Administrative_Duration
8. ExitRates
9. Total_Pages

## Repository Structure

Online-Shopping-Purchase-Prediction/

├── README.md

├── notebook/

│   └── Online_Shopping_Purchase_Prediction.ipynb

├── data/

│   └── online_shoppers_intention.csv

├── visualizations/

├── models/

│   ├── decision_tree_model.pkl

│   └── svm_model.pkl

├── report/

│   └── Online_Shopping_Customer_Purchase_Prediction_Report.pdf

└── requirements.txt

## How to Run

### Step 1

Clone the repository:

git clone YOUR_GITHUB_REPOSITORY_LINK

### Step 2

Open the project folder:

cd Online-Shopping-Purchase-Prediction

### Step 3

Install dependencies:

pip install -r requirements.txt

### Step 4

Start Jupyter Notebook:

jupyter notebook

### Step 5

Open:

notebook/Online_Shopping_Purchase_Prediction.ipynb

### Step 6

Run all cells from beginning to end.

## Business Recommendations

- Optimize high-value pages
- Reduce bounce and exit rates
- Improve product discovery
- Analyze high-converting traffic sources
- Personalize experiences for different visitor types
- Monitor platform-specific performance

## Conclusion

The project demonstrates how machine learning can be used to predict online purchase conversion from browsing-session data.

The Decision Tree achieved the best overall performance among the tested models and can be used as a starting point for conversion-focused customer targeting.
