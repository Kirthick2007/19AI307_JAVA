# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To create a java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace.

## ALGORITHM :
1.	Start the Program
2.	Import `Scanner` and `StringTokenizer` and define class `tok`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Initialize the string `str` as "My name is Java Programming"
4.	Create a `StringTokenizer` object `token` to tokenize `str`
5.	Use a `while` loop to iterate through tokens:
-	a) Print each token using `token.nextToken()`
6.	End




## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
Developed by: kirthick sha R
RegisterNumber:  212224230124
*/
```

## Sourcecode.java:
```java
import java.util.Scanner;
import java.util.StringTokenizer;

class tok
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);

        String str = "My name is Java Programming";

        StringTokenizer token = new StringTokenizer(str);

        while (token.hasMoreTokens())
        {
            System.out.println(token.nextToken());
        }

        sc.close();
    }
}
```

## OUTPUT:
<img width="777" height="255" alt="image" src="https://github.com/user-attachments/assets/e568dfbc-b2e1-40d8-bc21-b1916a3dfb97" />



## RESULT:
Thus the java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace was executed successfully.



