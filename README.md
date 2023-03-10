# First-calculater-
package mypackage;

import java.util.Scanner;

public class Calculater {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("Welcome....!!!!");
       Scanner input=new Scanner(System.in);
        System.out.print("Enter the 1st Number:");
        double x=input.nextDouble();
        System.out.print("Enter the 2nd Number:");
        double y=input.nextDouble();
        int ch=input.nextInt();
         switch(ch) {
         case 1:
        	 double result=x+y;
        	 System.out.print("Addition of two number:"+result);
        	 break;
         
         case 2:
        	double result2=x-y;
        	System.out.print("Substraction of two number is:"+result2);
        	break;
         case 3:
        	 double result3= x*y;
        	 System.out.print("multiplication of two number is:"+result3);
        	 break;
         case 4:
        	 double result4=x/y;
        	 System.out.print("Division of two number is:"+result4);
        	 break;
         case 5:
        	 double result5=x%y;
        	 System.out.print("Modulo of two number is:"+result5);
        	break;
        	default:
        		System.out.println("Invaild input");


}
}
}
        
