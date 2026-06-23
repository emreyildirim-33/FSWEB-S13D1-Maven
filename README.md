# Java Control Flow Methods

A Java project focused on control flow, conditional statements, boolean logic, method design, method overloading, input validation, and basic mathematical calculations.

The project includes several beginner-friendly Java method challenges that demonstrate how to use conditions, return values, parameter validation, and overloaded methods.

## Overview

This project demonstrates core Java control flow concepts through small, focused method implementations.

The main goal is to practice writing clean Java methods that evaluate conditions, validate inputs, handle edge cases, and return correct results based on different scenarios.

The project includes challenges such as:

* Dog barking wake-up logic
* Teen age detection
* Cat playing temperature logic
* Rectangle area calculation
* Circle area calculation with method overloading

## Tech Stack

* Java
* Maven
* Control flow
* Conditional statements
* Boolean logic
* Method overloading
* Mathematical calculations
* Input validation

## Core Concepts

* `if` / `else` statements
* Boolean conditions
* Method return values
* Parameter validation
* Edge case handling
* Method overloading
* Basic arithmetic operations
* `Math.PI` usage
* Clean method-based problem solving

## Challenge 1: Barking Dog

The `shouldWakeUp()` method determines whether a person should wake up based on whether a dog is barking and the current hour.

Method:

```java
shouldWakeUp(boolean barking, int hourOfDay)
```

Rules:

* Returns `true` if the dog is barking between 20:00 and 08:00
* Returns `false` if the dog is not barking
* Returns `false` if the hour is invalid
* Valid hour range is `0` to `23`

Example behavior:

```java
shouldWakeUp(true, 1);   // true
shouldWakeUp(false, 2);  // false
shouldWakeUp(true, 8);   // false
shouldWakeUp(true, -1);  // false
```

## Challenge 2: Teen Number Checker

The `hasTeen()` method checks whether at least one of three given ages is between 13 and 19.

Method:

```java
hasTeen(int firstAge, int secondAge, int thirdAge)
```

Rules:

* Returns `true` if any parameter is between `13` and `19`
* Returns `false` if none of the parameters are teen ages

Example behavior:

```java
hasTeen(9, 99, 19);   // true
hasTeen(23, 15, 42);  // true
hasTeen(22, 23, 34);  // false
```

## Challenge 3: Playing Cat

The `isCatPlaying()` method checks whether a cat is playing based on the temperature and whether it is summer.

Method:

```java
isCatPlaying(boolean summer, int temperature)
```

Rules:

* If it is not summer, the cat plays between `25` and `35` degrees
* If it is summer, the upper limit becomes `45` degrees
* Returns `true` only if the temperature is inside the valid range

Example behavior:

```java
isCatPlaying(true, 10);   // false
isCatPlaying(false, 36);  // false
isCatPlaying(false, 35);  // true
```

## Challenge 4: Area Calculator

The `area()` method is overloaded to calculate both rectangle area and circle area.

### Rectangle Area

Method:

```java
area(double width, double height)
```

Rules:

* Returns `width * height`
* Returns `-1` if width or height is negative

Example behavior:

```java
area(5.0, 4.0);   // 20.0
area(-1.0, 4.0);  // -1
```

### Circle Area

Method:

```java
area(double radius)
```

Rules:

* Returns `radius * radius * Math.PI`
* Returns `-1` if radius is negative

Example behavior:

```java
area(5.0);  // 78.53981633974483
area(-1);   // -1
```

## Features

* Dog barking time validation
* Teen age range checking
* Temperature-based condition checking
* Rectangle area calculation
* Circle area calculation
* Method overloading practice
* Invalid input handling
* Boolean return logic
* Clean and simple Java method structure
* Pure Java problem-solving examples

## Project Structure

```text
src/
 └── main/
     └── java/
         └── org/example/
             ├── Main.java
             └── ...
```

## What This Project Demonstrates

* Writing conditional logic in Java
* Returning boolean results from methods
* Validating method parameters
* Handling invalid values safely
* Using method overloading for related calculations
* Applying mathematical formulas in Java
* Solving small algorithmic problems with clean methods
* Building strong Java control flow fundamentals

## Getting Started

### Prerequisites

Make sure you have the following installed:

* Java 17+
* Maven
* IntelliJ IDEA or another Java IDE

### Installation

Clone the repository:

```bash
git clone https://github.com/emreyildirim-33/Java-Control-Flow-Methods.git
cd Java-Control-Flow-Methods
```

Run the project from your IDE or with Maven:

```bash
mvn test
```

## Notes

This project focuses on Java control flow, conditional statements, boolean logic, method overloading, input validation, and basic mathematical calculations.

The main purpose is to demonstrate how small Java methods can solve focused logic problems with clear conditions and predictable return values.

## Repository

GitHub: https://github.com/emreyildirim-33/Java-Control-Flow-Methods
