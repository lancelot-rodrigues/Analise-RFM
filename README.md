# 🛍️ Segmentação de Clientes para E-commerce de Presentes – Projeto CRM

## 🎯 Objetivo

Este projeto tem como objetivo realizar uma análise exploratória e uma segmentação de clientes para um e-commerce britânico especializado em presentes personalizados. A ideia é identificar grupos de clientes com comportamentos semelhantes a partir do histórico de transações entre 2010 e 2011, para apoiar decisões nas áreas de **Marketing, Vendas e Produtos**.

---

## 🧰 Ferramentas Utilizadas

- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Scikit-learn (para clusterização)
- Google Colab

---

## 📊 Etapas do Projeto

### 1. Coleta de Dados
- Dataset transacional público (disponível no Kaggle).
- Período analisado: 01/12/2010 a 09/12/2011.

### 2. Limpeza e Pré-processamento
- Remoção de dados nulos e registros inconsistentes.
- Conversão de colunas de datas.
- Exclusão de transações canceladas e valores negativos.

### 3. Análise Exploratória
- Identificação dos países com maior número de pedidos.
- Visualização interativa de pedidos por país.
- Análise do volume e valor das vendas.

![Mapa de vendas por país](images/mapa_pedidos_pais.png)

### 4. Engenharia de Atributos – RFM
- Criação das variáveis:
  - **Recência**: dias desde a última compra.
  - **Frequência**: número total de compras.
  - **Valor Monetário**: total gasto pelo cliente.
- Normalização das variáveis.

### 5. Segmentação com K-Means
- Determinação do número ideal de clusters (método do cotovelo).
- Aplicação do algoritmo K-Means.
- Visualização dos segmentos de clientes.

![Gráfico de clusters](images/segmentacao_clusters.png)

---

## 🧠 Insights de Negócio

- **Foco geográfico**: O Reino Unido representa a maioria das vendas, apesar do modelo de negócio ser online. O marketing internacional pode ser mais bem segmentado.
- **Agrupamento estratégico**: A análise de clusters permite ações direcionadas para cada grupo: fidelização de clientes rentáveis, reativação de clientes inativos e aumento da frequência de clientes ocasionais.
- **Apoio visual**: A visualização interativa dos clusters e do mapa facilita a comunicação entre as equipes técnicas e de negócios.

---

## 🔗 Links

- 📄 [Notebook no Google Colab](https://colab.research.google.com/drive/1vobc8p_swPcnWUmEbDNR-EbsPXaupbQh#scrollTo=AOelAKEyvnBI)
- 📂 [Dataset no Kaggle (Online Retail)](https://www.kaggle.com/datasets)
- 🖼️ Gráficos e visualizações disponíveis na pasta `/images`

---
