# SWITCH-CASE
import java.util.Scanner;
public class SWITCHCASE {

        public static void main(String[] args) {
        Scanner ac=new Scanner(System.in);
        int number;
        System.out.println("enter a number");
        number=ac.nextInt();
        switch (number){
            case 29:
                System.out.println("the size is small");
                break;
            case 42:
                System.out.println("the size is medium");
                break;
            case 44:
                System.out.println("the size is large");
                break;
            case 48:
                System.out.println("the size is extra large");
                break;
            default:
                System.out.println("the size is unknown");
                break;
        }
    }
    
}


