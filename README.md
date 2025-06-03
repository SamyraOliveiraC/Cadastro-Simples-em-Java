import java.util.Scanner;

public class CadastroBasico {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Dados do usuário
        String nome;
        int idade;
        String email;

        System.out.println(" Sistema de Cadastro");

        // Coleta dos dados
        System.out.print("Digite seu nome: ");
        nome = scanner.nextLine();

        System.out.print("Digite sua idade: ");
        idade = scanner.nextInt();
        scanner.nextLine(); // limpar o buffer

        System.out.print("Digite seu email: ");
        email = scanner.nextLine();

        // Exibindo os dados cadastrados
        System.out.println("Dados Cadastrados");
        System.out.println("Nome: " + nome);
        System.out.println("Idade: " + idade);
        System.out.println("Email: " + email);

        scanner.close();
    }
}
