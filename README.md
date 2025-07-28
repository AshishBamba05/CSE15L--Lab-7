# ListExamples

This project implements two basic Java functions—`filter()` and `merge()`—to manipulate lists of strings. It also includes automated tests using JUnit and a Bash script to compile and run the tests.

## Features

- `filter(List<String> list, StringChecker sc)`:  
  Returns a new list containing only the elements of the input list that satisfy the provided `StringChecker` condition.

- `merge(List<String> list1, List<String> list2)`:  
  Merges two sorted lists of strings into a single sorted list.

- JUnit test suite to validate functionality and edge cases
- Bash script (`test.sh`) to compile and execute tests using JUnit

## Technologies

- Java
- JUnit 4.13.2
- Bash

## How to Run

### 1. Compile the code
```bash
javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
```

### 2. Run JUnit tests
```
java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests
```

