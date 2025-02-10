# Projeto de Posto de Combustível em Java

## Descrição

Este projeto é uma aplicação em Java que simula o funcionamento de um posto de combustível. Utiliza conceitos de Programação Orientada a Objetos (POO) para modelar diferentes tipos de veículos (Carro, Caminhão e Moto) e um funcionário que atende os clientes.

## Estrutura do Projeto

### Classes

- **Veiculo (Classe Mãe)**
  - Atributos:
    - `String marca`
    - `String tipoVeiculo`
    - `String tipoCombustivel`
    - `int capacTanque`
    - `int kmAtual`
    - `int kmUltimaTroc`
    - `int qtdLitrosComb`
    - `String tipoOleo`
  - Métodos:
    - Construtor
    - Métodos getters e setters
    - `abastecer()`
    - `cadastrar()`

- **Carro (Classe Filha)**
  - Atributos:
    - `String qtdCv`
  - Métodos:
    - Construtor
    - Métodos getters e setters

- **Caminhao (Classe Filha)**
  - Atributos:
    - `String tipoCarga`
    - `String injecao`
  - Métodos:
    - Construtor
    - Métodos getters e setters

- **Moto (Classe Filha)**
  - Atributos:
    - `String qtdCilindrada`
    - `String tipoCarburador`
  - Métodos:
    - Construtor
    - Métodos getters e setters

- **Funcionario**
  - Atributos:
    - `String nome`
    - `int idFunc`
    - `float valHora`
    - `int horasTrab`
  - Métodos:
    - Construtor
    - Métodos getters e setters
    - `calcularSalario(int horasTrab, double valHora)`
    - `calcularSalario(double bonus)`

### Diagrama de Classes

O diagrama de classes do projeto pode ser encontrado no arquivo `Diagrama de Classe POO.pdf`, que ilustra a relação entre as classes e seus atributos/métodos.

## Como Executar o Projeto

1. **Pré-requisitos**
   - Java JDK instalado (versão 8 ou superior)
   - IDE de sua preferência (Eclipse, IntelliJ, etc.)

2. **Compilação e Execução**
   - Clone o repositório ou baixe os arquivos do projeto.
   - Abra a IDE e importe o projeto.
   - Compile e execute a classe `Principal`.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

## Autor

Silvio Henrique Mendes dos Santos  
