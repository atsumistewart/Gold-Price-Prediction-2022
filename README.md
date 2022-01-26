# Gold-Price-Prediction-2022
An attempt to create a 'ML goose' that lays golden eggs 

PROJECT IDEA EXPLAINED
With Machine Learning, can we forecast tomorrow's GOLD PRICE using inputs avaiable today? My first Data Science project attempts to answer this question.

What drives GOLD PRICE?
Generally, investors turn to GOLD when we expect an economic downturn / shaky equity markets / inflationary environment, 
and we are looking for a safe-heaven. In economic good times, GOLD is not a great investment as it doesn’t provide any dividend. Moreover, 
unlike copper, most of physical gold is not 'consumed,' but used as storage of value. 
The six features are chosen because they are generally considered good indicators of economic health indicator /equity market indicator / inflationary environment.

With that knowledge, I chose daily data of six independent variables (X) which may explain the movement in GOLD PRICE (y).
These variables are
1) US Inflation (as expressed in US Consumer Price Index),
2) Demand for bonds (as expressed in 5-yr Treasury bond yield),
3) Demand for Crypto Currency (as expressed in ETH Ethereum closing price),
4) Swiss Franc / USD exchange rate,
5) Chinese RMB / USD exchange rate, and
6) Oil Price (as expressed in Crude Oil closing price)

Using historical GOLD PRICE against historical values of the above six features, I tried to run the following four regression models.

1) Decision Tree Regression,
2) Random Forest Regression,
3) XG Boost Regressor, and
4) Multivariable Linear Regression.

Historical data was downloaded from www.NASDAQ.com

CONCLUSION
1) Random Forest Regression Model gave the lowest Mean Square Error
2) Linear Regression Model gave R-Square of 62% and very large MSE
3) The linear regression model's prediction for Jan 14th gold price was off by 3.8%.
as such, we cannot count on my 'ML goose' to lay golden eggs consistently.
