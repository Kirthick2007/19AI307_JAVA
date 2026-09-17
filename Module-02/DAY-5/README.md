# Ex.No:2(E)  SMALLEST ELEMENT IN AN ARRAY

## AIM:
To write a Java program that reads an array size and elements from the user and then finds and prints the smallest element in the array.
## ALGORITHM :
1.	Start the program.
2.	Read the size of the array from the user.
3.	Declare an array of the given size.
4.	Read the array elements from the user.
5.	Initialize a variable min with the first element of the array.
6.	Traverse the array using a loop.
7.	Compare each element with min. If an element is smaller, update min.
8.	After the loop ends, print the smallest number.
9.	End the program.
	

## PROGRAM:
 ```
Program to implement a Smallest Element in an Array
Developed by: Kirthick sha R
RegisterNumber:  212224230124
```

## Sourcecode.java:
```java
import java.util.Scanner;

class Smallest
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);

        int size = sc.nextInt();

        int arr[] = new int[size];

        for (int i = 0; i < size; i++)
        {
            arr[i] = sc.nextInt();
        }

        int min = arr[0];

        for (int i = 1; i < size; i++)
        {
            if (arr[i] < min)
            {
                min = arr[i];
            }
        }

        System.out.println("Smallest element = " + min);

        sc.close();
    }
}
```






## OUTPUT:

<img width="756" height="307" alt="image" src="https://github.com/user-attachments/assets/a45a1ec4-a284-4d0a-b92b-a732cda68680" />



## RESULT:
Thus the java program successfully reads the array size and elements from the user and correctly finds and prints the smallest number in the array.
