# CalculatorMavenProject

## Description
**CalculatorMavenProject** is a Java-based calculator application built using Maven. The primary goal of this project is to implement and validate unit tests, ensuring the correctness and reliability of the calculator's functionality.

## Features
- Perform basic arithmetic operations: addition, subtraction, multiplication, and division.
- Integration with Maven for project management and build automation.
- Unit testing with JUnit to validate the application's logic.

## Technologies Used
- **Java**: Core programming language for the application.
- **Maven**: Build automation tool for managing dependencies and the project lifecycle.
- **JUnit**: Framework for writing and running unit tests.

## Prerequisites
Before running or building the project, make sure you have the following installed:
- Java Development Kit (JDK) version 8 or higher
- Maven version 3.6 or higher

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/your-username/CalculatorMavenProject.git
cd CalculatorMavenProject
```

### Build project

```bash
mvn clean install
```

### Execute unit tests

```bash
mvn test
```

### Run the Application

```bash
mvn exec:java -Dexec.mainClass="com.example.calculator.Main"
```