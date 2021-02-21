# Code Challenge Rocketseat


## Micro-serviço com Node.js

- Utilizando Kafka;
- Utilizando Node.js;

## Aplicações

- API principal (Station);
- Geração de certificados;

## Fluxo

- API principal envia uma mensagem pro serviço de certificado para gerar o certificado;
- Micro-serviço de certificado devolve uma resposta (síncrona/assíncrona);

Se conseguir síncrona/assíncrona:

- Receber uma resposta assíncrona de quando o e-mail com o certificado for enviado;

## O que sabemos?

- REST (latência);
- Redis / RabbitMQ / **Kafka**;

- Utilizam o Kafka: Nubank, Uber, Paypal, Netflix; 