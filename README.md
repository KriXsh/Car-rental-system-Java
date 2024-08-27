# Car Rental System            

## Overview

The Car Rental System is a Java-based application that allows users to rent and return cars. The system manages car inventory, customer information, and rental transactions.
            
## Features          
           
- **Rent a Car**: Allows users to rent an available car and calculates the total rental price.
- **Return a Car**: Allows users to return a rented car and updates its availability status.
- **Car Availability**: Displays a list of available cars for rent.
- **Customer Management**: Adds new customers during the rental process.
   
## Classes      
      
- **Car**: Represents a car with details such as ID, brand, model, base price per day, and availability.
- **Customer**: Represents a customer with details such as ID and name.
- **Rental**: Represents a rental transaction including the car, customer, and rental duration.
- **CarRentalSystem**: Manages the car rental operations including adding cars, renting cars, and returning cars.

## How to Run

1. Clone the repository:

   
   git clone https://github.com/KriXsh/Car-rental-system-Java.git

2. Navigate to the project directory:
     
    cd Car-rental-system-Java

3. Compile the Java code:

    javac -d bin src/*.java

4. Run the application:

  java -cp bin carRental



## Example
When running the application, choose the option to rent a car.
Enter your name and select an available car.
Enter the rental duration to get the total rental price.
Confirm the rental or cancel it.
For returning a car, provide the car ID to mark it as returned.

## Contribution
Feel free to contribute to this project by creating issues or submitting pull requests.

