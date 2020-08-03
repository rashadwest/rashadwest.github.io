# Histograph flow

I learned about histographs this weekend.  I was familiar with them before but never identified it as a histograph.  They are really cool for data science.  It reminds 
me of when you are in school.  Some of my favorite classes included research where you use graphs.  It made sense to me.  

It would be great to create a histograph of player data.  It could include many different things.  For this project I will focus on shooting performance.  It will be interesting 
to see who does better in the playoffs.  I amy focus on critical time periods of the game at some point as well.  Like who does best under pressure.  

Now that I understand computer vision I am thinking about ways this can be incorporated as well. 

This is an assignment where I messed up on the code in the second line.  I was not sure how to make it happen.  You can see the error below.  As you can see my solution 
intitally I just have birth_weight and full_term out of order.  
![Infant baby weight assignment](https://github.com/rashadwest/rashadwest.github.io/blob/master/_posts/Screen%20Shot%202020-08-02%20at%208.57.35%20PM.png)

```
# Create a Boolean Series for full-term babies
full_term = nsfg['prglngth'] >= 37

# Select the weights of full-term babies
full_term_weight = full_term[birth_weight]

# Compute the mean weight of full-term babies
print(full_term_weight.mean())
```
