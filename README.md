# Global-Trade-Analytics-master

### Dashboard Link : https://app.powerbi.com/groups/me/reports/5aec5163-39cf-42ec-afb5-3d14e1040b03/ReportSection?redirectedFromSignup=1&experience=power-bi

## Problem Summary
## Objective:
Following the COVID-19 pandemic, the aviation industry began to recover from the significantly low ticket prices experienced during the peak of the pandemic. However, the war in Ukraine and the rise in Aviation Turbine Fuel (ATF) prices have driven ticket prices to unprecedented highs. This project aims to analyze ticket prices in India to better understand the factors influencing them. The goal is to uncover insights regarding the number of flights available across India, the availability of tickets in different classes, and the price range for each class.

## Problem Statement:
The analysis focuses on identifying and understanding key factors, such as the class of travel, duration of flight, and other variables, that affect ticket pricing. By doing so, the objective is to enable more efficient planning and scheduling of air travel.

## Data Description:
The dataset, cleaned and prepared for analysis, includes the following features:

__Airline:__ The name of the airline. There are six different airlines, making it a categorical trait.

__Flight:__ The flight code of the aircraft.

__Source City:__ The city from which the flight departs, with six distinctive cities represented.

__Departure Time:__ A categorical feature indicating the time period of departure, binned into six different time labels.

__Stops:__ The number of stops between the source and destination cities, categorized into three different values.

__Arrival Time:__ A categorical feature indicating the time period of arrival, binned into six different time labels.

__Destination City:__ The city where the flight lands, with six distinctive cities represented.

__Class:__ Indicates the travel class (e.g., economy, business).
Duration: The total number of hours needed to travel between cities.

__Days Left:__ Derived feature calculated by subtracting the booking date from the trip date.

__Price:__ The target variable storing information about the ticket price.

        
## Screenshots of Dashboard

![Screenshot 2024-06-17 163907](https://github.com/avinashgiri324/Airlines-in-India-Ticket-Prices/assets/140068588/bd876d2a-86a0-4dd4-a644-f1ebd9754e98)


 
 
## Insights Derived

__1- Airline Pricing by Class:__

--Economy Class: 'Air Asia' offers the cheapest flight tickets.

--Business Class: 'Air India' offers the cheapest flight tickets.

__2- Optimal Booking Window:__

--3-7 Weeks Before Travel: Booking tickets during this period is generally cheaper.

--Within 3 Weeks of Travel: Prices rise rapidly, especially in the 2-20 days before travel.

--1 Day Before Travel: Tickets can be cheaper but not as cheap as when booked more than 3 weeks in advance.

__3- Ticket Price and Flight Duration:__

--Linear Growth: Ticket prices increase linearly with the duration of the flight, peaking at around 20 hours.

--Outliers: Due to some outliers, prices may fall for flights with a duration of more than 20 hours. The relationship can be approximated by a 2nd-degree curve.

__4-Departure and Arrival Times__:

--Cheapest Flights: Flights departing late at night and arriving early morning or late at night tend to be the cheapest.

__5-Number of Stops:__

--Price Increase: Ticket prices increase with the number of stops.

__6-City-Specific Pricing:__

--Cheapest Flights: Delhi offers the cheapest flights.

--Most Expensive Flights: Hyderabad is the most expensive city to fly to.

These insights provide a comprehensive understanding of the factors influencing air travel prices in India, aiding travelers in making informed decisions to plan and schedule their trips more efficiently.
