# Comprehensive Design of Data Structure

## Array-Based Stack and Hash Table

This repository contains my programming assignment for the
**Comprehensive Design of Data Structure** course at **Southwest
University of Science and Technology (SWUST)**. The project demonstrates
two fundamental data structures implemented in Java.

## Project Contents

-   **`ArrayStack.java`** --- Implements a stack using an array and
    follows the Last In, First Out (LIFO) principle.
-   **`HashTable.java`** --- Implements a hash table with a custom hash
    function and separate chaining to handle collisions.
-   **`Main.java`** --- Provides an interactive menu for trying the
    stack and hash table operations.
-   **`TestDataStructures.java`** --- Runs tests for normal operations
    and edge cases, including stack overflow/underflow and hash-table
    collisions.
-   **`README.md`** --- Project overview and instructions.

## Key Concepts

### 1. Array-Based Stack

A stack follows **LIFO (Last In, First Out)**: the last item added is
the first item removed.

Typical operations: - `push` --- add an item to the top. - `pop` ---
remove and return the top item. - `peek` --- view the top item without
removing it.

### 2. Hash Table

A hash table uses a hash function to map keys to buckets, allowing
efficient insertion, lookup, and removal. This implementation uses
**separate chaining** to manage collisions.

Typical operations: - `put` --- insert a key-value pair or update an
existing key. - `get` --- retrieve the value associated with a key. -
`contains` --- check whether a key exists. - `remove` --- delete a
key-value pair.

## Requirements

-   Java Development Kit (JDK)
-   A terminal or Java IDE, such as IntelliJ IDEA

No external libraries are required.

## Compile and Run

Compile the application:

``` bash
javac ArrayStack.java HashTable.java Main.java
```

Run it:

``` bash
java Main
```

## Run the Tests

Compile the test program:

``` bash
javac ArrayStack.java HashTable.java TestDataStructures.java
```

Run the tests:

``` bash
java TestDataStructures
```

The test program reports the results of its checks and finishes with a
completion message when the tests have run.

## Time and Space Complexity

  -----------------------------------------------------------------------
  Data Structure          Operation               Time Complexity
  ----------------------- ----------------------- -----------------------
  Array-Based Stack       `push`, `pop`, `peek`   O(1)

  Array-Based Stack       Display items           O(n)

  Hash Table              `put`, `get`,           Average O(1),
                          `contains`, `remove`    worst-case O(n)
  -----------------------------------------------------------------------

For the stack, space usage is **O(C)**, where `C` is its capacity. For
the hash table, space usage is **O(C + n)**, where `C` is the number of
buckets and `n` is the number of stored entries.

## Learning Objectives

-   Understand how arrays can be used to implement a stack.
-   Apply the LIFO principle through stack operations.
-   Understand hashing and collision handling.
-   Test data structures using normal and invalid input cases.
-   Compare the time and space complexity of common operations.
  ## 🚀 Access the Project

**Download the complete project:** [Array-Based Stack and Hash Table]([Stack_HashTable_Assignment_Updated.zip](https://github.com/user-attachments/files/34059450/Stack_HashTable_Assignment_Updated.zip)


Download the ZIP file, extract it, and open the project in IntelliJ IDEA to explore and run the Java implementations.

## Author

**Mir Maryam Naveed**

Course: **Comprehensive Design of Data Structure**\
University: **Southwest University of Science and Technology (SWUST)**
