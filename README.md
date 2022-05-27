# Trip Duration Prediction


This project analyzes a set of taxi trips and predicts how long a trip will take from the pickup point to the dropoff point.</br>

It was developed by using <b>Python's</b> `Sklearn` Library. </br>

``` 
1. Data pre-processing.
    ● Remove outliers
    ● Remove pickup and dropoff points outside the city
    ● Add new features based on the trip date like 'day_name', 'day_period' etc.
    ● Perform log transformation on the trip_duration and add it as a new feature
    ● Add the manhattan distance of each trip as a feature
```
```
2. Data Analysis
    ● Busiest pickup and dropoff days, day periods and months
    ● Average trip duration per pickup hour, day period and day of the week
    ● Average trip duration for each vendor
    ● Average trip distance per day of the week
    ● Average speed per hour, day of the week and month
```
```
3. Clustering
    ● K-Means algorithm
    ● 'Elbow' method to find optimal number of clusters
    ● Split pickup points into clusters
```
```
4. Training model
    ● Random Forest Regressor
    ● Find feature importances
    ● Find optimal parameters with GridSearchCV
```
```
5. Predictions
    ● Model performs predictions on the 'log_trip_duration' feature
    ● Find Mean Absolute Error and Mean Squared Error
```
