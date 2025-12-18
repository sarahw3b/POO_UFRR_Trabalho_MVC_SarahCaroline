# Trabalho Prático – MVC em Java

Projeto acadêmico desenvolvido em **Java**, no **Apache NetBeans**, com o objetivo de aplicar os conceitos de **Arquitetura de Software** e **Padrões de Projeto**, conforme as aulas 23 e 24 da disciplina de Programação Orientada a Objeto da Universidade Federal de Roraima, ministrada pelo professor Jean Bertrand.

## Arquitetura
A aplicação segue o padrão **MVC (Model–View–Controller)**:
- **Model**: entidade Aluno
- **View**: interface gráfica Swing (`JFrame`)
- **Controller**: validações e controle do fluxo

## Padrões de Projeto
- **Singleton**: utilizado na classe `BancoDeDados`, garantindo instância única para armazenamento dos dados em memória.

## Funcionalidades
- Cadastro de alunos
- Validação de CPF (11 dígitos e não duplicado)
- Listagem de alunos no console (ID, nome, CPF e matrícula)

## UML
O diagrama UML foi elaborado no **draw.io**, representando corretamente as classes, associações, herança e o uso do Singleton, de acordo com o código implementado.

![UML-ALUNOS](https://github.com/user-attachments/assets/03879323-f53f-4fc8-8a2e-2c16152de124)


## Execução
Executar a classe `TelaAluno` no Apache NetBeans.

