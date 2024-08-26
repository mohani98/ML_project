## ML_Project

With more than 83 million subscribers and presence in more than 190 countries, Netflix is the most popular Internet television network in the world. Its users watch more than 125 million hours of TV and movie content daily, including original series, documentaries, and feature films. On almost any screen that is linked to the Internet, members can watch as much as they want, whenever and wherever. Without interruptions or obligations, members can play, pause, and resume watching at any time. This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

## Problem Statement
The problem statement revolves around improving the Netflix experience for users by understanding their preferences and viewing habits. By analyzing data on what users watch and how they interact with the platform, the goal is to enhance Netflix's recommendation algorithms. This can lead to better personalized recommendations, ultimately increasing user satisfaction and engagement with the platform.

## Business Objective : Netflix's business objectives for clustering movies and TV shows are closely aligned with enhancing the user experience, optimizing content selection and promotion, and ultimately retaining subscribers in a competitive streaming landscape. Clustering serves as a powerful tool in achieving these objectives and maintaining Netflix's position as a leader in the streaming industry than other to make more profit .

## Attribute Information
show_id : Unique ID for every Movie / Tv Show

type : Identifier - A Movie or TV Show

title : Title of the Movie / Tv Show

director : Director of the Movie

cast : Actors involved in the movie / show

country : Country where the movie / show was produced

date_added : Date it was added on Netflix

release_year : Actual Releaseyear of the movie / show

rating : TV Rating of the movie / show

duration : Total Duration - in minutes or number of seasons

listed_in : Genere

description: The Summary description
# Steps

Importing Libraries
Import Data
Data Summary
Data Visualization
Data Cleaning ( EDA )
Feature Selection
Model Selection
Hyperparameter Tuning
Conclusion

# Conclusion
Director and cast contains a large number of null values so we will drop these 2 columns .

In this dataset there are two types of contents where 30.86% includes TV shows and the remaining 69.14% carries Movies.

We have reached a conclusion from our analysis from the content added over years that Netflix is focusing movies and TV shows (Fom 2016 data we get to know that Movies is increased by 80% and TV shows is increased by 73% compare)

From the dataset insights we can conclude that the most number of TV Shows released in 2017 and for Movies it is 2020

On Netflix USA has the largest number of contents. And most of the countries preferred to produce movies more than TV shows.

Most of the movies are belonging to 3 categories

TOP 3 content categories are International movies , dramas , comedies.

In text analysis (NLP) I used stop words, removed punctuations , stemming & TF-IDF vectorizer and other functions of NLP.

Applied different clustering models like Kmeans, hierarchical, Agglomerative clustering, DBSCAN on data we got the best cluster arrangements.

By applying different clustering algorithms to our dataset.we get the optimal number of cluster is equal to 3

