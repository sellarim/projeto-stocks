# 📈 Análise de Dados Financeiros - B3 & Python

Automação de análise financeira em Python. O script coleta dados da B3 via API, calcula indicadores técnicos (RSI, Bollinger, Médias Móveis) e gera gráficos de rentabilidade comparada ao Ibovespa. Foco em DataViz e automação.

## 📋 Sobre o Projeto

O objetivo desta atividade foi aplicar conhecimentos de manipulação de dados e visualização financeira (`DataViz`) para criar um dashboard de análise técnica. O estudo explora o comportamento do ativo **ITSA4 (Itaúsa)**, aplicando conceitos de Médias Móveis, Bandas de Bollinger e Índice de Força Relativa (RSI), além de compará-lo com o índice **IBOVESPA**.

### 🛠 Tecnologias Utilizadas

* ![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
* ![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas)
* ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=for-the-badge)
* ![yFinance](https://img.shields.io/badge/yFinance-API-green?style=for-the-badge)
* **Google Colab** (Ambiente de desenvolvimento)

## 📊 Análises e Visualizações

Abaixo estão as etapas visuais desenvolvidas no projeto:

### 1. Gráfico Simples (Histórico de Preços)
Visualização inicial da série temporal de fechamento do ativo nos últimos anos.

<img width="1189" height="590" alt="download (2)" src="https://github.com/user-attachments/assets/42af17d0-bfa3-4209-b870-88428ad38cff" />


### 2. Análise Técnica Avançada (Bollinger + RSI)
Dashboard combinando Preço, Médias Móveis (20/200), Bandas de Bollinger e o oscilador RSI para identificar zonas de compra e venda.

<img width="1389" height="989" alt="download (3)" src="https://github.com/user-attachments/assets/04443ef3-8a2e-4e3c-881f-fee2090d137f" />


### 3. Benchmark (Comparativo de Rentabilidade)
Gráfico normalizado (Base 100) comparando a performance percentual da ITSA4 contra o índice IBOVESPA.

<img width="1189" height="590" alt="download (4)" src="https://github.com/user-attachments/assets/e909aac7-6b94-4fe3-bd68-658c9d9a13d9" />


---

## 💡 Principais Insights

Com base na análise realizada via script Python, observou-se que:

* **Volatilidade:** A utilização das **Bandas de Bollinger** permitiu identificar visualmente os momentos de alta volatilidade e possíveis pontos de exaustão de preço (quando tocam as bandas).
* **Tendência:** O cruzamento das médias móveis e a posição do preço em relação à média de 200 dias serviram como indicador claro da tendência macro do ativo.
* **Performance Relativa:** Através da normalização dos dados (Gráfico 3), foi possível mensurar o "Alpha" do ativo, ou seja, o quanto ele rendeu acima ou abaixo da média de mercado (Ibovespa) no período estipulado.

## 🚀 Acesso ao Projeto

Você pode visualizar e executar o código completo diretamente no Google Colab através do link abaixo:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fPWY04liGKWPn3Sw0X18DiDhblITXjkG?usp=sharing)

## ✒️ Autor

**Leonardo Miralles**
* **Área:** Dados / Finanças

---
*Projeto desenvolvido para fins de portfólio e estudos - 2025.*
