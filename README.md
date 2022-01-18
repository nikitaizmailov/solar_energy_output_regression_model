# solar_energy_output_regression_model

### Aim of the project: find the most optimal and accuracte model to forecast the next day solar output for a solar farm measured in kWh using the datasets like waether forecast and solar radiation for the day ahead.

I have trained and cross-validated 4 models (Linear Regression, Random Forest Regression, SVM model and Recurring Neural Network LSTM) and used Root-Mean-Squared Error to check which model's performance is better i.e. which has the smallest error.

Also built data processing pipeline which had transformers like SimpleImputer and MinMaxScaler.

I split the dataset into 80% train and 20% test dataframe.
