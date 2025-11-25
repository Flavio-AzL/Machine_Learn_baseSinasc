# Previsão de Baixo Peso ao Nascer com Machine Learning (SINASC)

## Objetivo
Projeto desenvolvido para a disciplina de Inteligência Computacional (A2). O objetivo é utilizar algoritmos de Machine Learning (Random Forest) para prever o risco de baixo peso ao nascer (< 2.500g) baseando-se em dados do DATASUS (2020-2024).

## Sobre os Dados
A base utilizada foi extraída do Sistema de Informações sobre Nascidos Vivos (SINASC).
* **Fonte:** DATASUS (Ministério da Saúde).
* **Tratamento:** Limpeza de outliers, imputação de dados faltantes (Mediana/Moda) e seleção de features baseada em literatura médica.
* **Volume:** Aprox. 2.5 milhões de registros analisados.

## Modelo Utilizado
* **Algoritmo:** Random Forest Classifier.
* **Performance:** Recall de 60% para a classe de risco (Baixo Peso).

## Como Executar
1. Instale as dependências: `pip install -r requirements.txt`
2. Execute o notebook: `analise_sinasc.ipynb`

## 👥 Autores
* Flávio Vieira de Araújo
* Renan
* Rafel
* Marcelo