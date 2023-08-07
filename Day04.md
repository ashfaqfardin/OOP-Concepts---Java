**Day 4 - Polymorphism**

**Polymorphism**
- Polymorphism allows objects to take multiple forms. In Java, it can be achieved through method overloading and method overriding.

**Method Overloading**
- Method overloading allows defining multiple methods with the same name but different parameter lists.

**Method Overriding**
- Method overriding occurs when a subclass provides a specific implementation for a method that is already defined in its superclass.

**Java Polymorphism Example**
```java
// Method Overloading example
class MathOperations {
    int add(int a, int b) {
        return a + b;
    }

    double add(double a, double b) {
        return a + b;
    }
}

// Method Overriding example
class Shape {
    void draw() {
        System.out.println("Drawing a shape");
    }
}

class Circle extends Shape {
    @Override
    void draw() {
        System.out.println("Drawing a circle");
    }
}
```
