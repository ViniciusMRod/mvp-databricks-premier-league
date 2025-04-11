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

## 📓 Notebook

O notebook principal com todo o pipeline de dados está disponível em:  
🔗 [`notebook/premier_league_mvp.ipynb`](notebook/premier_league_mvp.ipynb)

## 📁 Organização do repositório

- `notebook/`: notebook completo com o pipeline e análises
- `dataset/`: referência da fonte de dados usada (Kaggle)
- `evidencias/`: imagens e capturas de tela das visualizações

## 📁 Fonte de Dados

Este projeto utiliza o dataset público do Kaggle:

🔗 https://www.kaggle.com/datasets/pablohfreitas/all-premier-league-matches-20102021

O arquivo utilizado é o: `df_full_premierleague.csv`

Você pode baixá-lo diretamente da página acima e carregá-lo no Databricks.

## 🧪 Autoavaliação

O objetivo principal deste projeto foi construir um pipeline completo de engenharia de dados na nuvem, utilizando a plataforma **Databricks**, com foco na análise de dados de partidas da Premier League. A proposta incluía prever resultados com base em estatísticas históricas, além de realizar análises que pudessem gerar insights sobre desempenho de mandantes e visitantes.

### ✅ Conquistas
- Todas as etapas do pipeline foram concluídas com sucesso: **coleta, transformação, modelagem dimensional, carga e análise**.
- As **tabelas fato e dimensões** foram criadas seguindo o modelo estrela, com consistência e clareza na estrutura.
- Foram elaboradas **análises em SQL e Python** que responderam às perguntas de negócio levantadas inicialmente.
- O projeto foi documentado e publicado no **GitHub**, com organização de pastas, visualizações e `README.md` completo.

### ⚠️ Dificuldades encontradas
- Inicialmente, houve desafios técnicos na manipulação de joins entre as dimensões e a tabela fato, especialmente relacionados a renomeações de colunas e conflitos de schema.
- Alguns erros no Databricks exigiram atenção especial à tipagem, persistência de tabelas em Delta/Parquet, e à diferenciação entre tabelas temporárias e permanentes.
- A etapa de visualização exigiu atenção extra para se alinhar com os objetivos do negócio e comunicar os resultados de forma clara.

### 💡 Trabalhos futuros
- Expandir o projeto com **modelos preditivos de classificação** (ex: logistic regression, random forest) para prever resultados com maior precisão.
- Construir um **dashboard interativo** com ferramentas como **Power BI**, **Tableau** ou **Streamlit**, consumindo as tabelas já modeladas.
- Adicionar uma **camada de orquestração** (ex: Airflow ou Databricks Jobs) para simular um pipeline de produção.
- Incluir **mais temporadas** ou outros campeonatos para ampliar a base e enriquecer os resultados.

### 🎯 Conclusão
O projeto atendeu aos objetivos definidos no início do trabalho, entregando uma solução funcional, bem documentada e com potencial de evolução. Além do aprendizado técnico com Spark e Databricks, o projeto fortaleceu habilidades de organização, troubleshooting e comunicação de dados.

## 👤 Autor

- Vinicius Rodrigues
- vinicius.matos.r@gmail.com
- www.linkedin.com/in/viniciusmrodrigues

---
