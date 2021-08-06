# Criando microsserviços em Java com AWS ECS e Fargate!

Projeto desenvolvido no curso da Udemy 🔥 [Criando serviços em Java com AWS ECS e Fargate](https://www.udemy.com/course/aws-ecs-fargate-java/?referralCode=859777729E4809B20485) 🔥

Nesse curso foi desenvolvido duas aplicações utilizando **[Spring Boot](https://spring.io/projects/spring-boot) em containers [Docker](https://www.docker.com)**, para interagir com serviços da AWS.

[<img src="imagens/projeto-infra.png" alt="aws_course_image" style="zoom:30%;"/>](https://www.udemy.com/course/aws-ecs-fargate-java/?referralCode=859777729E4809B20485)

Infraestrutura das aplicações baseadas em **Docker** com **AWS CDK**, interagindo com serviços da AWS como **SNS**, **SQS**, **RDS**, **DynamoDB** e **S3**.

- **[ECS](https://aws.amazon.com/ecs/):** o Elastic Container Service é o serviço de orquestração de containers da AWS. Com ele é possível gerenciar a execução de aplicações baseados em **containers Docker** de forma robusta e escalável. E com o **[AWS Fargate](https://aws.amazon.com/fargate)**, o **[Serverless](https://aws.amazon.com/serverless/)** compute for containers da AWS, não é necessário criar instâncias de máquinas EC2, reduzindo o custo de operação de aplicações baseadas em containers;
- **[RDS](https://aws.amazon.com/rds/)**: o Relational Database Service é um recurso que permite a criação de instâncias de banco de dados, com serviços como backups automáticos e diretrizes de segurança de acesso;

- **[SNS](https://aws.amazon.com/sns)**: o Simple Notification Service é um recurso muito utilizado para criação de mecanismos de notificações para diversas aplicações ou outros serviços;

- **[SQS](https://aws.amazon.com/sqs/)**: o Simple Queue Service é um recurso que permite a criação de filas para entrega de mensagens de forma rápida e confiável, possibilitando a criação de um mecanismo assíncrono de comunicação entre aplicações;

- **[DynamoDB](https://aws.amazon.com/dynamodb)**: esse é um poderoso serviço de banco de dados NoSQL, que permite a criação de tabelas, sem a necessidade de se criar um servidor, com características exclusão automática de dados, escalabilidade e muito mais;

- **[S3](https://aws.amazon.com/s3/)**: o Simple Storage Service permite a criação de buckets para armazenamento seguro de arquivos. Além disso é possível configurar eventos a serem gerados quando esses arquivos são colocados nesses buckets, fazendo com outras aplicações sejam avisadas desses eventos.

Foi utilizado o **[AWS SDK](https://aws.amazon.com/sdk-for-java/)**, que é um conjunto de bibliotecas desenvolvido pela própria AWS para utilizar seus serviços. Esses recursos serão criados na AWS utilizando o **AWS Cloud Development Kit - [CDK](https://aws.amazon.com/cdk/)**, uma forma moderna de modelamento e provisionamento de infrastrutura na AWS. Você também aprenderá como monitorar os serviços através de gráficos e métricas, além de utilizar o **[CloudWatch Insights](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/logs/AnalyzingLogData.html),** para visualização e pesquisa de logs das aplicações. 

[<img src="imagens/aws_course_image.png" alt="aws_course_image" style="zoom:30%;"/>](https://www.udemy.com/course/aws-ecs-fargate-java/?referralCode=859777729E4809B20485)

