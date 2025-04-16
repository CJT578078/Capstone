Analyzing the MSE (mean squared error) of our regression models, both linear regression and random forest regressor 
perform well on the holdout set. It does seem that the linear regression model does perform slightly better. 

Taking a look at STL (Seasonal Trend decomposition using Loess) decomposition trained on data from 2008 - 2010 it appears 
that energy usage peaks in winter months with energy consumption being the lowest in fall months. 

Looking into the average daily use of electrical power, energy consumption seems to peak at 6 pm to 10 pm, while being at 
its lowest from 12 am to 6 am. These hours seem to reflect the times when people get off work and when people go to sleep. 
The weekend seems to have an small increase in energy spent, which might be due to people being home for longer periods. 

Of the three groups of appliances that are tracked, it is clear that the water heater/AC expends the most electrical power. 
The appliances in the kitchen and the appliances in the laundry room seem to use similar amounts of energy. 

Knowing the peak hours of the day and which season the energy grid is most stressed, actions such as increasing the price per 
unit of kW may be taken to dissuade use at such times. This can benefit the energy provider both by increasing revenue as well
as decreasing strain on the energy grid (lowing chances of equipment failure). 

