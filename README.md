# Flight-price-prediction
deployed on heroku
https://flightpp.herokuapp.com/

 # INFO:
 This is a Random forest model for predicting flight prices.
  
  Dataset- 
- Size of training set: 10683 records
- Size of test set: 2671 records
- FEATURES: Airline: The name of the airline.
- Date_of_Journey: The date of the journey
- Source: The source from which the service begins.
- Destination: The destination where the service ends.
- Route: The route taken by the flight to reach the destination.
- Dep_Time: The time when the journey starts from the source.
- Arrival_Time: Time of arrival at the destination.
- Duration: Total duration of the flight.
- Total_Stops: Total stops between the source and destination.
- Additional_Info: Additional information about the flight
- Price: The price of the ticket
 
 #summary
 
LinearRegression : 

- root mse: 2863.9705929717807
 
 - R^2: 0.61959437290701
 
Lasso : 

 - root mse: 2866.031260248825
 
 - R^2: 0.6190467615317858
 
Ridge : 

 - root mse: 2867.952888339789
 
 - R^2: 0.6185357441757686
 
DecisionTreeRegressor :

 - root mse: 2406.979012127453

 - R^2: 0.7313081888980144

RandomForestRegressor : 
 
 - root mse: 2091.302149061624
 
 - R^2: 0.7971647688458681

# After Hyperparameter tuning
best parameters

{'n_estimators': 700,

'min_samples_split': 15,

'min_samples_leaf': 1,

'max_features': 'auto',

'max_depth': 20}
 
 # Final values 
root mse: 2010.889719116718

R^2: 0.8124632733697996
 
 
