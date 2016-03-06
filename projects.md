---
layout: page
title: Project Work
permalink: /projects/
---

I have worked on a number of assignments and projects throughout my time at Columbia. Some of the major ones are listed below.

# Group Project Work

### Social Network Analysis of Twitter (in partnership with Synergic Partners)

The goal of this project was to characterize and map, using network science and text mining techniques, the online Twitter conversation surrounding ‘Data Science’ and ‘Big Data.’ Specifically, we were interested in identifying Twitter influencers in a manner that would facilitate effective marketing campaigns by targeting individuals who can diffuse information in an efficient manner. To this end, the network was constructed by combining the “retweet” and “mention” layers into one projected layer that captures both information diffusion processes. Community structures were identified in the projected network using K-Clique, Modularity, Random Walk, and the Mixed Membership Stochastic Blockmodel. We subsequently identified influencers within each community by utilizing various centrality metrics and analyzed user profiles to gain further insight into the demographics of the communities. Latent Dirichlet Allocation (LDA) was explored in our analysis to incorporate textual data into characterizing the communities. While each of the community detection algorithms we explored has its merits, for our sparse network of tweets, we found that modularity and random walk produced the most coherent communities based on user demographics and influencers. Finally, the network and user demographics of each community were represented in an interactive visualization to allow for further exploration.

*[Write-Up](https://cdn.rawgit.com/jmrosen155/coursework/master/Capstone%20Project/TwitterGraph_FinalReport.pdf)*

*[Slides](https://cdn.rawgit.com/jmrosen155/coursework/master/Capstone%20Project/Twitter%20-%20Presentation%2020151214.pdf)*

### Yelp Recommendation System

Implemented new features to visualize Yelp search results around Columbia University using the 2012 Yelp academic dataset:

- Scraped relevant restaurant data from the Yelp website using Beautiful Soup in Python.
- Calculated the Jaccard index and performed matrix factorization to identify similar restaurants in order to build a similarity recommendation system in Leaflet and Shiny.
- Created a 'food vs star preference search' feature in d3 for fast restaurant search.
- Designed a food recommendation engine in JavaScript and d3 that displays the most mentioned food items in a square tree map, with the size of each square image corresponding to the number of mentions in a review.

*[Yelp Similarity Recommendation System](http://jmrosen155.shinyapps.io/YelpRecommendationSystemFinal)*

*[Yelp User Preference Search](http://run.plnkr.co/plunks/jRIGKXMZLDn5xrMJgqTl/)*

*[Food Map](http://www.samgshare.com/edav/FoodMap/foodMap.html)*

*[Write-Up](https://cdn.rawgit.com/CUDSY/Yelp/master/Write-Up/EDAV:%20Exploring%20the%20Yelp%20Dataset.html)*

*[GitHub](https://github.com/CUDSY/Yelp)*

### Music Recommendation System Using the Million Song Dataset (last.fm)

Used collaborative filtering algorithms that utilize user feedback in order to predict what songs users may like. For benchmarking the algorithms, we used a Mean Average Precision score truncated at 500 recommended songs. It was discovered that probabilistic matrix factorization with a MAP value of 0.014 did not improve results much from using a baseline of simply recommending popular songs, while artist-based popularity along with user-based and item-based collaborative filtering methods yielded much better results, with the best method giving a MAP value of 0.048.

*[Write-Up](https://cdn.rawgit.com/jmrosen155/coursework/master/Modeling%20Social%20Data/Music%20Analysis%20Project/MSDgroupwriteup.pdf)*

*[Algorithms](https://github.com/jmrosen155/coursework/tree/master/Modeling%20Social%20Data/Music%20Analysis%20Project/Algorithms)*

*[GitHub](https://github.com/jmrosen155/musicanalysis)*

## Coursework

Please also check out my GitHub coursework repo at the link below, where I have uploaded much of the code for my coursework (e.g. algorithms, machine learning, distributed computer systems, visualization, etc).

*[GitHub](https://github.com/jmrosen155/coursework)*
