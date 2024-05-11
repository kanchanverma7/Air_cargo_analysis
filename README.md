# Air_cargo_analysis
To analyze the busiest route which helps to increase the number of aircraft required and prepare an analysis to determine the ticket sales details.

Air Cargo Database Management System
Introduction:
The Air Cargo Database Management System is designed to facilitate the analysis of passenger travel data and ticket sales details for Air Cargo, an aviation company. The system aims to identify regular customers, analyze popular routes, and optimize ticket sales strategies to improve customer satisfaction and operational efficiency.

Project Objectives:
Identify regular customers to provide personalized offers.
Analyze the busiest routes to optimize aircraft allocation.
Prepare detailed analyses of ticket sales to enhance revenue generation and customer service.

Dataset Description:
The dataset comprises several tables containing information on customers, passenger travel details, ticket sales, and route information. Key tables include:

Customer: Contains customer information such as ID, name, date of birth, and gender.
Passengers_on_flights: Records travel details including aircraft ID, route ID, customer ID, travel date, seat number, and class ID.
Ticket_details: Stores ticket purchase details including purchase date, customer ID, aircraft ID, class ID, number of tickets, ticket price, and airline brand.
Routes: Contains route details including route ID, flight number, origin airport, destination airport, aircraft ID, and distance in miles.

Operations to be Performed:
ER Diagram: Create an Entity-Relationship (ER) diagram for the database.
Table Creation: Write a query to create the route_details table with appropriate data types and constraints.
Passenger Query: Display all passengers who have traveled on routes 01 to 25.
Business Class Analysis: Identify the number of passengers and total revenue in the business class.
Customer Details: Extract full names of customers from the customer table.
Customer Registration Query: Identify customers who have registered and booked tickets.
Customer and Brand Query: Identify customers who have traveled with a specific airline brand.
Economy Plus Query: Identify customers who have traveled in Economy Plus class.
Revenue Threshold Query: Determine if revenue has crossed a certain threshold.
User Management Query: Create a new user and grant database access.
Maximum Ticket Price Query: Find the maximum ticket price for each class using window functions.
Performance Optimization: Optimize performance for retrieving passengers on a specific route.
Execution Plan Query: View the execution plan for retrieving passengers on a specific route.
Rollup Function Query: Calculate total ticket prices for each customer across different aircraft IDs.
Business Class View Query: Create a view containing only business class customers and airline brands.
Stored Procedure 1: Get details of passengers flying between a range of routes.
Stored Procedure 2: Extract details of routes with distances exceeding 2000 miles.
Stored Procedure 3: Group flight distances into categories based on travel distance.
Stored Function Query: Determine if complimentary services are provided based on the ticket class.
Cursor Query: Extract the first record of a customer with a specific last name.

Implementation:
The project involves writing SQL queries and stored procedures to perform the required operations on the Air Cargo database.

Requirements
SQL database management system (MySQL)
Dataset provided in the course resource section
Author:
Kanchan Verma

License
This project is licensed under the MIT License
