# challenge3-data-science-TelecomX_parte2
📊 Challenge 3: Modelagem Preditiva de Evasão de Clientes - Telecom X (Parte 2)

📄 Descrição do Projeto
Este é o Challenge 3 da análise de evasão de clientes da Telecom X. Após a análise exploratória realizada na primeira parte, o objetivo agora é desenvolver modelos preditivos capazes de identificar quais clientes têm maior probabilidade de cancelar seus serviços. Através da construção de modelos de Machine Learning e da aplicação de técnicas avançadas de balanceamento de classes e avaliação de desempenho, buscamos ajudar a empresa a antecipar o problema da evasão, permitindo a criação de estratégias de retenção mais eficazes.
A modelagem será realizada utilizando os algoritmos mais populares de classificação, como Regressão Logística, Random Forest e XGBoost. Além disso, será aplicada a técnica de SMOTE para balanceamento das classes desbalanceadas e avaliação da importância das variáveis.

## ✅ Funcionalidades

### Carregamento e Preparação de Dados:
- Leitura dos dados em formato **CSV**.
- Pré-processamento para remover variáveis irrelevantes, tratamento de valores nulos e codificação de variáveis categóricas.

### Balanceamento de Classes:
- Aplicação do **SMOTE** para gerar exemplos sintéticos da classe minoritária (**churn = 1**) e balancear o conjunto de dados.

### Construção de Modelos Preditivos:
- Criação de modelos de **Regressão Logística**, **Random Forest** e **XGBoost** para prever a evasão de clientes.
- Treinamento dos modelos e avaliação utilizando dados de treino e teste.

### Avaliação de Desempenho:
- Avaliação dos modelos utilizando **Acurácia**, **Precisão**, **Recall**, **F1-score**, **Matriz de Confusão** e **AUC-ROC**.
- Comparação de desempenho entre os modelos para identificar o melhor modelo para o problema.

### Interpretação dos Resultados:
- Análise da **importância das variáveis** para entender quais características mais impactam a previsão do churn.
- Geração de recomendações estratégicas para ações de retenção com base nos resultados dos modelos.

## 🛠️ Tecnologias Utilizadas
- **Python 3**: Linguagem de programação utilizada para análise e modelagem.
- **Pandas**: Manipulação e preparação dos dados.
- **Scikit-learn**: Implementação dos modelos preditivos e avaliação de performance.
- **XGBoost**: Implementação de um modelo de boosting.
- **SMOTE (Imbalanced-learn)**: Técnica para balanceamento de classes.
- **Matplotlib & Seaborn**: Visualização de dados e resultados.
- **Jupyter Notebook / Google Colab**: Ambiente de desenvolvimento para análise interativa.

## ▶️ Como Executar o Projeto

### 📌 Pré-requisitos:
- **Python 3** instalado.
- Ambiente de desenvolvimento **Jupyter Notebook** ou **Google Colab**.

### Passo a Passo:

1. **Clone este repositório ou baixe os arquivos**:
    git clone https://github.com/janairacs/challenge3-data-science-TelecomX_parte2
   
## Instale as dependências:
Instale as bibliotecas necessárias utilizando:
    pip install pandas matplotlib seaborn scikit-learn xgboost imbalanced-learn
    
## Carregar os Dados:
O primeiro passo é carregar os dados a partir de um arquivo CSV ou de uma API.

## Pré-processamento dos Dados:
Normalização, codificação de variáveis categóricas e tratamento de dados ausentes.

## Balanceamento de Classes:
Aplique o SMOTE para balancear as classes do conjunto de dados.

## Construção dos Modelos:
Treine os modelos de Regressão Logística, Random Forest e XGBoost.

## Avaliação dos Modelos:
Avalie o desempenho de cada modelo com métricas como Acurácia, Precisão, Recall, F1-score e AUC-ROC.

## Interpretação dos Resultados:
Analise a importância das variáveis e extraia insights sobre os fatores que mais influenciam o churn.

## Geração do Relatório Final:
Baseado nas conclusões dos modelos e análise, gere um relatório detalhado com recomendações estratégicas.
