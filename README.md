# CarRentalSystem
This Java project is a simple implementation of a Car Rental System focusing on **Object-Oriented Programming (OOP)** concepts. The project allows users to fetch car details, check availability based on date and time, and retrieve owner information for each car in the system.
<hr>
# Features
View car details such as make, model, year, and mileage.
Check availability of cars for a specific date and time.
Retrieve owner information for each car.
Object-Oriented Concepts Used
Classes and Objects:

Various classes are used to represent different entities such as Car, RentalSystem, and Owner.
Objects are instantiated from these classes to interact with the system.
**Encapsulation:**

Data members in classes are private, accessible only through public getter and setter methods.
**Inheritance:**

Inherited relationships might be used for different types of cars, such as Sedan, SUV, or Truck.
**Polymorphism:**

Methods like checkAvailability() might behave differently based on the type of car.
<hr>
# How to Use
Clone the repository to your local machine:
bash

git clone https:[Click Me to Go to GitHub](https://github.com/Jayeshpansuriya/CarRentalSystem/blob/c33ebc34a1fd15ac04f01a976470e9c175a86e1a/Car%20Rental%20System/car.java)
Compile the Java files:

<hr>

# Follow the on-screen instructions to:

View car details
Check availability
Retrieve owner information
Project Structure
perl
<hr>
car-rental-system/
│
├── Main.java        # Main class to run the program
│
├── Car.java         # Class representing a Car
├── Owner.java       # Class representing an Owner
└── RentalSystem.java# Class representing the Rental System

<hr>
# Example Usage
java
<hr>
// Create a Car Rental System
RentalSystem carRental = new RentalSystem();

<hr>
// Add cars to the system
carRental.addCar(new Car("Toyota", "Camry", 2020, 25000, true, new Owner("John Doe", "123 Main St")));
carRental.addCar(new Car("Honda", "CRV", 2021, 20000, false, new Owner("Jane Smith", "456 Elm St")));

<hr>
// Check availability for a specific date and time
boolean available = carRental.checkAvailability("Toyota Camry", "2024-04-10", "10:00 AM");

<hr>
if (available) {
    System.out.println("The car is available for rent!");
} else {
    System.out.println("Sorry, the car is not available for the specified date and time.");
}

<hr>
// Get owner information for a car
Owner owner = carRental.getOwner("Toyota Camry");
System.out.println("Owner of Toyota Camry: " + owner.getName());
<hr>


# Contributing
Contributions are welcome! If you have ideas on how to improve this Car Rental System, please open an issue or submit a pull request.
<hr>

# License
This project is licensed under the MIT License - see the LICENSE file for details.
