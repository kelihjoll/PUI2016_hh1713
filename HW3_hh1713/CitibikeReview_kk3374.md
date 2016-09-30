Hey Keli, here are my thoughts on your Citi Bike project. Very interesting and extremely well done!

1. Verify the null and alternative hypotheses are formulated correctly:
Given your idea that the average number of bike trips of a working day in February is higher than the average numbers of bike 
trips on the weekend, H0 is formulated correctly. However, HA is not included in the markdown cell so I would add it and say:
ALTERNATIVE HYPOTHESIS = the average number of bike trips on a weekday is greater than the average number of bike trips on the
weekend. 
I may also add a mathematical formula to test:
HO = weekday_biketrip_mean <= weekend_biketrip_mean
HA = weekday_biketrip_mean > weekend_biketrip_mean

2. Verify the datasets support the idea / project: does the dataset have appropriate variables to to answer the question? 
Is the data pre-processed to extract necessary values?
The dataset created supports the idea. I like that you created a new column in the dataframe to identify each date by a 
numerical value associated with a day of the week. Your process and workflow were extremely clear and easy to read. You 
counted the number of trips associated with each day and summed them and subsequently divided those totals by the total
number of weekdays and weekend days, 20 and 8 respectively, to calculate the average number of trips for each group. 

3. Choose appropriate test to test H0 given the type of data and the type of question asked. 
Based on the hypothesis, I would recommend that you use a t-test because you are testing a difference in means of two
different groups of subjects. 