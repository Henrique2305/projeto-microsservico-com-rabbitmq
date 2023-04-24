# Projeto Alura Food (curso de microsserviços da Alura)

## Descrição

Esse projeto tem como objetivo o estudo de microsserviços com Java
usando Spring boot e RabbitMQ.

## Pré-requisito

Instale o Docker e o SDK do Java.

## Instalação

```bash
# Faça um clone desse projeto
> git clone https://github.com/Henrique2305/projeto-microsservico-com-rabbitmq.git

# Dentro do diretório do /rabbit, rode o docker compose para subir o RabbitMQ
> docker-compose up
```
Abra os projeto /pagamentos e /pedidos. Altere as configurações de banco de dados
no arquivo application.properties.

Rode primeiro o projeto /server e em seguido o /gateway. 

Rode os projetos de /avaliacao, /pagamentos e /pedidos.

Faça uma requisição para o endpoint do /pedidos e uma requisição para o /pagamentos.