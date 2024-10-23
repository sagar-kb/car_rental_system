# Car Rental System in Java

This project is a simple **Car Rental System** implemented in Java. It allows customers to rent cars for a specified number of days, and it calculates the total price based on the car's base price per day. The system also provides an option for returning rented cars.

## Features

- **Car Rental**: Customers can rent a car from the available options.
- **Car Return**: Rented cars can be returned, updating the car's availability status.
- **Price Calculation**: The total rental price is calculated based on the number of days a car is rented.
- **Car and Customer Management**: The system tracks cars and customers, allowing multiple rentals and returns.

## Classes

1. **Car**: Represents a car available for rent, with attributes such as car ID, brand, model, base price per day, and availability status.
2. **Customer**: Represents a customer who rents a car, storing customer ID and name.
3. **Rental**: Represents the rental details, including the rented car, customer, and rental duration.
4. **CarRentalSystem**: Manages the list of cars, customers, and rentals, providing functionality for renting and returning cars.
5. **Main**: Entry point of the application, initializing the car rental system and cars, and providing the user interface for interacting with the system.
