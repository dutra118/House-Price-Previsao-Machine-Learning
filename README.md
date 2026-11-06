# House-Price-Previsao-Machine-Learning
Projeto desenvolvido durante o curso de Data Science da IBM, com o objetivo de analisar características de imóveis residenciais e desenvolver modelos de Machine Learning capazes de prever seus preços de mercado.

A análise utilizou uma base de dados imobiliários contendo informações como área construída, número de quartos, banheiros, andares e outras características dos imóveis.

## Etapas do projeto

- **Análise exploratória:** exploração das variáveis e identificação de características relacionadas aos preços dos imóveis.
- **Preparação dos dados:** seleção e organização das variáveis utilizadas nos modelos.
- **Regressão Linear:** desenvolvimento de um modelo inicial para previsão dos preços.
- **Regressão Polinomial:** aplicação de transformações polinomiais para avaliar relações não lineares entre as variáveis.
- **Ridge Regression:** aplicação de regularização para avaliar o desempenho dos modelos e reduzir o risco de sobreajuste.
- **Avaliação dos modelos:** utilização das métricas R² e MSE (Erro Quadrático Médio) para avaliar os resultados.

## Resultados

Na avaliação final, foram obtidos os seguintes resultados:

| Métrica | Resultado |
|---|---:|
| R² – Treinamento | 0,91 |
| R² – Teste | 0,68 |
| MSE – Teste | 28.500 |

Os resultados demonstraram que o modelo apresentou melhor ajuste aos dados de treinamento do que aos dados de teste, indicando espaço para melhorias na capacidade de generalização das previsões.

## Tecnologias e ferramentas

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Objetivo do aprendizado

Aplicar conceitos de análise de dados e Machine Learning na construção e avaliação de modelos preditivos, desenvolvendo conhecimentos em regressão, preparação de dados e avaliação de desempenho.
