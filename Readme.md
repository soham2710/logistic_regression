Titanic Dataset
This dataset contains information about passengers aboard the Titanic, and it is commonly used for predictive modeling and machine learning tasks.

Overview:
Source: The dataset is available as a built-in dataset in the Seaborn library and is derived from the Titanic passenger manifest.
Purpose: It is frequently used for binary classification tasks to predict passenger survival based on various features.
Features: The dataset includes the following columns:
pclass: Passenger class (1st, 2nd, or 3rd)
sex: Gender of the passenger (male or female)
age: Age of the passenger
sibsp: Number of siblings or spouses aboard
parch: Number of parents or children aboard
fare: Passenger fare
embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
Target Variable: The survived column indicates whether the passenger survived (1) or did not survive (0).
Data Preprocessing:
Handling Missing Values: The dataset has been preprocessed to remove missing values by dropping rows with null values.
Encoding Categorical Variables: The 'sex' column has been label-encoded to convert categorical gender labels into numerical values.
Usage:
Training and Testing: The dataset has been split into training and test sets (80-20 split) for machine learning modeling.
Model Used: Logistic Regression has been applied as a predictive model for survival prediction based on the selected features.
Files:
titanic_data.csv: The original dataset containing passenger information.
README.md: The current file providing information about the dataset.
Instructions:
Dependencies: Ensure you have the necessary libraries (NumPy, Pandas, Scikit-Learn, Seaborn, Matplotlib) installed to work with this dataset.
Usage: Use this dataset for predictive modeling, machine learning exercises, or educational purposes.
References:
Kaggle Titanic Dataset
Seaborn Documentation - Titanic Dataset
