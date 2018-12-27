# Nto1
import java.util.Scanner;

public class P02_Nto1 {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        int n =Integer.parseInt(scanner.nextLine());

        for (int i = 1; n >= i ; n--) {
            System.out.println(n);
        }

    }

}
