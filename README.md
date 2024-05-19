🚗 Car Rental System
--------------------------------------------------------------------------------------------------------------

##Overview
This Car Rental System is a Java-based application developed using core Java concepts. It provides functionalities to manage a fleet of rental cars, handle customer information, and process rentals. The project employs Object-Oriented Programming (OOP) principles and Java Collections framework to ensure a robust and scalable design.

##Features
Car Management: Add, update, delete, and view cars available for rent.
Customer Management: Add, update, delete, and view customer details.
Rental Processing: Rent a car to a customer, return a car, and view rental history.
Search and Filter: Search cars by various attributes (e.g., make, model, availability).


##Technologies Used
Java: The core programming language used for development.
Java Collections Framework: Utilized for managing data using ArrayList.
Object-Oriented Programming (OOP): Principles like classes, objects, and encapsulation are used to design the system.


##OOP Concepts
Classes and Objects: Defined classes for Car, Customer, and Rental, each encapsulating relevant properties and methods.
Encapsulation: Used private fields with public getters and setters to protect data.


##Collections
ArrayList: Used to store and manage collections of Car, Customer, and Rental objects. The ArrayList provides dynamic array capabilities, allowing the system to handle an undefined number of elements efficiently.


##Database Simulation
In this project, a traditional database is simulated using ArrayList. This approach simplifies the implementation while allowing us to focus on core Java concepts. Each entity (e.g., cars, customers, rentals) is stored in its respective ArrayList.

##Example Code Snippet

import java.util.ArrayList;

public class CarRentalSystem {
    private ArrayList<Car> carList;
    private ArrayList<Customer> customerList;
    private ArrayList<Rental> rentalList;

    public CarRentalSystem() {
        carList = new ArrayList<>();
        customerList = new ArrayList<>();
        rentalList = new ArrayList<>();
    }

    public void addCar(Car car) {
        carList.add(car);
    }

    public void addCustomer(Customer customer) {
        customerList.add(customer);
    }

    public void addRental(Rental rental) {
        rentalList.add(rental);
    }

    // Additional methods for managing cars, customers, and rentals
}

##Getting Started

Clone the Repo: https://github.com/gajendra29/CarRental_Project.git

##Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request. Contributions are welcome and appreciated!