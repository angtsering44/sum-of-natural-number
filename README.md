# sum-of-natural-number
import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        int loop, i,sum=0;
        System.out.println("Enter the number:");

        Scanner input = new Scanner(System.in);
        loop = input.nextInt();

        for (i = 1; i <= loop; i++) {
            sum=sum+i;
           
        }
 System.out.println("Your number is");
    }
}
