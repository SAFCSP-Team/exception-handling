# Exception-Handling

**Objectives**

This project learn to handle and manage errors or exceptional conditions that can occur during the execution of a program. 

**Concepts**

| Concept   |      Resources      |
|----------|:-------------:|
|Concept of Exception Handling |  [What is an Exception Handling](https://github.com/nourabyte/Exception-Handling/blob/main/resource/What-is-exception-handling.md) |
|Tutorial for Exception Handling    |    [Exception Handling Using try catch](https://www.youtube.com/watch?v=osEjmECD8bI)  |


**Problem**

Include error handling to handle cases such as duplicate id numbers or non-existent students.



**Implementation**

Before start, you should resolve [project one](https://github.com/nourabyte/Package-Project/blob/main/README.md) to complete exception hadling concept in your program.




1. Create a package to organize your classes.
2. Create `Student` class within the package, with attributes like name, id number, age, and grade. Include 
   appropriate getters and setters.
3. Create "StudentManagementSystem" class, which serves as the main entry point for the system.
4. Implement methods to add and remove a student.
6. Implement a method to calculate the average grade of all the students in the system.


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

