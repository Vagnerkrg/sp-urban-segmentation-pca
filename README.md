# 🏙️ Análise de Segmentação Socioeconômica dos Distritos de São Paulo

🐍 Python | 📊 Data Science | 🗺️ Geospatial Analysis | 📦 v1.0.0

---

## 📌 Visão Geral do Projeto

Este projeto tem como objetivo analisar e segmentar os distritos da cidade de São Paulo com base em indicadores socioeconômicos, utilizando técnicas de redução de dimensionalidade e análise multivariada.

O resultado final é um ranking interpretável dos distritos, apoiado por visualização geográfica interativa.

---

## 🎯 Problema de Negócio

Cidades grandes possuem alta heterogeneidade socioeconômica entre regiões.

O objetivo deste projeto é:

> Criar uma metodologia estatística capaz de identificar padrões e desigualdades entre distritos, apoiando análises urbanas e tomada de decisão baseada em dados.

---

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas e NumPy
- Scikit-Learn (PCA)
- GeoPandas e Shapely
- Folium (mapas interativos)
- Mapclassify
- Unidecode

---

## 📊 Metodologia

### 1. Preparação e Padronização dos Dados

Foi aplicada padronização via Z-score para garantir que todas as variáveis estivessem na mesma escala.

---

### 2. Validação Estatística

Antes da aplicação do PCA, foram realizados testes para garantir adequação dos dados:

- KMO (Kaiser-Meyer-Olkin)
- Teste de Bartlett

---

### 3. Redução de Dimensionalidade (PCA)

Foi aplicada Análise de Componentes Principais para reduzir a dimensionalidade dos dados e identificar padrões latentes.

Os componentes principais foram selecionados com base no critério de variância explicada.

---

### 4. Construção do Índice de Ranking

Os componentes foram combinados para gerar um índice único de ordenação socioeconômica dos distritos.

---

### 5. Análise Geoespacial

Os dados foram integrados com shapefiles oficiais da cidade de São Paulo, permitindo a construção de mapas interativos e análise espacial dos resultados.

---

## 📁 Estrutura do Projeto

- `dados/` → bases socioeconômicas e shapefiles
- `notebooks/` → análise e modelagem PCA
- `mapas/` → visualizações geográficas geradas
- `requirements.txt` → dependências do projeto

---

## 🚀 Resultado

O projeto gera um ranking socioeconômico interpretável dos distritos de São Paulo, permitindo identificar padrões espaciais e desigualdades urbanas de forma visual e analítica.
