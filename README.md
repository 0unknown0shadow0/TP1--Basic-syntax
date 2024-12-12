

# Java Basics with Examples

This program demonstrates the fundamental concepts of Java, including variables, operators, conditional statements, and more. It also includes practical examples for string manipulation, math operations, and flow control.

## Table of Contents
- [Variables](#variables)
- [Operators](#operators)
- [String Manipulation](#string-manipulation)
- [Math Operations](#math-operations)
- [Flow Control](#flow-control)
- [Notes on String Functions](#notes-on-string-functions)

---

## Variables

Variables in Java are used to store data. Examples of variable types:

```java
String samy = "samyyyyy";
int number = 12;
boolean V = true;
float nn = 4.545457F;
double allll = 4.524545645554;
char c = 'g';
```

---

## Operators

Operators perform operations on variables. Examples:

- **Arithmetic Operators**: `+`, `-`, `*`, `/`, `%`
- **Assignment Operators**: `=`, `+=`, `-=`, `*=`, `/=`
- **Comparison Operators**: `==`, `!=`, `<`, `>`, `<=`, `>=`
- **Logical Operators**: `&&` (AND), `||` (OR)

### Example:
```java
int x = 5;
int y = 3;
int z = 2;

z += y; // z = z + y
z -= x; // z = z - x
z *= x; // z = z * x
z /= x; // z = z / x
```

---

## String Manipulation

Java provides various methods to work with strings.

### Examples:
```java
String text = "    AIN CHOK    ";
System.out.println(text.indexOf("C")); // Find the index of a character
System.out.println(text.replace("AIN", "FOUARATE")); // Replace text
System.out.println(text.concat(" EXTRA TEXT")); // Concatenate strings
System.out.println(text.trim()); // Remove whitespace from start and end
System.out.println(text.length()); // Get the length of the string
```

### Escaping Characters:
```java
String sentence = "Hello, I am from \"Beni Mellal\" and I love it.\t";
System.out.println(sentence);
```

---

## Math Operations

Perform mathematical calculations using the `Math` library.

### Examples:
```java
int squareRoot = (int) Math.sqrt(9); // Square root
int power = (int) Math.pow(4, 2); // Power
System.out.println(squareRoot);
System.out.println(power);
```

---

## Flow Control

Flow control allows decision-making and loops.

### `if-else` Example:
```java
String user = "samy";

if (user.equals("laila")) {
    System.out.println("Welcome: " + user);
} else {
    System.out.println("User not valid");
}
```

### `switch-case` Example:
```java
System.out.println("Choose an option: \n 1: Recharge \n 2: Check Bill \n 3: Help");
Scanner sc = new Scanner(System.in);

switch (sc.nextInt()) {
    case 1:
        System.out.println("Enter a 14-digit recharge code.");
        break;
    case 2:
        System.out.println("Your bill is 99 DH.");
        break;
    case 3:
        System.out.println("Help section.");
        break;
    default:
        System.out.println("Invalid option.");
        break;
}
```

---

## Notes on String Functions

Here are some commonly used string functions and what they do:

| **Function**          | **Description**                              | **Example**                                                   |
|------------------------|----------------------------------------------|---------------------------------------------------------------|
| `indexOf()`           | Returns the index of a character or substring | `"hello".indexOf('e')` → `1`                                 |
| `replace()`           | Replaces occurrences of a substring          | `"hello".replace('e', 'a')` → `"hallo"`                      |
| `concat()`            | Concatenates strings                         | `"hello".concat(" world")` → `"hello world"`                 |
| `trim()`              | Removes whitespace from the start and end    | `"  hello  ".trim()` → `"hello"`                             |
| `length()`            | Returns the length of the string             | `"hello".length()` → `5`                                     |
| `toUpperCase()`       | Converts to uppercase                        | `"hello".toUpperCase()` → `"HELLO"`                          |
| `toLowerCase()`       | Converts to lowercase                        | `"HELLO".toLowerCase()` → `"hello"`                          |
| `substring()`         | Extracts a portion of the string             | `"hello".substring(1, 4)` → `"ell"`                          |
| `equals()`            | Compares two strings for equality            | `"hello".equals("HELLO")` → `false`                          |

---

### Have fun coding! 😊
```
