import java.util.Scanner;

public class calculadora {

public static void main(String[] args){

     Scanner teclado = new Scanner(System.in);
     
     int numero; 
     
     double x, y;
     
     
     System.out.println("Insira o valore de X ");
     
     x = teclado.nextDouble();

     System.out.println("Insira o valore de y ");
     
     y = teclado.nextDouble();
     
     System.out.println("a soma dos produtos da: ");
     
     System.out.println("a subtrção dos produtos da: ");
     
     System.out.println("a divição dos produtos da: ");
     
     System.out.println("a multiplicação dos produtos da: ");
     
    }
     public static double soma (double x , double y){
         
         double soma;
         
         soma = (x + y);
         
         return soma;
         
        }
        
        public static double subtracao (double x , double y){
         
         double subtracao;
         
         subtracao = (x - y);
         
         return subtracao;
         
        }
        
        public static double divisao (double x , double y){
         
         double divisao;
         
         divisao = (x / y);

         return divisao;
         
        }
        
        public static double multiplicacao (double x , double y){
         
         double multiplicacao;
         
         multiplicacao = (x * y);
         
         return multiplicacao;
         
        }
        
    }
