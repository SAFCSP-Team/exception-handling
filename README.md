# Exception Handling

**Objective**

In this project, we will learn to **handle and manage** errors or exceptional conditions that can occur during the execution of a program. 

**Concepts**

| Concept   |      Resources      |
|----------|:-------------:|
| What is an Exception Handling | [Exception Handling Concept](https://github.com/nourabyte/Exception-Handling/blob/main/resource/What-is-exception-handling.md) |
| Exception Handling Using try catch | [Exception Handling (Tutorial)](https://www.youtube.com/watch?v=osEjmECD8bI)  |
|Exception Handling, ArrayIndexOutOfBoundsException|[ArrayIndexOutOfBoundsException](https://www.youtube.com/watch?v=YXHu5YLKCUM)|


**Problem**

Using the provided code snippet, find the issue in the program and handle it.

**Implementation**

The main class contain an error, handle it using try and catch to resolve it.

```Java

public class Main {
    public static void main(String[] args) {

    int[] myNumbers = {1, 2, 3};
    System.out.println(myNumbers[10]);

  }
}

```

