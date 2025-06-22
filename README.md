# 📊 Análise de Acessos por Tecnologia de Telefonia Móvel - ANATEL

Este projeto realiza uma análise descritiva e inferencial sobre os acessos às tecnologias de telefonia móvel no Brasil com base em dados públicos da ANATEL.

## 🔍 Objetivo

Avaliar se há diferenças significativas no número de acessos entre as tecnologias 2G, 3G e 4G, utilizando estatísticas descritivas, visualizações e testes estatísticos não paramétricos.

## 📁 Fonte dos Dados

- **Arquivo CSV**: `br_anatel_telefonia_movel_ddd.csv`
- **Origem**: ANATEL - Agência Nacional de Telecomunicações

## 🧰 Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- SciPy (Shapiro-Wilk e Mann-Whitney U)

## 📈 Etapas da Análise

### 1. Análise Descritiva
- Cálculo de estatísticas gerais dos acessos.
- Total de acessos por tipo de tecnologia (2G, 3G, 4G).
- Gráfico de barras com comparação por tipo de sinal e tecnologia.

### 2. Análise Inferencial
- Teste de normalidade (Shapiro-Wilk).
- Teste de Mann-Whitney U para comparar acessos entre:
  - 2G vs 3G
  - 3G vs 4G
- Visualização das distribuições com boxplots (sem outliers).

## 🔎 Principais Resultados

- As distribuições de acessos **não seguem normalidade** (p < 0.05).
- Há **diferença estatisticamente significativa** entre os grupos 2G vs 3G e 3G vs 4G.
- O volume de acessos varia significativamente entre as tecnologias analisadas.

## 📌 Conclusão

O estudo evidencia mudanças relevantes no comportamento de uso das tecnologias móveis. A análise serve como base para tomada de decisão por operadoras, reguladores e planejadores de rede.
