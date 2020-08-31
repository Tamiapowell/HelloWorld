package com.company;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
	//
       Scanner input = new Scanner(System.in);
       System.out.println("Hi, Who are you?");
       String n = input.nextLine();

        System.out.println("Hello, " + n + " Nice to meet you." );
System.out.println("how long have you been at howard?");
int y = input.nextInt();
System.out.println(); // talk about how long its been
System.out.println("What is your GPA?");
float g = input.nextFloat();
// talk about GPA
    }
}
