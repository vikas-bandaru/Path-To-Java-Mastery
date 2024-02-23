# Java Operators and Expressions

This document provides an overview of operators and expressions in Java, which are fundamental to creating algorithms and logic in your programs.

## Introduction

  In Java, an **expression** is a construct made up of variables, operators, and method invocations, which are constructed according to the syntax of the language, that evaluates to a single value. Operators are special symbols that perform specific operations on one, two, or three operands, and then return a result.

  Operators in Java are categorized into several types:

1. Arithmetic Operators
2. Relational Operators
3. Logical Operators
4. Assignment Operators
5. Unary Operators
6. Bitwise Operators
7. Ternary Operator

## 1. Arithmetic Operators

  Arithmetic operators are used in mathematical expressions in the same way that they are used in algebra.

- Addition (`+`)
  ```java
  int result = 10 + 5; // 15
  ```
- Subtraction (`-`)
  ```java
  int result = 10 - 5; // 5
  ```
- Multiplication (`*`)
  ```java
  int result = 10 * 5; // 50
  ```
- Division (`/`)
  ```java
  int result = 10 / 5; // 2
  ```
- Modulus (`%`)
  ```java
  int result = 10 % 5; // 0
  ```

## 2. Relational Operators

  Relational operators are used to compare two values.

- Equal to (`==`)
  ```java
  boolean result = (5 == 5); // true
  ```
- Not Equal to (`!=`)
  ```java
  boolean result = (5 != 5); // false
  ```
- Greater Than (`>`)
  ```java
  boolean result = (10 > 5); // true
  ```
- Less Than (`<`)
  ```java
  boolean result = (10 < 5); // false
  ```
- Greater Than or Equal to (`>=`)
  ```java
  boolean result = (10 >= 5); // true
  ```
- Less Than or Equal to (`<=`)
  ```java
  boolean result = (10 <= 5); // false
  ```

## 3. Logical Operators

  Logical operators are used to combine multiple boolean expressions or values.

- Logical AND (`&&`)
  ```java
  boolean result = (5 > 3) && (8 > 5); // true
  ```
- Logical OR (`||`)
  ```java
  boolean result = (5 < 3) || (8 > 5); // true
  ```
- Logical NOT (`!`)
  ```java
  boolean result = !(5 > 3); // false
  ```

## 4. Assignment Operators

  Assignment operators are used to assign values to variables.

- Simple Assignment (`=`)
  ```java
  int x = 5;
  ```
- Add AND Assign (`+=`)
  ```java
  x += 5; // Equivalent to x = x + 5;
  ```
- Subtract AND Assign (`-=`)
  ```java
  x -= 5; // Equivalent to x = x - 5;
  ```
- Multiply AND Assign (`*=`)
  ```java
  x *= 5; // Equivalent to x = x * 5;
  ```
- Divide AND Assign (`/=`)
  ```java
  x /= 5; // Equivalent to x = x / 5;
  ```
- Modulus AND Assign (`%=`)
  ```java
  x %= 5; // Equivalent to x = x % 5;
  ```

## 5. Unary Operators

  Unary operators require only one operand. They perform various operations such as incrementing/decrementing a value by one, negating an expression, or inverting the value of a boolean.
  
- Increment (`++`)
  ```java
  int x = 5;
  x++; // x now equals 6
  ```
- Decrement (`--`)
  ```java
  int x = 5;
  x--; // x now equals 4
  ```
- Unary Plus (`+`) (Indicates positive value, not necessary to use explicitly)
  ```java
  int x = +5; // x equals 5
  ```
- Unary Minus (`-`) (Negates an expression)
  ```java
  int x = -5; // x equals -5
  ```
- Logical Complement (`!`) (Inverts the value of a boolean)
  ```java
  boolean y = !true; // y equals false
  ```

## 6. Bitwise Operators

  Bitwise operators are used to perform manipulation of individual bits of a number. They can be applied to the integer types: long, int, short, char, and byte.

- Bitwise AND (`&`)
  ```java
  int result = 12 & 5; // 4
  ```
- Bitwise OR (`|`)
  ```java
  int result = 12 | 5; // 13
  ```
- Bitwise XOR (`^`)
  ```java
  int result = 12 ^ 5; // 9
  ```
- Bitwise Complement (`~`)
  ```java
  int result = ~12; // -13
  ```

## 7. Ternary Operator

  The ternary operator is a shortcut for the if-then-else statement and is used to assign one of two values to a variable based on a given condition.

```java
int result = (10 > 5) ? 1 : 0; // result is assigned 1
```

**Note:** Understanding and using Java operators is crucial for programming logic and algorithms in Java. Operators allow you to perform different kinds of operations on variables and values, enabling complex decision-making and calculation in your programs.