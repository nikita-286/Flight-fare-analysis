### Flight Fare Analysis


### Introduction

This project analyzes how flight prices fluctuate over time and provides actionable insights for travelers on when to book flights for the best deals. By leveraging historical flight data, it predicts ticket prices based on commonly known features such as:

Route (source and destination cities)

Flight class (Economy, Business, etc.)

Number of stops

Booking lead time (days left until departure)

The project combines Exploratory Data Analysis (EDA), statistical insights, and predictive modeling to help users make informed decisions and save money.


### Dataset

The dataset contains historical flight booking information and includes the following columns:

| Column Name        | Data Type | Description |
|-------------------|-----------|------------|
| `airline`          | object    | Name of the airline |
| `flight`           | object    | Flight number or code |
| `source_city`      | object    | Departure city |
| `departure_time`   | object    | Scheduled departure time |
| `stops`            | object    | Number of stops (non-stop, 1 stop, etc.) |
| `arrival_time`     | object    | Scheduled arrival time |
| `destination_city` | object    | Arrival city |
| `class`            | object    | Ticket class (Economy, Business, etc.) |
| `duration`         | float64   | Flight duration in hours |
| `days_left`        | float64   | Days remaining until flight departure at time of booking |
| `price`            | float64   | Ticket price in local currency |
