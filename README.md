# 📈 Regressão Linear com o dataset `mt_cars` — Análise Estatística com Python

Este repositório contém uma análise prática de **Regressão Linear Simples e Múltipla** aplicada ao dataset `mt_cars`, utilizando bibliotecas populares do ecossistema Python para ciência de dados.

---

## 📌 Objetivo

Demonstrar como construir um modelo de regressão linear utilizando:
- Análise exploratória dos dados
- Estudo de correlação entre variáveis
- Ajuste do modelo com `statsmodels`
- Interpretação dos coeficientes
- Visualização gráfica da reta de regressão

---

## 🛠️ Tecnologias e bibliotecas utilizadas

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- scipy

---

## 📊 Etapas do projeto

### 1. **Importação dos dados**
Leitura do dataset `mt_cars.csv` com `pandas`.

### 2. **Limpeza e preparação**
Remoção de colunas desnecessárias e análise inicial da estrutura da base.

### 3. **Análise exploratória**
- Uso de `.describe()` e `.info()`
- Gráficos com `seaborn` e `matplotlib`
- Heatmap de correlação para identificar variáveis com forte relação linear

### 4. **Modelagem com `statsmodels`**
- Construção do modelo de regressão linear
- Exibição do resumo estatístico (coeficientes, p-valores, R², etc.)
- Interpretação do impacto das variáveis independentes sobre a dependente

### 5. **Visualização da regressão**
Gráfico da reta de regressão sobre os dados, mostrando como o modelo se ajusta.

---

## 📈 Exemplo de gráfico gerado
🔥 Heatmap de Correlação
Visualiza a correlação entre todas as variáveis
Cores ajudam a identificar relações fortes positivas ou negativas

📊 Scatterplots múltiplos
Compara mpg (milhas por galão) com outras variáveis
Usado para identificar relações lineares visuais antes da regressão

📉 Histograma dos resíduos
Verifica se os resíduos estão distribuídos normalmente (um dos pressupostos da regressão)

---

## 📁 Arquivos

- `LinearRegression.ipynb`: Notebook com todo o processo de análise e modelagem
- `mt_cars.csv`: Dataset utilizado (você pode encontrar facilmente online ou gerar um mock se necessário)

---

## 💡 Conclusões

Este projeto é uma base sólida para quem está iniciando com **estatística aplicada à ciência de dados**. Com ele, você aprende na prática como funciona uma regressão linear e como interpretar os seus resultados.

---

## 👨‍💻 Autor

Projeto feito como parte do processo de aprendizado contínuo em Data Science e Machine Learning.  
Conecte-se comigo no https://www.linkedin.com/in/leonardomdev/ e acompanhe os próximos projetos!

---

## 📎 Licença

Este repositório é de uso educacional e livre para estudo e modificação.

