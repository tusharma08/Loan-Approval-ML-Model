# Loan Approval Prediction Model

This repository contains the code for a loan approval prediction model. The model is designed to predict whether a loan will be approved based on various features such as education, employment status, and the number of dependents.

## Project Overview

The goal of this project is to build a predictive model that can accurately determine the likelihood of a loan being approved. This model can be useful for financial institutions to make informed decisions about loan approvals.

## Data

The dataset used for this project is a loan approval dataset, which includes features such as:

- Education level
- Employment status
- Number of dependents
- Loan status (approved or not)

The dataset is loaded from a CSV file named `loan_approval_dataset.csv`.

## Methodology

The project uses the following steps:

1. **Data Exploration**: Initial analysis of the dataset to understand the structure, missing values, and unique values in each column.
2. **Data Preprocessing**: Encoding categorical variables using `LabelEncoder` from `sklearn.preprocessing`.
3. **Feature Engineering**: Visualizing the distribution of categorical features and their relationship with the loan status.
4. **Model Training**: Training two models - Logistic Regression and RandomForestClassifier - to predict the loan status.
5. **Model Evaluation**: Evaluating the models using accuracy score and comparing their performance.

## Models

Two models are used in this project:

- **Logistic Regression**: A simple yet powerful model for binary classification problems.
- **RandomForestClassifier**: An ensemble learning method that operates by constructing multiple decision trees at training time and outputting the class that is the mode of the classes of the individual trees.

## Results

The model's performance is evaluated using the accuracy score. The results are compared between the two models to determine which one performs better on the loan approval prediction task.

## How to Run

1. Clone this repository.
2. Install the required Python packages: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`.
3. Run the Jupyter notebook `Project1.ipynb` to execute the code and see the results.

## Contributing

Contributions are welcome. Please feel free to submit a pull request or open an issue to discuss potential improvements.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
