# Coursera-IBM-Certification
Coursera Certification

# Capstone Final Project

# Business Problem:
Me and my friends are planning for an adventurous trip from Mumbai India. We have noted down 11 cities across World out of which we would like to choose one City as our final destination. Our plan was to get to that city which has DIFFERENT LIFE STYLE compared to Mumbai India. The Cities chosen by me are Colombo(Srilanka),Cape Town(SouthAfrica), Roma(Italy), Canberra(Australia), Santiago(Chile),Copenhagen(Denmark),Paris(France),Stockholm(Sweden),Mumbai(India),Moscow(Russia),Kuala-lumpur(Malaysia) and Male(Maldives).To accomplish this task we will be leveraging Foursquare location data of mentioned cities.


# Data: 
For this business requirement we will be leveraging Foursquare location data of mentioned cities. First we will get the latitude and longitude of mentioned Cities and once done we will use Foursquare location data to get the neighborhood details of these cities such as nearby Gardens, Restaurants and other famous places to visit in these Cities.

# Methodology:
Our base idea is to leverage machine learning and find cities which have life styles very different to that of our current city Mumbai as a part of our Adventurous trip. So to accomplish this, I have chosen KMeans clustering. The idea is to take all the mentioned 12 cities data from Foursquare location data and cluster them into 2 groups. The expectation is that all the cities which have similar life styles to that of Mumbai will be in one cluster and rest of cities with different life styles will be in other cluster. Now once done with clustering all we have to do is pick one of the cities in the cluster in which Mumbai city IS NOT PART OF and make plans for Adventurous trip to that city.

# Results:
After performing Kmeans clustering with 2 clusters, its Canberra Australia that made to one cluster and rest of 11 cities including Mumbai were part of second cluster. 

# Discussion:
So finally its Canberra Australia life style that stood out compared to all other cities including Mumbai. So for our adventurous trip we will be heading to Canberra Australia.

# Conclusion:
Our target was to plan a trip to the city which has total or atleast partially different life style compared to that of our current city Mumbai. Thanks to Machine learning and Foursquare data, we have finally got the city to which we will be planning to go very soon: Canberra Australia.
