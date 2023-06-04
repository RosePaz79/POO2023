Atv02 Exibir a mensagem “Informe um inteiro: “, deixando o cursor na mesma linha e armazenado como inteiro
import java.io.IOException; //importação de classe public class Atv02 {

public static void main(String args[]) throws IOException {
    System.out.print("Pressione um número: "); //solicitação de entrada de dados
    int i = System.in.read();
}

}

Atribuir o produto das variáveis b e c para a variável a

import java.util.Scanner; //importação de classe

public class Atv02{ public static void main(String args[]) {

    Scanner s = new Scanner(System.in);
    int a = 0, b = 2, c 6; //declaração de variáveis com valores

        a = b * c; // equação
        System.out.println(+a); // retorno em tela
   
    s.close();
}

}
Demonstrar a execução do cálculo e utilizar um comentário para afirmar que é um programa de exemplo de folha de pagamento.

import java.util.Scanner; //importação de classe

public class Atv01{ public static void main(String args[]) {

    Scanner s = new Scanner(System.in);
    int a = 0, b, c;

        System.out.print("Digite o valor da diária: ");
        b = s.nextInt();
       System.out.print("Digite número de dias trabalhados: ");
        c = s.nextInt();
        a = b * c;
        System.out.println("O valor a receber pelos dias trabalhados é: " +a); 
   
    s.close();
}

}
