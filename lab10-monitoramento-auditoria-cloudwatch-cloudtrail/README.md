# Lab10 - Monitoramento e Auditoria com CloudWatch e CloudTrail na AWS

## Descrição

Neste laboratório prático, aprendi a configurar um ambiente de monitoramento e auditoria na AWS utilizando o Amazon CloudWatch e o AWS CloudTrail. Também explorei o uso do Amazon SNS para envio de notificações por e-mail. O processo incluiu a configuração de alarmes para monitorar a utilização de CPU de uma instância EC2, o rastreamento de atividades da conta com o CloudTrail e a visualização dos logs armazenados em um bucket S3.

## Passos para Conclusão do Laboratório

- Configurar um alarme no CloudWatch para monitorar a utilização de CPU em uma instância EC2 e configurar notificações via SNS.
- Habilitar o rastreamento de atividades da conta com o AWS CloudTrail e armazenar os logs em um bucket S3.
- Acessar e analisar os logs do CloudTrail utilizando o S3 ou CloudWatch Logs.
- Configurar o Amazon SNS para enviar notificações por e-mail quando o alarme do CloudWatch for acionado.

## Objetivos

- Configurar um alarme no CloudWatch para monitorar a utilização de CPU e enviar notificações por e-mail (SNS).
- Habilitar a auditoria (rastreamento de eventos) com o AWS CloudTrail e armazenar logs em um bucket S3.
- Visualizar os logs do CloudTrail via S3 ou CloudWatch Logs.

## Cenário

Configurar um ambiente de monitoramento e auditoria que permita:
- Monitorar o desempenho de uma instância EC2 e receber alertas sobre alta utilização de CPU.
- Manter um registro de auditoria das atividades da conta AWS para garantir segurança e conformidade.

## Prints


## Conclusão

O laboratório proporcionou um entendimento prático sobre como configurar um ambiente robusto de monitoramento e auditoria na AWS. A combinação do CloudWatch com alarmes e notificações por SNS permite um monitoramento proativo da infraestrutura, enquanto o CloudTrail garante a rastreabilidade e segurança das atividades realizadas na conta AWS. A visualização dos logs em um bucket S3 complementa a capacidade de análise e auditoria contínua, alinhando a prática com as melhores estratégias de segurança em nuvem.
