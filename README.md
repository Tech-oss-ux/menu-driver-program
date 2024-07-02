# menu-driver-program
import java.util.Scanner;

public class loops {
    public static void main(String[] args) {
      Scanner s = new Scanner(System.in);
      System.out.println("do you wish to start (1--yes, 0--no)");
      int n = s.nextInt();
      do {
        System.out.println("please enter your marks");
        int x = s.nextInt();
        if (x >= 90) {
            System.out.println("this is good");  
        }else if (x>=60 && x<=89) {
        System.out.println("this is also good");
        }else if (x>=0 && x<=59){
            System.out.println("this is good as well");
        }else {
            System.out.println("INVALID INPUT");
        }
System.out.println("MARKS DONT MATTER YOUR EFFORT DOES");
System.out.println("do you wish to continue");
n = s.nextInt();

      }while(n == 1);

    }
}
