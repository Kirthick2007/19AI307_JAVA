# Ex.No:1(A) CLASS & OBJECTS

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'address' and initialize it with the value "Chennai"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'address' variables of the 'obj' object
9.	End



## PROGRAM:
 ```
Program to implement a class & objects using Java
Developed by: Kirthick sha R
RegisterNumber:  212224230124
```

## Sourcecode.java:
```java
public class Test {
    public static void main(String[] args) {
        Student obj = new Student();

        System.out.println(obj.name);
        System.out.println(obj.address);
    }
}

class Student {
    String name = "name";
    String address = "address";
}
```






## OUTPUT:

<img width="670" height="221" alt="image" src="https://github.com/user-attachments/assets/2925c1ba-cc87-4c90-a5ab-e6323471373f" />



## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
