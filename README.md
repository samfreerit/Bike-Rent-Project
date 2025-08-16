# Bike-Rent-Project

A Bike Rental System


A full fledged bike rental system implemented in Python using object oriented programming.

Customers can see available bikes on the shop. Rent bikes on daily basis Rs.100 per day. Rent bikes on weekly basis Rs.500 per week. Family Rental, a promotion that can include from 3 to 5 Rentals (of any type) with a discount of 30% of the total price.

The bike rental shop can issue a bill when customer decides to return the bike, display available inventory ,take requests on daily and weekly basis by cross verifying stock.

For simplicity we assume that Any customer requests rentals of only one type i.e daily or weekly and is free to choose the number of bikes he/she wants. Requested bikes should be less than available stock.

Step 1

Create a parent class BikeRental. Define stock as class attribute and assign value 100 to it.

This class should not take any other attribute and when the object is created, it should display the message "Welcome to rental bike shop."

Define a method displaystock inside this class and when this method is called, it should display the total number of stock available.


Step 2

Create a derived class Customer to inherit the methods from BikeRental class. Define bill as class attributeand set it's initial value as zero.

This class has number_of_bikes, rentalBasis (daily or weekly) and number_of_days_or_weeks as attributes.


Step 3

Write complete Customer class using above defined functions returnBike and rentBike inside it as methods.


Step 4

Check your Bike Rental System for test-case objects given below :

For first four customers - check all the three attribute values and call rentBike and returnBike methods.


- customer_1 = Customer(2,'day',5)


- customer_2 = Customer(1,'week',3)


- customer_3 = Customer(4,'day',3) - Is family discount applicable here ?


- customer_4 = Customer(3,'week',3) - Is family discount applicable here ?


Call rentBike and displaystock methods for test-case objects given below :


- customer_5 = Customer(120,'week',3)


- customer_6 = Customer(0,'week',3)


- customer_7 = Customer(-5,'week',3)


- customer_8 = Customer(1,'day',3)
