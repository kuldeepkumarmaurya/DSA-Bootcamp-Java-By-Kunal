# [Video Link](https://youtu.be/TAtrPoaJ7gc)



## Write Java programs for the following:

1. Write a program to print whether a number is even or odd, also take
input from the user.
2. Take name as input and print a greeting message for that particular name.
3. Write a program to input principal, time, and rate (P, T, R) from the user and
find Simple Interest.
4. Take in two numbers and an operator (+, -, *, /) and calculate the value.
(Use if conditions)

import java.util.Scanner;
public class question_4 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter Number 1 : ");
        float num1 = sc.nextInt();
        System.out.print("Enter Number 2 : ");
        float num2 = sc.nextInt();
        System.out.println(" Select Your Option");
        System.out.println( " 1 = + ");
        System.out.println( " 2 = - ");
        System.out.println( " 3 = * ");
        System.out.println( " 4 = / ");
        int option = sc.nextInt();
        if(option == 1 ){
            System.out.println( num1 + " + " + num2 + " = " + (num2+num1));
        }
        else if(option == 2 ){
            System.out.println( num1 + " - " + num2 + " = " + (num1-num2));
        }
        else if(option == 3 ){
            System.out.println( num1 + " * " + num2 + " = " + (num2*num1));
        }
        if(option == 4 ){
            System.out.println( num1 + " / " + num2 + " = " + (num1/num2));
        }
    }
}

6. Take 2 numbers as input and print the largest number.
7. Input currency in rupees and output in USD.
8. To calculate Fibonacci Series up to n numbers.
9. To find out whether the given String is Palindrome or not.
10. To find Armstrong Number between two given number.

