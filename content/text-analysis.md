---
title: Text analysis
prev: network-analysis
---

Now that the actor collaboration network have been explored (Check the Network page), it is time to delve deeper and finally put light on the forming of actor communities inside our network. As it can be seen on the Network page, the actors are forming some kinda of groupings among each other, where certain types of actors seems to be co-acting more than with others. We will here call these actor groupings of the network for "communities". With Machine Learning techniques (See explainer notebook) the actor network has been split into communities, which are investigated. But this leaves you thinking: 

<u>**How Can The Extensive Reach of Actor Communities be Differentiated?**</u> 
Text analysis is our answer. The movie abstracts are the most descriptive information in the datasets about the actor colloborations. Therefore the collection of movie abstract within each of the actor communities will be analyzed. First of all we cleaned and filtered all of the 30000 movie abstracts, to avoid meaningless undescriptive words like "and", "a", "to" etc.. By doing so, more unique and characterizing words are left back in the text data. The next step was to find the most defining words in each of the communities, in other words their importance. This was simply done by finding the most frequent words in a community but at the same time the most outstanding compared to other communities. These are exactly the words that will distinguish the abstract collections and thereby the communities. To visualize these types of words, clouds of words have been made for the top 9 communities in terms of their average rating, where the size of the word is depending on their importance as described before. To put faces on the communities, the names of the top 5 most collaborating actors in each community are printed above the associated communities. Let us dive into that.

<img src="/images/wordcloud.png">

As seen on the plot above, the resulting 9 wordcloud plots are consisting of very different words with different sizes, that are easy to distinct. It is very clear that the communties in these cases are based on types of movies. 
All the 9 communties are easily identifiable, but to highlight a few, the 3rd community in the bottom row is clearly dominated by the Lord of the Rings movies, seen by the words "dwarv" and "hobbit" and the names "bilbo", "gandalf", "smaug", "erebor", etc. The rest of the communities, starting from the top left, could be categorized as anime (japanese animation), wrestling, korean, Harry Potter, japanese, cartoon and Star Wars.

It can be seen across all these 9 communities that the 5 most collaborating actors all are very central characters in the movie domains described by their respective word-clouds, which makes sense since they work with most of the other actors and therefore are likely to star in the largest proportion of movies in the community. It can also be noted that numerous of actors from the top 5s from the same communities have different characteristics such as birthplace and age. For example, in the Marvel Superheroes community (community 8), Benedict Cumberbatch is from the UK, while the rest are from the U.S. As these are the most collaborating actors and therefore the most central in the communities, this indicates that the groupings of actor collaborations are more dependent on the movie domains rather than other actor characteristics such as birthplace or age.

<u>**A community canvas, painting actor collaborations with movie posters**</u>

To give a better picture of how a movie from such a community could look like, we have made movie posters based on the top 10 most important words within each community. This has been done on the Marvel community, the Harry Potter community and japanese anime community with their respective community numbers below. Beware, here comes the movie posters of some of the highest rated communities among the most popular actors.

<div style="display: flex;">
    <img src="/images/marvel.png" width="200" height="200">
    <img src="/images/anime_dj.png" width="200" height="200">
    <img src="/images/harry_potter.png" width="200" height="200">
</div>

The movie posters from the Marvel and Harry Potter communities are very recognisable with the Avengers like group of marvel heroes look a likes and futuristic structures screaming marvel, and the magic vibes with wizards, witches and dark themes that nearly seems like a legit Harry Potter poster. Through this text analysis with more, it has become more than evident that distinct communities among the most popular actor collaborations, do indeed form.