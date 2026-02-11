# Classificação de Inadimplência em Crédito

Projeto desenvolvido como parte do **Trabalho 1 da disciplina Introdução ao Aprendizado de Máquina (UFRJ)**, no período 2025.2.  
O trabalho foi conduzido no formato de **competição no Kaggle**, com foco na construção de um modelo de classificação para apoio à decisão de concessão de crédito.

## Objetivo
Desenvolver um classificador supervisionado capaz de prever se um solicitante de crédito será um **bom pagador** ou **inadimplente**, com base em dados históricos de solicitações de crédito previamente aprovadas.

O desempenho do modelo é avaliado pela **acurácia** obtida em um conjunto de teste com rótulos ocultos, disponibilizado pela plataforma Kaggle.

## Conjunto de Dados
- **Treinamento:** aproximadamente 20.000 solicitações de crédito contendo atributos cadastrais e financeiros, acompanhados do desfecho (adimplente ou inadimplente).
- **Teste:** aproximadamente 5.000 solicitações de crédito, sem rótulos visíveis, utilizadas exclusivamente para avaliação no Kaggle.

A descrição completa dos atributos está disponível na aba *Data* da competição.

## Metodologia
O pipeline do projeto contempla as seguintes etapas:
1. Análise exploratória dos dados
2. Pré-processamento:
   - Tratamento de valores ausentes  
   - Codificação de variáveis categóricas  
   - Normalização/padronização de atributos numéricos
3. Seleção de atributos com maior potencial preditivo
4. Treinamento e comparação de modelos de classificação
5. Validação cruzada para avaliação de desempenho
6. Ajuste de hiperparâmetros
7. Geração de previsões e submissão ao Kaggle

## Avaliação
- **Métrica:** Acurácia
- Avaliação realizada automaticamente pelo Kaggle com base no conjunto de teste com gabarito oculto.

## Estrutura do Repositório
.
├── Data/                     # Conjunto de dados fornecido
├── classif_inadp_credito.ipynb  # Código principal do projeto
├── submission_trab1.csv      # Arquivo de submissão no Kaggle
├── Relatorio_Trabalho1.pdf   # Relatório detalhado do trabalho
└── README.md


## Relatório
O relatório detalha todo o desenvolvimento do trabalho, incluindo pré-processamento, modelos testados, técnicas de validação, ajustes de hiperparâmetros e resultados obtidos.
