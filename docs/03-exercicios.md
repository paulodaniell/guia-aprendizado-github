# 03. Exercícios Práticos

## Exercício 1: Modelando uma Conta Bancária (Encapsulamento)
Crie uma classe `ContaBancaria` com:
- Atributos privados: `titular`, `saldo`, `numeroConta`.
- Métodos públicos: `depositar(valor)`, `sacar(valor)` e `consultarSaldo()`.
- Regra: Não permitir saques com valor superior ao saldo disponível.

## Exercício 2: Veículos e Hierarquia (Herança e Polimorfismo)
1. Crie uma classe abstrata/base `Veiculo` com método `mover()`.
2. Crie as classes filhas `Carro` e `Bicicleta`.
3. Sobrescreva o método `mover()` em cada classe filha exibindo uma mensagem personalizada.