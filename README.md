# Customer Lifetime Value Prediction

Customer Lifetime Value (CLV) is a crucial metric for businesses as it represents the projected revenue from a customer throughout their purchasing lifecycle. Accurate prediction of CLV helps businesses make informed decisions about customer acquisition and retention strategies. This project aims to predict the CLV for an Auto Insurance company located in the United States.

## Dataset Description

The dataset provided represents customer data for an Auto Insurance company. It includes various features such as customer demographics, policy information, and historical data. The target variable is the CLV, which we aim to predict accurately.

## Exploratory Data Analysis (EDA)

The initial exploration of the dataset involves examining its structure, summary statistics, and distribution of variables. Key steps in EDA include:

- Loading the dataset and examining its structure using `info()` and `describe()` functions.
- Visualizing the distribution of numeric variables using histograms and correlation matrices.
- Exploring categorical variables to understand unique categories and their distributions.

## Data Preprocessing

Data preprocessing is crucial for preparing the dataset for modeling. Key steps include:

- Handling missing values: Impute or remove missing values as appropriate.
- Encoding categorical variables: Convert categorical variables into numerical format using techniques like one-hot encoding or ordinal encoding.
- Splitting the dataset: Divide the dataset into training and testing sets for model evaluation.

## Model Building

Various regression models are explored for predicting CLV. These include:

- Linear Regression: A basic regression model that assumes a linear relationship between input features and the target variable.
- Decision Tree Regression: A non-linear regression model that splits the data into subsets based on features to make predictions.
- Random Forest Regression: An ensemble method that combines multiple decision trees to improve prediction accuracy.
- Polynomial Regression: A regression technique that models the relationship between input features and the target variable as an nth-degree polynomial.

## Model Evaluation

Models are evaluated using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared. Cross-validation techniques are employed to assess model performance robustly.

## Model Deployment

The best-performing model is selected for deployment. In this case, the Random Forest Regression model shows promising results and is deployed for predicting CLV in real-world scenarios.
