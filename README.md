# Hello World Java Project

A simple Java application that prints "Hello, World!" to the console.

## Project Structure

```
src/
└── main/
    └── java/
        └── com/
            └── example/
                └── HelloWorld.java
pom.xml
README.md
```

## Prerequisites

- Java 11 or higher
- Maven 3.6 or higher

## How to Run

### Using Maven

1. Compile the project:

   ```bash
   mvn compile
   ```

2. Run the application:
   ```bash
   mvn exec:java
   ```

### Using Java directly

1. Compile the Java file:

   ```bash
   javac -d target/classes src/main/java/com/example/HelloWorld.java
   ```

2. Run the compiled class:
   ```bash
   java -cp target/classes com.example.HelloWorld
   ```

## Expected Output

```
Hello, World!
Welcome to your Java project!
```

## Building a JAR file

To create a JAR file:

```bash
mvn package
```

This will create a JAR file in the `target/` directory.
