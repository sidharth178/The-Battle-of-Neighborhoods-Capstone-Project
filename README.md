# THE-BATTLE-OF-THE-NEIGHBOURHOODS-PROJECT

This is the capstone project of machine learning nanodegree program of udacity.Here is the link of my blog post about this project
https://medium.com/@sidharth.ku178/the-battle-of-the-neighbourhoods-3d90f56dae69

### Library Used

  1.pandas
  
  2.matplotlib
  
  3.sklearn
  
  4.json
  
  5.folium
  

 
### Problem Statement

Hong Kong is one of the biggest international cities in the world, and one of the financial center of Asia. Opening a restaurant here is an attractive idea for any one who want to extends its business to Asia. They would be very interested in this project.I will explore the neighborhoods in Hong Kong and answer the question: "Where is the appropriate place to open a new restaurant in Hong Kong"., I will use the Foursquare location data to explore neighborhoods in Hong Kong, and to come up with a problem that I can use the Foursquare location data to solve.    

### Elements to consider:

1. Average rents by neighborhood
2. Ratio of Hotels to Restaurants
3. Proximity to ‘high rent’ neighborhoods

### Datasets and Inputs 
    	    
My main two data sources are:

1.	Wikipedia[1] provides the list of districts and neighborhoods in Hong Kong

2.	Venues data from Foursquare[2]

The coordinates data is from https://www.maps.ie/coordinates.html
Hong Kong consists of Hong Kong Island, the Kowloon Peninsula, the New Territories, Lantau Island, and over 200 other islands. This project will focus on Hong Kong Island and Kowloon.In this project, I will get data of recommended venues inside 1000 meters radius of every neighborhood, calculate the top10 most common venues by its category as features. Plus, the 11th feature is if there is a bus/metro station nearby.

For this project, k-means is an appropriate clustering algorithm. Because we have a unlabelled dataset, so this is an unsupervisied learning project. K-means clustering aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean.By clustering the neighborhoods, we can find out the pattern in them, identify the identical neighborhoods and see which is our target.One difficulty of k-means is to determine the hyperparameter k . In this project I will choose k=5 , means clustering the neighborhoods into 5 clusters. k=5 is an experience hyperparameter.

In this project, we need to use the location data from Foursquare to solve the problem "Where is the appropriate place to open a new restaurant in Hong Kong".
I collect the neighborhoods data from wikipedia page, and format it manually. Get venues data using Foursquare's API. One-hot encode the venues' categories and calculate the frequencies, then get TOP10 common venues for each neighborhood plus the bus/metro station existence as features.
