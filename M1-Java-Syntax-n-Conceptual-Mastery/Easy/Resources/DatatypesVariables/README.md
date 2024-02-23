# Study Material: Java Fundamentals

## Topic: Java Data Types, Variables, Assignment, Print, Naming Conventions, and Type Conversion

### Purpose
The purpose of this section is to provide a foundational understanding of Java's data types, variable declaration and assignment, output operations, standard naming conventions, and type conversions. Mastering these basics is essential for writing clear and efficient Java code.

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
  Output:
  ```
  The Car has 4 wheels.
  ```

- **Printing to Console**

  ```java
  String name = "Raju";
  int age = 27;
  System.out.println(age);      // Prints the value of age variable
  System.out.println("Hello, " + name + ". Are you " + age + " years old?!");
      // Concatenates and prints a string with the value of name variable
  ```
  Output:
  ```
  Hello, Raju. Are you 27 years old?!
  ```

### Exercises

1. **Declare and Initialize**
   Declare and initialize variables for each of the following data types: `int`, `double`, `boolean`, and `String`.

   <details>
   <summary>Answer</summary>
   <code>
   int population = 1000000;<br>
   double temperature = 36.5;<br>
   boolean isRaining = false;<br>
   String cityName = "Metropolis";
   </code>
   </details>

2. **Printing Variables**
   Using the variables from the previous exercise, write a program that prints a sentence incorporating all the variables, like:

   ```
   The city of Metropolis has a population of 1000000. The current temperature is 36.5 degrees Celsius. Is it raining? false
   ```
   <details>
   <summary>Answer</summary>
   <code>
   System.out.println("The city of " + cityName + " has a population of " + population + ". The current temperature is " + temperature + " degrees Celsius. Is it raining? " + isRaining);
   </code>
   </details>

3. **Naming Practice**
   Create variable names using the appropriate naming conventions for the following descriptions:

   - Number of students in a class.
   - The title of a book.
   - Whether a door is open or not.
   - The speed of a vehicle.

   <details>
   <summary>Answer</summary>
   <code>int numberOfStudents; // Number of students in a class</code><br>
   <code>String bookTitle;     // Title of a book</code><br>
   <code>boolean isDoorOpen;   // Whether a door is open or not</code><br>
   <code>double vehicleSpeed;  // Speed of a vehicle</code><br>
   </details>

4. **Type Conversion**
   Write a program where you need to convert a `float` to an `int` and concatenate a number with a `String`.
   <details>
   <summary>Answer</summary>
   <code>float productPrice = 19.99f;</code><br>
   <code>int price = (int) productPrice;</code><br>
   <code>String message = "The price is: " + price;</code><br>
   <code>System.out.println(message);</code><br><br>
   Output:</code><br>
   <code>The price is: 19</code><br>
   </details>

**Note:** These exercises are designed to reinforce the concepts outlined in the study material. Ensure you test your code as you go to see the output and understand how Java works with different data types and variables.