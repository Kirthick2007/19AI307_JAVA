# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a Java program that creates a StringBuilder object using a given string and assigns its reference to the variable sb.

## ALGORITHM :
1.	Start the program.
2.	Declare and initialize a string variable str1.
3.	Create a StringBuilder object by passing str1 to its constructor.
4.	Store the object reference in the variable sb.
5.	Print the contents of sb to verify the output.
6.	End the program.


## PROGRAM:
 ```
Program to implement a StringBuilder Object Reference in Java
Developed by: kirthick sha R
RegisterNumber: 212224230124
```

## Sourcecode.java:
```java
class StringBuilderExample
{
    public static void main(String args[])
    {
        String str1 = "Hello Java";

        StringBuilder sb = new StringBuilder(str1);

        System.out.println("StringBuilder contents: " + sb);
    }
}
```






## OUTPUT:
<img width="707" height="175" alt="image" src="https://github.com/user-attachments/assets/2f08b4cc-23a3-4d13-9ecb-dc7466931f6a" />



## RESULT:
Thus the  Java program successfully creates a StringBuilder object using the given string and stores the reference in the variable sb. The contents of the object are printed using the reference variable.

