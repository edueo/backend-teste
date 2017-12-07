# Teste para candidatos à vaga de backend

> [![Logo Viva Decora](https://cdn.rawgit.com/vivadecora/backend-teste/master/vivadecora-logo.png)](https://www.vivadecora.com.br)
>
> Esse teste é público. Candidatos para o teste devem implementar a aplicação solicitada e criar uma issue com um link para um repositório com a solução do mesmo.

## Objetivo do desafio
Criar uma aplicação web que implemente um CRUD de veículos. Um veículo é um carro ou moto com as seguintes características:

### Carro:
- Montadora (Chevrolet, Ford, Honda, ...)
- Modelo (Monza, Fusion, Maverick, ...)
- Cor (azul, verde, vermelho, ...)
- Kilometragem (0km, 5000km, 12000km, ...)
- Motor (1.0, 1.4, 2.0, ...)

### Moto:
- Montadora (Ducati, Yamaha, Honda, ...)
- Modelo (Burgman, Tenere, MT-03, ...)
- Cor
- Kilometragem
- Motor (150, 660, 1200, ...)

A aplicação é apenas um CRUD sem usuários (não existe autenticação). Deve ser possível:
- Inserir, editar e deletar uma montadora, um modelo ou um veículo
- Pesquisar os veículos disponíveis com a possibilidade de filtrar por quaisquer características ou combinação de características disponíveis. Também deve ser possível filtrar por faixas de valores. Por exemplo:
* Motos da Yamaha com kilometragem menor que 10000km;
* Carros Chevrolet com motor maior que 1.4

A interface de uso fica a critério do desenvolvedor. A UI/UX da aplicação não será avaliada, o únicos critérios que devem atendendidos são os requisitos funcionais. 

## Requisitos:
- A aplicação deve executar as operações de CRUD através de chamadas AJAX. É um diferencial positivo se a aplicação for uma SPA (single-page application). Outro diferencial bastante positivo é o frontend ser desenvolvido em AngularJS.
- Backend desenvolvido em qualquer linguagem dinamicamente tipada. É um diferencial positivo se for desenvolvido em Python. É mais positivo se utilizar o framework Django.
- Processo de desenvolvimento versionado via Git em algum repositório público do github ou bitbucket.
- Relatório de cobertura dos testes unitários de backend.
- Readme que explique como rodar o projeto, como gerar o relatório de cobertura e como executar quaisquer scripts necessários.
- A aplicação deve possuir um script que popula o banco inicialmente com alguns veículos para demonstração.

## Critérios de avaliação:
- Modelagem do banco de dados. Você tem toda a liberdade de criar quantas tabelas ou campos considerar necessários.
- Organização do código: desacoplamento e legibilidade contam.
- Automatização de tarefas.
- Flexibilidade do sistema para adição/remoção de funcionalidades.
- O front só será avaliado segundo o código Javascript. Não se preocupe com o HTML/CSS, fique à vontade para usar qualquer framework ou bootstrap que achar conveniente.

## Como vamos avaliar:
- Vamos subir a aplicação e acessar via localhost:<alguma-porta>. Vamos cadastrar/editar/deletar algumas entidades. Vamos listar os veículos segundo diferentes combinações de filtros. Vamos analisar as chamadas AJAX feitas durante essa utilização.
- Vamos analisar o relatório de cobertura da aplicação.
- Vamos ler o código.

## O que nós gostamos:
- Arquitetura que favorece a escalabilidade do sistema.
- Hierarquia clara entre componentes.
- Diante de dúvidas sobre qual caminho seguir, buscamos inspiração no Zen do Python.
- Gostamos do padrão REST, mas não ficamos limitado a ele.
