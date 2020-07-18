# House-Price-predictor
ML regression model project to predict house price.

# About the project.
In this project I have implemented regression model to predict the house price on giving it required house data.In this project i have implemented two model one is linear model which takes only the house area in sqft and anothoer model is non-linear regression model multiple inputs.In the project i have used sklrean famework to add many functionality to a project which the framework provides.Finaly on predicting the house price the model2 gives more accurate value compared to basic model1.

# Used cases
* This project can be integrated to a any service provider which includes selling or buying of the houses.
* This will help the user to set correct price to house if they want to sell the house but dont know how much it worths.
* This will also help the user who wants to buy a house and wants to cross check the price which were given on the plartform.


# Technologies used
* Python 
* Sklearn ml framework 
* Matplotlib graph library 
* Numpy for math functions 

# Project output 
```
>> print("-----------------------------------------------------------------------------------")
>> print("Model 1")
>> print("Actual price = {0} But the model predicted = {1}".format(y_test1[2],y_pred_model1[2]))
>> print("------------------------------------------------------------------------------------")
>> print("Model 2")
>> print("Actual price = {0} But the model predicted = {1}".format(y_test2[0],y_pred_model2[0]))
```
### Result
```
-----------------------------------------------------------------------------------
Model 1
Actual price = 320000 But the model predicted = 357409.20109429525
------------------------------------------------------------------------------------
Model 2
Actual price = 221000 But the model predicted = 238982.86095643044

```
