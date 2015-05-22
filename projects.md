---
layout: page
title: Project Work
permalink: /projects/
---

I have worked on a number of assignments and projects throughtout my time at Columbia thus far. Some of the major ones are listed below.

##Group Project Work

###Yelp Recommendation System

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

###Music Recommendation System Using the Million Song Dataset (last.fm)

Used collaborative filtering algorithms that utilize user feedback in order to predict what songs users may like. For benchmarking the algorithms, we used a Mean Average Precision score truncated at 500 recommended songs. It was discovered that probabilistic matrix factorization with a MAP value of 0.014 did not improve results much from using a baseline of simply recommending popular songs, while artist-based popularity along with user-based and item-based collaborative filtering methods yielded much better results, with the best method giving a MAP value of 0.048.

*[Write-Up](https://cdn.rawgit.com/jmrosen155/coursework/master/Modeling%20Social%20Data/Music%20Analysis%20Project/MSDgroupwriteup.pdf)*

*[Algorithms](https://github.com/jmrosen155/coursework/tree/master/Modeling%20Social%20Data/Music%20Analysis%20Project/Algorithms)*

*[GitHub](https://github.com/jmrosen155/musicanalysis)*

##Coursework

Please also check out my GitHub coursework repo at the link below, where I upload all of the code for my coursework (e.g. algorithms, machine learning, distributed computer systems, etc).

*[GitHub](https://github.com/jmrosen155/coursework)*
