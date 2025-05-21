# 🧠 Predição de Câncer Pulmonar com Machine Learning

Este projeto foi desenvolvido como parte de um desafio prático de Inteligência Artificial para a FORMAÇÃO 4.0 da FACULDADE SENAC, com foco na criação de um modelo de classificação para prever a presença de doença pulmonar com base em dados de estilo de vida e saúde.

---

## 📌 Objetivo

Desenvolver um sistema inteligente capaz de prever o risco de câncer de pulmão a partir de variáveis clínicas e comportamentais, utilizando técnicas de **Aprendizado de Máquina**.

---

## 📊 Dados Utilizados

- **Fonte**: [Lung Cancer Prediction Dataset](https://www.kaggle.com/datasets/shantanugarg274/lung-cancer-prediction-dataset?classId=eb4da7ef-4f14-4865-93f3-0aecb57e40e7&assignmentId=09f00e74-a3aa-4b11-b4ac-aa671507e086&submissionId=af24a853-5779-f08b-5a4a-7bc27734a68b) 
- **Atributos**:
  - `FUMANTE`
  - `PROBLEMAS_RESPIRATORIOS`
  - `EXPOSICAO_POLUICAO`
  - `SISTEMA_IMUNE_FRACO`
  - `CONSUMO_ALCOOL`
  - `HISTORICO_FAMILIAR`
  - `FAMILIA_FUMANTE`
  - `NIVEL_ENERGIA`
  - `ESTRESSE`
  - `IDADE`
- **Variável alvo**: `DOENCA_PULMONAR` (0 = Não, 1 = Sim)

---

## 🧪 Desempenho dos Modelos

| Modelo                 | Acurácia Média | Desvio Padrão |
|------------------------|----------------|---------------|
| Regressão Logística    | ~0.7988        | ~0.0093       |
| Floresta Aleatória     | ~0.7945        | ~0.0101       |

> O modelo de melhor desempenho foi salvo como `modelo_melhor.pkl`.

---

## 💻 Interface Interativa

O projeto inclui uma interface feita com **Gradio**, onde o usuário pode inserir dados e obter a predição do modelo:

