# Airline-client-segmentation

<img width="601" alt="image" src="https://user-images.githubusercontent.com/59221097/222922779-43ab380b-3b12-48ea-9d89-fb4757dcb355.png">

## Goal
Understanding customer segmentation of Sun Country Airline, and providing recommendations to increase membership and boost the customer booking rate.

## About data
- Flights information variables (serviceCity, startDate, airlinecode...)
- Passenger demographic variables (age, postalcode, gender...)
- Transaction details variables (bookingchannel, memberstatus, cardholder...)

## Data Preprocessing
1. Data Cleaning: Define primary key (Cus_ID = EncryptedName + birthdateid + GenderCode)
2. Feature Creation and data aggregation 
- Passenger information: UFly Membership Status, Age, Gender
- Booking information: Card holders, Number of trips, BookingChannel
- Ticket information: Total amount spent & number of discounts, Upgrade & downgrade
- Trip information: Number of trips by class

## Clustering
1. Used block randomization technique to take sample of data. This helped us wholistically understand every type of Sun Country Airlines customer
2. Used K-mediod to method cluster data (cluster number = 5)
3. Visualized to see how eliter customers/first class traveler perform in different cluster

## Result
We identified 5 segments and recommended based on cluster characteristics to help Sun Country Airline improve their customer experience and compete in the travel market.

<img width="723" alt="image" src="https://user-images.githubusercontent.com/59221097/222924025-6bf17311-25f0-48e0-9f74-9df590ea22b6.png">

## Business Recommendations
- Focusing on the periods after the Christmas holidays (Attract potential customers via promotion code)
- Boosting the customers’ booking rate on the website of Sun Country Airlines (Discounts on the first several rides, Free bags on the first trip)
- Seniors Travel Assistance programs
- Social Media Promotion
