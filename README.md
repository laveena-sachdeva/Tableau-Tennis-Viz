# Tableau-Tennis-Viz
Analyzing and Visualizing Australian Open Tennis Dataset, 2009-2014 

# DATA ANALYSIS
While exploring the data, I tried focusing on finding the trends in data by comparing matches with each other and players with each other.  Since we were given attributes like Number of Aces and Fast Serve Speed, I narrowed down the analysis to aggressive and defensive play.    
  
Just comparing the performance of the final’s match would not have given a wholistic picture of the player’s playing strategies, hence I decided to include more evidences in favor of the trends that I saw. I exported an additional dataset for the years 2009-2014, which had the data of other games of the match, in addition to the finals’ data, including 2 attributes – the Number of Aces hit, and the First Serve Speed of the player.  Going by the trend that I saw while comparing Roger Federer and Rafael Nadal, I saw that Roger Federer had consistently hit high number of Aces as compared to Rafael Nadal, and always had a higher first serve speed, again indicating his aggressive serves to hit an ace.  So, I finally decided to go ahead with a visualization comparing this defensive (Rafael Nadal) and aggressive (Roger Federer) behavior.   
 

# VISUALIZATION’S DESIGN:
I wanted to include several factors in a simple visualization, while also ensuring that there is no information overload for the reader, and things are easy to understand without going in depth and can be understood by skimming through it.   

### Why Bar Chart? 
I went ahead with a bar chart, which I think is a simple yet effective medium of representing numbers.  Also, size of two bars are easily comparable and therefore is a good representation in this scenario where I am comparing two players’ data.    

# Details of Visualization:
•	Since I had more than one game for each year, the total number of Aces hit during that year could be further represented as the sum of number of Aces in individual games. The bar indicating the total number of Aces is a stacked bar with each stack representing the Aces hit during each game of the match, where the size of the bar indicates the number of Aces.   
•	I also wanted to visualize the matches played by each player to indicate how far they reached in the game – Round of 128, 64, 32, 16, Quarter-Final, Semi-Final or Final.  Hence, I color coded the stacked bar, where each stack is colored based on the game it indicates.  
•	Comparing two players’ average performance per match accurately, apart from their year-round performance, requires the numbers to be on the same scale.  Since both players may have played different number of games in each year’s tournament, I included another attribute – average number of Aces hit per game.   Each bar with total number of Aces also has a marker indicating average number of Aces for each player.   
•	There were some lose ends in the data which could confuse the reader – Roger Federer got a walk over in his match with Andreas Beck during AUS open 2012, hence his corresponding bar graph does not indicate his Second Round’s points. The reason has been given in the footnotes. Similarly, Rafael Nadal’s Ace score is ‘0’ in 2013 tournament.  Since 0 could indicate anything for a reader who does not know the data already, the reason for the missing data (Rafael did not compete in 2013 AUS Open) has been provided in the footnotes.   
 
# Design Decisions:
•	As stated above, I chose to use a bar graph because it is a simple yet effective tool while comparing stats of two entities.  
•	The title of the chart ‘WHO “ACED” THE MATCH?” gives a good entry point to the visualization to let the reader know that the chart goes on to compare the Aces between Rafael Nadal and Roger Federer without even reading the detailed title.  
•	Since I am depicting ‘Defensive’ v/s ‘Attacking’ behavior, I chose to use cold and warm colors respectively to bring out that contrast. Also, since games in the match (represented by stacks of the bar) are sequential (though they can be categorized as distinct games, but they will always occur in a particular sequence), I have used a sequence of cold shades for the defensive player (Rafael Nadal) and sequence of warm shades for the attacking player (Roger Federer).  
•	Since it is easy to compare size of two elements to have an approximate comparison, I have scaled the size of each stack of the bar by the number of Aces hit by the player in that particular game.  
•	For the legend, since there are 14 distinct variables to be indicated, I have kept the colors representing the same attributes together so that it is easier to compare the corresponding game of each player and also the visualization/legend looks simpler and less cluttered.    
•	The footnotes explain each axes of the chart, along with giving clarifications about the data points (as explained above) which may otherwise seem ambiguous.   

# What all do these graphics convey?
•	The comparison in the number of Aces hit by Rafael and Roger during each tournament, showing a trend.  
•	The average number of Aces hit per game, hence depicting the trend that Roger plays more aggressively when it comes to Aces than Rafael – which is consistently indicated by the chart.  
•	The performance of each player in the tournament based on the color of the stack of bar graph – how far did they reach in the tournament.  
  
