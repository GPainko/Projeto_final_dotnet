# Projeto final da materia de Programação .NET

Desenvolver uma aplicação ASP.NET Core MVC com Entity Framework Core, aplicando os conceitos apresentados ao longo da disciplina. O foco principal é demonstrar a capacidade de construir uma aplicação web completa com as seguintes características:

- Estruturação da aplicação no padrão MVC;
- Persistência de dados com Entity Framework Core;
- Implementação de um relacionamento um para muitos (1:N);

Utilização das boas práticas de organização de código e navegação entre telas.

## Tema da aplicação

Você deverá implementar um sistema de controle de **Projetos** e suas respectivas **Tarefas**.

No sistema, um **Projeto** poderá ter várias **Tarefas** associadas a ele. Cada **Tarefa**, por sua vez, estará sempre vinculada a um único **Projeto**.

A aplicação deverá permitir:

- Cadastro, listagem, edição e exclusão de **Projetos**;
- Cadastro, listagem, edição e exclusão de **Tarefas** vinculadas a cada **Projeto**;
- Exibição, ao visualizar os detalhes de um **Projeto**, de todas as **Tarefas** associadas a ele.

## Modelagem

Você deverá criar duas entidades:

- **Projeto**, contendo informações como um identificador, nome do projeto, cliente, data de início e data de término (opcional);
- **Tarefa**, contendo um identificador, título, descrição, status da tarefa e a referência ao projeto ao qual está vinculada.

O relacionamento entre as entidades deverá ser implementado corretamente, de forma que um **Projeto** possa conter múltiplas **Tarefas**.
