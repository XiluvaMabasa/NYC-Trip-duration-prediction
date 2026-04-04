# NYC-Trip-duration-prediction
### Overview
This project focuses on predicting the duration of taxi trips in New York City using historical trip data. Accurate trip duration prediction can improve route planning, pricing strategies, and overall efficiency in transportation systems.

### Dataset
The dataset includes:
-Pickup and drop-off locations
Pickup datetime
Passenger count
Trip distance (derived from Haversine distance)

### Approach
Data cleaning and preprocessing
Feature engineering
Exploratory data analysis to identify patterns in trip duration
Model training using: Linear Regression and Random Forest Regressor
Model evaluation using Root Mean Squared Error (RMSE)

### Key Results
Random Forest outperformed Linear Regression by capturing non-linear relationships
Trip distance was the strongest predictor of trip duration
Time-based features (e.g., pickup time) also influenced trip duration

### Key Insights
Longer distances naturally lead to longer trip durations
Traffic patterns (time of day) impact trip duration
Feature engineering significantly improves model performance

### Future Improvements
Incorporate real-time traffic and weather data
Perform hyperparameter tuning for better model performance
Use more advanced models such as Gradient Boosting

### Background
This project demonstrates regression modelling and feature engineering techniques, forming part of my data science portfolio.
