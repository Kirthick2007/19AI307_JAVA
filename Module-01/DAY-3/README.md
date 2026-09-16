# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check given number is zero or not.

## ALGORITHM :
1.	Start the program.
2.	Declare an integer variable 'num'
3.	Create a Scanner object 'sc' to read input from the user
4.	Read an integer input from the user and store it in 'num'
5.	Check if 'num' is equal to 0:
a.	If true, print "Given number is Zero"
b.	If false, print 'num' followed by " is Non-Zero"
6.	End





## PROGRAM:
 ```

Program to implement a class & objects using Java
Developed by: Kirthick sha R
RegisterNumber:  212224230124

```

## Sourcecode.java:
```java
import java.util.*;

class Demo
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);

        int num = sc.nextInt();

        if (num == 0)
        {
            System.out.print("Given number is Zero");
        }
        else
        {
            System.out.print(num + " is Non-Zero");
        }
    }
}
```






## OUTPUT:
<img width="708" height="182" alt="image" src="https://github.com/user-attachments/assets/9909d714-a9b8-49ca-9ab5-749ebe382066" />

<img width="723" height="241" alt="image" src="https://github.com/user-attachments/assets/f06f6dc9-03de-4016-bd61-b23b8f71192a" />


## RESULT:

Thus, the Java program to check given number is zero or not was created successfully.


