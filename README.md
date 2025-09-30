# Trabalhos de Machine Learning - Classificação e Regressão

Este repositório reúne dois projetos desenvolvidos em **Python no Google Colab**, aplicando técnicas de **aprendizado de máquina** para **classificação** e **regressão**.

---

## 📊 Projeto 1 - Classificação (Fetal Health Dataset)

- **Objetivo:** Classificar a saúde fetal em três categorias: **Normal (1), Suspeito (2), Patológico (3)**.  
- **Dataset:** [Fetal Health Classification (Kaggle)](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification)  
- **Etapas realizadas:**
  - Tratamento de valores ausentes e duplicados
  - Normalização com Z-score
  - Visualizações exploratórias (countplot, boxplots, pairplots)
  - Treinamento com modelos de classificação:
    - Random Forest (acurácia: **95,2%**)
    - Regressão Logística
    - KNN
  - Seleção de features mais importantes
  - Retreinamento do Random Forest com features selecionadas

---

## 🏠 Projeto 2 - Regressão (Boston Housing Dataset)

- **Objetivo:** Prever o valor médio das casas em Boston (variável **MEDV**).  
- **Dataset:** [Boston Housing (UCI)](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/housing.data)  
- **Etapas realizadas:**
  - Tratamento de valores ausentes e duplicados
  - Normalização com StandardScaler
  - Comparação de modelos de regressão:
    - Random Forest (R² = **88%**)
    - KNN
    - Regressão Linear
  - Seleção de features com importância > 0.01
  - Retreinamento do Random Forest com GridSearch

---

## 🚀 Tecnologias Utilizadas
- Python (Google Colab)
- Bibliotecas: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## 📚 Informações Acadêmicas:

**Matéria:** Mineração de Dados (Data Mining) - Fatec Franca  
**Alunos:**  
- Paula Cristina Abib Teixeira  
- Allison Rodrigues de Paula e Silva
