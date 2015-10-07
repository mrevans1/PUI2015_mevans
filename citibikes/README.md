# PUI2015_mevans

We looked at citibike data for September 2015 to determine whether or not people ride faster on weekdays.
Out null hypothesis is that people ride at the same speed during weekdays and weekends.
Our alternative hypothesis is that people are faster during weekdays.
We used date time to filter the data into these two groups, and use scipy’s independent t-test to determine whether they come from the ams distribution, and found that they did not. So, we rejected out null hypothesis at a 95% confidence level.
I created a function that estimates Manhattan distances (by road) for starting point - ending point pairs, and used this to estimate speed. After the rest of the group determined which days were weekdays, I filtered the data by this variable for the t test. I helped interpret the results and write documentation.