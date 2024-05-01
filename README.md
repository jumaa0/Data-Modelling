# Airline Data Modelling Project

## Overview
This project aims to provide comprehensive business intelligence solutions for a major airline company. By analyzing various aspects of the airline's operations, such as flight activity, reservation processes, customer care interactions, frequent flyer programs, and hotel stay services, the project aims to assist executive management in making informed decisions to improve operational efficiency and customer satisfaction.

## Data Marts

### Flight Activity Data Mart
- **Purpose**: Analyze flight activity to ensure ongoing business processes.
- **Grain Level**: Ticket-reservation level, capturing revenue generated from each ticket reserved.
- **Dimensions**: Flights, aircraft, passengers, time, booking channels.
- **Facts**: Reservation details including date, time, passenger, aircraft, class, airport, ticket, channel, passenger profile, promotion, fare bases, flight, and revenue.

![image](https://github.com/jumaa0/Data-Modelling/assets/126451388/7e84cd9d-e9fa-4f51-a896-b0261fa3530a)


### Reservation Data Mart
- **Purpose**: Analyze reservation processes to understand customer booking behaviors and optimize revenue.
- **Grain Level**: Ticket-reservation level, capturing revenue generated from each ticket reserved.
- **Dimensions**: Passengers, aircraft, classes, airports, booking channels, passenger profiles, promotions, fare bases, flights, time.
- **Facts**: Reservation details including date, time, passenger, aircraft, class, airport, ticket, channel, passenger profile, promotion, fare bases, flight, and revenue.


![image](https://github.com/jumaa0/Data-Modelling/assets/126451388/cd04c1b4-9607-4e3a-b901-f57051845ff4)

### Customer Care Data Mart
- **Purpose**: Analyze customer care interactions to improve customer service and resolve issues efficiently.
- **Grain Level**: Segment level, allowing for detailed analysis of customer feedback and inquiries.
- **Dimensions**: Passengers, flights, employees, feedback types, time.
- **Facts**: Details of customer care interactions including passenger information, feedback key, origin and destination airports, date, type of feedback, employee handling the interaction, confirmation key, flight key, ticket key, segment sequence number, description, and rating.

![image](https://github.com/jumaa0/Data-Modelling/assets/126451388/2aacdf88-cfd0-41ce-b2d2-52f0d5e69fa2)

### Frequent Flyer Data Mart
- **Purpose**: Analyze frequent flyer program data to understand passenger behavior and improve program effectiveness.
- **Grain Level**: Passenger level, providing insights into points earned and redeemed.
- **Dimensions**: Passengers, passenger profiles, properties, time.
- **Facts**: Details of frequent flyer program activities including date, passenger information, passenger profile, property information, and points redeemed.


![image](https://github.com/jumaa0/Data-Modelling/assets/126451388/fb43a955-a54c-45a2-baa0-f6540d25e409)

### Hotel Stay Data Mart
- **Purpose**: Analyze hotel stay services to understand passenger preferences and improve service offerings.
- **Grain Level**: Reservation level, providing information about the duration of stays.
- **Dimensions**: Reservations, properties, sales channels, time.
- **Facts**: Details of hotel stay services including reservation date, arrival and departure dates, passenger information, property information, confirmation number, ticket number, and number of nights.

![image](https://github.com/jumaa0/Data-Modelling/assets/126451388/52e6548d-5e0e-40f8-a2b3-7755e9764b9f)

## Importance of Data Marts
- Decision Making: Provide actionable insights for executive management to make informed decisions and improve operational efficiency.
- Customer Satisfaction: Enhance customer satisfaction and loyalty by analyzing customer care interactions and frequent flyer programs.
- Revenue Optimization: Optimize revenue generation by analyzing reservation data to understand booking behaviors and trends.
- Operational Efficiency: Improve operational efficiency in terms of scheduling, capacity planning, and resource allocation.
- Competitive Advantage: Provide a competitive advantage by identifying new opportunities and trends in the market.

[Shcema](image.png):



## Implementation
The data marts were built by implementing four steps:
1. Define Business Processes: Identified key business processes such as flight activity, reservation management, customer care interactions, frequent flyer programs, and hotel stay services.
2. Define Grain Levels: Determined the appropriate grain levels for each data mart, considering the business aspects and needs.
3. Define Dimensions: Created dimensions related to each business process to provide context and granularity to the data.
4. Define Facts: Designed fact tables to capture key metrics and attributes for analysis and reporting purposes.

## Documentation
- [Documentation](Documentation.pdf)


## Conclusion
The Airline Business Intelligence Project aims to leverage data analytics to improve various aspects of the airline's operations. By implementing data marts for flight activity, reservation management, customer care interactions, frequent flyer programs, and hotel stay services, the project aims to provide valuable insights for decision-making and operational optimization.
