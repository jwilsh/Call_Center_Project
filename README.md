# Call_Center_Project
Portfolio practice project using a call center dataset


# Scenario
Welcome to this portfolio practice project where I have taken a look at a call center dataset and found some insights. The data includes information from a call center about each call that the center receives. The data records information about the caller and agent who participated in the call and more importantly feedback from the customer such as their sentiment and a csat score. Using this information we can find out some insights about if agents are respecting the SLA provided and how satisfied the customers are with the service. The customers table also includes some demographic data so we can further analyse based on demographics and by call center location.

## Data Cleaning
Firstly the data and checked and cleaned using Google sheets. The only issues found with the data was that csat scores weren’t given for each call and there was a lot of missing demographic information potentially due to customers ringing from private or withheld numbers. However this is still important to take into consideration. The next slides then show some of the analysis that I did using SQL.

# Findings
. Do we have certain agents who respond to calls in a timely matter? As we can see from the data 75.3% of the calls were responded to in a timely matter.



. Are any agents having poor response time? In order to see which agents responded in a timely matter and which had a poor response time, i’ve showed the top 10 agents with the most responses above SLA and the top 10 with responses below SLA.



. What about customer ratings towards them? As you can see from the tables there isn’t much difference in CSat score between the highest ranked and lowest ranked agents according to their customer response times.



. Where are our most loyal customers located? Unfortunately there is a lot of missing data related to the location of the customers calls. However from what data we have we can see the top 10 ranked states and cities. California has been broken down to show the top 10 cities within the state.



. Are there certain call centers that perform well? Not well? Are there certain channels that perform well? Not well? As you can see from the table there isn’t much different in terms of Csat score between all of the different call centers.




. How do our customers feel about our service? You can also see that when you break down the SLA times of each call center by % there are all this very similar. Even when we break down each call center by sentiment we can see that this is almost identical. Lastly if we go back to the Top 10 agents earlier based on SLA responses we can see that just because an agent has a good response time doesn’t necessarily mean that the customer is satisfied with their service.





# Key Findings
. The customer satisfaction can be looked at in several different ways from the data available. The SLA score shows whether customers are being responded to in time, the csat score rates the agent’s performance on a scale and the sentiment is also an indication of how satisfied the customer was overall. After analysing all 3 areas of the data we can conclude that the service being provided is very consistent across all centers and demographics. 

. We can see that overall across the board customers gave more negative feedback than positive and that agents were responding below SLA more frequently than they were answering above SLA. These are areas that the company needs to systematically improve on with more staff training and better management.

. Rather than improvements being made in certain demographics or at certain call centers. The company needs to improve is overall customer service in order to improve.

