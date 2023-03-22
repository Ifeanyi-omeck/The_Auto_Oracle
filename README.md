# The_Auto_Oracle
The Auto Oracle is a machine learning model developed to predict the prices of used cars in the US market. The model uses a variety of features such as make, model, year, mileage, location, and other relevant data to predict the price of a used car accurately. The model has been trained on a large dataset of used car sales data, which has allowed it to learn complex patterns and relationships between various features and prices.

# Data Analysis
Before training the model, we performed exploratory data analysis using popular data analysis libraries such as Pandas, NumPy, Matplotlib, and Seaborn. We also used statistical tests such as the chi-squared test to evaluate the significance of the relationships between the categorical features and the target variable.

We preprocessed the data by scaling the numerical features using MinMaxScaler and StandardScaler. We also split the data into training and testing sets using the train_test_split function.

# Machine Learning Libraries
We used several machine learning libraries to train and evaluate the Auto Oracle model. The libraries we used include:

* LinearRegression from scikit-learn's linear_model module
* ElasticNet from scikit-learn's linear_model module
* RandomForestRegressor from scikit-learn's ensemble module

# Evaluation Metrics
We used several evaluation metrics to evaluate the performance of the Auto Oracle model. The metrics we used include:

* mean_absolute_error from scikit-learn's metrics module
* mean_squared_log_error from scikit-learn's metrics module
* mean_squared_error from scikit-learn's metrics module
