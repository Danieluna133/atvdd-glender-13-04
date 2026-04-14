# atvdd-glender-13-04

import java.util.Scanner;
public static void main(String[] args) {
                Scanner entrada = new Scanner(System.in);
        System.out.print("Digite o número de linhas n: ");
        int n = entrada.nextInt();

        System.out.print("Digite o número de colunas m: ");
        int m = entrada.nextInt();

        int[][] matriz = new int[n][m];

       
        System.out.println("Digite os elementos da matriz:");
        for (int i = 0; i < n; i++) {
            for (int j = 0; j < m; j++) {
                matriz[i][j] = entrada.nextInt();
            }
        }
        System.out.println("\nMatriz original:");
        for (int i = 0; i < n; i++) {
            for (int j = 0; j < m; j++) {
                System.out.print(matriz[i][j] + " ");
            }
            System.out.println();
        }

       
        System.out.println("\nMatriz transposta:");
        for (int j = 0; j < m; j++) {
            for (int i = 0; i < n; i++) {
                System.out.print(matriz[i][j] + " ");
            }
            System.out.println();
        }
    }
    
}
