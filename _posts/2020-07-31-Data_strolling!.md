# Data Strolling 

I am not sure what this is at the bottom.  Even though I use .head I still do not understand why there is not a value in there.  I will do more exploring tomorrow with this. 

![Exploring the NSFG data](https://github.com/rashadwest/rashadwest.github.io/blob/master/_posts/Screen%20Shot%202020-08-01%20at%2012.52.13%20AM.png)

I am starting to learn more here about how to explore data.  I am having trouble on getting the solution to submit as correct even though when I run the code it seems that I executed the assignment.

![Clean a variable](https://github.com/rashadwest/rashadwest.github.io/blob/master/_posts/Screen%20Shot%202020-08-01%20at%201.05.16%20PM.png)

The solution is below.  It turns out I was missing a set of parathesis. 
```
# Replace the value 8 with NaN
nsfg['nbrnaliv'].replace([8], np.nan, inplace=True)

# Print the values and their frequencies
print(nsfg['nbrnaliv'].value_counts())
```
