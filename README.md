# API de Carros - webAPI

Esta é uma API RESTFUL desenvolvida para o gerenciamento de informações de carros, utilizando **Node.js** e **Express**. A API permite criar, ler, atualizar e excluir carros, com validação dos dados utilizando a biblioteca **Joi**.

Este é um projeto básico de CRUD (Create, Read, Update, Delete), que será expandido no futuro, Este é apenasd o escopo inicial.

## Funcionalidades

- **GET /**: Retorna a lista completa de carros.
- **GET /:sigla**: Retorna as informações de um carro específico,
identificado pela sigla.
- **POST /**: Adiciona um novo carro à lista.
- **PUT /:sigla**: Atualiza as informações de um carro específico,
identificando a sigla.
- **DELETE /:sigla**: Remove um carro específico pela sigla.
