# Pa33word_Please
Authentication using Java 

import java.util.Scanner;

public class Password_Gene-Test
{
  public static void main(String[] args)
  {
    Scanner sc = new Scanner(System.in);
    
    System.out.println("Enter your username");
    String username = sc.nextString();
    System.out.println("Enter your password");
    String pa33word = sc.nextString();
    
    System.out.println("Enter the password once more");
    String pa33word1 = sc.nextString();
    
    do
    {
      if(pa33word.equals(pa33word1))
          System.out.println("Correct! You may continue");
      
      else if
          System.out.println("Incorrect. Try again.");
    }
    while(!pa33word.equals(pa33word1));
    
    //I feel like this definitely need some renovation
