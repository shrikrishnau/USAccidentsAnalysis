
# US Accidents Analysis (2016-2021)


## Problem statement
The accident data of United States of America has to be sourced from web, cleaned and analysed using Python. Produce your insights from the data after analysis like top cities with most accidents, correlation with population.


## About the data set
* The dataset was sourced from Kaggle.
* This dataset contains data from 49 states excluding Alaska(AK).


## Overall Analysis View
The aim of this project is to find the major reasons for accidents and come up with meaningful suggestions to avoid them.

## Libraries Used
* Pandas
* Seaborn
* Matplotlib
* Folium

### Top Cities in the US based on number of accidents:
<p align="center">
 <img src='https://github.com/shrikrishnau/US_Accidents_Analysis/blob/main/US%20Accidents/TopCitiesByAccident.JPG?raw=true' width="600">

</p>

### Heatmap depicting the places where most accidents occur:

<p align="center">
<img src='https://github.com/shrikrishnau/US_Accidents_Analysis/blob/main/US%20Accidents/accidents%20heatmap.JPG?raw=true' width="600">

</p>


## Things learnt from this Project 
* Learnt to build different types of plot with data.
* Got introduced to Folium for making a heatmap.

## Some Important insights from the Analysis

* No Data for Alaska.
* Number of accidents per city decreases exponentially.
* Less that 5% of Cities reported the total number of accidents greater than 1000.
* About 1110 cities have reported only 1 case of an accident.
* The higher number of accidents occur during the winter months which not necessarily mean that more accidents occur during cold weather, but the fact that more people are out on the streets as December is Christmas month and people go shopping a lot.
* Top 5 cities in terms of number of accidents 
   * Miami 106966 
   * Los Angeles 68956 
   * Orlando 54691 
   * Dallas 41979 
   * Houston 39448
* Top 5 States in terms of number of accidents 
   * CA 795868 
   * FL 401388 
   * TX 149037 
   * OR 126341 
   * VA 113535
* The states with most number of accidents correspondingly also rank in the top states by count of population.
* New York despite having a high population has a considerably low count of accidents.
* A high percentage of accidents occur between 2 P.M and 6 P.M.
* Chance of accidents happening during weekdays is higher than during weekends.
* Winter months have more accident count.
* There has been a gradual increase in the number of accidents over the year which can be attributed to increase in number of vehicles on the streets.


## Acknowledgments

1) This project is mostly guided by Jovian and their youtube video titled, “Build an Exploratory Data Analysis Project from Scratch | Step-by-Step Guide”

2) The data set is duly credited to

  * Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. “A Countrywide Traffic Accident Dataset.”, 2019.

  * Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. "Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights." In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019
  
  
  
 <p align="center">
<img src='https://github.com/shrikrishnau/Portfolio/blob/main/images/traffic.jpg?raw=true' width="1000">

</p> 
  

