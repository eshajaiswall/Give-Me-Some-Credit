# Give-Me-Some-Credit

The training data has the following columns:
SeriousDlqin2yrs: The target variable indicating whether the person experienced financial distress in the next two years (1 = Yes, 0 = No).

RevolvingUtilizationOfUnsecuredLines: The percentage of available credit that is being used.

age: The age of the borrower.

NumberOfTime30-59DaysPastDueNotWorse: Number of times the borrower has been 30-59 days past due.

DebtRatio: The ratio of monthly debt payments to monthly income.

MonthlyIncome: The monthly income of the borrower.

NumberOfOpenCreditLinesAndLoans: The number of open credit lines and loans.

NumberOfTimes90DaysLate: Number of times the borrower has been 90 days or more past due.

NumberRealEstateLoansOrLines: Number of real estate loans or lines.

NumberOfTime60-89DaysPastDueNotWorse: Number of times the borrower has been 60-89 days past due.

NumberOfDependents: Number of dependents.


#MODELS BUILD-
1. Logistic Regression-
   ***Logistic Regression model was trained on the training data, achieving an accuracy of  0.933173 and a ROC AUC score of 0.5309, indicating its performance in predicting financial distress based on the given features.***
   
2. Random Forest-
***The Random Forest model, initialized with 100 decision trees and a specified random state for reproducibility, achieved high accuracy (0.9995) and a strong ROC AUC score (0.9968) on the training data. This indicates robust performance in predicting financial distress based on the selected features.***
   
3. XGBoost-
***The XGBoost model, configured without label encoding and using logarithmic loss, achieved an accuracy of 0.946562 and a ROC AUC score of 0.640154 on the training data, demonstrating effective performance in predicting financial distress.***
   
#Conclusion-
***From the above output we can conclude that , The impressive performance of the Random Forest model with nearly perfect accuracy and a very high ROC AUC score underscores its capability and reliability in predicting financial distress. Its robustness in handling complex data relationships and decision-making processes makes it a standout choice for making informed financial decisions based on data-driven insights.***
