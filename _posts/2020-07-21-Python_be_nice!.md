# Python be Nice!

The moment I think I am getting somewhere I then get humbled.  I was learning how to slice and dice my list and then I have some issues on how to do it after running 
my code.  Here is what I put and the output I recieved.  I did it without errors but it not giving me the correct answer when I run it.  It is asking it I ran 
downstairs without errors and I did. 

This is the most frustrating part about coding.  Where is the AI that tells you what you did wrong?


Here is the problem set that they had and it was my job to print out the first 6 items out of the list for downstairs and then the last for of the list for upstairs
and that is what I thought I did.  Here is the input:
```
# Create the areas list
areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]

# Use slicing to create downstairs
downstairs_list = areas[0:6]
downstairs_list

# Use slicing to create upstairs
upstairs_list = areas[6:11]   
upstairs_list

# Print out downstairs and upstairs
print(upstairs_list)
```

Here is the Output:
```
In [12]: # Create the areas list
         areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]
         
         # Use slicing to create downstairs
         downstairs_list = areas[0:6]
         downstairs_list
         
         # Use slicing to create upstairs
         upstairs_list = areas[6:11]   
         upstairs_list
         
         # Print out downstairs and upstairs
         print(upstairs_list)
         print(downstairs_list)
['bedroom', 10.75, 'bathroom', 9.5]
['hallway', 11.25, 'kitchen', 18.0, 'living room', 20.0]
```

It turns out I just printed the upstairs and downstairs out of order.  Attention to detail ladies and gentlemen!

```
# Create the areas list
areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]

# Alternative slicing to create downstairs
downstairs = areas[:6]

# Alternative slicing to create upstairs
upstairs = areas[6:]
```

Another example I did this right but I did not think to put downstairs = areas[:6].  Instead I put downstairs[:6] like the example but it was not reading the area.  I want to try to retain this stuff as much as possible. 

Below was an euphoric moment for me.  I figured out how to think about this problem.  At first I did not know what they were talking about. Then I ran some of the code and then looked back at what values were printed for floats in the previous excercise.  I wonder if this is the only way to go about this.  I will ask Alivia tomorrow. 

![List Lesson](https://github.com/rashadwest/rashadwest.github.io/blob/master/_posts/Screen%20Shot%202020-07-24%20at%202.26.15%20AM.png)

On this one I do not understand what I did wrong.  I cannot wait to see the results.  They are starting to make it fun as I feel like I am invloved in building a house.

```
# Create the areas list and make some changes
areas = ["hallway", 11.25, "kitchen", 18.0, "chill zone", 20.0,
         "bedroom", 10.75, "bathroom", 10.50]

# Add poolhouse data to areas, new list is areas_1
areas_1 = areas + ["poolhouse", float(24.5)]

# Add garage data to areas_1, new list is areas_2
areas_2 = areas + ["garage", float(15.45)]
```

The solution was the number without the float().  I am confused on when to use this and when not too.  It worked so I am thinking I could use it.  This is another quesiton I have.  


Examples of Data Types
- Integer = 26
- String = '26'
- variable = twenty_six 
- float = 26.01
- Bool = True 
