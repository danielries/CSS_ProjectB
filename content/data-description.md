---
title: Data description
prev: "/"
next: network-analysis
---
First of all, lets get familiar with the data used through the project. Every information we have stems from the data source, The Movie Data Base (TMDB), which covers a broad range of the film industry and it has built a reputation for being a well-known within the field. The main data of this project consists of information on the 5,000 most popular actors and information about movies from recent years (2010 and forward) they have participated, which results in around 30,000 movies in total. It should be mentioned that this popularity measure for actors is based on factors like the amount of page views, favorites, watchlists, and recent activity of the actor. To prepare for the dive into our analyses later, it is important to actually understand what each column name represents in our datasets and what the importance of it is. Here we are going to create a table that gives a nice overview of the different attributes.

It is worth noting that we here are only going to showcase the significant ones in order to understand the data of our project. For the interested readers, additional details can be found in our notebook ([Explainer Notebook](test.html)).

<div style="display: flex; justify-content: space-between;">

<div style="width: 45%;">

## Actor Information

| Column Name      | Description           |
| ---------------- | --------------------- |
| Actor Name       | Name of the actor     |
| Gender           | Gender of the actor   |
| Birthplace       | Birthplace of the actor |
| Age              | Age of the actor      |
| Actor Popularity | Popularity of the actor |
| Movies Acted In  | Movies the actor has acted in |
| Genres Acted In  | Genres the actor has acted in |

</div>

<div style="width: 45%;">

## Movie Information

| Column Name      | Description           |
| ---------------- | --------------------- |
| Movie Name       | Name of the movie     |
| Rating           | Rating of the movie   |
| Movie Popularity | Popularity of the movie |
| Genres           | Genres of the movie   |
| Release Date     | Release date of the movie |
| Abstract         | Abstract of the movie |

</div>

</div>

With this collection of data, this project will explore and illuminate the nature of collaborations among the most popular actors, to reveal the secret behind the success of popular actors. This is done by, among other things, using this data to create an actor collaboration network to be investigated. To continue the story with this actor network go to the Network page at the top right corner.
