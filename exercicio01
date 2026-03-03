import java.util.Scanner;

public class exercicio01 {
    public static void main(String[] args) {

        int rm[] = new int[30];
        double nota1[] = new double[30];
        double nota2[] = new double[30];

        Scanner le = new Scanner(System.in);

        int n=0;
        System.out.print("Informe RM (negativo para encerrar): ");
        int rmLido = le.nextInt();
        for (n=0; n<30 && rmLido>0; n++){
            rm[n] =rmLido;
            System.out.print("Nota 1: ");
            nota1[n] = le.nextDouble();
            System.out.print("Nota 2: ");
            nota2[n] = le.nextDouble();
            System.out.print("Informe RM (negativo para encerrar): ");
            rmLido = le.nextInt();

        }
        // Calcular Média
        double media[] = new double[30];
        for (int i =0; i<n; i++){
            media[i] = (nota1[i]+nota2[i])/2;
            System.out.println("RM: "+ rm[i]+"\t media: "+ media[i]);
        }

        // Alunos aprovados
        int aprovados[] = new int[n];
        int nAp=0;
        for (int i=0; i<n; i++){
            if (media[i]>=6){
                aprovados[nAp] = rm[i];
                nAp++;
            }
        }
        // Saida dos alunos aprovados
        System.out.println("\n **** Lista dos Aprovados");
        for (int i=0; i<nAp; i++){
            System.out.println(aprovados[i]);
        }
    }
}
