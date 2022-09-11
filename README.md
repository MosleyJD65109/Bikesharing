# BikeSharing Data Analysis

# Overview
This data analysis encompasses the NYC City Bike Data Analysis with Tableau


# Results

The Tableau Story can be consulted here:
https://public.tableau.com/views/Bikesharing_16627426405760/BikeSharingChallenge?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link


Bike riding is growing as the preferred transportation method for people of all ages. It´s fun, healthy, cheap and lets people see their neighborhood in a new way. Bike-sharing services, like Citi Bike in NYC, lets people to use a bike in a single way to go  to school or work or even in a tourist ride, deliver it in a station, and use another when required. That´s why bike-sharing program could be an atractive and very profitable bussines. Here, we will present the NYC Citi Bike Data Analysis from August 2019 in order to  convince investors that a bike-sharing program in Des Moines is a solid business proposal.

Althought Des Moines is not a large and dinamic city as New York City, its data can help us answer a few questions:  

  - Who uses bikeshare program?
  - How often they them?
  - What days are bikeshare used the most? and the least?
  - Who uses bikeshare the most, men or women? 
  - How old are most frequently users?
  - Who use more the bikes, suscribers or tourists?
 
To answer this questions, I analized the data with Tableau, taking advantage of its ploting options, combining the results and presented it  as a Tableau Story. 

## Cleaning the DataFrame
We start by changing the trip duration into a datetime format.

![clean data frame](https://user-images.githubusercontent.com/104540261/189543335-f75bbeb7-0928-4ec3-ab77-1058a9d19f0c.png)


## Checkout times 
In this plot we can see that mostly users take less than 30 minutes, so we can think they bikes for short trips, maybe to work, to school or only fot shor trips instead using motor driven transportation. In the second plot, we can see that men men and women ....

![Checkout](https://user-images.githubusercontent.com/104540261/189544056-5b98757e-827f-4c8b-90fb-b7f2187cfbf9.png)

## Checkout Times by Gender

![Checkout Times by Gender](https://user-images.githubusercontent.com/104540261/189544104-8f3c9e64-fef8-4bd9-a8a7-5d0ba91b5d13.png)


## Trips by Weekday 
In this heatmap, we can observe that service is mostly used on weekdays around office hours, and all day on weekends. We have an exception on Wednesdays afternoon, but we need more information.

![Trips by Weekday per Hour](https://user-images.githubusercontent.com/104540261/189544197-d0a5a4c5-c242-4440-94aa-9474b6b50363.png)


## Trips by Gender and Weekday
Here we can we can appreciate  that men and women has the same schedule  but men uses most the service than women. 

![Trips by Gender(Weekday per Hour)](https://user-images.githubusercontent.com/104540261/189544272-f7feb388-206a-459f-a1d1-fac93b4576cc.png)


## User Trips by Type and Gender 
This heatmap show us mostly users are Subscribers, i.e, users that prefers to  pay a perdiodical fee. This is a very interesting point, because suscription  is  a regular income to the bussiness. Customers could be ocasional users o tourists. The pie chart show us the proportion of Subscribers versus Customers. A opportunity to engage future subscribers!

![Trips by Gender by Weekday](https://user-images.githubusercontent.com/104540261/189544570-93959601-7758-4e32-a01b-ff9c23e4f70e.png)


# Summary 
Taking the experience of NYC bikesharing service may  give us a light about how atractive and affordable is this growing industry. It´ s a healthy, non contaminant, cheap and a fun way of transportation, so it´'s not a far-fetched idea that a bikesharing service like Citi Bike becomes successful in a metroplolitan area as  Des Moines. Althought there are very different cities in size, population, even weather, the fact is that Des Moines is beautiful city  that could be enriched  with a bikesharing services. 

Aditional to this information, I would propose two aditional plots to help explore the target maket in Des moins
  1. Users by Age.
  
   <img width="660" alt="Users per age" src="https://user-images.githubusercontent.com/102195803/177906484-6fb79a03-86ff-45f1-a336-9439a29cdf6e.png">
  2. Usertypes by Gender 
  
  <img width="660" alt="Aditional plots" src="https://user-images.githubusercontent.com/102195803/178115981-08479914-d1b6-4812-ace0-7ebf14bfd17e.png">

