**Day 2 - Encapsulation and Abstraction**

**Encapsulation**
- Encapsulation is the process of bundling data (properties) and methods (behaviors) within a class.
- It helps in data hiding, protecting the internal implementation, and ensuring controlled access to class members.

**Access Modifiers**
- Java has four access modifiers: `public`, `private`, `protected`, and package-private (default).
- `public`: Accessible from any class.
- `private`: Accessible only within the same class.
- `protected`: Accessible within the same package or subclasses.
- Default: Accessible within the same package.

**Abstraction**
- Abstraction allows us to create abstract classes and methods that define a contract but have no implementation.
- Abstract classes can have both abstract and concrete methods.

**Java Encapsulation and Abstraction Example**
```java
// Encapsulation and Abstraction example
class BankAccount {
    private String accountNumber;
    private double balance;

    public BankAccount(String accountNumber) {
        this.accountNumber = accountNumber;
        this.balance = 0.0;
    }

    public double getBalance() {
        return balance;
    }

    public void deposit(double amount) {
        if (amount > 0) {
            balance += amount;
        }
    }

    public void withdraw(double amount) {
        if (amount > 0 && amount <= balance) {
            balance -= amount;
        }
    }
}
```
