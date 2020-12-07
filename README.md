# Coursera_Capstone

## Applied Data Science Capstone Project - The Battle of Neighborhoods
Houston vs Dallas
## Introduction
When making plans to travel or move; our bestfriend is usually Google. We type the intended destination into our search bar and might even add top 10 for good measure. The info given to us is not necessarily useful at first glance. Especially if you intend on traveling to Texas. Texas is home to some of the biggest cities in America and it can be daunting on which city to choose, if you were to only go to one. A city in Texas is just a city in Texas, right? The objective of this study is to do a city-city comparison and find similar neighborhoods between the two biggest cities in Texas, Houston and Dallas, based on venue data collected from Foursquare.
## Description of the Problem and a Discussion of the Background
I plan to compare the major neighborhoods in both Houston and Dallas. If I can (if reliable data exist) refine the comparison to the inner-city neighborhoods I will. If not, I plan on scraping the neighborhood data from Wikipedia or some other website that fulfils the appropriate data. We will be able to assess the city a bit more granular than just an overall top 10 "city name" Google Search and instead begin to understand how citizens experience the city and what to expect from certain neighborhoods. Practical questions can start to be asked and answered with a simple comparison. For example, a potential tourist can really begin to explore the city without even putting their feet on the ground and without spending a dime to travel. Or a potential new resident can find out where they would like to move to. Does the neighborhood have all the right amenities they are looking for or too much of one amenity such as 'bars'. Similarly, a potential new business owner or venture capitalist is looking for the right neighborhood to put their new franchise. Will the new business be drowned out by all the others or will it fit right in? Doing a city to city comparison allows for any interested parties to muddle over not only what city but also what neighborhood to open their wallet and time to.

## Description of Data

To begin our comparison we will extract information from data online. The data needed will be Neighborhood, Latitude, Longitude.
This information and their corresponding coordinates for both the cities will be extracted from their respective Wikipedia pages. If there is no coordinates (as some wiki list do not), I will create a CSV file from the list obtained and use a Geocode program to extrapolate the coordinates. This will go into the CSV file and uploaded to both Kaggle and GitHub. This will be done in order to save on coding real estate and and the amount of request needed just to get coordinates. It will also make replication of the information easier and allows for others to use the information for their own projects in the future.

[Houston Wiki](https://en.wikipedia.org/wiki/List_of_Houston_neighborhoods)

[Dallas Wiki](https://en.wikipedia.org/wiki/List_of_neighborhoods_in_Dallas)

Also, I will take advantage of using Foursquare' free location API and obtain the venue list for the respective cities. The neighborhoods will be categorized by top 10 venues and then a k-means clustering algorithm will be done in order to start visualizing the data collected. 

Further updates will be done on the wiki of this repository.
