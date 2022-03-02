# Project of Managing Data Course
Movie Search &amp; Recommendation

**1. Background + problem**
Although more people started watching movies at home after the Covid-19 started, there were not many platforms that provide comprehensive reviews of a movie and information of other recommended movies based on what you searched or watched.
From multiple data sources, we have obtained all the scattered reviews, conducted sentiment analysis and created a single platform that houses reviews, sentiment ratings, recommendation lists.

 **2. Data Source specification & procurement**
⊹ Our data warehouse stores movie reviews from IMDb and New York Times.
⊹ Main attributes that have been populated are:
× Movie Title
× Review Comment
× Data Source
× Sentiment Categories
× Sentiment Scores
× A list of recommended movies
⊹ From two different data sources, we compiled and created a data warehouse in order to run a Sentiment Analysis and get sentiment scores & similarity matrix for Movie Recommendation.
⊹ We firstly scraped movie titles and reviews from IMDB and then retrieve reviews for the same movie titles from NY Times via API.
