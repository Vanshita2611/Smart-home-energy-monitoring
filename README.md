# Smart-home-energy-monitoring
Objective:
The goal of this project is to analyze a Smart Home dataset containing energy consumption data from various appliances connected to a smart meter, along with weather information. The primary objectives include:

Change Detection:

Detect excessive energy consumption in advance to prevent an increase in usage fees.
Identify change points in the usage tendency of energy consumption.
Predict Future Energy Consumption:

Utilize weather information to predict energy consumption for each appliance.
Optimize energy supply based on the predicted energy consumption.
Weather information features include:
Temperature
Humidity
Visibility
Apparent temperature
Pressure
Wind speed
Cloud cover
Wind bearing
Dew point
Precipitation probability
Precipitation intensity

Methodology:
Data Pre-processing:
Handle missing values and outliers.
Convert timestamps to datetime objects.
Explore data distributions and correlations.
Exploratory Data Analysis (EDA):
Analyze the relationship between energy consumption and time periods.
Visualize trends, patterns, and anomalies.
Understand the correlation between weather features and energy generation.
Anomaly Detection:
Implement ChangeFinder to detect anomalous energy consumption patterns.
Time-Series Modeling:
Use Vector AutoRegressive (VAR) model to capture dependencies between appliances.
Apply Prophet for appliance-specific time-series forecasting.
Utilize LightGBM Regressor for predicting overall energy consumption.
