
# Análise de Dados e Modelagem Preditiva — PETR4

## Sobre o projeto

Este projeto foi desenvolvido no contexto da disciplina de Programação para Ciências de Dados, durante o Bacharelado em Ciência e Tecnologia.

O trabalho utiliza dados históricos da ação PETR4.SA para explorar padrões de comportamento do ativo e investigar a aplicação de modelos de Machine Learning na classificação da direção dos movimentos do mercado.

## Objetivos

- Realizar análise exploratória dos dados financeiros.
- Preparar e transformar os dados para modelagem.
- Desenvolver modelos de classificação.
- Avaliar o desempenho dos modelos utilizando métricas estatísticas.
- Investigar as limitações da previsão de movimentos do mercado financeiro.

## Tecnologias e ferramentas

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Streamlit

## Metodologia

O desenvolvimento foi organizado nas seguintes etapas:

1. Obtenção e preparação dos dados históricos.
2. Análise exploratória e visualização dos dados.
3. Engenharia de atributos.
4. Separação dos dados em conjuntos de treinamento e teste.
5. Treinamento dos modelos de Regressão Logística e XGBoost.
6. Avaliação e comparação dos resultados.

## Modelos utilizados

**Regressão Logística**

Modelo de classificação utilizado como abordagem inicial para investigar a direção dos movimentos do ativo.

**XGBoost**

Algoritmo de Machine Learning baseado em árvores de decisão, utilizado para comparar o desempenho preditivo.

## Resultados

Os modelos foram avaliados utilizando métricas de classificação.

- Acurácia da Regressão Logística: aproximadamente 52,99%.
- Acurácia do XGBoost: aproximadamente 50,44%.
- F1-score do XGBoost: aproximadamente 51,72%.

Os resultados indicam desempenho preditivo limitado, reforçando a dificuldade de prever movimentos de ativos financeiros exclusivamente com base nos atributos utilizados.

## Estrutura do repositório

- `notebook/`: notebook com o desenvolvimento da análise.
- `docs/`: relatório final do projeto.
- `images/`: gráficos e visualizações dos resultados.

## Considerações finais

O projeto proporcionou a aplicação prática de conceitos de ciência de dados, estatística e aprendizado de máquina em um contexto financeiro.

Além da construção dos modelos, a análise permitiu compreender a importância da preparação dos dados, da avaliação estatística e da interpretação crítica dos resultados.

## Autoria

Projeto acadêmico desenvolvido no Bacharelado em Ciência e Tecnologia — UNIFEI.
