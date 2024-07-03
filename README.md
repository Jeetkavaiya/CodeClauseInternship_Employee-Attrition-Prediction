# Employee Attrition Prediction

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

Employee attrition is a significant concern for many organizations. Predicting which employees are likely to leave the company can help in taking proactive measures to retain valuable talent. This project aims to build a machine learning model to predict employee attrition based on various features such as job satisfaction, salary, and work environment.

## Project Structure


- `data/`: Folder containing raw and processed data.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and model training.
- `scripts/`: Python scripts for data preprocessing, feature engineering, model training, and evaluation.
- `models/`: Folder to save trained models.
- `reports/`: Folder for reports and visualizations.
- `README.md`: Project documentation.
- `requirements.txt`: Python dependencies.
- `config.yaml`: Configuration file for project settings.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Jeetkavaiya/CodeClauseInternship_Employee-Attrition-Prediction.git
    cd Employee-Attrition-Prediction
    ```

2. Create a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Preprocess the data:
    ```sh
    python scripts/data_preprocessing.py
    ```

2. Perform feature engineering:
    ```sh
    python scripts/feature_engineering.py
    ```

3. Train the model:
    ```sh
    python scripts/train_model.py
    ```

4. Evaluate the model:
    ```sh
    python scripts/evaluate_model.py
    ```

## Dataset

The dataset used for this project is hypothetical and contains various features such as:
- Employee ID
- satisfaction_level
- last_evaluation
- number_project
- average_monthly_hours
- time_spend_company
- Work_accident	left
- promotion_last_5years
- Department
- salary
<br/>
You can download the dataset from [here](https://www.kaggle.com/datasets/kmldas/hr-employee-data-descriptive-analytics).

## Feature Engineering

Feature engineering involves transforming raw data into meaningful features that can be used for machine learning. This includes:
- Encoding categorical variables.
- Handling missing values.
- Creating new features from existing ones.

## Modeling

Different machine learning algorithms are used to build the prediction model, including:
- Logistic Regression
- Decision Tree
- Random Forest

Hyperparameter tuning is performed using Grid Search, StratifiedKFold, and Random Search to optimize model performance.

## Evaluation

Model evaluation is done using various metrics such as:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion matrix

Cross-validation is used to ensure the model's robustness.

## Results

The final model's performance is summarized, and important features contributing to employee attrition are highlighted.
The accuracy score of Logistic Regression is 80.13%
The accuracy score of Random Forest is 99.10%
The accuracy score of the best parameter is 98.85%
## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

