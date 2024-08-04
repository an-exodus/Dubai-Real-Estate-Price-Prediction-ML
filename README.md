# Dubai Real Estate Price Prediction ML

## Description
This repository contains a research project that applies various machine learning algorithms to predict real estate prices in Dubai. Utilizing a dataset from Bayut, a prominent real estate portal, we compare the performance of four models: Decision Tree, Linear Regression, Random Forest, and Gradient Boosting. The models are evaluated based on Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score metrics.

## Dataset
The dataset, sourced from Bayut.com, includes over 41,000 property listings across various cities in the UAE. Key features include property location, type, size, and other attributes relevant to price estimation.

## Methodology
Four regression models were selected for comparison:

- **Decision Tree Regressor:** Captures non-linear relationships by recursively partitioning the data.
- **Linear Regression:** Assumes a linear relationship between features and the target variable.
- **Random Forest Regressor:** An ensemble of decision trees that improves generalization by averaging multiple trees.
- **Gradient Boosting Regressor:** Sequentially builds models to correct errors from previous ones, enhancing predictive accuracy.

## Evaluation Metrics
- **Mean Absolute Error (MAE):** Measures the average magnitude of errors in predictions without considering their direction.
- **Mean Squared Error (MSE):** Reflects the average of squared differences between predicted and actual values.
- **Root Mean Squared Error (RMSE):** The square root of MSE indicating the standard deviation of prediction errors.
- **R² Score:** Represents the proportion of variance in the dependent variable that is predictable from the independent variables.

## Results
The Random Forest model outperformed other models, making it suitable for real estate price prediction tasks.

## Future Work
- Improve data quality by ensuring completeness and accuracy in categorical variable encoding.
- Explore advanced models such as XGBoost or neural networks and consider additional features like market trends and economic indicators to enhance predictive performance.

## References
- [Scikit-learn documentation](https://scikit-learn.org/)
- [Bayut real estate data on Kaggle](https://www.kaggle.com/datasets/azharsaleem/dubai-real-estate-sales-insights/data)

For more details, refer to the full research paper included in this repository.
