# Cyclone-Preheater ( This file is more than 25 Mb so i uploaded this file in zip file because more than 25 Mb in github the file has not to be uploaded.)
Data was given with 3 attributes of temperature and 3 attributes of pressure.
Then gas outlet temperature was subtracted from gas inlet temperature.
All the subtraction was done to easily identify where the problem/outlying activity was occurring, to easily identify where defect happened in the time series data.
We plotted the data and filled the Null values by backward fill method.
Our Data is prepared here.
First I cleaned the data using Null Value Function I came to know how many null values ​​I have in all the columns
Then I filled all those null values ​​using the fill function.
Then I did relationship analysis so that I can get to know with the help of Correlation and Heatmap.
Then I analyzed the data with the help of histplat, boxplot, jointplot, distplot and pairplot with the help of seaborn library to analyze the data.
Last May I tried to understand the data even better by using pandas profiling where I got complete information of data at one place. Where i got the mean, median , standard deviation, maximum minimum, plot , heatmap and missing value .
