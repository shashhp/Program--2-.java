# Program--2-.java
import java.util.Scanner;

public class OddSeries {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter a value for a: ");
        int a = sc.nextInt();
        for (int i = 1; i <= a; i++) {
            int term = 2 * i - 1;  
            if (i == a) {
                System.out.print(term);       
            } else {
                System.out.print(term + ", ");
            }
        }
        sc.close();
    }
}
