## Laboratório 07 - Implantação e Gerenciamento de Aplicações com AWS Elastic Beanstalk

### Descrição

Neste laboratório, aprendi a  implantar uma aplicação web utilizando o serviço AWS Elastic Beanstalk e configurar as permissões necessárias por meio de uma role IAM (Perfil de Instância EC2). Essa abordagem permite uma implantação simplificada e o gerenciamento centralizado da aplicação e dos recursos subjacentes, como EC2, Auto Scaling, ELB e CloudWatch.

---

### Passos para Conclusão do Laboratório

- Criar uma role IAM com as permissões necessárias para ser utilizada como perfil de instância EC2 no Elastic Beanstalk.
- Implantar uma aplicação de exemplo (Node.js neste caso) no Elastic Beanstalk.
- Verificar a criação e o funcionamento do ambiente no console do Elastic Beanstalk.
- Acompanhar o status da aplicação acessando as opções de monitoramento, logs e métricas no painel do Elastic Beanstalk.
- Explorar a infraestrutura gerenciada automaticamente pelo Beanstalk (EC2, ELB, Auto Scaling e CloudWatch).
- Validar a aplicação em execução por meio do endpoint gerado automaticamente.
- Compreender como o Elastic Beanstalk abstrai a complexidade da infraestrutura e facilita a gestão contínua de aplicações em nuvem.

---

### Objetivos

- Criar uma role IAM (Perfil de Instância EC2) com as permissões necessárias para o Elastic Beanstalk.
- Configurar e lançar um ambiente Elastic Beanstalk para uma aplicação web.
- Navegar pelo console do Elastic Beanstalk para monitorar a saúde, logs e métricas da aplicação.
- Entender como o Elastic Beanstalk abstrai e gerencia a infraestrutura AWS subjacente (EC2, Auto Scaling, ELB, CloudWatch).

---

### Cenário

### Cenário

Implantar e configurar rapidamente uma aplicação web na AWS, garantindo que a infraestrutura esteja corretamente configurada, com permissões adequadas para gerenciamento e atualizações, permitindo que a aplicação seja facilmente gerenciada e monitorada. O AWS Elastic Beanstalk é a ferramenta escolhida para automatizar a maior parte desse processo.
