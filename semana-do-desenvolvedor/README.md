## Semana do Desenvolvedor AWS - 

Este laboratório prático faz parte da Semana do Desenvolvedor AWS da Escola da Nuvem, direcionado ao curso AWS Developer Associate.
Ao longo das quatro aulas que compõem este laboratório, construímos uma arquitetura AWS completa, funcional e orientada a eventos. Iniciamos com a criação de um endpoint API Gateway e o pipeline básico usando SQS e EventBridge. Seguimos integrando a ingestão de arquivos via S3 e implementando o processamento central que persiste dados no DynamoDB. Por fim, incorporamos fluxos de cancelamento e alteração de pedidos, além de mecanismos robustos de tratamento de erros com DLQs.

Esta solução serverless e desacoplada utiliza serviços-chave da AWS, como Lambda, API Gateway, SQS, EventBridge, SNS, S3, DynamoDB, IAM e CloudWatch, oferecendo uma visão prática e integrada de desenvolvimento em nuvem.

Os desafios enfrentados ao longo do laboratório proporcionam um aprendizado valioso, reforçando as boas práticas e o domínio dos serviços AWS.

## Prints da Implementação

![API Gateway](Semana-do-Desenvolvedor/APi-Gatway.png)  
*Configuração do endpoint no API Gateway para receber os pedidos.*

![AWS Lambda](Semana-do-Desenvolvedor/Lambda-validação-S3.png)  
*Função Lambda de pré-validação configurada para processar os pedidos antes de enviá-los para a fila SQS.*

![CloudWatch Logs](Semana-do-Desenvolvedor/CLoudWatch.png)  
*Logs da execução da função Lambda visualizados no CloudWatch para monitoramento e troubleshooting.*
