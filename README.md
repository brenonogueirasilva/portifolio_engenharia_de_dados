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
</p>

#### Link Projeto: https://github.com/brenonogueirasilva/captura-de-dados-de-alteracao-CDC-pyspark
