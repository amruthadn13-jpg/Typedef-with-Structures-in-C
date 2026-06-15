# Typedef with Structures in C

## Overview

This project demonstrates how the **`typedef` keyword** can be used with structures in C to simplify structure declarations and improve code readability.

Without `typedef`, the `struct` keyword must be used every time a structure variable is declared. Using `typedef` creates a custom type name that makes the code shorter and cleaner.

---

## Concepts Covered

- Structures (`struct`)
- `typedef` keyword
- Structure aliases
- Structure initialization
- Code readability and maintainability
- Formatted output using `printf()`

---

## Project Description

The program demonstrates two ways of creating structure variables:

### Without Typedef

```c
struct Car {
    char brand[30];
    int year;
};
```

Variable declaration:

```c
struct Car car1 = {"BMW", 1999};
```

The `struct` keyword is required every time a variable is declared.

### With Typedef

```c
typedef struct {
    char brand[30];
    int year;
} Car;
```

Variable declaration:

```c
Car car2 = {"Ford", 1969};
```

The `struct` keyword is no longer needed, making the code more concise.

---

## Sample Output

```text
BMW 1999
Ford 1969
```

---

## Learning Outcomes

- Understanding the use of `typedef` with structures
- Creating custom type names
- Simplifying structure declarations
- Writing cleaner and more maintainable code

---

## Structure Comparison

### Without Typedef

```c
struct Car car1;
```

### With Typedef

```c
Car car2;
```

The typedef version is shorter and easier to read.

---

## Real-World Applications

- Embedded Systems Development
- Device Driver Programming
- Operating Systems
- Networking Applications
- Automotive Software
- Large-Scale C Projects

Typedef is widely used in professional software development to improve code readability and reduce complexity.

---

## Time Complexity

```text
O(1)
```

Structure initialization and access take constant time.

---

## Space Complexity

```text
O(1)
```

A fixed amount of memory is allocated for the structure variables.

---

## Key Takeaway

Using `typedef` with structures eliminates the need to repeatedly write the `struct` keyword, resulting in cleaner, more readable, and professional C code.

---

## Author

**Amrutha D N**
