# Titanic Survival Prediction

## Description
This project involves predicting the survival of passengers on the Titanic using various machine learning models.
It demonstrates key aspects of data preprocessing, model training, hyperparameter tuning, and model evaluation.
Learning these aspects is important for building and deploying machine learning models effectively.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
    - [Loading Data](#loading-data)
    - [Data Preprocessing](#data-preprocessing)
    - [Model Training and Evaluation](#model-training-and-evaluation)
3. [Credits](#credits)

## Installation


### Required Libraries used:

* Pandas
* Numpy
* Matplotlib
* Skitlearn

To run this project locally, you need to have Python and Jupyter Notebook installed. Additionally, install the required Python libraries:

```bash
pip install pandas matplotlib scikit-learn

Usage
Loading Data
First, load the Titanic dataset:

import pandas as pd

titanic_df = pd.read_csv("titanic.csv")
titanic_df.head()


Data Preprocessing
Drop Irrelevant Columns:

titanic_df.drop(["Cabin", "Ticket"], axis=1, inplace=True)

Handle Missing Values:

titanic_temp = titanic_df.dropna()

Credits
This project was developed by Pascal Ononaku.

If you have any questions or suggestions, feel free to open an issue or contact me directly via GitHub.

