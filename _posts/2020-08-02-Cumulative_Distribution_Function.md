# CDF

The cumulative distribution function gives you the cumulative probability associated with a function. It is a similar concept to a cumulative frequency table. With a table, the frequency is the amount of times a particular number or item happens. The cumulative frequency is the total counts up to a certain number:

Histograms, PMF, and CDF are all graphs that help in data science.

![Learning CDF's](https://github.com/rashadwest/rashadwest.github.io/blob/master/_posts/Screen%20Shot%202020-08-04%20at%2012.30.03%20PM.png?raw=true)

I am so mad at myself this morning.  I did messed up on one part and was frustrated instead of just taking my time and figuring it out.  Here is the solution that was found in the screenshot and my code below that. I missed puting income into the Cdf.

![Ploting CDF's](https://github.com/rashadwest/rashadwest.github.io/blob/master/_posts/Screen%20Shot%202020-08-05%20at%205.41.59%20AM.png?raw=true)

```
# Select realinc
income = gss['realinc']

# Make the CDF
cdf_income = Cdf()

# Plot it
cdf_income.plot()

# Label the axes
plt.xlabel('Income (1986 USD)')
plt.ylabel('CDF')
plt.show()
```
