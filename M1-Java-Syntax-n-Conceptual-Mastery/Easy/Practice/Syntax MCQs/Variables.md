# Java Data Types and Variables MCQs

### 1. Which of the following is a valid declaration of a char in Java?
A) `char ch = 'ab';`  
B) `char ch = '\uabcd';`  
C) `char ch = 65;`  
D) `char ch = "a";`

<details>
<summary>Answer</summary>

B) `char ch = '\uabcd';`  
C) `char ch = 65;`  
</details>

### 2. What is the default value of a local variable of type int?
A) `null`  
B) `0`  
C) Not assigned  
D) `undefined`

<details>
<summary>Answer</summary>

C) Not assigned
</details>

### 3. Which of the following variable naming conventions is recommended in Java?
A) `int 1stNumber;`  
B) `int _firstNumber;`  
C) `int $firstNumber;`  
D) `int firstNumber;`

<details>
<summary>Answer</summary>

D) `int firstNumber;`
</details>

### 4. How do you correctly cast a double to an int in Java?
A) `int i = (double)d;`  
B) `int i = (int)d;`  
C) `double i = (int)d;`  
D) `int i = double(d);`

<details>
<summary>Answer</summary>

B) `int i = (int)d;`
</details>

### 5. Which of these is the correct way to declare and initialize an array in Java?
A) `int arr[] = new int[5] {1,2,3,4,5};`  
B) `int arr[] = {1,2,3,4,5};`  
C) `int arr[] = new int[] {1,2,3,4,5};`  
D) Both B and C are correct.

<details>
<summary>Answer</summary>

D) Both B and C are correct.
</details>

### 6. What will be the output of the following Java code snippet?
```java
System.out.println(1 + 2 + "3");
A) 6
B) 123
C) 33
D) 123
```
<details>
<summary>Answer</summary>
C) 33

</details>

### 7. Which operator is used for concatenation of two strings in Java?
A) `+`  
B) `-`  
C) `&`  
D) `||`

<details>
<summary>Answer</summary>

A) `+`
</details>

### 8. What does the following Java code snippet print?
```java
int x = 10;
double y = 20.2;
System.out.println(x + y);
A) 30.2
B) 30
C) Compilation Error
D) 1020.2
```
<details>
<summary>Answer</summary>
A) 30.2

</details>

### 9. Which keyword is used to declare constants in Java?
```java
A) constant
B) final
C) const
D) static
```
<details>
<summary>Answer</summary>
B) final

</details>

### 10. What is the result of the following code snippet?
```java
byte a = 40, b = 50;
byte sum = (byte) (a + b);
System.out.println(sum);
A) 90
B) Compilation Error
C) Runtime Exception
D) None of the above
```
<details>
<summary>Answer</summary>
A) 90

</details>

### 11. Which of these data types can store a value of true or false?
```java
A) int
B) boolean
C) char
D) double
```
<details>
<summary>Answer</summary>
B) boolean

</details>

### 12. In Java, which of the following is a valid float literal?
```java
A) 3.14
B) 3.14f
C) 314e-2
D) All of the above
```
<details>
<summary>Answer</summary>
B) 3.14f

</details>

### 13. How do you print a double quotation mark (") in Java?
```
A) System.out.println(""");
B) System.out.println("\"");
C) System.out.println("""");
D) System.out.println('/"');
```
<details>
<summary>Answer</summary>
B) System.out.println("\"");

</details>

### 14. Which of the following is true about the assignment operator in Java?
```java
A) It can be used to assign values of any type to variables.
B) It can be used to assign objects of one class to another.
C) It returns the assigned value.
D) All of the above
```
<details>
<summary>Answer</summary>
C) It returns the assigned value.

</details>

### 15. What is type casting in Java?
```java
A) Changing the value of a variable.
B) Changing the type of a variable during program execution.
C) Explicitly converting a value from one type to another.
D) Automatically converting a value from one type to another.
```
<details>
<summary>Answer</summary>
C) Explicitly converting a value from one type to another.

</details>

### 16. Which of the following is NOT a primitive data type in Java?
```
A) String
B) byte
C) short
D) float
```
<details>
<summary>Answer</summary>
A) String

</details>

### 17. When declaring multiple variables of the same type in Java, which of the following is correct?
```java
A) int a, b, c = 100;
B) int a = b = c = 100;
C) Both A and B are correct.
D) Neither A nor B is correct.
```
<details>
<summary>Answer</summary>
A) int a, b, c = 100;
Note: This initializes only c to 100, a and b remain uninitialized.

</details>

### 18. What will the following code snippet output?
```java
System.out.println(10 / 3);
A) 3.3333
B) 3
C) 3.3
D) Compilation error
```
<details>
<summary>Answer</summary>
B) 3

</details>

### 19. What is the output of the following code snippet?
```java
char letter = 'A';
letter++;
System.out.println(letter);
A) A
B) B
C) 66
D) Compilation error
```
<details>
<summary>Answer</summary>
B) B

</details>

### 20. Which of the following statements about naming conventions in Java is true?
```java
A) Package names are typically in uppercase.
B) Class names should start with a lowercase letter.
C) Method names should start with a lowercase letter.
D) Constants are typically named in lowercase.
```
<details>
<summary>Answer</summary>
C) Method names should start with a lowercase letter.

</details>

### 21. Which of the following is a valid identifier in Java?
```java
A) int _name;
B) int 1_name;
C) int $name;
D) int #name;
```
<details>
<summary>Answer</summary>

A) `int _name;`  
C) `int $name;`
</details>

### 22. What is the output of the following code snippet?
```java
double d = 100.04;  
long l = (long)d;  
int i = (int)l;  
System.out.println("Double value "+d);  
System.out.println("Long value "+l);  
System.out.println("Int value "+i);

A) Double value 100.04, Long value 100, Int value 100
B) Compilation Error
C) Runtime Exception
D) None of the above
```
<details>
<summary>Answer</summary>
A) Double value 100.04, Long value 100, Int value 100

</details>

### 23. What does the following Java code snippet print?
```java
System.out.println(10 + 20 + "Hello");
System.out.println("Hello" + 10 + 20);

A) 30Hello Hello1020
B) 30Hello Hello30
C) Hello30 1020
D) Hello30
```
<details>
<summary>Answer</summary>
A) 30Hello Hello1020

</details>

### 24. Which keyword in Java is used to create a variable that can store an object of any type?
```
A) var
B) Object
C) def
D) Any
```
<details>
<summary>Answer</summary>
A) var (Introduced in Java 10 for local variable type inference)<br/>
B) Object (Before Java 10)

</details>

### 26. What will be the result of the following code snippet?
```java
System.out.println('J' + 'A' + 'V' + 'A');

A) JAVA
B) Compilation Error
C) The sum of ASCII values of the characters
D) JAVAJAVAJAVA
```
<details>
<summary>Answer</summary>
C) The sum of ASCII values of the characters

</details>

### 27. Which of these is not a legal array declaration in Java?
```java
A) int[] arr;
B) int arr[];
C) int arr[5];
D) int []arr;
```
<details>
<summary>Answer</summary>
C) int arr[5]; (You cannot specify the size when declaring an array variable)

</details>

### 28. In Java, which of these lines will compile without error?
```java
A) byte b = 128;
B) char c = -3;
C) boolean bool = 0;
D) int i = 100L;
```
<details>
<summary>Answer</summary>
D) None of the above options will compile without error.

</details>

### 29. What is the output of the following code snippet?
```java
int var1 = 5;
int var2 = 6;
if ((var2 = 1) == var1)
    System.out.print(var2);
else 
    System.out.print(++var2);

A) 1
B) 2
C) 6
D) 7
```
<details>
<summary>Answer</summary>
B) 2

</details>

### 30. Which of the following is true about the main method in Java?
```
A) It must return a value.
B) It can only throw checked exceptions.
C) It must be declared public and static.
D) It can be declared final.
```
<details>
<summary>Answer</summary>
C) It must be declared public and static.
D) It can be declared final.

</details>

### 31. What will this code print?
```java
int a = 9, b = 2;
float f = a / b;
System.out.println(f);

A) 4.5
B) 4.0
C) 4
D) 0
```
<details>
<summary>Answer</summary>
C) 4

</details>

### 32. Which statement about the final keyword in Java is true?
```
A) A final method can be overridden in a subclass.
B) A final class can be extended.
C) A final variable can be reassigned a new value.
D) A final variable must be initialized when it is declared.
```
<details>
<summary>Answer</summary>
D) A final variable must be initialized when it is declared.

</details>

### 33. Consider the following code snippet. What is the issue?
```java
int[] nums = new int[3];
nums[3] = 5;

A) There is no issue with the code.
B) The array has not been initialized correctly.
C) The index is out of bounds.
D) The assignment to the array is incorrect.
```
<details>
<summary>Answer</summary>
C) The index is out of bounds.

</details>

### 34. What is the result of the following operation?
```java
System.out.println(10 % 3);

A) 1
B) 3
C) 0.333
D) 10
```
<details>
<summary>Answer</summary>
A) 1

</details>