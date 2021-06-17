# airbnb-munich

Udacity Data Science NanoDegree Project #1

## Table of contents
[Installation](#installation) <br>
[Motivation](#motivation) <br>
[File Description](#file) <br>
[Findings](#findings) <br>


## Installation
<a name="installation"/>
The code in the project can be executed using Anaconda / a Jupyter Notebook and Python ver 3.x and does not require any additional scripts.

## Motivation
<a name="motivation"/>

The objective of this analysis is to find insights in the AirBnB data from Munich. The project is part of the Udacity Nanodegree program Data Science. As AirBnB is a common way to travel and is especially attractive for low budget travels, one focus of this analysis will be to determine factors that influence the price of an AirBnB. By doing so I build a data model to predict the price of an accommodation. Next, for hosts one of the major sources for trust are the reviews. Therefore investigating variables that influencing a good review will be analyzed. After this I try to use the gained knowledge to find particular interesting AirBnB objects in Munich that have a price below the average but are still performing above the average in all the other categories.

The findings of the project are published here and in a blog article on medium.

## File descriptions
<a name="file"/>

Readme.md (this file) <br>
EDA.ipynb (the python Notebook) <br>
listings.csv.gz  <br>
listings.csv  <br>
neighbourhoods.csv <br>
reviews.csv.gz <br>
Data source — http://insideairbnb.com/get-the-data.html <br>

## Findings
<a name="findings"/>

The analysis focused on three questions:<br>

1. Which factors are influecing the price of an AirBnB? <br>
2. Which factors are influencing a review? <br>
3. Are there, based on the learnings from the question 1 & 2 underrated AirBnBs? <br>

First, the data provides information about that a price varies depending on the neighourhood and the room type of an AirBnB. The data model could, although we performed several iterations of feature engineering, predict the price with a r2 of 23,1%. Neighbourhood had the biggest impact on predicting the price iwth Altstadt-Lehel being the most expensive one. After that the room type of a shared room and private room predicted the price in a negative way. The host response time also played a important factor in predicting the price with having a negative impact when the host responded within a day.
Second, I build a data model that could predict the review rating with a r2 of 68,1%. Further analysis showed that especially the accuracy of availabe data on a certain AirBnB and the communication with the host as well as the cleanliness had a strong and positive impact on the reviews. Also in which neighbourhood the AirBnB is located tends to have an influence on the review.
Third, with this knowledge I tried to find AirBnBs that are underrated in terms of the price / performance ratio. I searched for listings that have a price below the average of the given neighbourhood and room type and perform better than the average in the reviews for a certain neighbourhood. With this search criteria I could identify six AirBnBs that are potentially interesting. The data also shows that those AirBnBs are highly booked what underlines there special value.

<br>
### Further information
Author<br>
Christoph Emmert<br>

<br>
https://github.com/chrisdiss/airbnb-munich/<br>
Blog at Medium - 
<br>

Thanks to Udacity for providing the necessary information for analyzing this data set.
