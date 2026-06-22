FEITO POR: FILIPE ZEGO E HUGO SILVA

SISTEMA DE GESTÃO DE BIBLIOTECA
Projeto desenvolvido em Java utilizando Programação Orientada a Objetos (POO), Java Swing para interface gráfica e ficheiros TXT para persistência de dados.

====================================================

1. DESCRIÇÃO DO PROJETO
====================================================

O Sistema de Gestão de Biblioteca permite administrar livros, utilizadores e empréstimos de forma simples e intuitiva.

O sistema foi desenvolvido com o objetivo de aplicar conceitos de:

* Programação Orientada a Objetos
* Estruturas de Dados
* Interface Gráfica com Java Swing
* Manipulação de Ficheiros
* Pesquisa e Ordenação de Dados

====================================================
2. FUNCIONALIDADES
====================================================

GESTÃO DE LIVROS

* Adicionar livros
* Editar livros
* Remover livros
* Pesquisar livros por ISBN
* Pesquisar livros por título
* Ordenar livros alfabeticamente (A-Z)

GESTÃO DE UTILIZADORES

* Adicionar utilizadores
* Editar utilizadores
* Remover utilizadores
* Pesquisar utilizadores por ID
* Pesquisar utilizadores por nome
* Ordenar utilizadores alfabeticamente (A-Z)

GESTÃO DE EMPRÉSTIMOS

* Registar empréstimos
* Registar devoluções
* Fila de espera para livros indisponíveis
* Histórico de operações

PERSISTÊNCIA DE DADOS

* Guardar livros em livros.txt
* Guardar utilizadores em utilizadores.txt
* Guardar histórico em historico.txt
* Carregamento automático dos dados ao iniciar o sistema

====================================================
3. ESTRUTURA DO PROJETO
====================================================

Biblioteca.java
Classe principal responsável pela lógica do sistema.

Livro.java
Representa os livros da biblioteca.

Utilizador.java
Representa os utilizadores registados.

Emprestimo.java
Representa os empréstimos efetuados.

MainGUI.java
Interface gráfica desenvolvida com Java Swing.

livros.txt
Armazena os livros registados.

utilizadores.txt
Armazena os utilizadores registados.

historico.txt
Armazena o histórico de operações.

====================================================
4. ESTRUTURAS DE DADOS UTILIZADAS
====================================================

LinkedList<Livro>
Armazena os livros da biblioteca.

LinkedList<Utilizador>
Armazena os utilizadores.

LinkedList<Emprestimo>
Armazena os empréstimos ativos.

Queue<Utilizador>
Implementa a fila de espera para livros indisponíveis.

Stack<String>
Armazena o histórico das operações realizadas.

====================================================
5. TECNOLOGIAS UTILIZADAS
====================================================

* Java
* Java Swing
* Programação Orientada a Objetos (POO)
* LinkedList
* Queue
* Stack
* Manipulação de Ficheiros TXT

====================================================
6. COMO EXECUTAR O PROJETO
====================================================

1. Abrir o projeto numa IDE Java
   (NetBeans, IntelliJ IDEA ou Eclipse).

2. Compilar todos os ficheiros .java.

3. Executar a classe:

   MainGUI.java

4. Utilizar a interface gráfica para gerir a biblioteca.

====================================================
7. AUTORES
====================================================

Projeto académico desenvolvido para a disciplina de Programação / Estruturas de Dados.

Universidade do Mindelo
Engenharia Informática e Sistemas Computacionais

====================================================
8. CONCLUSÃO
====================================================

Este projeto demonstra a aplicação prática de conceitos fundamentais de programação, estruturas de dados, persistência de dados e desenvolvimento de interfaces gráficas, permitindo a gestão eficiente de uma biblioteca através de uma aplicação Java completa.
