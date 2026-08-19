# Exemplos Práticos de Código

## Exemplo Completo: Classe, Objeto e Execução em Java

No Java, para rodar tudo no mesmo arquivo (`Main.java` ou `Aluno.java`), colocamos a instanciação dentro do método `public static void main`:

```java
// 1. Definição da Classe Aluno
class Aluno {
    private String nome;
    private double nota;

    // Construtor
    public Aluno(String nome, double nota) {
        this.nome = nome;
        this.nota = nota;
    }

    // Método de regra de negócio
    public boolean estaAprovado() {
        return this.nota >= 7.0;
    }

    // Métodos Getters
    public String getNome() {
        return this.nome;
    }

    public double getNota() {
        return this.nota;
    }
}

// 2. Classe Principal que executa o código
public class Main {
    public static void main(String[] args) {
        // Instanciando o objeto aluno1
        Aluno aluno1 = new Aluno("Paulo Daniel", 8.5);

        // Exibindo os dados e chamando métodos do objeto
        System.out.println("Aluno: " + aluno1.getNome());
        System.out.println("Nota: " + aluno1.getNota());
        System.out.println("Aprovado? " + aluno1.estaAprovado());
    }
}
```