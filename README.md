# Programming the farming Drone(Report)

# Introduction
Programming a farming drone involves blending cutting-edge technology with traditional farming practices to create a seamless, efficient system.

# Objective
Machine learning and AI Integration
Data collection and analysis

# Table of Contents
- [Code Snippets and Explanation](#code-snippets-and-explanation)
- [Challenges and Learnings](#challenges-and-learnings)
- [References](#references)

# Code-Snippets-and-Explanation
Write and explain your code along with recordings.



# Step 1
do_a_flip()
harvest()

# Explanation
Players earn gold by clicking on crops, which can be used to buy better tools and expand the farm.

# image
![img](<step 1 image.jpg>)

# Step 2
while true:
   if can_harvest():
   move(north)

# Explanation 
this code makes it harvest from south to north

# image
![img](<step 2 image.jpg>)

# Step 3
while true:
   plant(entities.bush)
   if can_harvest():
     harvest()
     move(north)
    else:
    move (north)

# Explanation
this code will harvest wood

# image
![img](<Screenshot 2024-11-04 093022.png>)


# Step 4
clear()
move (south)
while true:
   for i in range(get_world_size()):
     move(north)
   if can_harvest():
     PLant(entities.grass)
   else  num_items(item.hay)<500:
    plant(entities.bush)
else:
If num_items(Items.carrots_seed) ==0:
 trade(Items.carrots_seed)
if get_ground_type() == grounds.turfs:
   till()
plant(entities.carrots)
move(east)

# Explanation
This code will harvest bush grass and trade with carrot seed

# image
![img](<Screenshot 2024-11-04 093240.png>)


# Step 5
Clear()
move(south)
while true:
   for i in range(get_world_size()):
    move(north)
    if can_harvest()
       harvest()

# Trade water tank
if num_items(item.water_tank) < 100:
   trade(item.Empty_tank)
if num_items(item.hay)<500:
   plant(entities.grass)
elif num_items(items.wood)<100:
   plant(entities.bush)
else:
If num items(items.carrot_seed) ==0
    trade(items;carrot_seed)
if get_ground_type()==grounds.turfs:
  till()
plant(entities.carrots)
move(east)

# Explanation
This code with trade empty tank woods

# video
<video controls src="video.mp4" title="Title"></video>