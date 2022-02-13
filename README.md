# FifaPlayersAnalysis
Exploring the Fifa 2019 players Dataset
Steps:
1.	Get data, Import data: I downloaded the dataset from Kaggle.com and there are tons of other dataset there to explore. 

2.	Data cleaning: This step is perhaps the most time-consuming. In my analysis I had to do a difference of the wage and value series, but they were both containing strings which would make the difference operation not to work. I had to write a function to get convert the strings to int. I also used regex

3.	Extract important features: for my analysis the features which were important to me are the wages and values of each player, I stored the dataframe as df1    

4.	Visualize: used seaborn and bokeh to create interactive plots to help me understand my dataset ore.

