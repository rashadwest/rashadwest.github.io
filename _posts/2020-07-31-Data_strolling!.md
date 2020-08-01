# Data Strolling 

I am not sure what this is at the bottom.  Even though I use .head I still do not understand why there is not a value in there.  I will do more exploring tomorrow with this. 
[](https://github.com/rashadwest/rashadwest.github.io/blob/master/_posts/Screen%20Shot%202020-08-01%20at%2012.52.13%20AM.png)

# Display the number of rows and columns
nsfg.shape

# Display the names of the columns
nsfg.columns

# Select column birthwgt_oz1: ounces
ounces = nsfg['birthwgt_oz1']

# Print the first 5 elements of ounces
print(ounces.head())
