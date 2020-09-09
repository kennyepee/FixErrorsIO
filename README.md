# FixErrorsIO
package com.company;
import java.util.Scanner;
public class Debug {

    public static void main(String[] args)
        {
        Scanner input = new Scanner(System.in);
        String name;
        System.out.print("Input your name: ");
        name = input.nextLine();
        System.out.print("Enter your age: ");
        int age = Integer.parseInt(input.nextLine());
        System.out.print("Enter your DOB year: ");
        int dob = Integer.parseInt(input.nextLine());
        System.out.println("Summary: "+"Your name is: "+name+"\n"+"Your age is: "+age+"\n"+"Your birth year is: "+dob);
    }
}

