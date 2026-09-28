# Housing Price Prediction

This repository contains a machine learning assignment using the Ames Housing dataset.

The goal of the project is to prepare housing data, train different regression models, evaluate their performance, and answer the questions provided in the assignment (Q1–Q7).

## Project files

- `housing_price_prediction.ipynb`  
  The main Jupyter Notebook containing the complete solution to the assignment.  
  It includes the code, data preprocessing, model training, evaluation, visualizations, and written answers to questions Q1–Q7 from the assignment.

- `AmesHousing.csv`  
  The dataset used for the machine learning models.  
  The target variable is `SalePrice`.

- `Assignment_1_Housing_Price_Prediction.docx`  
  The original assignment description, including the tasks and questions Q1–Q7.

## Machine Learning Models

Three regression models are trained and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

The same prepared features are used for all three models to make the comparison fair.

## Workflow

The project follows these main steps:

1. Load and explore the Ames Housing dataset
2. Separate features (`X`) from the target variable (`SalePrice`)
3. Split the data into training and test sets
4. Preprocess the data
5. Train the regression models
6. Evaluate the models using:
   - RMSE (Root Mean Squared Error)
   - R² score
7. Visualize actual vs. predicted house prices
8. Compare and interpret the model results
9. Answer the assignment questions Q1–Q7

## Requirements

The project uses Python and Jupyter Notebook with the following libraries:

- pandas
- numpy
- scikit-learn
- matplotlib

## Running the project

1. Clone or download the repository.
2. Make sure `AmesHousing.csv` is located in the same project folder as the notebook.
3. Open `housing_price_prediction.ipynb` in Jupyter Notebook, JupyterLab, or an IDE that supports notebooks.
4. Run the notebook cells from top to bottom.

## Dataset

The project uses the Ames Housing dataset, which contains information about residential properties and their sale prices.

`SalePrice` is used as the target variable that the machine learning models attempt to predict.
