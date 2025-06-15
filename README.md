# Pipeline de Deploy com Elastic Beanstalk e CodePipeline

Este documento descreve como configurar um pipeline de CI/CD utilizando o AWS Elastic Beanstalk e o AWS CodePipeline para implantar uma aplicação.

## Pré-requisitos

1. **AWS CLI**: Certifique-se de que o AWS CLI está instalado e configurado com as permissões necessárias.
2. **Elastic Beanstalk CLI**: Instale o Elastic Beanstalk CLI para gerenciar o ambiente.
3. **Ambiente Elastic Beanstalk**: Crie um ambiente no Elastic Beanstalk para sua aplicação.
4. **Permissões do CodePipeline**: Garanta que você possui uma role IAM com permissões para gerenciar o CodePipeline, Elastic Beanstalk e S3.

#### Para rodar as migrations no container ####
```
docker compose exec server bash -c 'npx sequelize db:migrate'
```

## Formação AWS - Henrylle Maia 
## Aluno: Bruno Oliveira 