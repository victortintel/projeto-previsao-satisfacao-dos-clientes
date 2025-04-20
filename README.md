# 📊 Projeto: Previsão de Satisfação de Clientes com Machine Learning  

**Autor:** Victor Tintel  

## 🎯 Objetivo  
Construir um modelo preditivo para estimar o nível de satisfação de clientes, aplicando técnicas de **Data Science** e **ML** desde a coleta até a validação do modelo.  

## 🔍 Métodos Utilizados  
- **Pré-processamento:**  
  - Tratamento de dados faltantes e outliers.  
  - Normalização (MinMaxScaler/StandardScaler).  
- **EDA:** Análise de correlação, distribuição de variáveis e visualizações.  
- **Modelos Testados:**  
  - Regressão Logística.  
  - Random Forest.  
  - XGBoost (com otimização de hiperparâmetros).  
- **Avaliação:** Métricas como AUC-ROC, matriz de confusão e cross-validation.  

## 🛠️ Tecnologias  
- Python 3.  
- Bibliotecas: Pandas, Scikit-learn, NumPy, Matplotlib/Seaborn.  
- Ambiente: Jupyter Notebook.  

## 📂 Estrutura do Projeto  
```plaintext
/projeto-satisfacao-clientes  
├── data/               # Dados brutos e processados  
├── notebooks/          # Jupyter Notebook com análise e modelagem  
├── models/             # Modelos treinados (pickle/joblib)  
└── README.md  
