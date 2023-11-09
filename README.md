# Logistic Regression for Iris Dataset

This Python script demonstrates how to perform logistic regression on the Iris dataset for classification. It covers data loading, model training, hyperparameter tuning, model evaluation, and visualization of results.

## Table of Contents

- [Requirements](#requirements)
- [Usage](#usage)
- [Code Explanation](#code-explanation)
- [Sample Output](#sample-output)

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

## Usage

1. Clone this repository or download the script.
2. Make sure you have the required dependencies installed.
3. Run the script using Python:

```bash
python logistic_regression_iris.py
```

The script will load the Iris dataset, perform logistic regression, tune hyperparameters, and display evaluation metrics and visualizations.

## Code Explanation

- **Loading the Dataset**: The script loads the Iris dataset using `load_iris` from `sklearn.datasets`.

- **Train-Test Split**: It splits the dataset into training and testing sets for model evaluation.

- **Logistic Regression Model**: The script initializes and trains a logistic regression model.

- **Hyperparameter Tuning**: It offers two options for hyperparameter tuning: Grid Search and Random Search.

- **Model Evaluation**: The script evaluates the model using accuracy, a confusion matrix, and a classification report.

- **Interpretation of Model Coefficients**: It prints the coefficients and intercept of the logistic regression model.

- **Visualization**: The script provides visualizations, including a confusion matrix heatmap, an ROC curve, and a feature importance plot.

## Sample Output

You will see various evaluation metrics, visualizations, and interpretations displayed in the console and graphical plots.

For further customization or adaptation to your specific dataset, you can modify the code as needed.
