import java.util.Scanner;

public class calculadora {

public static void main(String[] args){

     Scanner teclado = new Scanner(System.in);
     
     int numero; 
     
     double x, y;
     
     
     System.out.print("insira um numero de 1 a 4" );
     
     numero = teclado.nextInt();
     
     System.out.println("Insira o valore de X ");
     
     x = teclado.nextDouble();

     System.out.println("Insira o valore de y ");
     
     y = teclado.nextDouble();
     
     switch (numero){

         case 1:
         
             System.out.println ("A soma dos valores da " + soma (x, y));
             
             break;
            
       
        case 2:
        
             System.out.println ("A subtração dos valores da " + subtracao(x, y));
             
             break;
            
         
        case 3:
        
             System.out.println ("A multiplicação dos valores da " + multiplicacao (x, y));
             
             break;
            
         
         case 4:
         
             System.out.println ("A divisão dos valores da " +divisao (x,y));
             
             break;
            
             
        default:
        
                 System.out.println (" esse numero esta invalido");
                 
                 break;
        
     }
     
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
