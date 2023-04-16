# Car-price-prediction-model
This is a simple car price prediction model that uses linear regression to predict the selling price of a car based on its features such as carwidth, horsepower, enginesize, etc.

Installations

To use this model, you will need Python 3.x and the following Python libraries:

numpy

pandas

sklearn

matplotlib

Dataset Desciption

The data used in the project has following columns:

1   **Car_ID**  Unique id of each car (Interger)
2   **Symboling**  Assigned insurance risk
rating; a value of +3
indicates that the car is
risky; -3 suggests that it is
probably a safe car
(Categorical)
3 **carCompany** Name of car company
(Categorical)
4 **fueltype** fuel-type i.e. petrol or diesel
(Categorical)
5 **aspiration** Aspiration used in a car
(Categorical)
6 **doornumber** Number of doors in a car
(Categorical)
7 **carbody** Body-type of a car
(Categorical)
8 **drivewheel** Type of drive wheel
(Categorical)
9 **enginelocation** Location of car engine
(Categorical)
10 **wheelbase** Weelbase of car (Numeric)
11 **carlength** Length of car (Numeric)
12 **carwidth** Width of car (Numeric)
13 **carheight** Height of car (Numeric)
14 **curbweight** The weight of a car without occupants or baggage
(Numeric)
15 **enginetype** Type of engine (Categorical)
16 **cylindernumber** Number of cylinders placed
in the car engine
(Categorical)
17 **fuelsystem** Fuel system of a car
(Categorical)
18 **boreratio** Bore ratio of car (Numeric)
19 **stroke** Stroke or volume inside the
engine (Numeric)
20 **compressionratio** Compression ratio of an
engine (Numeric)
21 **horsepower** Power output of an engine
(Numeric)
22 **peakrpm** Peak revolutions per minute
(Numeric)
23 **citympg** Mileage in city (Numeric)
24 **highwaympg** Mileage on highway
(Numeric)
25 **price**(Dependent variable) Price of a car (Numeric)

Method:

We have used linear regression to analyse which columns are highly correlated with the price column. We have evaluated the model using various model evaluation methods like R squared, MAE, MSE, RMSE, etc to check the model's efficiency.

Results:

In the end, we can see that the top 5 features which can be used to predict the price of the car are enginesize, horsepower, carwidth, drivewheel and carcompany.
