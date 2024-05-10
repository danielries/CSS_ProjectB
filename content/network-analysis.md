---
title: Network analysis
prev: data-description
next: text-analysis
---

Now with a better understanding of the data, the network can be created. The network consists of 5100 actors with a total of 23736 links that connect them. This is a lot to process and just to get a better idea of what this means, a visualization can be helpful. In the following figure of the network the actors are colored according to their country of birth. 

<img src="/images/network_plot.png">

The most important insight that can be gained from the visualization is that some clear groups are naturally made in the graph. As expected there are a lot of American actors placed in the center of the large component in the middle. But more interestingly, at the top of the figure a Japanese group of actors can be seen. Furthermore, to the left of the giant component a small Korean cluster can be seen. It makes sense that the Japanese and Korean groups are isolated from the rest of the actors, as they most likely work on movies in their respective native languages.

<u>**So who's the biggest?**</u> \
Continuing our analysis, it is interesting to look at the actors with most collaborations in the network. The actor who has collaborated with most different actors is Samuel L. Jackson, who will be one of the largest nodes in the graph. But the largest node is actually Grey Delisle, who since 2010 has collaborated 619 times with actors in this network. It is also found that Grey Delisle has worked 46 times with Frank Keller, which makes them the "best friends" in the network. Both of these actors are the voices of two important characters of Scooby Doo, which could account for the high number of collaborations. 

<u>**Does like attract like?**</u> \
Another way to analyze the network is to look into whether actors in the network tend to collaborate with actors who are similar to themselves. We found that this is actually the case for some actor characteristics, specifically birthplace, age, rating and genre. This means that the popular actors in the network are more likely to collaborate with other actors that are born in the same country, around the same age, similarly rated and working in the same genres. 

<u>**What separates the wheat from the chaff?**</u> \
By dividing the network into optimal communities based on a more complicated algorithm, it is possible to identify the most and least successful communities. The differences between these communities can shed light on what a young actor should do to increase the odds of making it as an actor. We found that it is easier to break down succes into popularity and rating. If your goal is to become a popular actor, your best bet is to surround yourself with english-speaking actors, particularly in the US or UK. Furthermore, to maximize popularity, avoid working in TV or animated movies. On the other hand, if you aim to be a highly rated actor, collaborate with Japanese or Korean actors and focus on animation. 





