# Predicting Used Car Prices Using Decision Tree Regression

This project aims to predict the selling prices of used cars using a Decision Tree model. The dataset consists of various features such as car name, year, selling price, kilometers driven, fuel type, seller type, transmission type, and ownership details.

# Project Overview
The project involves the following steps:
## Data Loading and Preprocessing:
- The dataset is loaded from a public source and preprocessed for analysis. 
url=https://raw.githubusercontent.com/sahilrahman12/Price_prediction_of_used_Cars_-Predictive_Analysis-/master/car_data.csv
- Various preprocessing techniques are applied, including encoding categorical variables, and concatenating dataset.
## Exploratory Data Analysis (EDA):
- Visualization of data distributions and relationships between variables.
- Insights into the factors influencing Current Selling Price.
## Model Building:
- Decision Tree Regression is employed to model the relationship between the independent variables and the probability of Current Selling Price.
- Some hyper-parameter tuning was performed to increase the accuracy of the model.
## Model Evaluation:
- The model is evaluated using r2_score
- Cross-validation techniques are used to ensure the model's generalizability.
## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- graphviz
- pydotplus
- IPython
 
## Usage

To run this project, clone the repository and execute the Jupyter Notebook. Ensure all dependencies are installed.

## Conclusion

This project demonstrates the application of machine learning techniques to predict car prices based on historical data. The Decision Tree model was initially evaluated, resulting in an R² score of 0.559. After hyperparameter tuning, the model's accuracy slightly improved, achieving an R² score of 0.562. This improvement, though modest, indicates that fine-tuning the model's parameters can enhance its predictive capabilities.
  
