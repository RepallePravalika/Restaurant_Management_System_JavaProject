# Restaurant_Management_System_JavaProject
The Project is about Restaurant Management System 

Project Overview
The Restaurant Management System is a Java-based application that simulates a simple restaurant ordering system. The system allows users to view a menu, place orders, and calculate the bill based on different billing strategies, such as normal billing and happy hour discounts. The program demonstrates key object-oriented programming concepts, including classes, inheritance, encapsulation, and polymorphism.

Features
Menu Management: Displays a list of dishes and drinks available in the restaurant with their respective prices.
Order Placement: Users can select items from the menu to create an order.
Billing Strategies:
Normal Billing: No discounts applied.
Happy Hour Billing: A 20% discount applied to the total bill.
Interactive Console Input: Users interact with the system through console input to place their orders.
Object-Oriented Concepts
Classes: Represent entities like Restaurant, Menu, Order, Dish, and Drink.
Inheritance: The Drink class inherits from the Dish class.
Encapsulation: The Order class encapsulates the details of the items ordered.
Polymorphism: Different billing strategies (NormalBillingStrategy and HappyHourBillingStrategy) demonstrate polymorphism.
Project Structure
css
Copy code
RestaurantManagementSystem/
├── Dish.java
├── Drink.java
├── Menu.java
├── Order.java
├── BillingStrategy.java
├── NormalBillingStrategy.java
├── HappyHourBillingStrategy.java
├── Restaurant.java
└── RestaurantManagementSystem.java

Class Descriptions
Dish.java: Represents a dish on the menu, including its name and price.
Drink.java: Represents a drink, which is a special type of dish with an additional attribute (isAlcoholic).
Menu.java: Manages the list of available dishes and provides a method to display the menu.
Order.java: Manages the list of ordered items and provides a method to display the order.
BillingStrategy.java: Interface for billing strategies.
NormalBillingStrategy.java: Implements normal billing without discounts.
HappyHourBillingStrategy.java: Implements billing with a 20% discount during happy hour.
Restaurant.java: Manages the menu, orders, and billing.
RestaurantManagementSystem.java: The main class that runs the program, interacting with the user through console input.

OUTPUT

AFTER RUNNING THE PROJECT
---- Menu ----
1. Biryani-Single - ₹230.0
2. Biryani-Full - ₹500.0
3. Roti-3 with panner - ₹350.0
4. Thumsup - ₹50.0
5. Sprite - ₹50.0
6. Wine - ₹200.0
Enter the item number to add to your order (or 0 to finish):

AFTER CHOOSING THE OPTION
Enter the item number to add to your order (or 0 to finish): 1
Biryani-Single added to your order.
Enter the item number to add to your order (or 0 to finish): 3
Roti-3 with panner added to your order.
Enter the item number to add to your order (or 0 to finish): 4
Thumsup added to your order.
Enter the item number to add to your order (or 0 to finish): 0

AFTER CALCULATING YOUR BILL
---- Your Order ----
Biryani-Single - ₹230.0
Roti-3 with panner - ₹350.0
Thumsup - ₹50.0
Total Bill: ₹630.0
With Discounts.....
Total Bill during Happy Hour: ₹504.0


