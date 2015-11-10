# Summary
The goal of this visualization is to show the performance of left handed and right handed baseball players in terms of their batting average and home runs average.
Conclusion, this visualization shows that left hand baseball player has the highest batting average and a better average home runs in comparison with right hand baseball player.

# Design

## Initial (index.html)
* Keeping a pie chart there is to let the user know the total handedness of baseball players selected.
* It's kind of cluttered when displaying all the players. So adding in a filter feature there should allow the user to see the top performance player.
* Having a bubble chart of Homerun versus Batting average allows the user to see each player's performance directly.

## Second (index1.html)
* In order to allow users to do comparison on the performance based on the handedness of the player. Added in handedness filtering.
* Color of the handedness is match up on all charts.
* Added in a histogram for Homeruns.
* For scatter plot tooltip, players name is placed on top of other statistics.

## Third (index2.html)
* In order to better explain the story which I am trying to convey, I decided to only include a scatter plot. Reason being, in a scatter plot I am able to show the relationship between homeruns and batting averages and using color for each dots to further differentiate the handedness. Reader can zoom into each player if they wanted more details by hovering over the dots.
* I choose to use only three colors (Blue, Orange, Red) to distinctively differentiate the handedness.
* I added in a reanimate button, if the reader missed the initial animation when the page loads.

## Forth (index3.html)
* In order to compare the Left and Right hand baseball player's distribution its best to use a multiple horizontal line chart. Batting average is placed on X-Axis as its needed to show the gradual increase of batting average from the lowest value to the highest value. Same goes with Y-Axis, it is represented by average home runs.
* In a multiple horizontal line chart, I used two different colors (red, blue) to represent the baseball player's handedess.

# Feedback

## Reviewer #1 - Laurie Reynolds
1. What do you notice in the visualization?
   Top batting average players are left handed, while the top home run hitters are right handed.

2. What questions do you have about the data?
   Why do more left handed players have the highest batting average?

3. What relationships do you notice?
   A number of the players with the top home run scores are from many years ago

4. What do you think is the main takeaway from this visualization?
   Most players are between 0.125 and 0.275 BA and less than 100 HR
   Handedness doesn't seem to be a big factor in success

5. Is there something you don’t understand in the graphic?
   No it is pretty self explanatory

### General observations

1. I am a fan of including a source for the data.  It can be either a link or text
2. It would be nice to match the colors of the pie chart in the bar chart
3. I wanted to be able to filter the players on l/r/b handedness and see where they fell on the scatter plot
4. Tooltips - It would be nice to put the name at the top.  If you have the , the years they played and the team that they played for, include that
5. When I selected one of the performance filters, the players selector reset, but when I selected a player filter, the performance filters didn't reset - should it have?
(e.g. selected more than 100 home runs and top 20 highest batting average for the players which showed me all 20 players some of which had less than 100 HR)
6. The title should reflect the story that you are trying to tell which seems to include handedness.
7. The bar chart could be thinner and then you'd have room for an average home run bar chart next to it.
8. Not sure if it is my resolution, but I had to scroll to see the full scatterplot on a desktop browser

## Reviewer #2 - Hicham Mallah
One thing I noticed, is that at each time I filter by performance, filter by top player resets, which is a bit confusing.

A nice thing that can be added is hand filtering. For example filter by left handed players, or both handed etc...

I don't follow baseball at all. So I might be out of subject :)

1. What do you notice in the visualization?
   Most players are right handed. Both handed are a rare. Both handed players have the highest batting average, then comes left-handed. Maybe baseball coaches have a preference for these people as batters. The higher the batting average, the higher the homeruns.

2. What questions do you have about the data?
   We see an increase in the homeruns with the increase of the batting average, but then after 0.3 homeruns decrease fast, why?

3. What relationships do you notice?
   The relationship between more batting and homeruns.
   The relationship with which hand is the player and his batting average.

4. What do you think is the main takeaway from this visualization?
5. Is there something you don’t understand in the graphic?
   Not really, it is not a subject that interests me, so I don't want to think a lot :)﻿

## Reviewer #3 - Christopher Kaalund
1. What do you notice in the visualization?
   I can see three charts showing batting average for left and right handed players, their proportions, and the number of home runs presented against batting average.

2. What questions do you have about the data?
   B = Both? Why is batting average a fractional number? (I don't follow baseball)

3. What relationships do you notice?
   The number of home runs increases as batting average increases. Suggest trying a log plot ;-)

4. What do you think is the main takeaway from this visualization?
   The number of home runs increases as batting average increases.

5. Is there something you don’t understand in the graphic?
   Why the need for a pie chart and bar chart to present the same information? Do the filters work in combination? Why does the number of home runs increase with batting average, and how is this related to the handedness of the players?

# Resources
1. https://github.com/PMSI-AlignAlytics/dimple/wiki
2. http://stackoverflow.com/questions/23305230/how-do-you-reduce-the-number-of-y-axis-ticks-in-dimple-js/23318244#23318244
3. http://stackoverflow.com