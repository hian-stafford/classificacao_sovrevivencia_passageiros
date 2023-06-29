# Classificação sobrevivência dos passageiros do Titanic

Este é um projeto de classificação que utiliza várias técnicas e modelos de Machine Learning para prever a sobrevivência dos passageiros a bordo do Titanic. O objetivo é explorar os dados disponíveis, realizar pré-processamento e engenharia de recursos, treinar vários modelos e avaliar o desempenho de cada um.

## Técnicas utilizadas:
- Informações de amostra;
- Agrupamento;
- Visualização de dados;
- Engenharia de recursos;
- Variáveis dummy (para transformar os dados em binários);
- Preenchimento de dados faltantes (utilizando a moda dos dados);
- Divisão dos dados em treinamento e teste (70% para treino, 30% para teste);
- Aprendizado de Máquina;
- Validação cruzada (para evitar expectativas excessivamente altas em relação aos modelos);
- Curvas ROC e AUC (para avaliar falsos positivos e falsos negativos).

## Modelos de Aprendizado de Máquina utilizados:
Neste projeto, foram testados vários modelos de classificação para identificar os mais adequados para o problema em questão:
- Logistic Regression
- Extra Trees Classifier
- Gradient Boosting Classifier
- AdaBoost Classifier
- SVC
- KNeighbors Classifier
- Gaussian NB
- Perceptron
- Linear SVC
- SGD Classifier
- Decision Tree Classifier
- Random Forest Classifier

## Ensembling:
Foram exploradas técnicas de ensemble para combinar as previsões dos modelos individuais e melhorar o desempenho geral do sistema.

### Voting Classifier:
Um Voting Classifier foi implementado, onde os votos de vários modelos são combinados para tomar a decisão final.

### Bagging:
- KNN (K-Nearest Neighbors)
- Decision Tree

### Boosting:
- Ada Boost
- Gradient Boosting Classifier

## Feature Importance:
A análise de importância de recursos foi realizada para identificar as variáveis mais relevantes para a previsão da sobrevivência dos passageiros.

Esse projeto serve como um exemplo de como abordar um problema de classificação usando diferentes técnicas e modelos de Machine Learning, além de destacar a importância da pré-processamento dos dados e avaliação adequada do desempenho do modelo.
