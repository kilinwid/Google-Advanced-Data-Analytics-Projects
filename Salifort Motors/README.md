# Salifort Motors Project
## Overview
Salifort Motors senior leadership ask the human resources department and the data team to develop a machine learning model that can determine what factors affecting employee to leave the company. With further understanding these factors, the company can improve their employee retention.

The data came from Salifort Motors, consists of 14,999 trips and 10 features. The features include satisfaction level, last evaluation, number of project, average working hours, years working, work accident, employee left, promotion last 5 years, department, and salary.

## Conclusion
### Machine Learning model
After constructing logistic regression (decision tree) model and random forest model (Machine Learning model), the data team concluded the random forest model slightly outperform decision tree model (roc_auc score of 0.967 vs 0.956), roc_auc as a main metric. This scores are achieved after two iterations, with the second iteration drop satisfaction level feature, and engineered a new feature from average working hours feature.
