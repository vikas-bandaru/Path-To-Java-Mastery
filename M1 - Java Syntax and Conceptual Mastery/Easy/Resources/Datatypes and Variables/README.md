# Study Material: Java Fundamentals

## Topic: Java Data Types, Variables, Assignment, Print, and Naming Conventions

### Purpose
The purpose of this section is to provide a foundational understanding of Java's data types, variable declaration and assignment, output operations, and standard naming conventions. Mastering these basics is essential for writing clear and efficient Java code.

### Data Types
In Java, there are two main data type categories: primitive and reference.

- **Primitive Data Types**: These include `int`, `double`, `float`, `boolean`, `char`, etc., which store simple values.
- **Reference Data Types**: These include `String`, arrays, and objects that store references to the actual data.

### Syntax

- **Variables Declaration and Initialization**

  ```java
  int age = 30;                 // integer
  double salary = 4500.50;      // floating-point number
  boolean isEmployed = true;    // boolean value
  char grade = 'A';             // character
  String name = "John Doe";     // string of characters
  ```

- **Printing to Console**

  ```java
  System.out.println(age);      // Prints the value of age variable
  System.out.println("Hello, " + name);  // Concatenates and prints a string with the value of name variable
  ```

- **Naming Conventions**

  - Use camelCase for variable and method names.
  - Use PascalCase for class and interface names.
  - Be descriptive and use full words for clarity.

### Examples

- **Variable Assignment and Printing**

  ```java
  int numberOfWheels = 4;
  String vehicleType = "Car";
  System.out.println("The " + vehicleType + " has " + numberOfWheels + " wheels.");
  ```

- **Printing to Console**

  ```java
  System.out.println(age);      // Prints the value of age variable
  System.out.println("Hello, " + name);  // Concatenates and prints a string with the value of name variable
  ```
  Output:
  ```
  The Car has 4 wheels.
  ```

### Exercises

1. **Declare and Initialize**
  Declare and initialize variables for each of the following data types: `int`, `double`, `boolean`, and `String`. Then, print each variable to the console.

  ```java
  int population = 1000000;
  double temperature = 36.5;
  boolean isRaining = false;
  String cityName = "Metropolis";
  ```

2. **Printing Variables**
  Using the variables from the previous exercise, write a program that prints a sentence incorporating all the variables, like so:

  ```java
  System.out.println("The city of " + cityName + " has a population of " + population + ". The current temperature is " + temperature + " degrees Celsius. Is it raining? " + isRaining);
  ```
  Output:
  ```
  The Car has 4 wheels.
  ```

3. **Naming Practice**
  Create variable names using the appropriate naming conventions for the following descriptions:

  - Number of students in a class.
  - The title of a book.
  - Whether a door is open or not.
  - The speed of a vehicle.

  ```java
  int numberOfStudents; // Number of students in a class
  String bookTitle;     // Title of a book
  boolean isDoorOpen;   // Whether a door is open or not
  double vehicleSpeed;  // Speed of a vehicle
  ```

4. **Type Conversion**
  Write a program where you need to convert a `float` to an `int` and concatenate a number with a `String`.
  ```java
  float productPrice = 19.99f;
  int price = (int) productPrice;
  String message = "The price is: " + price;
  System.out.println(message);
  ```

**Note:** These exercises are designed to reinforce the concepts outlined in the study material. Ensure you test your code as you go to see the output and understand how Java works with different data types and variables.