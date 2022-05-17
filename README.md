# Given-Number-is-Even-or-odd
import java.io.*;
import java.util.*;
public class Z{
  public static void main(String Arguments[]){
    Scanner input = new Scanner(System.in);
    int N= input.nextInt();
    if(N%2!=0){
      System.out.println("The Given Number is odd");
    }else{
      System.out.println("The Given Number is Even");
    }
  }
}
