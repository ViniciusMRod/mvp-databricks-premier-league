# ⚽ MVP Engenharia de Dados – Premier League (Databricks)

Este projeto é o MVP da disciplina de Engenharia de Dados da pós-graduação em Análise e Ciência de Dados. O objetivo é construir um pipeline completo utilizando a plataforma Databricks Community Edition, com foco em análise de partidas da Premier League.

## 🎯 Objetivo do Projeto

Analisar estatísticas históricas para prever se um time vai vencer, empatar ou perder, e gerar insights a partir de métricas como posse de bola, cartões vermelhos e desempenho de mandantes.

## 🧱 Tecnologias Utilizadas
- Apache Spark / PySpark
- Delta Lake
- SQL (no Databricks)
- Kaggle Datasets
- Visualizações no Databricks

## 📊 Análises Realizadas

- ✅ Quais times mandantes mais venceram?
- ✅ Quem teve maior média de posse de bola?
- ✅ Mandantes ou visitantes recebem mais cartões vermelhos?

## 🗃️ Modelagem de Dados

O projeto utiliza o modelo dimensional do tipo **Esquema Estrela**, com:

- **Tabela fato:** `fato_partida`
- **Tabelas dimensão:** `dim_time`, `dim_tempo`, `dim_local`, `dim_partida`

## 📁 Organização do repositório

- `notebook/`: notebook completo com o pipeline e análises
- `dataset/`: referência da fonte de dados usada (Kaggle)
- `evidencias/`: imagens e capturas de tela das visualizações

## 📌 Fonte dos Dados

[Kaggle – All Premier League Matches 2010–2021](https://www.kaggle.com/datasets/pablohfreitas/all-premier-league-matches-20102021)

## 👤 Autor

- Vinicius Rodrigues
- vinicius.matos.r@gmail.com
- www.linkedin.com/in/viniciusmrodrigues


