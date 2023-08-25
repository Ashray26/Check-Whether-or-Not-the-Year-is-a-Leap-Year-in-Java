//Check Whether or Not the Year is a Leap Year in Java
import java.util.*;
public class Main
{
  public static void main (String args[])
  {
    Scanner sc = new Scanner (System.in);
      System.out.println ("Enter the Year");
    int year = sc.nextInt ();

    if (year % 4 == 0 && year % 100 !=0)
      {
      System.out.println (year + " The year is leap");
          
      }
    else
      {
	System.out.println (year + "   The year is not leap year");
      }
  }
}

