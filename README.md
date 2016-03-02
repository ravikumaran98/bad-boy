import java.util.Scanner;
public class Number {
 public static void main(String args[])
 {
  Scanner input = new Scanner(System.in);
  int a;
  a = input.nextInt();
  if(a<0){
   System.out.print("a is negative");
   else if(a>0)
    System.out.print("a is positive");
    else
     System.out.print("a is zero");
     }
  }
  }
