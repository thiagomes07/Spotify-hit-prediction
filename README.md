# Spotify Hit Prediction 🎶

Este projeto foi desenvolvido para o **Kaggle Challenge** com o objetivo de **prever o próximo hit** do Spotify, utilizando modelos de machine learning para alcançar a melhor acurácia possível. O desafio consiste em prever se uma música será um *hit*, com base em diversas características musicais e metadados fornecidos.

## 📋 Descrição do Projeto

A indústria musical é altamente competitiva, e prever o sucesso de uma música pode fornecer vantagens significativas para artistas, gravadoras e plataformas de *streaming*. Utilizando um conjunto de dados do Spotify contendo informações detalhadas sobre músicas, como características acústicas (*danceability*, *energy*, *loudness*, etc.), o objetivo deste projeto é construir modelos preditivos capazes de identificar se uma música tem potencial para se tornar um *hit*.

### 🚀 Tecnologias Utilizadas

- **Python** para o desenvolvimento dos scripts e análise de dados.
- **Scikit-learn** para a construção e validação dos modelos de machine learning.
- **Pandas & NumPy** para manipulação e análise dos dados.
- **Matplotlib & Seaborn** para visualização de dados e exploração inicial.
- **Joblib** para salvamento dos modelos treinados.
- **Jupyter Notebook** para desenvolvimento interativo.
- **Kaggle API** para obtenção dos dados e envio das previsões.

## 🔍 Estrutura do Repositório

```
Spotify-hit-prediction/
│
├── README.md                      # Documentação do projeto
├── best_model.ipynb               # Notebook Jupyter
├── data/                          # Conjuntos de dados .csv
├── models/                        # Modelos treinados e salvos
└── submissions/                   # Arquivos .csv para as submissões do desafio
```

### 📊 Conjunto de Dados

O conjunto de dados utilizado contém informações sobre milhares de músicas disponíveis no Spotify, como:

- **Danceability**: O quão adequada é uma música para dançar.
- **Energy**: Nível de intensidade e atividade da música.
- **Key**: A tonalidade da música.
- **Liveness**: Indica a presença de um público ao vivo.
- **Loudness**: Volume médio da música.
- **Speechiness**: A presença de falas na faixa.
- **Tempo**: A velocidade da música.
- **Popularity**: Nível de popularidade no Spotify.
- **Duration**: Duração da música em milissegundos.

### 📈 Modelos de Machine Learning Utilizados

- **Gradient Boosting**
- **Random Forest**
- **Support Vector Machine (SVM)**
- **Logistic Regression**
  
Cada um desses modelos foi treinado e avaliado com base em métricas de desempenho, como **acurácia**, **precisão**, **recall** e **F1-score**.


### 🔮 Resultados

O modelo de **Gradient Boosting** apresentou os melhores resultados, com uma acurácia de cerca de **85%**, superando outros modelos. Os hiperparâmetros foram otimizados utilizando **RandomizedSearchCV** para maximizar o desempenho.

### 📚 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir **issues** ou enviar **pull requests**.