# Investigating_Fandango_Movie_Ratings

In October 2015, a data journalist named Walt Hickey analyzed movie ratings and found strong evidence to suggest that Fandango's rating system was biased and dishonest. His analysis was published in an article on Fivethirtyeight. Post this article, Fandango's officials promised to fix the bug as soon as possible.

In this project, we will perform data analysis on more recent movie ratings to determine whether there has been any change in Fandango's rating system after Hickey's analysis

To do this analysis, the population of interest is all the movie ratings on Fandango's website, regardless of the releasing year.

- The sampling conditions for the first sample, the data collected before Hickey's Analysis as mentioned in the [readme](https://github.com/fivethirtyeight/data/blob/master/fandango/README.md) file.

- The sampling conditions for our other sample are mentioned in the [readme](https://github.com/mircealex/Movie_ratings_2016_17/blob/master/README.md) file.

Having a preliminary look at the data we see that sampling is not random and not quiet respresntative of the population we want to study.The sample is subject to temporal trends as movies in 2015 might be significantly good or bad compared to other years.

As we now know, the samples are unreprentative of the population we want to study,we change the goal of our analysis by placing some limitations on it as that is the much faster choice compared to collecting new data. 
Our ** new goal ** now would be "whether there has been a change in Fandango's movie ratings of popular movies in 2016 compared to Fandango's movie ratings of popular movies in 2015"

For our purposes, we then isolated only the movies released in 2015 and 2016 to perform our analysis.

To understand whether there is a change in Fandango's movie ratings, we perform the following analysis:
- Compare the absolute and relative frequencies of both sample sets
- Examine the kde plots of both sample sets
- Compute and compare the summary statistics of both sample sets

Our Analysis concludes that there has been a change in fandango ratings after Hickey's Analysis in 2015. 

