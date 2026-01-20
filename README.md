
2. Para o repositório Apache_spark  
→ Mesmo processo: edite o README.md existente → apague o conteúdo atual (que é bem curto) → cole isso → Commit.
Markdown# Apache Spark - Exercícios de Fixação em Engenharia de Dados

![Apache Spark Logo](https://img.shields.io/badge/Apache%20Spark-EE742A?style=for-the-badge&logo=apache-spark&logoColor=white)  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

Repositório com exercícios práticos e de fixação usando **Apache Spark** (via PySpark), focado em conceitos fundamentais de **Engenharia de Dados**.

Objetivo: praticar manipulação de dados em larga escala, transformações, agregações, joins, window functions e boas práticas em Spark.

## Sobre o Projeto

Este repositório contém um notebook Jupyter (`Apache_Spark.ipynb`) com exercícios resolvidos e comentados, cobrindo tópicos essenciais para quem está iniciando ou consolidando conhecimentos em Spark para engenharia de dados.

Exercícios baseados em cenários reais como:
- Leitura e processamento de datasets (CSV, Parquet, JSON)
- Limpeza e transformação de dados
- Operações com DataFrames (select, filter, groupBy, agg, join)
- Uso de funções SQL e UDFs
- Window functions e ranking
- Otimização básica (cache, partition, broadcast)

## Tecnologias Utilizadas
- **Apache Spark** (PySpark)  
- **Python** 3.x  
- **Jupyter Notebook**  
- Bibliotecas: pyspark.sql, pyspark.ml (quando aplicável)

## Como Executar o Notebook

### Pré-requisitos
- Python 3.8+ instalado
- Apache Spark instalado localmente ou via Docker
- Ou use ambientes prontos como:
  - Google Colab (recomendado para iniciantes)
  - Databricks Community Edition (gratuito)
  - Jupyter local com PySpark configurado

### Opção 1: Google Colab (mais simples – sem instalação)
1. Abra o notebook diretamente no Colab:

2. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Lucas-Martins920/Apache_spark/blob/main/Apache_Spark.ipynb)  
   (clique no badge acima ou copie o link do notebook)

3. Instale PySpark no início do notebook (já deve ter uma célula para isso):
   ```python
   !pip install pyspark

Execute as células sequencialmente.

Opção 2: Local com Jupyter + PySpark

Instale PySpark:Bashpip install pyspark
Inicie o Jupyter:Bashjupyter notebook
Abra Apache_Spark.ipynb e execute.

Estrutura do Repositório
textApache_spark/
├── Apache_Spark.ipynb      # Notebook principal com todos os exercícios
├── LICENSE                 # Licença MIT
└── README.md               # Esta documentação
