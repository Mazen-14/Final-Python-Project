# Final-Python-Project
Employee Management System
This project is a Employee Management System implemented in Python under supervision of Eng Baraa Abu Sallout. 
It allows you to perform basic CRUD (Create, Read, Update, Delete) operations on employee data stored in a CSV file. 


------------------------------Features------------------------------------
1) Add a new employee with ID, name, position, salary, email.
2) Update any field (name, position, salary, email) for an existing employee with ID.
3) Remove an employee from the csv using their ID.
4) Search for an employee by their ID and display their details.
5) List all employee data.
6) Exit the application.


--------------------------Structure---------------------------------------

1. Employee Class

Represents an employee with :

id (string)

name (string)

position (string)

salary (float)

email (string)

Also :

update_field(): Update a specific field (ID, name, position, salary, email).

display(): Display specific employee details.

2. EmployeeManager Class

Manages the employee records stored in a CSV file.

-It provides ways for:

Read employee data from a CSV file.

Write employee data to a CSV file and save it.

-CRUD Operations:

add_employee()

update_employee()

delete_employee()

search()

list()

Lastly it make sure the salary is a number and is positive.

3. Command-Line Interface (CLI):

A simple menu-driven interface allowing users to interact with the system.

The Menu :

------------------------------------------------------------------------------------------
-----------------------------Welcome to Mazen Project-------------------------------------
------------------------------------------------------------------------------------------

Please choose a number :)
------------------------------------------------------------------------------------------
Add Employee---1

Update Employee---2

Delete Employee---3

Search Employee---4

List All Employees---5

Exit---6

------------------------------------------------------------------------------------------


------------------------------Attatched---------------------------------------------------


1.The ipynnb file contain the code

2.CSV file with some data I tried upon working on the project

------------------------------------------------------------------------------------------
