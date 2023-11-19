# Exception-Handling

**Objective**

In this project we will learn to **handle and manage** errors or exceptional conditions that can occur during the execution of a program. 

**Concepts**

| Concept   |      Resources      |
|----------|:-------------:|
|Concept of Exception Handling |  [What is an Exception Handling](https://github.com/nourabyte/Exception-Handling/blob/main/resource/What-is-exception-handling.md) |
|Tutorial for Exception Handling    |    [Exception Handling Using try catch](https://www.youtube.com/watch?v=osEjmECD8bI)  |


**Problem**

Using the provided project, find the exception that cause the program to fail and handl it.

**Implementation**

Before starting, you must `resolve` [project one](https://github.com/nourabyte/Package-Project/blob/main/README.md) and use it to add exception handling concept.

1. resolve duplicate id numbers and non-existent students using exception handling.

```Java

public class Main {
    public static void main(String[] args) {
        StudentManagementSystem sms = new StudentManagementSystem();
        /* Adding students */
        Student student1 = new Student("Khaled", 1, 20, 85.5);
        sms.addStudent(student1);

        Student student2 = new Student("Rema", 2, 21, 92.3);
        sms.addStudent(student2);

        Student student3 = new Student("Noura", 3, 19, 78.9);
        sms.addStudent(student3);
         }
}
```

