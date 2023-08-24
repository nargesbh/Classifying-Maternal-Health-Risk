# Classifying Maternal Health Risk

## Overview

This GitHub repository contains a machine learning project focused on predicting maternal health risks. The project uses various classification algorithms to analyze maternal health data and predict the risk level of expectant mothers. In this README, you will find an overview of the project structure, how to use the code, and a summary of the results.

## Project Structure

The project is organized as follows:

- **Data**: The dataset used for this project is stored in the `Maternal Health Risk Data Set.csv` file.

- **Code**: The main code for data preprocessing, model selection, and evaluation is provided in the Jupyter Notebook file named `Maternal_Health_Risk_Prediction.ipynb`.

- **README**: This README file provides an overview of the project, how to use the code, and a summary of the results.

## How to Use the Code

To run and use the code in this repository, follow these steps:

1. **Clone the Repository**: Clone this GitHub repository to your local machine using the following command:

```
git clone https://github.com/your-username/maternal-health-risk-prediction.git
```


2. **Install Dependencies**: Make sure you have Python and the required libraries installed. You can install the necessary libraries using pip:

```
pip install pandas matplotlib seaborn numpy scikit-learn scipy
```

3. **Run the Jupyter Notebook**: Open the `Maternal_Health_Risk_Prediction.ipynb` file in a Jupyter Notebook environment. You can do this by running the following command in your terminal:

```
jupyter notebook Maternal_Health_Risk_Prediction.ipynb
```


4. **Execute Code Cells**: Execute the code cells in the Jupyter Notebook one by one. This will load the dataset, preprocess the data, select machine learning models, and evaluate their performance.

5. **Interpret Results**: After running the code, you will see the results of different machine learning models, including their accuracy scores and confusion matrices. You can interpret these results to understand which model performs best for predicting maternal health risks.

 ## Dataset Information

The dataset used in this project contains information related to maternal health risks, including features such as age, blood pressure, blood sugar, body temperature, and heart rate. The target variable is the risk level, which has been encoded numerically.

## Summary of Results

Here is a summary of the results obtained from the machine learning models:

- **Decision Tree**:
- Cross-validation accuracy: 76%
- Test accuracy: 81%
- Train accuracy: 92%

- **K-Nearest Neighbors (KNN)**:
- Cross-validation accuracy: 77%
- Test accuracy: 80%
- Train accuracy: 90%

- **Support Vector Machine (SVM)**:
- Cross-validation accuracy: 69%
- Test accuracy: 73%
- Train accuracy: 71%

- **Random Forest**:
- Cross-validation accuracy: 77%
- Test accuracy: 85%
- Train accuracy: 92%

The Random Forest model appears to have the highest test accuracy, but there is a notable difference between the test and train accuracies, suggesting some degree of overfitting. Further optimization and feature engineering may be required to improve model performance.


