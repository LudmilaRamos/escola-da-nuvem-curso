# Lab11 - Criação de Tabela DynamoDB e Operação CRUD com AWS Lambda, API Gateway e S3

## Descrição

Este laboratório prático apresenta a criação de uma aplicação serverless utilizando o Amazon DynamoDB como banco de dados e o AWS Lambda para executar operações CRUD (Create, Read, Update e Delete). A aplicação é integrada via API Gateway e possui uma interface web hospedada no Amazon S3. Também foi configurado o monitoramento da solução com Amazon CloudWatch.

## Passos para Conclusão do Laboratório

- Criar uma role IAM com permissões adequadas para Lambda e DynamoDB.
- Criar uma tabela no Amazon DynamoDB.
- Desenvolver uma função Lambda em Python e integrá-la ao DynamoDB.
- Configurar o Amazon API Gateway com rotas para operações CRUD.
- Hospedar uma interface web no Amazon S3.
- Ativar o monitoramento da aplicação com o Amazon CloudWatch.
- Validar o funcionamento da aplicação e realizar a limpeza dos recursos utilizados.

## Objetivos

- Criar uma role IAM com permissões adequadas para Lambda e DynamoDB.
- Criar uma tabela no DynamoDB.
- Desenvolver uma função Lambda em Python integrada ao DynamoDB.
- Configurar o API Gateway com rotas de API para operações CRUD.
- Hospedar uma interface web no Amazon S3.
- Ativar o monitoramento com CloudWatch.
- Validar o funcionamento da aplicação e realizar limpeza dos recursos utilizados.

## Cenário

Construir uma aplicação web simples de cadastro de produtos. O frontend estático é hospedado em um bucket do Amazon S3, enquanto as requisições de criação, leitura, atualização e exclusão são processadas por uma função AWS Lambda que interage diretamente com uma tabela DynamoDB. As chamadas da aplicação passam por um endpoint exposto no API Gateway, e o monitoramento da solução é realizado via Amazon CloudWatch.

## Prints


Exemplo de uso:
```markdown
![Aplicação Web Funcionando](lab11-site-funcionando.png)
