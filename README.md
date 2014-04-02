BOOLEAN-WITH-FOROKK
===================

BOOLEAN WITH FOR OKKK

//By  Reina Olarte


//	Guessing Number using BOOLEAN with FOR

import java.util.Scanner;


import java.util.Random;

public class BooleanForOK
{
	public static void main( String[]args)
{
//Create the Scanner to input the number
Scanner input = new Scanner(System.in);
//Create the Random number
Random randomNumber = new Random();

for(int i=0; i<3; i++)
{

//Declaring the variables
int UserNumber;
int computerNumber;
computerNumber = 0 + (int)(Math.random() *10);
boolean GameWon = true;
boolean ResultLow = true;
boolean ResultHigh = true;

System.out.println("Welcome to the Guessing game\nPlease enter a digit from 0 to 10:\n");
UserNumber = input.nextInt();


if(GameWon=computerNumber == UserNumber)
{
	System.out.println("You Guessed the right number\n");
	System.out.printf("Your number %d, Random number %d\n" , UserNumber, computerNumber);
}
else if (ResultHigh=computerNumber < UserNumber)
{
	System.out.println("You Guessed to High\n");
	System.out.printf("Your number %d, Random number %d\n" , UserNumber, computerNumber);
}
else if (ResultLow=computerNumber > UserNumber)
{
	System.out.println("You Guessed to Low\n");
	System.out.printf("Your number %d, Random number %d\n" , UserNumber, computerNumber);
}

}	
}//End main

}//End class
