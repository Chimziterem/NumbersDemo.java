# NumbersDemo.java

public class NumbersDemo {
    public static void main (String args[]) {
        int num1= 1;
        int num2= 2;

   //Calling method displayTwiceTheNumber()

   displayTwiceTheNumber(num1);

   displayTwiceTheNumber(num2);

   //Calling method displayNumberPlusFive()

   displayNumberPlusFive(num1);

   displayNumberPlusFive(num2);

   //Calling method displayNumberSquared()

   displayNumberSquared(num1);

   displayNumberSquared(num2);
   }

   public static void displayTwiceTheNumber(int num1){

       System.out.println(num1*2);
   }

   public static void displayNumberPlusFive(int num1){

       System.out.println(num1+5);
   }

   public static void displayNumberSquared(int num1){

       System.out.println(num1*num1);

   } 
}
    
