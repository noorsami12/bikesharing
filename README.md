# NYC Citibike Data Analysis

## Overview of the Analysis
For the purpose of this analysis, I utilized Tableau Public and Pandas, Jupyter Notebook, and Python to clean up and analyze bikesharing data in New York City. First, the trip duration column was converted to a datetime using Pandas in order to allow more specific filtering of data. Then, various analyses were run through Tableau on areas such as gender, location, checkout time, and more. After creating multiple visualizations, the data was compiled into a story with captions to use in a presentation.

## Results
Visualizations were completed in the following areas: checkout times, trips by days of the week, gender, users and subscribers, and starting locations. 

[link to dashboard](https://public.tableau.com/app/profile/noor.sami/viz/NYCCitibikeAnalysis_16646491751670/NYCCitibikeDataAnalysis?publish=yes)

To begin with, we see a distinct gender breakdown of bikeshare users. The vast majority of bikeshare users are male, with a small percetage being female and a slightly larger percentage listed as unknown. Additionally, the top starting locations map shows us that most bikeshare users are centered around the same area of the city, while the outskirts have far fewer users. 

The checkout time analysis shows that the most popular amount of checkout time for a bike on average is about 5 minutes with 146,752 users. The number of users checking out bikes for times longer than 5 minutes decreases steadily to around 1,000 at an hour. When broken down by gender, the checkout time popularity remains at a peak of 5 minutes for men while women have a similar range from 6-28 minutes. 

Analyzing the number of trips based on days of the week shows the the most popular days of the week for checkout time are weekdays, specifically Monday, Tuesday, Thursday, and Friday. Most of the bike checkout on weekdays happens in the morning, from 6-9 AM, or in the afternoon, from 5-9 PM. This is most likely because bikeshare users are checking out bikes to commute to and from school or work. On the weekends, there is a steady use of bikes from 10 AM to 7 PM. Breaking down trips by weekdays further by gender shows us a similar trend for all categories, with the most obvious being for men since they have the most users. 

Finally, the breakdown of bikeshare trips by user versus subscribers is significant. Subscribers show more bike usage in all gender categories except female, where customers had more usage than subscribers. Male users were significantly more like to use bikes as subscribers than as regular customers. 

## Summary
Overall, the data shows us that there are more male bikeshare users than other genders. Weekday bike usage centers around commute times, and weekend bike usage is frequent throughout the afternoon and early evening. Generally, users checkout bikes for a short period of time, mostly under 30 minutes. 

Two additional visualizations that could provide us with further data could be a graph that shows us a gender breakdown of top starting locations so that we can see if certain areas of the city show more female users. Those areas can be targeted for extra marketing, as currently most bikeshare users are male. Another visualization could show us amount of bikeshare locations compared to the map of top starting locations. It would be helpful to see if the lower use areas are a result of less bikeshare hubs to begin with. 

