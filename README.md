5.
==

Write a method to replace all spaces in a string with ‘%20’.



import java.util.Scanner;

public class Program1 {

  public static void main(String args[]) {
		
		Scanner in = new Scanner(System.in);
		System.out.println("Enter a statement");
		String str = in.nextLine();
		System.out.println("You enterd " + str);

		String replacedString= str.replace(" ", "%20"); 
		
		System.out.println("After replacing space with %20, " + replacedString);

	}
}
