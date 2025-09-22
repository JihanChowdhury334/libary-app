# 📚 Library / Bookstore Management App (Java)

A console-based Java application simulating a **library/bookstore system**.  
Built to practice **object-oriented programming (OOP), state patterns, and class design**.

---

## 🚀 Features & Functionality
- **Book Management**
  - Add and manage book objects (`Book` class).  
  - Track titles, authors, and availability.  

- **User Management**
  - Two main roles: `Customer` and `Owner`.  
  - `Owner` can manage inventory and oversee the system.  
  - `Customer` can browse, borrow, and return books.  

- **Customer State Pattern**
  - Implements **Silver** and **Gold** membership states (`SilverState`, `GoldState`).  
  - Rewards frequent users with perks (e.g., discounts, benefits).  
  - Demonstrates the **State design pattern**.  

- **Application Entry Point**
  - `BookStoreApp.java` runs the system and ties together all functionality.  

---

## 🧠 What I Practiced & Learned
- **Java OOP**
  - Encapsulation, inheritance, polymorphism, and abstraction.  
  - Working with multiple interacting classes (`Book`, `Customer`, `Owner`, `CustomerState`, etc.).  

- **Design Patterns**
  - Implemented the **State pattern** to handle customer membership levels dynamically.  

- **Project Structure**
  - Organized code into logical classes inside `src/`.  
  - Focused on clean modular design for scalability.  

---

## 📂 Project Structure
```
src/
├── BookStoreApp.java   # Main entry point
├── Book.java           # Book entity class
├── Customer.java       # Customer class
├── Owner.java          # Owner class
├── CustomerState.java  # Abstract state class
├── SilverState.java    # Silver membership state
├── GoldState.java      # Gold membership state
├── User.java           # Base user class
```

---

## 🛠️ Compilation & Usage
```bash
# Compile all Java files inside src
javac src/*.java

# Run the application
java -cp src BookStoreApp
```

---

## 🎯 Purpose
This project is an **early OOP learning exercise** showcasing:
- Java fundamentals and object-oriented principles.  
- State design pattern implementation.  
- Building a modular, console-based management system.  
