# one-two
basically in this cod you have to give two no. and the no. which you are given that no. of time the output will print 1 and 2
import java.util.Scanner;

public class onetwo {
    public onetwo() {
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int r = sc.nextInt();
        int c = sc.nextInt();

        for(int i = 1; i <= r; ++i) {
            for(int j = 1; j <= c; ++j) {
                if ((i + j) % 2 == 0) {
                    System.out.print(1);
                } else {
                    System.out.print(2);
                }

                System.out.println();
            }
        }

    }
}
