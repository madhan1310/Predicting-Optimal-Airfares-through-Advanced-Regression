# Predicting-Optimal-Airfares-through-Advanced-Regression
This project aims to predict flight ticket prices using machine learning techniques. It uses a dataset of flight information like airline, source, destination, stops, and departure time to train regression models and estimate optimal airfares.

Data Exploration and Preparation
Loaded flight dataset and performed exploratory analysis to understand relationships between variables
Handled missing values, cleaned data issues, removed outliers and engineered new features as needed
Selected key features through correlation analysis, domain knowledge and feature importance techniques
Model Building and Evaluation
Compared performance of linear regression, random forest, XGBoost and SVM regression models
Tuned hyperparameters using grid search to optimize model accuracy
Achieved best model performance with XGBoost with a cross-validation R2 score of 0.74
Improved model explainability through feature importance analysis
Key Insights
Flight prices are highly influenced by airline, source, destination, stops and departure time
Prices tend to be higher on weekends and early mornings compared to weekdays
Number of stops is correlated to higher ticket prices
Future Work
Incorporate additional data like fuel prices, demand forecasts and holiday calendars
Experiment with deep learning models like RNNs to model temporal relationships
Containerize model for easy deployment to production environments
Repository Contents
Flight price data in csv format
Jupyter notebook containing data preparation, analysis and modeling code
README with project overview and instructions
