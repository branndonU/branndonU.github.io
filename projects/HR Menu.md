---
layout: project
type: project
image: img/IMG_8797.jpg
title: "HR Menu"
date: 2023-03-23
published: true
labels:
  - ICS 211
  - Java
summary: "In my spring 2023 semester, I had to make a User Menu for an HR Employee Database."
---

**Code 1: EmployeeManager**
This Java program represents a command-line application for managing an HR employee database. It provides a user menu for performing various actions related to employee information, including adding and removing employees, printing employees with specific salary criteria, and printing all employees.

**Code 2: Employee**
The `Employee` class models an employee object with attributes such as employee number, salary, and name. It includes mutator and accessor methods for setting and getting these attributes, with validation checks to ensure valid inputs. The class also defines a `toString` method to provide a formatted representation of the employee's details.

**Code 3: EmployeeException**
The `EmployeeException` class defines a custom exception that can be thrown in the `Employee` class. This exception is designed to handle errors related to invalid employee input. It includes methods to set and get a custom error message associated with the exception, allowing for informative error messages to be displayed when validation conditions are not met.

**Overall Purpose:**
1. **EmployeeManager (`Code 1`):**
   This program serves as a user interface for managing employee records. Users can add, remove, and retrieve employee information based on specific criteria. It interacts with the `Employee` class to create and manage employee objects.

2. **Employee (`Code 2`):**
   This class defines the structure and behavior of an individual employee. It ensures that valid inputs are used for employee attributes and provides a way to represent employee details in a formatted manner.

3. **EmployeeException (`Code 3`):**
   This class defines a custom exception to handle errors in the employee program. It allows for more informative error messages to be generated and displayed when there's an issue with employee input.

Together, these three codes create a system for managing employee data with input validation and custom exception handling. It provides an essential foundation for handling employee records within an HR context.


