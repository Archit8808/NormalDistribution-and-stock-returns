# NormalDistribution-and-stock-returns

Simple returns : Price today - Price yesterday / price yesterday  #if we are talking on a single day closing scale 


log returns :   log(price today / price yesterday) = ln(1+R(t)) 


Reflection : Log distributions are useful because these graphs are symmetric and bell-shaped. This shape is useful because it can be used to describe many populations.
Usually stock data that we have available isnt in normal destribution , but we can always check it by plotting a histogram and looking for erratic points on the graph with hight 
standard deviation values. 

The clear cut test for this would either be the shapiro wilks test or the KS test which would help us see if the given distribution is close the theoretical distribution 
of normal distribution 

Over larger periods of time, stock data can have some abnormalities and its more probable to notice a non normal distribution and the via verse is true for short periods of time 

Scipy , seaborn and stats were some new libraries used in this project. 
