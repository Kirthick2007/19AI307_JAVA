# Ex.No:3(A)  STRING AND ITS OPERATIONS IN JAVA
## AIM:
To create a java program to read input and print length of the string in java.

## ALGORITHM :
1.  Start the Program.
2.	Import `Scanner` and define class `demo`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read a line of text into `String` variable `str`
4.	Print "The size of the String is " + `str.length()`
5.	End




## PROGRAM:
 ```
Program to implement a String and its Operations using Java
Developed by: Kirthick sha R
RegisterNumber:  212224230124
```

## Sourcecode.java:

```java
import java.util.Scanner;

class demo
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);

        String str = sc.nextLine();

        System.out.println("The size of the String is " + str.length());

        sc.close();
    }
}
```





## OUTPUT:
<img width="686" height="193" alt="image" src="https://github.com/user-attachments/assets/eee3e1af-8d6c-4e33-8c69-e420e328fe95" />



## RESULT:
Thus the java Program to read input and print length of the string in java was executed successfully.

