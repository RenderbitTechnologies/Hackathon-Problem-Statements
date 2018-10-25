# Urban Transport

## Background

Transport demand in India has increased by almost eight times since the 1980s as rapid economic development and increasing wealth among households has led to higher vehicle ownership. This is higher than anywhere else in the Asia-Pacific region, according to BCG. On average, travellers in Delhi, Mumbai, Bengaluru, and Kolkata spend 1.5 hours more on their daily commutes than their counterparts in other Asian cities during peak traffic times, according to an April 18 report released by The Boston Consulting Group (BCG) and commissioned by Uber. It is estimated that traffic jams in just these four Indian cities cost $22 billion a year.

Road congestion may be reduced by the use of good public transport management, traffic management and car pools. Carpooling is the easiest and most common ridesharing arrangement. Promoting more efficient carpooling can not only help with urban traffic decongestion, but will also go a long way towards reducing environmental impact by cutting down emissions and idling.

## Problem Statement

Design a car pooling system which takes into account the points of start & stop of the commuter and availability of cars at that particular point in time to match him with available vehilces. The system should be mobile app (Android) based.

The system should have two interfaces:

### Vehicle Owner

* For a vehicle owner, it should give an option to add his vehicles(s) with appropriate parameters
* The vehicle owner should be able to mention the availabilty of each vehicle for carpooling for at least the next 7 days
* The vehicle owner should be able to see all upcoming carpooling requests and approve/reject each request
* He should also be able to see a record of past trips

### Commuter

* For a commuter, he should be able to search for available vehicles by mentioning 3 parameters:
  * Trip start location
  * Trip end location
  * Trip start date & time
* He should be able to send carpooling requests to multiple car owners for at least the next 7 days
* He should be able to see all upcoming trips with status (approved/rejected)
* He should be able to see all past trips


## Deliverables

For the demonstration of the system, you may use pre-filled data. We would like to see the codebase route matching algorithm you are using. We would also like to see your database schema. You can use any language or framework to create this system.

## Bonus credits

* Make a web interface for both vehicle owner & commuter
* Implement a hybrid mobile app (Android/iOS)
* Make an admin web interface where we can see all vehicle owners, commuters, trips, trip requests (past & upcoming) etc.
* Implement billing logic for each trip:
  * Vehicle owner mentions cost per kilometer and cost per minute for each vehicle
  * Trip data is collected from start & end time and distance computation
  * Payment is collected at end of trip

&copy; 2018 Renderbit Technologies LLP. All rights reserved.
