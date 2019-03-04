Bikes
Scott Smith


This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. 

There were 519,700 records, but a lot of NAN's, so I cleaned up the file and now there are 453,159. There are 15 different characteristics about the ride and the riders.

1. The duration of the ride (how long are the customers using the bikes?)
2. Which gender rides more often? What age group rides most often?
3. Are they regular riders (subscriber) or just occasional (customer).

The main characteristics I will be investigating are - member gender, member birth year, user type and duration.

## Summary of Findings
Duration has a long-tailed distribution, with a few rides of a very long duration. Plotted with a log scale, it shows to be unimodel and peaking between 500 to 900 seconds (roughly 10 minute rides, about a 1/4 of the rides)

The Univariate graphs shows an overwhelming number of Subscribers as compared to the random Customer, as well as male riders to female or other riders. They also show that the majority of the birth years were early to mid 1980's, with early 1990's as the next level.

In the Bivariate section, the boxplot shows that despite the fact that there were considerably more males than females or others, the mean of the age range for females was slightly younger than the other 2 groups, which were about the same. The clustered bar chart varifies that the porportion of subscribers to customers is the same through all groups. The scatterplot reveals the majority of rides were less than 20000 secs, while the longer rides fell within the mid 1980's age group.

In the Multivariate section, the plots show that the mean age of the subscribers for both male and females is older than the mean for the regular customers, while in the other group they are the same age. The overall age of the females is younger than both of the other groups. The scatterplot reinforces the majority of rides fall into the 20000 or less sec.

While there are considerably more male riders to female, the longer duration rides show a fairly even amount of males and females taking the longer rides.

## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.