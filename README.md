# API de Carros - webAPI

Esta é uma API RESTFUL desenvolvida para o gerenciamento de informações de carros, utilizando **Node.js** e **Express**. A API permite criar, ler, atualizar e excluir carros, com validação dos dados utilizando a biblioteca **Joi**.

Este é um projeto básico de CRUD (Create, Read, Update, Delete), que será expandido no futuro, Este é apenas o escopo inicial.

## Funcionalidades

- **GET /**: Retorna a lista completa de carros.
- **GET /:sigla**: Retorna as informações de um carro específico, identificado pela sigla.
- **POST /**: Adiciona um novo carro à lista.
- **PUT /:sigla**: Atualiza as informações de um carro específico, identificando a sigla.
- **DELETE /:sigla**: Remove um carro específico pela sigla.

## Estrutura do Projeto

- **app.js**: Arquivo principal que configura o servidor Express e as rotas de API.
- **tabelacarros.js**: Contém a lista de carros (dados fictícios).
- **validacao.js**: Contém as validações Joi para os dados dos carros.

## Endpoints

### 1. **GET /**

Retorna a lista completa de carros disponivéis.

#### Exemplo de Resposta:

```json
[
    
  {
	"nome": "BMW",
	"sigla": "BMW",
	"velocidadeMaxima": 200,
	"potencia": 500,
	"consumo": 7.5,
	"aceleracao": 4,
	"preco": 120000
  },
        

    
]
```