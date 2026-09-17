# Ex.No:2(A)  STATIC METHOD
2.	Declare a variable to store input : Declare an integer variable n to hold the number whose cube will be calculated.
3.	Create a Scanner object : Create a Scanner object (sc) to read the input from the user.
4.	Read input from the user : Prompt the user to input an integer value. The input value is stored in the variable n.
5.	Call the cubecal function : Call the function cubecal(n) which computes the cube of the number by performing n * n * n.
6.	Store the result : Store the result of the cubecal function in an integer variable result.
7.	Output the result :
8.	Print the cube of the number using System.out.println("Cube is: " + result);.
9.	End the program.




## PROGRAM:
 ```
Program to implement a Static method using Java
Developed by: Kirthick sha R
RegisterNumber:  212224230124

```

## Sourcecode.java:
```java
import java.util.*;

class Cube
{
    static int cubecal(int n)
    {
        return n * n * n;
    }

    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);

        int n = sc.nextInt();

        int result = cubecal(n);

        System.out.println("Cube is: " + result);
    }
}
```






## OUTPUT:
<img width="711" height="172" alt="image" src="https://github.com/user-attachments/assets/16ebe860-ba76-418f-8eaa-673f2571cfea" />



## RESULT:
Thus the java program for calculate cube of a number using static method has been executed successfully.

