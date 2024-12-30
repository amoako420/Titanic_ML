# Titanic Dataset Analysis

This notebook, `code.ipynb`, contains an analysis of the Titanic dataset. The goal of this analysis is to explore the data and build a predictive model to determine the survival of passengers.

## Dataset

The dataset used in this analysis is located in the `titanic_data/` directory and includes the following files:
- `train.csv`: The training dataset containing features and the target variable (survival).
- `test.csv`: The test dataset containing features without the target variable.
- `sample_submission.csv`: A sample submission file in the correct format.
- `Amoako_Heskey_submission.csv`: The final submission file.

## Contents

The notebook includes the following sections:
1. **Data Loading**: Loading the training and test datasets.
2. **Data Exploration**: Exploring the data to understand the distribution of features and the target variable.
3. **Data Cleaning**: Handling missing values and preparing the data for modeling.
4. **Feature Engineering**: Creating new features from existing ones to improve model performance.
5. **Model Building**: Building and evaluating different machine learning models.
6. **Prediction**: Making predictions on the test dataset and preparing the submission file.

## Usage

To run the notebook, open `code.ipynb` in Jupyter Notebook or JupyterLab and execute the cells sequentially. Ensure that the `titanic_data/` directory is in the same directory as the notebook.

## Requirements

The following Python libraries are required to run the notebook:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using pip:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn