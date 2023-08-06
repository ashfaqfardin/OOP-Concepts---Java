**Day 3 - Inheritance**

**Inheritance**
- Inheritance allows a class (subclass) to inherit properties and behaviors from another class (superclass).
- The subclass can extend the superclass by adding new members or overriding existing ones.

**Java Inheritance Example**
```java
// Base class (superclass)
class Animal {
    void sound() {
        System.out.println("Animal makes a sound");
    }
}

// Derived class (subclass)
class Dog extends Animal {
    @Override
    void sound() {
        System.out.println("Dog barks");
    }
}
```

