# Bank Marketing Campaign - Machine Learning Model

This project focuses on developing a machine learning model to improve the efficiency of a bank's marketing campaign for term deposit products. By leveraging data to predict which customers are most likely to subscribe, the model aims to optimize marketing efforts and reduce costs.

## Table of Contents
- [Context](#context)
- [Problem Statement](#problem-statement)
- [Goal](#goal)
- [Business Problem](#business-problem)
- [Analytic Approach](#analytic-approach)
- [Data Preparation](#data-preparation)
- [Model Development](#model-development)
- [Evaluation and Results](#evaluation-and-results)
- [Recommendations](#recommendations)
- [Usage](#usage)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Context
The bank offers term deposit products and runs marketing campaigns to acquire new customers. However, these campaigns are not always efficient, often leading to wasted resources. The aim is to improve this by targeting customers who are most likely to subscribe.

## Problem Statement
The problem is to improve marketing efficiency by developing a model that can accurately classify which customers are likely to subscribe to a term deposit.

## Goal
To develop a machine learning model that classifies customers as likely or unlikely to subscribe to a term deposit.

## Business Problem
Inefficient marketing campaigns result in higher costs and lower customer acquisition rates. Optimizing marketing efforts with a predictive model can reduce expenses and increase effectiveness.

## Analytic Approach
1. **Exploratory Data Analysis (EDA):** Understand the data distribution and identify patterns.
2. **Data Preprocessing:** Clean and preprocess the data to prepare it for modeling.
3. **Model Development:** Develop and evaluate various machine learning models.
4. **Model Tuning:** Perform hyperparameter tuning to optimize model performance.
5. **Model Deployment:** Deploy the final model for real-time predictions.

## Data Preparation
- No null values or mismatched data types.
- Identified and handled outliers.
- Selected relevant features for modeling.

## Model Development
- Split the data into training and testing sets.
- Applied feature engineering techniques such as one-hot encoding and scaling.
- Tested several models and found the Gradient Boosting Classifier to have the best performance.

## Evaluation and Results
- **Benchmark Model:** Gradient Boosting Classifier showed the best test score and stability.
- **Hyperparameter Tuning:** Improved train score but test score remained the same.
- **Feature Importance:** Refined feature selection process based on importance scores.
- **Final Model:** Improved overall scores and stability.

## Recommendations
- Find new and creative marketing strategies.
- Develop new models with different objectives.
- Regularly review and refine campaign performance.
- Collaborate with other teams to align campaigns with customer insights and business objectives.

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```
2. Navigate to the project directory:
    ```bash
    cd your-repo-name
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
5. Open and run the `capstone 3_1.01.ipynb` notebook to see the project details and results.

## Installation
To set up the project on your local machine, follow these steps:
1. Ensure you have Python installed.
2. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
