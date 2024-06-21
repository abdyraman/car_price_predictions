# Car Price Predictions

Two datasets, one for training and one for testing, contain used car features and their sale prices. 

The majority of the features are categorical. Therefore, I first cleaned the data by removing rows with empty values and then grouped infrequent categories under 'Other'. The numerical features were not altered. 

The target variable, price, was cleaned by removing outliers that were skewing the predictions.

The first model was linear regression with an R² score of 10000, while the alternative model, XGBoost, had an R² score of 3000.

## Files

- `train.csv`: The training dataset. 
- `test.csv`: The test dataset. 
