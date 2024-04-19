# Projeto Alura Food (curso de microsserviços da Alura)
![GitHub language count](https://img.shields.io/github/languages/count/Henrique2305/projeto-microsservico-com-rabbitmq)
![GitHub top language](https://img.shields.io/github/languages/top/Henrique2305/projeto-microsservico-com-rabbitmq)

## Descrição

Esse projeto teve como objetivo, o estudo de microsserviços com Java,
utilizando o Spring boot e o RabbitMQ.

## ✔️ Tecnologias utilizadas

- ``Java``
- ``Spring Boot``
- ``Spring Cloud``
- ``MySQL``
- ``RabbitMQ``

## Modo de uso

```bash
# Dentro do diretório do /rabbit, rode o docker compose para subir o RabbitMQ
> docker-compose up
```

Abra os projeto /pagamentos e /pedidos. Altere as configurações de banco de dados
no arquivo application.properties.

Rode primeiro o projeto, /server e em seguido o /gateway. 

Rode os projetos de /avaliacao, /pagamentos e /pedidos.

Faça uma requisição para o endpoint do /pedidos e uma requisição para o /pagamentos.
