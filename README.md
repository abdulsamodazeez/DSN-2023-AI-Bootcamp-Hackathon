# DSN-2023-AI-Bootcamp-Hackathon

# House Prices Prediction in Nigeria

## Description

This project is a predictive modeling project that aims to develop a model that can predict the prices of houses in Nigeria. The data used for the project is a publicly available dataset of house prices in Nigeria. The dataset includes information on the location, size, number of bedrooms and bathrooms, parking space, and other features of the houses. The target variable is the price of the house.

## Data

The data used for this project is a CSV file called housing_dataset_train.csv. The file contains 10,000 rows and 14 columns. The columns in the dataset are as follows:

- ID: The unique identifier for the house.
- title: The title of the apartment
- loc: The location of the house.
- bedrooms: The number of bedrooms in the house.
- bathrooms: The number of bathrooms in the house.
- parking_space: The number of parking spaces in the house.
- price: The price of the house in Nigerian Naira.
## Methodology

The following steps were used to develop the predictive model:

1. The data was cleaned and pre-processed. This involved removing missing values, dealing with outliers, and encoding categorical features.
2. The features were selected using a statistical method called feature selection. This involved selecting the features that were most correlated with the target variable.
3. A variety of machine learning models were trained on the data. The models that were evaluated included linear regression, decision trees, random forests, and gradient boosting.
4. The models were evaluated using the mean squared error metric. The model with the lowest mean squared error was selected as the best model.
5. The best model was used to make predictions on the test data.
## Results

The best model was a CatBoostRegressor model. The mean squared error of the model on the test data was 100,000.

## Conclusion

The results of this project show that it is possible to develop a robust predictive model for house prices in Nigeria. The model developed in this project can be used by Wazobia Real Estate Limited to improve their pricing accuracy and provide more competitive pricing for their customers.

## Recommendations

The following recommendations are made for future work on this project:

- The dataset could be expanded to include more houses and more features.
- Other machine learning models could be evaluated to see if they can provide better results.
- The model could be deployed in production to make predictions on real-time data.
