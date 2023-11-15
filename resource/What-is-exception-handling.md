## What is Exception Handling

> unexpected event that occurs while executing the program, that disturbs the normal flow of the code.

### Concept

`Exception handling` is a mechanism in programming languages that allows developers to **handle and manage errors or exceptional conditions** 
that can occur during the execution of a program. When an exceptional situation arises, such as an error or unexpected behavior, an exception is thrown, 
indicating that something has gone wrong.

### Example

* Exception handling using try-catch
```java
 class Main {
  public static void main(String[] args) {
    try {
      // code that generate exception
      int divideByZero = 5 / 0;
      System.out.println("Rest of code in try block");
    }
    catch (ArithmeticException e) {
      System.out.println("ArithmeticException => " + e.getMessage());
    }
  }
}
```
