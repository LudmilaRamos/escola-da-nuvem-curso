# Lab 5 - Integração SNS e SQS com Dead-Letter Queue (DLQ)

Neste laboratório, aprendi a criar um fluxo de mensagens desacoplado utilizando SNS (Simple Notification Service) e SQS (Simple Queue Service) com uma Dead-Letter Queue (DLQ). Esse cenário simula a arquitetura de microsserviços, onde eventos são publicados e processados de forma assíncrona, com tolerância a falhas.

## Objetivos

- Criar uma fila SQS para servir como Dead-Letter Queue (DLQ).
- Criar uma fila SQS padrão principal.
- Configurar a fila principal para usar a DLQ (Política de Redirecionamento/Redrive Policy).
- Criar um tópico SNS padrão.
- Inscrever a fila SQS principal no tópico SNS.
- Testar o envio de mensagens via SNS e o recebimento na fila SQS.
- Compreender e simular o envio de mensagens para a DLQ.

## O que foi feito

1. Criada a fila SQS para DLQ.
2. Criada a fila SQS principal.
3. Configurada a política de redirecionamento da fila principal para a DLQ.
4. Criado o tópico SNS.
5. Inscrita a fila SQS principal no tópico SNS.
6. Testado envio e recebimento de mensagens.
7. Simulado o envio de mensagens para a DLQ.

## Cenário
Estamos desenvolvendo uma aplicação baseada em microsserviços. Um serviço (publicador) precisa notificar outros serviços (assinantes) sobre eventos de forma assíncrona e resiliente.

## 🖼️ Prints do Laboratório


