# NYC-taxi-trip-time-prediction
ML - Regression project
Abstract:

New York City taxi rides form the core of the traffic in the city of New York. Predicting the duration of a taxi trip is very important since a user would always like to know precisely how much time it would require of him to travel from one place to another. Prediction of duration can help users to plan their trips properly, thus keeping potential margins for traffic congestions. It can also help drivers to determine the correct route which in-turn will take lesser time as accordingly. Moreover, the transparency about trip duration will help to attract users.

We used six months data, of the year 2016 which contains data of customers who would provide at the start of a ride, or while booking a ride.

Introduction

New York City is one of the highly advanced cities of the world with extensive use of taxi services. Along with a vast population, the requirement of commonly available transportation serves the common purpose as it provides a very large transportation system. New York facilitates one of the largest subway systems in the world and comprises various green and yellow cabs which approximately count of around 13,000 taxis. Most of the population of New York depends upon public transport, and it has been estimated that 54 percent of the people do not own a car or a personal vehicle. As a matter of fact, it accounts for almost 200 million taxi trips per year. Our goal here is to build a predictive model, which could help in predicting the time duration of each trip.

Problem Statement:

Task is to build a model that predicts the total ride duration of taxi trips in New York City. Your primary dataset is one released by the NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.

 id - a unique identifier for each trip

 vendor_id - a code indicating the provider associated with the trip record

 pickup_datetime - date and time when the meter was engaged

 dropoff_datetime - date and time when the meter was disengaged

 passenger_count - the number of passengers in the vehicle (driver entered value)

 pickup_longitude - the longitude where the meter was engaged

 pickup_latitude - the latitude where the meter was engaged

 dropoff_longitude - the longitude where the meter was disengaged

 dropoff_latitude - the latitude where the meter was disengaged

 store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip

 trip_duration - duration of the trip in seconds. (DV)
