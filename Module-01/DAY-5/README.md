## Ex.No:1(E)  STATIC VARIABLE
```
1.Start
2.Declare a class Student.
3.Declare static variable age and string variable name.
4.Initialize name using the constructor.
5.Set Student.age = 20.
6.Create student1 with name Aswin.
7.Create student2 with name Arun.
8.Create student3 with name Karthik.
9.Display details of student1.
10.Display details of student2.
11.Display details of student3.
Stop.
```


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

