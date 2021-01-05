# Recommendation System
 Type of Recommendation Systems
 
 In this Repository, I will be working with the MovieTweetings data to apply each of the three methods of recommendations:
 ***
    1. Knowledge Based Recommendations 
    2. Collaborative Filtering Based Recommendations 
    3. Content Based Recommendations 
***


## 1. MovieTweetings data

If you would like additional information about the MovieTweetings data, you can find more information at the links provided here:

* [Getting to Know The Data](https://github.com/A2Amir/Recommendation-Systems/blob/main/1.Introduction%20to%20the%20Recommendation%20Data.ipynb)

* [The MovieTweetings white paper. ](http://crowdrec2013.noahlab.com.hk/papers/crowdrec2013_Dooms.pdf)
* [A Github account set up for MovieTweetings ](http://crowdrec2013.noahlab.com.hk/papers/crowdrec2013_Dooms.pdf)
* [A slide deck by Simon Doom about MovieTweetings. ](https://www.slideshare.net/simondooms/movie-tweetings-a-movie-rating-dataset-collected-from-twitter)


## 1. Knowledge Based Recommendations

Knowledge based recommendations frequently are implemented using filters, and are extremely common amongst luxury based goods. Filters that you might see when purchasing items like cars or homes are examples of knowledge based recommendations. In knowledge based recommendations, users provide information about the types of recommendations they would like back.

 Take a look at the filters available on Zillow in the image below. This is an example of building in a knowledge based recommendation, as users can add their own preferences to the items that are provided.


<p align="center">
<img src="./images/1.png" alt="Knowledge Based Recommendation" />
<p align="center">


Often a rank based algorithm is provided along with knowledge based recommendations to bring the most popular items in particular categories to the user's attention. In the linke below, you will get some practice implementing this type of recommendation for the MovieTweetings dataset.


* [Knowledge Based_Recommendations](https://github.com/A2Amir/Recommendation-Systems/blob/main/2.%20%20Knowledge%20Based_Recommendations.ipynb)

## 2.Collaborative filtering


Collaborative filtering is a method of making recommendations based only on the interactions between users and items.  We don't need any information about items and users (information like user like or dislike item, … will be needed)

for example We know that Rima and Amir both have similar tastes in books. If we recommend a book Rima has read to Amir, this is an example of a...collaborative filtering(see below).


<p align="center">
<img src="./images/2.png" width="500" height="400" alt="Collaborative filtering" />
<p align="center">


There are two main ways to implement collaborative filtering:

    1. Model Based Collaborative Filtering which uses machine learning techniques to make recommendation
    2. Neighborhood Based Collaborative Filtering which is used to identify items or users that are "neighbors" with one another.
    
There are a number of ways we might go about finding an individual's closest neighbors - the metrics we will take a closer look at include:

    1. Pearson's correlation coefficient 
    2. Spearman's correlation coefficient 
    3. Kendall's Tau 
    4. Euclidean Distance 
    5. Manhattan Distance 



In the linke below, you will work through a few examples to get more familiar with how each of these metrics is computed, and why you might use one over another.

* [Measuring Similarity ](https://github.com/A2Amir/Recommendation-Systems/blob/main/3.%20Measuring%20Similarity%20.ipynb)



https://github.com/sidooms/MovieTweetings
