# Analyzing the Relationship Between the Number of Impression and Amount Spent in SnapChat in 2019

Using [Snapchat Election Advertising Data](https://www.snap.com/en-US/political-ads/), I was able to get number of impressions for an advertisement for year 2019.
The reason why I didn't choose 2020 is because i was worried that i will not get an accurate answer due to the lack of data since it has not been a full year yet.
Relatively, 2019 is the recent year that will have a sufficent data. 

After I got the data, I filtered it so I could only get the 2019 data.
Then, I deleted start date and the end date, and created a new column of 'duration.'
With it, I was able to see the length of the time or duration clearly and easily.

Afterward, I used 'regression' in 'data analysis' to analyze the data in depth.

## Regression Output for Number of Impression and Amount Spent in 2019
![alt text](https://github.com/ywonjun1021/Analyzing-the-Relationship-Between-the-Number-of-Impression-and-Amount-Spent-in-SnapChat-in-2019/blob/master/Data%20Analysis-%20project%202.png)

R squared represents the percent of the data that can be represented by this line. 
The higher the R squared is, the better because that means that the line will be more accurate.
Based on the regression output, R squared was 0.742, meaning that 74 percent of the data is shown using this model

Significance F is the probability of non of the variables having an impact for impression.
The lower the better, since I got 0, it shows that variables are impacting the impression

If the P-value is greater than 0.5, that means the statistic is a bad representation.
Since spending is 0, I can interpret that it has a very good correlation. 

## Linear Regression Graph for Number of Impression and Amount Spent in 2019

![alt text]


