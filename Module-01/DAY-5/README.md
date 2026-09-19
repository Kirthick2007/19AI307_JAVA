# Ex.No:1(E)  STATIC VARIABLE
Start
Declare a class named Student.
Declare a static variable age and a normal String variable name.
Create a constructor Student(String name) to initialize the student's name.
Create a method displayDetails() to display:
Student's name
Student's age
In the main() method, set the static variable Student.age = 20.
Create three student objects:
student1 with name Aswin
student2 with name Arun
student3 with name Karthik
Call displayDetails() for each student object.
Display the name and common age (20) for all three students.
Stop.



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

