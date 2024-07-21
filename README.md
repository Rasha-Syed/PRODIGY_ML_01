# Task 01: Predicting House Prices with Linear Regression

## Objective
Implement a linear regression model to predict house prices based on their square footage and the number of bedrooms and bathrooms.

### Dataset
- **train.csv**: Contains training data with features and `SalePrice`.
- **test.csv**: Contains test data for making predictions.
- **sample_submission.csv**: Example submission file format for reference.

#### Steps Implemented

##### Data Loading and Exploration
- **Loaded the training and test datasets using Pandas.**
- **Explored the structure and content of the datasets to understand the features and target variable (`SalePrice`).**

##### Data Preprocessing
- **Checked for missing values in both datasets and filled missing values for numeric columns with their mean values.**
- **Selected relevant features (`GrLivArea`, `BedroomAbvGr`, `FullBath`) and defined the target variable (`SalePrice`).**

##### Model Building
- **Split the training data into training and validation sets using `train_test_split`.**
- **Built a linear regression model using scikit-learn's `LinearRegression`.**

##### Model Evaluation
- **Evaluated the model's performance on the training set using Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE).**
- **Assessed the model's generalization performance on the validation set.**

##### Prediction and Output
- **Made predictions on the test dataset using the trained model.**
- **Saved the predictions in a CSV file (`predictions.csv`) structured similarly to `sample_submission.csv`.**

##### Visualization
- **Visualized the actual vs predicted SalePrice using scatter plots for both training and validation datasets to understand model performance visually.**

#### Model Evaluation Metrics
- **Training RMSE**: Root Mean Squared Error on the training data.
- **Training MAE**: Mean Absolute Error on the training data.
- **Validation RMSE**: Root Mean Squared Error on the validation data.
- **Validation MAE**: Mean Absolute Error on the validation data.

### Files Included
- **train.csv**: Contains training data with features and `SalePrice`.
- **test.csv**: Contains test data for making predictions.
- **sample_submission.csv**: Example submission file format.
- **predictions.csv**: Generated CSV file containing predicted house prices for the test dataset.

