
import java.util.Scanner;

public class zerodois {
    public static void main(String[] args) {
        Integer n1_re, n2 ,mnr=0;
        Scanner Ler = new Scanner(System.in);
            System.out.println("Informe a quantidade de repetições: ");
            n1_re = Ler.nextInt();
        for (int i = 0; i < n1_re; ++i) {
            while (true){
                System.out.println("Informe o número: ");
            while (true)
            try {
                n2 = Ler.nextInt();
                if (n2 > 0) {
                    System.out.println("O número " + n2 + " é positivo");
                    break;
                }
                if (n2 < 0) {
                    System.out.println("O número " + n2 + " é negativo.");
                    break;
                }
                if (n2 == 0) {
                    System.out.println("Você digitou zero.");
                    break;
                }


            } catch (Exception e) {
                System.out.println("Caracter invalided");
            }
        }
    }
    }
}
