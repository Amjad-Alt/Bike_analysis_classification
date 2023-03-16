# GOCO Bike Sharing System Analysis
This project analyzes six months of data from the GOCO bike sharing system using R, which was obtained from the company's official website.
The data was cleaned and processed to create new columns, and statistical analysis was performed to identify trends and patterns in the usage of
the system. Then we proceed to apply various machine learning models to detect customers' behaviours to suggest a strategy to increase the company's profit.

## Methodology
The data was initially converted to the correct data types and cleaned to remove any missing values or anomalies. 
New columns were created to calculate the duration of bike rides, categorize bike types, and group the data by day, hour, and station.
Statistical analysis was performed using R, including t-tests and confidence intervals to compare the usage patterns of different user 
types and bike types.
### Columns
- Rider ID
- Bike Type
- Start Time and Date
- Stop Time and Date
- Start Station Name
- End Station Name
- Station ID
- Station Lat/Long
- User Type
- Time predioud: create column from (stop time - start time)

## Findings
The analysis revealed several key findings:

- There are 4,069 one-time users and 3,347 Annual members. 
- There are 4012 Electric bike users, 3401 Classis bike users, and 3 Docked bike users. 
- One-time members prefer electric bikes over classic bikes with around 680 users.
- Saturdays and Wednesdays have the most number of users, while Sunday has the least.
- During the weekend hours, the rush hour starts at 9:00 am, while on weekdays it starts earlier at 6:00 am. The number of users drops earlier during the weekends.
- The peak hours of August are between 3:00 pm to 7:30 pm with above 400 users, and this changes with each month. 
- The top 5 stations are Bicentennial Park; North Bank Park; High St & Broad St; Scioto Audubon Center; High St & Warren.
- Accoring to two sample t-test of one-time and annual customers time preiod of usage, 29% of one-time customers use bikes over 30 mins and *30 mins is the critical perioud that the company charges*.
- According to the t-test of the usage time period of customers, 16% of Classic bikes users go over 30 mins, and 4% of Electric bikes users go over 30 mins.

## Recommendations
Based on the findings, we recommend the following actions for the GOCO bike sharing system:

- Stop investing in docked bikes and focus on electric bikes, which are preferred by one-time users.
- Perform maintenance work on Sundays since it has the least number of users.
- Increase the price during peak hours and reduce it on Sundays and other days with low usage.
- Invest more in the top 5 stations and increase the number of bikes. Increase the price for users of these stations and reduce it based on usage patterns in the future.
- Reduce the time boundary to 20 minutes for one-time users, and increase the price margin for Classic bikes used over 30 mins.


## Conclusion
In conclusion, this analysis provides valuable insights into the usage patterns of the GOCO bike sharing system, which can inform the company's future decisions and strategies. By focusing on electric bikes, performing maintenance work on Sundays, and adjusting pricing and inventory based on usage patterns, the company can improve its profitability and customer satisfaction.
