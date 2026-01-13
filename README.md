# IAA_Projeto_Final

# Análise e Previsão de Consumo Energético (CPE)

Projeto desenvolvido no âmbito da unidade curricular **Inteligência Artificial Aplicada**, com o objetivo de analisar e prever padrões de consumo energético em edifícios, utilizando dados reais associados a diferentes **Códigos de Ponto de Entrega (CPE)**.

---

## Objetivos

- Analisar padrões de consumo energético
- Identificar perfis de consumo através de **clustering**
- Prever consumo energético usando:
  - Modelos de séries temporais (ARIMA)
  - Modelos supervisionados baseados em *feature engineering*
- Comparar modelos com abordagens **baseline**

---
## Conteúdo do Repositório
**├── IAA_LN4_Projeto.ipynb # Notebook com todo o desenvolvimento** 

**├── IAA_Relatório.docx # Relatório final**

**├── README.md # Descrição do p rojeto**

---

## Metodologia (Resumo)

- **Data Understanding:** análise exploratória, séries temporais e heatmaps horário × dia da semana  
- **Data Preparation:** criação de variáveis agregadas por CPE (médias, máximos, percentis, variabilidade, etc.)
- **Modeling:**
  - K-Means + PCA (clustering)
  - ARIMA (previsão temporal)
  - Random Forest (aprendizagem supervisionada)
- **Evaluation:** comparação com baselines e análise do impacto da normalização

---

## Tecnologias

Python · Pandas · NumPy · Scikit-learn · Statsmodels · Matplotlib · Jupyter Notebook

---

## Autores

- **Josué da Glória** – nº 134449  
- **Ricardo Ourelo** – nº 120141  
