# temperature-conversion-
#temperature conversion tool that allow users to convert temperature from fahrenheit to celsius and vice versa.
import java.util.Scanner;
class FahrenheittoCelsius
{
	public static void main(String args[])	
	{
             	    Scanner sc=new Scanner(System.in);	   	 
	    System.out.println("Enter  Fahrenheit temperature");
                    double a=sc.nextDouble(); 
	    System.out.println("Celsius temperature is = "+celsius(a));		  	  	     
	} 
	static double celsius(double f)
	{	
	return  (f-32)*5/9;
	}
}
