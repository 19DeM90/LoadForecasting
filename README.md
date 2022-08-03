# LoadForecasting

This jupyter notebook contains python code to forecast the energy demand.
It is mainly based on the scikit-learn package and utilizes three different machine learning algorithms:

1. Linear Regression 
2. Gradient Boosting Regression 
3. Random Forest Regression 

As features for the model training and forecasting, the following inputs are used:

- population weighted temperature 
- wind speed
- irradiance 
- dayspecific data (indicating if a given day is a holiday, weekday or working day)

