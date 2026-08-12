# 📊 Análise Exploratória do Catálogo da Netflix

Projeto de análise exploratória de dados desenvolvido em Python com o objetivo de investigar as principais características do catálogo da Netflix.

A análise envolve etapas de exploração, limpeza e transformação dos dados, além da criação de visualizações para identificar padrões relacionados aos tipos de conteúdo, gêneros, países, duração, classificações indicativas e evolução do catálogo ao longo dos anos.

## 🎯 Objetivo

O objetivo deste projeto é aplicar conceitos fundamentais de análise de dados utilizando Python e Pandas, transformando dados brutos em informações que permitam compreender melhor a composição e a evolução do catálogo analisado.

## 🛠️ Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- Jupyter
- Visual Studio Code

## 📂 Estrutura do projeto

```text
analise-netflix/
├── data/
│   └── netflix_titles.csv
├── notebooks/
│   └── analise_netflix.ipynb
└── README.md

## 🔎 Etapas da análise

O projeto foi desenvolvido seguindo as seguintes etapas:

1. Carregamento e exploração inicial dos dados;
2. Identificação de valores ausentes e possíveis inconsistências;
3. Tratamento e transformação das variáveis;
4. Preparação dos dados de gêneros e países;
5. Análise exploratória dos dados;
6. Criação de visualizações;
7. Interpretação dos resultados e identificação dos principais insights.

## 📈 Principais insights

A análise permitiu identificar alguns padrões importantes no catálogo:

- Aproximadamente **69,6% dos títulos são filmes**, enquanto 30,4% são séries.
- O número de títulos adicionados ao catálogo apresentou forte crescimento principalmente a partir de 2016.
- **International Movies** é a categoria mais frequente, seguida por Dramas e Comedies.
- Os **Estados Unidos** apresentam a maior presença entre os países associados às produções.
- Os filmes possuem duração média de aproximadamente **99,6 minutos**.
- Cerca de **67% das séries possuem apenas uma temporada**.
- **TV-MA** é a classificação indicativa mais frequente, representando aproximadamente 36,4% do catálogo.
- Os filmes atingiram o maior número de adições em 2019, enquanto as séries atingiram seu pico em 2020.

## ⚠️ Limitações dos dados

Os dados de 2021 estão disponíveis somente até 25 de setembro, portanto os resultados desse ano não devem ser comparados diretamente com anos completos.

Além disso, algumas produções estão associadas a múltiplos gêneros e países. Nessas análises, cada categoria foi considerada individualmente, portanto as contagens representam ocorrências e não necessariamente títulos exclusivos.