# 📊 Collection of Datasets for Data Science & AI

[![Datasets](https://img.shields.io/badge/Datasets-CSV-orange.svg)]()
[![Python](https://img.shields.io/badge/Python-Pandas-blue.svg)](https://pandas.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Bem-vindo ao repositório de datasets! Esta é uma coleção curada de conjuntos de dados em formato `.csv`, prontos para uso em projetos de **Ciência de Dados**, **Aprendizado de Máquina (Machine Learning)**, **Análise Exploratória de Dados (EDA)** e práticas de **Banco de Dados**.

Este repositório é mantido com o objetivo de fornecer dados limpos e organizados para fins educacionais, pesquisa e desenvolvimento de protótipos.

---

## 📁 Catálogo de Datasets

| Arquivo | Descrição | Principais Casos de Uso |
| :--- | :--- | :--- |
| **`titanic.csv`** | O clássico conjunto de dados dos passageiros do Titanic. | Classificação binária, EDA, introdução ao Machine Learning. |
| **`StudentsPerformance.csv`** | Dados demográficos e notas de estudantes em exames. | Regressão, classificação, análise de correlação e viés em dados. |
| **`DisasterTweets.csv`** | Tweets classificados como relacionados ou não a desastres reais. | Processamento de Linguagem Natural (NLP), classificação de texto. |
| **`tweets.csv`** | Conjunto de dados geral de tweets (texto e metadados). | Análise de sentimentos, mineração de texto, modelagem de tópicos. |
| **`books-15k.csv`** | Metadados de 15.000 livros (título, autor, avaliações, etc.). | Sistemas de recomendação, EDA, análise de tendências de mercado. |
| **`car_sales.csv`** | Registro de vendas de veículos com características e preços. | Regressão (previsão de preço), análise de séries temporais, BI. |
| **`superstore.csv`** | Dados de vendas de uma grande rede de varejo (Superstore). | Business Intelligence, previsão de demanda, criação de dashboards. |

---

## 💻 Como Utilizar

Os arquivos estão em formato CSV (Comma-Separated Values), compatíveis com a maioria das ferramentas de análise. 

### Exemplo em Python (Pandas)
```python
import pandas as pd

# Carregar o dataset
df = pd.read_csv('titanic.csv')

# Visualizar as primeiras linhas
print(df.head())

# Estatísticas descritivas básicas
print(df.describe())
