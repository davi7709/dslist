# Lista de Jogos em Java

Este é um projeto simples em Java que lista jogos de vídeo game, feito no intensivo de Java Spring do Professor Nelio Alves. Ele permite que o usuário visualize uma lista de jogos, veja detalhes de cada jogo e reposicione o jogo na lista.

## Funcionalidades

- Exibir uma lista de jogos com nome, gênero e ano de lançamento.
- Exibir detalhes de cada jogo.
- Reposiciona o jogo na lista

### Observação

Não possui Front-end

## Pré-requisitos

Antes de rodar o projeto, você precisa ter o [Java 8+](https://www.oracle.com/java/technologies/javase-downloads.html) instalado em sua máquina.

### Como rodar o projeto

1. Clone o repositório para sua máquina:
    ```bash
    git clone https://github.com/davi7709/dslist
    ```

2. Compile o código:
    ```bash
    javac Main.java
    ```

3. Execute o projeto:
    ```bash
    java Main
    ```

## Estrutura do Projeto

- **Main.java**: Contém a lógica principal de execução do programa, onde o menu de opções é exibido e o usuário interage com o sistema.
- **Game.java**: Classe que representa um jogo, com atributos como nome, gênero e ano de lançamento.
- **GameList.java**: Classe que gerencia a lista de jogos, permitindo adicionar, remover e listar jogos.
- **GameDTO.java: Classe que faz o transporte dos dados.

## Modelo de Domínio
![image](https://github.com/user-attachments/assets/6b8cd95b-a1a9-4cca-a9c6-110e1f3edba0)




