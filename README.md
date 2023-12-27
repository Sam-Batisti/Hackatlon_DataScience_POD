# Hackatlon_DataScience_POD

# Projeto: Modelo de Risco de Crédito

## Introdução

O projeto Modelo de Previsão de Risco de Crédito visa desenvolver um modelo preditivo para avaliar o risco de crédito de indivíduos, utilizando dados históricos fornecidos pela Home Credit. O objetivo é ajudar a instituição financeira a tomar decisões informadas sobre a concessão de crédito.

## Estrutura do Projeto

```plaintext
|-- data/                   # Dados brutos e processados
|-- notebooks/              # Notebooks Jupyter com análises e modelagem
|-- src/                    # Códigos-fonte
|-- results/                # Resultados e modelos treinados
|-- README.md               # Documentação principal
|-- requirements.txt        # Dependências do projeto
|-- main.py                 # Script principal


Instruções para Execução
Pré-processamento de Dados:

Execute o notebook 01_preprocessamento_dados.ipynb para realizar o pré-processamento dos dados.
Este notebook trata valores ausentes, realiza encoding de variáveis categóricas, etc.
Análise Exploratória de Dados:

Utilize o notebook 02_analise_exploratoria.ipynb para explorar visualmente os dados.
Identifique padrões, tendências e correlações.
Modelagem:

Execute o notebook 03_modelagem.ipynb para treinar e avaliar o modelo de risco de crédito.
Experimente diferentes algoritmos e otimize hiperparâmetros.
Documentação do Modelo
Arquitetura do Modelo
O modelo de risco de crédito utiliza um algoritmo de Machine Learning baseado em árvore de decisão.

Treinamento do Modelo
Hiperparâmetros:

Critério: Gini
Profundidade máxima: 10
Número de estimadores: 100
Avaliação:

AUC-ROC: 0.85
Precision: 0.78
Recall: 0.92
Resultados e Visualizações
O gráfico de Curva ROC está disponível no diretório results/roc_curve.png.
Matriz de Confusão: results/matriz_confusao.txt.
Requisitos de Dados
Origem dos Dados:
Os dados foram fornecidos pela Home Credit e consistem em informações sobre clientes, transações e histórico de crédito.
Considerações de Segurança e Privacidade
O projeto adere a medidas rigorosas de segurança e privacidade para proteger informações sensíveis dos clientes.
FAQ
P: Como interpretar a Curva ROC?
R: A Curva ROC mostra a taxa de verdadeiros positivos em função da taxa de falsos positivos, ajudando a avaliar o desempenho do modelo.

P: Como contribuir para o projeto?
R: Siga as instruções no README.md para configurar o ambiente e execute os notebooks para análise e modelagem.
