# 09-14-16class-work
/* Programmer: Collin Palmer
 * Date:09/14/16
 * COSC 111
 * Chapter 3
 */
import java.util.*;
public class class1 
{
     


	public static void main(String[] args)
	{
		 Scanner keyb= new Scanner(System.in);
		 Random r= new Random();
		 int computer=0;
		 int n= 0;
		 
		 computer = r.nextInt(6)+1;
		 
		 System.out.println("Enter your guess from 1-6");
		 n=keyb.nextInt();
		 
		 if (n==computer) 
		 {
			System.out.println("You're right.");
		 }
		 else 
		 {
			System.out.println("You're a loser.");
		 }
		 System.out.println("Enter an integer");
		 n=keyb.nextInt();
		 
		if(n>=0)
		{
			System.out.println(n+" is postive");
		}
		else
		
		{
			System.out.println(n+" is negative");
		}
		
		
		System.out.println("Enter another an integer");
		n=keyb.nextInt();
		
		if (n%2==0) 
		{
			System.out.println(n+" is even");
		}
		else 
		{
			System.out.println(n+" is odd");
		}
		keyb.close();	
	}
}

