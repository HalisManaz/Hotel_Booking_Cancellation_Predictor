# Hotel Booking Cancellation Predictor

The Hotel Booking Cancellation Predictor is a machine learning project aimed at predicting whether hotel bookings are likely to be cancelled. The model could help hotel managers better manage room inventory and increase overall revenue.

## Project Overview

This project uses a dataset containing information about hotel bookings. The goal is to use this data to train a machine learning model that can predict whether a future booking is likely to be cancelled. This has applications in improving room occupancy rates, optimizing revenue, and enhancing customer satisfaction.

## Dataset

The dataset used in this project contains booking information like the number of adults, children, and babies, the type of meal booked, country of origin, market segment, distribution channel, whether a repeated guest or not, previous cancellations, reserved room type, assigned room type, booking changes, deposit type, agent, company, days in the waiting list, customer type, the average daily rate (ADR), required car parking spaces, total of special requests, and eventually whether the booking was canceled or not.

## Models

Several models were trained and evaluated, including:

- Logistic Regression
- Random Forest
- XGBoost
- XGBoost with hyperparameter tuning and feature engineering

## Installation and Usage

The project is implemented in Python using Jupyter Notebook. The primary libraries used are pandas for data handling, scikit-learn for machine learning algorithms and model evaluation, and XGBoost for the gradient boosting model.

To use this project:

1. Clone the repository.
2. Install the required packages (`pandas`, `scikit-learn`, `xgboost`, `numpy`, and `matplotlib`).
3. Open and run the Jupyter Notebook.

## Results

The XGBoost model with hyperparameter tuning and feature engineering performed the best with an accuracy of 90.52% on both the training and test sets.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

