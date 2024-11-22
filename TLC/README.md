# New York Taxi and Limousine Commission (TLC) Project
## Overview
The New York City Taxi and Limousine Commission (TLC) ask Automatidata to develop a regression model that helps estimate taxi fares before the ride, based on data that TLC has gathered.

The data came from TLC, consists of 22,699 trips and 18 features. The features include information on trip duration and destination, vendor used, payment type and payment amount.

## Content
- Course 1: Project proposal for TLC project.
- Course 2: Preliminary data inspection.
- Course 3: Exploratory Data Analysis (EDA).
- Course 4: Statistical review and A/B testing.
- Course 5: Multiple linear regression model.
- Course 6: Machine learning models (Random Forest and XGBoost).

## Conclusion
### Multiple Linear Regression for predicting taxi fares
Multiple linear regression model is constructed to predict the fares before the ride. This model reach satisfactory results, with predicted vs actual test result reach:
- Coefficient of Determinaton: 0.868
- MAE: 2.134 (Mean Abosulte Error)
- RMSE: 3.785 (Root of Mean Squared Error)

### Machine Learning model for predicting whether a customer will give tip
Finished with original goal, TLC ask Automatidata to further request building machine learning model to predict if the customer will leave the tip or not. After much ethical consideration, Automatidata decided to change the target to predict if the customer will leave a generous tip or not.
After constructing random forest model and XGBoost model (Machine Learning models), Automatidata concluded that random forest will be a champion model with F1 score metric of 0.723 as a main metric.
