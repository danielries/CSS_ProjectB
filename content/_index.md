---
title: Home Page
layout: single
next: data-description
---

This project is about networks, specifically a network made up of the most popular actors in the world. These actors have been in countless movies and collaborated with many other actors. But what happens if we create a network that only includes popular actors and connect them through their movie collaborations? Do the actors form specific groups based on factors like age, birthplace or ratings? \
By analyzing data from popular actors and their collaborations within the network, our main objective is to identify key insights that reveal what drives the success in the film industry from the actor's perspective. We seek to answer the following question:

> Based on recent collaborations among the most popular actors, do distinct communities form, and if so, what characterizes the most successful communities?

<div style="display: flex;">
    <img src="/images/marvel.png" width="200" height="200">
    <img src="/images/anime_dj.png" width="200" height="200">
    <img src="/images/harry_potter.png" width="200" height="200">
</div>

To find the answer to our question, we need data. The data source for this project is The Movie Database (TMDB), from where all desired information about the most popular actors can be found. On top of that, TMDB also provides information about all the movies that these actors have been in. With the data in place, we can create the actual network.

And it's a big one! The top 5000 actors in the world are put in the network and connections between them are drawn through movie collaborations. Now having this large network, it is possible to look into whether the actors group up according to personal attributes. 

By looking into these characteristics, a lot of new insights can be made. One interesting finding is that the birthplace and rating of the actors seem to play a role when looking at the communities in the network. This suggests that popular actors born in the country tend to collaborate more than with other countries and that actors are more likely to work with other similarly rated actors.

After diving into the network, another part of this project involves text analysis. Given the context of movies, analyzing movie abstracts felt like a natural next step. By grouping the popular actors into distinct communities and collecting the abstracts of the films they have appeared in, text analysis could be done. Looking for both the most common and central words used in these movie abstracts for the best communities, may reveal some common features for the communities. 

A major takeaway from the text analysis was that examining central words in each community made it possible to identify the types of movies they primarily worked on. AI allowed us to generate movie posters inspired by words from distinct communities like Japanese animation, Marvel Studios, and Harry Potter films. You can see them at the top of the page.

But there is still one question left to be answered for a young and aspiring actor: How do I become a succesful actor? Looking at succesful and unsuccesful communities show a specific pattern. If you want to be popular go to english-speaking countries (US or UK) and stay away from TV movies and animation films. On the other hand, if you want to be a highly rated actor move to Japan or Korea and work with animation films. 


To delve further into our findings and to get a better understanding of the project, check out the other pages on the website and for more technical details, see the [Explainer Notebook](explainer_notebook.html).
