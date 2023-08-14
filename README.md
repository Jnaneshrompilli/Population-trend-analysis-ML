# Population trend analysis
## Aim
The aim of this analysis is to visualize and analyze the global population trend over the past 70 years and develop a predictive model for future world population

## Models
* **Random Forest Regressor**: An ensemble learning algorithm that builds multiple decision trees and outputs the mean/mode of their predictions.

* **Logistic Regression**: Utilized here for regression, it measures the probability of a binary response based on predictor variables.

* **XGBoost Regressor**: A powerful gradient boosting algorithm for supervised regression tasks.

* **Linear Regression**: A  simple linear model assuming a linear relationship between input variables and the output

The models are evaluated using three metrics: R2 score, Mean Absolute Error, and Mean Squared Error. A final score is calculated by combining these metrics to find the best-performing model.


## Conclusion
Based on the final score, Linear Regression excels, making it ideal for predicting future population.

