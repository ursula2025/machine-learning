# Projeto de Machine Learning: Previsão de Produtividade

## Descrição do Projeto

Este repositório contém um projeto completo de Machine Learning, partindo de uma Análise Exploratória de Dados (AED) para investigar a relação entre hábitos digitais e a produtividade. O objetivo final é construir e avaliar modelos de regressão capazes de prever a produtividade real de um indivíduo com base nos dados fornecidos, partindo da questão inicial sobre a discrepância entre a produtividade real e a autopercebida.

## O Conjunto de Dados

Foi utilizado o dataset público "Social Media vs Productivity" do Kaggle, que contém 19 atributos sobre os hábitos e o bem-estar de 30.000 indivíduos.

## Resumo da Metodologia

A análise partiu de uma investigação exploratória que revelou uma forte correlação entre a **"Satisfação Trabalho-Vida"** e a produtividade. Com base nesse e em outros insights, os dados foram submetidos a um rigoroso pré-processamento, incluindo tratamento de outliers, imputação de valores ausentes, codificação de variáveis categóricas e padronização. Em seguida, múltiplos modelos de regressão (`Regressão Linear`, `Random Forest` e `XGBoost`) foram treinados e comparados. Por fim, os melhores modelos foram otimizados com `RandomizedSearchCV` para encontrar a configuração de máxima performance.

##  Principais Descobertas e Resultados

* **Insight da Análise:** A **"Satisfação Trabalho-Vida"** demonstrou ser o fator mais forte e positivamente correlacionado com a produtividade, superando variáveis como tempo de tela ou nível de stress.

* **Performance do Modelo Campeão:** O modelo final, um **XGBoost Regressor otimizado**, alcançou um excelente **R² de 0.9288** no conjunto de teste, explicando quase 93% da variabilidade da produtividade real, com um erro médio de apenas 0.5 pontos.

* **Principal Preditordo Modelo:** A análise do modelo campeão revelou que a `PONT_PRODUT_AUTOAVALIADA` foi, de longe, a variável mais importante para suas previsões, servindo como uma excelente aproximação para a produtividade real.


* **Ursula Machado Weinstein**
* GitHub: https://github.com/ursula2025/machine-learning
