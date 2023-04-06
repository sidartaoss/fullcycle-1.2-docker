# Iniciando com Docker - Desafio nginx com node.js

Este desafio consiste em:

- Utilizar o _Docker Compose_ para subir o servidor web _nginx_ para atuar como **proxy reverso**;

- Assim, ao acessar o _nginx_, o mesmo fará uma chamada para uma aplicação _node.js_;

- A aplicação _node.js_, por sua vez, adicionará um registro em um banco de dados _mysql_ na tabela _people_;

- O retorno da aplicação _node.js_ para o _nginx_ deve ser:

  - `<h1>Full Cycle Rocks!</h1>`;
  - Lista de nomes cadastrados no banco de dados.

- Ao rodar `docker-compose up -d`, o _nginx_ deverá estar disponível para ser acessado na porta **8080**.
