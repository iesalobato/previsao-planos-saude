# Previsão de Preços de Planos de Saúde com Machine Learning

Este projeto tem como objetivo aplicar técnicas de Machine Learning para prever os preços de planos de saúde com base em dados demográficos e de estilo de vida, como idade, índice de massa corporal (IMC), tabagismo, entre outros.

O trabalho foi desenvolvido como parte de uma atividade da pós-graduação em Inteligência Artificial da FIAP, envolvendo as etapas de exploração dos dados, análise de correlação, pré-processamento, testes com diferentes modelos de regressão e avaliação de desempenho.

## Modelos Utilizados

- Regressão Linear (`LinearRegression`)
- Árvore de Decisão (`DecisionTreeRegressor`)
- Floresta Aleatória (`RandomForestRegressor`)
- Gradient Boosting (`GradientBoostingRegressor`)
- HistGradientBoosting (`HistGradientBoostingRegressor`)
- K-Nearest Neighbors (`KNeighborsRegressor`)

## Etapas do Projeto

1. Análise de correlação (ex: IMC vs. Charges)
2. Análise exploratória dos dados
3. Tratamento e preparação do dataset
4. Separação em treino e teste
5. Treinamento de diferentes modelos
6. Avaliação de desempenho (MSE, R², etc.)

## Observações

- O dataset utilizado não possui dados nulos ou duplicados.
- Foi feita uma análise adicional segmentando a correlação entre IMC e Charges por fumantes e não fumantes.
- A escolha dos modelos buscou diversidade e comparação de abordagens lineares, baseadas em árvore, vizinhança e redes neurais.

## Requisitos

- Python 3.8+
- Bibliotecas:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

## Contribuição

Este projeto foi desenvolvido em equipe como parte da disciplina de Machine Learning na pós-graduação em Inteligência Artificial da FIAP. Feedbacks e sugestões são bem-vindos!


