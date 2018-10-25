# Waste Management

## Background

With increasing populations, changing policy requirements, new sustainability and recycling goals and improved technology departments, municipalities across the globe are joining the “smart cities” movement to become more efficient in managing solid waste. The improvement of the urban waste collection service and, in general, the achievement of a more efficient management of the waste, is one of the main challenges that the cities face, especially due to the population growth. Thus, smart waste management is a key factor of smart cities.

## Problem statement

Design a smart waste collection system that allows citizens to segregate the various types of solid waste they want to dispose and the municipal authorities to efficiently collect the same. The system should be mobile app (Android) based.

The system should have two interfaces:

### Citizen

* Citizen should have an option to schedule a waste pickup request, at a particular date and time at his chosen location (via map or geolocation). The pickup request can be no less than 24 hours in advance.
* Citizen should mention the amount of waste for disposal, choose what categories of waste are present for disposal as well as optionally snap a picture of the waste.
* Citizen should be able to see all upcoming waste pickup requests, as well as past pickup request history.

### Garbage Collector

* Garbage collection is done via trucks. Each truck can only carry one category of waste. You have to calculate the most optimal route for each truck, basis the previous days pickup requests from citizens.
* Garbage collector should be shown a list of all pickups to be made that day, along with a most efficient route for all pickups. Please note that start and stop point for each truck is from a central depot with fixed location.
* There should be GPS based navigation for the garbage collector from one point to another.
* For each pickup request, garbage collector is shown the following:
  * Citizen name & location (address & map)
  * Garbage amount
  * Garbage category
  * Garbage photo, if available
  
The following categories of waste are available:
* Organic waste (kitchen waste, vegetables, flowers, leaves, fruits)
* Recyclable waste (paper, glass, metals, plastics)
* Toxic waste (old medicines, paints, chemicals, bulbs, spray cans, fertilizer and pesticide containers, shoe polish)
* Electronic waste (batteries, phones, TVs, laptops)

## Deliverables

For the demonstration of the system, you may use pre-filled data. We would like to see the codebase route matching algorithm you are using. We would also like to see your database schema. You can use any language or framework to create this system.

## Bonus credits

* Make a web interface for both citizen & garbage collector
* Implement a hybrid mobile app (Android/iOS)
* Make an admin web interface where we can see all garbage trucks, citizens, collection requests (past & upcoming) etc.
* Implement a waste classification helper for citizen which suggests what waste category it is after the citizen takes a photo of the waste. It can suggest multiple categories as well.

_&copy; 2018 Renderbit Technologies LLP. All rights reserved._
