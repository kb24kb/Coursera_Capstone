# **Restaurants in Mumbai**
## Introduction/Business Problem  
According to the website https://worldpopulationreview.com/world-cities/mumbai-population/, Mumbai has a population of about 22 million people which creates a high demand for places like restaurants and cafes where people can enjoy food with family or friends.

As stated by a blog on www.torqus.com, Mumbai is known to be a melting pot of all regional tastes of India. It is not a surprise that a city like Mumbai that offers impeccable and varied flavors for all palates and all pocket sizes stands for a unique gastronomical experience. From roadside food stalls to hoity-toity restaurants, Mumbai serves it all.

The overall Indian foodservice industry is estimated to be Rs 5.99 trillion by 2022-23, growing at a compounded annual growth rate of 9 percent, a National Restaurant Association of India (NRAI) report said.

Pegging Mumbai's organized foodservice market at Rs 40,480 crore, the report noted it was the highest amongst metros in the country.

The average spend per month per household on eating out in the city is Rs 2,890, higher than the national average of Rs 2,500, it said while adding that the average frequency of consuming non-home cooked food in Mumbai is 4.2 times per month including dine-out, delivery, and takeaways.

### Traget Audience
Entrepreneurs interested in the opening restaurant in Mumbai, who may require external advice concerning what type of restaurants are in trend and where exactly it should be inaugurated which could create a high chance of being successful  

## Data Description
I used the following data to analyze the city of Mumbai

### Neighborhood Data
Using pandas converted the table on https://www.mapsofindia.com/pincode/india/maharashtra/mumbai/ website consisting the name of the neighborhood with respect to its Pincode
     
### Geopy.geocoders
Using geopy.geocoders library to get the latitude and longitude of each neighborhood in Mumbai

### Foursquare API
Using Foursquare API to explore venue information for each neighborhood in the Mumbai city. Some features extracted include ‘Venue’, ‘Venue Category’, ‘Venue Latitude’, ‘Venue Longitude’, etc.
