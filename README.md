- Faça um Programa que peça as 4 notas bimestrais e mostre a média.

import java.util.Scanner;

class Main {
  public static void main(String[] args) {
Scanner console = new Scanner(System.in);

   
  
    int nota1 = 30;
    System.out.println("primeira nota  : " + nota1  );

    int nota2 = 20;
    System.out.println(" segunda nota: " + nota2  );

    int nota3 = 30;
    System.out.println(" terceira nota : " + nota3  );

    int nota4 = 20;
    System.out.println(" quarta nota : " + nota4  );

    int media = (nota1 + nota2 + nota3 + nota4);
    System.out.println(" media bimestral: " + media / 4  );
