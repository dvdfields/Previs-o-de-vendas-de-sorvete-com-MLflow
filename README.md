# 🍦 Gelato Mágico — Previsão de Vendas com Azure Machine Learning

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![Azure Machine Learning](https://img.shields.io/badge/Azure%20ML-MLOps%20Pipeline-0078D4?logo=microsoftazure)
![Status](https://img.shields.io/badge/Status-Em%20Produção-success)
![License](https://img.shields.io/badge/License-MIT-green)
![Model](https://img.shields.io/badge/Model-VotingEnsemble%20(XGBoost)-orange)

---

## 📖 Sobre o Projeto

A **Gelato Mágico** é uma sorveteria cuja demanda diária é fortemente influenciada pela temperatura.  
Este projeto de **Machine Learning** e **MLOps em nuvem (Azure ML)** foi desenvolvido para prever as **vendas diárias de sorvetes** com base na temperatura, otimizando o **planejamento de produção e estoque**.

---

## 🎯 Objetivos

- 🧠 Desenvolver um modelo de **Regressão** para prever vendas com base na temperatura.  
- ⚙️ Comparar duas abordagens de MLOps no **Azure ML**:
  - **Designer (low-code):** criação visual de pipeline de regressão.  
  - **Automated ML (AutoML):** otimização automática de modelo, hiperparâmetros e features.  
- 🗂️ Gerenciar o modelo via **Azure ML Registry / MLflow**.  
- ☁️ Implantar o modelo vencedor em um **Real-Time Endpoint** para previsões instantâneas.  

---

## 🛠️ Tecnologias e Ferramentas

| Categoria | Ferramenta | Uso no Projeto |
|------------|-------------|----------------|
| **Plataforma MLOps** | Azure Machine Learning | Orquestração de pipelines, registro e deployment |
| **Modelagem 1** | Azure ML Designer | Criação visual (drag-and-drop) do pipeline de Regressão Linear |
| **Modelagem 2** | Automated ML (AutoML) | Otimização automática de algoritmos e hiperparâmetros |
| **Modelo Final** | VotingEnsemble (7 XGBRegressor) | Ensemble vencedor |
| **Rastreamento** | MLflow | Registro e monitoramento de modelos e métricas |

---

## 📂 Estrutura do Repositório


