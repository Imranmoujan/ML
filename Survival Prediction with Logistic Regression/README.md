# Survival Prediction with Logistic Regression

  This project aims to predict survival probabilities using logistic regression. The dataset used is the Titanic dataset, which contains information about passengers on the Titanic, including their demographics, class, and survival status.

## Project Overview
The project involves the following steps:

### Data Loading and Preprocessing:

- The dataset is loaded from a public source and preprocessed for analysis.
      url=https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv
- Various preprocessing techniques are applied, including handling missing values, and encoding categorical variables.

### Exploratory Data Analysis (EDA):

- Visualization of data distributions and relationships between variables.
- Insights into the factors influencing survival.

### Model Building:

- Logistic Regression is employed to model the relationship between the independent variables and the probability of survival.
- The model is evaluated using various metrics such as accuracy, confusion matrix, and classification report.

### Model Evaluation:

- The performance of the model is assessed, and the results are presented.
- Cross-validation techniques are used to ensure the model's generalizability.

### Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
 
### Usage

To run this project, clone the repository and execute the Jupyter Notebook. Ensure all dependencies are installed.

## Conclusion

This project provides a comprehensive guide to using logistic regression for binary classification problems. The final model achieved an accuracy of **82%** on the test set. This result demonstrates the model's effectiveness in predicting survival based on the available features. The workflow covered data preprocessing, feature engineering, model building, and evaluation, providing a complete example of a machine learning pipeline.


