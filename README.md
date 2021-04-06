# flight-price-prediction
deployed on heroku
https://flightpp.herokuapp.com/

 info:
 This is a Random forest model for predicting flight prices.
 
 #summary
 
LinearRegression : 

- root mse: 2863.9705929717807
 
 - R^2: 0.61959437290701
 
Lasso : 

 root mse: 2866.031260248825
 
 R^2: 0.6190467615317858
 
Ridge : 

 root mse: 2867.952888339789
 
 R^2: 0.6185357441757686
 
DecisionTreeRegressor :

 root mse: 2406.979012127453

R^2: 0.7313081888980144

RandomForestRegressor : 
 
 root mse: 2091.302149061624
 
 R^2: 0.7971647688458681

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
 
 
