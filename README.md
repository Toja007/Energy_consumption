#                             Energy Consumption Forecasting Model

![download (3)](https://github.com/Toja007/Energy_consumption/assets/131866743/bfa65d1d-1f99-4732-a96e-f81f9daede26)
                                    Energy Consumption Forecasting Model
                    
# Overview
This repository contains an energy consumption forecasting model developed using machine learning techniques. The model is designed to predict energy consumption based on historical data and additional features.

# Dataset Observations
The dataset used for training and testing the model includes the following observations:

Datetime: The timestamp of the data point.
Hour: The hour of the day.
Dayofweek: The day of the week (0 = Monday, 6 = Sunday).
Quarter: The quarter of the year.
Month: The month of the year.
Year: The year.
Dayofyear: The day of the year.
Dayofmonth: The day of the month.
Weekofyear: The week of the year.
Weekday: The weekday (0 = Monday, 6 = Sunday).
Season: The season of the year (e.g., winter, spring, summer, fall).
PJME_MW: The energy consumption in megawatts.
PJME_MW.L1: The lag of energy consumption by 1 hour.

# Model Application
The energy consumption forecasting model is applied in the following steps:

Data Preprocessing: The dataset is preprocessed to handle missing values, convert categorical features into numerical ones (e.g., one-hot encoding), and split the data into training and testing sets.

Feature Engineering: Additional features such as lag variables are created to capture temporal dependencies in the data.

Model Training: The XGBoost regressor model is trained using the training data, with hyperparameters tuned for optimal performance.

Model Evaluation: The model's performance is evaluated using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) on the testing dataset.

Prediction: Once the model is trained and evaluated, it can be used to make energy consumption predictions for future time periods.

# Usage
To use the energy consumption forecasting model:

Clone this repository to your local machine.
Install the necessary dependencies (e.g., pandas, scikit-learn, XGBoost).
Run the provided Jupyter Notebook or Python script to train the model and make predictions.

