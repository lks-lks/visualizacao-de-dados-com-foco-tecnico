# Visualização de Dados com Foco Técnico

Este projeto tem como objetivo simular um cenário de monitoramento de sensores industriais e aplicar técnicas de visualização de dados para análise técnica dos parâmetros coletados.

## Objetivo

Demonstrar visualmente o comportamento de variáveis técnicas como temperatura, pressão e vibração, a partir de dados sintéticos gerados com base em distribuições normais, imitando sensores reais.

## Dados

Os dados são gerados artificialmente com as seguintes características:

- 1000 observações
- Leituras a cada 1 minuto
- Variáveis: temperatura (°C), pressão (bar), vibração (mm/s)
- Inclusão de metadado de operador técnico (nome fictício)

## Etapas do projeto

1. Geração de dados sintéticos com `random`, `numpy` e `Faker`
2. Estatísticas descritivas básicas
3. Análise temporal das variáveis
4. Correlação entre sensores
5. Distribuição estatística das leituras
6. Comparação entre operadores

## Tecnologias utilizadas

- Python 3
- Pandas
- Numpy
- Faker
- Matplotlib
- Seaborn
