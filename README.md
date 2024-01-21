# Predicting-Optimal-Airfares-through-Advanced-Regression
This project aims to predict flight ticket prices using machine learning techniques. It uses a dataset of flight information like airline, source, destination, stops, and departure time to train regression models and estimate optimal airfares.

Data Exploration and Preparation:
1. Loaded flight dataset and performed exploratory analysis to understand relationships between variables.
2. Handled missing values, cleaned data issues, removed outliers and engineered new features as needed.
3. Selected key features through correlation analysis, domain knowledge and feature importance techniques.

Model Building and Evaluation:
1. Compared performance of linear regression, random forest, XGBoost and SVM regression models.
2. Tuned hyperparameters using grid search to optimize model accuracy.
3. Achieved best model performance with XGBoost with a cross-validation R2 score of 0.74.
4. Improved model explainability through feature importance analysis.

Key Insights:
1. Flight prices are highly influenced by airline, source, destination, stops and departure time.
2. Prices tend to be higher on weekends and early mornings compared to weekdays.
3. Number of stops is correlated to higher ticket prices.

Future Work:
1. Incorporate additional data like fuel prices, demand forecasts and holiday calendars.
2. Experiment with deep learning models like RNNs to model temporal relationships.
3. Containerize model for easy deployment to production environments.

Repository Contents:
1. Flight price data in csv format.
2. Jupyter notebook containing data preparation, analysis and modeling code.
3. README with project overview and instructions.
