import java.util.Scanner;
class HelloWorld {
    public static void main(String[] args) {
        Scanner teclado = new Scanner (System.in);
        System.out.println("Escribe una palabra: ");
       String texto = teclado .nextLine();
       if("hola".equals(texto)){
           System.out.print("Hola Mundo");
       } else {
           System.out.print("El mejor");
       }
        
        teclado.close();
        }
    }
