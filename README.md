# Portfólio de Engenharia de Dados

## Projeto 1: Solução de Versionamento de Dados (CDC) com PySpark
Este projeto foi concebido em resposta a uma necessidade identificada no meu ambiente de trabalho. Nossa equipe lida com uma tabela dentro de um Data Lake que sofre modificações (updates) que impede a existência de um histórico acessível. Curiosamente, a origem dessa tabela é um arquivo de backup de um banco de dados MySQL, impedindo aplicar um processo de Change Data Capture (CDC) tradicional, o que nos levou a desenvolver um script capaz de simular um CDC. Dada a escala dessa tabela, com mais de dois milhões de linhas e mais de vinte colunas, optamos pelo uso do Spark, uma ferramenta ideal para o processamento de volumes massivos de dados. Como linguagem de programação, escolhemos o Python e utilizamos o PySpark como uma interface para interagir com o Apache Spark.
### Tecnologias Utilizadas
  Python, Pyspark, Minio, Airflow, Docker
<p align="left">
<img src="/img/python-logo.png" alt="python" height="50" /> 
<img src="/img/minio-logo.webp" alt="minio" height="50" /> 
<img src="/img/pyspark.jpg" alt="pyspark" height="50"/> 
<img src="/img/AirflowLogo.png" alt="airflow" height="50"/> 
<img src="/img/docker-logo.png" alt="docker" height="50"/> 
</p>

#### Link Projeto: https://github.com/brenonogueirasilva/captura-de-dados-de-alteracao-CDC-pyspark


## Projeto 2: Ingestão de Dados por API
Este projeto tem como objetivo desenvolver uma automação que seja capaz de coletar dados governamentais por meio de uma API e realizar o armazenamento dos dados coletados em um banco de dados interno relacional. O projeto será implementando utilizando o Python, junto de programação orientado a objetos (POO) e boas práticas de programação. Além disso, o projeto será versionado dentro de um repositório no Github utilizando um padrão de mensagens de commit e de git flow. Por fim, serão implementados testes unitários para validar métodos e funções.
### Tecnologias Utilizadas
  Python, Postgres, Docker
<p align="left">
<img src="/img/python-logo.png" alt="python" height="50" /> 
<img src="/img/postgres-logo.png" alt="minio" height="50" /> 
<img src="/img/docker-logo.png" alt="docker" height="50"/> 
</p>

#### Link Projeto: https://github.com/brenonogueirasilva/ingestao_api/

## Projeto 3: Data Lake on Premisse

Na era do Big Data, com o surgimento dos famosos três "V's" (Velocidade, Variedade e Volume), tornou-se imperativo o desenvolvimento de uma nova arquitetura de armazenamento de dados capaz de lidar com esse cenário desafiador. Nesse contexto, o Data Lake emergiu como uma das principais abordagens de armazenamento de dados concebidas para atender às demandas do Big Data.

Com o intuito de aprofundar o entendimento do Data Lake e compreender de maneira prática o seu funcionamento, surgiu a ideia deste projeto que visa criar um Data Lake on-premises. Esse Data Lake simulará as três principais camadas de um Data Lake (Silver, Bronze e Gold), juntamente com as etapas de ingestão de dados e processamento.

### Tecnologias Utilizadas

  Minio, Hive, Trino, Python, Pyspark, Docker 
<p align="left">
<img src="/img/minio-logo.webp" alt="minio" height="50" /> 
<img src="/img/hive-logo.jpg" alt="hive" height="50" /> 
<img src="/img/trino-logo.png" alt="trino" height="50"/> 
<img src="/img/python-logo.png" alt="python" height="50"/> 
<img src="/img/pyspark.jpg" alt="pyspark" height="50"/> 
<img src="/img/docker-logo.png" alt="docker" height="50"/> 
</p>

#### Link Projeto: https://github.com/brenonogueirasilva/datalake_on_premisse/

## Projeto 4: Ingestão de Dados por API em ambiente Cloud (GCP)

O objetivo deste projeto é desenvolver uma automação que colete dados governamentais por meio de uma API e armazene esses dados. O projeto será implementado em nuvem, especificamente na Google Cloud Platform (GCP). Será utilizado Cloud Functions como local de execução do código, que será desenvolvido em Python, seguindo os princípios da programação orientada a objetos (POO) e as melhores práticas de programação.

Após a coleta dos dados da API, as respostas serão salvas no formato JSON no Cloud Storage e, posteriormente, serão inseridas no BigQuery. O gatilho de execução será configurado por meio do Cloud Scheduler. Toda a infraestrutura será provisionada utilizando o Terraform, que permite a criação da infraestrutura como código.

### Tecnologias Utilizadas

  Python, Cloud Function, Cloud Storage, Cloud Scheduler, Big Query, Terraform  
<p align="left">
<img src="/img/python-logo.png" alt="python" height="50" /> 
<img src="/img/cloud-function.png" alt="cloud-function" height="50" /> 
<img src="/img/logo-googlecloudstorage.png" alt="cloud_storage" height="50" /> 
<img src="/img/cloud-scheduler-2.png" alt="cloud_scheduler" height="50" />
<img src="/img/google-bigquery-logo-1.jpg" alt="google-bigquery" height="50" />
<img src="/img/terraform.png" alt="terraform.png" height="50" />  
</p>

#### Link Projeto: https://github.com/brenonogueirasilva/ingestao_api_cloud

## Projeto 5: Desenvolvimento de uma API junto a banco de dados NoSQL

Este projeto tem como objetivo desenvolver uma API que interaja com um banco de dados NoSQL MongoDB, hospedado no ambiente de nuvem da Google (GCP). A API será capaz de realizar todas as operações do CRUD (Create, Read, Update, Delete), permitindo a criação, leitura, atualização e exclusão de registros ou documentos. A proposta visa simular uma etapa do ambiente de trabalho de um engenheiro de dados, que frequentemente precisa disponibilizar dados por meio de uma API para uma aplicação por exemplo, frente às inúmeras vantagens proporcionadas como maior segurança, abstração mais eficiente dos dados, padronização e flexibilidade na manutenção.

### Tecnologias Utilizadas

  MongoDb, CloudRun, FastApi, Google Comput Engine, Python, Secret Manager, Terraform, Docker
  
<p align="left">
<img src="/img/MongoDB-Logo.jpg" alt="mongoDB" height="50" /> 
<img src="/img/cloud-run.png" alt="cloud-run" height="50" /> 
<img src="/img/fast-api.png" alt="fastapi" height="50"/> 
<img src="/img/Google-Compute-Engine.png" alt="google-compute-engine" height="50"/> 
<img src="/img/python-logo.png" alt="python" height="50"/> 
<img src="/img/secret-manager.png" alt="secret-manager" height="50"/> 
<img src="/img/terraform.png" alt="terraform" height="50"/> 
<img src="/img/docker-logo.png" alt="docker" height="50"/> 
</p>

#### Link Projeto: https://github.com/brenonogueirasilva/api_nosql

## Projeto 6: Desenvolvimento de um DataWarehouse em ambiente Cloud

O objetivo deste projeto é desenvolver um datawarehouse em ambiente cloud da Google, em específico no BigQuery, tendo como fonte um banco de dados relacional Mysql hospedado em um CloudSql. O banco de dados de produção por ser de natureza transacional (OLTP) é modelado orientado a entidade relacionamento, como no datawarehouse é voltado para processamento analítico (OLAP) será necessário trabalhar com modelo dimensional, junto de tabelas fatos e dimensões.

Para a transformação dos dados e consolidação das tabelas dimensionais no BigQuery, será utilizada a ferramenta DBT. Esta solução open source permite a materialização de tabelas do Data Warehouse por meio de consultas SQL, além de implementar lógica de carga incremental e tabelas de dimensão do tipo Slowly Changing Dimension (SCD). A integração entre o BigQuery e o Cloud SQL permitirá consultas federadas, possibilitando que o DBT realize toda a ETL de maneira eficiente. 

### Tecnologias Utilizadas

  CloudSql, MySql, Python, CloudFunctions, CloudScheduler, DBT, BigQuery, Terraform 
  
<p align="left">
<img src="/img/cloud-sql.png" alt="cloud_sql" height="50" /> 
<img src="/img/mysql-logo.png" alt="mysql" height="50" /> 
<img src="/img/python-logo.png" alt="python" height="50"/> 
<img src="/img/cloud-function.png" alt="cloud_functions" height="50"/> 
<img src="/img/cloud-scheduler-2.png" alt="cloud-scheduler" height="50"/> 
<img src="/img/dbt-logo.png" alt="dbt" height="50"/> 
<img src="/img/google-bigquery-logo-1.jpg" alt="bigquery" height="50"/> 
<img src="/img/terraform.png" alt="terraform" height="50"/> 
</p>

#### Link Projeto: https://github.com/brenonogueirasilva/data-warehouse/

## Projeto 7: Disponibilização de dados através de uma API de um banco de dados SQL

Dentro do escopo de atividades de um engenheiro de dados, a disponibilização ou recebimento de dados por meio de uma API é uma prática comum. Essa API pode ser consumida por diferentes aplicações, alinhando-se com as vantagens associadas à filosofia de microsserviços. Dentre outras como melhoria da segurança, a abstração eficiente de dados, e a flexibilidade de manutenção. 

Nesse contexto, este projeto tem como objetivo o desenvolvimento de uma API capaz de realizar operações CRUD (Create, Read, Update, Delete) em um banco de dados MySQL hospedado no Cloud SQL, dentro do ambiente de nuvem da Google (GCP). Ao longo do desenvolvimento, serão incorporadas boas práticas de Integração Contínua e Entrega Contínua (CI/CD). Isso incluirá o provisionamento da infraestrutura como código, utilizando o Terraform, e a implementação de pipelines automatizadas de código. Essas práticas serão integradas ao GitHub, permitindo a execução automática em ambientes de produção ou desenvolvimento sempre que houver mudanças no repositório. 

### Tecnologias Utilizadas

MySql, CloudSql, CloudRun, FastApi, Python, SecretManager, Terraform, Docker, GitHub, ApitGateway  
  
<p align="left">
<img src="/img/mysql-logo.png" alt="mysql" height="50" /> 
<img src="/img/cloud-sql.png" alt="cloud_sql" height="50" />
<img src="/img/cloud-run.png" alt="cloud_run" height="50" /> 
<img src="/img/fast-api.png" alt="fast_api" height="50" />
<img src="/img/python-logo.png" alt="python" height="50" />
<img src="/img/secret-manager.png" alt="secret_manager" height="50" />
<img src="/img/terraform.png" alt="terraform" height="50" />
<img src="/img/docker-logo.png" alt="docker" height="50" />
<img src="/img/cloud_build.png" alt="cloud_build" height="50" />
<img src="/img/git_hub.jpg" alt="git_hub" height="50" />
<img src="/img/api_gateway.png" alt="api_gateway" height="50" />
</p>

#### Link Projeto: https://github.com/brenonogueirasilva/criacao-api-sql

## Projeto 8: Versionamento de Tabelas com Streaming de Dados usando Dataflow

Dentro do meu ambiente de trabalho, nos deparamos com tabelas em bancos transacionais que passam por edições e exclusões físicas de registros, resultando na impossibilidade de consultar seus históricos, sendo possível apenas visualizar o seu estado atual. 

Este projeto tem como objetivo desenvolver uma pipeline capaz de versionar os registros dessas tabelas, criando um histórico acessível em tempo real para a área de negócios. Para lidar com os dados em tempo real, optamos pelo uso de tecnologia de streaming, especificamente o Apache Beam, executado no ambiente em nuvem da Google (GCP) por meio de um job no Dataflow. Além disso, para capturar as alterações nos registros do banco, utilizaremos um serviço de Captura de Dados Alterados (CDC) gerenciado no GCP chamado Datastream. 

### Tecnologias Utilizadas

MySql, CloudSql, Data Stream, Cloud Data Storage, Pub/Sub, Data Flow, Apache Beam, BigQuery, Clound Build, GitHub, Terraform, Docker   
  
<p align="left">
<img src="/img/mysql-logo.png" alt="mysql" height="50" /> 
<img src="/img/cloud-sql.png" alt="cloud_sql" height="50" />
<img src="/img/datastream.png" alt="datastream" height="50" /> 
<img src="/img/cloud storage.png" alt="cloud storage" height="50" />
<img src="/img/cloud-pub-sub.png" alt="cloud-pub-sub" height="50" />
<img src="/img/dataflow-logo.webp" alt="dataflow-logo" height="50" />
<img src="/img/Apache-Beam.png" alt="Apache-Beam" height="50" />
<img src="/img/google-bigquery-logo-1.jpg" alt="google-bigquery-logo-1" height="50" />
<img src="/img/cloud_build.png" alt="cloud_build" height="50" />
<img src="/img/git_hub.jpg" alt="git_hub" height="50" />
<img src="/img/terraform.png" alt="terraform" height="50" />
<img src="/img/docker-logo.png" alt="docker-logo" height="50" />
</p>

#### Link Projeto: https://github.com/brenonogueirasilva/cdc-streamming---V2


## Contato
https://www.linkedin.com/in/breno-nogueira-silva-52904012b/
