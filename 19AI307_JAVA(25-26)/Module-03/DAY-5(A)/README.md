# Ex.No:3(E) INNER CLASS

## QUESTION:
Write a Java program to create an inner class and access it from the outer class.

## AIM:
To demonstrate accessing an inner class from an outer class in Java.

## ALGORITHM :
Create an outer class with a private variable.
Define an inner class inside it with a method to access the outer variable.
In main(), create an object of the outer class.
Use it to create an object of the inner class.
Call the inner class method.





## PROGRAM:
 ```
/*
Program to implement a InnerClass using Java
Developed by: SHARON CLARA A
RegisterNumber:  212224040310
*/
```

## SOURCE CODE:


```
import java.util.Scanner;

class OuterClass {
    String name;

    OuterClass(String name) {
        this.name = name;
    }

    void display() {
        InnerClass inner = new InnerClass();
        inner.showMessage();
    }

    class InnerClass {
        void showMessage() {
            System.out.println("Hello, " + name + "! This message is from the Inner Class.");
        }
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("");
        String input = scanner.next();
        scanner.close();

        OuterClass outer = new OuterClass(input);
        outer.display();
    }
}




```




## OUTPUT:


<img width="1223" height="347" alt="512459138-3a4a3b07-7cc7-4e68-877e-4bb04d3aab6d" src="https://github.com/user-attachments/assets/70dc9e89-1b82-4732-b3d0-de7fd4eab76d" />


## RESULT:


The program successfully accesses and prints data from the inner class using the outer class.
