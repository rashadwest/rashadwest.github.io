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
