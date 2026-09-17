# Ex.No:2(B) ACCESS MODIFIERS
3.	Declare two private integer variables, `num1` and `num2`
4.	Define a private method `add()` that:
a)	Returns the sum of `num1` and `num2`
5.	Define a public method `display(int n1, int n2)` that:
a)	Assigns `n1` to `num1` and `n2` to `num2`
b)	Calls the `add()` method and prints the result using `System.out.println`
6.	Define the `main` method as static
a)	Create an instance of the `addition` class called `ad`
b)	Call the `display(8, 9)` method on the `ad` object
7.	End






## PROGRAM:
 ```
/*
Program to implement a access modifiers using Java
Developed by: Kirthick sha R
RegisterNumber:  212224230124
*/
```

## Sourcecode.java:

```java
class addition
{
    private int num1;
    private int num2;

    private int add()
    {
        return num1 + num2;
    }

    public void display(int n1, int n2)
    {
        num1 = n1;
        num2 = n2;

        System.out.println("Addition = " + add());
    }

    public static void main(String args[])
    {
        addition ad = new addition();

        ad.display(8, 9);
    }
}
```





## OUTPUT:
![Image](https://github.com/aswin0603/19AI307_JAVA/blob/main/Module-02/DAY-2/Screenshot%202026-08-25%20195501.png)


## RESULT:
Thus the java program to display the addition number using private modifiers only was executed successfully.


