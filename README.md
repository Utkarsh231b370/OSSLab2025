# OSSLab2025

Name: Utkarsh Sharma  
Roll Number: 231B370  
Email: utkarshsharma@juetguna.in  

<Solution code to part F>

1. Greatest of two number java : 

import java.util.Scanner;

public class GreatestOfTwo {  
    public static void main(String[] args) {  
        Scanner scanner = new Scanner(System.in);  

        System.out.print("Enter the first number: ");
        int num1 = scanner.nextInt();
        System.out.print("Enter the second number: ");
        int num2 = scanner.nextInt();

        if (num1 > num2) {
            System.out.println("The greatest number is: " + num1);
        } else if (num2 > num1) {
            System.out.println("The greatest number is: " + num2);
        } else {
            System.out.println("Both numbers are equal.");
        }

        scanner.close();
    }
}


2. Sum of two number python :

num1 = float(input("Enter the first number: "))  
num2 = float(input("Enter the second number: "))  

sum = num1 + num2

print("The sum of", num1, "and", num2, "is:", sum)