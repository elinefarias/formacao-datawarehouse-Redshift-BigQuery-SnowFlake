# Formação Data Warehouse com Redshift, BigQuery e SnowFlake 

Bem-vindo ao meu repositório! Aqui você encontrará o que aprendi durante o Curso de Data Warehouse. Este repositório serve como um registro do meu progresso e das habilidades que adquiri ao longo do curso.

### Descrição :
Um data warehouse é um sistema de armazenamento de dados projetado para análise eficiente de informações de negócios. Serve como um repositório central de dados extraídos de várias fontes, fornecendo insights estratégicos para a tomada de decisões organizacionais. Neste curso foi abordado as três das principais ferramentas de Data Warehouse:

- **Snowflake**: um data warehouse nativo da nuvem que oferece escalabilidade, segurança e desempenho sem a necessidade de gerenciar infraestrutura física. Utiliza uma arquitetura de banco de dados em nuvem que separa o armazenamento de dados do processamento de consultas, permitindo escalabilidade independente.
  
- **Amazon Redshift**: um data warehouse baseado em nuvem que permite armazenar e analisar grandes volumes de dados usando SQL. Utiliza uma arquitetura em cluster massivamente paralela para processar consultas de forma rápida e eficiente, permitindo análises em tempo real e escalabilidade.

- **BigQuery**: um serviço de data warehouse baseado em nuvem que permite armazenar e analisar grandes volumes de dados usando SQL. Utiliza uma arquitetura de processamento em coluna para consultas rápidas e escaláveis em grandes conjuntos de dados.

### Conteúdo :

- Fundamentos de Data Warehouse, incluindo clusters, replicação, particionamento, armazenamento colunar e tolerância a falhas.
  
- Modelagem de Dados para Data Warehouses, como modelos dimensionais star e snowflake, modelo relacional, Galaxy Schema e outros.
  
- Fundamentos e aplicações em Redshift, incluindo conceitos como sortkey, distkey, diststyle, cache, criação de consultas utilizando CTEs, planos de execução, vinculação a dados externos, importação com copy, views e views materializadas.
  
- Fundamentos e aplicações em BigQuery, como criação de projetos, tabela pivot, partições, tabelas externas, views e mais.
  
- Fundamentos e aplicações em Snowflake, incluindo Virtualwarehouse, cache, clustering, views, time travel, fail-safe, tasks e mais.

- Criação de um projeto prático: carga de dados do staging de forma incremental para um Data Warehouse, utilizando CDC, streams e tasks.

### Os tipos da linguagem SQL são:
<ul>
  <li><strong>DDL</strong> - Linguagem de Definição de Dados (Data Definition Language).</li>
  <p>Estes comandos interagem com os objetos do banco.</p>
  <p>Comandos DDL: CREATE, ALTER e DROP.</p>

  <li><strong>DML</strong> - Linguagem de Manipulação de Dados (Data Manipulation Language).</li>
  <p>Estes comandos interagem com os dados dentro das tabelas.</p>
  <p>Comandos DML: INSERT, DELETE e UPDATE.</p>

  <li><strong>DQL</strong> - Linguagem de Consulta de Dados (Data Query Language).</li>
  <p>Estes são comandos de consulta.</p>
  <p>Comando DQL: SELECT (às vezes agrupado na DML, dependendo da fonte).</p>

  <li><strong>DTL</strong> - Linguagem de Transação de Dados (Data Transaction Language).</li>
  <p>Estes comandos controlam as transações.</p>
  <p>Comandos DTL: BEGIN TRANSACTION, COMMIT e ROLLBACK.</p>

  <li><strong>DCL</strong> - Linguagem de Controle de Dados (Data Control Language).</li>
  <p>Estes comandos controlam a segurança do banco de dados.</p>
  <p>Comandos DCL: GRANT, REVOKE e DENY.</p>
</ul>
