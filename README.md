# ExercicioCondiciona2
# exercício do curso JAVA COMPLETO da Udemy 
# Objetivo do programa: identificar se o número inserido pelo usuário é par ou ímpar 

	package exercicioCond2;
	import java.util.Scanner;
	public class ExercicioCondicional2 {

		public static void main(String[] args) {
			// TODO Auto-generated method stub
			
			Scanner sc = new Scanner(System.in);
			int numero;
			System.out.println("Digite um numero: ");
			numero = sc.nextInt();
			
			if (numero % 2 == 0) {
				System.out.println("PAR !");
			}
			else {
				System.out.println("IMPAR");
			}
			
			
			sc.close();
			
		}

}

