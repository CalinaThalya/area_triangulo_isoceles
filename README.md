java
import java.util.Scanner;

public class AreaTrianguloIsosceles {
   public static void main(String[] args) {
      double base, altura, area;

      Scanner sc = new Scanner(System.in);

      System.out.println("Digite a base do triângulo isósceles: ");
      base = sc.nextDouble();

      System.out.println("Digite a altura do triângulo isósceles: ");
      altura = sc.nextDouble();

      area = (base * altura) / 2;

      System.out.println("A área do triângulo isósceles é " + area);

      sc.close();
   }
}
