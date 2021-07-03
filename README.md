# OddPattern
import java.util.Scanner; 
public class Oddpattern
{
    public static void main(String[] args)
    { 
        Scanner sc = new Scanner(System.in);
        System.out.println("How many rows you want in this pattern?");
         
        int n = sc.nextInt();
         
    for (int i= 0; i<= n-1 ; i=i+2)
        {
            for (int j=0; j<=i; j++)
            {
                System.out.print("* ");
            }
            System.out.println("");
        }

    for (int i = n-2; i >= 0; i=i-2) {
      for (int j = 0; j <= i-1; ++j) {
        System.out.print("* ");
      }
      System.out.println();
    }
  }
}
