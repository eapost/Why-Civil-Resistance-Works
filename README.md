# WhyCivilResistanceWorks

In this assignment, you will replicate some of the findings of a well-received book, Why Civil Resistance Works by Erical Chenoweth and Maria J. Stephan. The two authors examined whether nonviolent campaigns are more effective than violent campaigns. They found that yes; from a data set containing details of campaigns from 1900 onwards, they found that in general peaceful campaigns are more effective in achieving their aims than violent ones.

To answer the following questions you will use the data that the authors helpfully provide at https://www.ericachenoweth.com/wp-content/uploads/2012/01/Data-and-Replication-Files-3.zip. The data is in Stata format, which pandas can read without a problem. To understand the data, read the documentation at https://www.ericachenoweth.com/wp-content/uploads/2019/07/WCRW-Appendix.pdf (in particular, Table WA.7).

# 1. Frequency of Nonviolent and Violent Campaign End Years

Create a plot showing the frequency of nonviolent and violent campaigns; the frequency should be counted based on their end years, at decades. The violent and nonviolent campaign counts should be stacked on each other.

# 2. Number of Nonviolent Campaigns and Percentage of Success
Create a plot showing, for each decade from 1940 onwards, the number of nonviolent campaigns and the percentage of success. Your plot will have two vertical axes, one for each of the metrics.

# 3. Success Rate by Decade
Create a plot showing the success rate for violent and nonviolent campaigns by decade so that nonviolent campaigns have higher success probabilities.

# 4. Twenty-Five Largest Resistance Campaigns, 1900-2006
Create a table with the twenty-five largest resistance campaigns, for all years, based on their number of members at highest point (peak membership). The table should include the membership, the start year, the end year, the location, the target, whether it was violent or not, and whether it was successful or not. Notice if you find anything about Greece.

# 5. The Effect of Participation on the Probability of Campaign Success
Examine the effect of participation on the probability of campaign success. You should run a logistic regression for success on membership per capita, controlling for the location’s logged population the year the campaign ends. Explain your results.
Having done that, create a scatter plot showing the logged participants per capita, on the x axis, and the probability of success, on the y axis.


# 6. The Level of Participation Tipping Point
From the results you obtained in the previous question, find the percentage of the population that is the tipping point for success in a campaign.

# 7. Nonviolent Resistance, Target Regime Type, Geographical Location
Examine whether nonviolent resistance remains significant even if we control for the regime type. Run a logistic regression of success on the nonviolence indicator controlling for the POLITY IV score of campaign target (tpolity), the log of peakmembership, and the location’s logged population the year the campaign ends. Examine whether nonviolent resistance remains significant even if we control for geographical location of the compaign.
