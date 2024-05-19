I set out to determine if, in his most dominant year of 2005, world #1 Roger Federer was also the most *quick* 
to dispose of his opponents. This was measured by average minutes per 2, 3, 4, and 5 and set matches. 
The data was compared to the #2 and #3 ranked players.
*source : Jeff Sackman atp data

Steps: 
In Power Query
- sheets created for WIN and LOSS for RF (Roger Federer), RN (Rafael Nadal), AR (Andy Roddick).
-  choosing relevant columns, removing tie break score
  
In Excel:
- adding score LEN column (length). 7 = 2 sets, 11 = 3 sets, 15 = 4 sets, 19 = 5 sets to convert score to a referable number
- AVERAGEIF(score length, "=LEN", minutes) applied to each player for both wins and losses
- Chart called

Conclusion: no surprise that, given his blistering service game, Andy Roddick was actually quicker !
