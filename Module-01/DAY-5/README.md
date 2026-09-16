# Ex.No:1(E)  STATIC VARIABLE
5.	Create a constructor to initialize the student's name.
6.	Define a method displayDetails() to print the student's name and age.
7.	In the main method:
I.	Assign a value to the static variable age.
II.	Create multiple Student objects with different names.
III.	Call the displayDetails() method for each student.
8.	End the program.



## PROGRAM:
 ```
Program to implement a Static Variable using Java
Developed by: Kirthick sha R
RegisterNumber:  212224230124
```

## Sourcecode.java:
```java
class Student
{
    static int age;
    String name;

    Student(String name)
    {
        this.name = name;
    }

    void displayDetails()
    {
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
    }

    public static void main(String args[])
    {
        Student.age = 20;

        Student student1 = new Student("Aswin");
        Student student2 = new Student("Arun");
        Student student3 = new Student("Karthik");

        student1.displayDetails();
        student2.displayDetails();
        student3.displayDetails();
    }
}
```






## OUTPUT:
<img width="647" height="276" alt="image" src="https://github.com/user-attachments/assets/54cab95d-3a5d-4f05-8959-3015a3e614d3" />



## RESULT:
Thus, the Java program for the concept of using a static variable for shared data was correctly implemented and verified successfully. 

