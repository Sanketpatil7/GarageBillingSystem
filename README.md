<h1 align="center">🚗 Garage Billing System (Java Console Application)</h1>
A simple Garage Service Billing System built using Core Java and OOP concepts.
This console-based application allows a garage to manage customers, assign services, and generate invoices.

🎯 What I Learned
- Implemented OOP concepts in real application
- Learned how to manage data using HashMap and ArrayList
- Understood object relationships using composition
- Practiced Java console application design

This project was built as part of my learning journey in Core Java.
I wanted to apply OOP concepts in a real-world scenario like a garage billing system.


📌 Features

✅ Add new customers

✅ Store customer car details

✅ Display available garage services

✅ Add multiple services to a customer

✅ Automatically calculate total bill

✅ Generate formatted invoice

🛠️ Technologies Used

Java

OOP Concepts:

Encapsulation

Composition

Collections (HashMap, ArrayList)

Classes & Objects

Constructor usage

Java Scanner for user input

🏗️ Project Structure
GarageBillingSystem/
│
├── Car.java
├── Customer.java
├── Service.java
├── Invoice.java
├── GarageService.java
└── GarageBillingApp.java

🧠 OOP Concepts Implemented
1️⃣ Encapsulation

All fields are private and accessed using getter methods.

Example:

private String carNumber;
public String getCarNumber() { return carNumber; }

2️⃣ Composition

A Customer has-a Car
An Invoice has-a list of Service

private Car car;
private List<Service> serviceList;

3️⃣ Collections Framework

HashMap<String, Customer> → Stores customers by car number

ArrayList<Service> → Stores available and selected services

🚀 How to Run the Project....

Clone the repository

git clone git clone https://github.com/Sanketpatil7/GarageBillingSystem.git



Open in any Java IDE (IntelliJ / Eclipse / VS Code)

Run:

GarageBillingApp.java

📷 Sample Output
------------------Bharti Car Service Center------------------
1. Add Customer
2. Display Services
3. Exit

Available Services:
1. Car Wash - ₹500
2. Oil Change - ₹700
3. Wheel Alignment - ₹300
4. Tyre Replacement - ₹3000
5. Puncture - ₹50

💡 Future Improvements

🔹 Store customer data in file/database

🔹 Add date & time in invoice

🔹 Add GST calculation

🔹 Export invoice as PDF

🔹 Build GUI using JavaFX / Swing
