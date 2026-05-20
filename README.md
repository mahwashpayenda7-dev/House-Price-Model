# House-Price-Model
A machine learning project that predicts house prices using Linear Regression based on square footage, number of bedrooms, and number of bathrooms.
# House Price Prediction Using Linear Regression

This project is a simple machine learning model that predicts house prices using Linear Regression. The model uses important house features such as square footage, number of bedrooms, and number of bathrooms to estimate the selling price of a house.

## Project Objective

The main goal of this project is to understand how Linear Regression works in a real-world prediction problem. By using house-related data, the model learns the relationship between house features and house prices.

## Dataset

The dataset used in this project is an open-source house price dataset. From the dataset, only the most relevant columns were selected for this task:

- `GrLivArea` — square footage of the house
- `BedroomAbvGr` — number of bedrooms
- `FullBath` — number of bathrooms
- `SalePrice` — actual house price

These columns were cleaned and renamed for easier understanding:

- `square_footage`
- `bedrooms`
- `bathrooms`
- `price`

## Machine Learning Model

The model used in this project is:

- Linear Regression

Linear Regression is used because the task is a regression problem, where the goal is to predict a continuous numerical value: the house price.

## Project Workflow

1. Load the dataset
2. Select the required columns
3. Clean and prepare the data
4. Split the data into training and testing sets
5. Train the Linear Regression model
6. Evaluate the model performance
7. Predict the price of a new house
8. Save the trained model

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Joblib
- Jupyter Notebook / Google Colab

  ## Dataset source:
  Hugging Face

## Example Prediction

The model can predict the price of a house based on input values such as:

```python
square_footage = 2000
bedrooms = 3
bathrooms = 2
