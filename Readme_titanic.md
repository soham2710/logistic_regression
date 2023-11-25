# Logistic Regression for Titanic Dataset

This dataset contains information about passengers aboard the Titanic, and it is commonly used for predictive modeling and machine learning tasks.

## Table of Contents

- [Requirements](#requirements)
- [Overview](#overview)
- [Data Handling](#data-handling)
- [Usage](#usage)
- [Files](#files)
- [Instructions](#instructions)
- [References](#references)

## Requirements

Make sure you have the following libraries installed:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

You can install them using `pip` if not already installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Overview

1. Source: The dataset is available as a built-in dataset in the Seaborn library and is derived from the Titanic passenger manifest.
2. Purpose: It is frequently used for binary classification tasks to predict passenger survival based on various features.
3. Features: The dataset includes the following columns:
4. pclass: Passenger class (1st, 2nd, or 3rd)
5. sex: Gender of the passenger (male or female)
6. age: Age of the passenger
7. sibsp: Number of siblings or spouses aboard
8. parch: Number of parents or children aboard
9. fare: Passenger fare
10. embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
11. Target Variable: The survived column indicates whether the passenger survived (1) or did not survive (0).

## Data Handling:

- Handling Missing Values: The dataset has been preprocessed to remove missing values by dropping rows with null values.
- Encoding Categorical Variables: The 'sex' column has been label-encoded to convert categorical gender labels into numerical values.


## Usage

1. Clone this repository or download the script.
2. Make sure you have the required dependencies installed.
3. Run the script using Python:

```bash
python lr_encord_soham.py
```

The script will load the Titanic dataset, perform logistic regression and display evaluation metrics and visualizations.

## Files:
- titanic_data.csv: The original dataset containing passenger information.
- Readme.md: The current file providing information about the dataset.

## Instructions:
- Dependencies: Ensure you have the necessary libraries (NumPy, Pandas, Scikit-Learn, Seaborn, Matplotlib) installed to work with this dataset.
- Usage: Use this dataset for predictive modeling, machine learning exercises, or educational purposes.

## References:
- [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic)
- [Seaborn Documentation](https://seaborn.pydata.org/generated/seaborn.load_dataset.html)
