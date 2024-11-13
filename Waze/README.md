# Waze Project
## Overview
Waze leadership ask the data team to develop a churn predictive model that will help prevent churn, improve user retention, and grow Waze’s business

The data came from Waze, consists of 14,999 trips and 13 features. The features include id, label, sessions, drives, total sessions, days using apps, favorite navigation total, distance drives, duration drives, activity days, driving days, and device used.

### Machine Learning model
After constructing random forest model and XGBoost model (Machine Learning models), the Waze data team concluded that XGBoost model is better than random forest model (recall score of 0.1735 vs 0.1268), recall as a main metric. This model is not a satisfactory model, but can be used to guide further exploratory efforts. The data team recommends a second iteration of this project.
