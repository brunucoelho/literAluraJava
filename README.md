# Challenger LiterAlura

<p align="center" style="display:flex>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=java,maven,spring,postgresql" />
  </a>
</p>


## Índice

- [Resumo](#resumo)
- [Setup](#setup)
- [Como Usar](#como-usar)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Acesso ao Projeto](#acesso-ao-projeto)


## Resumo

<p align="justify">
LiterAlura é parte do desafio da Alura, para a formação JAVA, o programa oferece uma interface de console, permitindo aos usuários explorar e interagir com um catálogo de livros de diversas formas. As informações dos livros são obtidas por meio da API Gutendex, assegurando que os dados estejam sempre atualizados.
</p>

## Setup

1. Certifique-se de ter o Java 17 instalado. Você pode obtê-lo em [java.com](https://www.java.com/pt-BR/download/).
2. Garanta que o Maven esteja instalado. Faça o download em [maven.apache.org](https://maven.apache.org/download.cgi).
3. Clone este repositório:

    ```bash
    git clone https://github.com/brunucoelho/literAluraJava.git
    ```

4. Entre no diretório do projeto:

    ```bash
    cd literAluraJava
    ```

5. Configure o PostgreSQL:

   - Crie um banco de dados chamado `literAluraJava`.
   - Atualize as credenciais do banco no arquivo `src/main/resources/application.properties`.

6. Compile e execute o projeto com Maven:

    ```bash
    mvn spring-boot:run
    ```

## Como Usar

1. Abra o projeto em sua IDE Java preferida ou use o terminal conforme instruções acima.
2. Execute a aplicação.
3. Siga as instruções no console para interagir com o catálogo de livros.

## Funcionalidades

LiterAlura oferece as seguintes funcionalidades:

1. **Buscar livro por título**: Pesquise um livro específico pelo título.
2. **Listar livros registrados**: Veja uma lista de todos os livros no catálogo.
3. **Listar Autores**: Veja uma lista de todos os autores no catálogo.
4. **Listar Autores vivos em determinado ano**: Encontre autores que estavam vivos em um ano específico.
5. **Listar Livros em determinado Idioma**: Veja uma lista de livros disponíveis em um idioma específico.
6. **Exibir a quantidade de livros em um determinado idioma**: Mostra a quantidade de livros disponíveis em um idioma específico.
7. **Exibir as Estatísticas de Downloads dos Livros**: Mostra estatísticas de downloads, incluindo soma, média, máximo, mínimo e contagem.


## Acesso ao Projeto

Você pode acessar o projeto no GitHub [aqui](https://github.com/brunucoelho/literalurajava).

## Como Contribuir

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.



<p align="center">
  <img src="https://logos-world.net/wp-content/uploads/2020/09/Oracle-Logo.png" alt="Oracle" height="50" style="display:flex">
  <img src="https://www.alura.com.br/assets/img/alura-logo.svg" alt="Alura" height="50">
</p>

---

Desenvolvido por [Bruno Coelho](https://github.com/brunucoelho).