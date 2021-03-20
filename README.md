# import java.util.Scanner;

import jdk.javadoc.internal.doclets.toolkit.resources.doclets_zh_CN;

class Box{
        int a;
        int b;
        int c;
        Box()
        {
           System.out.println("This is coonstructor calling");
        }
       void volume(int a, int b,int c)
       {
         
          int d=a*b*c;
          System.out.println("The Multiplication  is:"+d);
       }
  }
  
  
  
  class firstJavaProgramx
{
  public static void main(String arg[])
  {
         Scanner sc=new Scanner(System.in);
           System.out.println("This is main function calling");
           
           System.out.println("Enter first number:");
           int x=sc.nextInt();
           System.out.println("Enter second number:");
           int y=sc.nextInt();
           System.out.print("Enter third number:");
           int z=sc.nextInt();
           Box b=new Box();
           b.volume(x,y,z);


  }

}
