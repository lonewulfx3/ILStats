# Invadedlands forum statistics
Have you ever wondered who got likes from who. Worry not Lone has done it. I made a scraper that collected most of the important people's likes. 
With the data I collected I did 3 things per user. I made a pie chart that shows the distribution of all likes (no labels, too many people). A bar chart that shows the top 30 people that liked you (ranked by how much likes they've given you). I also did one thing. I calculated if someone was like boosted or not. This calculation is very simple. I only checked people with more than 100 likes (active +). From those people if the number 1 person that liked them was 25% of the likes, I count that as a like boost. If the 2 top people make up 40% of the total likes, that's a like boost. IF the 3 top people are 50% of the total likes... If the top 4 people are the top 60% likes... After that you're fine. Keep in mind that this is *probably* like boosted. Sometimes people are just friends ya know ¯\\\_(ツ)_/¯. Also like boosted people in the beginning of the forums can be hidden by the likes they collected after the like boost happened. To be honest at that point what does it even matter.

## HOW TO INTERPRET THE PIE CHART
Sometimes you look at a pie chart and are amazed by the distribution. I urge you to keep in mind that people may have very few likes and because of that the pie chart may show some huge slices. Don't go spouting toxicity at these forum users because you interpreted the pie chart wrong.


## WHO WAS SCRAPED
Atm I only scraped 1500 people. The program takes time to run as I didn't want to burden the invadedlands forums host too much. I have like a 2 second average for requests. I made my program run for 3 days.
The likes from people 0-147 aren't complete because I made an error. ¯\\\_(ツ)_/¯ sorry.


## SPECIAL MENTIONS

My code isn't perfect. It works on exception handling, meaning that if a certain posts doesn't have any likes it waits for an exception to be thrown (which takes more time). So when people have many posts that are liked in a row (happens when people are popular or like boosted) my program works in overtime. This causes the program to run out of memory (it needs to time to release memory). It releases memory when it's waiting for the exception to happen.

### ASH

First person that was like boosted so much that I had to refactor my code. Kinda sus that it was ashley and happened right when staff season was announced but what do I know.

### SPYCY

LIKE BOOSTED SOOOOO much that my pc couldn't keep up even with refactoring. I didn't feel like changing the code anymore so I had to manually freeze the program when scraping him.

### Emboxity

He was the only one to have something weird happen during execution and had to add another catch for an exception, love ya buddy.

### JoeMS
It was when I was scraping you that I realised I made a small error in the program causing likes from straight profile posts to not be gathered. 

### The tons and tons of people with no likes

Had to check if people had no likes just to make scraping faster. There are so many of you :(
