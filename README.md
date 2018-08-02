// Write a program that prompts
//the user to enter a, b, c, d, e, and f and displays the result. If ad - bc is 0, report
//that “The equation has no solution.”

# Extra_Ex3_3
package com.personal.Extra3;

import java.util.Scanner;

public class Extra3_3 {

	public static void main(String[] args) {
		Scanner sc= new Scanner(System.in);
		System.out.println("Enter a, b, c, d, e,f");
		Double a,b,c,d,e,f,X,Y;
		a= sc.nextDouble();;
		b= sc.nextDouble();
		c= sc.nextDouble();
		d= sc.nextDouble();
		e= sc.nextDouble();
		f= sc.nextDouble();
		X=0.0;
		Y=0.0;
		if ( (a*d )-(b*c)== 0)
			System.out.println("The equation has no solution");
		else {
			X= ((e*d)-( b*f )) / ((a*d)- (b*c));
			Y= ((a*f)-( e*c )) / ((a*d)- (b*c));
		}
			System.out.println("X is : " + X + "Y is : "+ Y);

				}	

}
