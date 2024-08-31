# Previsão de Casos de Diabetes com Machine Learning

Este projeto utiliza Machine Learning para prever a presença de diabetes com base em um conjunto de dados médicos. Utilizando técnicas de aprendizado supervisionado, como Gradient Boosting, o objetivo é fornecer uma ferramenta útil para identificar possíveis casos de diabetes.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada.
- **Pandas**: Manipulação e análise de dados.
- **Scikit-learn**: Modelagem e treinamento de algoritmos de aprendizado de máquina.
- **lightgbm**: Biblioteca que oferece o modelo LGBMClassifier para trainamento utilizando Gradient Boosting
- **Matplotlib**: Visualização de dados.
- **NumPy**: Manipulação eficiente de arrays e operações matemáticas.

## Estrutura do Projeto

- **`data/`**: Diretório contendo o conjunto de dados utilizado para treinamento e testes.
- **`notebooks/`**: Jupyter Notebooks com a análise exploratória dos dados.
- **`src/`**: Scripts e funções principais treinamento de modelos e avaliação.
- **`requirements`**: Arquivo contendo as dependências do projeto.

## Descrição dos Dados

O conjunto de dados contém informações médicas sobre pacientes, incluindo:

- **gender**: Gênero do paciente (0 para feminino, 1 para masculino
- **age**: Idade do paciente
- **hypertension**: Histórico de hipertensão (0 para não, 1 para sim)
- **heart_disease**: Histórico de doenças cardíacas (0 para não, 1 para sim)
- **smoking_history**: Histórico de tabagismo (0 para nunca, 1 para atual, 2 para ex-fumante)
- **bmi**: Índice de massa corporal
- **HbA1c_level**: Nível de HbA1c (Hemoglobina glicada)
- **blood_glucose_level**: Nível de glicose no sangue
- **diabetes**: Diagnóstico de diabetes (0 para não, 1 para sim)

## Pré-processamento de Dados

O pré-processamento inclui:

- **Tratamento de valores ausentes**: Substituição ou remoção de valores ausentes.
- **Codificação de variáveis categóricas**: Conversão de variáveis categóricas em valores numéricos.
- **Normalização dos dados**: Escalonamento das características para melhorar o desempenho dos modelos.

## Avaliação do Modelo


A avaliação do modelo é realizada usando:

- **Matriz de Confusão**: Para visualizar o desempenho do modelo na classificação de casos positivos e negativos.

## Resultados

Os resultados mostram a eficácia de **90%** do modelo na previsão de diabetes, com uma análise detalhada das previsões e a comparação com os dados reais. A precisão e outras métricas são avaliadas para garantir a robustez do modelo.

## Como Usar

1. **Clone o Repositório**

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
