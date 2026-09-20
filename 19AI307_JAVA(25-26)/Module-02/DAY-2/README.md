# Ex.No:2(B) METHODS

## QUESTION:
Define a class Car with brand (String), color (String), and year (int). Create 2 different objects of Car Assign values to attributes. Print the details of both cars.import java.util.Scanner;

## AIM:

To define a class Car with attributes brand, color, and year; create two objects of the class; assign values to their attributes; and print the details of both cars.

## ALGORITHM :

Define a class demo with two methods:

square(int n) → returns n * n. cube(int n) → returns n * square(n) by calling the square() method internally.

In the main class, read an integer input from the user.

Create an object of the demo class.

Call the cube() method using the object and print the result.

End the program.





## PROGRAM:
 ```
/*
Program to implement a Methods using Java
Developed by: SHARON CLARA A
RegisterNumber:  212224040310
*/
```

## SOURCE CODE:


```

import java.util.*;
class demo
{
    public int square(int n)
    {
        return n*n;
    }
    public int cube(int n)
    {
        return n*square(n);
    }
    
}
public class main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        demo d=new demo();
        System.out.println(d.cube(n));
    }
}



```




## OUTPUT:

<img width="392" height="243" alt="513803438-aa929a40-c871-4a15-8d09-12604778a14b" src="https://github.com/user-attachments/assets/96ad5090-32aa-477d-931f-756931816e20" />



## RESULT:

Therefore the program successfully computes the cube of a number by internally using the square method.
