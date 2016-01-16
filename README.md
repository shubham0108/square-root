import java.lang.Math;
import java.util.Scanner;
class SquareRooy
{
  public static void main(String args[])
  { float num,root;
    Scanner in = new Scanner(System.in);
    System.out.println("Enter a number");
    num=in.nextFloat();
    root=Math.sqrt(num);
    System.out.println("The square root of the number "+num+" is "+root);
  
  }

}
