# Credit Score Predict - Projeto EBAC

## Sobre o projeto
Este projeto consiste em uma análise e pré-processamento de dados para previsão de Score de Crédito, desenvolvido como atividade prática do curso de Ciência de Dados da EBAC. O objetivo é preparar e explorar uma base de dados bancária, aplicando técnicas de análise estatística, tratamento de dados e balanceamento de classes, visando a construção de modelos preditivos futuros.

## Objetivo
O principal objetivo é analisar e preparar uma base de dados de clientes bancários para prever o Score de Crédito, identificando padrões, relações e possíveis fatores que influenciam a pontuação de crédito dos clientes.

## Base de Dados
A base utilizada contém informações como:
- Idade (`Age`)
- Salário mensal (`Income`)
- Gênero (`Gender`)
- Escolaridade (`Education`)
- Estado civil (`Marital Status`)
- Número de filhos (`Number of Children`)
- Tipo de residência (`Home Ownership`)
- Score de crédito (`Credit Score`)

Os dados foram fornecidos em formato CSV, com variáveis numéricas e categóricas.

## Estrutura do projeto
- `M17_Projeto_Profissao_Cientista_de_Dados.ipynb`: Notebook principal com todo o fluxo de análise, pré-processamento, visualização e balanceamento dos dados.
- Arquivos CSV gerados para treino e teste após o balanceamento.

## Resultados
- Análise exploratória detalhada das variáveis.
- Tratamento de dados faltantes e inconsistências.
- Codificação de variáveis categóricas.
- Balanceamento das classes do Score de Crédito usando SMOTE.
- Geração de conjuntos de treino e teste prontos para modelagem.

## Tecnologias e Bibliotecas
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- scikit-learn
- imbalanced-learn

## Insights
- Clientes com casa própria, maior idade e renda tendem a apresentar Score de Crédito mais alto.
- Estado civil e escolaridade também influenciam significativamente o Score.
- A base apresenta desbalanceamento nas classes de Score, corrigido com técnicas de oversampling.

## Como rodar
1. Clone o repositório e acesse a pasta do projeto.
2. Certifique-se de ter um ambiente Python 3 com as bibliotecas necessárias instaladas.
3. Abra o notebook `M17_Projeto_Profissao_Cientista_de_Dados.ipynb` em seu Jupyter ou VSCode.
4. Execute as células sequencialmente para reproduzir toda a análise.

## Contribuições
Sugestões, melhorias e novas ideias são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

## Autoria
Projeto desenvolvido por Ana Paula Dias, como parte da formação em Ciência de Dados pela EBAC.
