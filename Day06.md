**Day 6 - Interfaces and Abstract Classes**

**Interfaces**
- An interface is a contract that defines a set of methods that implementing classes must provide.
- A class can implement multiple interfaces but extend only one class.

**Abstract Classes**
- An abstract class is a class that cannot be instantiated, but it can have abstract and concrete methods.
- Abstract methods have no implementation and must be implemented by the subclasses.

**Java Interfaces and Abstract Classes Example**
```java
// Interface example
interface Shape {
    void draw();
}

// Abstract class example
abstract class Animal {
    abstract void sound();
}

class Dog extends Animal {
    @Override
    void sound() {
        System.out.println("Dog barks");
    }
}
```
