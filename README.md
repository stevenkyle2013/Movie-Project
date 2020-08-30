# General Insights in the Movie Industry
Project Members: Steven Kyle

## Projects Purpose
The purpose of this project is to conduct general exploratory data analysis in the movie industry to try and find insights that will help guide the company in making a successful production studio.

## Resources that were used

Data sets used from
+ TheMovieDB.org
+ Box Office Mojo
+ the-numbers.com


Python tools
+ seaborn
+ pandasql
+ numpy
+ panda
+ matplotlib
+ Jupyter Notebook



## Topics that are covered
1. The Market - Has the movie industry been growing or declining?
2. Content - What genres have been the most well received by audience?
3. Production Costs and Profit - Is there a correlation between production costs and profit?
4. Release Dates - Is there a certain time of year movies should be released for maximum profit?

## Findings

### The Market - Has the movie industry been growing or declining?
Data from Box Office Mojo was used to look at the state of the market. The data was grouped by year and the total domestic and foreign gross of all movies in that year were calculated. According to Box Office Mojo there has been a slight increase of Total Domestic Gross from 10 billion dollars in 2010 to 11 billion dollars in 2018. And a great increase in Foreign Domestic Gross from 14 billion dollars in 2010 to 17 billion dollars in 2018. Based off of this data it looks like that the movie industry is steady and on the rise.

##### INSERT FIRST GRAPH HERE

#### Take Away
The total gross of movies has been steady and on the rise indicating that this is a profitable endeavor for the company.

### Content - What genres have been the most well received by audience?
Data from TheMovieDB.org was used to look at genre popularity and ratings. The average popularity of genres did not vary too greatly. However, the genres that became greatly popular did. By comparing "Maximum" of the box plots the potential of a genre to become very popular can be determined. The Genres that had the greatest "Maximum" were Action, Adventure, and Fantasy. Next the average rating for genres were looked at. When looking at the average rating for genre it's seen that some of the least popular genres actually have the highest average ratings (Documentary and Music).

##### INSERT SECOND GRAPH HERE

#### Take Away
Because the most popular genres aren't necessarily the most highly rated genres the recommendation is to prioritize 5 genres:
+ Action, Adventure, and Fantasy to maximize the potential of having very popular movies
+ Documentaries and Music to maximize the potential of having highly rated movies

### Budget - Is there a correlation between production budget and profit?
Data from the-numbers.com were used for comparing the relationship between revenue and production budget. 5,415 movies were used in this dataset. The plot shows that as production budget increases so does the profit. A regression line shows the possible linear relationship but the r value is only 0.61, indicating that there is a moderate positive relationship.

##### INSERT THIRD GRAPH HERE

#### Take Away
There is a moderate positive correlation between production budget and profit, r=0.61.

### Release Dates - Is there a certain time of year movies should be released for maximum profit?
Data from the-numbers.com were used for comparing the relationship between release dates and profit. The first graph looks at the average profit of a movie by release month. This graph shows that movies released during the summer (May-Jul) and winter (Nov-Dec) have the highest average profit. However this might be due to bigger productions coming out during those times. The second graph takes that into account and looks at the average percent ROI (Return on Investment) by release month. The second graph shows that Jun has the highest average percent ROI.

##### INSERT FOURTH GRAPH HERE

#### Take Away
It is best to release movies in June to get the best possible ROI.

## Conclusion
These are the recommendations we suggest based on the trends that were discovered through exploratory data analysis. The movie industry has been on the rise so it is profitable endeavor for the company to produce a studio. The 5 main genres the studio should focus on are the most popular genres (Action, Adventure, and Fantasy) and the most highly rated genres (Documentaries and Music). Larger production costs does not necessarily mean a Larger profit. There are many factors that make a movie successful and there is only a moderate positive correlation between profit and production costs. Lastly, the recommended time of the year to release a new movie is June. That is when the average ROI is highest.
