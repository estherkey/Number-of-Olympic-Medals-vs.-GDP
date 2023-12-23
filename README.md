# Number-of-Olympic-Medals-vs.-GDP
In this project, we aimed to investigate whether there is a relationship between GDP and number of medals won in the Winter Olympics using the data sourced from Winter Olympics Medal Count dataset and Worldwide GDP History dataset. We performed a simple linear regression analysis with the weighted total
medal points as our response variable and log(GDP) as our explanatory variable. We set up our null hypothesis as β1 = 0, meaning there is no relationship between the two variables and our alternative hypothesis as β1 > 0, meaning there is a positive relationship between the two variables. 
From the results, we obtained β̂0 = -158.733, β̂1 = 7.326, p-value for β̂1 = 7.66e-07, and confidence interval for β̂1 = (4.51, 10.14). Therefore, we reject our null hypothesis and conclude that there is a positive relationship between the total medal points and log(GDP).

The data was collected from the Winter Olympics Medal Count dataset and Worldwide GDP History dataset.
The size of data is 175 rows and 12 columns. This is the data on the countries that won medals in the 10
Olympics, from the 1984 Sarajevo Olympics to the 2018 Pyeongchang Olympics. The collected variables
are host country, host city, participating countries, number of gold, silver, and bronze medals, GDP, GDP per
capita, number of athletes and total medal points. Total medal points are calculated by weighting 6 points for
gold, 4 points for silver, and 3 points for bronze. Countries who won no medals are not included.
b. Statistical Methods:
We assumed that the residuals are independent and identically and normally distributed. We used R to run a
simple linear regression model. Our population model is the following: Total Medal Points = β0 +
β1
log(GDP)i + εi
