# Desafio Gerenciador de Tarefas
<br/>

Este é um desafio proposto pelo bootcamp Ignite da [Rocketseat](https://www.rocketseat.com.br/). O projeto é uma aplicação para gerenciar tarefas (ou todos), com algumas mudanças. Agora é permitida a criação de usuários com `name` e `username` e cada usuário pode fazer o CRUD de seus próprios todos.

A aplicação inclui as seguintes funcionalidades:

- Criação de um novo todo;

- Listagem de todos os todos do usuário;

- Alteração do `title` e `deadline` de um todo existente;

- Marcação de um todo como feito;

- Exclusão de um todo.

O usuário tem dois planos disponíveis: o plano grátis permite a criação de até dez todos, enquanto o plano Pro permite criar todos ilimitados. A validação do plano é feita usando middlewares.
<br/><br/>

## Tecnologias utilizadas

Este projeto foi desenvolvido em Node.js, com as seguintes tecnologias:

- <img 
    align="center" 
    alt="Express.js" 
    src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge" 
  /> para construir a API RESTful;

- <img 
    align="center" 
    alt="Jest" 
    src="https://img.shields.io/badge/Jest-323330?style=for-the-badge&logo=Jest&logoColor=white" 
  /> para testes unitários e de integração.
<br/><br/>

## Instalação e execução

Para executar este projeto, é necessário ter o Node.js instalado na sua máquina. Em seguida, siga os passos abaixo:

1. Clone este repositório usando o comando git clone https://github.com/seu-usuario/nome-do-repositorio.git.

2. Navegue até o diretório do projeto com o comando `cd nome-do-repositorio`.

3. Instale as dependências do projeto com o comando `npm install`.

4. Execute o servidor de desenvolvimento com o comando `npm run dev`.
<br/><br/>

## Testes

Para executar os testes unitários e de integração do projeto, utilize o comando `npm run test`.
<br/><br/>