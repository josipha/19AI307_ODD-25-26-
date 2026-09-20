# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:

Define a class Car with brand (String), color (String), and year (int). Create 2 different objects of Car Assign values to attributes. Print the details of both cars.import java.util.Scanner;
## AIM:
To define a class Car with attributes brand, color, and year; create two objects of the class; assign values to their attributes; and print the details of both cars.

## ALGORITHM :
Define a class Car with three data members:

String brand String color int year and a method printDetails() to display these values.

In the main() method, create a Scanner object to read user inputs.

Create the first object car1 and read its brand, color, and year from the user.

Create the second object car2 and read its brand, color, and year.

Call printDetails() for car1 to display its information.

Call printDetails() for car2 to display its information.

Close the scanner and end the program.




## PROGRAM:
 ```
/*
Program to implement a Class and Objects using Java
Developed by: SHARON CLARA A
RegisterNumber:  212224040310
*/
```

## SOURCE CODE:

```

import java.util.Scanner;

class Car {
    String brand;
    String color;
    int year;

    void printDetails() {
        System.out.println("Brand: " + brand);
        System.out.println("Color: " + color);
        System.out.println("Year: " + year);
    }
}

class prog {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        
        Car car1 = new Car();
        car1.brand = scanner.nextLine();
        car1.color = scanner.nextLine();
        car1.year = scanner.nextInt();
        scanner.nextLine();

        
        Car car2 = new Car();
        car2.brand = scanner.nextLine();
        car2.color = scanner.nextLine();
        car2.year = scanner.nextInt();

        car1.printDetails();
        car2.printDetails();

        scanner.close();
    }
}






```






## OUTPUT:

<img width="597" height="685" alt="513801192-05ebe553-f279-4f17-b125-675b4afd47bd" src="https://github.com/user-attachments/assets/ab18a7f4-d585-46d2-8a72-6a325ed57a2b" />



## RESULT:

Therefore,the program successfully creates two Car objects and assigns values to their attributes.
