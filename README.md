Predicting Restaurant Tips using Predictive Analytics in Excel

Objective:
The goal of this project was to use Microsoft Excel to build a predictive model that estimates restaurant tip amounts based on customer and transaction details.

Dataset:
The 'Restaurant Tips' dataset includes customer information such as gender, smoker status, day and time of visit, number of diners, total bill amount, and the tip given.

Approach:

Data Cleaning: Checked for missing values—none were found.

Feature Identification:

Dependent Variable: Tip (USD)

Independent Variables: Sex, Smoker, Day, Time, Size, Total Bill

Problem Type: Identified as a regression problem because the target (tip amount) is a continuous variable.

Data Encoding: Used IF statements to convert categorical variables into numeric values to prepare them for regression analysis.

Model Building:

Used Excel’s Data Analysis Toolpak to run linear regression.

Extracted coefficients to create a prediction equation for tips.

Prediction and Evaluation:

Applied the model to generate predicted tip values.

Compared actual vs predicted tips.

Calculated Root Mean Square Error (RMSE) to evaluate model accuracy.

Outcome:
The predictive model was able to estimate tip values with reasonable accuracy. The RMSE value was relatively low, indicating good model performance. The final mathematical equation derived from the regression output can now be used to predict future tips based on customer and order inputs.


