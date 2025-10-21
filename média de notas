import java.util.Scanner;

public class CalculoNotas {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        double[] notas = new double[8];
        System.out.println("Digite as 8 notas anuais:");

        for (int i = 0; i < 8; i++) {
            System.out.print("Nota " + (i + 1) + ": ");
            notas[i] = scanner.nextDouble();
        }

        scanner.close();

        // Cálculo da média
        double soma = 0;
        for (int i = 0; i < 8; i++) {
            soma += notas[i];
        }
        double media = soma / 8;

        // Exibir a média
        System.out.printf("A média das notas é: %.2f%n", media);
    }
}
