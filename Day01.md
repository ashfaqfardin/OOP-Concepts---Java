**Day 1 - Introduction to OOP and Classes**

**OOP Introduction**
Object-Oriented Programming (OOP) is a programming paradigm that focuses on modeling real-world entities as classes and objects. OOP provides a set of principles and concepts to organize code and create reusable and maintainable software.

**Classes and Objects**
- A class is a blueprint or a template that defines the properties and behaviors of objects.
- An object is an instance of a class, representing a specific entity with its unique data and behavior.

**Java Class Example**
```java
// Define a simple class
class Car {
    // Properties
    String make;
    String model;
    int year;

    // Constructor
    public Car(String make, String model, int year) {
        this.make = make;
        this.model = model;
        this.year = year;
    }

    // Method
    public void start() {
        System.out.println("The car is starting...");
    }
}

// Create objects from the class
Car car1 = new Car("Toyota", "Camry", 2020);
Car car2 = new Car("Honda", "Civic", 2022);

// Access properties and call methods
System.out.println(car1.make); // Output: Toyota
car2.start(); // Output: The car is starting...
```
