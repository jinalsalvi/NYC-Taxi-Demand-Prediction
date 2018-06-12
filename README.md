# NYC-Taxi-Demand-Prediction
Predict the taxi demand for yellow cabs with the location in next 10 minutes for new york city.

This python notebook is to develop machine learning model to predict the taxi demand for yellow cabs in new york city with the data provided by the Taxi & Limousine Commission for yellow cabs. Based on the data, machine learning model predicts the pickup demand of cabs in 10 minutes time frame. In this python notebook different machine learning model have been trained and accuracy is tested.

Data Overview
- pick-up and drop-off dates/times,
- pick-up and drop-off locations,
- trip distances,
- itemized fares,
- rate types,
- payment types,
- driver-reported passenger counts

With the given data first, we will do the data cleaning and convert data into the required format.

To divide new york city into the region so that prediction can be done region vise, we will use K-means algorithm.

Feature importance is an important part for any of the machine learning problem. Here we will use below baseline model by generating feature with ratio and previous value at a time (t-1) and will calculate Mean Absolute Percentage Error.
- Moving Averages
- Weighted Moving Averages
- Exponential Moving Averages

Along with that, we will use below regression model by selecting best hyper-parameter with the help of different technique depending on hype parameter to predict the taxi demand.
- Linear Regression
- Random Forest Regressor
- XgBoost Regressor

__Objective: By comparing the different model we will select the best model to predict the Yellow Taxi demand which helps the taxi drivers.__

This project is developed with the help of videos provided by appliedaicourse.com.
