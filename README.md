# EXP-1 Java program to print the Arithmetic operations.

## Aim:

To write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers.

## Algorithm:

1.Create the main class and declare the main method so that the program can be identified and start running.

2.In main method decalre two variables with appropriate data type declaration.

3.Perform the basic arithmatic operations (addition,subtraction,multiplication,division).

4.Print the output using "System.outprintln" to see the results.

5.The program completes it's execution and the output will be displayed eventually.

## Program:
``` java
import java.util.Scanner;
public class math_calc
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter first number: ");
        int a = sc.nextInt();
        System.out.print("Enter second number: ");
        int b = sc.nextInt();
        System.out.println("Addition = "+(a+b));
        System.out.println("Subtraction = "+(a-b));
        System.out.println("Multiply = "+(a*b));
        System.out.println("Divide = "+(a/b));
        System.out.println("Reminder = "+(a%b));
    }
}
```
## Output:
![image](https://github.com/VaishnaviMariappan/Arithmeticoperations/assets/94169913/198d36ca-fd15-41aa-bf25-26600761c997)

## Result:

Thus a java program is written to print the sum, multiply, subtract, divide and remainder of two numbers.
